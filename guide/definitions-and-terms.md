# Definitions & Terms

<details>

<summary>Market cap</summary>

Monitors the value of certain NFT collections from the network and sum them together to get the total value of NFT assets

</details>

<details>

<summary>Price</summary>

NFT’s price is currently bound to ETH, which can also be purchased with digital currency. We can provide price of NFT by querying the real-time exchange rate from some authoritative exchange.

</details>

<details>

<summary>Transaction</summary>

Auction , Matchmaking and Transfers are main types of NFT transaction. We monitor the number of transactions related to NFT assets on the chain, then classify and record the corresponding dataset.

</details>

<details>

<summary>Trader</summary>

Traders are the most important participants in NFT market and constitute an important part of trading data. Traders can be divided into buyers and sellers. We use transaction price as seller's revenue (sales volume) and buyer's cost (purchase volume).

</details>

<details>

<summary>Holder</summary>

A person who has owned an NFT asset can be called a holder. Both former owners of NFT assets and current owners of NFT assets have varying degrees of influence on the value of the overall market. In the future transaction, we can make reference according to the transaction record of the past holder.

</details>

<details>

<summary>Liquidity</summary>

NFT Liquidity Calculation FormulaERC721 (in any given period)：the number of NFT transactions within the project / total number of NFT issued(The ERC721 is Ethereum's first standard for NFT digital assets for non-exchangeable tokens, used in projects such as CryptoKitties, Decentraland, etc. The ERC721 standard was created and published by CryptoKitties CTO Dieter Shirley, one of the founders of NFT.The advantages of assets under ERC721 are the security of ownership, ease of transfer of ownership, and immutable and transparent ownership history. In addition, ERC721 facilitates the tracking, trading and management of real assets, and more. The ERC721 protocol has a bright future as gaming virtual assets continue to grow in popularity, 5G and VR become ubiquitous, and blockchain technology is enabled.)ERC1155 (in any given period)：

* Token ID Liquidity: the number of transactions of this token ID / total amount issued of this token ID
* Project Liquidity: ∑ token ID liquidity \* the amount issued / total amount issued of all token IDs.
* Liquidity of a certain type = ∑liquidity of each project under this type \* the number of transactions / total number of transactions of all projects under this type

(Compared to ERC721 and other standards, the ERC-1155 token protocol standard stands out in that it is cross-chain compatible. Until now, most of a user's assets were only available on the Ethereum blockchain, however the ERC-1155 standard also made their assets compatible with other ecosystems, and being able to operate across multiple blockchains seemed the only way forward.)

###

</details>
