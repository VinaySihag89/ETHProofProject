MyOwnToken Contract:

Description:
This is a basic ERC-20 token contract written in Solidity. It allows for the creation, management, and destruction of a custom token called "LOOT" (abbreviated as "LT").

Features:
Public Variables
tokenName: The name of the token, set to "LOOT".
tokenAbbrv: The abbreviation of the token, set to "LT".
totalSupply: The total supply of tokens, initialized to 0.
balances: A mapping of addresses to their corresponding token balances.

Functions:
'mint'
Takes two parameters: _address and _value.
Increases the totalSupply by _value.
Increases the balance of the _address by _value.

'burn'
Takes two parameters: _address and _value.
Checks if the balance of _address is greater than or equal to _value.
If true, decreases the totalSupply by _value.
Decreases the balance of _address by _value.

Usage:
To use this contract, you can deploy it to a compatible blockchain network (e.g., Ethereum) and interact with it using a Web3 library or a wallet interface.

Note:
This is a basic implementation and may not include all the features and security measures required for a production-ready token contract. Use at your own risk.
