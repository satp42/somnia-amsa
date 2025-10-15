# Somnia DeFi Agent: Adaptive MEV Shield Agent (AMSA)

A Next.js dApp on Somnia that detects and mitigates MEV while capturing safe opportunities for the user.

## Project Structure

```
somnia-amsa/
├── apps/
│   ├── web/          # Next.js frontend
│   └── agent/        # Node.js agent service
├── contracts/        # Solidity contracts
├── packages/
│   ├── ui/           # Shared UI components
│   ├── config/       # Shared config & types
│   ├── sdk/          # Type-safe client SDK
│   └── eslint-config/ # Shared ESLint config
└── infra/
    ├── docker/       # Docker setup
    └── db/           # Database schemas
```

## Getting Started

### Prerequisites

- Node.js >= 18.0.0
- npm >= 10.2.4

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Lint

```bash
npm run lint
```

## Somnia Network

- **Testnet RPC**: https://dream-rpc.somnia.network
- **Chain ID**: 50312
- **Explorer**: https://shannon-explorer.somnia.network
- **Faucet**: https://testnet.somnia.network

## License

MIT

