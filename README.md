# Open NFT Hub

A decentralized NFT marketplace built with Ethereum smart contracts, enables anyone to **mint, trade, and showcase NFTs** in a fully transparent, open ecosystem powered by blockchain technology.
---


---

##  Overview

next-generation decentralized marketplace where users can **create their own NFTs**, **list them for sale**, and **purchase NFTs from others** — all securely managed by Ethereum smart contracts and connected through IPFS for decentralized storage.

Each interaction (minting, offering, buying, claiming funds) is executed via blockchain transactions, ensuring full transparency and ownership verification.

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/blixor7/open-nft-marketplace.git
cd open-nft-marketplace
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Install Truffle (if not installed globally)

```bash
npm install -g truffle
```

---

##  Local Deployment

### Compile Contracts

```bash
truffle compile
```

### Run Local Blockchain

Use [Ganache](https://trufflesuite.com/ganache/) to start a local Ethereum environment.

### Run Tests

```bash
truffle test
```

### Deploy Contracts Locally

```bash
truffle migrate
```

### Launch the Frontend

```bash
npm start
```

#### Connect Metamask

1. Install the [Metamask browser extension](https://metamask.io/).
2. Connect to `http://localhost:7545` (Ganache).
3. Import an account using a private key from Ganache.

---

##  Deploy to Testnet

Create a `.env` file with:

```
PRIVATE_KEYS=<your-private-key>
INFURA_API_KEY=<your-infura-api-key>
```

Deploy to Ropsten (or any other testnet):

```bash
truffle migrate --network ropsten
```

Then build the production UI:

```bash
npm run build
```

---

##  Features

| Feature                | Description                                                    |
| ---------------------- | -------------------------------------------------------------- |
| **Mint NFTs**          | Create custom NFTs with a name, description, and image.        |
| **List NFTs for Sale** | Set your price in Ether and offer your NFT to the marketplace. |
| **Cancel Listings**    | Withdraw NFTs from sale at any time.                           |
| **Buy NFTs**           | Purchase NFTs listed by others securely via smart contracts.   |
| **Claim Funds**        | Claim Ether from sold NFTs.                                    |

---

##  Technology Stack

* **Solidity** – Smart contract language
* **React.js** – Frontend UI framework
* **Truffle** – Smart contract development and testing
* **Web3.js** – Blockchain communication library
* **Ganache** – Local Ethereum network
* **Node.js** – Backend environment
* **Metamask** – Wallet integration
* **IPFS** – Decentralized NFT storage

---

##  Resources

* [ethereum.org](https://ethereum.org)
* [Truffle Suite](https://trufflesuite.com)
* [Node.js](https://nodejs.org)
* [Web3.js](https://web3js.readthedocs.io/)
* [React.js](https://react.dev)
* [IPFS](https://ipfs.tech)

---

## Author

**blixor**
Building open and decentralized applications for the Web3 era.
