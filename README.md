# smart-contract-management-ETH-AVX

This project is a decentralized application (DApp) that interacts with the Contract smart contract. The DApp allows you to view the owner's name and balance, as well as transfer ethers to the contract owner.

## Description

The Contract DApp is built using Hardhat and React. It consists of a smart contract written in Solidity and a React frontend that provides a user-friendly interface to interact with the contract. The smart contract handles the logic for retrieving the owner's name and balance, as well as transferring ethers to the owner. The React frontend displays the owner's information and provides a form to initiate a transfer.

## Getting Started

To run the DApp, follow these steps:
   ```
   npm install
   ```
   ```
   npx hardhat node
   ```
   ```
   npx hardhat run scripts/deploy.js --network localhost
   ```
   ```
   cd ./frontend
   ```
   ```
   npm start
   ```
   ```
   npm start
   ```

   The DApp will be accessible in your web browser at `http://localhost:3000`.
