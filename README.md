# chainflip-docker

## TODO

* publish images
* docker-compose up -d
* add engine and geth
* add ethereum-key input dialog
* check expose vs ports
* blocked connection to WebSockets server with untrusted host: Some("chainflip-node:9944")

## Running

```bash
docker-compose up
```

## Building

```bash
docker build -t chainflip-engine --target engine .
docker build -t chainflip-cli --target cli .
docker build -t chainflip-node --target node .
docker build -t chainflip-subkey --target subkey .
docker build -t chainflip-keys --target keys .
```
