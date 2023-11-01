---
title: "RiB Newsletter #53"
description: "October 2023"
date: 2023-11-01
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #53 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #52](/newsletters/rib-newsletter-52/).

&nbsp;

## Thanks

Thanks to contributors:
[Anton Kaliaev],
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Anton Kaliaev]: https://github.com/melekes
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### Blog Posts

- [The Cross-Domain Thesis Part 2: Storage Proofs, Computation, and Bloat](https://maven11.substack.com/p/the-cross-domain-thesis-part-2-storage)
- [Building Apps with Nova: an example from zkConnect4](https://hackmd.io/lfL00N75R_G4dVVMU_iMsA)

#### Papers

- [Proof-of-Work-based Consensus in Expected-Constant Time](https://eprint.iacr.org/2023/1663)
- [FaBFT: Flexible Asynchronous BFT Protocol Using DAG](https://eprint.iacr.org/2023/1660)
- [Withdrawable Signature: How to Call off a Signature](https://eprint.iacr.org/2023/1621)
- [Better Safe than Sorry: Recovering after Adversarial Majority](https://eprint.iacr.org/2023/1556)
- [Cornucopia: Distributed randomness beacons at scale](https://eprint.iacr.org/2023/1554)

#### Videos

- [Let's Fuzz: Putting Contracts To The Test](https://drive.google.com/file/d/1NT0SdP-1Kc5_hzv9vN7V8KvBAuk3-SMo/view)

&nbsp;

## Most Active in October

[Sui](https://github.com/MystenLabs):
470 merged PRs,
74 closed issues,
15 open issues

[Solana](https://github.com/solana-labs/solana):
339 merged PRs,
108 closed issues,
54 open issues

[Dfinity](https://github.com/dfinity):
330 merged PRs,
9 closed issues,
4 open issues

[Parity](https://github.com/paritytech):
327 merged PRs,
124 closed issues,
139 open issues

[Starkware](https://github.com/starkware-libs):
312 merged PRs,
17 closed issues,
6 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

151 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]),
242 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
272 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aleo-open_issues-4]: https://github.com/AleoHQ/aleo-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Testnet 3 Phase III Deploy Incentives Retrospective](https://aleo.org/post/testnet-3-phase-3-deploy-incentives-retrospective/)
- [Introducing zPass: Aleo's pioneering step toward privacy-preserving digital identity](https://aleo.org/post/introducing-zpass-aleos-pioneering-step-toward-privacy-preserving-digital/)

#### [Anoma](https://github.com/anoma)

63 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
42 closed issues ([1][anoma-closed_issues-1]),
53 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2])

[anoma-merged-prs-1]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/namada-sdk-starter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [A brief introduction to Anoma's P2P layer](https://anoma.net/blog/anomas-p2p-layer)
- [This is not the SUAVE you are looking for](https://anoma.net/blog/suave)

#### [Aptos](https://github.com/aptos-labs)

296 merged PRs ([1][aptos-merged-prs-1], [2][aptos-merged-prs-2]),
31 closed issues ([1][aptos-closed_issues-1]),
36 open issues ([1][aptos-open_issues-1], [2][aptos-open_issues-2])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aptos-merged-prs-2]: https://github.com/aptos-labs/aptos-indexer-processors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[aptos-open_issues-2]: https://github.com/aptos-labs/aptos-indexer-processors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Graffio: Web3’s Overnight Sensation](https://medium.com/aptoslabs/graffio-web3s-overnight-sensation-81a6cf18b626)

#### [Casper](https://github.com/casper-network)

29 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
31 closed issues ([1][casper-closed_issues-1]),
28 open issues ([1][casper-open_issues-1])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/casper-wasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

1 merged PRs ([1][comit-merged-prs-1]),
1 closed issues ([1][comit-closed_issues-1]),
0 open issues

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

35 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]),
15 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4], [5][concordium-closed_issues-5], [6][concordium-closed_issues-6]),
25 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4], [5][concordium-open_issues-5])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-misc-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-umbrella-oracle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-rosetta/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-smart-contract-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-misc-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-umbrella-oracle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-closed_issues-5]: https://github.com/Concordium/concordium-smart-contract-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-closed_issues-6]: https://github.com/Concordium/concordium-transaction-logger/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-misc-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-open_issues-4]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[concordium-open_issues-5]: https://github.com/Concordium/concordium-smart-contract-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

11 merged PRs ([1][conflux-merged-prs-1]),
1 closed issues ([1][conflux-closed_issues-1]),
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Monthly Progress Report — October 2023](https://medium.com/conflux-network/monthly-progress-report-october-2023-b8ae3ede15f4)

#### [Dfinity](https://github.com/dfinity)

330 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7], [8][dfinity-merged-prs-8], [9][dfinity-merged-prs-9], [10][dfinity-merged-prs-10], [11][dfinity-merged-prs-11], [12][dfinity-merged-prs-12], [13][dfinity-merged-prs-13], [14][dfinity-merged-prs-14], [15][dfinity-merged-prs-15], [16][dfinity-merged-prs-16], [17][dfinity-merged-prs-17]),
9 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5]),
4 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2])

[dfinity-merged-prs-1]: https://github.com/dfinity/ICRC-1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/internet-identity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/metrics-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/journald-parser/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/stable-structures/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-7]: https://github.com/dfinity/canister-profiling/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-8]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-9]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-10]: https://github.com/dfinity/standalone-sig-verifier-web/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-11]: https://github.com/dfinity/ic-repl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-12]: https://github.com/dfinity/nns-dapp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-13]: https://github.com/dfinity/ic-wasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-14]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-15]: https://github.com/dfinity/bitcoin-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-16]: https://github.com/dfinity/response-verification/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-merged-prs-17]: https://github.com/dfinity/metrics-encoder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/stable-structures/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-closed_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-closed_issues-5]: https://github.com/dfinity/bitcoin-developer-preview/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/canister-profiling/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Announcing the Zero to Dapp Educate Series — learn and build on the Internet Computer!](https://medium.com/dfinity/announcing-the-zero-to-dapp-educate-series-learn-and-build-on-the-internet-computer-6c5003d2cf53)
- [Index Canisters: Account-based search for ledgers on the Internet Computer](https://medium.com/dfinity/index-canisters-account-based-search-for-ledgers-on-the-internet-computer-f93145f57663)
- [Jumpstarting Your Internet Computer Developer Journey](https://medium.com/dfinity/jumpstarting-your-internet-computer-developer-journey-c707e2d8517f)
- [Claim free cycles to kick off your project on the Internet Computer](https://medium.com/dfinity/claim-free-cycles-to-kick-off-your-project-on-the-internet-computer-e97e1e50dc1c)

#### [Dusk Network](https://github.com/dusk-network)

77 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5], [6][dusk_network-merged-prs-6], [7][dusk_network-merged-prs-7], [8][dusk_network-merged-prs-8], [9][dusk_network-merged-prs-9], [10][dusk_network-merged-prs-10], [11][dusk_network-merged-prs-11], [12][dusk_network-merged-prs-12], [13][dusk_network-merged-prs-13]),
58 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4], [5][dusk_network-closed_issues-5], [6][dusk_network-closed_issues-6], [7][dusk_network-closed_issues-7], [8][dusk_network-closed_issues-8], [9][dusk_network-closed_issues-9]),
18 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/Poseidon252/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/piecrust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-4]: https://github.com/dusk-network/kadcast/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-5]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-6]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-7]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-8]: https://github.com/dusk-network/dusk-pki/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-9]: https://github.com/dusk-network/bls12_381-sign/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-10]: https://github.com/dusk-network/merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-11]: https://github.com/dusk-network/schnorr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-12]: https://github.com/dusk-network/phoenix-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-merged-prs-13]: https://github.com/dusk-network/Hades252/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/Poseidon252/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/piecrust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-4]: https://github.com/dusk-network/kadcast/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-5]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-6]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-7]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-8]: https://github.com/dusk-network/merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-closed_issues-9]: https://github.com/dusk-network/schnorr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

92 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5], [6][espresso_systems-merged-prs-6], [7][espresso_systems-merged-prs-7], [8][espresso_systems-merged-prs-8]),
51 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4]),
75 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4], [5][espresso_systems-open_issues-5], [6][espresso_systems-open_issues-6], [7][espresso_systems-open_issues-7])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/espresso-sequencer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/espresso-polygon-zkevm-demo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/async-compatibility-layer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-6]: https://github.com/EspressoSystems/sequencer-example-l2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-7]: https://github.com/EspressoSystems/discord-faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-merged-prs-8]: https://github.com/EspressoSystems/hotshot-query-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/hotshot-query-service/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/espresso-polygon-zkevm-demo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-open_issues-5]: https://github.com/EspressoSystems/espresso/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-open_issues-6]: https://github.com/EspressoSystems/discord-faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[espresso_systems-open_issues-7]: https://github.com/EspressoSystems/surf-disco/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

69 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6]),
28 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5]),
7 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/bls-signatures/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/rust-gpu-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/filecoin-project/bls-signatures/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Filecoin News 76](https://filecoin.io/blog/posts/filecoin-news-76/)

#### [Findora](https://github.com/FindoraNetwork)

10 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/nft-issue-transaction/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

181 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7], [8][fluence-merged-prs-8], [9][fluence-merged-prs-9], [10][fluence-merged-prs-10]),
3 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2]),
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/nox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/fRPC-Substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/decider/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-8]: https://github.com/fluencelabs/marine-rs-sdk-test/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-9]: https://github.com/fluencelabs/spell/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-merged-prs-10]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-closed_issues-1]: https://github.com/fluencelabs/fRPC-Substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fluence-closed_issues-2]: https://github.com/fluencelabs/registry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

167 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10]),
112 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
81 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8])

[fuel-merged-prs-1]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/sway-applications/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/sway-standards/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/sway-libs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuel-canary-watchtower/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/sway-applications/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway-standards/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/sway-libs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/sway-applications/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/sway-standards/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Inside Fuel: Q3 2023](https://fuel-labs.ghost.io/inside-fuel-q3-2023/)

#### [Golem](https://github.com/golemfactory)

59 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]),
68 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3]),
14 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/erc20_payment_lib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-merged-prs-5]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/erc20_payment_lib/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/erc20_payment_lib/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Grin](https://github.com/mimblewimble/grin)

6 merged PRs ([1][grin-merged-prs-1], [2][grin-merged-prs-2]),
0 closed issues,
1 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[grin-merged-prs-2]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

42 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4], [5][helium-merged-prs-5], [6][helium-merged-prs-6]),
9 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2], [3][helium-closed_issues-3]),
3 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2], [3][helium-open_issues-3])

[helium-merged-prs-1]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/oracles/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/proto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-merged-prs-5]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-merged-prs-6]: https://github.com/helium/xorf-generator/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-closed_issues-2]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-closed_issues-3]: https://github.com/helium/xorf-generator/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/oracles/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-open_issues-2]: https://github.com/helium/virtual-lorawan-device/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[helium-open_issues-3]: https://github.com/helium/xorf-generator/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

115 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4], [5][holochain-merged-prs-5], [6][holochain-merged-prs-6]),
32 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2], [3][holochain-closed_issues-3]),
13 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2], [3][holochain-open_issues-3], [4][holochain-open_issues-4])

[holochain-merged-prs-1]: https://github.com/holochain/tx5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-merged-prs-4]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-merged-prs-5]: https://github.com/holochain/scaffolding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-merged-prs-6]: https://github.com/holochain/influxive/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/tx5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-closed_issues-3]: https://github.com/holochain/scaffolding/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/tx5/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-open_issues-3]: https://github.com/holochain/scaffolding/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[holochain-open_issues-4]: https://github.com/holochain/deepkey/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [IOTA](https://github.com/iotaledger)

99 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3]),
78 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3]),
40 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2])

[iota-merged-prs-1]: https://github.com/iotaledger/iota-sdk-native-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[iota-closed_issues-3]: https://github.com/iotaledger/chronicle.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [A New Consensus Model: Nakamoto Consensus on a DAG](https://blog.iota.org/a-new-consensus-model-iota20/)
- [Data Structures Explained: The Parts that Make the Tangle](https://blog.iota.org/data-structures-explained-iota20/)
- [Understanding Congestion Control: Regulating Access in a Permissionless System](https://blog.iota.org/understanding-congestion-control-iota20/)
- [Finality Explained: How Nodes Sync the Ledger](https://blog.iota.org/finality-explained-iota20/)
- [Q3 2023 Progress Report](https://blog.iota.org/q3-2023-progress-report/)

#### [Maidsafe](https://github.com/maidsafe)

118 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4], [5][maidsafe-merged-prs-5]),
2 closed issues ([1][maidsafe-closed_issues-1]),
8 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn-node-manager/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/sn-releases/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/sn-testnet-deploy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[maidsafe-merged-prs-5]: https://github.com/maidsafe/self_encryption/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

17 merged PRs ([1][mina-merged-prs-1]),
7 closed issues ([1][mina-closed_issues-1], [2][mina-closed_issues-2]),
13 open issues ([1][mina-open_issues-1])

[mina-merged-prs-1]: https://github.com/openmina/openmina/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[mina-closed_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[mina-closed_issues-2]: https://github.com/openmina/openmina-poc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

50 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2], [3][mobilecoin-merged-prs-3]),
1 closed issues ([1][mobilecoin-closed_issues-1]),
0 open issues

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/attestation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[mobilecoin-merged-prs-3]: https://github.com/mobilecoinfoundation/sgx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

62 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3], [4][multiversx-merged-prs-4], [5][multiversx-merged-prs-5], [6][multiversx-merged-prs-6], [7][multiversx-merged-prs-7], [8][multiversx-merged-prs-8]),
1 closed issues ([1][multiversx-closed_issues-1]),
1 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-sovereign-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-merged-prs-4]: https://github.com/multiversx/mx-bridge-eth-sc-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-merged-prs-5]: https://github.com/multiversx/mx-contracts-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-merged-prs-6]: https://github.com/multiversx/mx-exchange-tools-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-merged-prs-7]: https://github.com/multiversx/mx-metabonding-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-merged-prs-8]: https://github.com/multiversx/mx-vm-executor-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-contracts-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

221 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10], [11][near-merged-prs-11], [12][near-merged-prs-12], [13][near-merged-prs-13], [14][near-merged-prs-14], [15][near-merged-prs-15], [16][near-merged-prs-16], [17][near-merged-prs-17]),
146 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8], [9][near-closed_issues-9], [10][near-closed_issues-10], [11][near-closed_issues-11], [12][near-closed_issues-12], [13][near-closed_issues-13], [14][near-closed_issues-14], [15][near-closed_issues-15], [16][near-closed_issues-16], [17][near-closed_issues-17], [18][near-closed_issues-18], [19][near-closed_issues-19], [20][near-closed_issues-20], [21][near-closed_issues-21], [22][near-closed_issues-22]),
130 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8], [9][near-open_issues-9], [10][near-open_issues-10], [11][near-open_issues-11], [12][near-open_issues-12], [13][near-open_issues-13], [14][near-open_issues-14], [15][near-open_issues-15], [16][near-open_issues-16], [17][near-open_issues-17], [18][near-open_issues-18], [19][near-open_issues-19], [20][near-open_issues-20], [21][near-open_issues-21], [22][near-open_issues-22], [23][near-open_issues-23], [24][near-open_issues-24], [25][near-open_issues-25], [26][near-open_issues-26], [27][near-open_issues-27], [28][near-open_issues-28], [29][near-open_issues-29], [30][near-open_issues-30], [31][near-open_issues-31], [32][near-open_issues-32])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-account-id-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-token-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/near-sdk-contract-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/near-gas-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-9]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-10]: https://github.com/near/near-workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-11]: https://github.com/near/mpc-recovery/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-12]: https://github.com/near/cargo-near/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-13]: https://github.com/near/pagoda-relayer-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-14]: https://github.com/near/neardevhub-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-15]: https://github.com/near/near-abi-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-16]: https://github.com/near/near-microindexers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-merged-prs-17]: https://github.com/near/read-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-account-id-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-token-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-7]: https://github.com/near/near-gas-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-8]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-9]: https://github.com/near/near-workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-10]: https://github.com/near/mpc-recovery/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-11]: https://github.com/near/cargo-near/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-12]: https://github.com/near/near-memory-tracker/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-13]: https://github.com/near/pagoda-relayer-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-14]: https://github.com/near/neardevhub-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-15]: https://github.com/near/near-microindexers/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-16]: https://github.com/near/near-enhanced-api-server/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-17]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-18]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-19]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-20]: https://github.com/near/near-linkdrop/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-21]: https://github.com/near/calibrator/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-closed_issues-22]: https://github.com/near/near-blake2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-account-id-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-token-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/near-gas-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-7]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-8]: https://github.com/near/near-workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-9]: https://github.com/near/mpc-recovery/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-10]: https://github.com/near/cargo-near/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-11]: https://github.com/near/bos-loader/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-12]: https://github.com/near/near-memory-tracker/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-13]: https://github.com/near/pagoda-relayer-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-14]: https://github.com/near/neardevhub-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-15]: https://github.com/near/near-abi-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-16]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-17]: https://github.com/near/near-microindexers/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-18]: https://github.com/near/near-enhanced-api-server/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-19]: https://github.com/near/near-lake-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-20]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-21]: https://github.com/near/near-abi-client-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-22]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-23]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-24]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-25]: https://github.com/near/near-linkdrop/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-26]: https://github.com/near/dkim-auth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-27]: https://github.com/near/sdk-rs-gas-benchmark/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-28]: https://github.com/near/near-sdk-abi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-29]: https://github.com/near/fast-kv-store/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-30]: https://github.com/near/nft-bid-market/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-31]: https://github.com/near/calibrator/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[near-open_issues-32]: https://github.com/near/near-blake2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [NEAR Query API Beta Is Now Open for Apps Building on B.O.S](https://pages.near.org/blog/near-query-api-beta-is-now-open-for-apps-building-on-b-o-s/)

#### [Nervos](https://github.com/nervosnetwork)

30 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6]),
6 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
6 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-light-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-sdk-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/nervosnetwork/ckb-standalone-debugger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-sdk-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/nervosnetwork/force-bridge-eth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-sdk-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

15 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]),
0 closed issues,
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/emerald-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[oasis-merged-prs-2]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Oasis Introduces Major Network Improvements With Core 23.0 Testnet Upgrade](https://oasisprotocol.org/blog/core-testnet-release-announcement)

#### [Parity](https://github.com/paritytech)

327 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15], [16][parity-merged-prs-16], [17][parity-merged-prs-17], [18][parity-merged-prs-18], [19][parity-merged-prs-19], [20][parity-merged-prs-20], [21][parity-merged-prs-21], [22][parity-merged-prs-22], [23][parity-merged-prs-23], [24][parity-merged-prs-24], [25][parity-merged-prs-25], [26][parity-merged-prs-26], [27][parity-merged-prs-27], [28][parity-merged-prs-28], [29][parity-merged-prs-29], [30][parity-merged-prs-30], [31][parity-merged-prs-31], [32][parity-merged-prs-32]),
124 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13], [14][parity-closed_issues-14], [15][parity-closed_issues-15], [16][parity-closed_issues-16], [17][parity-closed_issues-17], [18][parity-closed_issues-18], [19][parity-closed_issues-19], [20][parity-closed_issues-20], [21][parity-closed_issues-21], [22][parity-closed_issues-22]),
139 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14], [15][parity-open_issues-15], [16][parity-open_issues-16], [17][parity-open_issues-17], [18][parity-open_issues-18], [19][parity-open_issues-19], [20][parity-open_issues-20], [21][parity-open_issues-21], [22][parity-open_issues-22], [23][parity-open_issues-23], [24][parity-open_issues-24], [25][parity-open_issues-25])

[parity-merged-prs-1]: https://github.com/paritytech/polkadot-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/scale-info/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/substrate-telemetry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/subxt-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/try-runtime-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/mixnet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/polkadot-sdk-docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/arkworks-substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/ink-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/arkworks-extensions/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-15]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-16]: https://github.com/paritytech/zombienet-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-17]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-18]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-19]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-20]: https://github.com/paritytech/parity-db/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-21]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-22]: https://github.com/paritytech/trie/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-23]: https://github.com/paritytech/parity-scale-codec/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-24]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-25]: https://github.com/paritytech/extended-parachain-template/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-26]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-27]: https://github.com/paritytech/prdoc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-28]: https://github.com/paritytech/trappist/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-29]: https://github.com/paritytech/polkadot-introspector/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-30]: https://github.com/paritytech/substrate-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-31]: https://github.com/paritytech/orchestra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-merged-prs-32]: https://github.com/paritytech/smart-bench/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/subport/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/subxt-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/polkadot-sdk-docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/ink-examples/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/zombienet-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/parity-db/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-13]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-14]: https://github.com/paritytech/trie/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-15]: https://github.com/paritytech/parity-scale-codec/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-16]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-17]: https://github.com/paritytech/extended-parachain-template/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-18]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-19]: https://github.com/paritytech/prdoc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-20]: https://github.com/paritytech/trappist/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-21]: https://github.com/paritytech/polkadot-stps/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-closed_issues-22]: https://github.com/paritytech/parity-publish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/subxt-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/try-runtime-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/jsonrpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/polkadot-sdk-docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/zombienet-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-13]: https://github.com/paritytech/polkadot-interaction-examples-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-14]: https://github.com/paritytech/parity-db/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-15]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-16]: https://github.com/paritytech/parity-scale-codec/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-17]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-18]: https://github.com/paritytech/diener/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-19]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-20]: https://github.com/paritytech/prdoc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-21]: https://github.com/paritytech/frontier-parachain-template/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-22]: https://github.com/paritytech/trappist/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-23]: https://github.com/paritytech/substrate-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-24]: https://github.com/paritytech/parity-publish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[parity-open_issues-25]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Fungible Assets on Asset Hub](https://medium.com/polkadot-network/fungible-assets-on-asset-hub-c051d5ef5394)

#### [Radix](https://github.com/radixdlt)

37 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3], [4][radix-merged-prs-4]),
2 closed issues ([1][radix-closed_issues-1]),
1 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/radix-engine-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[radix-merged-prs-4]: https://github.com/radixdlt/babylon-ledger-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

11 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]),
2 closed issues ([1][secret_network-closed_issues-1], [2][secret_network-closed_issues-2]),
0 open issues

[secret_network-merged-prs-1]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[secret_network-closed_issues-2]: https://github.com/scrtlabs/snip20-reference-impl/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [2024 Secret Network Development Roadmap](https://scrt.network/blog/roadmap-2024)

#### [Solana](https://github.com/solana-labs/solana)

339 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3], [4][solana-merged-prs-4], [5][solana-merged-prs-5], [6][solana-merged-prs-6], [7][solana-merged-prs-7]),
108 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
54 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/perpetuals/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-merged-prs-3]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-merged-prs-4]: https://github.com/solana-labs/secure-wrap-token/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-merged-prs-5]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-merged-prs-6]: https://github.com/solana-labs/cargo-run-solana-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-merged-prs-7]: https://github.com/solana-labs/launchpad/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Soroban](https://github.com/stellar)

62 merged PRs ([1][soroban-merged-prs-1], [2][soroban-merged-prs-2], [3][soroban-merged-prs-3], [4][soroban-merged-prs-4], [5][soroban-merged-prs-5], [6][soroban-merged-prs-6]),
35 closed issues ([1][soroban-closed_issues-1], [2][soroban-closed_issues-2], [3][soroban-closed_issues-3], [4][soroban-closed_issues-4]),
39 open issues ([1][soroban-open_issues-1], [2][soroban-open_issues-2], [3][soroban-open_issues-3], [4][soroban-open_issues-4])

[soroban-merged-prs-1]: https://github.com/stellar/soroban-example-dapp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-merged-prs-2]: https://github.com/stellar/rs-soroban-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-merged-prs-3]: https://github.com/stellar/rs-soroban-env/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-merged-prs-4]: https://github.com/stellar/rs-stellar-xdr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-merged-prs-5]: https://github.com/stellar/soroban-quest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-merged-prs-6]: https://github.com/stellar/xdrgen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-closed_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-closed_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-closed_issues-3]: https://github.com/stellar/rs-stellar-xdr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-closed_issues-4]: https://github.com/stellar/xdrgen/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-open_issues-1]: https://github.com/stellar/soroban-examples/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-open_issues-2]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-open_issues-3]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[soroban-open_issues-4]: https://github.com/stellar/xdrgen/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Stellar Development Foundation Q3 2023 in Review](https://stellar.org/blog/foundation-news/stellar-development-foundation-q3-2023-in-review)
- [Sorobounty Spectacular: Dapp Tutorials You Can Use!](https://stellar.org/blog/developers/sorobounty-spectacular-dapp-tutorials)

#### [Spacemesh](https://github.com/spacemeshos)

10 merged PRs ([1][spacemesh-merged-prs-1]),
1 closed issues ([1][spacemesh-closed_issues-1]),
2 open issues ([1][spacemesh-open_issues-1])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/post-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/post-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[spacemesh-open_issues-1]: https://github.com/spacemeshos/post-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

138 merged PRs ([1][subspace_network-merged-prs-1], [2][subspace_network-merged-prs-2], [3][subspace_network-merged-prs-3]),
24 closed issues ([1][subspace_network-closed_issues-1]),
25 open issues ([1][subspace_network-open_issues-1], [2][subspace_network-open_issues-2], [3][subspace_network-open_issues-3])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[subspace_network-merged-prs-2]: https://github.com/subspace/subspace-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[subspace_network-merged-prs-3]: https://github.com/subspace/pulsar/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[subspace_network-open_issues-2]: https://github.com/subspace/subspace-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[subspace_network-open_issues-3]: https://github.com/subspace/pulsar/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Securing Dilithium with Proof-of-Time](https://blog.subspace.network/securing-dilithium-with-proof-of-time-26a82aa5b7e0)
- [Gemini 3 Phase 2 | Incentivized Testnet Gets An Upgrade](https://blog.subspace.network/gemini-3-phase-2-incentivized-testnet-gets-an-upgrade-f015c8727ebb)

#### [Sui](https://github.com/MystenLabs)

470 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2], [3][sui-merged-prs-3]),
74 closed issues ([1][sui-closed_issues-1], [2][sui-closed_issues-2]),
15 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[sui-merged-prs-2]: https://github.com/MystenLabs/fastcrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[sui-merged-prs-3]: https://github.com/MystenLabs/mysticeti/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[sui-closed_issues-2]: https://github.com/MystenLabs/fastcrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [View Verified Move Source Code in Sui Explorer](https://blog.sui.io/explorer-verified-source-code/)
- [Sui Linters and Warnings Update Increases Coder Velocity](https://blog.sui.io/linter-compile-warnings-update/)
- [Delivering Fair Gas Fees Through Resource Usage Metering](https://blog.sui.io/computation-costs-gas-fee-model/)

#### [Zcash](https://github.com/zcash)

20 merged PRs ([1][zcash-merged-prs-1]),
3 closed issues ([1][zcash-closed_issues-1]),
5 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2])

[zcash-merged-prs-1]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [New Release 5.7.0](https://electriccoin.co/blog/new-release-5-7-0/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

17 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3]),
18 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
20 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/rust-esplora-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/rust-esplora-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bdk-open_issues-4]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

17 merged PRs ([1][bitmask-merged-prs-1]),
8 closed issues ([1][bitmask-closed_issues-1]),
7 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

7 merged PRs ([1][electrs-merged-prs-1]),
2 closed issues ([1][electrs-closed_issues-1]),
1 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

89 merged PRs ([1][fedimint-merged-prs-1]),
77 closed issues ([1][fedimint-closed_issues-1]),
34 open issues ([1][fedimint-open_issues-1], [2][fedimint-open_issues-2])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[fedimint-open_issues-2]: https://github.com/fedimint/fedimint-custom-modules-example/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

57 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3], [4][ldk-merged-prs-4], [5][ldk-merged-prs-5], [6][ldk-merged-prs-6]),
16 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2], [3][ldk-closed_issues-3], [4][ldk-closed_issues-4]),
24 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2], [3][ldk-open_issues-3])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rapid-gossip-sync-server/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-merged-prs-4]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-merged-prs-5]: https://github.com/lightningdevkit/ldk-lsp-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-merged-prs-6]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rapid-gossip-sync-server/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-closed_issues-3]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-closed_issues-4]: https://github.com/lightningdevkit/ldk-lsp-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ldk-open_issues-3]: https://github.com/lightningdevkit/ldk-lsp-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

7 merged PRs ([1][lnp/bp-merged-prs-1]),
4 closed issues ([1][lnp/bp-closed_issues-1]),
1 open issues ([1][lnp/bp-open_issues-1])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

47 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]),
0 closed issues,
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/turbofish-org/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

10 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2], [3][rgb-merged-prs-3]),
8 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2]),
4 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2], [3][rgb-open_issues-3], [4][rgb-open_issues-4])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-merged-prs-3]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-open_issues-2]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-open_issues-3]: https://github.com/RGB-WG/rgb-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rgb-open_issues-4]: https://github.com/RGB-WG/rgb-schemata/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

55 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
18 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]),
15 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bech32/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/hex-conservative/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-bech32/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/hex-conservative/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bech32/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/hex-conservative/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

1 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

24 merged PRs ([1][ethers-rs-merged-prs-1]),
3 closed issues ([1][ethers-rs-closed_issues-1]),
6 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

197 merged PRs ([1][foundry-merged-prs-1], [2][foundry-merged-prs-2], [3][foundry-merged-prs-3], [4][foundry-merged-prs-4]),
156 closed issues ([1][foundry-closed_issues-1], [2][foundry-closed_issues-2], [3][foundry-closed_issues-3]),
136 open issues ([1][foundry-open_issues-1], [2][foundry-open_issues-2], [3][foundry-open_issues-3], [4][foundry-open_issues-4])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-merged-prs-2]: https://github.com/foundry-rs/starknet-foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-merged-prs-3]: https://github.com/foundry-rs/block-explorers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-merged-prs-4]: https://github.com/foundry-rs/compilers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-closed_issues-2]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-closed_issues-3]: https://github.com/foundry-rs/compilers/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-open_issues-2]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-open_issues-3]: https://github.com/foundry-rs/block-explorers/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[foundry-open_issues-4]: https://github.com/foundry-rs/compilers/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

26 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2], [3][lighthouse-merged-prs-3], [4][lighthouse-merged-prs-4], [5][lighthouse-merged-prs-5], [6][lighthouse-merged-prs-6]),
21 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2], [3][lighthouse-closed_issues-3]),
27 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2], [3][lighthouse-open_issues-3], [4][lighthouse-open_issues-4])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-merged-prs-3]: https://github.com/sigp/eleel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-merged-prs-4]: https://github.com/sigp/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-merged-prs-5]: https://github.com/sigp/milhouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-merged-prs-6]: https://github.com/sigp/superstruct/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-closed_issues-3]: https://github.com/sigp/enr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/eleel/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-open_issues-3]: https://github.com/sigp/ethereum_ssz/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[lighthouse-open_issues-4]: https://github.com/sigp/ssz_types/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [Quic Support](https://lighthouse-blog.sigmaprime.io/Quic.html)

#### [Polygon Zero](https://github.com/0xPolygonZero)

57 merged PRs ([1][polygon_zero-merged-prs-1], [2][polygon_zero-merged-prs-2], [3][polygon_zero-merged-prs-3], [4][polygon_zero-merged-prs-4]),
13 closed issues ([1][polygon_zero-closed_issues-1]),
7 open issues ([1][polygon_zero-open_issues-1])

[polygon_zero-merged-prs-1]: https://github.com/0xPolygonZero/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[polygon_zero-merged-prs-2]: https://github.com/0xPolygonZero/paladin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[polygon_zero-merged-prs-3]: https://github.com/0xPolygonZero/plonky-block-proof-gen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[polygon_zero-merged-prs-4]: https://github.com/0xPolygonZero/plonky-edge-block-trace-parser/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[polygon_zero-closed_issues-1]: https://github.com/0xPolygonZero/plonky2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[polygon_zero-open_issues-1]: https://github.com/0xPolygonZero/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

224 merged PRs ([1][reth-merged-prs-1]),
91 closed issues ([1][reth-closed_issues-1]),
62 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

1 merged PRs ([1][rust_web3-merged-prs-1]),
1 closed issues ([1][rust_web3-closed_issues-1]),
0 open issues

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[rust_web3-closed_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

312 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3], [4][starkware-merged-prs-4]),
17 closed issues ([1][starkware-closed_issues-1]),
6 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2], [3][starkware-open_issues-3])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/blockifier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[starkware-merged-prs-4]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/blockifier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[starkware-open_issues-3]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

- [7 Super Cool Dev Tools for Starknet Devs](https://medium.com/starkware/7-super-cool-dev-tools-for-starknet-devs-ea789febd5a0)

#### [zkSync](https://github.com/matter-labs/zksync)

275 merged PRs ([1][zksync_era-merged-prs-1], [2][zksync_era-merged-prs-2], [3][zksync_era-merged-prs-3], [4][zksync_era-merged-prs-4], [5][zksync_era-merged-prs-5], [6][zksync_era-merged-prs-6], [7][zksync_era-merged-prs-7], [8][zksync_era-merged-prs-8], [9][zksync_era-merged-prs-9], [10][zksync_era-merged-prs-10], [11][zksync_era-merged-prs-11], [12][zksync_era-merged-prs-12], [13][zksync_era-merged-prs-13], [14][zksync_era-merged-prs-14], [15][zksync_era-merged-prs-15], [16][zksync_era-merged-prs-16], [17][zksync_era-merged-prs-17], [18][zksync_era-merged-prs-18], [19][zksync_era-merged-prs-19], [20][zksync_era-merged-prs-20], [21][zksync_era-merged-prs-21], [22][zksync_era-merged-prs-22], [23][zksync_era-merged-prs-23]),
86 closed issues ([1][zksync_era-closed_issues-1], [2][zksync_era-closed_issues-2], [3][zksync_era-closed_issues-3], [4][zksync_era-closed_issues-4]),
10 open issues ([1][zksync_era-open_issues-1], [2][zksync_era-open_issues-2], [3][zksync_era-open_issues-3])

[zksync_era-merged-prs-1]: https://github.com/matter-labs/zksync-era/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-2]: https://github.com/matter-labs/zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-3]: https://github.com/matter-labs/era-revm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-4]: https://github.com/matter-labs/foundry-zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-5]: https://github.com/matter-labs/era-sync_vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-6]: https://github.com/matter-labs/era-compiler-llvm-builder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-7]: https://github.com/matter-labs/era-compiler-llvm-context/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-8]: https://github.com/matter-labs/franklin-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-9]: https://github.com/matter-labs/vise/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-10]: https://github.com/matter-labs/era-test-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-11]: https://github.com/matter-labs/era-consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-12]: https://github.com/matter-labs/era-zkevm_test_harness/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-13]: https://github.com/matter-labs/era-boojum/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-14]: https://github.com/matter-labs/era-compiler-vyper/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-15]: https://github.com/matter-labs/era-boojum-cuda/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-16]: https://github.com/matter-labs/era-compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-17]: https://github.com/matter-labs/era-zk_evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-18]: https://github.com/matter-labs/era-zkevm_opcode_defs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-19]: https://github.com/matter-labs/era-shivini/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-20]: https://github.com/matter-labs/era-compiler-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-21]: https://github.com/matter-labs/rescue-poseidon/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-22]: https://github.com/matter-labs/era-boojum-validator-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-merged-prs-23]: https://github.com/matter-labs/snark-wrapper/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-closed_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-closed_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-closed_issues-3]: https://github.com/matter-labs/vise/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-closed_issues-4]: https://github.com/matter-labs/era-test-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-open_issues-1]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-open_issues-2]: https://github.com/matter-labs/era-test-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot
[zksync_era-open_issues-3]: https://github.com/matter-labs/era-zkevm_test_harness/issues?q=is%3Aissue+is%3Aopen+created%3A2023-10-01..2023-10-31%20-author:app/dependabot

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

Nov 7-10 | Lisbon, Portugal | [Nearcon 23](https://near.org/nearcon23.near/widget/Index)

Nov 8-Dec 10 | Online | [Constellation Chainlink Hackathon](https://blog.chain.link/introducing-constellation-chainlink-hackathon/)

Nov 10-12 | Istanbul, Turkey | [ZK Hack Istanbul](https://www.zkistanbul.com/)

Nov 13-19 | Istanbul, Turkey | [Devconnect](https://devconnect.org/)

Nov 13-17 | Istanbul, Turkey | [LabWeek23](https://23.labweek.io/)

Nov 16-17 | Hollywood, CA, US and Virtual | [HackFest Summit 2023](https://www.sans.org/cyber-security-training-events/hackfest-summit-2023/)

Nov 17-19 | Istanbul, Turkey | [ETHGlobal Istanbul](https://ethglobal.com/events/istanbul)

Dec 8-10 | Bengaluru, India | [ETHIndia](https://ethindia.co/)


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


