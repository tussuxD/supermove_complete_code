## Rock-Paper-Scissors dApp

This decentralized application (dApp) is an on-chain implementation of the classic Rock-Paper-Scissors game, built on the Aptos Blockchain. It allows users to play the game with others securely and transparently, leveraging blockchain technology to ensure fairness and immutability.

Features

- Decentralized Gameplay: All game logic is handled on-chain using Move smart contracts.

- Player Matching: Enables users to challenge others or join an open game.

- Fairness: Ensures moves are securely committed and revealed to prevent cheating.

- Transparent Transactions: All moves and outcomes are recorded on the Aptos blockchain for auditability.

Tech Stack
- Frontend: React

- Backend: Aptos Move smart contracts

- Blockchain: Aptos

- Wallet Integration: Supports Aptos wallets like Petra or Martian for transaction signing.

## Run Locally

Clone the project

```bash
https://github.com/tussuxD/supermove_complete_code
```

Go to the frontend of the project directory

```bash
  cd rock-paper-scissors-dapp
```

Install dependencies

```bash
  npm install
```
Deploy the Move smart contract:

```bash
aptos move compile
aptos move publish --profile default
```

Start the frontend:

```bash
  npm start
```

Connect your wallet and start playing!
