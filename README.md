# Arc Network Testnet Exploration 🌐

> Documenting my hands-on journey exploring the Arc Network public testnet as an early contributor.

## About This Repo

Arc is an open Layer-1 blockchain built by Circle, purpose-built for stablecoin finance. It uses USDC as the native gas token, delivers sub-second transaction finality, and is designed to be the Economic OS for the internet.

This repository documents every activity I completed on the Arc testnet, from wallet setup to deploying a smart contract and providing DeFi liquidity.

**Wallet Address:** `0x63f4d4DCF687D1fB107152266A91088C0ACa36E8`
**Onchain Explorer:** [View on ArcScan](https://testnet.arcscan.app/address/0x63f4d4DCF687D1fB107152266A91088C0ACa36E8)
**Domain:** `thirtyfirstson.arc`

---

## ✅ Completed Activities

### 1. Wallet & Network Setup
- Added Arc Testnet to MetaMask wallet manually
- Network details: RPC `https://rpc.testnet.arc.network` | Chain ID `5042002`
- Confirmed connection via ArcScan block explorer

### 2. Faucet Claims
- Claimed **20 testnet USDC** from [Circle Faucet](https://faucet.circle.com)
- Claimed **20 testnet EURC** from [Circle Faucet](https://faucet.circle.com)
- Both tokens confirmed on ArcScan

### 3. Token Transfers
- Sent **0.11 USDC** to self — first self-initiated transaction on Arc
- Verified transaction hash on ArcScan

### 4. Domain Registration — InfinityName
- Registered **thirtyfirstson.arc** — a lifetime domain on Arc Testnet
- Platform: [InfinityName](https://infinityname.com)
- Cost: 1 USDC

### 5. Omnihub Activities
- **Swapped tokens** using the Bridge & swap feature
- **Deployed an ERC-721 smart contract** — created "Thirtyfirstson Collection" NFT collection
- **Minted an NFT** from the deployed contract
- Platform: [Omnihub](https://omnihub.xyz)

### 6. Curve Finance — DeFi Interactions
- **Swapped USDC → WUSDC** on Curve Finance Arc DEX
- **Deposited liquidity** into a Curve pool on Arc Testnet
- Platform: [Curve Finance](https://curve.finance/dex/arc/swap/)

---

## 🔍 Observations & Feedback

### What worked well
- Circle's faucet was smooth and delivered tokens instantly
- MetaMask wallet had no issues connecting to Arc Testnet
- ArcScan block explorer is clean and easy to navigate
- Omnihub made NFT contract deployment accessible to non-developers
- Curve Finance integration on Arc felt familiar and worked reliably although the Swap and Pools pages took 10-15 minutes to load

### What could be improved
- No official bridge UI exists yet — bridging requires code (CCTP/Bridge Kit)
- Thirdweb faucet requires a paid plan which was unexpected
- Some redirect issues on Omnihub after contract deployment (404 page)
- DEX options on Arc testnet are still limited — more live apps needed

---

## 🔭 What's Next (Phase 2)

- Write a JavaScript script using ethers.js to bridge USDC from Sepolia → Arc via CCTP
- Deploy a smart contract programmatically using Arc's developer docs
- Document the full developer experience for other learners
