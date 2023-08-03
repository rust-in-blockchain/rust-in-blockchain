---
title: "RiB Newsletter #50"
description: "July 2023"
date: 2023-08-02
categories:
  - "newsletters"
summary: "Welcome to the #49 edition of Rust in Blockchain."
---

Welcome to the #50 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #49](/newsletters/rib-newsletter-49/).

&nbsp;

## Thanks

Thanks to contributors:
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

None this month.

&nbsp;


## Interesting Things

#### Blog Posts

- Can we Obtain Privacy in a Private Proof-of-Stake Blockchain? [Part-I](https://decentralizedthoughts.github.io/2023-07-21-ppos1/), [Part-II](https://decentralizedthoughts.github.io/2023-07-21-ppos2/)
- [The zero-knowledge attack of the year might just have happened, or how Nova got broken](https://www.zksecurity.xyz/blog/posts/nova-attack/)
- [ZPU: The Zero-Knowledge Processing Unit](https://medium.com/@ingonyama/zpu-the-zero-knowledge-processing-unit-f886a48e00e0)

#### Papers

- [SoK: Public Randomness](https://eprint.iacr.org/2023/1121)
- [Streebog as a Random Oracle](https://eprint.iacr.org/2023/1075)
- [Security-Performance Tradeoff in DAG-based Proof-of-Work Blockchain Protocols](https://eprint.iacr.org/2023/1089)
- [Automated Analysis of Halo2 Circuits](https://eprint.iacr.org/2023/1051)
- [(Revised) Peer-to-Peer Energy Trading Meets Blockchain: Consensus via Score-Based Bid Assignment](https://eprint.iacr.org/2022/1471)
- [(Revised) Fast Fully Oblivious Compaction and Shuffling](https://eprint.iacr.org/2022/1333)

&nbsp;

## Most Active in July

[Parity](https://github.com/paritytech):
376 merged PRs,
131 closed issues,
130 open issues

[Starkware](https://github.com/starkware-libs):
322 merged PRs,
38 closed issues,
7 open issues

[Sui](https://github.com/MystenLabs):
305 merged PRs,
14 closed issues,
29 open issues

[Aptos](https://github.com/aptos-labs):
289 merged PRs,
58 closed issues,
46 open issues

[Reth](https://github.com/paradigmxyz/reth):
288 merged PRs,
163 closed issues,
87 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)
132 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4], [5][aleo-merged-prs-5]),
19 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4], [5][aleo-closed_issues-5]),
23 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4], [5][aleo-open_issues-5], [6][aleo-open_issues-6])

[aleo-merged-prs-1]: https://github.com/AleoHQ/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-merged-prs-5]: https://github.com/AleoHQ/welcome/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-closed_issues-4]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-closed_issues-5]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-open_issues-4]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-open_issues-5]: https://github.com/AleoHQ/wagyu/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aleo-open_issues-6]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Anoma](https://github.com/anoma)

84 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3], [4][anoma-merged-prs-4]),
30 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
30 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-merged-prs-4]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/masp/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

289 merged PRs ([1][aptos-merged-prs-1]),
58 closed issues ([1][aptos-closed_issues-1]),
46 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Aptos Multisig v2 and Econia v4](https://medium.com/econialabs/aptos-multisig-v2-and-econia-v4-757d542238cc)

#### [Casper](https://github.com/casper-network)

49 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
58 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
60 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

1 merged PRs ([1][comit-merged-prs-1]),
0 closed issues,
2 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

46 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
47 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
16 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

5 merged PRs ([1][conflux-merged-prs-1]),
0 closed issues,
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Monthly Progress Report — July 2023](https://confluxnetwork.medium.com/monthly-progress-report-july-2023-39d330e0fa9e)

#### [DarkFi](https://dark.fi)

2 merged PRs ([1][darkfi-merged-prs-1]),
2 closed issues ([1][darkfi-closed_issues-1]),
2 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

69 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
5 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]),
7 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4], [5][dfinity-open_issues-5])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-open_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dfinity-open_issues-5]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Dusk Network](https://github.com/dusk-network)

36 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3]),
21 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3]),
11 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

73 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5]),
22 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
16 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/espresso/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/hyperplonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Releasing the Espresso Sequencer Testnet II: Doppio](https://medium.com/@espressosys/releasing-the-espresso-sequencer-testnet-ii-doppio-bcc46c315c30)

#### [Filecoin](https://github.com/filecoin-project)

135 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7]),
62 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5], [6][filecoin-closed_issues-6]),
54 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/lurk-lab/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-gpu-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/lurk-lab/neptune/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/filecoin-project/rust-gpu-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-closed_issues-6]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/blstrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Monitoring booster-http Retrievals](https://filecoin.io/blog/posts/monitoring-booster-http-retrievals/)
- [CC Sector Upgrade: Guidelines and Modeling](https://filecoin.io/blog/posts/cc-sector-upgrade-guidelines-and-modeling/)

#### [Findora](https://github.com/FindoraNetwork)

36 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [What Zero Knowledge Proofs Do for Bridges](https://findora.org/2023/07/what-zero-knowledge-proofs-do-for-bridges/)
- [The Monthly Rollup: June ’23](https://findora.org/2023/07/the-monthly-rollup-june-23/)

#### [Fluence](https://github.com/fluencelabs)

130 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7]),
1 closed issues ([1][fluence-closed_issues-1]),
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/nox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

209 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8]),
130 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
101 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Inside Fuel: Q2 2023](https://fuel-labs.ghost.io/inside-fuel-q2-2023/)

#### [Golem](https://github.com/golemfactory)

26 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3]),
23 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3]),
35 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Grin](https://github.com/mimblewimble/grin)

3 merged PRs ([1][grin-merged-prs-1], [2][grin-merged-prs-2]),
3 closed issues ([1][grin-closed_issues-1], [2][grin-closed_issues-2]),
0 open issues

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[grin-merged-prs-2]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[grin-closed_issues-2]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

9 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3]),
1 closed issues ([1][helium-closed_issues-1]),
1 open issues ([1][helium-open_issues-1])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/helium-crypto-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Helium-Solana migration: The Most Asked Community Questions](https://blog.helium.com/helium-solana-migration-the-most-asked-community-questions-3d107c1b85cd)

#### [Holochain](https://github.com/holochain/)

74 merged PRs ([1][holochain-merged-prs-1]),
7 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
7 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Bundle Your hApp in a Kangaroo Pouch](https://blog.holochain.org/bundle-your-happ-in-a-kangaroo-pouch/)

#### [IOTA](https://github.com/iotaledger)

30 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4]),
0 closed issues,
1 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

80 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2]),
24 closed issues ([1][maidsafe-closed_issues-1]),
2 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

2 merged PRs ([1][mina-merged-prs-1]),
8 closed issues ([1][mina-closed_issues-1]),
11 open issues ([1][mina-open_issues-1])

[mina-merged-prs-1]: https://github.com/openmina/openmina/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mina-closed_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

23 merged PRs ([1][mobilecoin-merged-prs-1]),
4 closed issues ([1][mobilecoin-closed_issues-1]),
2 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

45 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3]),
0 closed issues,
1 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-bridge-eth-sc-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

82 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6]),
33 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5]),
36 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Nervos](https://github.com/nervosnetwork)

41 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]),
18 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

4 merged PRs ([1][oasis-merged-prs-1]),
1 closed issues ([1][oasis-closed_issues-1]),
1 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Oasis June 2023 Engineering Update](https://oasisprotocol.org/blog/june-2023-engineering-update)

#### [Parity](https://github.com/paritytech)

376 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13]),
131 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11]),
130 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Radix](https://github.com/radixdlt)

85 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3]),
28 closed issues ([1][radix-closed_issues-1]),
0 open issues

[radix-merged-prs-1]: https://github.com/radixdlt/community-scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

1 merged PRs ([1][secret_network-merged-prs-1]),
5 closed issues ([1][secret_network-closed_issues-1]),
0 open issues

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Announcing Secret Ethereum](https://scrt.network/blog/announcing-secret-ethereum)

#### [Solana](https://github.com/solana-labs/solana)

237 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
70 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2], [3][solana-closed_issues-3]),
33 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[solana-closed_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Network Performance Report: July 2023](https://solana.com/news/network-performance-report-july-2023)

#### [Soroban](https://github.com/stellar)

103 merged PRs ([1][soroban-merged-prs-1], [2][soroban-merged-prs-2], [3][soroban-merged-prs-3], [4][soroban-merged-prs-4], [5][soroban-merged-prs-5]),
37 closed issues ([1][soroban-closed_issues-1], [2][soroban-closed_issues-2], [3][soroban-closed_issues-3]),
50 open issues ([1][soroban-open_issues-1], [2][soroban-open_issues-2], [3][soroban-open_issues-3], [4][soroban-open_issues-4])

[soroban-merged-prs-1]: https://github.com/stellar/rs-soroban-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-merged-prs-2]: https://github.com/stellar/rs-soroban-env/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-merged-prs-3]: https://github.com/stellar/soroban-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-merged-prs-4]: https://github.com/stellar/soroban-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-merged-prs-5]: https://github.com/stellar/scaffold-soroban/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-closed_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-closed_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-closed_issues-3]: https://github.com/stellar/soroban-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-open_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-open_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-open_issues-3]: https://github.com/stellar/soroban-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[soroban-open_issues-4]: https://github.com/stellar/soroban-examples/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Stellar Development Foundation Q2 2023 in Review](https://www.stellar.org/blog/stellar-development-foundation-q2-2023-in-review)

#### [Subspace Network](https://github.com/subspace)

62 merged PRs ([1][subspace_network-merged-prs-1]),
39 closed issues ([1][subspace_network-closed_issues-1]),
13 open issues ([1][subspace_network-open_issues-1])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

305 merged PRs ([1][sui-merged-prs-1]),
14 closed issues ([1][sui-closed_issues-1]),
29 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Simple and Meta Oracles on Sui](https://tech.mystenlabs.com/simple-and-meta-oracles-on-sui/)

#### [Zcash](https://github.com/zcash)

79 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5]),
36 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]),
13 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [The Trailing Finality Layer: A stepping stone to proof of stake in Zcash](https://electriccoin.co/blog/the-trailing-finality-layer-a-stepping-stone-to-proof-of-stake-in-zcash/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

8 merged PRs ([1][aluvm-merged-prs-1], [2][aluvm-merged-prs-2]),
2 closed issues ([1][aluvm-closed_issues-1]),
0 open issues

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aluvm-merged-prs-2]: https://github.com/AluVM/aluasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[aluvm-closed_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

18 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4], [5][bdk-merged-prs-5]),
13 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
17 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-merged-prs-5]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

34 merged PRs ([1][bitmask-merged-prs-1]),
13 closed issues ([1][bitmask-closed_issues-1]),
11 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

7 merged PRs ([1][electrs-merged-prs-1]),
3 closed issues ([1][electrs-closed_issues-1]),
3 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

107 merged PRs ([1][fedimint-merged-prs-1]),
58 closed issues ([1][fedimint-closed_issues-1]),
29 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

48 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
22 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
18 open issues ([1][ldk-open_issues-1])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

14 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2]),
1 closed issues ([1][lnp/bp-closed_issues-1]),
2 open issues ([1][lnp/bp-open_issues-1])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [MyCitadel](https://github.com/orgs/mycitadel)

5 merged PRs ([1][mycitadel-merged-prs-1]),
5 closed issues ([1][mycitadel-closed_issues-1]),
2 open issues ([1][mycitadel-open_issues-1])

[mycitadel-merged-prs-1]: https://github.com/mycitadel/mycitadel-desktop/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mycitadel-closed_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mycitadel-open_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

41 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]),
1 closed issues ([1][nomic-closed_issues-1]),
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[nomic-closed_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

6 merged PRs ([1][rgb-merged-prs-1]),
5 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2]),
1 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rust-rgb20/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

38 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3]),
11 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]),
7 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/jean-airoldie/zeromq-src-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

10 merged PRs ([1][rust_simplicity-merged-prs-1]),
2 closed issues ([1][rust_simplicity-closed_issues-1]),
4 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_simplicity-closed_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

2 merged PRs ([1][talaia-merged-prs-1]),
0 closed issues
5 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

16 merged PRs ([1][ethers-rs-merged-prs-1]),
5 closed issues ([1][ethers-rs-closed_issues-1]),
11 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

75 merged PRs ([1][foundry-merged-prs-1]),
93 closed issues ([1][foundry-closed_issues-1]),
73 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

19 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
20 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]),
32 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Lighthouse Update #42](https://lighthouse-blog.sigmaprime.io/update-42.html)

#### [Mir Protocol](https://github.com/mir-protocol)

35 merged PRs ([1][mir_protocol-merged-prs-1], [2][mir_protocol-merged-prs-2]),
5 closed issues ([1][mir_protocol-closed_issues-1]),
6 open issues ([1][mir_protocol-open_issues-1])

[mir_protocol-merged-prs-1]: https://github.com/mir-protocol/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mir_protocol-merged-prs-2]: https://github.com/mir-protocol/evm-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mir_protocol-closed_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[mir_protocol-open_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

288 merged PRs ([1][reth-merged-prs-1]),
163 closed issues ([1][reth-closed_issues-1]),
87 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Rust Ethereum](https://github.com/rust-ethereum)

0 merged PRs,
1 closed issues ([1][rust_ethereum-closed_issues-1]),
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

1 merged PRs ([1][rust_web3-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_web3-open_issues-1])

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

322 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3]),
38 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2], [3][starkware-closed_issues-3]),
7 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[starkware-closed_issues-3]: https://github.com/starkware-libs/starknet-api/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/starknet-api/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Joining Forces: SHARP](https://medium.com/starkware/joining-forces-sharp-cfbd05f4b340)
- [Paradex: Starknet’s first Appchain](https://medium.com/starkware/paradex-starknets-first-appchain-85a0a760320f)
- [Harnessing the Beast — Madara and the Revolution of Starknet Appchains](https://medium.com/starkware/harnessing-the-beast-madara-and-the-revolution-of-starknet-appchains-7f76f774072e)

#### [zkSync](https://github.com/matter-labs/zksync)

1 merged PRs ([1][zksync_era-merged-prs-1]),
3 closed issues ([1][zksync_era-closed_issues-1], [2][zksync_era-closed_issues-2], [3][zksync_era-closed_issues-3]),
19 open issues ([1][zksync_era-open_issues-1], [2][zksync_era-open_issues-2], [3][zksync_era-open_issues-3])

[zksync_era-merged-prs-1]: https://github.com/matter-labs/foundry-zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zksync_era-closed_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zksync_era-closed_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zksync_era-closed_issues-3]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zksync_era-open_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zksync_era-open_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot
[zksync_era-open_issues-3]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-07-01..2023-07-31%20-author:app/dependabot

- [Boojum Upgrade: zkSync Era’s New High-performance Proof System for Radical Decentralization](https://zksync.mirror.xyz/HJ2Pj45EJkRdt5Pau-ZXwkV2ctPx8qFL19STM5jdYhc)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

Aug 2 | Barcelona, Spain | [ZKProof 5.5](https://zkproof.org/events/zkproof-5-5-barcelona/)

Aug 28-30 | Palo Alto, CA, US | [The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Aug 31 | San Francisco, CA, US | [Starknet Summit](https://summit23.starknet.io/)

Sep 5-6 | Seoul, Korea | [Korea Blockchain Week](https://koreablockchainweek.com/)

Sep 11-13 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

Sep 12-13 | Singapore | [DeCompute 2023](https://www.decompute.xyz/)

Sep 12-15 | Albuquerque, NM & Online | [RustConf 2023](https://rustconf.com/)

Sep 15 | Berlin, Germany | [Protocol Berg](https://protocol.berlin/)

Sep 20 | London, UK | [zkSummit10](https://www.zksummit.com/)

Sep 22-24 | New York City, US | [ETHGlobal New York](https://ethglobal.com/events/newyork2023)

Sep 26-28 | Madrid, Spain | [Stellar Meridian](https://meridian.stellar.org/)

Oct 2-4 | Istanbul, Turkey | [Cosmoverse 2023](https://cosmoverse.org/)

Oct 5-6 | US - Virtual Eastern | [Blockchain Security Summit 2023](https://www.sans.org/cyber-security-training-events/blockchain-summit-2023/)

Oct 30-Nov 3 | Amsterdam, Netherlands | [Solana Breakpoint](https://solana.com/breakpoint)

Nov 7-10 | Lisbon, Portugal | [Nearcon 23](https://near.org/nearcon23.near/widget/Index)

Nov 13-19 | Istanbul, Turkey | [Devconnect](https://devconnect.org/)

Nov 17-19 | Istanbul, Turkey | [ETHGlobal Istanbul](https://ethglobal.com/events/istanbul)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->



More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


