# fun.pump

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (Next.js & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Next.js](https://nextjs.org/) (Frontend Framework)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/). We recommend using an LTS (long-term-support) version, and preferably installing NodeJS via [NVM](https://github.com/nvm-sh/nvm#intro).

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Run tests
`$ npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal execute:

`$ npx hardhat ignition deploy ignition/modules/Factory.js --network localhost`

If you have previously deployed you may want to append `--reset` at the end:

`$ npx hardhat ignition deploy ignition/modules/Factory.js --network localhost --reset`

### 6. Start frontend
`$ npm run dev`