# Indorse Airdrop Contract
This repo is for the Smart Contract used for Indorse airdrop.
The Smart Contract itself is quite simple, it has only one function which accepts 
- A token address
- Array of addresses to send tokens to
- Number of tokens to be sent

The contract itself is ownable and sends the tokens through a transfer function of a standard ERC20 token interface.

I could have made this contract transferFrom, but personally, I preferred to keep control over the damage that might occur 
by transferring only X number of tokens to this contract at a time.
