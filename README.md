# Eth Beginner

# Description
The program introduces a simple custom token called "OurToken" built on the Ethereum blockchain using Solidity. It allows for the creation and destruction of tokens, keeping track of their total supply and individual balances. Overall, it provides a user-friendly and accessible framework for creating and managing custom tokens on the Ethereum platform, offering a reliable solution for token issuance and tracking.


## Getting Started
- SPDX License Identifier: A comment that indicates the license under which the code is distributed.

- Solidity Version Pragma: Specifies the version of the Solidity compiler to be used for compiling the contract.

- Contract Declaration: Starts the declaration of a Solidity smart contract named OurTokens.

#### Token Variables:

- Declares and initializes three state variables:
- token_name: Holds the name of the token(Encanto).
- token_abbr: Holds the abbreviation of the token(enc).
- total_sum: Represents the total sum of tokens.
- Balances Mapping: Declares a mapping named balances that associates addresses with token balances.

#### Mint Function
- A function named mint used to create new tokens:
- Parameters: add (address) and val (number of tokens to create).
- Increases the total_sum and adds tokens to the balance of the provided address.
#### Burn Function
- A function named burn used to destroy (burn) existing tokens:
- Parameters: add (address) and val (number of tokens to burn).
- Decreases the total_sum and reduces tokens from the balance of the provided address.
- Closing Brace: Indicates the end of the OurTokens contract.

In summary, the code defines a Solidity smart contract representing a simple token system. It allows the creation and destruction of tokens, tracks balances for different addresses, and maintains a total sum of all tokens.


### Installing

- Open Remix:
Open the Remix IDE in your web browser.

- Create a New File:
Click on the "+" icon to create a new file. Name the file something like OurTokens.sol.

- Paste the Code:
Paste the provided Solidity code into the newly created file.

### Deploying 

- Compile the Contract:
In the Remix IDE, go to the "Solidity Compiler" tab. Select the correct version (0.8.18) from the compiler version dropdown. Click the "Compile" button to compile the contract. You should see a green checkmark indicating successful compilation.

- Deploy the Contract:
Go to the "Deploy & Run Transactions" tab. In the "Deploy" section, select the OurTokens contract from the dropdown. Choose an Ethereum environment (like JavaScript VM for testing). Click the "Deploy" button.

- Interact with the Contract:
After deploying the contract, you'll see the contract interface showing the deployed contract address, available functions, and state variables.


### Exceution 

- mint: To create tokens, enter an Ethereum address and a value for tokens to be minted. Click the "transact" button.
- burn: To burn tokens, enter an Ethereum address and a value for tokens to be burned. Click the "transact" button.
- balances: You can read the token balance associated with a specific address.
- token_name: Encanto.
- token_abbr: enc.
- total_sum: You can read the total sum of tokens.


# SUMMARY 

## Code Summary:

- SPDX License Identifier: A comment indicating the license under which the code is distributed.

- Solidity Version Pragma: Specifies the version of the Solidity compiler for contract compilation.

- Contract Declaration: Begins the declaration of a Solidity smart contract named OurTokens.

- Token Variables: Initializes state variables for token-related information, including name, abbreviation, and total supply.

- Balances Mapping: Creates a mapping called balances to link addresses with token balances.

- Mint Function: Defines a function named mint to create new tokens, adjusting the total supply and individual balances.

- Burn Function: Defines a function named burn to destroy tokens, updating the total supply and individual balances.

- Closing Brace: Marks the end of the OurTokens contract.


# Author
- Arshdeep Kaur

- 21BCG1068

# License
This contract is licensed under the MIT License. SPDX-License-Identifier: MIT.
