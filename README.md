# BRO💪FIGHTS
Buy weapons and battle with other Bro NFTs.

⚙️ Built using NextJS, RainbowKit, Hardhat, Wagmi, and Typescript. Deployed on AIA Testnet

Deployed smart contract on AIA testnet : https://testnet.aiascan.com/address/0xb7a39632a3C45FF7027AfdF0B41dad8408C12190

## Welcome to BRO💪FIGHTS Homepage

![Screenshot_30-10-2024_2184_localhost](https://github.com/user-attachments/assets/11781c5f-dcdd-405f-8eed-a3c00bb89506)

## Marketplace page

![Screenshot_30-10-2024_21819_localhost](https://github.com/user-attachments/assets/95d59f1e-e599-47c6-a3b5-36b09dc0d9b8)

## Game Play page

![Screenshot_30-10-2024_21840_localhost](https://github.com/user-attachments/assets/5cba374c-e171-4389-add7-8eda5c9e218a)

## Requirements

Before you begin, you need to install the following tools:

- [Node (v18 LTS)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

## Quickstart

To get started with BRO💪FIGHTS, follow the steps below:

1. Clone this repo & install dependencies

```
git clone https://github.com/govardhan666/Bro_Fights_on_Aia_testnet
cd Bro_Fights_on_Aia_testnet
yarn install
```

2. Run a local network in the first terminal:

```
yarn chain
```

This command starts a local Ethereum network using Hardhat. The network runs on your local machine and can be used for testing and development. You can customize the network configuration in `hardhat.config.ts`.

3. On a second terminal, deploy the test contract:

```
yarn deploy
```

This command deploys a test smart contract to the local network. The contract is located in `packages/hardhat/contracts` and can be modified to suit your needs. The `yarn deploy` command uses the deploy script located in `packages/hardhat/deploy` to deploy the contract to the network. You can also customize the deploy script.

4. On a third terminal, start your NextJS app:

```
yarn start
```

Visit your app on: `http://localhost:3000`. You can interact with your smart contract using the contract component or the example ui in the frontend. You can tweak the app config in `packages/nextjs/scaffold.config.ts`.
