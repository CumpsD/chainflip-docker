# chainflip-docker

## TODO

* docker-compose up -d
* add ethereum-key input dialog
* check expose vs ports

## Running

```bash
docker-compose up
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
