
# ERC20

This contract facilitates the minting, transferring, and burning of tokens from a wallet.


## Description

This Solidity smart contract enables the creation of a custom ERC20 token named "MINK" with the symbol "SLS" on the Ethereum blockchain. The contract provides functionalities for the owner to mint new tokens and allocate them to designated addresses, transfer tokens between addresses, and burn tokens. For security, the contract utilizes the OpenZeppelin ERC20 implementation.
 

## Requirements

To use this contract, you will need:

1)An Ethereum wallet (such as MetaMask) to interact with the contract

2)Some ETH to pay for gas fees on the Ethereum network
## Usage

1)Deploy the contract to the Ethereum network using Remix or another Solidity compiler. Make sure to set the name and symbol for your token.

2)Once the contract is deployed, call the mint function to create new tokens and assign them to an address. This function can only be called by the contract owner.

3)Use the transfer function to send tokens from one address to another.

4)Use the burn function to permanently remove tokens from circulation.
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

This contract is based on the OpenZeppelin ERC20 implementation and follows best practices for secure smart contract development. The contract was created for educational purposes only and should not be used in production without appropriate security audits and testing.
