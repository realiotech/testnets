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
# dc273fa5ffff13890be1d5596fce9394047df8b4e1122ed198c367bf6138056b  genesis.json
```

## Details

- Network Chain ID: `realionetwork_3300-2`
- EIP155 Chain ID: `3300`
- Explorer: [explorer.realionetwork.dev](https://explorer.k8s.stage.realio.fund/)
- `realio-networkd` version: [`v0.8.0-rc4`](https://github.com/realiotech/realio-network/releases/tag/v0.8.0-rc4)
   ```bash
     realio-networkd version --long
    
  commit: 692d8ccbd4c229135445d82b51bd2dfd52224651
  cosmos_sdk_version: v0.46.11
  go: go version go1.20.2 darwin/arm64
  name: realio-network
  server_name: realio-networkd
  version: 0.8.0-rc4

    
    ```

## Seeds & Peers

Pop in the [ testnet seed channel on discord](https://discord.gg/Nv9EUbRnKb) and ask for a peer/seed node
