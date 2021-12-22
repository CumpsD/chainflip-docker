# Setting up a Chainflip Node

## Prepare an instance

Start a fresh Ubuntu server and run the following commands.

```bash
sudo apt-get update && sudo apt-get upgrade

sudo apt-get install \
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
git clone https://github.com/CumpsD/chainflip-docker chainflip
echo "YOUR_PRIVATE_ETH_KEY" > chainflip/config/ethereum_key
```

## Run Chainflip

You are now ready! Run the following commands.

```bash
cd chainflip
docker-compose up -d
```

## View output

```bash
docker-compose logs -f
```

## Stake

At a certain point, the logs will show something like this:

```
chainflip-engine    | {"msg":"Initalising State Chain state at block `34816`; block hash: `0x8556858cc036c8d7f85801765087043662f2978aa31bf33c0dc993ebdb798ae0`","level":"INFO","ts":"2021-12-22T16:51:19.892853796+00:00","tag":"","component":"StateChainConnector"}
chainflip-engine    | thread 'main' panicked at 'Failed to connect to state chain: AccountId 4a21d305010112570ff0da53fab57b85d980849139109717bb24e6b28baf9a07 (5DjuSy9m...) doesn't exist on the state chain. Please ensure you have staked and can see your stake on chain.', engine/src/main.rs:44:14
chainflip-engine    | note: run with `RUST_BACKTRACE=1` environment variable to display a backtrace
```
