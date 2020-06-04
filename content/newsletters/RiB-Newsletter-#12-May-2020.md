---
title: "RiB Newsletter #12 – ZK-Rustups"
description: "#12 - May 2020"
date: 2020-06-03
slug: "/2020-06-03-zk-rustups"
categories:
  - "newsletters"
summary: Hey there and welcome to another month in the world of Rust blockchain. This month, what strikes us most is the proliferation of Rust cryptography, and especially zero-knowledge proof, projects. Even blockchains that aren't primarily implemented in Rust are increasingly looking to Rust for their crypto. So many of these are springing up that we've lost track, so we spent some time doing a survey of the world of Rust crypto and zero-knowledge proofs, and what we found kind of blew us away! For Rust blockchain developers there are an overwhelming number of choices for their crypto building blocks. Here are some of them.

---

Welcome to the #12 edition of Rust in Blockchain, the hypest newsletter about the hypest tech.
[Previous: #11](/newsletters/2020-05-06-the-flourishing-spring).

This month, what strikes us most is the proliferation of Rust cryptography, and
especially zero-knowledge proof, projects. Even blockchains that aren't
primarily implemented in Rust are increasingly looking to Rust for their crypto.
So many of these are springing up that we've lost track, so we spent some time
doing a survey of the world of Rust crypto and zero-knowledge proofs, and what
we found kind of blew us away! For Rust blockchain developers there are an
overwhelming number of choices for their crypto building blocks. Here are some
of them.

- Rust-crypto-specific GitHub orgs
  - [rustcrypto]: lots of well-maintained, basic crypto primitives and abstractions
  - [dalek-cryptography]: mature ed25519 and zkp implementations
  - [zkcrypto] maintains a number of zero-knowledge crates used by multiple projects, [bellman],
    [ff], [pairing], [group], [jubjub], [bls12_381].
  - [SCIPR Lab] has several zero-knowledge Rust projects, [zexe], for [decentralized private computation (paper)][zp],
    [poly-commit], for polynomial commitments, [marlin], for the [Marlin SNARK (paper)][ms], and [ripp], for [proofs of inner pairing products (paper)][ppro]
  - [KZen-networks] is another organization filled with Rust crypto, dedicated to threshold cryptography, [multi-party-ecdsa], [curv],
    [multi-party-schnorr], [class], [white-city], and more.
- Non-Rust blockchains using Rust for security and other purposes
  - [0xProject/OpenZKP]. A ZKP implementation by 0x Network.
  - [algorand/pointproofs]. An implementation of Algorand's [Pointproofs: Aggregating Proofs for Multiple Vector Commitments (paper)][pp].
  - [Stellar] has a separate Rust blockchain, [Slingshot], built on a zero-knowledge VM, [ZkVM],
    and containing several other interesting in-tree Rust crypto projects.
  - [dusk-network], a blockchain written in Go, has multiple Rust crypto projects, [phoenix], a ZK transaction model,
    [Poseidon252], a hash function, and many more. It apears that they support smart contracts written in Rust.
  - [Tendermint], another Go blockchain, also has many Rust crypto and security projects.
  - [Komodo], uses Rust for their cross-chain [AtomixDEX] matchmaking network.
  - [IOTA] is [developing some new projects in Rust][iod].
  - [Input-Output HK], contributors to Cardano and Ethereum Classic, have multiple Rust projects in Rust,
    including [jormungandr], a Rust blockchain that appears to be an implementation of Cardano in Rust.
  - The Ethereum community has many projects in Rust, as does Zcash, and there exist Bitcoin implementations in Rust.

By a rough counting, 13 of the top 50 blockchains by market cap are using Rust
in some way, whether primary implementations, alternate or unofficial
implementanions, libraries, support code, or research projects. Those projects
are: Bitcoin, Ethereum, Bitcoin Cash, Cardano, Stellar, Crypto.com, Ethereum
Classic, IOTA, Zcash, Ontology, 0x, Algorand, Qtum. While reviewing these it's
notable that while an increasing number of blockchain projects are _using_ Rust,
few of the top projects are _primarily implemented in_ Rust (the exception being
Crypto.com). Yet, of course.

[iod]: https://github.com/tendermint
[Tendermint]: https://github.com/tendermint
[ripp]: https://github.com/scipr-lab/ripp
[IOTA]: https://github.com/IOTAledger
[ZkVM]: https://github.com/stellar/slingshot/blob/main/zkvm
[Slingshot]: https://github.com/stellar/slingshot
[Stellar]: https://github.com/stellar
[jormungandr]: https://github.com/input-output-hk/jormungandr
[Input-Output HK]: https://github.com/input-output-hk
[Komodo]: https://github.com/KomodoPlatform/
[AtomixDEX]: https://github.com/KomodoPlatform/atomicDEX-API
[dalek-cryptography]: https://github.com/dalek-cryptography/
[rustcrypto]: https://github.com/rustcrypto
[Tednermint]: https://github.com/tendermint
[white-city]: https://github.com/KZen-networks/white-city
[class]: https://github.com/KZen-networks/class
[multi-party-schnorr]: https://github.com/KZen-networks/multi-party-schnorr
[curv]: https://github.com/KZen-networks/curv
[multi-party-ecdsa]: https://github.com/KZen-networks/multi-party-ecdsa
[KZen-networks]: https://github.com/KZen-networks
[Poseidon252]: https://github.com/dusk-network/Poseidon252
[phoenix]: https://github.com/dusk-network/phoenix
[dusk-network]: https://github.com/dusk-network
[0xProject/OpenZKP]: https://github.com/0xProject/OpenZKP
[algorand/pointproofs]: https://github.com/algorand/pointproofs
[pp]: https://eprint.iacr.org/2020/419
[SCIPR Lab]: https://github.com/scipr-lab
[zexe]: https://github.com/scipr-lab/zexe
[poly-commit]: https://github.com/scipr-lab/poly-commit
[marlin]: https://github.com/scipr-lab/marlin
[ms]: https://ia.cr/2019/1047
[ppro]: https://eprint.iacr.org/2019/1177
[zp]: https://ia.cr/2018/962
[zkcrypto]: https://github.com/zkcrypto
[bellman]: https://github.com/zkcrypto/bellman
[ff]: https://github.com/zkcrypto/ff
[pairing]: https://github.com/zkcrypto/pairing
[group]: https://github.com/zkcrypto/group
[jubjub]: https://github.com/zkcrypto/jubjub
[bls12_381]: https://github.com/zkcrypto/bls12_381
[groth16]: https://github.com/zkcrypto/groth16

This month Rust-behemoth Polkadot [launched their mainnet][pmn]. Congrats to Parity
and Polkadot contributors.

[pmn]: https://polkadot.network/web3-foundation-initiates-launch-polkadot-is-live/

&nbsp;

## Thanks

This edition of RiB was produced with contributions from [Anais Urlichs][contributorau], [Calvin Lau][contributorcl], Paulii Good, [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. If you follow a particular project, or otherwise find information that is beneficial to the Rust & blockchain community, please contribute to the next issue. Either submit a PR to the [#13 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorau]: https://github.com/AnaisUrlichs
[contributorcl]: https://github.com/calvinlauco
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[near/core-contracts].

The NEAR project is a blockchain written in Rust, that runs smart contracts
written in Rust, on a WASM VM. It's super-rusty. This recently-released project
provides well-documented examples of NEAR Rust contracts written with the [NEAR
SDK].

The NEAR developers are interested in any feedback about the experience
of writing smart contracts in Rust on NEAR.

[near/core-contracts]: https://github.com/near/core-contracts
[NEAR SDK]: https://github.com/near/near-sdk-rs

&nbsp;

## Interesting Things

- [zexe: Rust library for decentralized private computation](https://github.com/scipr-lab/zexe)
- [curv: Rust language general purpose elliptic curve cryptography](https://github.com/KZen-networks/curv)
- [OpenZKP: pure Rust implementations of Zero-Knowledge Proof systems](https://github.com/0xProject/OpenZKP)
- [marlin: A Rust library for the Marlin preprocessing zkSNARK](https://github.com/scipr-lab/marlin)
- [rusk-vm: The Dusk Rust WASM VM implementation](https://github.com/dusk-network/rusk-vm)
- [distaff](https://github.com/GuildOfWeavers/distaff), the new SNARK VM, posted two status updates
  ([1](https://ethresear.ch/t/distaff-vm-now-with-deep-fri/7459), [2](https://ethresear.ch/t/expanding-instruction-set-of-distaff-vm/7504)) to ethresear.ch
- [near-sdk-rs: Rust library for writing NEAR smart contracts](https://github.com/near/near-sdk-rs)
- [rainbow-bridge: NEAR bridge to Ethereum](https://github.com/near/rainbow-bridge)
- [ckb-boxer: Nervos CKB as a Rust library](https://github.com/xxuejie/ckb-boxer)
- [electrs: An Electrum server implementation](https://github.com/romanz/electrs)
- Blog: [Everything You Need to Know About Reddit's New Blockchain-Based Community Points](https://consensys.net/blog/news/everything-you-need-to-know-about-reddits-new-blockchain-based-community-points/)
  - Reddit is a collection of discussion boards (called subreddits) on various topics where members can upvote or downvote posts. It has an enormous (and devoted) userbase with 430 million monthly active users and 150 million pages visited each day.
  - Community points on the blockchain
- Blog: [The Problem With Grants](https://www.etherean.org/blockchain/economics/2020/05/10/the-problem-with-grants.html)
- Blog: [A Field Guide to zkSNARKs (Part I) : A Primer on Computation](https://write.as/knowledgeprover/zero-knowledge-proof-systems-a-primer)
- Blog: [A Rust Learning Group in the IOTA Ecosystem](https://medium.com/@huhn/a-rust-learning-group-in-the-iota-ecosystem-385a8a1d913e)
- Blog: [Opinion: On Private Blockchains](https://bitfalls.com/2020/05/25/opinion-on-private-blockchains/)
- Proposal: [Kin Improvement Proposal (Move to Solana)](https://github.com/kinecosystem/technology/blob/master/improvement-proposals/solana-migration.md)


&nbsp;

## Most Active in May

[**Solana**](https://github.com/solana-labs/solana): 
383 merged PRs ([1][solana-merged-prs-1]), 79 closed issues ([1][solana-closed_issues-1]), 60 open issues ([1][solana-open_issues-1])

[**Parity** ](https://github.com/paritytech): 
283 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2]), 128 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 
72 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[**COMIT**](https://comit.network/):
235 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3], [4][comit-merged-prs-4], [5][comit-merged-prs-5], [6][comit-merged-prs-6]), 72 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3], [4][comit-closed_issues-4]), 
32 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2], [3][comit-open_issues-3])

[**NEAR**](https://github.com/nearprotocol/nearcore):
79 merged PRs ([1][near-merged-prs-1]), 74 closed issues ([1][near-closed_issues-1]), 
51 open issues ([1][near-open_issues-1])

&nbsp;

## Project Updates

#### [CodeChain](https://github.com/codeChain-io/)

44 merged PRs ([1][codechain-merged-prs-1], [2][codechain-merged-prs-2]), 14 closed issues ([1][codechain-closed_issues-1]), 
8 open issues ([1][codechain-open_issues-1])

[codechain-merged-prs-1]: https://github.com/CodeChain-io/codechain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[codechain-merged-prs-2]: https://github.com/CodeChain-io/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[codechain-closed_issues-1]: https://github.com/CodeChain-io/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[codechain-open_issues-1]: https://github.com/CodeChain-io/codechain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02
[codechain-open_issues-2]: https://github.com/CodeChain-io/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- PR: [Implement Account module](https://github.com/CodeChain-io/foundry/pull/288) by [@somniumism](https://github.com/somniumism)
- PR: [Implement Staking module](https://github.com/CodeChain-io/foundry/pull/335) by [@HoOngEe](https://github.com/HoOngEe)

#### [COMIT](https://comit.network/)

235 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3], [4][comit-merged-prs-4], [5][comit-merged-prs-5], [6][comit-merged-prs-6]), 72 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3], [4][comit-closed_issues-4]), 
32 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2], [3][comit-open_issues-3])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[comit-merged-prs-2]: https://github.com/comit-network/comit-js-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[comit-merged-prs-3]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[comit-merged-prs-4]: https://github.com/comit-network/comit.network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[comit-merged-prs-5]: https://github.com/comit-network/a2l-poc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[comit-merged-prs-6]: https://github.com/comit-network/RFCs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[comit-closed_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[comit-closed_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[comit-closed_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[comit-closed_issues-4]: https://github.com/comit-network/comit.network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[comit-open_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02
[comit-open_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02
[comit-open_issues-3]: https://github.com/comit-network/comit.network/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- PR: [Add hbit module](https://github.com/comit-network/comit-rs/pull/2623) by [@tcharding](https://github.com/tcharding)
- PR: [Implement GET /swaps/:id (lightning)](https://github.com/comit-network/comit-rs/pull/2521) by [@tcharding](https://github.com/tcharding)
- PR: [Validate lnd invoice and payment against swap params](https://github.com/comit-network/comit-rs/pull/2573) by [@rishflab](https://github.com/rishflab)
- PR: [Bob does not reject announcement if the swap is not yet created](https://github.com/comit-network/comit-rs/pull/2583) by [@D4nte](https://github.com/D4nte)
- PR: [Replace `parity` config section with `web3_url`](https://github.com/comit-network/comit-rs/pull/2575) by [@D4nte](https://github.com/D4nte)


#### [Crypto.com Chain](https://chain.crypto.com)

114 merged PRs ([1][crypto.com-merged-prs-1], [2][crypto.com-merged-prs-2], [3][crypto.com-merged-prs-3]), 65 closed issues ([1][crypto.com-closed_issues-1], [2][crypto.com-closed_issues-2]), 29 open issues ([1][crypto.com-open_issues-1], [2][crypto.com-open_issues-2])

[crypto.com-merged-prs-1]: https://github.com/crypto-com/chain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[crypto.com-merged-prs-2]: https://github.com/crypto-com/cro-nodelib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[crypto.com-merged-prs-3]: https://github.com/crypto-com/sample-chain-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[crypto.com-closed_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[crypto.com-closed_issues-2]: https://github.com/crypto-com/sample-chain-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[crypto.com-open_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02
[crypto.com-open_issues-2]: https://github.com/crypto-com/sample-chain-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [Crypto.com Chain Dev Update #9](https://blog.crypto.com/crypto-com-chain-dev-update-9)
  - [Testnet Upgraded to v0.5](https://blog.crypto.com/crypto-com-chain-dev-update-9/#new-binary-release-and-testnet-upgrade)  
  - Further information: [Changelog](https://github.com/crypto-com/chain/blob/release/v0.5/CHANGELOG.md#v053), [Release](https://github.com/crypto-com/chain/releases), [Documentation](https://crypto-com.github.io/getting-started/thaler-testnet.html), [Block Explorer](https://chain.crypto.com/explorer), [Sample Wallet UI](https://github.com/crypto-com/sample-chain-wallet)
- News: [Node.js](https://github.com/crypto-com/cro-nodelib) library supports more transaction types. It is using Neon bindings to Rust code.
- Doc update: [Stabilized Transaction Test Vectors](https://crypto-com.github.io/getting-started/serialization.html#test-vectors) are now documented.
- PR: [Problem: tx-query not yet ported to EDP](https://github.com/crypto-com/chain/pull/1494) by [@devashishdxt](https://github.com/devashishdxt)
- PR: [Problem (#1483): client rpc setup code is duplicated between server and c-api](https://github.com/crypto-com/chain/pull/1619) by [@yihuang](https://github.com/yihuang)
- PR: [Problem: (fix #1545)light client doesn't verify genesis hash](https://github.com/crypto-com/chain/pull/1594) by [@linfeng-crypto](https://github.com/linfeng-crypto)

#### [Golem](https://golem.network/)

15 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]), 21 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3]), 
4 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/gwasm-runner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[golem-merged-prs-2]: https://github.com/golemfactory/golem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[golem-merged-prs-3]: https://github.com/golemfactory/sp-wasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[golem-merged-prs-4]: https://github.com/golemfactory/g-flite/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[golem-merged-prs-5]: https://github.com/golemfactory/golem-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[golem-closed_issues-1]: https://github.com/golemfactory/gwasm-runner/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[golem-closed_issues-2]: https://github.com/golemfactory/golem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[golem-closed_issues-3]: https://github.com/golemfactory/golem-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[golem-open_issues-1]: https://github.com/golemfactory/golem/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [Clay Golem Beta 0.23.1](https://blog.golemproject.net/clay_beta_23_1/)
- Blog: [ReadyLayerOne - The next milestone: A Golem (R)evolution Synopsis](https://blog.golemproject.net/the-next-milestone-a-golem-r-evolution-synopsis/)
- Blog: [Solving Challenges in Golem with gWASM](https://blog.golemproject.net/solving-challenges-in-golem-with-gwasm/)
- Blog: [Summary of the Golem AMA May 2020](https://blog.golemproject.net/summary-of-the-golem-ama-may-2020/)
- PR: [Wasi](https://github.com/golemfactory/gwasm-runner/pull/47) by [@prekucki](https://github.com/prekucki)
- PR: [Wasi support rewrite for master](https://github.com/golemfactory/gwasm-runner/pull/51) by [@prekucki](https://github.com/prekucki)

#### [Holochain](https://github.com/holochain/)

5 merged PRs ([1][holochain-merged-prs-1]), 1 closed issues ([1][holochain-closed_issues-1]), 
2 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[holochain-closed_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[holochain-open_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [Monthly Roundup for Holo & Holochain](https://medium.com/h-o-l-o/monthly-roundup-for-holo-holochain-9c89a8fc8747)
  - Infrastructure Challenges, Holo Web SDK, More HoloFuel Speedups, H-Wiki Goes Public
- News: [Holochain Dev Pulse 72: Play with a mutual credit currency and join the modularity discussion](https://blog.holochain.org/play-with-a-mutual-credit-currency-and-join-the-modularity-discussion/)
  - Play a mutual credit currency game with other Holochain users
  - Dig deep into hApp dev best practices with the community
  - Holochain v0.0.48 cancelled, Holochain v0.0.49 released
- News: [Holochain Dev Pulse 71: Yes, The Nano Is Still On Its Way](https://blog.holochain.org/dev-pulse-71-yes-the-nano-is-still-on-its-way/)
  - What’s happening with the HoloPort Nano?
  - HoloPort release with USB Reset tool
  - Watch for a new Holochain release soon
- Blog: [The Nextnet Series: Part 3 of 3: Unleashing the Power of Unenclosable Carriers](https://medium.com/holochain/unleashing-the-power-of-unenclosable-carriers-and-how-holochain-can-help-1a4d443aa844)
- Video: [Open 2020 webinar Mutual Credit Demo](https://www.youtube.com/watch?v=7_VhMTXxr24)
- PR: [Fix hold aspect bugs](https://github.com/holochain/holochain-rust/pull/2184) by [@zippy](https://github.com/zippy)
- PR: [bump futures for broken upstream dep in tokio (pin-utils).](https://github.com/holochain/holochain-rust/pull/2188) by [@zippy](https://github.com/zippy)
- PR: [don't re-fetch entries we've fetched within the last second](https://github.com/holochain/holochain-rust/pull/2185) by [@neonphog](https://github.com/neonphog)


#### [Libra](https://libra.org)

0 merged PRs (0), 33 closed issues ([1][libra-closed_issues-1]), 
51 open issues ([1][libra-open_issues-1])

[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [New JSON-RPC Libra client API: The gRPC API is being deprecated](https://libra.org/en-US/blog/new-json-rpc/)
- News: [Lead Maintainer, Maintainers, and Libra Improvement Proposal (LIP) announced](https://libra.org/en-US/blog/lip-maintainers/)
- News: [The Libra Association announces new members](https://libra.org/en-US/updates/new-members/)
- News: [The Libra Association appoints Robert Werner as General Counsel](https://libra.org/en-US/updates/general-counsel-announcement/)
- News: [Testnet push announcement for 5/20](https://community.libra.org/t/testnet-push-announcement-for-5-20/2841)
  - [Testnet is live](https://libra.org/en-US/developers/)
- Blog: [Digital wallets: Key concepts to know](https://libra.org/en-US/blog/digital-wallets-key-concepts/)


#### [Lighthouse](https://lighthouse.sigmaprime.io/)

87 merged PRs ([1][lighthouse-merged-prs-1]), 33 closed issues ([1][lighthouse-closed_issues-1]), 
29 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [Lighthouse Update #25](https://lighthouse.sigmaprime.io/update-25.html)
  - Key Management Implementation
  - Schlesi: The First Multiclient Testnet
  - External Security Review
- PR: [EIP-2335: Keystore](https://github.com/sigp/lighthouse/pull/1071) by [@paulhauner](https://github.com/paulhauner)
- PR: [Implement Slashing Protection](https://github.com/sigp/lighthouse/pull/1116) by [@michaelsproul](https://github.com/michaelsproul)
- PR: [Add attestation gossip pre-verification](https://github.com/sigp/lighthouse/pull/983) by [@paulhauner](https://github.com/paulhauner)
- PR: [Wallet-based, encrypted key management](https://github.com/sigp/lighthouse/pull/1138) by [@paulhauner](https://github.com/paulhauner)
- PR: [Arbitrary trait for eth2/types](https://github.com/sigp/lighthouse/pull/1040) by [@kirk-baird](https://github.com/kirk-baird)
- PR: [EIP-2386 (draft): Eth2 wallet](https://github.com/sigp/lighthouse/pull/1117) by [@paulhauner](https://github.com/paulhauner)

#### [MobileCoin](https://www.mobilecoin.com/)

61 merged PRs ([1][mobilecoin-merged-prs-1]), 4 closed issues ([1][mobilecoin-closed_issues-1]), 
1 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinofficial/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinofficial/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[mobilecoin-open_issues-1]: https://github.com/mobilecoinofficial/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- PR: [Make Ristretto implement Kex, make CryptoBox generic over Kex](https://github.com/mobilecoinofficial/mobilecoin/pull/74) by [@garbageslam](https://github.com/garbageslam)
- PR: [Add watcher node and incorporate signatures into block explorer](https://github.com/mobilecoinofficial/mobilecoin/pull/147) by [@sugargoat](https://github.com/sugargoat)
- PR: [MC-1416 Infrastructure around llvm-bolt](https://github.com/mobilecoinofficial/mobilecoin/pull/142)

#### [NEAR](https://github.com/nearprotocol/nearcore)

79 merged PRs ([1][near-merged-prs-1]), 74 closed issues ([1][near-closed_issues-1]), 
51 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[near-closed_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[near-open_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [NEAR Hackathon at Ready Layer One: Winners Announced](https://near.org/blog/near-hackathon-at-ready-layer-one-winners-announced/)
- News: [Introducing the NEAR Foundation](https://near.org/blog/introducing-the-near-foundation/)
- News: [Community Update: May 22nd, 2020](https://near.org/blog/community-update-may-22nd-2020/)
  - Stake Wars
  - Flux <> NEAR
  - Hackathons
- Blog: [Future of Blockchain Hackathon](https://near.org/blog/future-of-blockchain-hackathon-near-recap/)
- Blog: [Stake Wars Episode II](https://near.org/blog/stake-wars-episode-ii/)
- Blog: [Ready Layer One Rewind](https://near.org/blog/ready-layer-one-rewind/)
- Blog: [Introducing 4 NEAR apps at Consensus Distributed](https://near.org/blog/introducing-4-apps-building-on-near-at-consensus-distributed/)
- Podcast: [Onboarding The 99% of Developers Into Web 3, Illia Polosukhin of NEAR](https://podcasts.apple.com/gb/podcast/onboarding-99-developers-into-web-3-illia-polosukhin/id1511782129?i=1000473941624)
- Podcast: [Ready Layer One: Who Competes With Ethereum?](https://unchainedpodcast.com/ready-layer-one-who-competes-with-ethereum/)
- Video: [Community Talk: The Rise of SoFi -- Introducing Personal Tokens](https://www.youtube.com/watch?v=wQu6En04_aA)
  - More [community talks](https://www.youtube.com/playlist?list=PL9tzQn_TEuFUmEmTQ80Mu9vCPu9a2v-V5)
- Video: [NEAR Engineering Weekly -- May 11, 2020](https://www.youtube.com/watch?v=Amsg_TOBWTk)
- PR: [Standalone runtime for testing](https://github.com/nearprotocol/nearcore/pull/2598) by [@fckt](https://github.com/fckt)
- PR: [Updated cost docs](https://github.com/nearprotocol/nearcore/pull/2655) by [@olonho](https://github.com/olonho)


#### [Nervos](https://github.com/nervosnetwork)

35 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]), 7 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
2 open issues ([1][nervos-open_issues-1], [2][nervos-closed_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[nervos-merged-prs-3]: https://github.com/nervosnetwork/rfcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[nervos-closed_issues-2]: https://github.com/nervosnetwork/rfcs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [Nervos Researcher Alan Szepieniec’s Paper Accepted by the International Association for Cryptologic Research (IACR)](https://medium.com/nervosnetwork/nervos-researcher-alan-szepieniecs-paper-accepted-by-the-international-association-for-cryptologic-71f7649229d6)
  - Paper: [Transparent SNARKs from DARK Compilers](https://eprint.iacr.org/2019/1229.pdf)
- News: Nervos CKB Development Update [#34][nervos-dev-34], [#35][nervos-dev-35]
  - The team is building dApp development frameworks: Capsule and Lumos. [Capsule](https://github.com/nervosnetwork/capsule) is a Rust based smart contract development framework.
  - Released [ckb-rich-node](https://github.com/ququzone/ckb-rich-node) for dApp backend data source
  - Optimized chain sync speed by 50%.
- News: [Synapse Extension v0.0.1 is Released](https://talk.nervos.org/t/synapse-extension-v0-0-1-is-released/4730)
- Blog: [Introducing Keyper for cell management on Nervos](https://medium.com/nervosnetwork/introducing-keyper-for-cell-management-on-nervos-8e5a8a42fa5f)
- Blog: [A Generic Payment Channel Construction and Its Composability](https://talk.nervos.org/t/a-generic-payment-channel-construction-and-its-composability/4697)
- Blog: [Explained: Best DEX Design & UDTswap for Nervos](https://blog.usejournal.com/explained-best-dex-design-udtswap-for-nervos-e899bdb432e5)
- Discussion: [The background reasoning on why Molecule was created #1](https://github.com/nervosnetwork/ckb-why-the-design/issues/1)
- Video: [Nervos Network (CKB) - Huge project for 2020/21. CKB to 100 x ?](https://www.youtube.com/watch?v=Lf9bpUy2y9c)
- Video: [Meet the Researchers of Nervos](https://www.youtube.com/watch?v=Qn3QkyjtRJA)
- Video: [Technical Dive into Nervos and SKALE Networks](https://www.crowdcast.io/e/layered-conversations-with-skale-and-nervos)
- PR: [Docs: add a document about how to build CKB on windows](https://github.com/nervosnetwork/ckb/pull/2077) by [@yangby-cryptape](https://github.com/yangby-cryptape)
- PR: [Feat: make minor change to pow algorithm for testnet](https://github.com/nervosnetwork/ckb/pull/2028) by [@yangby-cryptape](https://github.com/yangby-cryptape)
- PR: [Doc: Update syscall rfc to Lina mainnet setup](https://github.com/nervosnetwork/rfcs/pull/189) by [@xxuejie](https://github.com/xxuejie)

[nervos-dev-34]: https://medium.com/nervosnetwork/nervos-ckb-development-update-34-4bc796624ea4
[nervos-dev-35]: https://medium.com/nervosnetwork/nervos-ckb-development-update-35-d711f5c8b41e

#### [Parity](https://github.com/paritytech)

283 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2]), 128 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 
72 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [W3F Initiates Launch: Polkadot is Live](https://polkadot.network/web3-foundation-initiates-launch-polkadot-is-live/)
- News: [Westend: Introducing a New Testnet for Polkadot and Kusama](https://polkadot.network/westend-introducing-a-new-testnet-for-polkadot-and-kusama/)
- News: [Results of DOT Redenomination Referendum](https://polkadot.network/results-of-dot-redenomination-referendum/)
- News: [Build Polkadot: Network Launch Bounty Challenges](https://polkadot.network/build-polkadot-network-launch-bounty-challenges/)
- Blog: [An Updated Overview of Polkadot](https://polkadot.network/an-updated-overview-of-polkadot/)
- Blog: [What is Polkadot? A Brief Introduction](https://polkadot.network/what-is-polkadot-a-brief-introduction/)
- Blog: [Explaining the Polkadot Launch Process](https://polkadot.network/explaining-the-polkadot-launch-process/)
- Paper: [Overview of Polkadot and its Design Considerations](https://eprint.iacr.org/2020/641.pdf)
- Blog: [IoT on Substrate: Nodle.io](https://www.parity.io/iot-on-substrate-nodle-io/)
- PR: [Offchain storage lock](https://github.com/paritytech/substrate/pull/6010) by [@drahnr](https://github.com/drahnr)
- PR: [[CI] Expose WASM binaries on publish](https://github.com/paritytech/polkadot/pull/1093) by [@s3krit](https://github.com/s3krit)
- PR: [Pallet-contracts: State rent fixes](https://github.com/paritytech/substrate/pull/6147) by [@pepyakin](https://github.com/pepyakin)

#### [Solana](https://github.com/solana-labs/solana)

383 merged PRs ([1][solana-merged-prs-1]), 79 closed issues ([1][solana-closed_issues-1]), 
60 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [Solana Foundation Permanently Removes ◎11.365M From Token Supply](https://medium.com/solana-labs/solana-foundation-permanently-removes-11-365m-from-token-supply-dd58c8db8d0d)
  - Paper: [A Web-Scale Blockchain for Secure and Scalable Decentralized Apps and Marketplaces](https://research.binance.com/projects/solana)
- News: [Pocket Announces Its Integration With Solana, Providing Decentralized API Solutions For Developers](https://medium.com/solana-labs/pocket-announces-its-integration-with-solana-providing-decentralized-api-solutions-for-developers-a1b514459018)
- News: [Hummingbot Announces Support for Solana, Launches Liquidity Mining Campaign](https://medium.com/solana-labs/hummingbot-and-solana-team-up-to-launch-a-liquidity-mining-campaign-60d02bd2f607)
- PR: [Multi-version snapshot support](https://github.com/solana-labs/solana/pull/9980) by [@svenski123](https://github.com/svenski123)
- PR: [Cli: transfer ALL; check spend+fee in client](https://github.com/solana-labs/solana/pull/10012) by [@CriesofCarrots](https://github.com/CriesofCarrots)
- PR: [Introduce eager rent collection](https://github.com/solana-labs/solana/pull/9527) by [@ryoqun](https://github.com/ryoqun)

#### [Zcash](https://z.cash/)

42 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 11 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
14 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-05-01..2020-06-02
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[zcash-closed_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-05-01..2020-06-02
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02
[zcash-open_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aopen+created%3A2020-05-01..2020-06-02

- News: [The upside of quadratic funding for the Zcash ecosystem](https://electriccoin.co/blog/the-upside-of-quadratic-funding-for-the-zcash-ecosystem/)
- News: [The Zcash Foundation Welcomes Jane and Teor](https://www.zfnd.org/blog/welcome-jane-and-teor/)
- News: [Scaling Tor with Walking Onions](https://www.zfnd.org/blog/about-walking-onions/)
- News: [Bringing Privacy to Cosmos with Zcash](https://www.zfnd.org/blog/cosmos-pegzone-early-design/)
- News: Zcash Developers Update [05-01][zcash-dev-0501], [05-07][zcash-dev-0507], [05-22][zcash-dev-0522]
  - The [Zcash Documentation](https://zcash.readthedocs.io/en/latest/index.html) page got a refresh.
  - The team hosted the [Zcash Gardening Club](https://forum.zcashcommunity.com/t/gardening-club-may-recap/36444). The recording is up on [Youtube](https://www.youtube.com/watch?v=R5slrhMjAGk&t=532s)
  - Significant progress on Rust refactorings.
  - Improved TZE API in Rust.
- Blog: [Explaining viewing keys](https://electriccoin.co/blog/explaining-viewing-keys/)
- PR: [[ZIP 211] Disabling Addition of New Value to the Sprout Value Pool](https://github.com/zcash/zips/pull/214) by [@daira](https://github.com/daira)
- PR: [[ZIP 212] Allow recipient to derive Sapling ephemeral secret from note plaintext](https://github.com/zcash/zips/pull/222) by [@ebfull](https://github.com/ebfull)
- PR: [transaction/hash.rs: Add FromStr implementation (issue #299)](https://github.com/ZcashFoundation/zebra/pull/386) by [@kiminuo](https://github.com/kiminuo)

[zcash-dev-0501]: https://www.zcashcommunity.com/2020/05/01/zcash-developers-update-5-1-2020/  
[zcash-dev-0507]: https://www.zcashcommunity.com/2020/05/07/zcash-developers-update-5-7-2020/
[zcash-dev-0522]: https://www.zcashcommunity.com/2020/05/22/zcash-developers-update-5-22-2020/


&nbsp;

## Events

June 15 | Online

[Protect Privacy: Virtual hackathon starts June 15](https://electriccoin.co/blog/protect-privacy-virtual-hackathon-starts-june-15/)

Jun 17 | Barcelona, EU

[EthBarcelona](http://ethbarcelona.io/)

Aug 3-6, 2020 | Oxford, UK

[IEEE DAPPS 2020](https://ieeedapps.net/)

Aug 5, 2020 | Online

[DeFi Conference 2020](http://bitcoinevents.co.za/)

Oct 21-23 | NYC, US

[ACM Advances in Financial Technologies](https://aft.acm.org/)


&nbsp;

## Careers

Chainlink | Remote, US

[Developer Evangelist](https://careers.chain.link/o/developer-evangelist-global)

Definity | SF, US

[Software Engineer, SDK](https://boards.greenhouse.io/dfinity/jobs/4286745002)

[Senior Software Engineer - Infrastructure and Tools](https://boards.greenhouse.io/dfinity/jobs/4473085002)

Findora | CA, US

[Systems Engineer](https://jobs.lever.co/findora/88501a0d-a86d-4cd2-b0b7-8625a107b02b)

IOTA | Remote

[Software Engineer - Rust](https://iota.bamboohr.com/jobs/view.php?id=105)

Kraken | London, UK; Remote

[Backend Engineer, Kraken Futures](https://jobs.lever.co/kraken/fe1e07f4-6d7c-4f65-9a8f-27cf3b3fd2b1)

[Backend Engineer, Data Processing](https://jobs.lever.co/kraken/246f7fd2-000a-4f61-8f53-b1cc783d51cb)

Nervos | Remote

[Senior Blockchain Engineer & Developer Relations](https://angel.co/company/nervos-1/jobs/710826-developer-relations)

Ockam | Remote

[Software Architect - Applied Cryptography in Rust](https://www.ockam.io/team/Software-Architect-Applied-Cryptography-in-Rust/61e07e82-0589-51de-b250-42dbceb31c3c)

Polymath | Ontario; Remote

[Senior Rust Engineer](https://polymath.bamboohr.com/jobs/view.php?id=96)

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#13 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
