# Health Checker

## Script

Create a Discord webhook and save the webhook url.

Save the following as `health.sh` using your webhook url and Validator Id.

Make it executable with `chmod +x health.sh`

Put it in a cron job and you can check the health of your node.

```bash
#!/bin/bash

WEBHOOK_URL="https://discord.com/api/webhooks/xxxxxxxx"
NODE_ID="xxxxxx"

NODE_STATUS=$(curl 'https://state-chain-cache.chainflip.io/graphql' -s \
  -H 'Accept-Encoding: gzip, deflate, br' \
  -H 'Content-Type: application/json' \
  -H 'Accept: application/json' \
  -H 'Connection: keep-alive' \
  -H 'DNT: 1' \
  -H 'Origin: https://state-chain-cache.chainflip.io' \
  --data-binary '{"query":"{query:auctions{bids {nodeId, nodeStatus}}}"}' \
  --compressed | jq -r --arg NODE_ID "$NODE_ID"  '.data.query[0].bids[] | select(.nodeId==$NODE_ID) | .nodeStatus')

if [ $NODE_STATUS = "active" ] || [ $NODE_STATUS = "backup" ] || [ $NODE_STATUS = "online" ]; then
  echo "Node Online"
else
  echo "Node Offline"
  curl \
    -H "Content-Type: application/json" \
    -d '{"username": "chainflip", "content": "Bad news...Chainflip Node '"$NODE_ID"' is offline!"}' \
    $WEBHOOK_URL
  systemctl restart chainflip-node
  systemctl restart chainflip-engine
fi
```

## Cron Job

An example to run the script every 10 minutes.

```
*/10 * * * * /home/ubuntu/chainflip/health.sh
```
