# 🚀 MyToken (MTK) – ERC-20 Token Project

MyToken (MTK) is a custom token that mimics the behavior of a standard ERC-20 token.  
The goal of this project was to understand:

- How token balances are stored  
- How transfers work internally  
- How approvals and allowances function  
- How to deploy and interact with smart contracts using Remix  

This project helped reinforce core concepts of Ethereum, Solidity programming, and smart contract execution.

---

## 🧩 Features Implemented

✔️ Minting full supply to the deployer  
✔️ Transfer tokens to another address  
✔️ Approve a spender to use tokens  
✔️ Transfer tokens using allowance (`transferFrom`)  
✔️ Check balances and allowances  
✔️ Emits standard events (`Transfer` and `Approval`)  

---

## 📂 Project Structure

my_token/
├── contracts/
│ └── MyToken.sol
├── screenshots/
│ ├── compilation.png
│ ├── deployment.png
│ ├── token-info.png
│ ├── transfer-test.png
│ └── events.png
└── README.md

markdown
Copy code

---

## 📜 Smart Contract Overview

The contract is written in **Solidity 0.8.x** and includes:

- `name`, `symbol`, `decimals`
- `balances` mapping for storing user balances
- `allowances` mapping for spender permissions
- `transfer()`, `approve()`, `transferFrom()` functions
- ERC-20 style `Transfer` and `Approval` events  

You can view the full source code in:

contracts/MyToken.sol

yaml
Copy code

---

## 🖥️ Steps Performed in Remix

### 1️⃣ **Compilation**
- Selected compiler version **0.8.30**
- Compiled successfully without warnings or errors  

### 2️⃣ **Deployment**
- Environment: **Remix VM (Prague)**
- Entered total supply as constructor input  
- Contract deployed successfully  

### 3️⃣ **Interaction & Testing**
Performed the following tests:

- Checked balances using `balanceOf`
- Sent tokens using `transfer`
- Approved a spender using `approve`
- Executed delegated transfer using `transferFrom`
- Verified allowance values  
- Observed emitted events in Remix logs  

All screenshots of these steps are available in the **screenshots/** folder.

---

## 🎯 Learning Outcomes

Through this project, I learned:

- How ERC-20 token standards work internally  
- How mappings store token balances  
- How allowance-based transfers function  
- How to deploy and test a smart contract in Remix  
- How to organize and publish a blockchain project on GitHub  

---

## 📎 License

This project is licensed under the **MIT License**.
