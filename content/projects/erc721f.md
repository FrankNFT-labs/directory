---
name: ERC721F
description: >-
  A low-gas ERC-721 base contract for minting single and multiple NFTs,
  named by the CryptoPunks V1 community.
url: https://github.com/FrankNFT-labs/ERC721F
launchDate: 2022-03-02
tags:
  - Tool
  - Education
links:
  - https://www.npmjs.com/package/@franknft.eth/erc721-f
creators:
  - 4706
thumbnail: /projects/erc721f.png
---

ERC721F extends OpenZeppelin's ERC721 without ERC721Enumerable, and keeps `totalSupply()` and `walletOfOwner()`. Every token is written to storage when it is minted, so whoever buys it later does not pay for someone else's cheap batch mint. FrankNFT wrote it in March 2022 as a reply to Chiru Labs' ERC721A, which makes batch mints cheap and moves the cost to each token's first transfer.

The repo's own benchmark (May 2026) puts the saving against ERC721Enumerable at 36% for a single mint and 77% for a mint of a hundred. Version tags follow OpenZeppelin's, so ERC721F 5.7 goes with OpenZeppelin 5.7. The repo also ships a learning path of example contracts for new Solidity developers, starting with a free mint and ending with a Diamond proxy.

The punk connection is the name. FrankNFT wanted to call it ERC721B, and the CryptoPunks V1 crowd talked him out of it: "Are you crazy, call it F." F stands for Frank.
