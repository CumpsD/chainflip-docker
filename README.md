# chainflip-docker

## TODO

* expose geth ports
* add ethereum-key input dialog
* check expose vs ports
* Investigate `Thread 'tokio-runtime-worker' panicked at 'Storage root must match that calculated.', /usr/local/cargo/git/checkouts/substrate-a7ad12d678bd31ac/e563465/frame/executive/src/lib.rs:472`

## Running

⚠️⚠️ **Add `config/ethereum_key` first** ⚠️⚠️

```bash
docker-compose up -d
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
