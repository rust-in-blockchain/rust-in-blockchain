---
title: "RiB Newsletter #33 - _TODO_"
description: "February 2022"
date: 2022-03-02
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #33 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #32](/newsletters/rib-newsletter-32/).

&nbsp;

## Thanks

Thanks to contributors:
[Dan Shields],
[David],
[John Adler],
[oiclid],
[Brian Anderson], and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Dan Shields]: Https://github.com/NukeManDan
[David]: https://github.com/djdo83
[John Adler]: https://github.com/adlerjohn
[oiclid]: https://github.com/oiclid
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News

- Wormhole hack:
  - Offcial report: [Wormhole Incident Report — 02/02/22](https://wormholecrypto.medium.com/wormhole-incident-report-02-02-22-ad9b8f21eec6)
  - Rekt report: [WORMHOLE - REKT](https://rekt.news/wormhole-rekt/)
- [Decommissioning Wormhole V1](https://wormholecrypto.medium.com/decommissioning-wormhole-v1-da79e4bfff99)
- [Arti 0.1.0 is released: Your somewhat-stable API is here!](https://blog.torproject.org/arti_010_released/)

#### Blog Posts

- [Rust Survey 2021 Results](https://blog.rust-lang.org/2022/02/15/Rust-Survey-2021.html)
- [What Are Cross-Chain Smart Contracts?](https://blog.chain.link/cross-chain-smart-contracts/)
- [Encapsulated vs systemic complexity in protocol design](https://vitalik.ca/general/2022/02/28/complexity.html)

#### Papers

- [Round-Optimal Byzantine Agreement](https://eprint.iacr.org/2022/255)
- [Gradecast in Synchrony and Reliable Broadcast in Asynchrony with Optimal Resilience, Efficiency, and Unconditional Security](https://eprint.iacr.org/2022/264)
- [Efficient NIZKs and Signatures from Commit-and-Open Protocols in the QROM](https://eprint.iacr.org/2022/270)
- [The Power of the Differentially Oblivious Shuffle in Distributed Privacy Mechanisms](https://eprint.iacr.org/2022/177)
- [CryptoMaze: Privacy-Preserving Splitting of Off-Chain Payments](https://eprint.iacr.org/2022/123)
- [Azeroth: Auditable Zero-knowledge Transactions in Smart Contracts](https://eprint.iacr.org/2022/211)
- [Zero-Knowledge Protocols for the Subset Sum Problem from MPC-in-the-Head with Rejection](https://eprint.iacr.org/2022/223)
- [Proving UNSAT in Zero Knowledge](https://eprint.iacr.org/2022/206)
- [Short-lived zero-knowledge proofs and signatures](https://eprint.iacr.org/2022/190)
- [SNACKs: Leveraging Proofs of Sequential Work for Blockchain Light Clients](https://eprint.iacr.org/2022/240)
- [Non-interactive Mimblewimble transactions, revisited](https://eprint.iacr.org/2022/265)


#### Projects

- [awesome-move](https://github.com/MystenLabs/awesome-move).
  Code and content from the Move programming language community.
- [Teleport Transactions](https://github.com/bitcoin-teleport/teleport-transactions/).
  CoinSwap implementation aims to improve the privacy of Bitcoin.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust


&nbsp;

## Most Active in February

[Parity](https://github.com/paritytech):
299 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
74 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6]), 
91 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[Solana](https://github.com/solana-labs/solana):
254 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
45 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
52 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Zcash](https://github.com/zcash):
124 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
121 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]),
39 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

92 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]), 
74 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]), 
24 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[aleo-closed_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [Incentivized Testnet Retrospective](https://www.aleo.org/post/incentivized-testnet-retrospective)

#### [Anoma](https://github.com/anoma)

21 merged PRs ([1][anoma-merged-prs-1]), 
34 closed issues ([1][anoma-closed_issues-1]), 
33 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [ChainSafe](https://github.com/ChainSafe)

22 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]), 
11 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2]), 
11 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/filecoindot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/filecoindot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [COMIT](https://github.com/comit-network)

9 merged PRs ([1][comit-merged-prs-1]), 
2 closed issues ([1][comit-closed_issues-1]), 
8 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [XMR-BTC swaps: Maintainers Wanted](https://comit.network/blog/2022/02/07/xmr-btc-looking-for-maintainer)

#### [Concordium](https://github.com/Concordium)

12 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]), 
6 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2]), 
6 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[concordium-open_issues-2]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [Concordium Transaction Fees 101](https://medium.com/concordium/concordium-transaction-fees-101-8a6d33dc590e)

#### [Conflux](https://github.com/Conflux-Chain)

27 merged PRs ([1][conflux-merged-prs-1]), 
11 closed issues ([1][conflux-closed_issues-1]), 
7 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [Our Long Awaited Hard Fork Hydra is Almost Here!](https://confluxnetwork.medium.com/conflux-hard-fork-hydra-is-almost-here-19dae229a690)

#### [DarkFi](https://dark.fi)

5 merged PRs ([1][darkfi-merged-prs-1]), 
7 closed issues ([1][darkfi-closed_issues-1]), 
6 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Dfinity](https://github.com/dfinity)

37 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6]), 
13 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]), 
5 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[dfinity-merged-prs-4]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[dfinity-merged-prs-6]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[dfinity-closed_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[dfinity-closed_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[dfinity-closed_issues-3]: https://github.com/dfinity/ic-types/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[dfinity-open_issues-1]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[dfinity-open_issues-3]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [Bitcoin Smart Contracts Are Coming to Internet Computer DeFi Projects](https://medium.com/dfinity/bitcoin-smart-contracts-are-coming-to-internet-computer-defi-projects-dd6786078853)
- [The Internet Computer’s Bitcoin Developer Preview Is Now Available](https://medium.com/dfinity/the-internet-computers-bitcoin-developer-preview-is-now-available-85ce1df6b17d)
- [Bitcoin Integration Developer Preview](https://github.com/dfinity/bitcoin-developer-preview)

#### [Elrond](https://github.com/ElrondNetwork)

44 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3]), 
0 closed issues, 
1 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-dns-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [Elrond DeFi 2.0: The Era Of Autonomous Banking, A 100-Trillion Dollar Opportunity](https://elrond.com/blog/elrond-defi-20-autonomous-banking-economic-growth/)

#### [Findora](https://github.com/FindoraNetwork)

13 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2]), 
1 closed issues ([1][findora-closed_issues-1]), 
3 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[findora-merged-prs-2]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Fluence](https://github.com/fluencelabs)

15 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3]), 
6 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2]), 
3 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fluence-closed_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[fluence-open_issues-2]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[fluence-open_issues-3]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Fuel](https://github.com/FuelLabs)

112 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8]), 
77 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6]), 
80 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6])

[fuel-merged-prs-1]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-merged-prs-8]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-types/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fuel-closed_issues-6]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[fuel-open_issues-5]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[fuel-open_issues-6]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Golem](https://github.com/golemfactory)

16 merged PRs ([1][golem-merged-prs-1]), 
18 closed issues ([1][golem-closed_issues-1]), 
13 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Grin](https://github.com/mimblewimble/grin)

4 merged PRs ([1][grin-merged-prs-1]), 
0 closed issues, 
2 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Holochain](https://github.com/holochain/)

57 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]), 
5 closed issues ([1][holochain-closed_issues-1]), 
0 open issues

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28

- [Big HDK Change](https://blog.holochain.org/big-hdk-change/)

#### [IOTA](https://github.com/iotaledger)

28 merged PRs ([1][iota-merged-prs-1]), 
2 closed issues ([1][iota-closed_issues-1]), 
7 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Lighthouse](https://github.com/sigp/lighthouse)

2 merged PRs ([1][lighthouse-merged-prs-1]), 
20 closed issues ([1][lighthouse-closed_issues-1]), 
22 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [Lighthouse Update #39](https://lighthouse.sigmaprime.io/update-39.html)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

83 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]), 
17 closed issues ([1][mobilecoin-closed_issues-1]), 
13 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/fog/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [NEAR](https://github.com/nearprotocol/nearcore)

84 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 
46 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
41 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[near-closed_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Nervos](https://github.com/nervosnetwork)

20 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]), 
1 closed issues ([1][nervos-closed_issues-1]), 
1 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[nervos-merged-prs-3]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[nervos-open_issues-1]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Parity](https://github.com/paritytech)

299 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
74 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6]), 
91 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[parity-closed_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[parity-closed_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[parity-open_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[parity-open_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- Proposal: [Treasury for upstream](https://that.world/~wei/polkadot/council/upstream/)
- [Substrate Builders Program Milestone Update: February 2022](https://www.parity.io/blog/substrate-builders-program-milestone-update-february-2022)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

36 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]), 
15 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2]), 
27 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[rust_bitcoin-merged-prs-4]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[rust_bitcoin-closed_issues-2]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[rust_bitcoin-open_issues-4]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Rust Ethereum](https://github.com/rust-ethereum)

3 merged PRs ([1][rust_ethereum-merged-prs-1]), 
1 closed issues ([1][rust_ethereum-closed_issues-1]), 
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

6 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 
18 closed issues ([1][secret_network-closed_issues-1]), 
7 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Solana](https://github.com/solana-labs/solana)

254 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
45 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
52 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [Announcing Soteria Premium: Auto Auditor for Solana Smart Contracts](https://medium.com/coinmonks/announcing-soteria-premium-auto-auditor-for-solana-smart-contracts-866476b50ff2)
- [Welcome to the Solana Riptide Hackathon](https://solana.com/news/solana-riptide-announcement)

#### [Spacemesh](https://github.com/spacemeshos)

1 merged PRs ([1][spacemesh-merged-prs-1]), 
68 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
16 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Subspace Labs](https://github.com/subspace)

42 merged PRs ([1][subspace_labs-merged-prs-1], [2][subspace_labs-merged-prs-2], [3][subspace_labs-merged-prs-3]), 
14 closed issues ([1][subspace_labs-closed_issues-1], [2][subspace_labs-closed_issues-2]), 
16 open issues ([1][subspace_labs-open_issues-1], [2][subspace_labs-open_issues-2])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[subspace_labs-merged-prs-2]: https://github.com/subspace/subspace-desktop/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[subspace_labs-merged-prs-3]: https://github.com/subspace/sloth256-189/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[subspace_labs-closed_issues-2]: https://github.com/subspace/subspace-desktop/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[subspace_labs-open_issues-2]: https://github.com/subspace/subspace-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [TezEdge](https://github.com/tezedge)

26 merged PRs ([1][tezedge-merged-prs-1]), 
0 closed issues, 
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [Zcash](https://github.com/zcash)

124 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
121 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
39 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-02-01..2022-02-28
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-02-01..2022-02-28
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs, 
0 closed issues, 
2 open issues ([1][zksync-open_issues-1])

[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2022-02-01..2022-02-28

- [zkSync 2.0: Public Testnet is Live!](https://matterlabs.medium.com/zksync-2-0-public-testnet-is-live-de870ba9632a)

&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Apr 16 - May 13th | Online

[Scaling Ethereum](https://scaling.ethglobal.co/)

Apr 18-25 | Amsterdam

[Devconnect](https://devconnect.org/)

May 2-6 | Canada

[Financial Cryptography and Data Security 2022](http://fc22.ifca.ai/index.html)

May 29-30 | Trondheim, Norway

[CBCrypto 2022: International Workshop on Code-Based Cryptography](https://www.cb-crypto.org/)

May 30 - Jun 3 | Trondheim, Norway

[Eurocrypt 2022](https://eurocrypt.iacr.org/2022/)

Jun 13-17 | Šibenik, Croatia

[Summer school on real-world crypto and privacy](https://summerschool-croatia.cs.ru.nl/2022/)

Aug 29-31 | Arrillaga Alumni Center, Stanford University

[SBC'22: The Science of Blockchain Conference 2022](https://cbr.stanford.edu/sbc22/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Anon | Africa, Remote
- [Rust Developer](https://proximal-finch-4f9.notion.site/Rust-Developer-for-Blockchain-03afbedc6cf24b188bf9caff0581b958)

Blockstream | Remote
- [Software Library Engineer (Rust)](https://grnh.se/fc3876861us)
- [Software Library Engineer (C++)](https://grnh.se/69d260dc1us)
- [Full-Stack Software Engineer](https://grnh.se/aed921721us)
- [Cryptographic Engineer](https://grnh.se/3b9acf401us)
- [QA Engineer](https://grnh.se/ce2891871us)
- [Product Management Director, Liquid](https://grnh.se/aca150011us)
- [Sr. Product Manager](https://grnh.se/11354dd01us)
- [Product Manager](https://grnh.se/1bdd2ced1us)

Fuel Labs | Remote
- [Application Engineer [Rust, Sway]](https://jobs.lever.co/fuellabs/05417e26-4c6a-4be6-8fb9-95b51daf74cd)
- [Compiler/Language Engineer [Rust]](https://jobs.lever.co/fuellabs/5c5e0c29-2657-4046-ae24-0e3674361450)
- [Junior Software Engineer [Rust]](https://jobs.lever.co/fuellabs/c5a0c172-a378-4d25-b792-e2e96a6490c8)
- [Senior Protocol Engineer [Rust]](https://jobs.lever.co/fuellabs/11f95c0b-e2bb-4e13-bea2-7348b2a491fc)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


