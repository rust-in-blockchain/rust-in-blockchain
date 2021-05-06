---
title: "RiB Newsletter #23"
description: "#23 - April 2021"
date: 2021-05-05
slug: "/"
categories:
  - "newsletters"
summary: ""
---

Welcome to the #23 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #22](/newsletters/_TODO_/).

This month we're rewriting things in Rust.
After hearing again [about TezEdge][teb],
an implementation of Tezos in Rust,
we are struck anew by the number of blockchains
that either have alternative implementations in Rust,
or that have rewritten their official implementations in Rust.

[teb]: https://medium.com/tezedge/the-tezedge-node-a-preview-of-whats-coming-up-ad353bc537c5

Let us count them:

- [Iota.rs](https://github.com/iotaledger/iota.rs).
  IOTA in Rust.
  Official client beta.
- [OpenEthereum](https://github.com/openethereum/openethereum).
  Ethereum in Rust.
  While Geth is often considered the "official" client,
  Ethereum purposefully has multiple implementations.
  Originally developed by Parity.
- [parity-bitcoin](https://github.com/paritytech/parity-bitcoin).
  Bitcoin in Rust.
  Includes support for Bitcoin Cash.
- [rust-bitcoin](https://github.com/rust-bitcoin).
  Bitcoin libraries in Rust.
  Not a full node.
- [rust-ethereum](https://github.com/rust-ethereum).
  Ethereum libraries in Rust.
  Includes a client, but it's not clear if it is a full node.
- [TezEdge](https://github.com/tezedge/tezedge).
  Tezos in Rust.
- [Yagna](https://github.com/golemfactory/yagna).
  Golem in Rust.
  Official client.
- [Zebra](https://github.com/ZcashFoundation/zebra).
  Zcash in Rust.
  By the Zcash Foundation.

So IOTA, Golem, and Zcash are rewriting in Rust,
or have finished rewriting in Rust.
Bitcoin, Ethereum, and Tezos have alternative implementations in Rust.
This must indicate something about Rust.
Have other blockchains rewritten in Rust,
or rewritten in languages that are not Rust?

&nbsp;

## Thanks

Thanks to contributors:
[Anthony DiPrinzio][contributorad],
[A Pruden][contributorap],
[J Wagstaff][contributorjw],
[James Prestwich][contributorjp],
[John Adler][contributorja],
[KauriHero][contributorkh],
[olesiah][contributorol],
[Tony Arcieri][contributorta],
[Wil Barnes][contributorwb],
[vinnyson][contributorv],
[Brian Anderson][contributorba], and [Aimee Zhu][contributoraz].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#24 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributorad]: https://github.com/adiprinzio
[contributorap]: https://github.com/apruden2008
[contributorjw]: https://github.com/rg3l3dr
[contributorjp]: https://github.com/prestwich
[contributorja]: https://github.com/adlerjohn
[contributorkh]: https://github.com/kauri-hero
[contributorol]: https://github.com/olesiah
[contributorta]: https://github.com/tarcieri
[contributorwb]: https://github.com/wilbarnes
[contributorv]: https://github.com/vinnyson
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[MASQ](https://github.com/MASQ-Project/Node).

MASQ is a mesh overlay network, somewhat like TOR, but with cryptoeconomic incentives for participation.

The [FAQ] contains some additional information.

[FAQ]: https://docs.masq.ai/knowledge/

&nbsp;


## Interesting Things

#### News

- [How Zero Knowledge Proofs Provide Privacy on the Blockchain](https://www.coindesk.com/video/how-zero-knowledge-proofs-provide-privacy-on-the-blockchain)
- [Signal Adds a Payments Feature — With a Privacy-Focused Cryptocurrency](https://www.wired.com/story/signal-mobilecoin-payments-messaging-cryptocurrency/)

#### Blog Posts

- [Decrypting Cryptography: Hash Functions](https://medium.com/zeroknowledge/decrypting-cryptography-hash-functions-5291d9139b9e)

#### Posts

- [Advice to a new programmer trying to get into rust blockchain programming](https://twitter.com/NewbieBrian/status/1386787136997888002)

#### Papers

- [A Tractable Probabilistic Approach to Analyze Sybil Attacks in Sharding-Based Blockchain Protocols](https://arxiv.org/abs/2104.07215)
- [Capability-based access control for multi-tenant systems using OAuth 2.0 and Verifiable Credentials](https://arxiv.org/abs/2104.11515)
- [Ethereum Name Service: the Good, the Bad, and the Ugly](https://cs.paperswithcode.com/paper/ethereum-name-service-the-good-the-bad-and)
- [ethSTARK Documentation](https://eprint.iacr.org/2021/582)
- [Forward-secure Multi-user Aggregate Signatures with Constant Complexities using Recursive zk-SNARKs](https://eprint.iacr.org/2021/567.pdf)
- [Post-Quantum Cryptography: Current state and quantum mitigation](https://www.enisa.europa.eu/publications/post-quantum-cryptography-current-state-and-quantum-mitigation)
- [RandChain: Practical Scalable Decentralized Randomness Attested by Blockchain](https://eprint.iacr.org/2021/450)
- [SnarkPack: Practical SNARK Aggregation](https://eprint.iacr.org/2021/529.pdf)
- [SCEW: Programmable BFT-Consensus with Smart Contracts for Client-Centric P2P Web Applications](https://dl.acm.org/doi/abs/10.1145/3447865.3457965)

#### Projects

- [Bit.Country](https://github.com/bit-country/Bit-Country-Blockchain).
  A blockchain network based on Substrate.
- [cosmos-sdk-rs](https://forum.cosmos.network/t/ann-cosmos-sdk-for-rust-v0-1-initial-release/4647).
  An implementation of the Cosmos SDK in Rust.
- [Chamomile](https://github.com/cypherlink/chamomile).
  A p2p library.
- [TDN](https://github.com/cypherlink/TDN).
  A p2p application framework.
- [Winterfell](https://github.com/novifinancial/winterfell).
  An experimental project for building a distributed STARK prover.

&nbsp;

## Most Active in April

[Parity](https://github.com/paritytech):
273 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
101 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
70 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[Solana](https://github.com/solana-labs/solana):
300 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
35 closed issues ([1][solana-closed_issues-1],[2][solana-closed_issues-2]), 
50 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Diem](https://github.com/diem):
144 merged PRs ([1][diem-merged-prs-1]),
21 closed issues ([1][diem-closed_issues-1]), 
14 open issues ([1][diem-open_issues-1])

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

96 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]),
50 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]), 
11 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[aleo-open_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

- News: [a16z Leads $28M Funding Round for Data Privacy Platform Aleo](https://www.coindesk.com/a16z-leads-funding-round-aleo-data-privacy-platform)
- Blog: [Discover Aleo](https://www.aleo.org/post/discover-aleo)

#### [COMIT](https://github.com/comit-network)

47 merged PRs ([1][comit-merged-prs-1]),
14 closed issues ([1][comit-closed_issues-1]), 
13 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Concordium](https://github.com/Concordium)

58 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
2 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2]), 
7 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Conflux](https://github.com/Conflux-Chain)

15 merged PRs ([1][conflux-merged-prs-1]),
6 closed issues ([1][conflux-closed_issues-1]), 
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

- Blog: [Understanding the Conflux Tree-Graph Consensus Algorithm](https://medium.com/conflux-network/understanding-the-conflux-tree-graph-consensus-algorithm-e1b57d5c3da9)

#### [Diem](https://github.com/diem)

144 merged PRs ([1][diem-merged-prs-1]),
21 closed issues ([1][diem-closed_issues-1]), 
14 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Elrond](https://github.com/ElrondNetwork)

26 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2],
[3][elrond-merged-prs-3]), 0 closed issues, 
0 open issues

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-dns-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30

#### [Fluence](https://github.com/fluencelabs)

41 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]),
1 closed issues ([1][fluence-closed_issues-1]), 
22 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3], [4][fluence-open_issues-4])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[fluence-merged-prs-2]: https://github.com/fluencelabs/fce/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[fluence-merged-prs-3]: https://github.com/fluencelabs/air/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[fluence-merged-prs-4]: https://github.com/fluencelabs/rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[fluence-open_issues-2]: https://github.com/fluencelabs/fce/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[fluence-open_issues-3]: https://github.com/fluencelabs/air/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[fluence-open_issues-4]: https://github.com/fluencelabs/rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

- Video: [Floating on Air and in Orbit](https://www.youtube.com/watch?v=AR8v5efuZEw&t=3643s)

#### [Golem](https://github.com/golemfactory)

34 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2]),
17 closed issues ([1][golem-closed_issues-1]), 
37 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Grin](https://github.com/mimblewimble/grin)

9 merged PRs ([1][grin-merged-prs-1]),
8 closed issues ([1][grin-closed_issues-1]), 
1 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Holochain](https://github.com/holochain/)

34 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]),
1 closed issues ([1][holochain-closed_issues-1]), 
3 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[holochain-merged-prs-3]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Interledger](https://github.com/interledger-rs)

10 merged PRs ([1][interledger-merged-prs-1]),
1 closed issues ([1][interledger-closed_issues-1]), 
3 open issues ([1][interledger-open_issues-1])

[interledger-merged-prs-1]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[interledger-closed_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[interledger-open_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [IOTA](https://github.com/iotaledger)

47 merged PRs ([1][iota-merged-prs-1]),
22 closed issues ([1][iota-closed_issues-1]), 
4 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Lighthouse](https://github.com/sigp/lighthouse)

3 merged PRs ([1][lighthouse-merged-prs-1]),
4 closed issues ([1][lighthouse-closed_issues-1]), 
6 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

- News: [Lighthouse Update #35](https://lighthouse.sigmaprime.io/update-35.html)
- Blog: [Why You Should Switch to Lighthouse](https://lighthouse.sigmaprime.io/switch-to-lighthouse.html)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

26 merged PRs ([1][mobilecoin-merged-prs-1]),
0 closed issues, 
3 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [NEAR](https://github.com/nearprotocol/nearcore)

61 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]),
20 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2]), 
34 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[near-closed_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

- News: [The Rainbow Bridge Is Live](https://near.org/blog/the-rainbow-bridge-is-live/)

#### [Nervos](https://github.com/nervosnetwork)

25 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]),
2 closed issues ([1][nervos-closed_issues-1]), 
2 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Oasis](https://github.com/oasislabs)

2 merged PRs ([1][oasis-merged-prs-1]),
0 closed issues, 
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/deoxysii-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30

#### [Parity](https://github.com/paritytech)

273 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
101 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
70 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[parity-open_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[parity-open_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

45 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3]),
6 closed issues ([1][rust_bitcoin-closed_issues-1]), 
14 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Rust Ethereum](https://github.com/rust-ethereum)

2 merged PRs ([1][rust-ethereum-merged-prs-1]),
1 closed issues ([1][rust-ethereum-closed_issues-1]), 
0 open issues

[rust-ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[rust-ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

6 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]),
2 closed issues ([1][secret_network-closed_issues-1]), 
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[secret_network-merged-prs-2]: https://github.com/enigmampc/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Solana](https://github.com/solana-labs/solana)

300 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
35 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
50 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [Spacemesh](https://github.com/spacemeshos)

3 merged PRs ([1][spacemesh-merged-prs-1], [2][spacemesh-merged-prs-2]),
12 closed issues ([1][spacemesh-closed_issues-1]), 
21 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/go-spacemesh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[spacemesh-merged-prs-2]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [TezEdge](https://github.com/tezedge)

12 merged PRs ([1][tezedge-merged-prs-1]),
0 closed issues, 
0 open issues

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30

- Blog: [The TezEdge node: a preview of what's coming up](https://medium.com/tezedge/the-tezedge-node-a-preview-of-whats-coming-up-ad353bc537c5)

#### [Zcash](https://github.com/zcash)

83 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
21 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
56 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-04-01..2021-04-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs,
3 closed issues ([1][zksync-closed_issues-1]), 
3 open issues ([1][zksync-open_issues-1])

[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-04-01..2021-04-30
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2021-04-01..2021-04-30

- Blog: [zkPorter: a breakthrough in L2 scaling](https://medium.com/matter-labs/zkporter-a-breakthrough-in-l2-scaling-ed5e48842fbf)


&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

May 10-13 | Online

[International Conference on Practice and Theory of Public-Key Cryptography](https://pkc.iacr.org/2021/)

May 15 - June 7 | Online

[Solana Season Hackathon](https://solana.com/solanaszn)

May 20 | Online

[Polkadot Decoded](https://decoded.polkadot.network/)

May 24-27 | Online

[42nd IEEE Symposium on Security and Privacy](https://www.ieee-security.org/TC/SP2021/index.html)

&nbsp;

## Careers

<!--
Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)
-->


Aleo | San Francisco, Remote
- [Senior Protocol Engineer](https://www.aleo.org/jobs/senior-protocol-engineer)
- [Senior Compiler Engineer](https://www.aleo.org/jobs/senior-compiler-engineer)
- [Full Stack Developer](https://www.aleo.org/jobs/full-stack-developer)
- [Interface Designer](https://www.aleo.org/jobs/interface-designer)

cLabs (Celo) | San Francisco, Berlin, or Remote
- [Senior Rust Smart Contract Engineer](https://jobs.lever.co/clabs/46bf6e13-ef54-4a5c-9287-2c0557ad9db4)

ElevenYellow | Remote
- [Rust Engineer](https://cryptocurrencyjobs.co/engineering/elevenyellow-rust-developer/)

Fuel Labs | Remote
- [Senior Software Engineer [Rust]](https://jobs.lever.co/fuellabs/13b01903-490a-4497-b778-35434f4188cf)

Jet Protocol | Remote
- [Rust Blockchain Engineer](https://docs.google.com/document/d/1GXuk2LPxoYxIdQGwsL9IZ34B7WjlgkdJBgY7QBgBIn0)

Subspace Labs | Remote
- [Core Protocol Engineer](https://jobs.lever.co/subspacelabs/7f6a654b-60a8-4740-aa19-36b9f7a9e624)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#24 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain

