# Awesome Aptos [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## A Safe, Scalable, and Upgradeable Web3 Infrastructure
Welcome! [Aptos](https://aptoslabs.com/) is a Layer 1 for everyone. In the Ohlone language, "Aptos" means "The People."

Aptos blockchain natively integrates and internally uses the Move language for fast and secure transaction execution.

## Contents

- [Overview](#overview)
- [Books](#books)
- [Tutorials](#tutorials)
- [Community](#community)
- [Code](#code)
  - [Fungible Tokens](#fungible-tokens)
  - [Non-Fungible Tokens](#non-fungible-tokens)
  - [Tooling](#tooling)
  - [DeFi](#defi)
  - [SocialFi](#socialfi)
  - [Cross-Chain Bridge](#cross-chain-bridge)
  - [Frameworks](#frameworks)
  - [Miscellaneous](#miscellaneous)
- [IDEs](#ides)
- [Wallets](#wallets)
- [SDKs](#sdks)
- [Papers](#papers)
  - [Language Design](#language-design)
  - [Static Analysis and Verification](#static-analysis-and-verification)
- [Videos](#videos)
- [Security](#security)


## Overview

- [WhitePaper](https://aptos.dev/aptos-white-paper/)
- [Installation](https://aptos.dev/tools/install-cli/)

## Books
- [Move On Aptos](https://aptos.dev/move/move-on-aptos) - A book on the Sui Move variant maintained by [@aptos-labs](https://github.com/aptos-labs/)
- [Move Book](https://move-language.github.io/move/) - Move book maintained by the Move core team ([中文](https://github.com/move-language/move/tree/main/language/documentation/book/translations/move-book-zh)).
- [Move Book](https://move-book.com/) - Move book maintained by [@damirka](https://github.com/damirka) ([中文](https://move-book.com/cn/)).
- [Move Patterns](https://www.move-patterns.com/) - A book on Move software design patterns maintained by [@villesundell](https://github.com/villesundell).

## Tutorials
- [Your First Transaction](https://aptos.dev/tutorials/your-first-transaction) - Maintained by the Aptos Core Team
- [Your First NFT](https://aptos.dev/tutorials/your-first-nft) - Maintained by the Aptos Core Team
- [Your First Coin](https://aptos.dev/tutorials/your-first-coin) - Maintained by the Aptos Core Team
- [Your First Move Module](https://aptos.dev/tutorials/first-move-module) - Maintained by the Aptos Core Team
- [Your First Dapp](https://aptos.dev/tutorials/your-first-dapp) - Maintained by the Aptos Core Team
- [Your First Multsig](https://aptos.dev/tutorials/your-first-multisig) - Maintained by the Aptos Core Team
- [Implementing, testing, and verifying a fungible token](https://github.com/move-language/move/tree/main/language/documentation/tutorial) - Maintained by the Move core team.

## Code

Code written in Move.

### Fungible Tokens
- [Fungible token Examples](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/move-examples/moon_coin) - Examples by Aptos.

### Non-Fungible Tokens
- [Non-Fungible Examples](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/move-examples/mint_nft) - Examples by Aptos.

### NFT 
- [Souffl3](https://souffl3.com/) - NFT Marketplace on Aptos and Sui 
- [Topaz](https://www.topaz.so/) - NFT Marketplace 
- [Seashrine](https://seashrine.io) - NFT Marketplace 

### Tooling
- [Aptos Name Service](https://www.aptosnames.com/) - Name Service on Aptos
- [AptosFaucet](https://www.aptosfaucet.com) - A faucet Tool on Aptos

### DeFI
- [PancakeSwap](https://aptos.pancakeswap.finance/swap)
- [Pontem Network](https://pontem.network)
- [Pontem Network](https://pontem.network)
- [Starswap]((https://starswap.xyz/)
- [Cetus](https://www.cetus.zone/)
- [AnimeSwap](AnimeSwap)

### SocialFi
- [TowneSquare](https://www.townesquare.xyz/)

### Cross-Chain Bridge
- [Axelar](https://axelar.network/)
- [Celer](https://www.celer.network/)
- [LayerZero](https://layerzero.network/)
- [Multichain](https://multichain.org/)
- [Wormhole](https://wormhole.com/)

### Frameworks

- [Aptos Framework](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework)
- [Aptos Stdlib](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework/aptos-stdlib)
- [Aptos Token Objects](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework/aptos-token-objects)
- [Aptos Token](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework/aptos-token)

### Miscellaneous
- [Move-on-EVM](https://github.com/move-language/move/tree/main/language/evm) - Experimental project to compile Move source code to EVM bytecode.

## Community
- [Move Language Discord](https://discord.gg/cPUmhe24Mz)
- [Move @ Aptos by Aptos-labs Discord]()

## IDEs
- [Move VS Code plugin](https://marketplace.visualstudio.com/items?itemName=move.move-analyzer) - Maintained by the Move core team ([source code](https://github.com/move-language/move/tree/main/language/move-analyzer)).
- [Move IntelliJ plugin](https://plugins.jetbrains.com/plugin/14721-move-language) - Maintained by the Pontem team ([source code](https://github.com/pontem-network/intellij-move)).
- [Move Playground](https://playground.pontem.network/) - Like [Remix](https://remix.ethereum.org/) for Move. Alpha version of a Web IDE. See [instructions](https://gist.github.com/borispovod/64b6d23741d8c1f4b0b958a3a74aa68d). Maintained by the Pontem team.
- [Starcoin IDE](https://marketplace.visualstudio.com/items?itemName=starcoinorg.starcoin-ide) - Maintained by the Starcoin team ([source code](https://github.com/starcoinorg/starcoin-ide)).
- [Move Vim](https://github.com/rvmelkonian/move.vim) - Maintained by [@rvmelkonian](https://github.com/rvmelkonian/).
- [move-mode](https://github.com/amnn/move-mode) - Major mode for Emacs maintained by [@amnn](https://github.com/amnn/).

## Wallets
- [Petra Aptos Wallet](https://petra.app/) - Petra wallet is an extension that lets you explore Aptos in your browser. Made by Aptos Labs ([Chrome Webstore](https://chrome.google.com/webstore/detail/petra-aptos-wallet/ejjladinnckdgjemekebdpeokbikhfci)).
- [bcs-js](https://github.com/pontem-network/lcs-js) - JavaScript implementation of the [BCS](https://github.com/diem/bcs) serialization scheme used by Move, may be useful for implementing wallets.
- [ComingChat](https://coming.chat/) - A decentralized social finance/web3 portal.  Supporting public chain wallets, such as Sui and Aptos wallets.
- [Pontem Wallet](https://github.com/pontem-network/pontem-wallet) - Wallet extension for Aptos network by the Pontem team ([Chrome Webstore](https://chrome.google.com/webstore/detail/pontem-wallet/phkbamefinggmakgklpkljjmgibohnba)).
- [Fewcha Aptos Wallet](https://github.com/fewcha-wallet/fewcha.app) - The wallet of layer 1 blockchain Aptos ([Chrome Webstore](https://chrome.google.com/webstore/detail/fewcha-aptos-wallet/ebfidpplhabeedpnhjnobghokpiioolj)).
- [StarMask](https://github.com/starcoinorg/starmask-extension) - A wallet for the Starcoin blockchain. Maintained by the Starcoin team ([Chrome Webstore](https://chrome.google.com/webstore/detail/starmask/mfhbebgoclkghebffdldpobeajmbecfk?hl=en)).
- [Martian](https://martianwallet.xyz/) - Self custodial web3 wallet for Sui blockchain and Aptos. Safely explore the Aptos and Sui ecosystem by the KEYGEN LABS ([Chrome Webstore](https://chrome.google.com/webstore/detail/martian-wallet-for-sui-ap/efbglgofoippbgcjepnhiblaibcnclgk))
- [Rise](https://risewallet.io/) - A secure and powerful crypto wallet that brings all of the benefits of Aptos to you. Rise by the Solrise Finance ([Chrome Webstore](https://chrome.google.com/webstore/detail/rise-aptos-wallet/hbbgbephgojikajhfbomhlmmollphcad))
- [Onekey](http://onekey.so/) - Multi-Chain Support for BTC, ETH, BNB, NEAR & other Layer2 Networks.By the Onekey Team([Chrome Webstore](https://chrome.google.com/webstore/detail/jnmbobjmhlngoefaiojfljckilhhlhcj))

### Wallet Adapters
- [Aptos Wallet Adapter](https://github.com/aptos-labs/aptos-wallet-adapter) - A monorepo modular wallet adapter developed and maintained by Aptos for wallet and dapp builders 
- [Wallet Adapter](https://github.com/pontem-network/wallet-adapter) - 
React and Vue WalletProvider supporting loads of aptos wallets. Forked and featured with wallet provider based on Vue.js/Pinia.js from Hippo Wallet Adapter. By the Pontem.

## SDKs
- [Rust SDK](https://github.com/aptos-labs/aptos-core/tree/main/sdk) - by Aptos-Labs (official)
- [TypeScript SDK](https://github.com/aptos-labs/aptos-core/tree/main/ecosystem/typescript/sdk) - by Aptos-Labs (official)
- [Python SDK](https://github.com/aptos-labs/aptos-core/tree/main/ecosystem/python/sdk) - by Aptos-Labs (official)
- [Java SDK](https://github.com/wubuku/aptos-java-sdk) - by wubuku (community)
- [Unity SDK](https://github.com/aptos-labs/Aptos-Unity-SDK) - by Aptos-Labs (official)
- [Golang SDK](https://github.com/portto/aptos-go-sdk) - by portto (community)
- [Golang SDK](https://github.com/coming-chat/go-aptos-sdk) - by coming-chat (community)
- [Swift SDK](https://github.com/OpenDive/AptosKit) - by OpenDive (community)
- [Elixir SDK](https://github.com/NonceGeek/web3_aptos_ex) - by NonceGeek (community)

## Papers

### Language Design
- [Move: A Language With Programmable Resources](https://developers.diem.com/papers/diem-move-a-language-with-programmable-resources/2019-06-18.pdf) - This was the original Move white paper released in 2018. Many aspects of this are now out of date (e.g., the syntax and description of the bytecode instructions), but the first two sections are worth a read for explaining the difficulties of programming with assets and how Move tackles them.
- [Robust Safety for Move](https://arxiv.org/abs/2110.05043)
- [The Move Borrow Checker](https://arxiv.org/abs/2205.05181)
- [Resources: A Safe Language Abstraction for Money](https://arxiv.org/abs/2004.05106)

### Static Analysis and Verification

- [Fast and Reliable Formal Verification of Smart Contracts with the Move Prover](https://arxiv.org/abs/2110.08362)
- [The Move Prover](https://research.facebook.com/publications/the-move-prover/)
- [Verification of Programs Written in Libra's Move Language](https://ethz.ch/content/dam/ethz/special-interest/infk/chair-program-method/pm/documents/Education/Theses/Constantin_M%C3%BCller_MS_Report.pdf)
- [Exact and Linear-Time Gas-Cost Analysis](https://research.facebook.com/publications/exact-and-linear-time-gas-cost-analysis/)

## Videos

- [The Move Programming Language](https://youtu.be/J1U_0exNFu0)
- [Move on Sui](https://www.youtube.com/watch?v=xMsE1X4wio4)
- [Move on Aptos](https://www.youtube.com/watch?v=gvRJdJTQd8U)
- [Move: A Safe Language for Programming with Money](https://www.youtube.com/watch?v=EG2-7bQNPv4&ab_channel=FieldsInstitute) - Talk from [@sblackshear](https://github.com/sblackshear) at the [Fields Institute Blockchain](http://www.fields.utoronto.ca/activities/seminar_series/blockchain-research-seminar-series) research seminar series.
- [Formal Verification of Move Programs for the Libra Blockchain](http://www.fields.utoronto.ca/talks/Formal-verification-Move-programs-Libra-blockchain) - Talk from [@DavidLDill](https://github.com/DavidLDill) at the [Fields Institute Blockchain](http://www.fields.utoronto.ca/activities/seminar_series/blockchain-research-seminar-series) research seminar series.
- [Move for the Masses](https://www.youtube.com/watch?v=b_2jZ4YEfWc) - Talk at the [Converge '22](https://converge.circle.com/event/4ea0d06f-3900-4b6d-a9cd-aeaedda9ef2e/summary).


## Contributing

Contributions welcome! Read the contribution guidelines[](CONTRIBUTING.md) first.