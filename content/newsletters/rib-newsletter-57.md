---
title: "RiB Newsletter #57"
description: "February 2024"
date: 2024-03-06
categories:
  - "newsletters"
summary: "Welcome to the #57 edition of Rust in Blockchain.
This month, we spotlight `sp1`, a zkVM that runs Rust code."
---

Welcome to the #57 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #56](/newsletters/rib-newsletter-56/).

&nbsp;

## Thanks

Thanks to contributors:
[camilahanada],
[François Garillot],
Ganzaro,
[Igor Berlenko],
[Samuel Burnham],
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[camilahanada]: https://github.com/camilahanada
[François Garillot]: https://github.com/huitseeker
[Igor Berlenko]: https://github.com/7flash
[Samuel Burnham]: https://github.com/samuelburnham
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[sp1](https://github.com/succinctlabs/sp1).

This project is a zkVM that runs Rust code:
that is, code written in Rust can be compiled
to their specialized VM,
and upon execution a proof is generated;
later the proof can be used to efficiently verify
that the specific Rust code was executed with specific inputs and outputs.

It is similar in function to [RISC0](https://github.com/risc0/risc0),
and its Rust toolchain is said to be derived from RISC0,
but it uses as different proover, [Plonky3](https://github.com/Plonky3/),
and is claimed to be comparatively performant.

It is described in [a blog post](https://blog.succinct.xyz/introducing-sp1/).

&nbsp;


## Interesting Things

#### Blog Posts

- [Master fuzzing with our new Testing Handbook chapter](https://blog.trailofbits.com/2024/02/09/master-fuzzing-with-our-new-testing-handbook-chapter/)
- [LambdaClass: Our highly subjective view on the history of Zero-Knowledge Proofs](https://blog.lambdaclass.com/our-highly-subjective-view-on-the-history-of-zero-knowledge-proofs/)
- [Starknet and zkSync: A comparative analysis](https://medium.com/nethermind-eth/starknet-and-zksync-a-comparative-analysis-d4648786256b)
- [Introducing Citrea: Bitcoin’s First ZK Rollup](https://www.blog.citrea.xyz/introducing-citrea/)

#### Papers

- [Distributed Randomness using Weighted VRFs](https://eprint.iacr.org/2024/198)
- [OCash: Fully Anonymous Payments between Blockchain Light Clients](https://eprint.iacr.org/2024/246)
- [A Better Proof-of-Work Fork Choice Rule](https://eprint.iacr.org/2024/200)
- [A Two-Layer Blockchain Sharding Protocol Leveraging Safety and Liveness for Enhanced Performance](https://eprint.iacr.org/2024/304)
- [Parallel Zero-knowledge Virtual Machine](https://eprint.iacr.org/2024/387)
- [Proof of Diligence: Cryptoeconomic Security for Rollups](https://arxiv.org/abs/2402.07241)
- [Breaking BFT: Quantifying the Cost to Attack Bitcoin and Ethereum](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4727999)
- [SoK: Decentralized Storage Network](https://eprint.iacr.org/2024/258)
- [SoK: What don't we know? Understanding Security Vulnerabilities in SNARKs](https://arxiv.org/abs/2402.15293)
- [Circle STARKs](https://eprint.iacr.org/2024/278)
- [FRIDA: Data Availability Sampling from FRI](https://eprint.iacr.org/2024/248)
- [Rollerblade: Replicated Distributed Protocol Emulation on Top of Ledgers](https://eprint.iacr.org/2024/210)
- [Mastic: Private Weighted Heavy-Hitters and Attribute-Based Metrics](https://eprint.iacr.org/2024/221).
  Implementation: [Mastic](https://github.com/TrustworthyComputing/mastic)

#### Projects

- [vyper-rs](https://github.com/crypdoughdoteth/vyper-rs).
  A rust library to interact with the Vyper compiler.
- [SP1](https://github.com/succinctlabs/sp1).
  A zkVM that can prove the execution of arbitrary Rust (or any LLVM-compiled language) programs.
  Blog post: [Introducing SP1: A performant, 100% open-source, contributor-friendly zkVM](https://blog.succinct.xyz/introducing-sp1/).
- [sp1-reth](https://github.com/succinctlabs/sp1-reth).
  A performant, type-1 zkEVM written in Rust & SP1.

&nbsp;

## Most Active in February

[Starkware](https://github.com/starkware-libs):
493 merged PRs,
8 closed issues,
4 open issues

[Dfinity](https://github.com/dfinity):
491 merged PRs,
7 closed issues,
13 open issues

[Reth](https://github.com/paradigmxyz/reth):
363 merged PRs,
130 closed issues,
87 open issues

[Parity](https://github.com/paritytech):
324 merged PRs,
147 closed issues,
109 open issues

[zkSync Era](https://github.com/matter-labs/zksync-era):
313 merged PRs,
52 closed issues,
115 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

74 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
96 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
91 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/aleo-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [The Road to Aleo Mainnet](https://aleo.org/post/the-road-to-aleo-mainnet/)

#### [Anoma](https://github.com/anoma)

67 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2]),
121 closed issues ([1][anoma-closed_issues-1]),
95 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

301 merged PRs ([1][aptos-merged-prs-1], [2][aptos-merged-prs-2]),
49 closed issues ([1][aptos-closed_issues-1], [2][aptos-closed_issues-2]),
54 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aptos-merged-prs-2]: https://github.com/aptos-labs/aptos-indexer-processors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aptos-closed_issues-2]: https://github.com/aptos-labs/aptos-indexer-processors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Move Revealed: The Revela Decompiler](https://aptoslabs.medium.com/move-revealed-the-revela-decompiler-b206eaf48b45)

#### [Casper](https://github.com/casper-network)

35 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2], [3][casper-merged-prs-3]),
27 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
31 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/juliet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[casper-merged-prs-3]: https://github.com/casper-network/casper-sidecar/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/casper-sidecar/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/casper-sidecar/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Chainflip](https://github.com/chainflip-io)

101 merged PRs ([1][chainflip-merged-prs-1]),
176 closed issues ([1][chainflip-closed_issues-1]),
0 open issues

[chainflip-merged-prs-1]: https://github.com/chainflip-io/chainflip-backend/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[chainflip-closed_issues-1]: https://github.com/chainflip-io/chainflip-backend/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Chainflip Development Update — March 4th 2024](https://blog.chainflip.io/chainflip-development-update-march-4th-2024/)
- [Chainflip Development Update — February 8th 2024](https://blog.chainflip.io/dev-update-64/)

#### [COMIT](https://github.com/comit-network)

3 merged PRs ([1][comit-merged-prs-1]),
1 closed issues ([1][comit-closed_issues-1]),
1 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

20 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5]),
11 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]),
16 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-dapp-starter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-governance-committee-voting/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-governance-committee-voting/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-governance-committee-voting/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

8 merged PRs ([1][conflux-merged-prs-1]),
0 closed issues,
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Monthly Progress Report — February 2024](https://medium.com/conflux-network/monthly-progress-report-february-2024-fe5f2a1664ba)

#### [DarkFi](https://dark.fi)

0 merged PRs,
0 closed issues,
0 open issues

- [Public report of Darkfi circuits and crypto audit](https://www.zksecurity.xyz/blog/posts/darkfi/)

#### [Dfinity](https://github.com/dfinity)

491 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7], [8][dfinity-merged-prs-8], [9][dfinity-merged-prs-9], [10][dfinity-merged-prs-10], [11][dfinity-merged-prs-11], [12][dfinity-merged-prs-12], [13][dfinity-merged-prs-13], [14][dfinity-merged-prs-14], [15][dfinity-merged-prs-15], [16][dfinity-merged-prs-16], [17][dfinity-merged-prs-17], [18][dfinity-merged-prs-18], [19][dfinity-merged-prs-19], [20][dfinity-merged-prs-20]),
7 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4]),
13 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4], [5][dfinity-open_issues-5], [6][dfinity-open_issues-6], [7][dfinity-open_issues-7])

[dfinity-merged-prs-1]: https://github.com/dfinity/canbench/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/internet-identity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/nns-dapp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/exchange-rate-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-7]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-8]: https://github.com/dfinity/dre/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-9]: https://github.com/dfinity/bitcoin-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-10]: https://github.com/dfinity/ICRC-1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-11]: https://github.com/dfinity/dfx-extensions/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-12]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-13]: https://github.com/dfinity/stable-structures/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-14]: https://github.com/dfinity/cycles-ledger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-15]: https://github.com/dfinity/dfxvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-16]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-17]: https://github.com/dfinity/response-verification/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-18]: https://github.com/dfinity/metrics-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-19]: https://github.com/dfinity/canister-profiling/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-merged-prs-20]: https://github.com/dfinity/metrics-encoder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/internet-identity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/ICRC-1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-closed_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/canbench/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-open_issues-4]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-open_issues-5]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-open_issues-6]: https://github.com/dfinity/stable-structures/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dfinity-open_issues-7]: https://github.com/dfinity/metrics-encoder/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Dusk Network](https://github.com/dusk-network)

110 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5], [6][dusk_network-merged-prs-6], [7][dusk_network-merged-prs-7], [8][dusk_network-merged-prs-8]),
96 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4], [5][dusk_network-closed_issues-5], [6][dusk_network-closed_issues-6]),
31 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3], [4][dusk_network-open_issues-4], [5][dusk_network-open_issues-5])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/Poseidon252/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-merged-prs-4]: https://github.com/dusk-network/piecrust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-merged-prs-5]: https://github.com/dusk-network/bls12_381-bls/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-merged-prs-6]: https://github.com/dusk-network/jubjub-schnorr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-merged-prs-7]: https://github.com/dusk-network/citadel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-merged-prs-8]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/piecrust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-closed_issues-4]: https://github.com/dusk-network/bls12_381-bls/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-closed_issues-5]: https://github.com/dusk-network/jubjub-schnorr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-closed_issues-6]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/piecrust/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/bls12_381-bls/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-open_issues-4]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[dusk_network-open_issues-5]: https://github.com/dusk-network/kadcast/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

159 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5], [6][espresso_systems-merged-prs-6], [7][espresso_systems-merged-prs-7], [8][espresso_systems-merged-prs-8]),
124 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4], [5][espresso_systems-closed_issues-5], [6][espresso_systems-closed_issues-6]),
81 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4], [5][espresso_systems-open_issues-5], [6][espresso_systems-open_issues-6])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/espresso-polygon-zkevm-demo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/espresso-sequencer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/hs-builder-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-merged-prs-6]: https://github.com/EspressoSystems/hotshot-query-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-merged-prs-7]: https://github.com/EspressoSystems/hs-builder-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-merged-prs-8]: https://github.com/EspressoSystems/versioned-binary-serialization/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/hotshot-query-service/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-closed_issues-5]: https://github.com/EspressoSystems/hs-builder-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-closed_issues-6]: https://github.com/EspressoSystems/versioned-binary-serialization/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/espresso-polygon-zkevm-demo/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-open_issues-5]: https://github.com/EspressoSystems/hotshot-query-service/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[espresso_systems-open_issues-6]: https://github.com/EspressoSystems/versioned-binary-serialization/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

45 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5]),
7 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2]),
3 open issues ([1][filecoin-open_issues-1])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/filplus-backend/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/rust-sha2ni/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Filecoin CalibrationNet Version 22 Dragon Upgrade](https://status.filecoin.io/incidents/dbnd5ws12dpw)
- [Filecoin News 84](https://filecoin.io/blog/posts/filecoin-news-84/)
- [Filecoin News 83](https://filecoin.io/blog/posts/filecoin-news-83/)

#### [Findora](https://github.com/FindoraNetwork)

7 merged PRs ([1][findora-merged-prs-1]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

209 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7], [8][fluence-merged-prs-8], [9][fluence-merged-prs-9], [10][fluence-merged-prs-10], [11][fluence-merged-prs-11], [12][fluence-merged-prs-12], [13][fluence-merged-prs-13]),
0 closed issues,
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/nox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/decider/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/capacity-commitment-prover/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-8]: https://github.com/fluencelabs/fRPC-Substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-9]: https://github.com/fluencelabs/marine-rs-sdk-test/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-10]: https://github.com/fluencelabs/effectors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-11]: https://github.com/fluencelabs/randomx-rust-wrapper/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-12]: https://github.com/fluencelabs/spell/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fluence-merged-prs-13]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Fluence Mainnet Launch at ETH Denver](https://kill-the-newsletter.com/alternates/mgfrwn7jyjvr840e.html)
- [The Future is Cloudless: Fluence’s DePIN computing platform DAO and FLT token are now live](https://blog.fluence.network/the-future-is-cloudless-fluences-depin-computing-platform-and-flt-token-are-now-live/)
- [Contributed to open source Web3 in 2023? Check your eligibility for FLT developer reward!](https://blog.fluence.network/flt-developer-reward/)

#### [Fuel](https://github.com/FuelLabs)

135 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12], [13][fuel-merged-prs-13], [14][fuel-merged-prs-14]),
153 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
86 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8], [9][fuel-open_issues-9])

[fuel-merged-prs-1]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/sway-applications/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/sway-standards/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuel-subgraph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-10]: https://github.com/FuelLabs/Solana-Wallet-Connector/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-11]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-12]: https://github.com/FuelLabs/sway-libs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-13]: https://github.com/FuelLabs/intro-to-predicates/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-merged-prs-14]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/sway-applications/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway-standards/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/sway-standards/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuel-subgraph/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fuel-open_issues-9]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Beta-5: Staging Network Upgrade](https://fuel.mirror.xyz/5JCTjM3jSG84QYLKqQ4idHf6X_zVtwTInQvg7kWhaMA)
- [The Rollup OS for Ethereum](https://fuel.mirror.xyz/uYMT39LiB538Q61Mgf4bRrsAwApJSeNiG_afDHhOhGs)

#### [Golem](https://github.com/golemfactory)

60 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]),
72 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3], [4][golem-closed_issues-4], [5][golem-closed_issues-5]),
25 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-runtime-ai/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-merged-prs-5]: https://github.com/golemfactory/erc20_payment_lib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-runtime-ai/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/erc20_payment_lib/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-closed_issues-4]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-closed_issues-5]: https://github.com/golemfactory/gvmkit-build-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-runtime-ai/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[golem-open_issues-3]: https://github.com/golemfactory/erc20_payment_lib/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Update on Golem GPU Beta Testing Program](https://blog.golem.network/update-on-golem-gpu-beta-testing-program/)
- [Reputation System: Experimental Version Roll-Out](https://blog.golem.network/reputation-system-experimental-version-roll-out/)

#### [Grin](https://github.com/mimblewimble/grin)

10 merged PRs ([1][grin-merged-prs-1], [2][grin-merged-prs-2], [3][grin-merged-prs-3]),
7 closed issues ([1][grin-closed_issues-1], [2][grin-closed_issues-2], [3][grin-closed_issues-3]),
3 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[grin-merged-prs-2]: https://github.com/mimblewimble/grin-gui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[grin-merged-prs-3]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[grin-closed_issues-2]: https://github.com/mimblewimble/grin-gui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[grin-closed_issues-3]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[grin-open_issues-1]: https://github.com/mimblewimble/grin-gui/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Helium](https://github.com/helium)

35 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4], [5][helium-merged-prs-5], [6][helium-merged-prs-6], [7][helium-merged-prs-7]),
0 closed issues (),
3 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2])

[helium-merged-prs-1]: https://github.com/helium/proto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/oracles/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-data/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-merged-prs-5]: https://github.com/helium/helium-anchor-gen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-merged-prs-6]: https://github.com/helium/virtual-lorawan-device/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-merged-prs-7]: https://github.com/helium/lorawan-h3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[helium-open_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

113 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4], [5][holochain-merged-prs-5]),
14 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2], [3][holochain-closed_issues-3]),
16 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/scaffolding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-merged-prs-4]: https://github.com/holochain/tx5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-merged-prs-5]: https://github.com/holochain/deepkey/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/scaffolding/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-closed_issues-3]: https://github.com/holochain/tx5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/scaffolding/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Holochain: A New Link in Web3](https://blog.holochain.org/holochain-a-new-link-in-web3/)
- [Verifying Energy](https://blog.holochain.org/verifying-energy/)
- [Holochain 0.2 is here!](https://blog.holochain.org/holochain-0-2-is-here/)
- [A Strange New Contraption](https://blog.holochain.org/a-strange-new-contraption/)

#### [IOTA](https://github.com/iotaledger)

113 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5]),
91 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5], [6][iota-closed_issues-6]),
56 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3])

[iota-merged-prs-1]: https://github.com/iotaledger/iota-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/inx-chronicle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/sd-jwt-payload/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/common-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/inx-chronicle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-closed_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-closed_issues-4]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-closed_issues-5]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-closed_issues-6]: https://github.com/iotaledger/iota-sdk-native-bindings/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/inx-chronicle/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Introducing the IOTA Legacy Migration Tool](https://blog.iota.org/iota-legacy-migration-tool/)

#### [Lurk](https://github.com/lurk-lab)

135 merged PRs ([1][lurk-merged-prs-1], [2][lurk-merged-prs-2], [3][lurk-merged-prs-3], [4][lurk-merged-prs-4], [5][lurk-merged-prs-5], [6][lurk-merged-prs-6], [7][lurk-merged-prs-7], [8][lurk-merged-prs-8], [9][lurk-merged-prs-9]),
59 closed issues ([1][lurk-closed_issues-1], [2][lurk-closed_issues-2], [3][lurk-closed_issues-3], [4][lurk-closed_issues-4], [5][lurk-closed_issues-5], [6][lurk-closed_issues-6], [7][lurk-closed_issues-7], [8][lurk-closed_issues-8]),
29 open issues ([1][lurk-open_issues-1], [2][lurk-open_issues-2], [3][lurk-open_issues-3], [4][lurk-open_issues-4], [5][lurk-open_issues-5], [6][lurk-open_issues-6], [7][lurk-open_issues-7], [8][lurk-open_issues-8])

[lurk-merged-prs-1]: https://github.com/lurk-lab/circom-scotia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-2]: https://github.com/lurk-lab/bellpepper/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-3]: https://github.com/lurk-lab/lurk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-4]: https://github.com/lurk-lab/arecibo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-5]: https://github.com/lurk-lab/bellpepper-gadgets/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-6]: https://github.com/lurk-lab/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-7]: https://github.com/lurk-lab/template-rust-lib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-8]: https://github.com/lurk-lab/ci-workflows/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-merged-prs-9]: https://github.com/lurk-lab/grumpkin-msm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-1]: https://github.com/lurk-lab/bellpepper/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-2]: https://github.com/lurk-lab/lurk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-3]: https://github.com/lurk-lab/arecibo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-4]: https://github.com/lurk-lab/bellpepper-gadgets/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-5]: https://github.com/lurk-lab/neptune/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-6]: https://github.com/lurk-lab/template-rust-lib/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-7]: https://github.com/lurk-lab/ci-workflows/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-closed_issues-8]: https://github.com/lurk-lab/ci-lab/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-1]: https://github.com/lurk-lab/circom-scotia/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-2]: https://github.com/lurk-lab/bellpepper/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-3]: https://github.com/lurk-lab/lurk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-4]: https://github.com/lurk-lab/arecibo/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-5]: https://github.com/lurk-lab/bellpepper-gadgets/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-6]: https://github.com/lurk-lab/neptune/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-7]: https://github.com/lurk-lab/ci-workflows/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lurk-open_issues-8]: https://github.com/lurk-lab/ci-lab/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

110 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4]),
1 closed issues ([1][maidsafe-closed_issues-1]),
4 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/sn-releases/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/sn-testnet-deploy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/safeup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/qp2p/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

34 merged PRs ([1][mina-merged-prs-1], [2][mina-merged-prs-2]),
0 closed issues,
3 open issues ([1][mina-open_issues-1], [2][mina-open_issues-2])

[mina-merged-prs-1]: https://github.com/openmina/openmina/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[mina-merged-prs-2]: https://github.com/openmina/state_machine_exp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[mina-open_issues-2]: https://github.com/openmina/mina-network-debugger/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

4 merged PRs ([1][mobilecoin-merged-prs-1]),
1 closed issues ([1][mobilecoin-closed_issues-1]),
1 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/sgx/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

65 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3], [4][multiversx-merged-prs-4], [5][multiversx-merged-prs-5], [6][multiversx-merged-prs-6], [7][multiversx-merged-prs-7]),
1 closed issues ([1][multiversx-closed_issues-1]),
0 open issues

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-bridge-eth-sc-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-exchange-tools-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[multiversx-merged-prs-4]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[multiversx-merged-prs-5]: https://github.com/multiversx/mx-contracts-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[multiversx-merged-prs-6]: https://github.com/multiversx/mx-sovereign-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[multiversx-merged-prs-7]: https://github.com/multiversx/mx-subscription-fee-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

185 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10], [11][near-merged-prs-11], [12][near-merged-prs-12], [13][near-merged-prs-13], [14][near-merged-prs-14]),
72 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8]),
63 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8], [9][near-open_issues-9], [10][near-open_issues-10], [11][near-open_issues-11], [12][near-open_issues-12])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/read-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/queryapi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/cargo-near/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/cargo-near-new-project-template/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/mpc-recovery/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-9]: https://github.com/near/near-workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-10]: https://github.com/near/bos-loader/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-11]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-12]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-13]: https://github.com/near/near-light-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-merged-prs-14]: https://github.com/near/sw4-account-creator/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/queryapi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/mpc-recovery/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-7]: https://github.com/near/near-sdk-contract-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-closed_issues-8]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/queryapi/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/cargo-near/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-7]: https://github.com/near/mpc-recovery/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-8]: https://github.com/near/near-workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-9]: https://github.com/near/near-sdk-contract-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-10]: https://github.com/near/bos-loader/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-11]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[near-open_issues-12]: https://github.com/near/near-light-client/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Nervos](https://github.com/nervosnetwork)

35 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7]),
6 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3]),
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-light-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/nervosnetwork/ckb-sdk-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-merged-prs-7]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-light-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

5 merged PRs ([1][oasis-merged-prs-1]),
1 closed issues ([1][oasis-closed_issues-1]),
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

324 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15], [16][parity-merged-prs-16], [17][parity-merged-prs-17], [18][parity-merged-prs-18], [19][parity-merged-prs-19], [20][parity-merged-prs-20], [21][parity-merged-prs-21], [22][parity-merged-prs-22], [23][parity-merged-prs-23], [24][parity-merged-prs-24], [25][parity-merged-prs-25], [26][parity-merged-prs-26], [27][parity-merged-prs-27], [28][parity-merged-prs-28], [29][parity-merged-prs-29], [30][parity-merged-prs-30]),
147 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13], [14][parity-closed_issues-14], [15][parity-closed_issues-15], [16][parity-closed_issues-16], [17][parity-closed_issues-17]),
109 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14])

[parity-merged-prs-1]: https://github.com/paritytech/polkadot-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/substrate-telemetry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/zombienet-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/ss58-registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/parity-db/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/prdoc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/trappist/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-15]: https://github.com/paritytech/ink-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-16]: https://github.com/paritytech/soketto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-17]: https://github.com/paritytech/scale-type-resolver/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-18]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-19]: https://github.com/paritytech/subxt-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-20]: https://github.com/paritytech/smart-bench/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-21]: https://github.com/paritytech/try-runtime-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-22]: https://github.com/paritytech/polkadot-introspector/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-23]: https://github.com/paritytech/erasure-coding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-24]: https://github.com/paritytech/disabling-e2e-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-25]: https://github.com/paritytech/scale-decode/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-26]: https://github.com/paritytech/scale-typegen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-27]: https://github.com/paritytech/scale-value/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-28]: https://github.com/paritytech/scale-info/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-29]: https://github.com/paritytech/scale-bits/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-merged-prs-30]: https://github.com/paritytech/scale-encode/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/zombienet-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/subport/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/trappist/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/trie/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-13]: https://github.com/paritytech/subxt-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-14]: https://github.com/paritytech/polkadot-introspector/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-15]: https://github.com/paritytech/erasure-coding/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-16]: https://github.com/paritytech/polkadot-sdk-docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-closed_issues-17]: https://github.com/paritytech/scale-decode/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/zombienet-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/subport/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/jsonrpc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/prdoc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/parity-tokio-ipc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/try-runtime-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/polkadot-sdk-docs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-13]: https://github.com/paritytech/scale-decode/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[parity-open_issues-14]: https://github.com/paritytech/scale-typegen/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Nearly Optimal State Merklization (in Polkadot-SDK)](https://www.rob.tech/blog/nearly-optimal-polkadot-merklization/)

#### [Radix](https://github.com/radixdlt)

51 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3], [4][radix-merged-prs-4], [5][radix-merged-prs-5], [6][radix-merged-prs-6]),
0 closed issues,
3 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/wallet-compatible-derivation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/babylon-ledger-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[radix-merged-prs-4]: https://github.com/radixdlt/sargon/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[radix-merged-prs-5]: https://github.com/radixdlt/radix-engine-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[radix-merged-prs-6]: https://github.com/radixdlt/official-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Thoughts on Sui’s MoveVM](https://www.radixdlt.com/blog/thoughts-on-suis-movevm)
- [How Radix Engine Avoids the Flaws of Sui's MoveVM](https://www.radixdlt.com/blog/how-radix-engine-avoids-the-flaws-of-suis-movevm)

#### [Solana](https://github.com/solana-labs/solana)

220 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
122 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
25 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Soroban](https://github.com/stellar)

50 merged PRs ([1][soroban-merged-prs-1], [2][soroban-merged-prs-2], [3][soroban-merged-prs-3], [4][soroban-merged-prs-4], [5][soroban-merged-prs-5], [6][soroban-merged-prs-6]),
12 closed issues ([1][soroban-closed_issues-1], [2][soroban-closed_issues-2], [3][soroban-closed_issues-3]),
16 open issues ([1][soroban-open_issues-1], [2][soroban-open_issues-2], [3][soroban-open_issues-3], [4][soroban-open_issues-4])

[soroban-merged-prs-1]: https://github.com/stellar/rs-soroban-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-merged-prs-2]: https://github.com/stellar/soroban-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-merged-prs-3]: https://github.com/stellar/rs-soroban-env/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-merged-prs-4]: https://github.com/stellar/soroban-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-merged-prs-5]: https://github.com/stellar/rs-stellar-xdr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-merged-prs-6]: https://github.com/stellar/soroban-quest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-closed_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-closed_issues-2]: https://github.com/stellar/soroban-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-closed_issues-3]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-open_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-open_issues-2]: https://github.com/stellar/soroban-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-open_issues-3]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[soroban-open_issues-4]: https://github.com/stellar/rs-stellar-xdr/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Validator Guide to Soroban Mainnet Phase 1](https://stellar.org/blog/developers/validator-guide-to-soroban-mainnet-phase-1)
- [Protocol 20 and Smart Contracts Are Live on Mainnet](https://stellar.org/blog/developers/protocol-20-and-smart-contracts-are-live-on-mainnet)

#### [Spacemesh](https://github.com/spacemeshos)

6 merged PRs ([1][spacemesh-merged-prs-1], [2][spacemesh-merged-prs-2]),
3 closed issues ([1][spacemesh-closed_issues-1]),
2 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/quicksync-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[spacemesh-merged-prs-2]: https://github.com/spacemeshos/post-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/post-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[spacemesh-open_issues-1]: https://github.com/spacemeshos/quicksync-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[spacemesh-open_issues-2]: https://github.com/spacemeshos/post-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

74 merged PRs ([1][subspace_network-merged-prs-1], [2][subspace_network-merged-prs-2]),
23 closed issues ([1][subspace_network-closed_issues-1], [2][subspace_network-closed_issues-2]),
20 open issues ([1][subspace_network-open_issues-1], [2][subspace_network-open_issues-2])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[subspace_network-merged-prs-2]: https://github.com/subspace/space-acres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[subspace_network-closed_issues-2]: https://github.com/subspace/space-acres/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[subspace_network-open_issues-2]: https://github.com/subspace/space-acres/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

356 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2], [3][sui-merged-prs-3], [4][sui-merged-prs-4], [5][sui-merged-prs-5]),
37 closed issues ([1][sui-closed_issues-1], [2][sui-closed_issues-2]),
13 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[sui-merged-prs-2]: https://github.com/MystenLabs/zklogin-verifier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[sui-merged-prs-3]: https://github.com/MystenLabs/fastcrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[sui-merged-prs-4]: https://github.com/MystenLabs/scion-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[sui-merged-prs-5]: https://github.com/MystenLabs/mysten-sim/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[sui-closed_issues-2]: https://github.com/MystenLabs/scion-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Shared Object Deletion Now Available On Sui](https://blog.sui.io/ephemeral-shared-objects/)
- [Enabling Zero Auth Downloads for Node Operators at a Tenth of the Cost](https://blog.sui.io/aws-s3-cloudflare-r2-snapshot/)
- [Sui Developer Newsletter (#3)](https://sui-23860326.hs-sites.com/sui-dev-newsletter-3)
- [Videos: MoveDevConf 2024](https://www.youtube.com/playlist?list=PL9t2y-BKvZBRfiyhgCU_jevh_X7-KsrfW)

#### [Zcash](https://github.com/zcash)

23 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4]),
17 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4]),
31 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/sapling-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/sapling-crypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/sapling-crypto/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

5 merged PRs ([1][aluvm-merged-prs-1]),
3 closed issues ([1][aluvm-closed_issues-1]),
0 open issues

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[aluvm-closed_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

15 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]),
9 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2]),
29 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4], [5][bdk-open_issues-5])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/rust-esplora-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-esplora-client/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bdk-open_issues-5]: https://github.com/bitcoindevkit/book-of-bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Bitcoin Protocol](https://github.com/BP-WG)

9 merged PRs ([1][bitcoin_protocol-merged-prs-1], [2][bitcoin_protocol-merged-prs-2], [3][bitcoin_protocol-merged-prs-3]),
3 closed issues ([1][bitcoin_protocol-closed_issues-1], [2][bitcoin_protocol-closed_issues-2]),
0 open issues

[bitcoin_protocol-merged-prs-1]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitcoin_protocol-merged-prs-2]: https://github.com/BP-WG/bp-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitcoin_protocol-merged-prs-3]: https://github.com/BP-WG/bp-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitcoin_protocol-closed_issues-1]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitcoin_protocol-closed_issues-2]: https://github.com/BP-WG/bp-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

1 merged PRs ([1][bitmask-merged-prs-1]),
0 closed issues,
2 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Bitswap](https://github.com/BitSwap-BiFi)

28 merged PRs ([1][bitswap-merged-prs-1], [2][bitswap-merged-prs-2]),
4 closed issues ([1][bitswap-closed_issues-1]),
1 open issues ([1][bitswap-open_issues-1])

[bitswap-merged-prs-1]: https://github.com/BitSwap-BiFi/Bitswap-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitswap-merged-prs-2]: https://github.com/BitSwap-BiFi/bitswap-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitswap-closed_issues-1]: https://github.com/BitSwap-BiFi/Bitswap-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[bitswap-open_issues-1]: https://github.com/BitSwap-BiFi/Bitswap-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Cyphernet](https://github.com/cyphernet-dao)

2 merged PRs ([1][cyphernet-merged-prs-1]),
1 closed issues ([1][cyphernet-closed_issues-1]),
0 open issues

[cyphernet-merged-prs-1]: https://github.com/cyphernet-dao/rust-netservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[cyphernet-closed_issues-1]: https://github.com/cyphernet-dao/rust-netservices/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

2 merged PRs ([1][electrs-merged-prs-1]),
5 closed issues ([1][electrs-closed_issues-1]),
2 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

142 merged PRs ([1][fedimint-merged-prs-1]),
50 closed issues ([1][fedimint-closed_issues-1]),
47 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

81 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3], [4][ldk-merged-prs-4], [5][ldk-merged-prs-5], [6][ldk-merged-prs-6], [7][ldk-merged-prs-7]),
24 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2], [3][ldk-closed_issues-3], [4][ldk-closed_issues-4]),
10 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2], [3][ldk-open_issues-3])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/ldk-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/lightning-liquidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-merged-prs-4]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-merged-prs-5]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-merged-prs-6]: https://github.com/lightningdevkit/vss-rust-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-merged-prs-7]: https://github.com/lightningdevkit/rapid-gossip-sync-server/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-closed_issues-3]: https://github.com/lightningdevkit/lightning-liquidity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-closed_issues-4]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/lightning-liquidity/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ldk-open_issues-3]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

6 merged PRs ([1][lnp/bp-merged-prs-1]),
0 closed issues,
0 open issues

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

27 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]),
1 closed issues ([1][nomic-closed_issues-1]),
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/turbofish-org/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[nomic-closed_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

18 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2], [3][rgb-merged-prs-3], [4][rgb-merged-prs-4]),
17 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2], [3][rgb-closed_issues-3], [4][rgb-closed_issues-4]),
4 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-merged-prs-3]: https://github.com/RGB-WG/rgb-schemata/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-merged-prs-4]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rgb-std/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-closed_issues-3]: https://github.com/RGB-WG/rgb-schemata/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-closed_issues-4]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rgb-open_issues-2]: https://github.com/RGB-WG/rgb-schemata/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

52 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
19 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]),
25 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/hex-conservative/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/rust-bech32/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/hex-conservative/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bech32/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/hex-conservative/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Rust Payjoin](https://github.com/payjoin/rust-payjoin)

11 merged PRs ([1][rust_payjoin-merged-prs-1]),
6 closed issues ([1][rust_payjoin-closed_issues-1]),
0 open issues

[rust_payjoin-merged-prs-1]: https://github.com/payjoin/rust-payjoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_payjoin-closed_issues-1]: https://github.com/payjoin/rust-payjoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

3 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Strict Types](https://github.com/strict-types)

8 merged PRs ([1][strict_types-merged-prs-1], [2][strict_types-merged-prs-2]),
1 closed issues ([1][strict_types-closed_issues-1]),
4 open issues ([1][strict_types-open_issues-1])

[strict_types-merged-prs-1]: https://github.com/strict-types/strict-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[strict_types-merged-prs-2]: https://github.com/strict-types/strict-encoding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[strict_types-closed_issues-1]: https://github.com/strict-types/strict-encoding/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[strict_types-open_issues-1]: https://github.com/strict-types/strict-types/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

21 merged PRs ([1][ethers-rs-merged-prs-1]),
1 closed issues ([1][ethers-rs-closed_issues-1]),
7 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

239 merged PRs ([1][foundry-merged-prs-1], [2][foundry-merged-prs-2], [3][foundry-merged-prs-3], [4][foundry-merged-prs-4], [5][foundry-merged-prs-5]),
204 closed issues ([1][foundry-closed_issues-1], [2][foundry-closed_issues-2], [3][foundry-closed_issues-3]),
119 open issues ([1][foundry-open_issues-1], [2][foundry-open_issues-2], [3][foundry-open_issues-3], [4][foundry-open_issues-4])

[foundry-merged-prs-1]: https://github.com/foundry-rs/starknet-foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-merged-prs-2]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-merged-prs-3]: https://github.com/foundry-rs/foundry-rust-template/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-merged-prs-4]: https://github.com/foundry-rs/block-explorers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-merged-prs-5]: https://github.com/foundry-rs/compilers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-closed_issues-2]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-closed_issues-3]: https://github.com/foundry-rs/compilers/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-open_issues-2]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-open_issues-3]: https://github.com/foundry-rs/block-explorers/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[foundry-open_issues-4]: https://github.com/foundry-rs/compilers/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

68 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2], [3][lighthouse-merged-prs-3], [4][lighthouse-merged-prs-4]),
30 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]),
22 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2], [3][lighthouse-open_issues-3])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-merged-prs-3]: https://github.com/sigp/milagro_bls/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-merged-prs-4]: https://github.com/sigp/superstruct/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/superstruct/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[lighthouse-open_issues-3]: https://github.com/sigp/superstruct/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [New release: Diablo Verde](https://github.com/sigp/lighthouse/releases/tag/v5.0.0). Mainnet Upgrade.

#### [Polygon Zero](https://github.com/0xPolygonZero)

78 merged PRs ([1][polygon_zero-merged-prs-1], [2][polygon_zero-merged-prs-2], [3][polygon_zero-merged-prs-3], [4][polygon_zero-merged-prs-4], [5][polygon_zero-merged-prs-5], [6][polygon_zero-merged-prs-6], [7][polygon_zero-merged-prs-7]),
21 closed issues ([1][polygon_zero-closed_issues-1], [2][polygon_zero-closed_issues-2], [3][polygon_zero-closed_issues-3], [4][polygon_zero-closed_issues-4]),
26 open issues ([1][polygon_zero-open_issues-1], [2][polygon_zero-open_issues-2], [3][polygon_zero-open_issues-3], [4][polygon_zero-open_issues-4], [5][polygon_zero-open_issues-5])

[polygon_zero-merged-prs-1]: https://github.com/0xPolygonZero/zk_evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-merged-prs-2]: https://github.com/0xPolygonZero/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-merged-prs-3]: https://github.com/0xPolygonZero/eth-tx-proof/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-merged-prs-4]: https://github.com/0xPolygonZero/zero-bin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-merged-prs-5]: https://github.com/0xPolygonZero/paladin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-merged-prs-6]: https://github.com/0xPolygonZero/evm-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-merged-prs-7]: https://github.com/0xPolygonZero/proof-protocol-decoder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-closed_issues-1]: https://github.com/0xPolygonZero/zk_evm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-closed_issues-2]: https://github.com/0xPolygonZero/plonky2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-closed_issues-3]: https://github.com/0xPolygonZero/eth-tx-proof/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-closed_issues-4]: https://github.com/0xPolygonZero/zero-bin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-open_issues-1]: https://github.com/0xPolygonZero/zk_evm/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-open_issues-2]: https://github.com/0xPolygonZero/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-open_issues-3]: https://github.com/0xPolygonZero/eth-tx-proof/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-open_issues-4]: https://github.com/0xPolygonZero/zero-bin/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[polygon_zero-open_issues-5]: https://github.com/0xPolygonZero/evm-tests/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

363 merged PRs ([1][reth-merged-prs-1]),
130 closed issues ([1][reth-closed_issues-1]),
87 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Rust Ethereum](https://github.com/rust-ethereum)

3 merged PRs ([1][rust_ethereum-merged-prs-1]),
3 closed issues ([1][rust_ethereum-closed_issues-1]),
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethereum/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethereum/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

493 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3], [4][starkware-merged-prs-4], [5][starkware-merged-prs-5]),
8 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
4 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2])

[starkware-merged-prs-1]: https://github.com/starkware-libs/stwo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-merged-prs-4]: https://github.com/starkware-libs/blockifier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-merged-prs-5]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/blockifier/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [Stwo Prover: the next-gen of STARK scaling is here](https://medium.com/starkware/stwo-prover-the-next-gen-of-stark-scaling-is-here-f7429e764127)

#### [zkSync Era](https://github.com/matter-labs/zksync-era)

313 merged PRs ([1][zksync_era-merged-prs-1], [2][zksync_era-merged-prs-2], [3][zksync_era-merged-prs-3], [4][zksync_era-merged-prs-4], [5][zksync_era-merged-prs-5], [6][zksync_era-merged-prs-6], [7][zksync_era-merged-prs-7], [8][zksync_era-merged-prs-8], [9][zksync_era-merged-prs-9], [10][zksync_era-merged-prs-10], [11][zksync_era-merged-prs-11], [12][zksync_era-merged-prs-12], [13][zksync_era-merged-prs-13], [14][zksync_era-merged-prs-14], [15][zksync_era-merged-prs-15], [16][zksync_era-merged-prs-16], [17][zksync_era-merged-prs-17], [18][zksync_era-merged-prs-18], [19][zksync_era-merged-prs-19], [20][zksync_era-merged-prs-20], [21][zksync_era-merged-prs-21], [22][zksync_era-merged-prs-22], [23][zksync_era-merged-prs-23]),
52 closed issues ([1][zksync_era-closed_issues-1], [2][zksync_era-closed_issues-2], [3][zksync_era-closed_issues-3], [4][zksync_era-closed_issues-4], [5][zksync_era-closed_issues-5], [6][zksync_era-closed_issues-6]),
115 open issues ([1][zksync_era-open_issues-1], [2][zksync_era-open_issues-2], [3][zksync_era-open_issues-3], [4][zksync_era-open_issues-4], [5][zksync_era-open_issues-5], [6][zksync_era-open_issues-6], [7][zksync_era-open_issues-7], [8][zksync_era-open_issues-8])

[zksync_era-merged-prs-1]: https://github.com/matter-labs/zksync-era/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-2]: https://github.com/matter-labs/foundry-zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-3]: https://github.com/matter-labs/zksync-withdrawal-finalizer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-4]: https://github.com/matter-labs/era-boojum-validator-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-5]: https://github.com/matter-labs/era-test-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-6]: https://github.com/matter-labs/era-zkevm_circuits/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-7]: https://github.com/matter-labs/era-zkevm_test_harness/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-8]: https://github.com/matter-labs/era-compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-9]: https://github.com/matter-labs/era-compiler-llvm-context/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-10]: https://github.com/matter-labs/era-boojum/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-11]: https://github.com/matter-labs/era-compiler-vyper/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-12]: https://github.com/matter-labs/era-zkevm_tester/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-13]: https://github.com/matter-labs/era-consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-14]: https://github.com/matter-labs/era-boojum-cuda/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-15]: https://github.com/matter-labs/era-shivini/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-16]: https://github.com/matter-labs/era-cuda/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-17]: https://github.com/matter-labs/era-compiler-llvm-builder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-18]: https://github.com/matter-labs/M1_algebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-19]: https://github.com/matter-labs/teepot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-20]: https://github.com/matter-labs/snark-wrapper/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-21]: https://github.com/matter-labs/era-zk_evm_abstractions/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-22]: https://github.com/matter-labs/era-zkevm_opcode_defs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-merged-prs-23]: https://github.com/matter-labs/era-compiler-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-closed_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-closed_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-closed_issues-3]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-closed_issues-4]: https://github.com/matter-labs/era-boojum-validator-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-closed_issues-5]: https://github.com/matter-labs/era-test-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-closed_issues-6]: https://github.com/matter-labs/era-zkevm_test_harness/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-3]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-4]: https://github.com/matter-labs/era-boojum-validator-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-5]: https://github.com/matter-labs/era-test-node/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-6]: https://github.com/matter-labs/era-boojum/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-7]: https://github.com/matter-labs/franklin-crypto/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot
[zksync_era-open_issues-8]: https://github.com/matter-labs/teepot/issues?q=is%3Aissue+is%3Aopen+created%3A2024-02-01..2024-02-29%20-author:app/dependabot

- [zkSync Insufficient Proof Verification Bugfix Review](https://medium.com/immunefi/zksync-insufficient-proof-verification-bugfix-review-dcd57944d0e2)
- [Zero-Knowledge Proofs explained like I'm 5](https://eli5.zksync.io/)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

Mar 15-17 | London, UK | [ETHGlobal London](https://ethglobal.com/events/london2024)

Mar 25–27 | Toronto, Canada | [RWC 2024](https://rwc.iacr.org/2024/)

Mar 26-28 | London, UK | [Rust Nation](https://www.rustnationuk.com/)

Apr 5-26 | Online | [Ethereum Async hackathon: Scaling Ethereum 2024](https://ethglobal.com/events/scaling2024)

Apr 8-12 | Paris, France | [Paris Blockchain Week](https://www.parisblockchainweek.com/)

Apr 10-11 | Paris, France | [Sui Basecamp](https://sui.io/basecamp)

Apr 10 | Athens, Greece | [zkSummit11](https://www.zksummit.com/)

Apr 11 | Athens, Greece | [ZK Accelerate](https://lu.ma/f5rwv3b1)

Apr 22-25 | Athens, Greece | [EuroSys 2024](https://2024.eurosys.org/about.html)

May 3-5 | Sydney, Australia | [ETHGlobal Sydney](https://ethglobal.com/events/sydney)

May 18-19 | Brisbane, Australia | [AI + Web3 Convention](https://web3convention.com/)

May 20-Jun 20 | Singapore | [The Polkadot Blockchain Academy](https://polkadot.network/development/blockchain-academy/)

May 21-23 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

May 24-26 | Berlin, Germany | [ETHBerlin](https://ethberlin.org/)

May 26-30 | Zurich, Switzerland | [Eurocrypt 2024](https://eurocrypt.iacr.org/2024/)

May 29-31 | Austin, US | [Consensus](https://consensus2024.coindesk.com/)

May 31-Jun 2 | Prague, Czech Republic | [ETH Prague](https://ethprague.com/)

Jun 5-6 | Santa Clara, US | [Blockchain Expo North America](https://blockchain-expo.com/northamerica/)

Jun 19-24 | Zurich, Switzerland | [RustFest Zürich](https://rustfest.ch/)

Jul 4-7 | Istanbul, Turkey | [Blockchain Expo World](https://blockchainexpoworld.com/)

Jul 8-11 | Brussels, Belgium | [EthCC](https://ethcc.io/)

Jul 12–14 | Brussels, Belgium | [ETHGlobal Brussels](https://ethglobal.com/events/brussels)

Aug 18-22 | Santa Barbara, US | [Crypto 2024](https://crypto.iacr.org/2024/)

Aug 28-29 | Tokyo, Japan | [WebX 2024](https://webx-asia.com/)

Sep 10-13 | Montreal, Canada | [RustConf 2024](https://foundation.rust-lang.org/news/save-the-date-rustconf-2024-september-10-13/)

Nov 12-15 | Bangkok, Thailand | [DevCon 7](https://blog.ethereum.org/2023/02/28/devcon-7-update)

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


