# Alchemy ERC 721 on Ropstan Testnet

## Important files

### MyNFT.sol

This file hold the solidity coded smart contract class

### deploy.js

This file deploys the NFT to the network

### mint-nft.js

This file mints NFT's

## How to Deploy & Mint

1. Compile the contracts
   `$ npx hardhat compile`

2. Deploy to ropsten
   `$ npx hardhat run scripts/deploy.js --network ropsten`

3. Mint NFT
   `$ node scripts/mint-nft.js`
