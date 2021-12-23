# Setting up a Chainflip Node

## Prepare an instance

Start a fresh Ubuntu server and run the following commands.

```bash
sudo apt-get update && sudo apt-get upgrade

sudo apt-get install \
    jq \
    ca-certificates \
    curl \
    gnupg \
    lsb-release

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
sudo groupadd docker
sudo usermod -aG docker $USER
sudo systemctl enable docker.service
sudo systemctl enable containerd.service
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
sudo reboot
```

## Prepare Chainflip

Login and run the following commands.

```bash
git clone https://github.com/CumpsD/chainflip-docker ~/chainflip
echo -n "YOUR_PRIVATE_ETH_KEY" > ~/chainflip/config/ethereum_key
```

## Run Chainflip

You are now ready! Run the following commands.

```bash
cd ~/chainflip
docker-compose up -d
```

## Save your keys

Save the following keys somewhere safe.

```bash
cat ~/chainflip/config/keys
cat ~/chainflip/config/node_key
cat ~/chainflip/config/signing_key
```

## Save your Validator Id

Save this Id for later usage. You will need it for staking.

```bash
jq -r ."ss58Address" ~/chainflip/config/keys
```

## View output

```bash
cd ~/chainflip
docker-compose logs -f
```

## Stake

At a certain point, the logs will show something like this:

```
chainflip-engine    | {"msg":"Initalising State Chain state at block `34816`; block hash: `0x8556858cc036c8d7f85801765087043662f2978aa31bf33c0dc993ebdb798ae0`","level":"INFO","ts":"2021-12-22T16:51:19.892853796+00:00","tag":"","component":"StateChainConnector"}
chainflip-engine    | thread 'main' panicked at 'Failed to connect to state chain: AccountId 4a21d305010112570ff0da53fab57b85d980849139109717bb24e6b28baf9a07 (5DjuSy9m...) doesn't exist on the state chain. Please ensure you have staked and can see your stake on chain.', engine/src/main.rs:44:14
chainflip-engine    | note: run with `RUST_BACKTRACE=1` environment variable to display a backtrace
```

Go to the [Staking App](https://not.yet/) and click [My Nodes](https://not.yet)

Click **+ Add a node** and stake your FLIP with the Validator Id you retrieved earlier.

Sign the transaction and wait until it is confirmed. The transaction will look something like this: [0x156a03a1c92dd5e0f1806d2c2605f11cc732a7a887765ad2a0b39e7cd5bdf384](https://rinkeby.etherscan.io/tx/0x156a03a1c92dd5e0f1806d2c2605f11cc732a7a887765ad2a0b39e7cd5bdf384)

At this point your node should appear on the [Staking App](https://not.yet/).

## Set Validator keys

Run the following command to set the keys that your Validator will use to produce blocks.

```bash
docker exec -it chainflip-node /chainflip/bin/chainflip-cli -c /chainflip/config/chainflip.toml rotate
```

This will rotate your key and output something like:

```
Connecting to state chain node at: `ws://chainflip-node:9944` and using private key located at: `/chainflip/config/signing_key`
Session key rotated at tx 0xa671c8ea4583e1b4c3eb136603285f1652a0836afe47e1397349a32ad711f711.
```

You can use this tx to look it up on the [Explorer App](https://not.yet).
