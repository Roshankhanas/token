**Token README**

### Overview
This repository contains the Solidity smart contract code for a custom ERC20 token. The token extends functionality from OpenZeppelin's ERC20 and ERC20Burnable contracts, and also incorporates Ownable functionality for administrative control.

### Contract Structure
The main contract `Token.sol` contains the following functionality:

1. **Token Contract**: This contract defines the behavior of the custom ERC20 token.
2. **Constructor**: Initializes the token with a name and symbol.
3. **Minting**: Allows the contract owner to mint new tokens and assign them to a specified address.
4. **Burning**: Provides the functionality for token holders to burn a specific amount of their tokens, reducing the total supply.
5. **Transfer**: Overrides the transfer functionality to provide additional checks and customization.


### Usage
Once deployed, the token contract can be interacted with using various Ethereum wallet interfaces or through smart contract interactions.

1. **Minting**: The contract owner can mint new tokens using the `mint` function, specifying the recipient's address and the amount to mint.
2. **Burning**: Token holders can burn their tokens using the `burn` function, specifying the amount to burn.
3. **Transferring**: Token holders can transfer tokens to other addresses using the standard ERC20 `transfer` function or the custom `transfer_` function provided in the contract.

### License
This project is licensed under the MIT License. See the `LICENSE` file for details.

