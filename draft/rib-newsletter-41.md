---
title: "RiB Newsletter #41"
description: "October 2022"
date: 2021-11-02
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #41 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #40](/newsletters/rib-newsletter-40/).

&nbsp;

## Thanks

Thanks to contributors:

[djddo],
[Hunter Trujillo],

_TODO_

[Brian Anderson], and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[djddo]: https://github.com/djddo
[Hunter Trujillo]: https://github.com/cryptoquick
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### Blog Posts

- [Blockchain Consensus Mechanisms Compared](https://halborn.com/blockchain-consensus-mechanisms-compared)
- [Creating wasm-opt Rust bindings with cxx](https://brson.github.io/2022/10/26/creating-wasm-opt-rust-bindings-with-cxx)
- [Introducing Noir: The Universal Language of Zero-Knowledge](https://medium.com/@aztecnetwork/ff43f38d86d9)
- [Polygon zkEVM Architecture](https://wiki.polygon.technology/docs/zkEVM/overview/)
- [MEV Resistance on a DAG](https://blog.chain.link/mev-resistance-on-a-dag/)
- [Secure Randomness: From Zero to Verifiable Delay Functions, Part 1](https://blog.neodyme.io/posts/secure-randomness-part-1/)
- [Public Randomness and Randomness Beacons](https://a16zcrypto.com/public-randomness-and-randomness-beacons/)
- [Explained: The BNB Chain Hack (October 2022)](https://halborn.com/explained-the-bnb-chain-hack-october-2022)
- [Security Analysis of Avalanche Consensus](https://medium.com/avalancheavax/security-analysis-of-avalanche-consensus-39543d09af4a)
- [Beyond IBC](https://maven11.substack.com/p/beyond-ibc)
- [Major New Cryptowatch Desktop Trading Release using fast Rust-native GUI Framework](https://blog.cryptowat.ch/cryptowatch-desktop-trading/)

#### Papers

- [Hyperproofs: Aggregating and Maintaining Proofs in Vector Commitments](https://eprint.iacr.org/2021/599)
- [Flexible Anonymous Transactions (FLAX): Towards Privacy-Preserving and Composable Decentralized Finance](https://eprint.iacr.org/2021/1249)
- [Byzantine Consensus under Fully Fluctuating Participation](https://eprint.iacr.org/2022/1448)
- [Transparent Batchable Time-lock Puzzles and Applications to Byzantine Consensus](https://eprint.iacr.org/2022/1421)
- [Validity Rollups on Bitcoin](https://bitcoinrollups.org)
- [Secure Distributed Key Generation for Discrete-Log Based Cryptosystems](https://link.springer.com/content/pdf/10.1007/3-540-48910-X_21.pdf)

#### Projects

- [zkcreds-rs](https://github.com/rozbb/zkcreds-rs).
  A cryptographic library for designing anonymous credential systems
  in a flexible, issuer-agnostic, and efficient manner using general-purpose zero-knowledge proofs.
- [zk-timelock](https://github.com/timoth-y/zk-timelock).
  Arkworks circuits for verifiable time-lock encryption.
- [rs-tlock](https://github.com/timoth-y/tlock-rs).
  Pure Rust implementation of drand/tlock scheme. It provides
  time-based encryption and decryption capabilities by relying on a
  drand threshold network and identity-based encryption (IBE).

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

<!-- https://github.com/rustsec/advisory-db/pulls -->
<!-- https://osv.dev/list?page=2&ecosystem=crates.io -->


&nbsp;

## Most Active in October

[Sui](https://github.com/MystenLabs):
433 merged PRs,
193 closed issues,
119 open issues

[Parity](https://github.com/paritytech):
423 merged PRs,
256 closed issues,
118 open issues

[Solana](https://github.com/solana-labs/solana):
423 merged PRs,
86 closed issues,
73 open issues

[Aptos](https://github.com/aptos-labs):
381 merged PRs,
52 closed issues,
93 open issues

[Fuel](https://github.com/FuelLabs):
316 merged PRs,
236 closed issues,
143 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

74 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
26 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]),
21 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-closed_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Anoma](https://github.com/anoma)

130 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
50 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
42 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

381 merged PRs ([1][aptos-merged-prs-1]),
52 closed issues ([1][aptos-closed_issues-1]),
93 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [The Making of the Aptos Gas Schedule](https://medium.com/aptoslabs/the-making-of-the-aptos-gas-schedule-508d5686a350)
- [Aptos Autumn is Here](https://medium.com/aptoslabs/aptos-autumn-is-here-92a8d904eb49)

#### [Casper](https://github.com/casper-network)

15 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
31 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
15 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

6 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2]),
1 closed issues ([1][comit-closed_issues-1]),
4 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/maia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

70 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6]),
36 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
12 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-transaction-logger/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[concordium-open_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

7 merged PRs ([1][conflux-merged-prs-1]),
0 closed issues,
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

8 merged PRs ([1][darkfi-merged-prs-1]),
11 closed issues ([1][darkfi-closed_issues-1]),
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

64 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6]),
105 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]),
5 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/icx-proxy/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dfinity-open_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [Building Effective Rust Canister Smart Contracts: Useful Patterns](https://medium.com/dfinity/building-effective-rust-canister-smart-contracts-patterns-and-pitfalls-d019221061b2)

#### [Dusk Network](https://github.com/dusk-network)

15 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5], [6][dusk_network-merged-prs-6]),
7 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3]),
12 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/dusk-hamt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/microkelvin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-merged-prs-4]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-merged-prs-5]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-merged-prs-6]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Elrond](https://github.com/ElrondNetwork)

69 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3]),
2 closed issues ([1][elrond-closed_issues-1]),
1 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-nft-marketplace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

18 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5]),
6 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
6 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/reef/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/cap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

195 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7]),
107 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3]),
98 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/builtin-actors-bundler/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-fil-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/ec-gpu/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Findora](https://github.com/FindoraNetwork)

58 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]),
6 closed issues ([1][findora-closed_issues-1]),
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/bulletproofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[findora-merged-prs-4]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [EVM Privacy with Findora](https://medium.com/findorafoundation/evm-privacy-with-findora-e127753e8044)

#### [Fluence](https://github.com/fluencelabs)

67 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6]),
4 closed issues ([1][fluence-closed_issues-1]),
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

316 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12]),
236 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8], [9][fuel-closed_issues-9], [10][fuel-closed_issues-10]),
143 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-11]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-merged-prs-12]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-9]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-closed_issues-10]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

26 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]),
37 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3], [4][golem-closed_issues-4], [5][golem-closed_issues-5]),
18 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/ya-runtime-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-merged-prs-5]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-service-bus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-closed_issues-4]: https://github.com/golemfactory/ya-runtime-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-closed_issues-5]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-service-bus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[golem-open_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Grin](https://github.com/mimblewimble/grin)

4 merged PRs ([1][grin-merged-prs-1]),
0 closed issues,
0 open issues

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

23 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]),
2 closed issues ([1][helium-closed_issues-1]),
3 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/semtech-udp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[helium-open_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

31 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4]),
8 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
8 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[holochain-merged-prs-4]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [IOTA](https://github.com/iotaledger)

102 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6], [7][iota-merged-prs-7]),
38 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5], [6][iota-closed_issues-6]),
20 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-merged-prs-6]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-merged-prs-7]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-closed_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-closed_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-closed_issues-5]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-closed_issues-6]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[iota-open_issues-4]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

54 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3]),
1 closed issues ([1][maidsafe-closed_issues-1]),
7 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2], [3][maidsafe-open_issues-3], [4][maidsafe-open_issues-4])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/blsttc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/sn_dbc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[maidsafe-open_issues-2]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[maidsafe-open_issues-3]: https://github.com/maidsafe/qp2p/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[maidsafe-open_issues-4]: https://github.com/maidsafe/sn_consensus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

68 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
15 closed issues ([1][mobilecoin-closed_issues-1]),
20 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

203 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9]),
42 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7]),
59 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-merged-prs-9]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-closed_issues-7]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/near-lake-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Nervos](https://github.com/nervosnetwork)

69 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8], [9][nervos-merged-prs-9]),
8 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4], [5][nervos-closed_issues-5]),
19 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4], [5][nervos-open_issues-5])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/mercury/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/nervosnetwork/ckb-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-7]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-8]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-merged-prs-9]: https://github.com/godwokenrises/godwoken-scripts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/mercury/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-closed_issues-5]: https://github.com/godwokenrises/godwoken-tests/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/mercury/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-open_issues-4]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nervos-open_issues-5]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

12 merged PRs ([1][oasis-merged-prs-1]),
2 closed issues ([1][oasis-closed_issues-1]),
2 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

423 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15]),
256 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13]),
118 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-merged-prs-15]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-closed_issues-13]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[parity-open_issues-13]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [Polkadot: Blockspace over Blockchains](https://www.rob.tech/polkadot-blockspace-over-blockchains/)

#### [Radix](https://github.com/radixdlt)

77 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3]),
1 closed issues ([1][radix-closed_issues-1]),
4 open issues ([1][radix-open_issues-1], [2][radix-open_issues-2])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/scrypto-challenges/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[radix-open_issues-2]: https://github.com/radixdlt/scrypto-challenges/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)


23 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]),
1 closed issues ([1][secret_network-closed_issues-1]),
2 open issues ([1][secret_network-open_issues-1], [2][secret_network-open_issues-2])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[secret_network-open_issues-1]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[secret_network-open_issues-2]: https://github.com/scrtlabs/snip20-reference-impl/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [Secret 2.0: Building The Next Generation of Web3 Privacy](https://scrt.network/blog/secret-2-0-building-the-next-generation-of-web3-privacy)

#### [Solana](https://github.com/solana-labs/solana)

423 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
86 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
73 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [Porting the Solana eBPF JIT compiler to ARM64](https://blog.trailofbits.com/2022/10/12/solana-jit-compiler-ebpf-arm64/)
- [Stake², or How To Cheat The Staking Mechanism - Exploring Solana Core Part 2](https://blog.neodyme.io/posts/solana_core_2/)

#### [Subspace Labs](https://github.com/subspace)

30 merged PRs ([1][subspace_labs-merged-prs-1]),
14 closed issues ([1][subspace_labs-closed_issues-1]),
8 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

433 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2]),
193 closed issues ([1][sui-closed_issues-1], [2][sui-closed_issues-2]),
119 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[sui-merged-prs-2]: https://github.com/MystenLabs/narwhal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[sui-closed_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Zcash](https://github.com/zcash)

104 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5]),
61 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4]),
35 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zcash-open_issues-4]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [Zebra Release Candidate](https://zfnd.org/zebra-release-candidate/)
- [New release 5.3.0](https://electriccoin.co/blog/new-release-5-3-0)

&nbsp;

### Rust in Bitcoin

It's been a crazy month in the Bitcoin space. In light of the mayhem happening on LND, it bears mentioning, there's two Rust Lightning implementations, LNP and LDK, activity on both listed below. In lighter news, Iris wallet, an Android Bitcoin wallet that supports RGB tokens was released, and it makes use of rgb-lib, behind Kotlin language bindings using `rust-ffi`. LDK releases 0.0.112, a largely incremental release to meet expanding use-cases as the project matures. BDK 0.23 was released shortly after last newsletter, and they're now gearing up for an 0.24 release containing support for rust-bitcoin 0.29, as mentioned in [RiB #39](https://rustinblockchain.org/newsletters/rib-newsletter-39/#rust-in-bitcoin). The Fedimint team is working hard on new features, including [an experimental web interface](https://github.com/justinmoon/webimint), and a 2nd-generation key generation system based on Discrete-Log Cryptography, which should be more secure. Finally, bitmask-core 0.4 was published, with support for Taproot P2TR addresses, and also LNDHub support.

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

22 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]),
14 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3], [4][bdk-closed_issues-4]),
11 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-closed_issues-4]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

7 merged PRs ([1][bitmask-merged-prs-1]),
2 closed issues ([1][bitmask-closed_issues-1]),
6 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

5 merged PRs ([1][electrs-merged-prs-1]),
1 closed issues ([1][electrs-closed_issues-1]),
0 open issues

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint)

> Fedimint is a bitcoin banking protocol. Highlights from the last month include:

- Distributed key generation so federation setup has no single point of failure ( https://github.com/fedimint/fedimint/pull/600)
- Modularization so that developers don't have to fork the repo to modify functionality (https://github.com/fedimint/fedimint/issues/673)
- Proper database transactions (https://github.com/fedimint/fedimint/pull/791)
- Improved connection to Lighting Network (https://github.com/fedimint/fedimint/pull/709)
- Deriving our anonymous IOUs from a cryptographic seed to enable safer recovery schemes (https://github.com/fedimint/fedimint/pull/811)

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

42 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
10 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
20 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

9 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3]),
5 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3], [4][lnp/bp-closed_issues-4]),
2 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-merged-prs-3]: https://github.com/BP-WG/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-closed_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-closed_issues-3]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-closed_issues-4]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lnp/bp-open_issues-2]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [LNP WG](https://github.com/LNP-WG)

1 merged PRs ([1][lnp_wg-merged-prs-1]),
0 closed issues,
0 open issues

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

15 merged PRs ([1][nakamoto-merged-prs-1]),
6 closed issues ([1][nakamoto-closed_issues-1]),
5 open issues ([1][nakamoto-open_issues-1])

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nakamoto-closed_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nakamoto-open_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

3 merged PRs ([1][nomic-merged-prs-1]),
1 closed issues ([1][nomic-closed_issues-1]),
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[nomic-closed_issues-1]: https://github.com/nomic-io/merk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

2 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2]),
0 closed issues,
1 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

35 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]),
21 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]),
20 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

2 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/ElementsProject/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Sapio](https://github.com/sapio-lang/sapio)

9 merged PRs ([1][sapio-merged-prs-1]),
5 closed issues ([1][sapio-closed_issues-1]),
24 open issues ([1][sapio-open_issues-1])

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[sapio-closed_issues-1]: https://github.com/sapio-lang/sapio/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[sapio-open_issues-1]: https://github.com/sapio-lang/sapio/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

0 merged PRs,
0 closed issues,
4 open issues ([1][talaia-open_issues-1])

[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

19 merged PRs ([1][ethers-rs-merged-prs-1]),
12 closed issues ([1][ethers-rs-closed_issues-1]),
7 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

60 merged PRs ([1][foundry-merged-prs-1]),
34 closed issues ([1][foundry-closed_issues-1]),
58 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

9 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
16 closed issues ([1][lighthouse-closed_issues-1]),
18 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [Rust Ethereum](https://github.com/rust-ethereum)

1 merged PRs ([1][rust_ethereum-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

#### [zkSync](https://github.com/matter-labs/zksync)

6 merged PRs ([1][zksync-merged-prs-1]),
3 closed issues ([1][zksync-closed_issues-1]),
1 open issues ([1][zksync-open_issues-1])

[zksync-merged-prs-1]: https://github.com/matter-labs/compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-10-01..2022-10-31%20-author:app/dependabot
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2022-10-01..2022-10-31%20-author:app/dependabot

- [Baby Alpha Has Arrived!](https://blog.matter-labs.io/baby-alpha-has-arrived-5b10798bc623)
- [zkSync End-to-End Prover Is Now Live on Testnet](https://blog.matter-labs.io/milestone-3-zksync-end-to-end-prover-is-now-live-on-testnet-9ee4fdc1874f)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Nov 3 | San Francisco, USA

[Ethereum hackathon: ETH San Francisco 2022](https://nftevening.com/event/eth-san-francisco-2022-san-francisco/)

Nov 3 | San Francisco, USA

[Polkadot Summit](https://www.polkadotsummit.com/)

Nov 7-10 | Chicago, USA

[TCC 2022](https://tcc.iacr.org/2022/)

Nov 10-11 | Dubai, United Arab Emirates

[ICSCB 2022: 16. International Conference on Smart Contracts and Blockchain](https://waset.org/smart-contracts-and-blockchain-conference-in-november-2022-in-dubai)

Nov 14-17 | Istanbul, Turkey

[Istanbul Blockchain Week](https://istanbulblockchainweek.com/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Blockstream | Remote
- [Senior Network Engineer](https://grnh.se/6ac8f7f11us)
- [Senior Product Designer -(Contract)](https://grnh.se/a4824d641us)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain
