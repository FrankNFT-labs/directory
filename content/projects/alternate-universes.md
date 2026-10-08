---
name: Alternate Universes
description: >-
  A wrapper that turns stranded Portion NFTs into standard ERC-1155 tokens,
  built after the Portion marketplace shut down.
url: https://alternate-universes.vercel.app
launchDate: 2024-02-12
tags:
  - Tool
  - Wrapper
links:
  - https://etherscan.io/address/0xC1A5F187F2d9f5590731D05F56aFFEAb183575AF
creators:
  - 4706
thumbnail: /projects/alternate-universes.png
---

Portion was an art marketplace and auction house on Ethereum. Its Alternate Universes artworks were issued as ERC-20 tokens. When Portion shut down in 2024, those tokens were stranded.

FrankNFT deployed the WrappedAlternateUniverses contract on 12 February 2024. It takes the original ERC-20 tokens into custody and mints an ERC-1155 token in return, one ID per artwork, and the holder can unwrap at any time to get the originals back. It covers four pieces: In search of Satori, Guardians of the galaxy, Buddha dreams in color, and The Doorway.

It is the same idea as the [CryptoPunks V1](/p/cryptopunks-v1) wrapper, applied to a different set of orphaned tokens.
