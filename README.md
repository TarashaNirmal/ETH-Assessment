'MyToken' is a simple token contract built on the Ethereum blockchain. This contract implements a token with basic minting and burining functionalities. The token, named "Delhi Capitals" with abbreviation "DC", allows for the creation and destruction of tokens, making it suitable for a variety of decentralized application and token management systems.

Token Name: Delhi Capitals
Token Abbreviation: DC
Initial Total Supply: 5

Here, Public variables 
1. tokenName: the name of the token i.e. Delhi capitals
2. totalAbbrv: The abbreviation of the token i.e. DC. 
3. totalSupply: The total supply of tokens initailly set to 5.
   
For mapping, here is balance which is a mapping that stores the balance of each address. This is in the form of 'mapping(address => uint)'.

Functions

1.mint: function mint(address _address, uint _value)public

here parameters are _address which is address where the token will be minted and _value which is the amount of token to mint.
This function increase the total supply of token and credit the specified address with the new tokens.

2. burn: function burn(address _address, uint _value)public
   
This function decrease the total supply of tokens and debits the specified address. It includes a check to ensure that the address has a sufficient balance to burn the requested amount of tokens.
