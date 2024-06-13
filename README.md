MyToken is a basic Solidity contract representing a custom token with functionalities to mint and burn tokens.

Requirements
Token Details: The contract stores public variables for the token name, token abbreviation, and total supply.
Balances Mapping: Utilizes a mapping of addresses to token balances.
Mint Function: Provides a function to mint new tokens, increasing the total supply and the balance of the specified address.
Burn Function: Implements a function to burn tokens, reducing the total supply and the balance of the specified address.
Burn Conditionals: Ensures the burn function only proceeds if the sender's balance is sufficient.
Usage
Deploy: Deploy the contract to your preferred Ethereum network.
Interact: Use the provided functions to mint or burn tokens as needed.
Verify Balances: Verify token balances using the balances mapping.
Monitor Total Supply: Keep track of the total token supply through the totalSupply variable.
Deployment
Compile the Solidity contract.
Deploy the compiled contract to your chosen Ethereum network.
Verify contract functionality through interaction with the deployed instance.
Example:-
// Deployed contract instance
MyToken myToken = MyToken();

// Mint tokens
myToken.mint(address, amount);

// Burn tokens
myToken.burn(address, amount);
