# Coffee Support

## Deployed Contracts

### CoffeeProfile
- **Network:** Arc Testnet (chain ID 5042002)
- **Address:** `0x9fe6b040a4c7972b299492e67805d3c352fdbe20`
- **Explorer:** https://explorer.testnet.arc.io/address/0x9fe6b040a4c7972b299492e67805d3c352fdbe20
- **Admin:** `0x306eDcCC533b08628278a6AFD60A628BB8B4Ab0E`
- **Deployed:** 2026-10-07

---

> Built with Arc Studio - money-powered apps in minutes

This is the **project memory** - what Arc Studio remembers about building this app. It helps future agents (or humans) understand and extend the project.

---

## What This App Does

[Brief description of what the app does and its primary use case]

## Tech Stack

- Frontend: React 18, Vite, TypeScript, Tailwind CSS
- Web3: wagmi v2, viem v2, ConnectKit
- Contracts: Solidity 0.8.28 + Foundry. Sources in `contracts/`, unit tests in `contracts/test/*.t.sol`. Build with `bun run contracts:build` (`forge build`), test with `bun run contracts:test` (`forge test`).
- Wallet: injected (MetaMask, etc.)
- Chain: Arc Testnet (Chain ID: 5042002, imported from `viem/chains`)
- Token: USDC (6 decimals) (Address: 0x3600000000000000000000000000000000000000, Chain: Arc Testnet)
- Toasts: Sonner

## Key Files

- `src/App.tsx` - Main application logic
- `src/components/` - UI components
- `src/config.ts` - wagmi config (chains, connectors, transports)

## To Run

```bash
bun install
bun run dev
```
