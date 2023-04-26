# NEUROS Token Overview
The NEUROS token plays an important part of the Shockwaves ecosystem as it is used for staking, AI NFT rewards and in-game payments.

### Token Utility:
NFT Rewards, DAO & Voting, Staking, Farming, Liquidity Providing.

## Contract Details
`Neuros.sol` is an ERC20/BEP20 standard smart-contract named NEUROS. The contract inherits from the ERC20, ERC20Burnable, and Ownable contracts. The token can be used for any type of transactions on the BSC blockchain. The contract mints 100,000,000 NEUROS tokens to the address that deploys the contrat, and does not have the ability to mint any more tokens after the deployment. 

- <b>Network:</b> Binance Smart Chain (BEP20)
- <b>Token Name:</b> Neuros
- <b>Token Symbol:</b> NEUROS
- <b>Total Supply:</b> 100,000,000 (100 Millions)
- <b>Decimals:</b> 18

### Solidity
- <b>License:</b> `SPDX-License-Identifier: MIT`
- <b>Solidity Version:</b> `pragma solidity ^0.8.9;`
- <b>The Neuros.sol contract imports the following OpenZeppelin smart-contracts:</b><br>
`import "@openzeppelin/contracts/token/ERC20/ERC20.sol";`<br>
`import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol";`<br>
`import "@openzeppelin/contracts/access/Ownable.sol";`<br>
