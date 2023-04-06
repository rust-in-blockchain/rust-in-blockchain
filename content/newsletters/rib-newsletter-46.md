---
title: "RiB Newsletter #46"
description: "March 2023"
date: 2023-04-05
categories:
  - "newsletters"
summary: "Welcome to the #46 edition of Rust in Blockchain.
This month we spotlight `Kind` and `HVM`.
Kind is a lazy, functional, but non-garbage-collected language, in the spirit of Haskell.
It runs on HVM."
---

Welcome to the #46 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #45](/newsletters/rib-newsletter-45/).

&nbsp;

## Thanks

Thanks to contributors:
[Andrew Dibble],
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Andrew Dibble]: https://github.com/acdibble
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

- [Kind](https://github.com/HigherOrderCO/kind) and [HVM](https://github.com/HigherOrderCO/HVM)

Kind is a lazy, functional, but non-garbage-collected language, in the spirit of Haskell.
It runs on HVM, the "Higher-order Virtual Machine", and is based on
a model of computation called [Interaction Nets](https://www.sciencedirect.com/science/article/pii/S0890540197926432?ref=pdf_download&fr=RR-2&rr=7b358c408c0c1f2d).
It features automatic parallelism and is said to be "beta-optimal",
in some cases resulting in faster performance than Haskell's GHC.

They are components of [Kindelia](https://github.com/HigherOrderCO/Kindelia),
a proof-of-work computation network that is not backed by a cryptocurrency.

&nbsp;


## Interesting Things

#### Blog Posts

- [Security Considerations for Precompiled Contracts](https://www.kalos.xyz/blog/security-considerations-for-precompiled-contracts)
- [Writing an LLVM backend for the Move language in Rust](https://brson.github.io/2023/03/12/move-on-llvm)
- [Settlement Layers? Ethereum Rollups? Sovereign Rollups?](https://stonecoldpat.substack.com/p/settlement-layers-ethereum-rollups)
- [Using Metal and Rust to make FFT even faster](https://www.notamonadtutorial.com/using-metal-and-rust-to-make-fft-even-faster/)
- [Bringing Zero-Knowledge Proofs to Penumbra](https://penumbra.zone/blog/zkproofs-intro/)
- [An Introduction To Zero-knowledge Machine Learning (ZKML)](https://worldcoin.org/blog/engineering/intro-to-zkml)
- [Codex (and GPT-4) can’t beat humans on smart contract audits](https://blog.trailofbits.com/2023/03/22/codex-and-gpt4-cant-beat-humans-on-smart-contract-audits/)
- [What is the difference between PBFT, Tendermint, HotStuff, and HotStuff-2?](https://decentralizedthoughts.github.io/2023-04-01-hotstuff-2/)
- [Risk Analysis of Intel's SGX and Other TEEs](https://zecsec.com/posts/risk-analysis-of-intel-sgx-and-other-tees/)

#### Papers

- [Extended Abstract: HotStuff-2: Optimal Two-Phase Responsive BFT](https://eprint.iacr.org/2023/397)
- [Simplex Consensus: A Simple and Fast Consensus Protocol](https://eprint.iacr.org/2023/463)
- [The Cost of Intelligence: Proving Machine Learning Inference with Zero-Knowledge](https://drive.google.com/file/d/1tylpowpaqcOhKQtYolPlqvx6R2Gv4IzE/view)

#### Projects

- [zkPoEX](https://github.com/zkoranges/zkPoEX) enables white hat
  hackers to report live vulnerabilities in smart contracts while
  maintaining the confidentiality of the exploit, facilitating
  efficient communication and collaboration between hackers and
  project owners for a more secure DeFi ecosystem.
- [EZKL](https://github.com/zkonduit/ezkl) is a library and
  command-line tool for doing inference for deep learning models and
  other computational graphs in a zk-snark.

&nbsp;

## Most Active in March

[Sui](https://github.com/MystenLabs):
1115 merged PRs,
167 closed issues,
102 open issues

[Parity](https://github.com/paritytech):
504 merged PRs,
236 closed issues,
172 open issues

[Aptos](https://github.com/aptos-labs):
442 merged PRs,
92 closed issues,
75 open issues

[Starkware](https://github.com/starkware-libs):
341 merged PRs,
24 closed issues,
12 open issues

[Solana](https://github.com/solana-labs/solana):
335 merged PRs,
54 closed issues,
33 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

39 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4], [5][aleo-merged-prs-5], [6][aleo-merged-prs-6]),
14 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]),
7 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/aleo-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-merged-prs-5]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-merged-prs-6]: https://github.com/AleoHQ/welcome/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-closed_issues-4]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Anoma](https://github.com/anoma)

53 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
22 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
46 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

442 merged PRs ([1][aptos-merged-prs-1]),
92 closed issues ([1][aptos-closed_issues-1]),
75 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Casper](https://github.com/casper-network)

78 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
67 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
43 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

1 merged PRs ([1][comit-merged-prs-1]),
0 closed issues,
1 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

77 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]),
29 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
14 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-use-case-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

11 merged PRs ([1][conflux-merged-prs-1]),
5 closed issues ([1][conflux-closed_issues-1]),
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

3 merged PRs ([1][darkfi-merged-prs-1]),
3 closed issues ([1][darkfi-closed_issues-1]),
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

89 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6]),
16 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4]),
7 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-closed_issues-4]: https://github.com/dfinity/experimental-minting-tool/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [Chain-Key Bitcoin: A Decentralized Bitcoin Twin](https://medium.com/dfinity/chain-key-bitcoin-a-decentralized-bitcoin-twin-ceb8f4ddf95e)
- [Understanding the Ethereum Virtual Machine Canister (EVMC): A Beginner’s Guide](https://medium.com/dfinity/understanding-the-ethereum-virtual-machine-canister-evmc-a-beginners-guide-df4fd69c8ad4)

#### [Dusk Network](https://github.com/dusk-network)

12 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2]),
13 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2]),
4 open issues ([1][dusk_network-open_issues-1])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

26 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2]),
30 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
37 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

136 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7], [8][filecoin-merged-prs-8]),
79 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5], [6][filecoin-closed_issues-6], [7][filecoin-closed_issues-7]),
46 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4], [5][filecoin-open_issues-5])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/lurk-lab/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-merged-prs-8]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/ec-gpu/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-closed_issues-6]: https://github.com/filecoin-project/rust-gpu-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-closed_issues-7]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/ec-gpu/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[filecoin-open_issues-5]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [The Filecoin Virtual Machine (FVM) is live on Mainnet!](https://filecoin.io/blog/posts/fvm-is-live-on-mainnet/)
- [Refreshing the Filecoin Bug Bounty Program](https://filecoin.io/blog/posts/refreshing-the-filecoin-bug-bounty-program/)

#### [Findora](https://github.com/FindoraNetwork)

48 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

146 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7]),
1 closed issues ([1][fluence-closed_issues-1]),
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fluence-closed_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

238 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8]),
166 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
102 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [Fuel VM Binary Analysis](https://jtriley.substack.com/p/fuel-vm-binary-analysis)

#### [Golem](https://github.com/golemfactory)

25 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3]),
34 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]),
11 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Grin](https://github.com/mimblewimble/grin)

3 merged PRs ([1][grin-merged-prs-1]),
2 closed issues ([1][grin-closed_issues-1], [2][grin-closed_issues-2]),
0 open issues

[grin-merged-prs-1]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[grin-closed_issues-2]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

33 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]),
3 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
1 open issues ([1][helium-open_issues-1])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/semtech-udp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[helium-closed_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [An Update on the Helium Network’s Migration to Solana](https://blog.helium.com/an-update-on-the-helium-networks-migration-to-solana-4550e20552a9)

#### [Holochain](https://github.com/holochain/)

100 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]),
18 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
9 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [hc CLI: Test, Run, and Package Your hApp](https://blog.holochain.org/hc-cli-test-run-and-package-your-happ/)

#### [IOTA](https://github.com/iotaledger)

87 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5]),
62 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3]),
4 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2])

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-closed_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

116 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4], [5][maidsafe-merged-prs-5]),
3 closed issues ([1][maidsafe-closed_issues-1], [2][maidsafe-closed_issues-2]),
3 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/sn_consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[maidsafe-merged-prs-5]: https://github.com/maidsafe/self_encryption/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[maidsafe-closed_issues-2]: https://github.com/maidsafe/bls_dkg/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

0 merged PRs,
0 closed issues,
1 open issues ([1][mina-open_issues-1])

[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [zkVMs are cool, but have you heard of zkCPUs?](https://www.cryptologie.net/article/589/zkvms-are-cool-but-have-you-heard-of-zkcpus/)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

51 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
19 closed issues ([1][mobilecoin-closed_issues-1], [2][mobilecoin-closed_issues-2]),
18 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[mobilecoin-closed_issues-2]: https://github.com/mobilecoinfoundation/mc-oblivious/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

49 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3]),
2 closed issues ([1][multiversx-closed_issues-1]),
0 open issues

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-bridge-eth-sc-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

140 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7]),
29 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4]),
44 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [Near Announces the Blockchain Operation System](https://near.org/blog/near-announces-the-blockchain-operation-system/)

#### [Nervos](https://github.com/nervosnetwork)

53 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6]),
17 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3]),
6 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

12 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]),
2 closed issues ([1][oasis-closed_issues-1]),
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[oasis-merged-prs-2]: https://github.com/oasisprotocol/emerald-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

504 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12]),
236 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12]),
172 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Radix](https://github.com/radixdlt)

96 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3], [4][radix-merged-prs-4], [5][radix-merged-prs-5]),
1 closed issues ([1][radix-closed_issues-1]),
1 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/community-scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-challenges/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[radix-merged-prs-4]: https://github.com/radixdlt/scrypto-demos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[radix-merged-prs-5]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

24 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]),
3 closed issues ([1][secret_network-closed_issues-1], [2][secret_network-closed_issues-2]),
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[secret_network-closed_issues-2]: https://github.com/scrtlabs/snip20-reference-impl/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[secret_network-open_issues-1]: https://github.com/scrtlabs/snip20-reference-impl/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

335 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
54 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
33 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

76 merged PRs ([1][subspace_network-merged-prs-1]),
31 closed issues ([1][subspace_network-closed_issues-1]),
38 open issues ([1][subspace_network-open_issues-1])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

1115 merged PRs ([1][sui-merged-prs-1]),
167 closed issues ([1][sui-closed_issues-1]),
102 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Zcash](https://github.com/zcash)

58 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5], [6][zcash-merged-prs-6]),
29 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4], [5][zcash-closed_issues-5], [6][zcash-closed_issues-6]),
32 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-merged-prs-6]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/incrementalmerkletree/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-closed_issues-5]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-closed_issues-6]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [Making Zcash Light Wallets Faster and More Private](https://zecsec.com/posts/making-zcash-light-wallets-faster-and-more-private/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

1 merged PRs ([1][aluvm-merged-prs-1]),
0 closed issues,
1 open issues ([1][aluvm-open_issues-1])

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[aluvm-open_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

23 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]),
28 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3], [4][bdk-closed_issues-4]),
26 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-closed_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

1 merged PRs ([1][bitmask-merged-prs-1]),
0 closed issues,
1 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

6 merged PRs ([1][electrs-merged-prs-1]),
4 closed issues ([1][electrs-closed_issues-1]),
4 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

168 merged PRs ([1][fedimint-merged-prs-1]),
38 closed issues ([1][fedimint-closed_issues-1]),
51 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

53 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
15 closed issues ([1][ldk-closed_issues-1]),
14 open issues ([1][ldk-open_issues-1])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

3 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2]),
4 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3]),
2 open issues ([1][lnp/bp-open_issues-1])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/invoices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/BP-WG/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/rust-lnpbp/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp/bp-closed_issues-2]: https://github.com/LNP-BP/invoices/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp/bp-closed_issues-3]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [LNP WG](https://github.com/LNP-WG)

9 merged PRs ([1][lnp_wg-merged-prs-1], [2][lnp_wg-merged-prs-2], [3][lnp_wg-merged-prs-3]),
3 closed issues ([1][lnp_wg-closed_issues-1]),
1 open issues ([1][lnp_wg-open_issues-1])

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp_wg-merged-prs-2]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp_wg-merged-prs-3]: https://github.com/LNP-WG/lightning_encoding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp_wg-closed_issues-1]: https://github.com/LNP-WG/lightning_encoding/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lnp_wg-open_issues-1]: https://github.com/LNP-WG/lnp-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

19 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2], [3][nomic-merged-prs-3]),
7 closed issues ([1][nomic-closed_issues-1]),
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/nomic-io/merk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nomic-merged-prs-3]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[nomic-closed_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

3 merged PRs ([1][rgb-merged-prs-1]),
7 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2]),
2 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

61 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
26 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4], [5][rust_bitcoin-closed_issues-5], [6][rust_bitcoin-closed_issues-6]),
14 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/rust-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-5]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-6]: https://github.com/jean-airoldie/zeromq-src-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

7 merged PRs ([1][rust_simplicity-merged-prs-1]),
3 closed issues ([1][rust_simplicity-closed_issues-1]),
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_simplicity-closed_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

3 merged PRs ([1][talaia-merged-prs-1]),
2 closed issues ([1][talaia-closed_issues-1]),
6 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

47 merged PRs ([1][ethers-rs-merged-prs-1]),
16 closed issues ([1][ethers-rs-closed_issues-1]),
16 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

71 merged PRs ([1][foundry-merged-prs-1]),
96 closed issues ([1][foundry-closed_issues-1]),
77 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

29 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
30 closed issues ([1][lighthouse-closed_issues-1]),
19 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Mir Protocol](https://github.com/mir-protocol)

56 merged PRs ([1][mir_protocol-merged-prs-1], [2][mir_protocol-merged-prs-2], [3][mir_protocol-merged-prs-3]),
0 closed issues,
2 open issues ([1][mir_protocol-open_issues-1])

[mir_protocol-merged-prs-1]: https://github.com/mir-protocol/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[mir_protocol-merged-prs-2]: https://github.com/mir-protocol/eth_trie_utils/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[mir_protocol-merged-prs-3]: https://github.com/mir-protocol/evm-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[mir_protocol-open_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

318 merged PRs ([1][reth-merged-prs-1]),
120 closed issues ([1][reth-closed_issues-1]),
40 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

2 merged PRs ([1][rust_web3-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_web3-open_issues-1])

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

341 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3]),
24 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
12 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2], [3][starkware-open_issues-3])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-03-01..2023-03-31%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot
[starkware-open_issues-3]: https://github.com/starkware-libs/starknet-api/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [Starknet Alpha v0.11.0: The Transition to Cairo 1.0 Begins](https://medium.com/starkware/starknet-alpha-v0-11-0-the-transition-to-cairo-1-0-begins-30442d494515)

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs,
3 closed issues ([1][zksync-closed_issues-1]),
10 open issues ([1][zksync-open_issues-1])

[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-03-01..2023-03-31%20-author:app/dependabot
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-03-01..2023-03-31%20-author:app/dependabot

- [gm zkEVM!](https://blog.matter-labs.io/gm-zkevm-171b12a26b36)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

Apr 28 - Jun 9 | Online | [Chainlink Hackathon Spring 2023](https://chain.link/hackathon)

May 1-5 | Bol, Brač, Croatia | [Financial Cryptography and Data Security 2023](https://fc23.ifca.ai/)

May 20-21 | Amsterdam, Netherlands | [ETHDam](https://www.ethdam.com/)

Jun 3-5 | Prague, Czech Republic | [Gateway to Cosmos 2023](https://gateway.events/)

Jun 17-20 | Paris, France | [EthCC](https://www.ethcc.io/)

Aug 28-30 | Palo Alto, CA, US | [The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Sep 11-13 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

Sep 12-15 | Albuquerque, NM & Online | [RustConf 2023](https://rustconf.com/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Chainflip Labs GmbH | Berlin
- [Senior Rust Engineer](https://angel.co/company/chainflip/jobs/1644220-senior-rust-engineer)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


