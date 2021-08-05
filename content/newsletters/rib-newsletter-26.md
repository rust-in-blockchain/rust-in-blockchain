---
title: "RiB Newsletter #26"
description: "#26 - July 2021"
date: 2021-08-04
categories:
  - "newsletters"
summary: "Welcome to the #26 edition of Rust in Blockchain!
This month we spotlight project
`jsonrpsee`, an async implementation of JSON-RPC."
---

Welcome to the #26 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #25](/newsletters/hello-summer/).

&nbsp;

## Thanks

Thanks to contributors:
[Ernest Kissiedu],
[haochizzle],
[Max Wegman],
[Pranay Mohan],
[Pratyush Mishra],
[Brian Anderson],
and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Ernest Kissiedu]: https://github.com/ernestkissiedu
[haochizzle]: https://github.com/haochizzle
[Max Wegman]: https://github.com/mastermaxy
[Pranay Mohan]: https://github.com/pranaymohan
[Pratyush Mishra]: https://github.com/Pratyush
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain
project. This month that project is…

[jsonrpsee].

This is an async implementation of [JSON-RPC],
from Parity,
who also created the popular [jsonrpc] crate.

[jsonrpsee]: https://github.com/paritytech/jsonrpsee
[JSON-RPC]: https://www.jsonrpc.org/specification
[jsonrpc]: https://github.com/paritytech/jsonrpc/


&nbsp;


## Interesting Things

#### News

- [Gnosis client development team Joins Erigon (formerly Turbo-Geth) to Release Next-Gen Ethereum
  Client](https://medium.com/openethereum/gnosis-joins-erigon-formerly-turbo-geth-to-release-next-gen-ethereum-client-c6708dd06dd).
  Gnosis deprecates OpenEthereum.

#### Blog Posts

- [2021 Altcoin Node Sync Tests](https://blog.lopp.net/2021-altcoin-node-sync-tests/)
- [Demystifying recursive zero-knowledge proofs](https://anoma.network/blog/demystifying-recursive-zkp/)
- [Awesome Unstable Rust Features](https://lazy.codes/posts/awesome-unstable-rust-features/)

#### Papers

- [Kadcast-NG: A Structured Broadcast Protocol for Blockchain Networks](https://eprint.iacr.org/2021/996)
- [AToM: Active Topology Monitoring for the Bitcoin Peer-to-Peer Network](https://arxiv.org/abs/2107.12912)
- [Stochastic Modelling of Blockchain Consensus](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3865040)
- [Proof-of-Stake Mining Games with Perfect Randomness](https://dl.acm.org/doi/10.1145/3465456.3467636)
- [Darlin: A proof carrying data scheme based on Marlin](https://eprint.iacr.org/2021/930)
- [Layer 2 Blockchain Scaling: a Survey](https://arxiv.org/abs/2107.10881v1)

#### Projects

- [Anoma](https://github.com/anoma/anoma).
  Implementation of the Anoma protocol in Rust.
  Anoma is a sovereign, proof-of-stake blockchain protocol
  that enables private, asset-agnostic cash and private bartering among
  any number of parties.
  The paper: [Anoma: Undefining Money](https://anoma.network/papers/vision-paper.pdf).
- [Nova](https://github.com/microsoft/Nova).
  Recursive SNARKs without trusted setup.
- [Winterfell](https://github.com/novifinancial/winterfell).
  A STARK prover and verifier for arbitrary computations.
- [The LibraBFT Simulator](https://github.com/novifinancial/librabft_simulator).
  Discrete-Event Simulation for BFT Consensus Protocols.
- [jsonrpsee](https://github.com/paritytech/jsonrpsee).
  JSON-RPC library designed for async/await in Rust.
  Designed to be the successor to ParityTech's JSONRPC crate.
- [Rust Cryptography Interest Group (RCIG): Awesome Rust Cryptography](https://github.com/The-DevX-Initiative/RCIG_Coordination_Repo/blob/main/Awesome_Rust_Cryptography.md)

&nbsp;

## Most Active in July

[Solana](https://github.com/solana-labs/solana):
345 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
29 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
65 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Parity](https://github.com/paritytech):
257 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
139 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
81 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[NEAR](https://github.com/nearprotocol/nearcore):
132 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]),
141 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4]), 
57 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])


&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

167 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]),
57 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
57 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [ChainSafe](https://github.com/ChainSafe)

10 merged PRs ([1][chainsafe-merged-prs-1]),
11 closed issues ([1][chainsafe-closed_issues-1]), 
3 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

- [Polkadot Index Network Token (PINT) community update #1 ](https://medium.com/chainsafe-systems/pint-community-update-1-2366f6cdcfc6)
- [Polkadot Index Network Token (PINT) community update #2 ](https://medium.com/chainsafe-systems/pint-community-update-2-b337ece3f031)
- [Forest Growth: An update from the Filecoin Rust implementation team](https://medium.com/chainsafe-systems/forest-growth-d26998a3da61)
- [Rising Tides: How the Mina Protocol can benefit Web 3.0 - An examination of Mina’s lightweight non-consensus full nodes and Rust x Wasm](https://medium.com/chainsafe-systems/mina-wasm-benefits-for-web-3-0-3d25991c3b75)


#### [CodeChain](https://github.com/CodeChain-io)

33 merged PRs ([1][comit-merged-prs-1]),
5 closed issues ([1][comit-closed_issues-1]), 
2 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Concordium](https://github.com/Concordium)

22 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
7 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]), 
27 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[concordium-open_issues-3]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[concordium-open_issues-4]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31


- [Concordium Announces Developers Open Grants Programme](https://markets.businessinsider.com/news/stocks/concordium-announces-developers-open-grants-programme-1030625795). [GitHub: Concordium-Free-Open-Grants-Program](https://github.com/Concordium/Concordium-Free-Open-Grants-Program). The Concordium Grant program has a specific mandate that recipients code must be open-sourced, and tooling developed must benefit both the Blockchain and Rustlang open source ecosystems.

#### [Conflux](https://github.com/Conflux-Chain)

18 merged PRs ([1][conflux-merged-prs-1]),
6 closed issues ([1][conflux-closed_issues-1]), 
2 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Dfinity](https://github.com/dfinity)

39 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
5 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]), 
5 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[dfinity-merged-prs-4]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[dfinity-closed_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[dfinity-closed_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[dfinity-closed_issues-3]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[dfinity-open_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[dfinity-open_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

- [Introducing the Motoko Playground, an Online Development Environment for the Internet Computer](https://medium.com/dfinity/introducing-the-motoko-playground-an-online-development-environment-for-the-internet-computer-efb4cd09ea8b)

#### [Diem](https://github.com/diem)

128 merged PRs ([1][diem-merged-prs-1]),
9 closed issues ([1][diem-closed_issues-1]), 
7 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Elrond](https://github.com/ElrondNetwork)

26 merged PRs ([1][elrond-merged-prs-1]),
0 closed issues, 
0 open issues

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31

#### [Fluence](https://github.com/fluencelabs)

22 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]),
1 closed issues ([1][fluence-closed_issues-1]), 
18 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3], [4][fluence-open_issues-4])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[fluence-open_issues-2]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[fluence-open_issues-3]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[fluence-open_issues-4]: https://github.com/fluencelabs/marine-rs-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Golem](https://github.com/golemfactory)

30 merged PRs ([1][golem-merged-prs-1]),
34 closed issues ([1][golem-closed_issues-1]), 
30 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Holochain](https://github.com/holochain/)

47 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4]),
3 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
5 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[holochain-merged-prs-4]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[holochain-closed_issues-2]: https://github.com/holochain/lair/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [IOTA](https://github.com/iotaledger)

31 merged PRs ([1][iota-merged-prs-1]),
6 closed issues ([1][iota-closed_issues-1]), 
2 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

18 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
13 closed issues ([1][lighthouse-closed_issues-1]), 
10 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[lighthouse-open_issues-2]: https://github.com/sigp/beacon-fuzz/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

- [Lighthouse Update #37](https://lighthouse.sigmaprime.io/update-37.html)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

17 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
3 closed issues ([1][mobilecoin-closed_issues-1]), 
9 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/fog/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

132 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]),
141 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4]), 
57 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[near-closed_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[near-closed_issues-3]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Nervos](https://github.com/nervosnetwork)

78 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]),
6 closed issues ([1][nervos-closed_issues-1]), 
6 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[nervos-open_issues-4]: https://github.com/nervosnetwork/ckb-std/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

- [Nervos Network Kicks Off Major Protocol Upgrade](https://www.nervos.org/blog/nervos-network-kicks-off-major-protocol-upgrade/)

#### [Parity](https://github.com/paritytech)

257 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
139 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
81 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

- [Research Update: The Case for Candle Auctions](https://polkadot.network/research-update-the-case-for-candle-auctions/)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

34 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]),
13 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]), 
22 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Rust Ethereum](https://github.com/rust-ethereum)

4 merged PRs ([1][rust_ethereum-merged-prs-1], [2][rust_ethereum-merged-prs-2]),
0 closed issues, 
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[rust_ethereum-merged-prs-2]: https://github.com/rust-ethereum/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

6 merged PRs ([1][secret_network-merged-prs-1]),
10 closed issues ([1][secret_network-closed_issues-1]), 
23 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [Solana](https://github.com/solana-labs/solana)

345 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
29 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
65 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

- [ok so what the fuck is the deal with solana anyway](https://2501babe.github.io/posts/solana101.html)

#### [Spacemesh](https://github.com/spacemeshos)

54 merged PRs ([1][spacemesh-merged-prs-1], [2][spacemesh-merged-prs-2]),
73 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
57 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/go-spacemesh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[spacemesh-merged-prs-2]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

#### [TezEdge](https://github.com/tezedge)

62 merged PRs ([1][tezedge-merged-prs-1]),
2 closed issues ([1][tezedge-closed_issues-1]), 
0 open issues

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[tezedge-closed_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31

#### [Zcash](https://github.com/zcash)

100 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
38 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
45 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-07-01..2021-07-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-07-01..2021-07-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-07-01..2021-07-31

- [Should Zcash switch from Proof of Work to Proof of Stake?](https://electriccoin.co/blog/should-zcash-switch-from-proof-of-work-to-proof-of-stake/)

&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

Jul 30 - Aug 20 | Online

[HackFS](https://fs.ethglobal.com/)

Aug 5 | Online

[DeFi Conference 2021](https://deficonference.floor.bz/)

Aug 5-7 | Online

[Smart Contract Summit #1](https://www.smartcontractsummit.io/)

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

Dec 1-3 | Seoul, Korea

[ICISC: The 24th Annual International Conference on information Security and Cryptology](http://www.icisc.org/)


&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

`arkworks` | Remote
- [Co-maintainer](https://form.jotform.com/212026632139145)

ChainSafe | Remote
- [Rust Developer](https://jobs.smartrecruiters.com/ChainSafeSystemsInc/743999739358248-rust-developer)

cLabs / Celo | Remote
- [Senior Rust Engineer](https://jobs.lever.co/clabs/46bf6e13-ef54-4a5c-9287-2c0557ad9db4)

Parity Technologies | Berlin or Remote 
- [Core Rust Developer - Cross-chain Messaging (Polkadot)](https://grnh.se/dafd8e973us)
- [Core Rust Developer - Consensus (Polkadot)](https://grnh.se/470a1a623us)
- [Rust Developer - Tools](https://grnh.se/e1cc2c0c3us)
- [Rust/Core Developer - Open Application to our 10+ open Rust engineering positions](https://grnh.se/0efc64513us)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#27 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


