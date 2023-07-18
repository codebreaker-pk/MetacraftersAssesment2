# MetacraftersAssesment2

# My Own Token

This repository is made for creating and managing a custom token called MyToken on the Ethereum blockchain. The MyToken contract, written in Solidity, allows for the minting and burning of tokens, as well as tracking token balances and total supply.

##  Problem Statement

Create a Token.
## Assesment Requirements
    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

## Description

MyToken provides a user-friendly solution for tokenization, allowing you to create and manage your own token ecosystem. The contract includes features for token creation, minting, burning, and balance tracking.


## Features
- Token Creation: Customize the token name, abbreviation, and initial supply to reflect your project or brand.
- Minting Functionality: Increase the total supply and balance of the sender's address by minting new tokens.
- Burning Functionality: Reduce the total supply and balance of the sender's address by burning existing tokens.
- Balance Tracking: Utilize the mapping structure to track token balances associated with different addresses.
- Ethereum Compatibility: MyToken follows the ERC20 token standard, ensuring compatibility with wallets, exchanges, and dApps on the Ethereum network.
- Solidity Implementation: The contract is implemented in Solidity, the primary programming language for Ethereum smart contracts.
- Open-Source: MyToken is an open-source project, welcoming contributions and collaborations from the community.
- License: The project is released under the MIT License, allowing for modification and distribution with proper attribution.

By leveraging the power of MyToken, you can unlock new possibilities in the decentralized world, enabling tokenization and creating vibrant ecosystems tailored to your specific needs.





## Getting Started
### Prerequisites

To run and interact with the MyToken contract, you'll need the following:

- Ethereum development environment (e.g., Ganache, Remix, or a testnet/mainnet provider)
- Solidity compiler (e.g., solc)
- Web3 library or Ethereum client (e.g., ethers.js, web3.js)

### Importing the Contract

1. Open Remix in your web browser by visiting https://remix.ethereum.org/.

2. In the Remix IDE, import the MyToken.sol contract by following these steps:
   - Click on the "File Explorer" icon (folder icon) in the left sidebar.
   - Click on the "Open from file" button (folder with an arrow icon) at the top of the file explorer.
   - Select the MyToken.sol file from your local file system and click "Open".

### Compiling and Deploying the Contract

3. Switch to the "Solidity Compiler" tab in the Remix IDE sidebar.

4. Under the "File Explorer" section, select the imported MyToken.sol contract.

5. Choose the desired compiler version from the compiler drop-down (e.g., 0.8.18).

6. Click the "Compile" button to compile the MyToken contract.

7. Once the contract is successfully compiled, switch to the "Deploy & Run Transactions" tab in the sidebar.

8. Under the "Deployed Contracts" section, you will find the compiled MyToken contract. Select it from the drop-down.

9. Configure the deployment settings as per your requirements (e.g., select the desired network, provide constructor arguments if any).

10. Click the "Deploy" button to deploy the MyToken contract to the selected network.

### Interacting with the Contract

11. After the contract is successfully deployed, you can interact with its functions and view its state in the Remix IDE.

12. Use the provided interface in Remix or interact with the contract programmatically using Web3 libraries or Ethereum clients.

### Testing the Contract

13. To ensure the functionality of the MyToken contract, it's recommended to write and run tests.

14. You can use tools like Remix's built-in testing functionality, Truffle, or other testing frameworks to execute the test suite against the deployed contract.
## Author

**Prashant Kumar**

- GitHub: [github.com/codebreaker-pk](https://github.com/codebreaker-pk)
- Email: official.pk.900@gmail.com
## License
This project is licensed under the [MIT License](https://github.com/codebreaker-pk/MetacraftersAssesment2/blob/main/LICENSE).

