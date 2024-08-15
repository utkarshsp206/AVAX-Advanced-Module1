# AVAX-Advanced-Module1 

## TASK 1 : Deploy your EVM subnet using the Avalanche CLI

Use Avalanche's official documentation to create a custom EVM subnet. This subnet will allow you to deploy your smart contracts on a custom chain, giving you control over transaction fees and the native currency used in your game.

Step 1: Installation
```
curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s
```

Step 2: Create Your Subnet Configuration
```
avalanche subnet create mySubnet
```

Step 3: Give Name, ChainID and Token to your custom subnet

Step 4: Deploy your token
```
avalanche subnet deploy mySubnet
```


## TASK 2 : Add the custom subnet to your metamask wallet
Step 1: Create a new network with the new RPC URL got in first task

Step 2: Add a new address given in Task 1 with test tokens


## TASK 3 : Connect Remix Editor to Metamask wallet 
Connect your metamask wallet and the address given to your remix editor

## TASK 4 : Deploy the smart contracts to the custom subnet
Step 1 : Compile the Smart Contract

Step 2 : In remix, select injected-provider -Metamask

Step 3 : Deploy the contract

## TASK 5 : Test the deployed contracts
Test the deployed contracts for the various methods like, mint, burn and balanceOf .

### Author
Utkarsh Singh

Chandigarh University