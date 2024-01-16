# Joint Savings Account - Smart Contract

## Overview

This Solidity smart contract, implements a joint savings account with withdrawal functionality. Users can set authorized accounts, deposit funds, and withdraw funds according to the specified conditions.

The file **`joint_savings.sol`** contains all the steps required to set up the smart contract.

The folder **`Executions`** contains screenshots of contract deployment and interactions.

## Steps to Deploy and Interact

### Step 1: Compile and Deploy

1. Open `joint_savings.sol` in Remix IDE.
2. Compile the contract.
3. Deploy using "JavaScript VM" environment.

### Step 2: Set Authorized Accounts

Use the `setAccounts` function to set authorized Ethereum addresses.

- Account1: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
- Account2: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0

### Step 3: Test Functionality

#### Deposit Funds

1. Transaction 1: Send 1 ether as wei.
2. Transaction 2: Send 10 ether as wei.
3. Transaction 3: Send 5 ether.

Verify balances using `contractBalance` function after each transaction.

#### Withdraw Funds

1. Withdraw 5 ether into accountOne.
2. Withdraw 10 ether into accountTwo.

Verify balances and details using `contractBalance`, `lastToWithdraw`, and `lastWithdrawAmount` functions after each withdrawal.




