# Deployment Guide

## Prerequisites
- Node.js v18+
- Hardhat or Foundry installed
- Access to Ethereum RPC (Infura, Alchemy, etc.)
- Private key with deployment funds

---

## Steps

### 1. Compile Contracts
```bash
npx hardhat compile
```

### 2. Configure Environment
Create a `.env` file:
```
PRIVATE_KEY=your_private_key
RPC_URL=https://mainnet.infura.io/v3/your_project_id
```

### 3. Deploy Vault Contract
```bash
npx hardhat run scripts/deploy_vault.js --network mainnet
```

### 4. Verify on Etherscan
```bash
npx hardhat verify --network mainnet <DEPLOYED_ADDRESS>
```

---

## Post-Deployment Tasks
- Register supported ERC20 tokens
- Assign admin/operator roles
- Add strategies and link protocol adapters
