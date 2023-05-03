---
title: "RiB Newsletter #47"
description: "April 2023"
date: 2023-05-03
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #47 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #46](/newsletters/rib-newsletter-46/).

&nbsp;

## Thanks

Thanks to contributors:
[Andrew Dibble],
[Calin Martinconi],
[Chan De Silva],
_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Andrew Dibble]: https://github.com/acdibble
[Calin Martinconi]: https://github.com/martinconic
[Chan De Silva]: https://github.com/cdsdesilva
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News

- [MERLIN DEX - REKT](https://rekt.news/merlin-dex-rekt/)

#### Blog Posts

- [Exciting times at the intersection of Compilers and Applied Cryptography: CAIRO and MLIR](https://www.notamonadtutorial.com/cairo-and-mlir/)
- [All you wanted to know about Plonk](https://www.notamonadtutorial.com/all-you-wanted-to-know-about-plonk/)
- [zkWASM: The Future of Scalable Computation in Blockchain](https://mirror.xyz/hyperoracleblog.eth/FRbMWj85951QWJdEhqGTC-p6TD41583SnZOa47EVsks)
- [zkWASM, zkOracle and Programmability: Pioneering Scalable and Secure Blockchain Solutions](https://mirror.xyz/hyperoracleblog.eth/g71SJoKEtkIshh5usUm9_1SOlEiwRYifcF7aEE5hBiI)
- [Hardware Review: GPUs , FPGAs and Zero Knowledge Proofs](https://hackmd.io/@0xMonia/SkQ6-oRz3)
- [Bridging the Gap: How ZK-SNARKs Bring Transparency to Private ML Models with zkml](https://medium.com/@danieldkang/bridging-the-gap-how-zk-snarks-bring-transparency-to-private-ml-models-with-zkml-e0e59708c2fc)
- [Do You Want Quality Code? Learn How to Use Differential Fuzzers!](https://www.notamonadtutorial.com/do-you-want-quality-code-learn-how-to-use-differential-fuzzers/)

#### Papers

- [HyperNova: Recursive arguments for customizable constraint systems](https://eprint.iacr.org/2023/573)

#### Projects

- [zkPoEX](https://github.com/zkoranges/zkPoEX) enables white hat
  hackers to report live vulnerabilities in smart contracts while
  maintaining the confidentiality of the exploit, facilitating
  efficient communication and collaboration between hackers and
  project owners for a more secure DeFi ecosystem.
  Blog post: [Revolutionizing DeFi Security: ZK Proof of Exploit on RISC Zero](https://www.risczero.com/blog/zkpoex).
- [Ola](https://github.com/Sin7Y/ola-lang). A high-level language for implementing
  smart contracts. From the outset, it is designed to be a zk-friendly programming language.
  Blog post: [A Programmable Privacy Platform for Ethereum: Understanding Ola’s Design Principles and Technical Features](https://medium.com/@sin7y/a-programmable-privacy-platform-for-ethereum-understanding-olas-design-principles-and-technical-8a47ff07e725)


&nbsp;

## Most Active in April

[Sui](https://github.com/MystenLabs):
759 merged PRs,
140 closed issues,
102 open issues

[Parity](https://github.com/paritytech):
345 merged PRs,
178 closed issues,
150 open issues

[Aptos](https://github.com/aptos-labs):
310 merged PRs,
71 closed issues,
54 open issues

[Solana](https://github.com/solana-labs/solana):
295 merged PRs,
56 closed issues,
23 open issues 

[Starkware](https://github.com/starkware-libs):
290 merged PRs,
33 closed issues,
19 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

69 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4], [5][aleo-merged-prs-5]),
16 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]),
7 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-merged-prs-5]: https://github.com/AleoHQ/welcome/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-closed_issues-4]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Fixed-Point Arithmetic in LEO](https://www.aleo.org/post/fixed-point-arithmetic-in-the-zksnark-based-programming-language-leo)
- [Pioneer the Future of Private Machine Learning with Aleo’s zkML Initiative](https://www.aleo.org/post/pioneer-the-future-of-private-machine-learning-with-aleos-zkml-initiative)
- [Neural Network Inference with Leo](https://www.aleo.org/post/neural-network-inference-with-the-zksnark-based-programming-language-leo-using-fixed-point-arithmetic)
- [Loan decisions with neural networks using Leo](https://www.aleo.org/post/loan-decisions-with-neural-networks-using-leo)

#### [Anoma](https://github.com/anoma)

59 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3], [4][anoma-merged-prs-4]),
29 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
14 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-merged-prs-4]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

310 merged PRs ([1][aptos-merged-prs-1]),
71 closed issues ([1][aptos-closed_issues-1]),
54 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Quorum Store: How Consensus Horizontally Scales on the Aptos Blockchain](https://medium.com/aptoslabs/quorum-store-how-consensus-horizontally-scales-on-the-aptos-blockchain-988866f6d5b0)
- [Aptos Labs brings Web3 to Gaming with its new SDK for Unity developers](https://medium.com/aptoslabs/aptos-labs-brings-web3-to-gaming-with-its-new-sdk-for-unity-developers-e6544bdf9ba9)

#### [Casper](https://github.com/casper-network)

80 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
80 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
60 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

0 merged PRs,
1 closed issues ([1][comit-closed_issues-1]),
1 open issues ([1][comit-open_issues-1])

[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

38 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6]),
13 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
10 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-euro2ccd-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

9 merged PRs ([1][conflux-merged-prs-1]),
2 closed issues ([1][conflux-closed_issues-1]),
5 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Monthly Progress Report — April 2023](https://medium.com/conflux-network/monthly-progress-report-april-2023-e73f87afe461)

#### [DarkFi](https://dark.fi)

4 merged PRs ([1][darkfi-merged-prs-1]),
0 closed issues,
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

64 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
11 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4]),
3 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-closed_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Eliminating Smart Contract Bugs with TLA+](https://medium.com/dfinity/eliminating-smart-contract-bugs-with-tla-e986aeb6da24)
- [Announcing the Internet Computer BUIDL Bitcoin Hackathon, powered by Encode Club](https://medium.com/dfinity/announcing-the-internet-computer-buidl-bitcoin-hackathon-powered-by-encode-club-70081b8d0406)

#### [Dusk Network](https://github.com/dusk-network)

9 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2]),
10 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4]),
8 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/microkelvin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/rusk-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dusk_network-closed_issues-4]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

34 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2]),
20 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
17 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Sequencer Decentralization and Liveness](https://medium.com/@espressosys/sequencer-decentralization-and-liveness-e5af7f4b25ca)

#### [Filecoin](https://github.com/filecoin-project)

104 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7], [8][filecoin-merged-prs-8], [9][filecoin-merged-prs-9], [10][filecoin-merged-prs-10]),
27 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5], [6][filecoin-closed_issues-6]),
18 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/blstrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/bls-signatures/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/lurk-lab/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-8]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-9]: https://github.com/filecoin-project/rust-gpu-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-merged-prs-10]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/blstrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/ec-gpu/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/lurk-lab/neptune/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-closed_issues-6]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/lurk-lab/neptune/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Indexer Scalability for Ingest-heavy Workload](https://filecoin.io/blog/posts/indexer-scalability-for-ingest-heavy-workload/)
- [The FVM Imaginarium: Developer Tooling, Hackathons and other Opportunities for Builders](https://filecoin.io/blog/posts/the-fvm-imaginarium-developer-tooling-hackathons-and-other-opportunities-for-builders/)

#### [Findora](https://github.com/FindoraNetwork)

46 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4], [5][findora-merged-prs-5]),
0 closed issues,
1 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[findora-merged-prs-4]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[findora-merged-prs-5]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[findora-open_issues-1]: https://github.com/FindoraNetwork/noah/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

124 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7]),
0 closed issues,
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

214 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8]),
147 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7]),
112 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

21 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4]),
13 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]),
21 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Golem Portal has been launched!](https://blog.golemproject.net/)

#### [Grin](https://github.com/mimblewimble/grin)

2 merged PRs ([1][grin-merged-prs-1]),
1 closed issues ([1][grin-closed_issues-1]),
2 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[grin-closed_issues-1]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Helium](https://github.com/helium)

19 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3]),
7 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
1 open issues ([1][helium-open_issues-1])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[helium-closed_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [A New Era for Helium Begins with Upgrade to Solana Blockchain](https://blog.helium.com/a-new-era-for-helium-begins-with-upgrade-to-solana-blockchain-88b742276ec1)
- [It’s here: The Helium Network Migrates to Solana Today](https://blog.helium.com/its-here-the-helium-network-migrates-to-solana-today-6b24d05ba57d)

#### [Holochain](https://github.com/holochain/)

120 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4]),
15 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2], [3][holochain-closed_issues-3]),
5 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-merged-prs-4]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-closed_issues-3]: https://github.com/holochain/holochain-client-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Holochain 0.1 Matures](https://blog.holochain.org/holochain-0-1-matures/)

#### [IOTA](https://github.com/iotaledger)

14 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6], [7][iota-merged-prs-7]),
5 closed issues ([1][iota-closed_issues-1]),
1 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-merged-prs-6]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-merged-prs-7]: https://github.com/iotaledger/chronicle.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/chronicle.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Progress Report Q1 2023](https://blog.iota.org/progress-report-q1-2023/)

#### [Maidsafe](https://github.com/maidsafe)

115 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2]),
42 closed issues ([1][maidsafe-closed_issues-1]),
23 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

0 merged PRs,
2 closed issues ([1][mina-closed_issues-1]),
1 open issues ([1][mina-open_issues-1])

[mina-closed_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [The State of Zero Knowledge 2023 Report](https://minaprotocol.com/blog/the-state-of-zero-knowledge-2023-report)
- [Unlocking the Power of Privacy: How Developers Can Leverage Homomorphic Encryption and Zero-Knowledge Proofs](https://blog.o1labs.org/unlocking-the-power-of-privacy-how-developers-can-leverage-homomorphic-encryption-and-6cab3b1e9325)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

25 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
11 closed issues ([1][mobilecoin-closed_issues-1], [2][mobilecoin-closed_issues-2]),
7 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mobilecoin-closed_issues-2]: https://github.com/mobilecoinfoundation/fog/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

26 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2]),
1 closed issues ([1][multiversx-closed_issues-1]),
1 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [MultiversX Rust game-dev tutorial published on CryptoZombies coding school](https://multiversx.com/blog/multiversx-rust-game-dev-tutorial)

#### [NEAR](https://github.com/nearprotocol/nearcore)

114 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8]),
29 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6]),
30 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-lake-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [NEAR Blockchain Operating System is Now Live on Near.org](https://pages.near.org/blog/near-blockchain-operating-system-is-now-live-on-near-org/)
- [NEAR Foundation Launches NEAR Horizon](https://pages.near.org/blog/near-foundation-launches-near-horizon/)

#### [Nervos](https://github.com/nervosnetwork)

80 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6]),
29 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
7 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/godwokenrises/godwoken-tests/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

10 merged PRs ([1][oasis-merged-prs-1]),
0 closed issues,
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [4 Ways to Compare Trusted Execution Environments and Zero-Knowledge Proofs](https://medium.com/oasis-protocol-project/4-ways-to-compare-trusted-execution-environments-and-zero-knowledge-proofs-293615b8c1b6)
- [Oasis March 2023 Engineering Update](https://medium.com/oasis-protocol-project/oasis-march-2023-engineering-update-c302e4dbf0b9)

#### [Parity](https://github.com/paritytech)

345 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13]),
178 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12]),
150 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Radix](https://github.com/radixdlt)

47 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3]),
0 closed issues,
0 open issues

[radix-merged-prs-1]: https://github.com/radixdlt/community-scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

16 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]),
1 closed issues ([1][secret_network-closed_issues-1]),
0 open issues

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/snip20-reference-impl/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

295 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]),
56 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2], [3][solana-closed_issues-3]),
23 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[solana-closed_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

55 merged PRs ([1][subspace_network-merged-prs-1]),
23 closed issues ([1][subspace_network-closed_issues-1]),
11 open issues ([1][subspace_network-open_issues-1])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Dilithium: Subspace Consensus v2](https://blog.subspace.network/dilithium-the-subspace-consensus-v2-3c5df0759e72)

#### [Sui](https://github.com/MystenLabs)

759 merged PRs ([1][sui-merged-prs-1]),
140 closed issues ([1][sui-closed_issues-1]),
102 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [Subset-optimized BLS Multi-signature with Key Aggregation](https://tech.mystenlabs.com/new-bls-aggregation-for-proof-of-stake/)

#### [Zcash](https://github.com/zcash)

62 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5]),
38 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4]),
19 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/incrementalmerkletree/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [New Release 5.5.0](https://electriccoin.co/blog/new-release-5-5-0/)
- [Experimental Zebra progress bars](https://zfnd.org/experimental-zebra-progress-bars/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

1 merged PRs ([1][aluvm-merged-prs-1]),
1 closed issues ([1][aluvm-closed_issues-1]),
0 open issues

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[aluvm-closed_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

16 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3]),
6 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
13 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

10 merged PRs ([1][bitmask-merged-prs-1]),
1 closed issues ([1][bitmask-closed_issues-1]),
0 open issues

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Cyphernet](https://github.com/cyphernet-dao)

4 merged PRs ([1][cyphernet-merged-prs-1]),
4 closed issues ([1][cyphernet-closed_issues-1]),
2 open issues ([1][cyphernet-open_issues-1])

[cyphernet-merged-prs-1]: https://github.com/cyphernet-dao/rust-netservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[cyphernet-closed_issues-1]: https://github.com/cyphernet-dao/rust-netservices/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[cyphernet-open_issues-1]: https://github.com/cyphernet-dao/rust-netservices/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

1 merged PRs ([1][electrs-merged-prs-1]),
5 closed issues ([1][electrs-closed_issues-1]),
1 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

159 merged PRs ([1][fedimint-merged-prs-1]),
84 closed issues ([1][fedimint-closed_issues-1]),
52 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

56 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
24 closed issues ([1][ldk-closed_issues-1]),
29 open issues ([1][ldk-open_issues-1])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

10 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3]),
3 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2]),
0 open issues

[lnp/bp-merged-prs-1]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lnp/bp-merged-prs-3]: https://github.com/BP-WG/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lnp/bp-closed_issues-2]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [LNP WG](https://github.com/LNP-WG)

1 merged PRs ([1][lnp_wg-merged-prs-1]),
0 closed issues,
1 open issues ([1][lnp_wg-open_issues-1])

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lnp_wg-open_issues-1]: https://github.com/LNP-WG/lnp-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [MyCitadel](https://github.com/orgs/mycitadel)

6 merged PRs ([1][mycitadel-merged-prs-1]),
17 closed issues ([1][mycitadel-closed_issues-1]),
23 open issues ([1][mycitadel-open_issues-1])

[mycitadel-merged-prs-1]: https://github.com/mycitadel/mycitadel-desktop/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mycitadel-closed_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mycitadel-open_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

0 merged PRs,
0 closed issues,
4 open issues ([1][nakamoto-open_issues-1])

[nakamoto-open_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

4 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]),
1 closed issues ([1][nomic-closed_issues-1]),
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[nomic-closed_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

1 merged PRs ([1][rgb-merged-prs-1]),
4 closed issues ([1][rgb-closed_issues-1]),
1 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

31 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
10 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]),
16 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/rust-bech32-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bech32-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

5 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot


If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

55 merged PRs ([1][ethers-rs-merged-prs-1]),
13 closed issues ([1][ethers-rs-closed_issues-1]),
7 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

46 merged PRs ([1][foundry-merged-prs-1]),
56 closed issues ([1][foundry-closed_issues-1]),
78 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

15 merged PRs ([1][lighthouse-merged-prs-1]),
22 closed issues ([1][lighthouse-closed_issues-1]),
23 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Mir Protocol](https://github.com/mir-protocol)

57 merged PRs ([1][mir_protocol-merged-prs-1], [2][mir_protocol-merged-prs-2]),
0 closed issues,
2 open issues ([1][mir_protocol-open_issues-1])

[mir_protocol-merged-prs-1]: https://github.com/mir-protocol/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mir_protocol-merged-prs-2]: https://github.com/mir-protocol/evm-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[mir_protocol-open_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

273 merged PRs ([1][reth-merged-prs-1]),
83 closed issues ([1][reth-closed_issues-1]),
52 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Rust Ethereum](https://github.com/rust-ethereum)

1 merged PRs ([1][rust_ethereum-merged-prs-1]),
0 closed issues,
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

1 merged PRs ([1][rust_web3-merged-prs-1]),
1 closed issues ([1][rust_web3-closed_issues-1]),
0 open issues

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[rust_web3-closed_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

290 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3]),
33 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
19 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2], [3][starkware-open_issues-3])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-04-01..2023-04-30%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-04-01..2023-04-30%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot
[starkware-open_issues-3]: https://github.com/starkware-libs/starknet-api/issues?q=is%3Aissue+is%3Aopen+created%3A2023-04-01..2023-04-30%20-author:app/dependabot

- [All roads lead to Giza, Starknet Roadmap and Cairo Book](https://starknet.substack.com/p/all-roads-lead-to-giza-starknet-roadmap)
- [What are Storage Proofs and how can they improve Oracles?](https://starkware.medium.com/what-are-storage-proofs-and-how-can-they-improve-oracles-e0379108720a)
- [StarkEx V5.0 for Spot Trading is Here!](https://medium.com/starkware/starkex-v5-0-for-spot-trading-is-here-41bfe90e25a6)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

May 1-5 | Bol, Brač, Croatia | [Financial Cryptography and Data Security 2023](https://fc23.ifca.ai/)

May 15-20 | Chicago, IL, US | [zkWeek](https://jumpcrypto.com/thepit/zkweek/)

May 19-23 | Montenegro | [EDCON 2023](https://www.edcon.io/)

May 20-21 | Amsterdam, Netherlands | [ETHDam](https://www.ethdam.com/)

Jun 3-5 | Prague, Czech Republic | [Gateway to Cosmos 2023](https://gateway.events/)

Jun 9-10 | Prague, Czech Republic | [ETHPrague](https://ethprague.com/)

Jun 17-20 | Paris, France | [EthCC](https://www.ethcc.io/)

Aug 28-30 | Palo Alto, CA, US | [The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Sep 5-6 | Seoul, Korea | [Korea Blockchain Week](https://koreablockchainweek.com/)

Sep 11-13 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

Sep 12-15 | Albuquerque, NM & Online | [RustConf 2023](https://rustconf.com/)


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


