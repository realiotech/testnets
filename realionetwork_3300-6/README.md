# RealioNetwork Testnet

## Instructions

## Full nodes and general participants

Follow the instructions on the official documentation to [join the testnet](https://docs.realio.network/testnet/overview) 

The team is [available on discord](https://discord.gg/Nv9EUbRnKb)

## Genesis File

Download the genesis file [genesis.json](./genesis.json)

Verify the SHA256 checksum using:

```bash
sha256sum genesis.json
# 66e6339ff13fe0d7c9f06b01f0b612b0440efcab0337627b3c3dde912dae5ced  genesis.json
```

## Details

- Network Chain ID: `realionetwork_3300-6`
- EIP155 Chain ID: `3300`
- Explorer: [explorer.realiostage.network](https://explorer.realiostage.network/)
1- `realio-networkd` version: [`v1.3.0`](https://github.com/realiotech/realio-network/releases/tag/v1.3.0)
   ```bash
     realio-networkd version --long
    
      commit: f6df1a734e80c612a08823773f60b0f44c55ee05
      cosmos_sdk_version: v0.50.13
      go: go version go1.22.5 linux/amd64
      name: realio-network
      server_name: realio-networkd
      version: 1.3.0
    ```

## Seeds & Peers

```bash
7209cbeb9bafb98add50ae29aa86524e11a4be9b@65.109.92.163:18020,e122b19623b6da8ef61775b9511a9b9470142263@65.21.197.14:26656
```
