# Token Issuance

The protocol issues crypto tokens (ERC20 on the EVM compatible chains) that represent athletes in different sports (football, basketball, etc) or teams. These tokens are in fixed supply and are all sold by the protocol in an auction. For auctions we use a mechanism called Variable Rate Gradual Dutch Auctions (VRDA). Which next players are offered for tokenisation is the result of a governance vote by the governance token (SVC) holder. A new token can be issued if there is an adequate oracle available for it. Proceeds from token issuance are used for liquidity reserves and for future performance payouts. The newly minted tokens can be traded on a DEX or any other centralised exchange that wants to list them. This is outside of the scope of SVT protocol.



An entity with the permission to issue new tokens (DAO executor) can initiate the issuance of a new athlete token.\


Issuance process:

1. A vote is cast about what new SVT to issue
2. If all conditions are set (data source is available), the token sale can be initiated
3. 50% of the tokens are offered for sale at an auction. They may not be sold completely if there is a lack of demand.
4. Unsold tokens are kept in the treasury
5. The token is listed on the DEX, and liquidity is provided by the treasury
