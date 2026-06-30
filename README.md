# Content Sharing DApp — Decentralised Education Platform

A blockchain-powered decentralised application (DApp) for sharing educational content securely and transparently. Built on Ethereum using Solidity smart contracts, this platform redefines content distribution by removing centralised intermediaries.

## Overview

Traditional educational platforms concentrate control in the hands of a few organisations. This DApp leverages decentralisation and blockchain immutability to create an open, tamper-proof content marketplace where educators own their work and learners access content directly.

## Features

- Decentralised content upload and storage
- Smart contract-enforced ownership and royalties
- Transparent transaction history on-chain
- MetaMask wallet integration
- No centralised server — runs entirely on Web3
- Educational content discovery and browsing

## Tech Stack

![Solidity](https://img.shields.io/badge/Solidity-0.8.x-363636?logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?logo=ethereum&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18.x-339933?logo=nodedotjs&logoColor=white)
![Truffle](https://img.shields.io/badge/Truffle-Framework-5e464d)
![Web3.js](https://img.shields.io/badge/Web3.js-F16822?logo=web3dotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## Project Structure

```
contracts/       # Solidity smart contracts
migrations/      # Truffle deployment scripts
test/            # Contract unit tests
app.js           # DApp backend / server
index.html       # Frontend interface
```

## Getting Started

### Prerequisites
- Node.js 18+
- Truffle: `npm install -g truffle`
- Ganache (local blockchain) or MetaMask with a testnet

### Setup

```bash
git clone https://github.com/DrOneEyed/Content_Sharing_DApp.git
cd Content_Sharing_DApp
npm install
truffle compile
truffle migrate
node app.js
```

Open `index.html` in your browser with MetaMask configured to the local network.

## License

MIT