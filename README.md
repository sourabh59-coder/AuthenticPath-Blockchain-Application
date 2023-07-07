# Blockchain-based food supply chain- “AuthenticPath” 
   <b>Repository : </b> (https://github.com/sourabh59-coder/AuthenticPath-Blockchain-Application) <br><br>
![Screenshot (661)](https://github.com/sourabh59-coder/AuthenticPath-Blockchain-Application/assets/77907942/685c174c-0f51-489b-988e-f32891bfc6ca)

</div>


## Problem Statement

We know that as technology progresses, we are moving towards a world with lesser trust and more frequently occurring frauds. For example, when we order a product from any online store or offline store, we doubt whether we will get the original product as promised or not.

## Abstract

To deal with the above problem, we have introduced a project model based on web3 and blockchain technology that basically monitors the supply chain and brings transparency to the users. Here I have taken a use case of the supply chain that is the "Food supply chain". As we all know that health is the first priority for all humans and to maintain that they need proper quality food, the food supply chain is complex but necessary food production arrangement needed by the global community to maintain sustainability and food security. The supply chain has been extended geographically involving many more stakeholders, making the supply chain longer and complicated and thus involving many challenges. Some challenges faced by the traditional food supply chain are:

- Lack of traceability and communication.
- Rising supply chain costs.
- Supply of fraudulent food products.
- Failure of monitoring warehouses.

So this blockchain-based food supply chain basically deals with all the challenges faced by traditional food supply chains. This decentralized food supply chain is designed to trace the products from end to end and provide a smart and reliable way of providing information to the customers.

## Features

- Platform to trace the food products worldwide.
- Restricting duplicate and unauthentic products.
- Proper food distribution.
- Reducing the supply chain cost.
- Making an automated chain.
- Securing the network using the blockchain protocols.
- Creating features of the reputation system.

## Architecture of the system
![Screenshot (703)](https://github.com/sourabh59-coder/AuthenticPath-Blockchain-Application/assets/77907942/bd7d5dab-7513-41e0-9472-8a66b4e070e1)

### Application layer

- Farmers
- Manufacturer/processor
- Distributors
- Retailers
- Consumer

### Blockchain layer

- Ethereum based Smart contract
- Reputation system
- Trading system

### Infrastructure layer

- IPFS
- Nodes

## Methodology

The project is built on three core modules: Traceability System, Trading Mechanism, and Reputation System.

### Traceability System
![Screenshot (704)](https://github.com/sourabh59-coder/AuthenticPath-Blockchain-Application/assets/77907942/d486cb37-2955-4868-80df-5d6be04db884)

- Each product is marked with a unique serial code which is owned by an externally owned account on Ethereum.
- Every product transaction is recorded and stored in a smart contract and linked with the product's serial code.
- This comes with Access Control Strategy which allows only authentic users to make specific transactions.

### Trading Mechanism

- The process of delivering goods from one entity to another is tracked and recorded on the blockchain.
- The consumers first register themselves on the system and request to purchase the product with a serial number.
- The purchase request is sent to the product owner who updates the product ownership with the new owner.
- This process ensures that retailers do not sell products with duplicate serial codes.

### Reputation System
![Screenshot (705)](https://github.com/sourabh59-coder/AuthenticPath-Blockchain-Application/assets/77907942/efe0eed3-a1ce-442c-ba29-468c10119b24)

- This system adds a layer of trust between customers and retailers.
- This mechanism allows only actual customers of the product to post feedback about the product.
- The reviews on the blockchain are immutable which does not allow any merchant or retailer to delete or update bad reviews to increase their overall ratings.
- And in this way, this mechanism maintains the complete integrity of the retailer and lets the customer know about the seller before making the transaction.

## Technologies used

- User interface
- Ethereum-based Smart Contract
- IPFS for storage system
- NFT-storage system using API
- Truffle
- Metamask
- Ganache
- Web3.js
- Solidity smart contract language
