---
title: "RiB Newsletter #59"
description: "April 2024"
date: 2024-05-01
categories:
  - "newsletters"
summary: "Welcome to the #59 edition of Rust in Blockchain.
This month, we spotlight `Rust in Cardano`, an ecosystem of Rust projects that interoperate with Cardano."
---

Welcome to the #59 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #58](/newsletters/rib-newsletter-58/).

&nbsp;

## Thanks

Thanks to contributors:
[AndrePanin],
[aleeusgr],
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[AndrePanin]: https://github.com/AndrePanin
[aleeusgr]: https://github.com/aleeusgr
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

_Rust in Cardano_.

[Cardano](https://github.com/IntersectMBO/cardano-node)
is written in Haskell, not Rust,
but there is an ecosystem of Rust projects that interoperate with Cardano.

- [Aiken](https://github.com/aiken-lang/aiken).
  A smart contract platform.
- [Pallas](https://github.com/txpipe/pallas).
  Rust building blocks for Cardano.
- [Scrolls](https://github.com/txpipe/scrolls).
  A read-optimized cache of on-chain entities.
- [Mithril](https://github.com/input-output-hk/mithril).
  Stake-based threshold multisignatures.
- [Hollow](https://github.com/txpipe/hollow).
  An SDK for building headless Cardano apps.
- [Dolos](https://github.com/txpipe/dolos).
  A specialized Cardano node.
- [Oura](https://github.com/txpipe/oura).
  A traffic monitor for Cardano's Ouroboros protocol.

&nbsp;

## Interesting Things

#### Blog Posts

- [The 4 Features of a zkVM: How to Choose your ZK Toolkit](https://www.risczero.com/blog/the-4-features-of-a-zkvm-how-to-choose-your-zk-toolkit)
- [Topology protocol walkthrough](https://www.guiltygyoza.xyz/2024/04/topology-protocol-walkthrough)

#### Papers

- [Ipotane: Achieving the Best of All Worlds in Asynchronous BFT](https://eprint.iacr.org/2024/653)
- [Optimal Asynchronous Byzantine Consensus with Fair Separability](https://eprint.iacr.org/2024/545)
- [Deep Selfish Proposing in Longest-Chain Proof-of-Stake Protocols](https://eprint.iacr.org/2024/622)

&nbsp;

## Most Active in April

[Reth](https://github.com/paradigmxyz/reth):
405 merged PRs,
138 closed issues,
83 open issues

[zkSync Era](https://github.com/matter-labs/zksync-era):
400 merged PRs,
93 closed issues,
24 open issues

[Starkware](https://github.com/starkware-libs):
372 merged PRs,
23 closed issues,
17 open issues

[Sui](https://github.com/MystenLabs):
369 merged PRs,
12 closed issues,
17 open issues

[Dfinity](https://github.com/dfinity):
335 merged PRs,
22 closed issues,
11 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

58 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]),
24 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
38 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [Announcing the first community-driven protocol changes: How StorSwift championed ARC0037 and 0038](https://aleo.org/post/key-protocol-changes-storswift-arcs/)

#### [Anoma](https://github.com/anoma)

88 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2]),
123 closed issues ([1][anoma-closed_issues-1]),
43 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/juvix-cairo-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/masp/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

230 merged PRs ([1][aptos-merged-prs-1], [2][aptos-merged-prs-2]),
44 closed issues ([1][aptos-closed_issues-1], [2][aptos-closed_issues-2]),
40 open issues ([1][aptos-open_issues-1], [2][aptos-open_issues-2])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aptos-merged-prs-2]: https://github.com/aptos-labs/aptos-indexer-processors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aptos-closed_issues-2]: https://github.com/aptos-labs/aptos-indexer-processors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[aptos-open_issues-2]: https://github.com/aptos-labs/aptos-indexer-processors/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Casper](https://github.com/casper-network)

49 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
14 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
16 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/casper-sidecar/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/casper-sidecar/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/casper-sidecar/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Chainflip](https://github.com/chainflip-io)

77 merged PRs ([1][chainflip-merged-prs-1]),
0 closed issues,
0 open issues

[chainflip-merged-prs-1]: https://github.com/chainflip-io/chainflip-backend/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [Chainflip Development Update — April 15th 2024](https://blog.chainflip.io/chainflip-development-update-april-15th-2024/)

#### [COMIT](https://github.com/comit-network)

2 merged PRs ([1][comit-merged-prs-1]),
0 closed issues,
2 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

48 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]),
33 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
10 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4], [5][concordium-open_issues-5])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-governance-committee-voting/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-rosetta/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-wallet-crypto-swift/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-dapp-starter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-governance-committee-voting/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-governance-committee-voting/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-rosetta/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-open_issues-4]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[concordium-open_issues-5]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

2 merged PRs ([1][conflux-merged-prs-1]),
1 closed issues ([1][conflux-closed_issues-1]),
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

335 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7], [8][dfinity-merged-prs-8], [9][dfinity-merged-prs-9], [10][dfinity-merged-prs-10], [11][dfinity-merged-prs-11], [12][dfinity-merged-prs-12], [13][dfinity-merged-prs-13], [14][dfinity-merged-prs-14], [15][dfinity-merged-prs-15], [16][dfinity-merged-prs-16], [17][dfinity-merged-prs-17], [18][dfinity-merged-prs-18], [19][dfinity-merged-prs-19], [20][dfinity-merged-prs-20], [21][dfinity-merged-prs-21]),
22 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5], [6][dfinity-closed_issues-6]),
11 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4], [5][dfinity-open_issues-5], [6][dfinity-open_issues-6])

[dfinity-merged-prs-1]: https://github.com/dfinity/subnet-rental-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/response-verification/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/nns-dapp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/bitcoin-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/dre/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/internet-identity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-7]: https://github.com/dfinity/stable-structures/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-8]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-9]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-10]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-11]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-12]: https://github.com/dfinity/canbench/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-13]: https://github.com/dfinity/dfxvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-14]: https://github.com/dfinity/ic-repl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-15]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-16]: https://github.com/dfinity/ICRC-1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-17]: https://github.com/dfinity/exchange-rate-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-18]: https://github.com/dfinity/ic-wasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-19]: https://github.com/dfinity/cycles-ledger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-20]: https://github.com/dfinity/dfx-extensions/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-merged-prs-21]: https://github.com/dfinity/canister-profiling/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/dre/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/internet-identity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-closed_issues-4]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-closed_issues-5]: https://github.com/dfinity/dfxvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-closed_issues-6]: https://github.com/dfinity/ICRC-1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/bitcoin-canister/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-open_issues-4]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-open_issues-5]: https://github.com/dfinity/ICRC-1/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dfinity-open_issues-6]: https://github.com/dfinity/cycles-ledger/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [ckBTC: A Decentralized Mechanism for Efficient Bitcoin Transfers](https://medium.com/dfinity/ckbtc-a-decentralized-mechanism-for-efficient-bitcoin-transfers-42b128bc44d9)

#### [Dusk Network](https://github.com/dusk-network)

69 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5], [6][dusk_network-merged-prs-6], [7][dusk_network-merged-prs-7], [8][dusk_network-merged-prs-8], [9][dusk_network-merged-prs-9]),
97 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4], [5][dusk_network-closed_issues-5], [6][dusk_network-closed_issues-6], [7][dusk_network-closed_issues-7], [8][dusk_network-closed_issues-8], [9][dusk_network-closed_issues-9], [10][dusk_network-closed_issues-10], [11][dusk_network-closed_issues-11], [12][dusk_network-closed_issues-12], [13][dusk_network-closed_issues-13]),
36 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3], [4][dusk_network-open_issues-4], [5][dusk_network-open_issues-5], [6][dusk_network-open_issues-6], [7][dusk_network-open_issues-7], [8][dusk_network-open_issues-8])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/Poseidon252/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/kadcast/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-4]: https://github.com/dusk-network/citadel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-5]: https://github.com/dusk-network/phoenix-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-6]: https://github.com/dusk-network/jubjub-schnorr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-7]: https://github.com/dusk-network/piecrust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-8]: https://github.com/dusk-network/bls12_381-bls/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-merged-prs-9]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/Poseidon252/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-4]: https://github.com/dusk-network/kadcast/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-5]: https://github.com/dusk-network/citadel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-6]: https://github.com/dusk-network/phoenix-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-7]: https://github.com/dusk-network/jubjub-schnorr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-8]: https://github.com/dusk-network/bls12_381-bls/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-9]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-10]: https://github.com/dusk-network/merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-11]: https://github.com/dusk-network/moat/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-12]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-closed_issues-13]: https://github.com/dusk-network/bls12_381-sign/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/citadel/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/phoenix-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-4]: https://github.com/dusk-network/jubjub-schnorr/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-5]: https://github.com/dusk-network/piecrust/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-6]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-7]: https://github.com/dusk-network/merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[dusk_network-open_issues-8]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

277 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5], [6][espresso_systems-merged-prs-6], [7][espresso_systems-merged-prs-7], [8][espresso_systems-merged-prs-8], [9][espresso_systems-merged-prs-9], [10][espresso_systems-merged-prs-10], [11][espresso_systems-merged-prs-11]),
68 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4], [5][espresso_systems-closed_issues-5], [6][espresso_systems-closed_issues-6], [7][espresso_systems-closed_issues-7]),
45 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4], [5][espresso_systems-open_issues-5], [6][espresso_systems-open_issues-6], [7][espresso_systems-open_issues-7], [8][espresso_systems-open_issues-8])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/espresso-sequencer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/Push-CDN/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/hotshot-builder-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/hotshot-query-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-6]: https://github.com/EspressoSystems/hotshot-events-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-7]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-8]: https://github.com/EspressoSystems/surf-disco/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-9]: https://github.com/EspressoSystems/es-version/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-10]: https://github.com/EspressoSystems/async-compatibility-layer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-merged-prs-11]: https://github.com/EspressoSystems/tide-disco/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/Push-CDN/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/hotshot-builder-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-5]: https://github.com/EspressoSystems/hotshot-query-service/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-6]: https://github.com/EspressoSystems/hotshot-events-service/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-closed_issues-7]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/hotshot-builder-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/hotshot-query-service/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-5]: https://github.com/EspressoSystems/hotshot-events-service/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-6]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-7]: https://github.com/EspressoSystems/discord-faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[espresso_systems-open_issues-8]: https://github.com/EspressoSystems/tide-disco/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [Partnering with 10 node operators to decentralize Espresso’s Cappuccino testnet](https://medium.com/@espressosys/partnering-with-10-node-operators-to-decentralize-espressos-cappuccino-testnet-a802dbbab16c)

#### [Filecoin](https://github.com/filecoin-project)

22 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6]),
3 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2]),
2 open issues ([1][filecoin-open_issues-1])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/filplus-backend/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-gpu-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [Filecoin News 85](https://filecoin.io/blog/posts/filecoin-news-85/)
- [Filecoin Network Version 22 Dragon Upgrade](https://status.filecoin.io/incidents/w1d72mxp08vp)

#### [Findora](https://github.com/FindoraNetwork)

28 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/evm-staking-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[findora-merged-prs-4]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

28 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5]),
0 closed issues,
1 open issues ([1][fluence-open_issues-1])

[fluence-merged-prs-1]: https://github.com/fluencelabs/nox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/capacity-commitment-prover/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/decider/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fluence-open_issues-1]: https://github.com/fluencelabs/examples/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [$FLT: Staking for Compute Resources](https://blog.fluence.network/flt-staking-for-compute-resources/)

#### [Fuel](https://github.com/FuelLabs)

194 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12]),
91 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
73 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8], [9][fuel-open_issues-9], [10][fuel-open_issues-10])

[fuel-merged-prs-1]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/sway-applications/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-block-committer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-subgraph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-11]: https://github.com/FuelLabs/forc.pub/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-merged-prs-12]: https://github.com/FuelLabs/fuel-canary-watchtower/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/sway-applications/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuel-subgraph/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-block-committer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-9]: https://github.com/FuelLabs/fuel-core-client-ext/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fuel-open_issues-10]: https://github.com/FuelLabs/indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

51 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]),
30 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3], [4][golem-closed_issues-4]),
25 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3], [4][golem-open_issues-4])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/erc20_payment_lib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-merged-prs-5]: https://github.com/golemfactory/ya-runtime-ai/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/erc20_payment_lib/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/ya-runtime-ai/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-closed_issues-4]: https://github.com/golemfactory/ya-runtime-wasi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-open_issues-3]: https://github.com/golemfactory/ya-runtime-ai/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[golem-open_issues-4]: https://github.com/golemfactory/gvmkit-build-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Grin](https://github.com/mimblewimble/grin)

7 merged PRs ([1][grin-merged-prs-1], [2][grin-merged-prs-2], [3][grin-merged-prs-3], [4][grin-merged-prs-4]),
2 closed issues ([1][grin-closed_issues-1], [2][grin-closed_issues-2]),
0 open issues

[grin-merged-prs-1]: https://github.com/mimblewimble/grin-gui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[grin-merged-prs-2]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[grin-merged-prs-3]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[grin-merged-prs-4]: https://github.com/mimblewimble/rust-secp256k1-zkp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[grin-closed_issues-1]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[grin-closed_issues-2]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Helium](https://github.com/helium)

21 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3]),
8 closed issues ([1][helium-closed_issues-1]),
2 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2])

[helium-merged-prs-1]: https://github.com/helium/oracles/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/proto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-anchor-gen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/oracles/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/oracles/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[helium-open_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

210 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4], [5][holochain-merged-prs-5], [6][holochain-merged-prs-6], [7][holochain-merged-prs-7], [8][holochain-merged-prs-8], [9][holochain-merged-prs-9], [10][holochain-merged-prs-10], [11][holochain-merged-prs-11]),
31 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2], [3][holochain-closed_issues-3], [4][holochain-closed_issues-4]),
95 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2], [3][holochain-open_issues-3], [4][holochain-open_issues-4], [5][holochain-open_issues-5])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/deepkey/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-4]: https://github.com/holochain/sodoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-5]: https://github.com/holochain/scaffolding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-6]: https://github.com/holochain/app-store-dnas/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-7]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-8]: https://github.com/holochain/devhub-dnas/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-9]: https://github.com/holochain/wind-tunnel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-10]: https://github.com/holochain/tx5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-merged-prs-11]: https://github.com/holochain/holochain-serialization/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/holochain-client-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-closed_issues-3]: https://github.com/holochain/scaffolding/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-closed_issues-4]: https://github.com/holochain/tx5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/scaffolding/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-open_issues-3]: https://github.com/holochain/wind-tunnel/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-open_issues-4]: https://github.com/holochain/sbd/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[holochain-open_issues-5]: https://github.com/holochain/tx5/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [IOTA](https://github.com/iotaledger)

32 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5]),
19 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2]),
12 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4])

[iota-merged-prs-1]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/iota-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/uni-resolver-driver-iota/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/inx-chronicle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/inx-chronicle/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[iota-open_issues-4]: https://github.com/iotaledger/common-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [The IOTA Foundation’s Dynamic Start to the Year](https://blog.iota.org/q1-2024-progress-report/)

#### [Lurk](https://github.com/lurk-lab)

8 merged PRs ([1][lurk-merged-prs-1], [2][lurk-merged-prs-2], [3][lurk-merged-prs-3]),
4 closed issues ([1][lurk-closed_issues-1], [2][lurk-closed_issues-2], [3][lurk-closed_issues-3]),
2 open issues ([1][lurk-open_issues-1], [2][lurk-open_issues-2])

[lurk-merged-prs-1]: https://github.com/lurk-lab/lurk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lurk-merged-prs-2]: https://github.com/lurk-lab/ci-workflows/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lurk-merged-prs-3]: https://github.com/lurk-lab/bellpepper-gadgets/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lurk-closed_issues-1]: https://github.com/lurk-lab/arecibo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lurk-closed_issues-2]: https://github.com/lurk-lab/lurk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lurk-closed_issues-3]: https://github.com/lurk-lab/ci-workflows/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lurk-open_issues-1]: https://github.com/lurk-lab/arecibo/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lurk-open_issues-2]: https://github.com/lurk-lab/lurk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

106 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3]),
5 closed issues ([1][maidsafe-closed_issues-1]),
9 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2], [3][maidsafe-open_issues-3], [4][maidsafe-open_issues-4])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/sn-testnet-deploy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/self_encryption/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[maidsafe-open_issues-2]: https://github.com/maidsafe/qp2p/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[maidsafe-open_issues-3]: https://github.com/maidsafe/self_encryption/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[maidsafe-open_issues-4]: https://github.com/maidsafe/safeup/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

37 merged PRs ([1][mina-merged-prs-1]),
12 closed issues ([1][mina-closed_issues-1]),
12 open issues ([1][mina-open_issues-1])

[mina-merged-prs-1]: https://github.com/openmina/openmina/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[mina-closed_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

32 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2], [3][mobilecoin-merged-prs-3]),
1 closed issues ([1][mobilecoin-closed_issues-1]),
0 open issues

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/sgx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[mobilecoin-merged-prs-3]: https://github.com/mobilecoinfoundation/attestation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

119 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3], [4][multiversx-merged-prs-4], [5][multiversx-merged-prs-5], [6][multiversx-merged-prs-6], [7][multiversx-merged-prs-7], [8][multiversx-merged-prs-8]),
0 closed issues,
2 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/sc-gravity-restaking-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-exchange-tools-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-merged-prs-4]: https://github.com/multiversx/sc-guilds-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-merged-prs-5]: https://github.com/multiversx/mx-contracts-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-merged-prs-6]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-merged-prs-7]: https://github.com/multiversx/mx-metabonding-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-merged-prs-8]: https://github.com/multiversx/mx-sovereign-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-exchange-sc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

290 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10], [11][near-merged-prs-11], [12][near-merged-prs-12], [13][near-merged-prs-13], [14][near-merged-prs-14], [15][near-merged-prs-15], [16][near-merged-prs-16]),
91 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8], [9][near-closed_issues-9], [10][near-closed_issues-10], [11][near-closed_issues-11]),
136 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8], [9][near-open_issues-9], [10][near-open_issues-10], [11][near-open_issues-11], [12][near-open_issues-12], [13][near-open_issues-13], [14][near-open_issues-14])

[near-merged-prs-1]: https://github.com/near/rollup-data-availability/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-abi-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/queryapi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/cargo-near/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/mpc-recovery/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-9]: https://github.com/near/read-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-10]: https://github.com/near/multichain-gas-station-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-11]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-12]: https://github.com/near/pagoda-relayer-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-13]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-14]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-15]: https://github.com/near/multichain-relayer-server/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-merged-prs-16]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/rollup-data-availability/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/queryapi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/mpc-recovery/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-7]: https://github.com/near/multichain-gas-station-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-8]: https://github.com/near/pagoda-relayer-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-9]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-10]: https://github.com/near/cargo-near-new-project-template/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-closed_issues-11]: https://github.com/near/bos-loader/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/rollup-data-availability/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/queryapi/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/cargo-near/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-7]: https://github.com/near/mpc-recovery/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-8]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-9]: https://github.com/near/multichain-gas-station-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-10]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-11]: https://github.com/near/pagoda-relayer-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-12]: https://github.com/near/near-sdk-contract-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-13]: https://github.com/near/near-light-client/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[near-open_issues-14]: https://github.com/near/near-workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Nervos](https://github.com/nervosnetwork)

35 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7]),
7 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
7 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4], [5][nervos-open_issues-5])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-light-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-merged-prs-7]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-light-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-light-client/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-std/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-open_issues-4]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[nervos-open_issues-5]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

8 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]),
1 closed issues ([1][oasis-closed_issues-1]),
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[oasis-merged-prs-2]: https://github.com/oasisprotocol/tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

332 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15], [16][parity-merged-prs-16], [17][parity-merged-prs-17], [18][parity-merged-prs-18], [19][parity-merged-prs-19], [20][parity-merged-prs-20], [21][parity-merged-prs-21], [22][parity-merged-prs-22], [23][parity-merged-prs-23], [24][parity-merged-prs-24]),
140 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12]),
133 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11])

[parity-merged-prs-1]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/substrate-telemetry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/polkadot-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/polkadot-introspector/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/try-runtime-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/zombienet-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/parity-scale-codec/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/psvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/smart-bench/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/litep2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/polkadot-staking-miner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/scale-typegen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/scale-value/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-15]: https://github.com/paritytech/scale-encode/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-16]: https://github.com/paritytech/scale-decode/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-17]: https://github.com/paritytech/scale-bits/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-18]: https://github.com/paritytech/scale-type-resolver/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-19]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-20]: https://github.com/paritytech/trie/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-21]: https://github.com/paritytech/disabling-e2e-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-22]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-23]: https://github.com/paritytech/scale-info/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-merged-prs-24]: https://github.com/paritytech/erasure-coding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/substrate-telemetry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/polkadot-introspector/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/zombienet-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/psvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/litep2p/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/polkadot-staking-miner/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/subport/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/substrate-telemetry/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/psvm/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/litep2p/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/polkadot-staking-miner/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/prdoc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/subport/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [Polkadot’s Solution to the Byzantine Generals Problem: Grandpa Protocol](https://blog.chainsafe.io/grandpa-protocol-polkadot/)

#### [Radix](https://github.com/radixdlt)

95 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3], [4][radix-merged-prs-4]),
0 closed issues,
1 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/official-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/sargon/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/radix-engine-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[radix-merged-prs-4]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

5 merged PRs ([1][secret_network-merged-prs-1]),
0 closed issues,
0 open issues

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

34 merged PRs ([1][solana-merged-prs-1]),
59 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
5 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Soroban](https://github.com/stellar)

60 merged PRs ([1][soroban-merged-prs-1], [2][soroban-merged-prs-2], [3][soroban-merged-prs-3], [4][soroban-merged-prs-4], [5][soroban-merged-prs-5], [6][soroban-merged-prs-6]),
23 closed issues ([1][soroban-closed_issues-1], [2][soroban-closed_issues-2], [3][soroban-closed_issues-3], [4][soroban-closed_issues-4]),
17 open issues ([1][soroban-open_issues-1], [2][soroban-open_issues-2], [3][soroban-open_issues-3], [4][soroban-open_issues-4], [5][soroban-open_issues-5])

[soroban-merged-prs-1]: https://github.com/stellar/soroban-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-merged-prs-2]: https://github.com/stellar/rs-soroban-env/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-merged-prs-3]: https://github.com/stellar/soroflare/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-merged-prs-4]: https://github.com/stellar/soroban-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-merged-prs-5]: https://github.com/stellar/rs-soroban-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-merged-prs-6]: https://github.com/stellar/rs-stellar-xdr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-closed_issues-1]: https://github.com/stellar/soroban-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-closed_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-closed_issues-3]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-closed_issues-4]: https://github.com/stellar/rs-stellar-xdr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-open_issues-1]: https://github.com/stellar/soroban-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-open_issues-2]: https://github.com/stellar/soroban-example-dapp/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-open_issues-3]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-open_issues-4]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[soroban-open_issues-5]: https://github.com/stellar/xdrgen/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [SDF’s Horizon: Limiting Data to 1 year](https://stellar.org/blog/foundation-news/sdf-s-horizon-limiting-data-to-1-year)

#### [Spacemesh](https://github.com/spacemeshos)

5 merged PRs ([1][spacemesh-merged-prs-1], [2][spacemesh-merged-prs-2]),
1 closed issues ([1][spacemesh-closed_issues-1]),
2 open issues ([1][spacemesh-open_issues-1])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/post-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[spacemesh-merged-prs-2]: https://github.com/spacemeshos/quicksync-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/post-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[spacemesh-open_issues-1]: https://github.com/spacemeshos/post-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

63 merged PRs ([1][subspace_network-merged-prs-1], [2][subspace_network-merged-prs-2]),
18 closed issues ([1][subspace_network-closed_issues-1], [2][subspace_network-closed_issues-2]),
8 open issues ([1][subspace_network-open_issues-1], [2][subspace_network-open_issues-2])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[subspace_network-merged-prs-2]: https://github.com/subspace/space-acres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[subspace_network-closed_issues-2]: https://github.com/subspace/space-acres/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[subspace_network-open_issues-2]: https://github.com/subspace/space-acres/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

369 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2], [3][sui-merged-prs-3]),
12 closed issues ([1][sui-closed_issues-1]),
17 open issues ([1][sui-open_issues-1], [2][sui-open_issues-2])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[sui-merged-prs-2]: https://github.com/MystenLabs/fastcrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[sui-merged-prs-3]: https://github.com/MystenLabs/multisig_tic-tac-toe/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[sui-open_issues-2]: https://github.com/MystenLabs/fastcrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [Dive into Data and Debugging with Sentio on Sui](https://blog.sui.io/sentio-launch-data-and-debugging-tools/)
- [Mysticeti Set to Supercharge Consensus on Sui](https://blog.sui.io/mysticeti-consensus-reduce-latency/)
- [All About Directed Acyclic Graphs](https://blog.sui.io/all-about-directed-acyclic-graphs/)
- [Migrate to Move 2024](https://blog.sui.io/move-2024-migration-guide/)

#### [Vara](https://github.com/gear-tech)

70 merged PRs ([1][vara-merged-prs-1], [2][vara-merged-prs-2]),
34 closed issues ([1][vara-closed_issues-1], [2][vara-closed_issues-2]),
32 open issues ([1][vara-open_issues-1], [2][vara-open_issues-2])

[vara-merged-prs-1]: https://github.com/gear-tech/sails/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[vara-merged-prs-2]: https://github.com/gear-tech/gear/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[vara-closed_issues-1]: https://github.com/gear-tech/sails/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[vara-closed_issues-2]: https://github.com/gear-tech/gear/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[vara-open_issues-1]: https://github.com/gear-tech/sails/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[vara-open_issues-2]: https://github.com/gear-tech/gear/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Vara](https://github.com/gear-tech)

#### [Zcash](https://github.com/zcash)

16 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
6 closed issues ([1][zcash-closed_issues-1]),
32 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/zcash-test-vectors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/zcash-test-vectors/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

- [New Release 5.9.0](https://electriccoin.co/blog/new-release-5-9-0/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

2 merged PRs ([1][aluvm-merged-prs-1]),
0 closed issues,
0 open issues

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

44 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]),
24 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
13 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4], [5][bdk-open_issues-5])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/coin-select/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/book-of-bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/book-of-bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bdk-open_issues-5]: https://github.com/bitcoindevkit/coin-select/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Bitcoin Protocol](https://github.com/BP-WG)

4 merged PRs ([1][bitcoin_protocol-merged-prs-1], [2][bitcoin_protocol-merged-prs-2]),
0 closed issues,
1 open issues ([1][bitcoin_protocol-open_issues-1])

[bitcoin_protocol-merged-prs-1]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bitcoin_protocol-merged-prs-2]: https://github.com/BP-WG/bp-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[bitcoin_protocol-open_issues-1]: https://github.com/BP-WG/bp-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Cyphernet](https://github.com/cyphernet-dao)

1 merged PRs ([1][cyphernet-merged-prs-1]),
0 closed issues,
0 open issues

[cyphernet-merged-prs-1]: https://github.com/cyphernet-dao/rust-internet2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

219 merged PRs ([1][fedimint-merged-prs-1], [2][fedimint-merged-prs-2]),
36 closed issues ([1][fedimint-closed_issues-1]),
54 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fedimint-merged-prs-2]: https://github.com/fedimint/fedimint-custom-modules-example/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

41 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3], [4][ldk-merged-prs-4], [5][ldk-merged-prs-5], [6][ldk-merged-prs-6]),
11 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2], [3][ldk-closed_issues-3]),
14 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2], [3][ldk-open_issues-3])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/vss-rust-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-merged-prs-4]: https://github.com/lightningdevkit/lightning-liquidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-merged-prs-5]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-merged-prs-6]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-closed_issues-3]: https://github.com/lightningdevkit/lightning-liquidity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ldk-open_issues-3]: https://github.com/lightningdevkit/lightning-liquidity/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

2 merged PRs ([1][lnp/bp-merged-prs-1]),
1 closed issues ([1][lnp/bp-closed_issues-1]),
0 open issues

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

1 merged PRs ([1][nomic-merged-prs-1]),
0 closed issues,
0 open issues

[nomic-merged-prs-1]: https://github.com/turbofish-org/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

36 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2], [3][rgb-merged-prs-3], [4][rgb-merged-prs-4]),
15 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2], [3][rgb-closed_issues-3], [4][rgb-closed_issues-4]),
7 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-merged-prs-3]: https://github.com/RGB-WG/rgb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-merged-prs-4]: https://github.com/RGB-WG/rgb-schemata/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-closed_issues-3]: https://github.com/RGB-WG/rgb-std/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-closed_issues-4]: https://github.com/RGB-WG/rgb-schemata/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rgb-open_issues-2]: https://github.com/RGB-WG/rgb-std/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

64 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
17 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]),
20 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/bitcoind/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/rust-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/bitcoind/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/rust-bech32-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Rust Payjoin](https://github.com/payjoin/rust-payjoin)

5 merged PRs ([1][rust_payjoin-merged-prs-1]),
3 closed issues ([1][rust_payjoin-closed_issues-1]),
2 open issues ([1][rust_payjoin-open_issues-1])

[rust_payjoin-merged-prs-1]: https://github.com/payjoin/rust-payjoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_payjoin-closed_issues-1]: https://github.com/payjoin/rust-payjoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[rust_payjoin-open_issues-1]: https://github.com/payjoin/rust-payjoin/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

1 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Strict Types](https://github.com/strict-types)

3 merged PRs ([1][strict_types-merged-prs-1], [2][strict_types-merged-prs-2]),
0 closed issues,
1 open issues ([1][strict_types-open_issues-1])

[strict_types-merged-prs-1]: https://github.com/strict-types/strict-encoding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[strict_types-merged-prs-2]: https://github.com/strict-types/strict-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[strict_types-open_issues-1]: https://github.com/strict-types/strict-encoding/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

1 merged PRs ([1][talaia-merged-prs-1]),
0 closed issues,
0 open issues

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

1 merged PRs ([1][ethers-rs-merged-prs-1]),
1 closed issues ([1][ethers-rs-closed_issues-1]),
1 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

207 merged PRs ([1][foundry-merged-prs-1], [2][foundry-merged-prs-2], [3][foundry-merged-prs-3], [4][foundry-merged-prs-4]),
179 closed issues ([1][foundry-closed_issues-1], [2][foundry-closed_issues-2], [3][foundry-closed_issues-3], [4][foundry-closed_issues-4]),
126 open issues ([1][foundry-open_issues-1], [2][foundry-open_issues-2], [3][foundry-open_issues-3], [4][foundry-open_issues-4], [5][foundry-open_issues-5])

[foundry-merged-prs-1]: https://github.com/foundry-rs/block-explorers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-merged-prs-2]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-merged-prs-3]: https://github.com/foundry-rs/starknet-foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-merged-prs-4]: https://github.com/foundry-rs/compilers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/block-explorers/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-closed_issues-2]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-closed_issues-3]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-closed_issues-4]: https://github.com/foundry-rs/compilers/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/block-explorers/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-open_issues-2]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-open_issues-3]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-open_issues-4]: https://github.com/foundry-rs/compilers/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[foundry-open_issues-5]: https://github.com/foundry-rs/foundry-rust-template/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

93 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2], [3][lighthouse-merged-prs-3], [4][lighthouse-merged-prs-4], [5][lighthouse-merged-prs-5]),
30 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2], [3][lighthouse-closed_issues-3]),
15 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-merged-prs-3]: https://github.com/sigp/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-merged-prs-4]: https://github.com/sigp/milhouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-merged-prs-5]: https://github.com/sigp/gossipsub-testground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-closed_issues-3]: https://github.com/sigp/enr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/milhouse/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Polygon Zero](https://github.com/0xPolygonZero)

83 merged PRs ([1][polygon_zero-merged-prs-1], [2][polygon_zero-merged-prs-2], [3][polygon_zero-merged-prs-3], [4][polygon_zero-merged-prs-4], [5][polygon_zero-merged-prs-5], [6][polygon_zero-merged-prs-6]),
18 closed issues ([1][polygon_zero-closed_issues-1], [2][polygon_zero-closed_issues-2], [3][polygon_zero-closed_issues-3], [4][polygon_zero-closed_issues-4], [5][polygon_zero-closed_issues-5], [6][polygon_zero-closed_issues-6]),
16 open issues ([1][polygon_zero-open_issues-1], [2][polygon_zero-open_issues-2], [3][polygon_zero-open_issues-3], [4][polygon_zero-open_issues-4])

[polygon_zero-merged-prs-1]: https://github.com/0xPolygonZero/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-merged-prs-2]: https://github.com/0xPolygonZero/zk_evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-merged-prs-3]: https://github.com/0xPolygonZero/zero-bin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-merged-prs-4]: https://github.com/0xPolygonZero/paladin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-merged-prs-5]: https://github.com/0xPolygonZero/eth-tx-proof/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-merged-prs-6]: https://github.com/0xPolygonZero/eth-trie-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-closed_issues-1]: https://github.com/0xPolygonZero/plonky2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-closed_issues-2]: https://github.com/0xPolygonZero/zk_evm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-closed_issues-3]: https://github.com/0xPolygonZero/zero-bin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-closed_issues-4]: https://github.com/0xPolygonZero/eth-tx-proof/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-closed_issues-5]: https://github.com/0xPolygonZero/evm-tests/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-closed_issues-6]: https://github.com/0xPolygonZero/eth-trie-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-open_issues-1]: https://github.com/0xPolygonZero/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-open_issues-2]: https://github.com/0xPolygonZero/zk_evm/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-open_issues-3]: https://github.com/0xPolygonZero/zero-bin/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[polygon_zero-open_issues-4]: https://github.com/0xPolygonZero/paladin/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

405 merged PRs ([1][reth-merged-prs-1]),
138 closed issues ([1][reth-closed_issues-1]),
83 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

372 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3], [4][starkware-merged-prs-4], [5][starkware-merged-prs-5], [6][starkware-merged-prs-6], [7][starkware-merged-prs-7]),
23 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
17 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2], [3][starkware-open_issues-3])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/blockifier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/mempool/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-merged-prs-4]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-merged-prs-5]: https://github.com/starkware-libs/committer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-merged-prs-6]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-merged-prs-7]: https://github.com/starkware-libs/stwo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/blockifier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/blockifier/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[starkware-open_issues-3]: https://github.com/starkware-libs/starknet-api/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

#### [zkSync Era](https://github.com/matter-labs/zksync-era)

400 merged PRs ([1][zksync_era-merged-prs-1], [2][zksync_era-merged-prs-2], [3][zksync_era-merged-prs-3], [4][zksync_era-merged-prs-4], [5][zksync_era-merged-prs-5], [6][zksync_era-merged-prs-6], [7][zksync_era-merged-prs-7], [8][zksync_era-merged-prs-8], [9][zksync_era-merged-prs-9], [10][zksync_era-merged-prs-10], [11][zksync_era-merged-prs-11], [12][zksync_era-merged-prs-12], [13][zksync_era-merged-prs-13], [14][zksync_era-merged-prs-14], [15][zksync_era-merged-prs-15], [16][zksync_era-merged-prs-16], [17][zksync_era-merged-prs-17], [18][zksync_era-merged-prs-18], [19][zksync_era-merged-prs-19], [20][zksync_era-merged-prs-20]),
93 closed issues ([1][zksync_era-closed_issues-1], [2][zksync_era-closed_issues-2], [3][zksync_era-closed_issues-3], [4][zksync_era-closed_issues-4], [5][zksync_era-closed_issues-5]),
24 open issues ([1][zksync_era-open_issues-1], [2][zksync_era-open_issues-2], [3][zksync_era-open_issues-3], [4][zksync_era-open_issues-4])

[zksync_era-merged-prs-1]: https://github.com/matter-labs/era-compiler-llvm-builder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-2]: https://github.com/matter-labs/zksync-era/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-3]: https://github.com/matter-labs/era-compiler-vyper/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-4]: https://github.com/matter-labs/foundry-zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-5]: https://github.com/matter-labs/era-consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-6]: https://github.com/matter-labs/era-zkevm_circuits/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-7]: https://github.com/matter-labs/zksync-withdrawal-finalizer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-8]: https://github.com/matter-labs/era-zk_evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-9]: https://github.com/matter-labs/teepot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-10]: https://github.com/matter-labs/era-compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-11]: https://github.com/matter-labs/era-compiler-tester/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-12]: https://github.com/matter-labs/era-zkevm_test_harness/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-13]: https://github.com/matter-labs/era-zkevm_opcode_defs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-14]: https://github.com/matter-labs/era-compiler-llvm-context/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-15]: https://github.com/matter-labs/era-zkevm_tester/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-16]: https://github.com/matter-labs/era-boojum/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-17]: https://github.com/matter-labs/vise/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-18]: https://github.com/matter-labs/era-boojum-cuda/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-19]: https://github.com/matter-labs/era-shivini/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-merged-prs-20]: https://github.com/matter-labs/risc_v_simulator/pulls?q=is%3Apr+is%3Aclosed+merged%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-closed_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-closed_issues-2]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-closed_issues-3]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-closed_issues-4]: https://github.com/matter-labs/era-test-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-closed_issues-5]: https://github.com/matter-labs/era-consensus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-open_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-open_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-open_issues-3]: https://github.com/matter-labs/era-test-node/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot
[zksync_era-open_issues-4]: https://github.com/matter-labs/zksync-withdrawal-finalizer/issues?q=is%3Aissue+is%3Aopen+created%3A2024-04-01..2024-04-30%20-author:app/dependabot

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->


May 3-5 | Sydney, Australia | [ETHGlobal Sydney](https://ethglobal.com/events/sydney)

May 18-19 | Brisbane, Australia | [AI + Web3 Convention](https://web3convention.com/)

May 20-Jun 20 | Singapore | [The Polkadot Blockchain Academy](https://polkadot.network/development/blockchain-academy/)

May 21-23 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

May 24-26 | Berlin, Germany | [ETHBerlin](https://ethberlin.org/)

May 26-30 | Zurich, Switzerland | [Eurocrypt 2024](https://eurocrypt.iacr.org/2024/)

May 29-31 | Austin, US | [Consensus](https://consensus2024.coindesk.com/)

May 31-Jun 2 | Prague, Czech Republic | [ETH Prague](https://ethprague.com/)

Jun 5-6 | Santa Clara, US | [Blockchain Expo North America](https://blockchain-expo.com/northamerica/)

Jun 13-26 | Online | [StarkHack Async hackathon](https://ethglobal.com/events/starkhack)

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


