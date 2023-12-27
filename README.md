# How to Develop an NFT Smart Contract (ERC721)

This is a simple project but very powerful for beginners. [Here](https://docs.alchemy.com/docs/how-to-develop-an-nft-smart-contract-erc721-with-alchemy) you can find the full walkthrough. 

We developed and deployed our own NFT contract modifying the code retrieved from OpenZeppelin's wizard. This contract allows minting any NFT of the user's choice, just by passing the address to which they wish to mint it and the IPFS CID of the metadata:

[Here](https://sepolia.etherscan.io/address/0x7bcaba578b18940fc46dfb230587b930ab5482cf) you can see the deployed contract, which we used to [mint](https://sepolia.etherscan.io/tx/0x0b3690934b3398dea8d9a29e760864ca643d87c9a60219b6b899db099c12404b) an NFT with the following [metadata](https://ipfs.filebase.io/ipfs/QmPjspL9dMP2y8m38RRoRkUaTnRByRcsjLaiwg3dKAcNM9):
```JSON
{
  "description": "Friendly OpenSea Creature that enjoys long swims in the ocean.",
  "external_url": "https://openseacreatures.io/3",
  "image": "ipfs://QmQjiFSrqjdoYvLApuSQ7UymcL3QRkVxPAmy2SNSwP4ZK2",
  "name": "Cindy Starbelly",
  "attributes": [
    {
      "trait_type": "Base",
      "value": "Starfish"
    },
    {
      "trait_type": "Eyes",
      "value": "Big"
    },
    {
      "trait_type": "Mouth",
      "value": "Smiling"
    }
  ]
}
```
Then on OpenSea we could see our minted NFT:

<p align="center">
  <img src="https://github.com/arynyestos/RoadToWeb3ERC721/assets/33223441/7d4097f4-1c62-4135-adb8-ae0db1d99678">
</p>
