
# Our Token

Introducing "OurToken" - a custom contract built on Ethereum using Solidity. This token facilitates token creation and destruction, tracking total supply and individual balances. The program ensures sufficient balance before token burning. The contract adheres to the MIT license, enabling free usage and distribution. 

## Description

Introducing "OurToken," a Solidity smart contract designed for the Ethereum blockchain. The contract stores essential token details, such as name, abbreviation, and total supply, in public variables. It utilizes a mapping to efficiently manage ownership by associating Ethereum addresses with their respective token balances. The contract offers  functions for creating new tokens, increasing total supply, and updating recipient balances, and "burn" for destroying tokens, reducing total supply, and deducting from token holder balances. Notably, the "burn" function includes a balance check to ensure sufficient funds before burning. With these functionalities, the contract provides a comprehensive solution for secure and decentralized token management on the Ethereum blockchain.


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
