---
title: "RiB Newsletter #48"
description: "May 2023"
date: 2023-06-07
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #48 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #47](/newsletters/rib-newsletter-47/).

&nbsp;

## Thanks

Thanks to contributors:
[camilahanada],
_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[camilahanada]: https://github.com/camilahanada
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### Blog Posts

- [Stylus in Action: Lifecycle of a Stylus Contract](https://offchain.medium.com/stylus-in-action-lifecycle-of-a-stylus-contract-630f492ff85c)
- [ZK app developers should be able to see down to the constraints](https://www.zksecurity.xyz/blog/posts/noname/)
- [Where's Waldo on RISC Zero](https://www.risczero.com/blog/waldo)
- [Using Continuations to Prove Any EVM Transaction](https://www.risczero.com/blog/continuations)


#### Papers

- [Arithmetization of predicates into Halo 2 using application specific trace types](https://eprint.iacr.org/2023/666)
- [Simplex Consensus: A Simple and Fast Consensus Protocol](https://eprint.iacr.org/2023/463)
- [ParBFT: Faster Asynchronous BFT Consensus with a Parallel Optimistic Path](https://eprint.iacr.org/2023/679)
- [SoK: Distributed Randomness Beacons](https://eprint.iacr.org/2023/728)
- [How to Design Fair Protocols in the Multi-Blockchain Setting](https://eprint.iacr.org/2023/762)
- [Private Proof-of-Stake Blockchains using Differentially-private Stake Distortion](https://eprint.iacr.org/2023/787)


&nbsp;

## Most Active in May

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

121 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4], [5][aleo-merged-prs-5], [6][aleo-merged-prs-6]),
46 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4], [5][aleo-closed_issues-5]),
13 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/aleo-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-merged-prs-5]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-merged-prs-6]: https://github.com/AleoHQ/welcome/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/aleo-std/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-closed_issues-4]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-closed_issues-5]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aleo-open_issues-4]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

- [Announcing the Aleo Bug Bounty Program](https://www.aleo.org/post/announcing-the-aleo-bug-bounty-program)
- [Announcing the Aleo Tooling & Infrastructure Grants Program](https://www.aleo.org/post/announcing-the-aleo-tooling-infrastructure-grants-program)

#### [Anoma](https://github.com/anoma)

84 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3], [4][anoma-merged-prs-4]),
53 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
40 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-merged-prs-4]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

293 merged PRs ([1][aptos-merged-prs-1]),
64 closed issues ([1][aptos-closed_issues-1]),
40 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Casper](https://github.com/casper-network)

62 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
71 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
37 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

63 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7], [8][concordium-merged-prs-8]),
26 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
20 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-euro2ccd-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-use-case-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-merged-prs-8]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[concordium-open_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

16 merged PRs ([1][conflux-merged-prs-1]),
0 closed issues,
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

2 merged PRs ([1][darkfi-merged-prs-1]),
0 closed issues,
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

62 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
6 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]),
2 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

- [Exchange Rate Canister — A Smart Contract with Oracle Capabilities](https://medium.com/dfinity/exchange-rate-canister-a-smart-contract-with-oracle-capabilities-f30694753c89)

#### [Dusk Network](https://github.com/dusk-network)

15 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2]),
14 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2]),
15 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

31 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3]),
145 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
44 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/espresso-systems-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/atomicstore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

111 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7], [8][filecoin-merged-prs-8]),
70 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5], [6][filecoin-closed_issues-6]),
32 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/lurk-lab/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/filecoin-project/rust-gpu-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-merged-prs-8]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/ec-gpu/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-closed_issues-6]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

- [Introducing Filecoin Data Tools (FDT)](https://filecoin.io/blog/posts/introducing-filecoin-data-tools-fdt/)

#### [Findora](https://github.com/FindoraNetwork)

43 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]),
1 closed issues ([1][findora-closed_issues-1]),
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/bulletproofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[findora-merged-prs-4]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[findora-closed_issues-1]: https://github.com/FindoraNetwork/noah/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

68 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7]),
0 closed issues,
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/nox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

161 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7]),
153 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7]),
83 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6])

[fuel-merged-prs-1]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

18 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3]),
19 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]),
25 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[golem-open_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

- [Golem Network Introduces 0.12.1 Patch Release, Addressing Critical Bug Fixes and Enhancing User Experience](https://blog.golemproject.net/golem-network-introduces-0-12-1-patch-release/)

#### [Grin](https://github.com/mimblewimble/grin)

2 merged PRs ([1][grin-merged-prs-1]),
0 closed issues,
1 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

2 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2]),
0 closed issues,
0 open issues

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

111 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]),
10 closed issues ([1][holochain-closed_issues-1]),
19 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [IOTA](https://github.com/iotaledger)

22 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4]),
2 closed issues ([1][iota-closed_issues-1]),
2 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2])

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

63 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2]),
19 closed issues ([1][maidsafe-closed_issues-1]),
15 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/sn_dbc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[maidsafe-open_issues-2]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

0 merged PRs,
1 closed issues ([1][mina-closed_issues-1]),
3 open issues ([1][mina-open_issues-1])

[mina-closed_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

12 merged PRs ([1][mobilecoin-merged-prs-1]),
3 closed issues ([1][mobilecoin-closed_issues-1]),
1 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

21 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2]),
2 closed issues ([1][multiversx-closed_issues-1]),
2 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-metabonding-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

111 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6]),
36 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6]),
31 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Nervos](https://github.com/nervosnetwork)

45 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6]),
16 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4], [5][nervos-closed_issues-5], [6][nervos-closed_issues-6]),
8 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-closed_issues-5]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-closed_issues-6]: https://github.com/godwokenrises/godwoken-tests/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

9 merged PRs ([1][oasis-merged-prs-1]),
0 closed issues,
3 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

- [Oasis April 2023 Engineering Update](https://oasisprotocol.org/blog/april-2023-engineering-update)

#### [Parity](https://github.com/paritytech)

465 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14]),
186 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11]),
135 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Radix](https://github.com/radixdlt)

86 merged PRs ([1][radix-merged-prs-1]),
5 closed issues ([1][radix-closed_issues-1]),
1 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

19 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]),
1 closed issues ([1][secret_network-closed_issues-1]),
1 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

334 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
73 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
27 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

38 merged PRs ([1][subspace_network-merged-prs-1]),
17 closed issues ([1][subspace_network-closed_issues-1]),
11 open issues ([1][subspace_network-open_issues-1])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

494 merged PRs ([1][sui-merged-prs-1]),
138 closed issues ([1][sui-closed_issues-1]),
50 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot


- [Groth-Sahai Proofs: Zero to Hero](https://tech.mystenlabs.com/groth-sahai-proofs-zero-to-hero/)
- [Sui Lutris: The distributed system protocol at the heart of Sui](https://tech.mystenlabs.com/sui-lutris-the-distributed-system-protocol-at-the-heart-of-sui/)

#### [Zcash](https://github.com/zcash)

87 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5]),
32 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4]),
26 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

18 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3]),
12 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
18 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

31 merged PRs ([1][bitmask-merged-prs-1]),
12 closed issues ([1][bitmask-closed_issues-1]),
11 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Cyphernet](https://github.com/cyphernet-dao)

7 merged PRs ([1][cyphernet-merged-prs-1], [2][cyphernet-merged-prs-2]),
14 closed issues ([1][cyphernet-closed_issues-1], [2][cyphernet-closed_issues-2]),
0 open issues

[cyphernet-merged-prs-1]: https://github.com/cyphernet-dao/rust-netservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[cyphernet-merged-prs-2]: https://github.com/cyphernet-dao/rust-cyphernet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[cyphernet-closed_issues-1]: https://github.com/cyphernet-dao/rust-netservices/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[cyphernet-closed_issues-2]: https://github.com/cyphernet-dao/rust-cyphernet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

6 merged PRs ([1][electrs-merged-prs-1]),
13 closed issues ([1][electrs-closed_issues-1]),
2 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

140 merged PRs ([1][fedimint-merged-prs-1]),
44 closed issues ([1][fedimint-closed_issues-1]),
35 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

38 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
21 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
31 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2], [3][ldk-open_issues-3])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ldk-open_issues-3]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

5 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2]),
0 closed issues,
1 open issues ([1][lnp/bp-open_issues-1])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [MyCitadel](https://github.com/orgs/mycitadel)

2 merged PRs ([1][mycitadel-merged-prs-1]),
0 closed issues,
2 open issues ([1][mycitadel-open_issues-1])

[mycitadel-merged-prs-1]: https://github.com/mycitadel/mycitadel-desktop/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[mycitadel-open_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

1 merged PRs ([1][nomic-merged-prs-1]),
0 closed issues,
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

3 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2]),
0 closed issues,
1 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

45 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]),
22 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2]),
18 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

9 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
9 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

5 merged PRs ([1][talaia-merged-prs-1]),
3 closed issues ([1][talaia-closed_issues-1]),
2 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

35 merged PRs ([1][ethers-rs-merged-prs-1]),
10 closed issues ([1][ethers-rs-closed_issues-1]),
7 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

85 merged PRs ([1][foundry-merged-prs-1]),
71 closed issues ([1][foundry-closed_issues-1]),
96 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

21 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
28 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]),
28 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

- [Unbundling attacks on MEV relays using RPC](https://lighthouse-blog.sigmaprime.io/mev-unbundling-rpc.html)

#### [Mir Protocol](https://github.com/mir-protocol)

46 merged PRs ([1][mir_protocol-merged-prs-1], [2][mir_protocol-merged-prs-2]),
0 closed issues,
4 open issues ([1][mir_protocol-open_issues-1])

[mir_protocol-merged-prs-1]: https://github.com/mir-protocol/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[mir_protocol-merged-prs-2]: https://github.com/mir-protocol/evm-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[mir_protocol-open_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

305 merged PRs ([1][reth-merged-prs-1]),
132 closed issues ([1][reth-closed_issues-1]),
45 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

259 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3]),
43 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
13 open issues ([1][starkware-open_issues-1])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-05-01..2023-05-31%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-05-01..2023-05-31%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-05-01..2023-05-31%20-author:app/dependabot

- [Under the hood of Cairo 1.0: Exploring Sierra](https://medium.com/nethermind-eth/under-the-hood-of-cairo-1-0-exploring-sierra-1220f6dbcf9)
- [Scarb: Simplifying Cairo1 Package Management](https://medium.com/@0xasten/scarb-simplifying-cairo1-package-management-1c43ceae7bc7)
- [From Solidity to Cairo 1.0 (WIP)](https://lead-archeology-a38.notion.site/From-Solidity-to-Cairo-1-0-WIP-07097d7de1ad45d9b7c6c63f60b7141c)
- [Exploring the Use Cases of Cheap Computation](https://medium.com/starkware/exploring-the-use-cases-of-cheap-computation-1ab6254e7895)
- [Scaling Ethereum Efficiently](https://starkware.medium.com/scaling-ethereum-efficiently-d91a8a908cab)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->


Jun 9-10 | Prague, Czech Republic | [ETHPrague](https://ethprague.com/)

Jun 11-Jul 3 | Online | [Pragma Cairo 1.0 Hackathon](https://taikai.network/pragma-oracle/hackathons/Cairo1hackathon)

Jun 17-20 | Paris, France | [EthCC](https://www.ethcc.io/)

Jun 28-29 | Copenhagen, Denmark | [Polkadot Decoded](https://polkadot.network/ecosystem/events/decoded-2023/)

Jul 30-Aug 1 | Barcelona, Spain | [Zcon 4](https://zfnd.org/zcon4/)

Aug 28-30 | Palo Alto, CA, US | [The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Sep 5-6 | Seoul, Korea | [Korea Blockchain Week](https://koreablockchainweek.com/)

Sep 11-13 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

Sep 12-13 | Singapore | [DeCompute 2023](https://www.decompute.xyz/)

Sep 12-15 | Albuquerque, NM & Online | [RustConf 2023](https://rustconf.com/)

Sep 26-28 | Madrid, Spain | [Stellar Meridian](https://meridian.stellar.org/)

Oct 30-Nov 3 | Amsterdam, Netherlands | [Solana Breakpoint](https://solana.com/breakpoint)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Holochain | Americas Centric, Remote
- [RUST Developer – Holo Americas](https://holo.host/careers/rust-developer)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


