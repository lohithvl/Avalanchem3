# ERC20 Token - LOHITH (AKM)

An ERC-20 contract for creating a fungible token on the Ethereum blockchain. This token adheres to the ERC-20 standard, ensuring compatibility with decentralized applications and exchanges.

## Description

This Solidity smart contract creates a custom ERC20 token named **LOHITH** with the symbol **AKM**. It provides standard token functions such as minting, transferring, and burning tokens. The contract leverages the OpenZeppelin ERC20 implementation to ensure robust security and best practices.

## Getting Started

### Installing

To interact with this contract:
1. Download or clone the contract files from the repository.
2. Ensure you have an Ethereum wallet like MetaMask installed.
3. Set up a Solidity development environment such as Remix or Truffle.

### Executing program

To deploy and use the contract:
1. Open the contract in Remix or your preferred IDE.
2. Compile the contract using the Solidity compiler.
3. Deploy the contract to the Ethereum network (Mainnet or Testnet).
4. Use the following steps to interact with the contract:
   * **Mint Tokens**: Only the owner can call the mint function to create new tokens.
   ```solidity
   function mint(address to, uint256 amount) public onlyOwner;
   ```
   * **Transfer Tokens**: Send tokens from one address to another.
   ```solidity
   function transfer(address recipient, uint256 amount) public;
   ```
   * **Burn Tokens**: Destroy tokens, reducing the total supply.
   ```solidity
   function burn(uint256 amount) public;
   ```

## Help

Common issues:
- Ensure that you have enough ETH in your wallet for gas fees.
- Use the correct contract address when interacting with it on-chain.
- For Remix, make sure to enable the Solidity plugin.
 

## License

This project is licensed under the **MIT License**. See the LICENSE file for details.

## Acknowledgements

The contract is based on the OpenZeppelin ERC20 implementation. It follows the standard practices for smart contract development and is intended for educational purposes. Use in production requires thorough testing and security audits.

--- 
