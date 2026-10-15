# QuantumPools

Automated concentrated-liquidity vaults for PancakeSwap V3 and Uniswap V3, deployed on **BNB Smart Chain (BSC)**.

This repository contains public deployment metadata for QuantumPools on BNB Chain. It holds no private source code, keys, or secrets.

## Technology Stack

- **Blockchain**: BNB Smart Chain (BSC)
- **Smart Contracts**: Solidity, verified on BscScan
- **DEX integrations**: PancakeSwap V3, Uniswap V3 (on BSC)
- **Governance / Security**: Timelock controller + Safe multisig

## Supported Networks

- **BNB Smart Chain Mainnet** (Chain ID: 56)

## Contract Addresses

| Network | Contract | Address |
|---------|----------|---------|
| BNB Smart Chain Mainnet | PancakeSwap V3 Vault | [`0x9597f68203d1bc85744A5Fc11D890aA7777e386B`](https://bscscan.com/address/0x9597f68203d1bc85744A5Fc11D890aA7777e386B) |
| BNB Smart Chain Mainnet | Uniswap V3 Vault | [`0x57cB3160D59e967D3ac62620Fc69f7e0898d2690`](https://bscscan.com/address/0x57cB3160D59e967D3ac62620Fc69f7e0898d2690) |
| BNB Smart Chain Mainnet | Timelock | [`0xE0db1d799dB2FF5aC539B95C3299c8AF060B4088`](https://bscscan.com/address/0xE0db1d799dB2FF5aC539B95C3299c8AF060B4088) |
| BNB Smart Chain Mainnet | Safe Multisig | [`0x00B3DCd95dDb5D1454dcbbfA6805e17f82244Ac1`](https://bscscan.com/address/0x00B3DCd95dDb5D1454dcbbfA6805e17f82244Ac1) |

Machine-readable config: [`bsc.json`](./bsc.json) (chain ID 56, BSC RPC, contract addresses).

## Features

- Automated liquidity management for PancakeSwap V3 and Uniswap V3 pools on BNB Smart Chain
- Pool Scanner for finding and comparing BSC liquidity pools
- Admin actions gated by a timelock and a Safe multisig on BSC
- Audited by Hashlock ([report](https://hashlock.com/audits/quantum-pools))

## Links

- Website: https://quantumpools.io
- App: https://app.quantumpools.io
- X: https://x.com/QuantumPoolsIO
- Telegram: https://t.me/QuantumPools
- Logo: https://quantumpools.io/brand/quantumpools-512.png
