# Royal Token (RT) Smart Contract

Royal Token (RT) is an Ethereum-based ERC-20 token with basic functionality. This smart contract allows an administrator to initialize the contract, mint new tokens, burn existing tokens, and transfer tokens. The token name is "Royal Token," and the symbol is "RT."

## Smart Contract Functions

### `initialize()`

Initialize the smart contract. This function sets the administrator and mints an initial supply of 200 RT tokens. It can only be called once.

### `Mint_Function(address userAddress, uint256 tokensToSend)`

Mint new RT tokens and assign them to the specified user address. Only the administrator can call this function.

### `Burn_Function(uint256 tokensToSend)`

Burn RT tokens, reducing the sender's token balance. Users can only burn their own tokens.

### `Transfer_Function(address toAddress, uint256 tokensToSend)`

Transfer RT tokens from the sender's address to the specified recipient address.

## Events

### `TokensEvent`

This event is emitted whenever tokens are minted, burned, or transferred. It includes information about the sender, recipient, and the number of tokens involved.

## Author 

YS Balaji

ysbalaji4@gmail.com
