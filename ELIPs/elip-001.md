---
elip: 001
title: Evolution Land Interstella Object Encoding
author: HF
type: Standards Track
category: Core
status: Draft
created: 2018-12-20
---


### Rationale

This would provide a way to share a global unique ERC721 object id with in Evolution Land, for identify different chain on the network, we need to give each chain a unique `CHAIN_ID`, and it is supposed to compatibe with EIP-155.

https://github.com/ethereum/EIPs/blob/master/EIPS/eip-155.md



### List of Chain ID's:

| `CHAIN_ID`     | Chain(s)                                   |
| ---------------| -------------------------------------------|
| 1              | Ethereum mainnet                           |
| 2              | Morden (disused), Expanse mainnet          |
| 3              | Ropsten                                    |
| 4              | Rinkeby                                    |
| 8              | Ubiq mainnet                               |
| 9              | Ubiq testnet                               |
| 30             | Rootstock mainnet                          |
| 31             | Rootstock testnet                          |
| 42             | Kovan                                      |
| 61             | Ethereum Classic mainnet                   |
| 62             | Ethereum Classic testnet                   |
| 66             | ewasm testnet                              |
| 1337           | Geth private chains (default)              |
| 6284           | Görli                                      |
| 314158         | Stureby                                    |
| TRON Chains    | --------------------------                 |
| 200000         | TRON mainet                                |
| 200001         | TRON Shasta                                |