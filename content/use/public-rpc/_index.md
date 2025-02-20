---
title: Public RPC Endpoints
menuTitle: Public RPC Endpoints
weight: 20
aliases:
  - /resources/public-rpc-endpoints
  - /home/resources/public-rpc-endpoints
  - /home/use/public-rpc
description: We've staked POKT on your behalf to provide public RPC endpoints for all of the networks that Pocket supports. Use these endpoints in any DApp that lets you use a custom endpoint.
---


## How to Customize Your Endpoint (e.g. MetaMask)

To change your endpoint in MetaMask, do the following, **filling in the fields from the table below**:

1. Click on the Networks drop-down menu, then press **Add Network**
2. Under the Network Name field, write **`<Network Name> Pocket Portal`**
3. Within the New RPC URL field, **copy** and **paste** **`<RPC URL>`**
4. (Optional) Put **`<ChainID>`** in the ChainID field
5. (Optional) Write **`<Symbol>`** as the Symbol
6. (Optional) Add **`<Explorer URL>`** as the Block Explorer URL
7. **Don’t forget to save**

{{% notice style="info" %}}
If you receive this error message from MetaMask `Invalid number. Enter a decimal or '0x'-prefixed hexadecimal number` then leave the optional fields blank.
{{% /notice %}}

{{< youtube 8ruuz3u2V2E >}}

## Endpoints

| Network Name                                        | RPC URL                                               | ETH ChainID    | Symbol | Explorer URL                          |
| --------------------------------------------------- | ----------------------------------------------------- | ----------     | ------ | ------------------------------------- |
| Arbitrum                                            | https://arbitrum-rpc.gateway.pokt.network             | 42161          | ARB    | https://arbiscan.io                   |
| [Avalanche](https://youtu.be/9SNGe2tfmmw)           | https://avax-rpc.gateway.pokt.network                 | 43114          | AVAX   | https://cchain.explorer.avax.network  |
| [BNB Smart Chain](https://youtu.be/fLTvtBtOEg0)     | https://bsc-rpc.gateway.pokt.network                  | 56             | BNB    | https://bscscan.com                   |
| DFK Chain                                           | https://avax-dfk-rpc.gateway.pokt.network             | 53935          | JEWEL  | https://subnets.avax.network/defi-kingdoms/dfk-chain/explorer         |
| [Ethereum](https://youtu.be/8ruuz3u2V2E)            | https://eth-rpc.gateway.pokt.network                  | 1              | ETH    | https://etherscan.io                  |
| Ethereum Archival                                   | https://eth-archival-rpc.gateway.pokt.network         | 1              | ETH    |                                       |
| Ethereum Goerli                                     | https://eth-goerli-rpc.gateway.pokt.network           | 5              | ETH    | https://goerli.etherscan.io           |
| Ethereum Kovan                                      | https://eth-kovan-rpc.gateway.pokt.network            | 42             | ETH    | https://kovan.etherscan.io            |
| Ethereum Rinkeby                                    | https://eth-rinkeby-rpc.gateway.pokt.network          | 4              | ETH    | https://rinkeby.etherscan.io          |
| Ethereum Ropsten                                    | https://eth-ropsten-rpc.gateway.pokt.network          | 3              | ETH    | https://ropsten.etherscan.io          |
| Ethereum Trace                                      | https://eth-trace-rpc.gateway.pokt.network            | 1              | ETH    |                                       |
| Evmos                                               | https://evmos-rpc.gateway.pokt.network                | 9001           | EVMOS  | https://evm.evmos.org                 |
| Fantom                                              | https://fantom-rpc.gateway.pokt.network               | 250            | FTM    | https://ftmscan.com                   |
| [FUSE](https://youtu.be/sSg8QWgR_T8)                | https://fuse-rpc.gateway.pokt.network                 | 122            | FUSE   | https://explorer.fuse.io              |
| Gnosis Chain                                        | https://gnosischain-rpc.gateway.pokt.network          | 100            | xDAI   | https://blockscout.com/poa/xdai       |
| Gnosis Chain Archival                               | https://gnosischain-archival-rpc.gateway.pokt.network | 100            | xDAI   |                                       |
| Kava Mainnet                                        | https://kava-rpc.gateway.pokt.network                 | 2222           | KAVA   | https://explorer.kava.io/             |
| Klaytn                                              | https://klaytn-rpc.gateway.pokt.network               | 8217           | KLAY   | https://scope.klaytn.com              |
| Moonbeam                                            | https://moonbeam-rpc.gateway.pokt.network             | 1284           | GLMR   | https://moonscan.io                   |
| Moonriver                                           | https://moonriver-rpc.gateway.pokt.network            | 1285           | MOVR   | https://moonriver.moonscan.io         |
| NEAR                                                | https://near-rpc.gateway.pokt.network                 |                | NEAR   | https://www.nearblocks.io             |
| Oasys Mainnet                                       | https://oasys-rpc.gateway.pokt.network                | 248            | OAS    | https://explorer.oasys.games/         |
| Optimism                                            | https://optimism-rpc.gateway.pokt.network             | 10             | ETH    | https://optimistic.etherscan.io       |
| Osmosis                                             | https://osmosis-rpc.gateway.pokt.network              |                | OSMO   | https://www.mintscan.io/osmosis       |
| Pocket Network                                      | https://pokt-rpc.gateway.pokt.network                 |                | POKT   | https://explorer.pokt.network         |
| [Polygon](https://youtu.be/C0jDq20pBYQ)             | https://poly-rpc.gateway.pokt.network                 | 137            | MATIC  | https://polygonscan.com               |
| Polygon zkEVM                                       | https://zkevm-polygon-mainnet-rpc.gateway.pokt.network| 1101           | ETH    | https://zkevm.polygonscan.com/        |