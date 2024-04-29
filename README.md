# Real Estate NFT DApp - ESTATE EASE

## Project Plan
![image](https://github.com/mkbhru/estate-ease/assets/74449664/1ec629ae-0769-44db-93ec-3239fa81f0f4)
![image](https://github.com/mkbhru/estate-ease/assets/74449664/c55b3a81-3360-4edc-97dd-d32aa433a2a6)



## Project Structure

<details>

```.
├── contracts
│   ├── Escrow.sol
│   └── RealEstate.sol
├── hardhat.config.js
├── metadata
│   ├── 1.json
│   ├── 2.json
│   └── 3.json
├── package.json
├── package-lock.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── README.md
├── scripts
│   └── deploy.js
├── src
│   ├── abis
│   │   ├── Escrow.json
│   │   └── RealEstate.json
│   ├── App.js
│   ├── App.test.js
│   ├── assets
│   │   ├── close.svg
│   │   ├── houses.png
│   │   └── logo.svg
│   ├── components
│   │   ├── Home.js
│   │   ├── Navigation.js
│   │   └── Search.js
│   ├── config.json
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
└── test
    └── Escrow.js
```
</details>
My project is basically utilizing already written open source contracts from openZeppelin framework. <br />
in contracts folder we have our Escrow and RealEstate contracts. <br />
in test folder we have our tests build using hardhat the file escrow.js contains all the tests.

## Testing Procedure
we can test our smart contract locally by Hardhat using command 
```npx hardhat node```
it'll start a local hardhat blockchain on our computer, it'll give us 20 accounts with fake ether in them

Now simultaneously run ```npx hardhat run scripts/deploy.js --network localhost```
and nfts would mint and get listed on bc

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
