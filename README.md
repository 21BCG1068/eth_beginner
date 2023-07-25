
# Our Token

Introducing "OurToken" - a custom contract built on Ethereum using Solidity. This token facilitates token creation and destruction, tracking total supply and individual balances. The program ensures sufficient balance before token burning. The contract adheres to the MIT license, enabling free usage and distribution. 

## Description

This Solidity smart contract named "OurTokens" represents a simple token system with basic minting and burning functionality. It uses the SPDX-License-Identifier tag to specify that it is licensed under the MIT license. Here's a short explanation of the code:

The contract defines the token's name as "Encanto" and its abbreviation as "enc". Additionally, it maintains a variable called "total_sum" to keep track of the total supply of tokens in circulation.

1. It uses a mapping named "balances" to associate token balances with addresses. Each address is mapped to the number of tokens it holds.

2. The "mint" function allows the contract owner to create new tokens and assign them to a specified address. It increases the total supply and updates the balance of the given address.

3. The "burn" function allows the contract owner to remove tokens from a specified address, effectively reducing the total supply and updating the balance of the address.


## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "HelloWorld" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the functions. 

## Author

Arshdeep Kaur

## License

This project is licensed under the MIT License 
