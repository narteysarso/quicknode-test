# Tonaton
A time-based auction marketplace. Think of it as ebay for blockchain where individuals
can create auctions for various NFTs, set an auction ellapse time, and a minimum bid amount 
for their auction. 
The auction charges 10 gwei for each auction which is deducted at the end of an auction when 
there is successful highest bidder.

Contract Address : 0x99b29F589b6112A50671C3b18dBA19779d877274
Test NFT Address: 0x2Bd06F74BE6A91A824c72cf7CB095DaE97B0c830

### Creating and starting an auction
- A user approves a selected NFT for the auction contract.
- The NFT contract address, tokenId and least bid amount are needed to create an auction.
- The created auction can be started for bidding.
