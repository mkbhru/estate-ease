# Real Estate NFT DApp - ESTATE EASE

## Project Plan
![image](https://github.com/mkbhru/estate-ease/assets/74449664/1ec629ae-0769-44db-93ec-3239fa81f0f4)
![image](https://github.com/mkbhru/estate-ease/assets/74449664/c55b3a81-3360-4edc-97dd-d32aa433a2a6)

## Project Structure

<details>
<summary>Project Tree </summary>
```
estate-ease
├─ .git
│  ├─ FETCH_HEAD
│  ├─ HEAD
│  ├─ ORIG_HEAD
│  ├─ branches
│  ├─ config
│  ├─ description
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     └─ remotes
│  │        └─ origin
│  │           ├─ HEAD
│  │           └─ main
│  ├─ objects
│  │  ├─ b8
│  │  │  └─ 18b4338731bd31b16c9f89068aa3fb6f2d1c11
│  │  ├─ ba
│  │  │  └─ d300388f3cada6236fcdbc15063414f1b6e3f4
│  │  ├─ fe
│  │  │  └─ dea77afe1728698a593fa3e30d7e73cee0f958
│  │  ├─ info
│  │  └─ pack
│  │     ├─ pack-d81641f227f4e0115e6e3ee3d026f006d3b9030d.idx
│  │     └─ pack-d81641f227f4e0115e6e3ee3d026f006d3b9030d.pack
│  ├─ packed-refs
│  └─ refs
│     ├─ heads
│     │  └─ main
│     ├─ remotes
│     │  └─ origin
│     │     ├─ HEAD
│     │     └─ main
│     └─ tags
├─ .gitignore
├─ README.md
├─ contracts
│  ├─ Escrow.sol
│  └─ RealEstate.sol
├─ hardhat.config.js
├─ metadata
│  ├─ 1.json
│  ├─ 2.json
│  └─ 3.json
├─ package-lock.json
├─ package.json
├─ public
│  ├─ favicon.ico
│  ├─ index.html
│  ├─ logo192.png
│  ├─ logo512.png
│  ├─ manifest.json
│  └─ robots.txt
├─ scripts
│  └─ deploy.js
├─ src
│  ├─ App.js
│  ├─ App.test.js
│  ├─ abis
│  │  ├─ Escrow.json
│  │  └─ RealEstate.json
│  ├─ assets
│  │  ├─ close.svg
│  │  ├─ houses.png
│  │  └─ logo.svg
│  ├─ components
│  │  ├─ Home.js
│  │  ├─ Navigation.js
│  │  └─ Search.js
│  ├─ config.json
│  ├─ index.css
│  ├─ index.js
│  ├─ logo.svg
│  ├─ reportWebVitals.js
│  └─ setupTests.js
└─ test
   └─ Escrow.js
```
</details>

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

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
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`
