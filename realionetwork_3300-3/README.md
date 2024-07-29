# RealioNetwork Testnet

## Instructions

## Full nodes and general participants

Follow the instructions on the official documentation to [join the testnet](https://docs.realio.network/testnet/overview) 

The team is [available on discord](https://discord.gg/Nv9EUbRnKb). Faucet is available on Realio Discord [`testnet-faucet`](https://discord.com/channels/1016319560581914747/1072894597509943346) channel.

For the validators who want to sync from scratch, check out the Upgrade section for binary information and follow the guides below for each upgrade.

### 1. Muktistaking upgrade: 310,744
When the node reaches the height `310744`, follow these guides to upgrade:
1. Stop the node
2. Export the state: `realio-networkd export > $HOME/.realio-network/config/state.json`
3. Install the new binary:
   ```bash
   cd ~/realio-network
   # or
   cd $HOME && git clone https://github.com/realiotech/realio-network.git && cd realio-network
   git checkout 3230cf1fd87a8d9b1398e50418deb362fa3c5694
   make install
   ```
4. Restart the node: `realio-networkd start`

## Genesis File

Download the genesis file [genesis.json](./genesis.json)

Verify the SHA256 checksum using:

```bash
sha256sum genesis.json
# cb7bff90eb083bed331e46aa6d8d3aef676d7efcce7d219d2a1bca3215fa80eb  genesis.json
```

## Details

- Network Chain ID: `realionetwork_3300-3`
- EIP155 Chain ID: `3300`
- Explorer: [testnet-explorer.realio.network](https://testnet-explorer.realio.network)
- `realio-networkd` version: [`0.9.3`](https://github.com/realiotech/realio-network/releases/tag/v0.9.3)
   ```bash
   $ realio-networkd version --long
    
   commit: 505655e1c64ecf2b73fba4147d94d302d7cee96a
   cosmos_sdk_version: v0.46.12
   go: go version go1.21.5 linux/amd64
   name: realio-network
   server_name: realio-networkd
   version: 0.9.3
   ```
   
## Upgrades

| Version           | Height  | Commit                                   |
|-------------------|---------|------------------------------------------|
| v0.8.3            | 1       | 55f63ff6ef1d98997106aab16e6accff43f40755 |
| 0.8.3-68-g3230cf1 | 310,744 | 3230cf1fd87a8d9b1398e50418deb362fa3c5694 |


Pop in the [ testnet seed channel on discord](https://discord.gg/Nv9EUbRnKb) and ask for other peer/seed nodes
