# Crowdfunding dAPP developped with Solidity and integrated with Bubble.io for the front end

This is modified version of the other Crowdfunding kickstart app in other repository. This time the front end is not developped in React, but with the Bubble.io nocode platform.

klink to test the App: https://live.trainingcompanion.app/version-test/web3_kickstarter

<h2>What does it do?</h1>
This is proof of concept of a decentralized crowdfunding application. The application enables Project Founders to create a funding campaign. Once created, people wanting to fund the project (Contributers) can send money to the campaign. The funds stay in a smart contract on Ethereum. When the Project Founder wants to spend money (to buy goods or services for his project, such as marketing campaign or raw materials), he needs to issue a spending requests (informing the concept, amount and provider). The contributers can approve or reject the request. The request is then processed if more than 50% of the contributers approve the request.

<h2>How is it implemented?</h2>
The full project relies on an Ethereum smart contract, which handles all the transactions (campaign creation, funding, spending requests, and approvals). It is then fully decentralized, and does not need any trusted authority.

<h2>What does it solve?</h2>
It solves the potential issue of Founders spending the money at their will (to buy a lambo for instance), without any control from the contributors. Here, the money stays in the smart contract, and the Project Founder can only spend it if the majority of contributors approve it.

<h2>How do I use it?</h2>
It is a proof of concept, it's not using real money (so, not real ETH). It is implemented on the Ethereum Rinkeby Test network. In order to use it, create a Metamask Wallet, switch it to the Rinkeby network. You can get some Ethereum (fake test money) for Rinkeby at the following link: https://faucets.chain.link/rinkeby
In order to simulate different users, you can switch account in your Metamask.
