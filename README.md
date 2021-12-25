# chainflip-docker

## Running

⚠️⚠️ **Add `config/ethereum_key` first** ⚠️⚠️

```bash
docker-compose up -d
```

To view and backup your keys:

```bash
cat config/keys
cat config/node_key
cat config/signing_key
cat config/ethereum_key
```

## Firewall

The following ports should be opened on your firewall:

* 3000 TCP, used by Grafana
* 30303 TCP & UDP, used by Geth
* 30333 TCP & UDP, used by Chainflip Node

## Updating

```bash
docker-compose pull
docker-compose up -d --remove-orphans
docker image prune
```

## Building

### Testing Docker Compose

```bash
docker-compose -f docker-compose-dev.yml up
```

### Testing individual images

```bash
docker build -t chainflip-engine --target engine --build-arg CHAINFLIP_VERSION=0.1.0 .
docker build -t chainflip-cli --target cli --build-arg CHAINFLIP_VERSION=0.1.0 .
docker build -t chainflip-node --target node --build-arg CHAINFLIP_VERSION=0.1.0 .
docker build -t chainflip-subkey --target subkey --build-arg CHAINFLIP_VERSION=0.1.0 .
docker build -t chainflip-keys --target keys --build-arg CHAINFLIP_VERSION=0.1.0 .
```
