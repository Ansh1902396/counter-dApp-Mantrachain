# counter-dApp

# Project Overview

This project involves the deployment of smart contracts on the Mantra chain using CosmWasm. It includes three main components:

1. **Contracts**: Smart contracts for the counter which are to be deployed on the Mantra chain.
2. **Client**: Client-side code written using `ts-codegen` and `cosmjs/stargate` for interacting with the deployed contracts.
3. **Deployer**: A script to deploy the contracts quickly on the Mantra chain.

## Components

### 1. Contracts

Your smart contracts for the counter, written in CosmWasm, are designed to be deployed on the Mantra chain. These contracts handle the core logic and state management for the counter application.

**Features:**
- Written in CosmWasm.
- Designed for the Mantra chain.
- Implements counter logic.

### 2. Client

The client-side code is developed using `ts-codegen` and `cosmjs/stargate`. This code enables interaction with the deployed smart contracts from a frontend application.

**Technologies Used:**
- `ts-codegen`: For TypeScript code generation.
- `cosmjs/stargate`: For interacting with the Cosmos blockchain.

**Functionality:**
- Interact with deployed smart contracts.
- Fetch and display contract data.
- Send transactions to the smart contracts.

#### Files:
- **codegen.ts**: Generates types out of your contracts using `ts-codegen`. You need to add the path of your schema.
- **index.ts**: Sample for interacting with your dApp written using `cosmjs/stargate` and `ts-codegen`.

### 3. Deployer

The deployer script automates the deployment of your smart contracts on the Mantra chain, making the process quick and efficient.

**Features:**
- Automates contract deployment.
- Quick and efficient deployment on the Mantra chain.
- Simplifies the deployment process.

**Deployment Command:**
1. Copy the compiled contract:
   ```bash
   cp ./contracts/<CONTRACT>/<CONTRACT>.wasm .


