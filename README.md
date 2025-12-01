
🚀 Project Overview

MyToken (MTK) is a custom token that mimics the behavior of a standard ERC-20 token.
The goal of this project was to understand:

How token balances are stored

How transfers work internally

How approvals and allowances function

How to deploy and interact with smart contracts using Remix

This project helped reinforce core concepts of Ethereum, Solidity programming, and smart contract execution.

🧩 Features Implemented

✔️ Minting full supply to the deployer
✔️ Transfer tokens to another address
✔️ Approve a spender to use tokens
✔️ Transfer tokens using allowance (transferFrom)
✔️ Check balances and allowances
✔️ Emits standard events (Transfer and Approval)

📂 Project Structure
my_token/
├── contracts/
│   └── MyToken.sol
├── screenshots/
│   ├── compilation.png
│   ├── deployment.png
│   ├── token-info.png
│   ├── transfer-test.png
│   └── events.png
└── README.md

📜 Smart Contract

The contract is written in Solidity 0.8.x and contains:

name, symbol, decimals

balances mapping

allowances mapping

approve(), transfer(), transferFrom() functions

Token events for tracking transactions

You can view the full contract code in contracts/MyToken.sol.

🖥️ Steps Performed in Remix
1️⃣ Compilation

Selected compiler version 0.8.30

Compiled the contract without errors

2️⃣ Deployment

Selected Remix VM (Prague)

Entered total supply

Deployed the contract successfully

3️⃣ Interaction

Tested the following:

Checking balanceOf

Transferring tokens

Using approve + transferFrom

Reading allowances

Observing event logs

Screenshots of these steps are available in the screenshots/ folder.

🎯 Learning Outcomes

Through this project, I learned:

How ERC-20 token standards work internally

How mappings store token balances

How allowance-based transfers work

How to deploy and test contracts in Remix

How to manage a simple blockchain project using GitHub

📎 License

This project is released under the MIT License.
