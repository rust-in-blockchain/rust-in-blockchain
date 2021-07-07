---
title: "RiB Newsletter #25 - Hello, Summer"
description: "#25 - June 2021"
date: 2021-07-07
slug: "/hello-summer"
categories:
  - "newsletters"
summary: Hello, Summer!
---

Welcome to the #25 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #24](/newsletters/bridges/).


&nbsp;

## Thanks

Thanks to contributors:
[convexitydmcc],
[haochizzle],
[jkdipeppe],
[Ken Carpenter],
[Manuel Mauro],
[Mikhail Zabaluev],
[Thomas Lisankie],
[Tony Arcieri],
[Brian Anderson],
and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#26 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[convexitydmcc]: https://github.com/convexitydmcc
[haochizzle]: https://github.com/haochizzle
[jkdipeppe]: https://github.com/jkdipeppe
[Ken Carpenter]: https://github.com/FoundationKen
[Manuel Mauro]: https://github.com/manuelmauro
[Mikhail Zabaluev]: https://github.com/mzabaluev
[Thomas Lisankie]: https://github.com/TomLisankie
[Tony Arcieri]: https://github.com/tarcieri
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[bip32.rs](https://github.com/iqlusioninc/crates/tree/main/bip32).

This is a pure Rust, generic, `no_std`-friendly implementation of
[BIP32] hierarchical deterministic wallets and BIP39 mnemonics.

[BIP32]: https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki

&nbsp;


## Interesting Things

#### Blog Posts

- All about [Zero-Knowledge Proofs](https://zkp.science/)
- [First impressions of Rust programming on Solana](https://brson.github.io/2021/06/08/rust-on-solana)
- [Interoperability Deep Dive: XCMP vs IBC vs Optics](https://alexeizamyatin.medium.com/interoperability-deep-dive-xcmp-vs-ibc-vs-optics-e365c72180cb)
- [On the optimization of PlonK](https://www.fluidex.io/en/blog/on-plonk/)
- [Optimizing Pairing-Based Cryptography: Montgomery Arithmetic in Rust](https://research.nccgroup.com/2021/06/09/optimizing-pairing-based-cryptography-montgomery-arithmetic-in-rust/)
- [Polygon: L2 or not L2?](https://adlrocha.substack.com/p/adlrocha-polygon-l2-or-not-l2)


#### Papers

- [A General Purpose Transpiler for Fully Homomorphic Encryption](https://arxiv.org/abs/2106.07893)
- [Asynchronous Data Dissemination and its Applications](https://eprint.iacr.org/2021/777)
- [DIV: Resolving the Dynamic Issues of Zero-knowledge Set Membership Proof in the Blockchain](https://dl.acm.org/doi/pdf/10.1145/3448016.3457248)
- [HEX-BLOOM: An Alternative to the Merkle Tree](https://eprint.iacr.org/2021/773)
- [VCProof: Constructing Shorter and Faster-to-Verify zkSNARKs with Vector Oracles](https://eprint.iacr.org/2021/710)
- [zkKYC: A solution concept for KYC without knowing your customer, leveraging self-sovereign identity and zero-knowledge proofs](https://eprint.iacr.org/2021/907)

#### Projects

- [Cupcake](https://github.com/facebookresearch/Cupcake).
  A Rust library for lattice-based additive homomorphic encryption.
- [Oramfs](https://github.com/kudelskisecurity/oramfs).
  ORAM filesystem written in Rust.
- [Rust `algonaut`](https://github.com/manuelmauro/algonaut).
  A rusty SDK for Algorand. It is currently working in progress.
- [Yatima](https://github.com/yatima-inc/yatima).
  A programming language for the decentralized web.

&nbsp;

## Most Active in June

[Parity](https://github.com/paritytech):
328 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5]),
129 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
128 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4])

[Solana](https://github.com/solana-labs/solana):
296 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
23 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
51 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Zcash](https://github.com/zcash):
136 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
44 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
88 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

88 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
57 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
33 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30


#### [ChainSafe](https://github.com/ChainSafe)

21 merged PRs ([1][chainsafe-merged-prs-1]),
32 closed issues ([1][chainsafe-closed_issues-1]), 
19 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

- [Back into the Forest: ChainSafe's Filecoin Rust implementation project update](https://medium.com/chainsafe-systems/back-into-the-forest-983a4344ffe9)
- [Realizing the Mina vision in Rust: ChainSafe's Mina Protocol Rust implementation announcement](https://medium.com/chainsafe-systems/realizing-the-mina-vision-in-rust-453f6f522205)

#### [COMIT](https://github.com/comit-network)

32 merged PRs ([1][comit-merged-prs-1]),
8 closed issues ([1][comit-closed_issues-1]), 
6 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Concordium](https://github.com/Concordium)

30 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
6 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2]), 
4 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

- [Concordium is live — First steps](https://medium.com/concordium/concordium-is-live-first-steps-edb128c0fb36)
- [Code Assessment of the Concordium Blockchain](https://research.kudelskisecurity.com/2021/06/04/code-assessment-of-the-concordium-blockchain)

#### [Conflux](https://github.com/Conflux-Chain)

18 merged PRs ([1][conflux-merged-prs-1]),
4 closed issues ([1][conflux-closed_issues-1]), 
5 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Dfinity](https://github.com/dfinity)

43 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
11 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5]), 
20 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[dfinity-merged-prs-4]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[dfinity-merged-prs-5]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[dfinity-closed_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[dfinity-closed_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[dfinity-closed_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[dfinity-closed_issues-5]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[dfinity-open_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[dfinity-open_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

- [Introducing the Internet Computer ‘Badlands’ Concept](https://medium.com/dfinity/introducing-the-internet-computer-badlands-concept-72e808482679)
- [Motoko, a Programming Language Designed for the Internet Computer, Is Now Open Source](https://medium.com/dfinity/motoko-a-programming-language-designed-for-the-internet-computer-is-now-open-source-8d85da4db735)

#### [Diem](https://github.com/diem)

141 merged PRs ([1][diem-merged-prs-1]),
22 closed issues ([1][diem-closed_issues-1]), 
26 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Elrond](https://github.com/ElrondNetwork)

22 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2]),
0 closed issues, 
0 open issues

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30

#### [Fluence](https://github.com/fluencelabs)

48 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]),
7 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2]), 
8 open issues ([1][fluence-open_issues-1])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[fluence-merged-prs-4]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[fluence-closed_issues-2]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Golem](https://github.com/golemfactory)

26 merged PRs ([1][golem-merged-prs-1]),
42 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]), 
28 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[golem-closed_issues-2]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Grin](https://github.com/mimblewimble/grin)

1 merged PRs ([1][grin-merged-prs-1]),
1 closed issues ([1][grin-closed_issues-1]), 
1 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Holochain](https://github.com/holochain/)

63 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4]),
3 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
4 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[holochain-merged-prs-4]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[holochain-closed_issues-2]: https://github.com/holochain/holochain-wasmer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Interledger](https://github.com/interledger-rs)

3 merged PRs ([1][interledger-merged-prs-1]),
1 closed issues ([1][interledger-closed_issues-1]), 
0 open issues

[interledger-merged-prs-1]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[interledger-closed_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30

#### [IOTA](https://github.com/iotaledger)

8 merged PRs ([1][iota-merged-prs-1]),
2 closed issues ([1][iota-closed_issues-1]), 
2 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Lighthouse](https://github.com/sigp/lighthouse)

9 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
23 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]), 
7 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [MobileCoin](https://github.com/mobilecoinfoundation)

15 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
3 closed issues ([1][mobilecoin-closed_issues-1]), 
3 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/fog/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [NEAR](https://github.com/nearprotocol/nearcore)

53 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]),
72 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
14 open issues ([1][near-open_issues-1], [2][near-open_issues-2])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[near-closed_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[near-open_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Nervos](https://github.com/nervosnetwork)

50 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]),
6 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3]), 
1 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[nervos-closed_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Oasis](https://github.com/oasislabs)

0 merged PRs, 0 closed issues, 
1 open issues ([1][oasis-open_issues-1])

[oasis-open_issues-1]: https://github.com/oasislabs/oasis-ethwasi-runtime/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30


#### [Parity](https://github.com/paritytech)
  
328 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5]),
129 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
128 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[parity-merged-prs-4]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[parity-closed_issues-3]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[parity-open_issues-4]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

- [Nominating and Validator Selection on Polkadot](https://medium.com/polkadot-network/nominating-and-validator-selection-on-polkadot-6c5c76cd6b9d)
- [Kusama Parachain Auctions](https://medium.com/polkadot-network/kusama-parachain-auctions-2e1e02e301c0)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

31 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2]),
15 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]), 
16 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Rust Ethereum](https://github.com/rust-ethereum)

1 merged PRs ([1][rust_ethereum-merged-prs-1]),
1 closed issues ([1][rust_ethereum-closed_issues-1]), 
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

2 merged PRs ([1][secret_network-merged-prs-1]),
1 closed issues ([1][secret_network-closed_issues-1]), 
3 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

- [Announcing the Secret Terra Bridge!](https://scrt.network/blog/announcing-secret-network-terra-bridge)

#### [Solana](https://github.com/solana-labs/solana)

296 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
23 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
51 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

- [RenVM Integrates with Solana for Interoperability](https://medium.com/renproject/renvm-integrates-with-solana-for-interoperability-cee10832356a)

#### [Spacemesh](https://github.com/spacemeshos)

6 merged PRs ([1][spacemesh-merged-prs-1], [2][spacemesh-merged-prs-2]),
35 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
27 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/go-spacemesh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[spacemesh-merged-prs-2]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [TezEdge](https://github.com/tezedge)

43 merged PRs ([1][tezedge-merged-prs-1]),
0 closed issues, 
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [Zcash](https://github.com/zcash)

136 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
44 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
88 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-06-01..2021-06-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs,
3 closed issues ([1][zksync-closed_issues-1]), 
3 open issues ([1][zksync-open_issues-1])

[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-06-01..2021-06-30
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2021-06-01..2021-06-30

&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

Sep 6-10 | Online

[6th IEEE European Symposium on Security and Privacy](https://www.ieee-security.org/TC/EuroSP2021/index.html)

Sep 14 | Online

[RustConf 2021](https://rustconf.com/).
[Submit your talk](https://cfp.rustconf.com/events/rustconf-2021) before Jul 11.

Sep 26-28 | Arlington, VA, US

[ACM Advances in Financial Technologies - AFT 2021](https://aft.acm.org/aft21/index.html)

Oct 4-8 | Darmstadt, Germany

[5th International Workshop on Cryptocurrencies and Blockchain Technology - CBT 2021](https://deic-web.uab.cat/conferences/dpm/cbt2021/)

Oct 6–8 | Darmstadt, Germany

[STM2021: The 17th International Workshop on Security and Trust Management](https://www.nics.uma.es/stm2021/)

Nov 18-19 | Online

[Tokenomics 2021: 3rd International Conference on Blockchain Economics, Security and Protocols](https://sites.google.com/nyu.edu/tokenomics2021)

Dec 3 | Seoul, Korea

[ICISC: The 24th Annual International Conference on information Security and Cryptology](http://www.icisc.org/)

&nbsp;

## Careers

<!--
Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)
-->

ChainSafe | Remote
- [Rust Developer](https://jobs.smartrecruiters.com/ChainSafeSystemsInc/743999739358248-rust-developer)

Convexity DMCC | Dubai, On Site & Remote
- [Smart Contract Engineer (Rust)](https://angel.co/company/convexity-dmcc/jobs/1453304-smart-contract-engineer-rust)

e^{i} Ventures | Remote
- [Senior Rust Smart Contract Engineer](https://angel.co/l/2vmk7m)

Foundation Devices | Boston, MA - San Diego, CA - Remote
- [Embedded Rust Engineer](https://angel.co/company/foundationdevices/jobs/1436754-embedded-rust-engineer)
- [Bitcoin Rust Engineer](https://angel.co/company/foundationdevices/jobs/1436755-bitcoin-rust-engineer)
- [Tools/Test/Build Software Engineer (Rust)](https://angel.co/company/foundationdevices/jobs/1436756-tools-test-build-software-engineer)

IO Global | Remote
- [Software Engineer - Rust](https://apply.workable.com/io-global/j/40A7923138/)
- [Software Engineering Lead - Rust](https://apply.workable.com/io-global/j/870698A849/)

Oxygen | Dubai or Remote
- [Rust Smart Contract Engineer](https://cryptocurrencyjobs.co/engineering/oxygen-smart-contract-engineer-rust/)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#26 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


