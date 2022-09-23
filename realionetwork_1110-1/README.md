# RealioNetwork Testnet

## Instructions

## Full nodes and general participants

Follow the instructions on the official documentation to [join the testnet](https://realio.network) and how to obtain tokens using the [faucet](https://realio.network).

## Genesis File

Download the zipped genesis file [genesis.zip](./genesis.zip)

Extract it with command

```bash
unzip genesis.zip
```

Verify the SHA256 checksum using:

```bash
sha256sum genesis.json
# 1231212312  genesis.json
```

## Details

- Network Chain ID: `realionetwork_1110-1`
- EIP155 Chain ID: `1110`
- `realio-networkd` version: [`v0.4.0`](https://github.com/realiotech/realio-network/releases)
- Faucet: [faucet.realionetwork.dev](https://realio.network)
- Explorer: [explorer.realionetwork.dev](https://realio.network)

## Seeds & Peers

You can find seeds & peers on the seeds.txt and peers.txt files, respectively. If you want to share your seed or peer, please fork this repo and and add it to the bottom of the corresponding .txt file.
