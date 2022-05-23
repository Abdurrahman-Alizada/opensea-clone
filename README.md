# History of Development

## Day 01

#### Project setup
On first day I Setup the project by doing following activities :

1. Made the Next.js Project
2. Infura setup
    - Project creation
    - Installation of packages
    - Link the Infura project with my local Next.js Project
    - Hard Hat configuration

## Day 02

#### Understanding the architecture of OpenZeppelin

I explored the overall contract architecture of OpenZeppelin.

## Day 03

#### Starting the development of Smart Contract in Solidity with OpenZeppelin

1. Create 2 contract NFT and NFTMarket 
2. write the nessecary funtions in both contracts

## Day 04 

1. Learned the testing methodolgy
2. write the tests for NFT and NFTMarket contract
3. completed the passed the passed successfully

## Day 05 

1. Start working on fronend

## Day 06
#### Index.js and create-item completed

In this two pages I write 4 function 

 1. loadNFT() in which all NFTs are loaded in render in through map function
 2. buyNFT() in which you can buy NFT by calling buyNFT function from NFTMarket smart contract
 3. createItem() in which NFT can be created
 4. createSale() in which NFT can be listed for sale

# How to use this project

- Clone the project
- yarn install or npm install
- create a .secret file in main directory
- paste the private key from your matamask account
  1. click on metamask
  2. click on 3 dots near to account address
  3. click on account details
  4. export private key and enter password
  5. copy the private key
- Sign in Infura
- Create new project
- Go to settings and copy the project Id 
- replace the project Id in hardhat.config.js 

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

