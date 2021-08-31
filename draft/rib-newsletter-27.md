---
title: "RiB Newsletter #27"
description: "#22 - August 2021"
date: 2021-09-01
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #27 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #26](/newsletters/rib-newsletter-26/).

&nbsp;

It was a slow month, with few project updates, and few new projects.


## Thanks

Thanks to contributors:

[apalepu23],
[etovika],

_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.  If you
follow a particular project, or otherwise find information that is
beneficial to the Rust & blockchain community, please contribute to
the next issue by submitting a PR to the [next
draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[apalepu23]: https://github.com/apalepu23
[etovika]: https://github.com/etovika
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain
project. This month that project is…

[Stateright](https://github.com/stateright/stateright).

Stateright is a model checker for implementing distributed systems in Rust.
Unlike traditional model checkers like TLA+, Stateright is a Rust DSL,
and is able to check the Rust production implementation of a system.
It includes examples of Paxos and other simple algorithms.


&nbsp;


## Interesting Things

#### News

- Video: [Rust Cryptography Interest Group sync up call #4](https://youtu.be/uSqXIPWr4-4)

#### Blog Posts

- [Plookup — An Algorithm Widely Used in
  zkEVM](https://medium.com/@sin7y/plookup-an-algorithm-widely-used-in-zkevm-a88177777ca9)
- [Exploring Popular zkEVM Solutions: AppliedZKP, Matter Labs, Hermez,
  and
  Sin7Y](https://medium.com/@sin7y/exploring-popular-zkevm-solutions-appliedzkp-matter-labs-hermez-and-sin7y-d17deb1f8808)
- [Overview of the Rust cryptography
  ecosystem](https://kerkour.com/blog/rust-cryptography-ecosystem/)
- [Bridges in
  Crypto-Space](https://medium.com/chainsafe-systems/bridges-in-crypto-space-12e158f5fd1e)
- [Mitigating Miner Extractable Value (MEV) with Gnosis
  Safe](https://blog.gnosis.pm/gnosis-safe-mev-how-to-mitigate-it-347e13535e34)

#### Papers

- [Aggregating hash-based signatures using
  STARKs](https://eprint.iacr.org/2021/1048)
- [One-time Traceable Ring
  Signatures](https://eprint.iacr.org/2021/1054)
- [Aurora: a probabilistic algorithm for distributed ledgers enabling
  trustless synchronization and transaction inclusion
  verification](https://arxiv.org/abs/2108.08272)
- [Sharding-Based Proof-of-Stake Blockchain Protocols: Security
  Analysis](https://arxiv.org/abs/2108.05835)
- [Zero-Knowledge Middleboxes](https://eprint.iacr.org/2021/1022)
- [The Limits of Code
  Deference](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3889630)

#### Projects

- [YUL compiler](https://github.com/matter-labs/compiler-yul)

&nbsp;

## Most Active in August

[Solana](https://github.com/solana-labs/solana):
341 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
45 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
53 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Parity](https://github.com/paritytech):
262 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
91 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
88 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[Aleo](https://github.com/AleoHQ):
136 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 
54 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
45 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

136 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 
54 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
45 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

- [Announcing Aleo Setup](https://aleo.org/post/announcing-aleo-setup)

#### [ChainSafe](https://github.com/ChainSafe)

7 merged PRs ([1][chainsafe-merged-prs-1]), 
12 closed issues ([1][chainsafe-closed_issues-1]), 
10 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [COMIT](https://github.com/comit-network)

15 merged PRs ([1][comit-merged-prs-1]), 
16 closed issues ([1][comit-closed_issues-1]), 
24 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Concordium](https://github.com/Concordium)

20 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3]), 
7 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]), 
12 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Conflux](https://github.com/Conflux-Chain)

2 merged PRs ([1][conflux-merged-prs-1]), 
2 closed issues ([1][conflux-closed_issues-1]), 
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31

#### [Dfinity](https://github.com/dfinity)

35 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]), 
4 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4]), 
10 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[dfinity-merged-prs-4]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[dfinity-closed_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[dfinity-closed_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[dfinity-closed_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[dfinity-open_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[dfinity-open_issues-3]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Diem](https://github.com/diem)

143 merged PRs ([1][diem-merged-prs-1]), 
13 closed issues ([1][diem-closed_issues-1]), 
14 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Elrond](https://github.com/ElrondNetwork)

32 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2]), 
0 closed issues, 
0 open issues

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dns-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31

- [Smart contracts for a decentralized exchange in Rust](https://github.com/ElrondNetwork/sc-dex-rs)

#### [Fluence](https://github.com/fluencelabs)

24 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]), 
3 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2], [3][fluence-closed_issues-3]), 
6 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[fluence-closed_issues-2]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[fluence-closed_issues-3]: https://github.com/fluencelabs/marine-rs-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[fluence-open_issues-2]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[fluence-open_issues-3]: https://github.com/fluencelabs/marine-rs-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Golem](https://github.com/golemfactory)

20 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2]), 
16 closed issues ([1][golem-closed_issues-1]), 
7 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Grin](https://github.com/mimblewimble/grin)

3 merged PRs ([1][grin-merged-prs-1]), 
0 closed issues, 
0 open issues

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31

#### [Holochain](https://github.com/holochain/)

55 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]), 
0 closed issues, 
7 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[holochain-merged-prs-3]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[holochain-open_issues-2]: https://github.com/holochain/lair/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Interledger](https://github.com/interledger-rs)

4 merged PRs ([1][interledger-merged-prs-1]), 
0 closed issues, 
2 open issues ([1][interledger-open_issues-1])

[interledger-merged-prs-1]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[interledger-open_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [IOTA](https://github.com/iotaledger)

18 merged PRs ([1][iota-merged-prs-1]), 
4 closed issues ([1][iota-closed_issues-1]), 
9 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

7 merged PRs ([1][lighthouse-merged-prs-1]), 
20 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]), 
14 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

- [Understanding Attestation Packing Efficiencies](https://lighthouse.sigmaprime.io/attestation-packing.html)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

27 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]), 
0 closed issues, 
7 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/fog/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

121 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 
43 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
49 open issues ([1][near-open_issues-1], [2][near-open_issues-2])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[near-merged-prs-2]: https://github.com/near/borsh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[near-closed_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[near-open_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Nervos](https://github.com/nervosnetwork)

79 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]), 
18 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3]), 
8 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Parity](https://github.com/paritytech)

262 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
91 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
88 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[parity-open_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[parity-open_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

- [Network Stability Report: Kusama With Parachains](https://polkadot.network/network-stability-report-kusama-with-parachains/)
- [Making History: An Overview of the First Five Parachain Slot Auctions on Kusama](https://polkadot.network/making-history-an-overview-of-the-first-five-parachain-slot-auctions-on-kusama/)
- [Kusama Parachain Auctions: Second Batch](https://medium.com/polkadot-network/kusama-parachain-auctions-second-batch-161cc1ac7658)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

36 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3]), 
11 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]), 
10 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Rust Ethereum](https://github.com/rust-ethereum)

1 merged PRs ([1][rust_ethereum-merged-prs-1]), 
1 closed issues ([1][rust_ethereum-closed_issues-1]), 
3 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

22 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 
15 closed issues ([1][secret_network-closed_issues-1]), 
4 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[secret_network-merged-prs-2]: https://github.com/enigmampc/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

- [Secret Monero Bridge is Live on Mainnet](https://scrt.network/blog/secret-monero-bridge-is-live-on-mainnet)

#### [Solana](https://github.com/solana-labs/solana)

341 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
45 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
53 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

- [Announcing Breakpoint: the annual Solana conference](https://solana.com/news/announcing-breakpoint-the-annual-solana-conference)
- [Getting Started with Solana Development](https://solana.com/news/getting-started-with-solana-development)

#### [Spacemesh](https://github.com/spacemeshos)

19 merged PRs ([1][spacemesh-merged-prs-1]), 
47 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
80 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

#### [TezEdge](https://github.com/tezedge)

42 merged PRs ([1][tezedge-merged-prs-1]), 
0 closed issues, 
0 open issues

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31

#### [Zcash](https://github.com/zcash)

86 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
36 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
57 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

- [What would a Zcash Proof-of-Stake transition look like?](https://electriccoin.co/blog/what-would-a-zcash-proof-of-stake-transition-look-like/)
- [New releases to help enable Zcash Shielded by Default](https://electriccoin.co/blog/new-releases-to-help-enable-zcash-shielded-by-default/)

#### [zkSync](https://github.com/matter-labs/zksync)

5 merged PRs ([1][zksync-merged-prs-1]), 
3 closed issues ([1][zksync-closed_issues-1]), 
3 open issues ([1][zksync-open_issues-1])

[zksync-merged-prs-1]: https://github.com/matter-labs/zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-08-01..2021-08-31
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-08-01..2021-08-31
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2021-08-01..2021-08-31

- [Into the Unknown](https://medium.com/matter-labs/zksync-2-0-updates-1ae2b9bb9ff0)
- [zkSync 2.0 Developer Update](https://medium.com/matter-labs/zksync-2-0-developer-update-d25417f16446)

&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

Aug 31 - Oct 8 | Online

[Solana Hackathon: Ignition](https://solana.com/ignition)

Sep 6-10 | Online

[6th IEEE European Symposium on Security and Privacy](https://www.ieee-security.org/TC/EuroSP2021/index.html)

Sep 10 - Oct 4 | Online

[Nervos Hackathon: Broaden the Spectrum](https://gitcoin.co/hackathon/nervos-2/onboard)

Sep 14 | Online

[RustConf 2021](https://rustconf.com/)

Sep 18 | Online

[Rust Tokyo](https://rust.tokyo/)

Sep 26-28 | Online

[ACM Advances in Financial Technologies - AFT 2021](https://aft.acm.org/aft21/index.html)

Oct 4-8 | Darmstadt, Germany

[5th International Workshop on Cryptocurrencies and Blockchain Technology - CBT 2021](https://deic-web.uab.cat/conferences/dpm/cbt2021/)

Oct 6–8 | Darmstadt, Germany

[STM2021: The 17th International Workshop on Security and Trust Management](https://www.nics.uma.es/stm2021/)

Nov 18-19 | Online

[Tokenomics 2021: 3rd International Conference on Blockchain Economics, Security and Protocols](https://sites.google.com/nyu.edu/tokenomics2021)

Dec 1-3 | Seoul, Korea

[ICISC: The 24th Annual International Conference on information Security and Cryptology](http://www.icisc.org/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

ChainSafe | Toronto; Remote
- [Rust Developer](https://jobs.smartrecruiters.com/ChainSafeSystemsInc/743999739358248-rust-developer)

Dash Core Group | Remote
- [Database Engineer](http://jobs.dash.org/apply/fDSbW6F7PM/Database-Engineer-Rust)
- [Senior Database Engineer](http://jobs.dash.org/apply/yg93YShb9i/Senior-Database-Engineer-Rust)

DEX Labs | Remote
- [Rust Engineer](https://dex-labs.breezy.hr/p/fea339739adb-rust-engineer)

Dusk Network | Remote 
- [Rust Developer](https://dusk.network/pages/rust-developer-vacancy) with experience in WASM

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#28 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


