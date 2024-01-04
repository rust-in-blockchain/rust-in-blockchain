---
title: "RiB Newsletter #55"
description: "December 2023"
date: 2024-01-03
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #55 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #54](/newsletters/rib-newsletter-54/).

&nbsp;

## Thanks

Thanks to contributors:
Aulee, Hunter Beast,
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

[iroh](https://github.com/n0-computer/iroh).

`iroh` is a protocol for syncing and moving bytes
over peer-to-peer QUIC connections.
Data is verified in transit with blake3 verified streaming
via the [bao-tree](https://github.com/n0-computer/bao-tree) crate.

[`sendme`](https://github.com/n0-computer/sendme)
is a simple file transfer program demonstrating
the use of `iroh`.

&nbsp;


## Interesting Things

#### Blog Posts

- [Lambdaworks as a drop-in replacement for Winterfell to prove the Miden-VM](https://blog.lambdaclass.com/lambdaworks-as-a-drop-in-replacement-for-winterfell/)
- [Lambdaworks Design and Usage: Part 1 - Finite Fields](https://blog.lambdaclass.com/lambdaworks-design-and-usage-part-1-finite-fields/)

#### Papers

- [Proof of Compliance for Anonymous, Unlinkable Messages](https://eprint.iacr.org/2023/1900)
- [COMMON: Order Book with Privacy](https://eprint.iacr.org/2023/1868)
- [Shoal: Improving DAG-BFT Latency And Robustness](https://arxiv.org/abs/2306.03058). Improvements to Bullshark.

#### Projects

- [arkworks-bridge](https://github.com/martyall/arkworks-bridge).
  Importing R1CS and witness files into arkworks via json.
- [bria](https://github.com/GaloyMoney/bria). Transaction batching and UTXO management for Bitcoin.

&nbsp;

## Most Active in December

[Sui](https://github.com/MystenLabs):
321 merged PRs,
169 closed issues,
2 open issues

[Dfinity](https://github.com/dfinity):
313 merged PRs,
3 closed issues,
8 open issues

[Starkware](https://github.com/starkware-libs):
311 merged PRs,
8 closed issues,
9 open issues

[Parity](https://github.com/paritytech):
288 merged PRs,
100 closed issues,
80 open issues

[zkSync Era](https://github.com/matter-labs/zksync-era):
250 merged PRs,
6 closed issues,
15 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

72 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
2119 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
2830 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Aleo completes security audits of snarkOS & snarkVM](https://aleo.org/post/aleo-completes-security-audits-of-snarkos-and-snarkvm/)
- [Public report of Aleo's consensus (Bullshark)](https://www.zksecurity.xyz/blog/posts/aleo-consensus/)
- [Public report of Aleo's synthesizer](https://www.zksecurity.xyz/blog/posts/aleo-synthesizer/)
- [Announcing the Aleo Foundation](https://aleo.org/post/announcing-aleo-foundation/)

#### [Anoma](https://github.com/anoma)

57 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
36 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
12 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/namada-sdk-starter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/namada-trusted-setup-claimer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/zkp-compiler-shootout/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/namada-sdk-starter/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

221 merged PRs ([1][aptos-merged-prs-1], [2][aptos-merged-prs-2]),
41 closed issues ([1][aptos-closed_issues-1], [2][aptos-closed_issues-2]),
52 open issues ([1][aptos-open_issues-1], [2][aptos-open_issues-2])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aptos-merged-prs-2]: https://github.com/aptos-labs/aptos-indexer-processors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aptos-closed_issues-2]: https://github.com/aptos-labs/aptos-indexer-processors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[aptos-open_issues-2]: https://github.com/aptos-labs/aptos-indexer-processors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Aggregators: How sequential workloads are executed in parallel on the Aptos Blockchain](https://medium.com/aptoslabs/aggregators-how-sequential-workloads-are-executed-in-parallel-on-the-aptos-blockchain-e7992c70cefb)

#### [Casper](https://github.com/casper-network)

6 merged PRs ([1][casper-merged-prs-1]),
8 closed issues ([1][casper-closed_issues-1]),
28 open issues ([1][casper-open_issues-1])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [2023 in Review: A Remarkable Year for Casper](https://casper.network/en-us/news/casper-year-in-review--2023)

#### [Chainflip](https://github.com/chainflip-io)

63 merged PRs ([1][chainflip-merged-prs-1]),
1 closed issues ([1][chainflip-closed_issues-1]),
0 open issues

[chainflip-merged-prs-1]: https://github.com/chainflip-io/chainflip-backend/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[chainflip-closed_issues-1]: https://github.com/chainflip-io/chainflip-backend/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Swapping Pre Release](https://blog.chainflip.io/swapping-pre-release/)

#### [COMIT](https://github.com/comit-network)

1 merged PRs ([1][comit-merged-prs-1]),
4 closed issues ([1][comit-closed_issues-1]),
4 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

16 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
3 closed issues ([1][concordium-closed_issues-1]),
4 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-governance-committee-voting/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-governance-committee-voting/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-governance-committee-voting/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

24 merged PRs ([1][conflux-merged-prs-1]),
2 closed issues ([1][conflux-closed_issues-1]),
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Monthly Progress Report — December 2023](https://medium.com/conflux-network/monthly-progress-report-december-2023-a7582e425b6f)

#### [DarkFi](https://dark.fi)

2 merged PRs ([1][darkfi-merged-prs-1]),
1 closed issues ([1][darkfi-closed_issues-1]),
2 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Development Update Q423](https://dark.fi/insights/development-update-q423.html)

#### [Dfinity](https://github.com/dfinity)

313 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7], [8][dfinity-merged-prs-8], [9][dfinity-merged-prs-9], [10][dfinity-merged-prs-10], [11][dfinity-merged-prs-11], [12][dfinity-merged-prs-12], [13][dfinity-merged-prs-13], [14][dfinity-merged-prs-14], [15][dfinity-merged-prs-15], [16][dfinity-merged-prs-16], [17][dfinity-merged-prs-17], [18][dfinity-merged-prs-18]),
3 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2]),
8 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4], [5][dfinity-open_issues-5])

[dfinity-merged-prs-1]: https://github.com/dfinity/exchange-rate-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/nns-dapp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/stable-structures/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/internet-identity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-7]: https://github.com/dfinity/ICRC-1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-8]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-9]: https://github.com/dfinity/cycles-ledger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-10]: https://github.com/dfinity/ic-repl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-11]: https://github.com/dfinity/bitcoin-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-12]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-13]: https://github.com/dfinity/dfxvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-14]: https://github.com/dfinity/dre/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-15]: https://github.com/dfinity/response-verification/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-16]: https://github.com/dfinity/cycles-burner-canister/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-17]: https://github.com/dfinity/metrics-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-merged-prs-18]: https://github.com/dfinity/motoko.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/nns-dapp/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/nns-dapp/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/stable-structures/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-open_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dfinity-open_issues-5]: https://github.com/dfinity/response-verification/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [RUSTSEC-2023-0073: Infinite decoding loop through specially crafted payload](https://rustsec.org/advisories/RUSTSEC-2023-0073.html)
- [Internet Computer Zero to Dapp Educate Series Summary](https://medium.com/dfinity/internet-computer-zero-to-dapp-educate-series-summary-dfcc670607b8)
- [Async-Friendly Performance Counter](https://medium.com/dfinity/async-friendly-performance-counter-dcf928226c2b)
- [New WebAssembly Instrumentation](https://medium.com/dfinity/new-webassembly-instrumentation-2c93631e5718)

#### [Dusk Network](https://github.com/dusk-network)

84 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5], [6][dusk_network-merged-prs-6], [7][dusk_network-merged-prs-7], [8][dusk_network-merged-prs-8], [9][dusk_network-merged-prs-9], [10][dusk_network-merged-prs-10], [11][dusk_network-merged-prs-11], [12][dusk_network-merged-prs-12], [13][dusk_network-merged-prs-13]),
42 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4], [5][dusk_network-closed_issues-5], [6][dusk_network-closed_issues-6], [7][dusk_network-closed_issues-7], [8][dusk_network-closed_issues-8]),
20 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3], [4][dusk_network-open_issues-4])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/citadel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-4]: https://github.com/dusk-network/piecrust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-5]: https://github.com/dusk-network/Poseidon252/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-6]: https://github.com/dusk-network/schnorr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-7]: https://github.com/dusk-network/Hades252/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-8]: https://github.com/dusk-network/merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-9]: https://github.com/dusk-network/moat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-10]: https://github.com/dusk-network/phoenix-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-11]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-12]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-merged-prs-13]: https://github.com/dusk-network/bls12_381-sign/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/citadel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-4]: https://github.com/dusk-network/piecrust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-5]: https://github.com/dusk-network/schnorr/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-6]: https://github.com/dusk-network/moat/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-7]: https://github.com/dusk-network/phoenix-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-closed_issues-8]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/Poseidon252/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[dusk_network-open_issues-4]: https://github.com/dusk-network/bls12_381-sign/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Release Cycle #30](https://dusk.network/news/release-cycle-update-30)

#### [Espresso Systems](https://github.com/EspressoSystems)

144 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5], [6][espresso_systems-merged-prs-6], [7][espresso_systems-merged-prs-7]),
92 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4], [5][espresso_systems-closed_issues-5], [6][espresso_systems-closed_issues-6], [7][espresso_systems-closed_issues-7]),
47 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4], [5][espresso_systems-open_issues-5], [6][espresso_systems-open_issues-6], [7][espresso_systems-open_issues-7])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/espresso-polygon-zkevm-demo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/sequencer-example-l2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/espresso-sequencer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-6]: https://github.com/EspressoSystems/tide-disco/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-7]: https://github.com/EspressoSystems/hotshot-query-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/espresso-polygon-zkevm-demo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/sequencer-example-l2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-5]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-6]: https://github.com/EspressoSystems/tide-disco/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-7]: https://github.com/EspressoSystems/hotshot-query-service/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/espresso-polygon-zkevm-demo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/espresso/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-open_issues-5]: https://github.com/EspressoSystems/hotshot-prover-service/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-open_issues-6]: https://github.com/EspressoSystems/espresso-sequencer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[espresso_systems-open_issues-7]: https://github.com/EspressoSystems/hotshot-query-service/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Espresso Systems and Offchain Labs release R&D roadmap for Decentralized Timeboost](https://medium.com/@espressosys/espresso-systems-and-offchain-labs-release-r-d-roadmap-for-decentralized-timeboost-5d0007dff66d)

#### [Filecoin](https://github.com/filecoin-project)

54 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6]),
10 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3]),
9 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/rust-gpu-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/filplus-backend/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/filplus-backend/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/bls-signatures/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Filecoin Network Version 21 Watermelon Upgrade](https://status.filecoin.io/incidents/b3fhgjlqlbjh)

#### [Findora](https://github.com/FindoraNetwork)

2 merged PRs ([1][findora-merged-prs-1]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

169 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7], [8][fluence-merged-prs-8], [9][fluence-merged-prs-9], [10][fluence-merged-prs-10]),
0 closed issues,
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/nox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/marine-rs-sdk-test/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/fRPC-Substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-8]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-9]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fluence-merged-prs-10]: https://github.com/fluencelabs/decider/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

103 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12]),
91 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8], [9][fuel-closed_issues-9], [10][fuel-closed_issues-10], [11][fuel-closed_issues-11]),
113 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7])

[fuel-merged-prs-1]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/sway-applications/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/sway-standards/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-11]: https://github.com/FuelLabs/sway-libs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-merged-prs-12]: https://github.com/FuelLabs/fuel-block-committer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/sway-applications/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-9]: https://github.com/FuelLabs/sway-standards/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-10]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-closed_issues-11]: https://github.com/FuelLabs/fuel-debugger/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

26 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5], [6][golem-merged-prs-6], [7][golem-merged-prs-7]),
15 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]),
12 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-runtime-vm-nvidia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-runtime-ai/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-merged-prs-5]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-merged-prs-6]: https://github.com/golemfactory/erc20_payment_lib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-merged-prs-7]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-runtime-ai/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-runtime-ai/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Yagna Updates: Enhancing Network Stability and Introducing a New Payment Driver](https://blog.golemproject.net/yagna-v0-13-2-and-v0-14-0-enhancing-network-stability-and-introducing-a-new-payment-driver/)

#### [Grin](https://github.com/mimblewimble/grin)

1 merged PRs ([1][grin-merged-prs-1]),
0 closed issues,
0 open issues

[grin-merged-prs-1]: https://github.com/mimblewimble/mwixnet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

29 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4], [5][helium-merged-prs-5], [6][helium-merged-prs-6]),
4 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2], [3][helium-closed_issues-3]),
2 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2])

[helium-merged-prs-1]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/downlink-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/multibuy-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/oracles/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-merged-prs-5]: https://github.com/helium/proto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-merged-prs-6]: https://github.com/helium/helium-config-service-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/helium-ledger-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-closed_issues-2]: https://github.com/helium/downlink-service/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-closed_issues-3]: https://github.com/helium/oracles/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-open_issues-1]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[helium-open_issues-2]: https://github.com/helium/oracles/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

75 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4], [5][holochain-merged-prs-5], [6][holochain-merged-prs-6], [7][holochain-merged-prs-7], [8][holochain-merged-prs-8], [9][holochain-merged-prs-9]),
11 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
3 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/scaffolding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/tx5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-4]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-5]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-6]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-7]: https://github.com/holochain/hc-utils/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-8]: https://github.com/holochain/hc-zome-lib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-merged-prs-9]: https://github.com/holochain/holochain-serialization/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/tx5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/scaffolding/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [2023 Year in Review](https://blog.holochain.org/holochain-2023-year-in-review/)

#### [IOTA](https://github.com/iotaledger)

68 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3]),
30 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3]),
21 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3])

[iota-merged-prs-1]: https://github.com/iotaledger/iota-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/sd-jwt-payload/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/sd-jwt-payload/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-closed_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/iota-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/inx-chronicle/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [IOTA 2.0: All You Need to Know](https://blog.iota.org/iota-2-0-all-you-need-to-know/)

#### [Maidsafe](https://github.com/maidsafe)

84 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4], [5][maidsafe-merged-prs-5], [6][maidsafe-merged-prs-6]),
3 closed issues ([1][maidsafe-closed_issues-1]),
10 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/sn-node-manager/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/self_encryption/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/sn-releases/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[maidsafe-merged-prs-5]: https://github.com/maidsafe/sn-testnet-deploy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[maidsafe-merged-prs-6]: https://github.com/maidsafe/safeup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

19 merged PRs ([1][mina-merged-prs-1]),
1 closed issues ([1][mina-closed_issues-1]),
9 open issues ([1][mina-open_issues-1])

[mina-merged-prs-1]: https://github.com/openmina/openmina/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[mina-closed_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Exploring Three Grant Programs for Mina Developers](https://minaprotocol.com/blog/mina-developers-grants)
- [Testworld Mission 2.0 Protocol Performance Testing – Program Extension Details](https://minaprotocol.com/blog/testworld-mission-2-0-program-extension-details)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

39 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2], [3][mobilecoin-merged-prs-3]),
4 closed issues ([1][mobilecoin-closed_issues-1], [2][mobilecoin-closed_issues-2]),
0 open issues

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/sgx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[mobilecoin-merged-prs-3]: https://github.com/mobilecoinfoundation/attestation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[mobilecoin-closed_issues-2]: https://github.com/mobilecoinfoundation/sgx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

39 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3], [4][multiversx-merged-prs-4], [5][multiversx-merged-prs-5], [6][multiversx-merged-prs-6], [7][multiversx-merged-prs-7], [8][multiversx-merged-prs-8], [9][multiversx-merged-prs-9]),
2 closed issues ([1][multiversx-closed_issues-1], [2][multiversx-closed_issues-2]),
1 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-subscription-fee-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-4]: https://github.com/multiversx/mx-delegation-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-5]: https://github.com/multiversx/mx-bridge-eth-sc-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-6]: https://github.com/multiversx/mx-contracts-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-7]: https://github.com/multiversx/mx-exchange-tools-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-8]: https://github.com/multiversx/mx-reproducible-contract-build-example-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-merged-prs-9]: https://github.com/multiversx/mx-metabonding-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-closed_issues-2]: https://github.com/multiversx/mx-contracts-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

146 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10], [11][near-merged-prs-11]),
47 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8], [9][near-closed_issues-9], [10][near-closed_issues-10], [11][near-closed_issues-11], [12][near-closed_issues-12]),
39 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8], [9][near-open_issues-9], [10][near-open_issues-10])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/read-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/near-account-id-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-9]: https://github.com/near/near-hat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-10]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-merged-prs-11]: https://github.com/near/mpc-recovery/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-7]: https://github.com/near/near-account-id-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-8]: https://github.com/near/near-workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-9]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-10]: https://github.com/near/mpc-recovery/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-11]: https://github.com/near/bos-loader/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-closed_issues-12]: https://github.com/near/near-microindexers/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/read-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/rollup-data-availability/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-7]: https://github.com/near/near-account-id-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-8]: https://github.com/near/near-hat/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-9]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[near-open_issues-10]: https://github.com/near/bos-loader/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [2023: NEAR In Review](https://pages.near.org/blog/2023-near-in-review/)

#### [Nervos](https://github.com/nervosnetwork)

46 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8], [9][nervos-merged-prs-9]),
22 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
16 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4], [5][nervos-open_issues-5], [6][nervos-open_issues-6])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/faster-hex/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-auth-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/nervosnetwork/ckb-light-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-7]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-8]: https://github.com/nervosnetwork/ckb-sdk-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-merged-prs-9]: https://github.com/nervosnetwork/ckb-standalone-debugger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-light-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/nervosnetwork/ckb-sdk-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/faster-hex/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-open_issues-4]: https://github.com/nervosnetwork/ckb-light-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-open_issues-5]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nervos-open_issues-6]: https://github.com/nervosnetwork/force-bridge-eth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

6 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]),
1 closed issues ([1][oasis-closed_issues-1]),
1 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[oasis-merged-prs-2]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Year in Review: The Oasis Network in 2023](https://oasisprotocol.org/blog/2023-review-yearly-highlights)
- [Oasis November 2023 Engineering Update](https://oasisprotocol.org/blog/november-2023-engineering-update)
- [The Eden Upgrade: A Technical Debrief from Oasis Engineering](https://oasisprotocol.org/blog/eden-upgrade-technical-debrief-engineering)

#### [Parity](https://github.com/paritytech)

288 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15], [16][parity-merged-prs-16], [17][parity-merged-prs-17], [18][parity-merged-prs-18], [19][parity-merged-prs-19], [20][parity-merged-prs-20], [21][parity-merged-prs-21], [22][parity-merged-prs-22], [23][parity-merged-prs-23]),
100 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13]),
80 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14], [15][parity-open_issues-15], [16][parity-open_issues-16], [17][parity-open_issues-17], [18][parity-open_issues-18], [19][parity-open_issues-19], [20][parity-open_issues-20])

[parity-merged-prs-1]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/parity-scale-codec/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/polkadot-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/arkworks-extensions/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/verifiable/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/try-runtime-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-15]: https://github.com/paritytech/reed-solomon-novelpoly/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-16]: https://github.com/paritytech/trappist/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-17]: https://github.com/paritytech/prdoc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-18]: https://github.com/paritytech/polkadot-introspector/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-19]: https://github.com/paritytech/scale-typegen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-20]: https://github.com/paritytech/polkadot-staking-miner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-21]: https://github.com/paritytech/substrate-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-22]: https://github.com/paritytech/ss58-registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-merged-prs-23]: https://github.com/paritytech/banana-recovery-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/trappist/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/subport/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/polkadot-staking-miner/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/polkadot-sdk-docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-closed_issues-13]: https://github.com/paritytech/parity-publish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/substrate-telemetry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/reed-solomon-novelpoly/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-13]: https://github.com/paritytech/trappist/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-14]: https://github.com/paritytech/prdoc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-15]: https://github.com/paritytech/subport/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-16]: https://github.com/paritytech/polkadot-introspector/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-17]: https://github.com/paritytech/polkadot-staking-miner/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-18]: https://github.com/paritytech/polkadot-sdk-docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-19]: https://github.com/paritytech/zombienet-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[parity-open_issues-20]: https://github.com/paritytech/parity-publish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Polkadot 2023 Roundup](https://medium.com/polkadot-network/polkadot-2023-roundup-7fe77d88f022)

#### [Radix](https://github.com/radixdlt)

32 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3], [4][radix-merged-prs-4]),
0 closed issues,
1 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/radix-engine-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/official-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[radix-merged-prs-4]: https://github.com/radixdlt/babylon-ledger-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radix-engine-toolkit/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Radix Engine Code Audit](https://www.radixdlt.com/blog/radix-engine-code-audit)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

1 merged PRs ([1][secret_network-merged-prs-1]),
0 closed issues,
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

249 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
66 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
25 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Basic Solana Data Analytics In One Hour (Youtube)](https://read.cryptodatabytes.com/p/basic-solana-data-analytics-in-one)

#### [Soroban](https://github.com/stellar)

61 merged PRs ([1][soroban-merged-prs-1], [2][soroban-merged-prs-2], [3][soroban-merged-prs-3], [4][soroban-merged-prs-4], [5][soroban-merged-prs-5], [6][soroban-merged-prs-6]),
24 closed issues ([1][soroban-closed_issues-1], [2][soroban-closed_issues-2], [3][soroban-closed_issues-3]),
9 open issues ([1][soroban-open_issues-1], [2][soroban-open_issues-2], [3][soroban-open_issues-3], [4][soroban-open_issues-4])

[soroban-merged-prs-1]: https://github.com/stellar/rs-soroban-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-merged-prs-2]: https://github.com/stellar/rs-soroban-env/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-merged-prs-3]: https://github.com/stellar/soroban-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-merged-prs-4]: https://github.com/stellar/escape-bytes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-merged-prs-5]: https://github.com/stellar/xdrgen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-merged-prs-6]: https://github.com/stellar/rs-stellar-xdr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-closed_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-closed_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-closed_issues-3]: https://github.com/stellar/xdrgen/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-open_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-open_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-open_issues-3]: https://github.com/stellar/escape-bytes/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[soroban-open_issues-4]: https://github.com/stellar/xdrgen/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [The Stellar Network’s Phased Rollout of Smart Contracts](https://stellar.org/blog/developers/the-stellar-network-s-phased-rollout-of-smart-contracts-the-road-to-mainnet)

#### [Spacemesh](https://github.com/spacemeshos)

4 merged PRs ([1][spacemesh-merged-prs-1]),
0 closed issues,
3 open issues ([1][spacemesh-open_issues-1])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/post-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[spacemesh-open_issues-1]: https://github.com/spacemeshos/post-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

73 merged PRs ([1][subspace_network-merged-prs-1], [2][subspace_network-merged-prs-2], [3][subspace_network-merged-prs-3]),
33 closed issues ([1][subspace_network-closed_issues-1]),
17 open issues ([1][subspace_network-open_issues-1])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[subspace_network-merged-prs-2]: https://github.com/subspace/pulsar/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[subspace_network-merged-prs-3]: https://github.com/subspace/subspace-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Gemini 3 Phase 3 Incentivized Testnet](https://blog.subspace.network/gemini-3-phase-3-incentivized-testnet-29ec85da299d)
- [Subspace Ecosystem: A Guide for Domain Operators and Developers](https://blog.subspace.network/subspace-ecosystem-a-guide-for-domain-operators-and-developers-af50dd59e51f)

#### [Sui](https://github.com/MystenLabs)

321 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2], [3][sui-merged-prs-3]),
169 closed issues ([1][sui-closed_issues-1]),
2 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[sui-merged-prs-2]: https://github.com/MystenLabs/mysticeti/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[sui-merged-prs-3]: https://github.com/MystenLabs/fastcrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Sui Hits Major Growth Milestones in 2023](https://blog.sui.io/2023-growth-milestones/)
- [How Settlement Time and Composability Help DeFi Flourish on Sui](https://blog.sui.io/settlement-time-and-composability-help-defi-flourish-on-sui/)

#### [Zcash](https://github.com/zcash)

35 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5], [6][zcash-merged-prs-6], [7][zcash-merged-prs-7], [8][zcash-merged-prs-8]),
18 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4], [5][zcash-closed_issues-5]),
11 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4], [5][zcash-open_issues-5])

[zcash-merged-prs-1]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/sapling-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/zcash_spec/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-merged-prs-6]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-merged-prs-7]: https://github.com/zcash/zip32/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-merged-prs-8]: https://github.com/zcash/zcash-test-vectors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/sapling-crypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-closed_issues-5]: https://github.com/zcash/zip32/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/sapling-crypto/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zcash-open_issues-5]: https://github.com/zcash/zcash_spec/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [A look back: NU5 and network sandblasting](https://electriccoin.co/blog/a-look-back-nu5-and-network-sandblasting/)
- [ECC Transparency Report for Q2 2023](https://electriccoin.co/blog/ecc-transparency-report-for-q2-2023/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

1 merged PRs ([1][aluvm-merged-prs-1]),
0 closed issues,
0 open issues

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

27 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4], [5][bdk-merged-prs-5], [6][bdk-merged-prs-6]),
7 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2]),
13 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4], [5][bdk-open_issues-5], [6][bdk-open_issues-6])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-esplora-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-merged-prs-5]: https://github.com/bitcoindevkit/coin-select/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-merged-prs-6]: https://github.com/bitcoindevkit/bdk-reserves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-esplora-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-open_issues-5]: https://github.com/bitcoindevkit/coin-select/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bdk-open_issues-6]: https://github.com/bitcoindevkit/bdk-reserves/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Bitcoin Protocol](https://github.com/BP-WG)

12 merged PRs ([1][bitcoin_protocol-merged-prs-1], [2][bitcoin_protocol-merged-prs-2], [3][bitcoin_protocol-merged-prs-3]),
1 closed issues ([1][bitcoin_protocol-closed_issues-1]),
5 open issues ([1][bitcoin_protocol-open_issues-1], [2][bitcoin_protocol-open_issues-2], [3][bitcoin_protocol-open_issues-3], [4][bitcoin_protocol-open_issues-4])

[bitcoin_protocol-merged-prs-1]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitcoin_protocol-merged-prs-2]: https://github.com/BP-WG/bp-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitcoin_protocol-merged-prs-3]: https://github.com/BP-WG/bp-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitcoin_protocol-closed_issues-1]: https://github.com/BP-WG/bp-std/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitcoin_protocol-open_issues-1]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitcoin_protocol-open_issues-2]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitcoin_protocol-open_issues-3]: https://github.com/BP-WG/bp-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitcoin_protocol-open_issues-4]: https://github.com/BP-WG/bp-std/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

11 merged PRs ([1][bitmask-merged-prs-1]),
6 closed issues ([1][bitmask-closed_issues-1]),
2 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Bitswap](https://github.com/BitSwap-BiFi)

5 merged PRs ([1][bitswap-merged-prs-1]),
4 closed issues ([1][bitswap-closed_issues-1]),
18 open issues ([1][bitswap-open_issues-1])

[bitswap-merged-prs-1]: https://github.com/BitSwap-BiFi/Bitswap-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitswap-closed_issues-1]: https://github.com/BitSwap-BiFi/Bitswap-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[bitswap-open_issues-1]: https://github.com/BitSwap-BiFi/Bitswap-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [CivKit](https://github.com/civkit)

13 merged PRs ([1][civkit-merged-prs-1], [2][civkit-merged-prs-2]),
2 closed issues ([1][civkit-closed_issues-1]),
0 open issues

[civkit-merged-prs-1]: https://github.com/civkit/civkit-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[civkit-merged-prs-2]: https://github.com/civkit/staking-credentials/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[civkit-closed_issues-1]: https://github.com/civkit/civkit-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

9 merged PRs ([1][electrs-merged-prs-1]),
5 closed issues ([1][electrs-closed_issues-1]),
6 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

98 merged PRs ([1][fedimint-merged-prs-1]),
48 closed issues ([1][fedimint-closed_issues-1]),
49 open issues ([1][fedimint-open_issues-1], [2][fedimint-open_issues-2])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[fedimint-open_issues-2]: https://github.com/fedimint/fedimint-custom-modules-example/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

54 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3], [4][ldk-merged-prs-4]),
23 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2], [3][ldk-closed_issues-3], [4][ldk-closed_issues-4]),
18 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2], [3][ldk-open_issues-3], [4][ldk-open_issues-4])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/lightning-liquidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/vss-rust-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-merged-prs-4]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/lightning-liquidity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-closed_issues-3]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-closed_issues-4]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/lightning-liquidity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-open_issues-3]: https://github.com/lightningdevkit/ldk-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ldk-open_issues-4]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

2 merged PRs ([1][lnp/bp-merged-prs-1]),
0 closed issues,
0 open issues

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [LNP WG](https://github.com/LNP-WG)

1 merged PRs ([1][lnp_wg-merged-prs-1]),
1 closed issues ([1][lnp_wg-closed_issues-1]),
0 open issues

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lnp_wg-closed_issues-1]: https://github.com/LNP-WG/lnp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

2 merged PRs ([1][nomic-merged-prs-1]),
0 closed issues,
1 open issues ([1][nomic-open_issues-1])

[nomic-merged-prs-1]: https://github.com/turbofish-org/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[nomic-open_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

15 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2], [3][rgb-merged-prs-3], [4][rgb-merged-prs-4]),
25 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2], [3][rgb-closed_issues-3], [4][rgb-closed_issues-4]),
8 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2], [3][rgb-open_issues-3], [4][rgb-open_issues-4])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-merged-prs-3]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-merged-prs-4]: https://github.com/RGB-WG/rgb-schemata/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rgb-std/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-closed_issues-3]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-closed_issues-4]: https://github.com/RGB-WG/rgb-schemata/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-open_issues-2]: https://github.com/RGB-WG/rgb-std/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-open_issues-3]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rgb-open_issues-4]: https://github.com/RGB-WG/rgb-schemata/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

50 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
19 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]),
23 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-bech32/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-ordered/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/hex-conservative/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-ordered/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/hex-conservative/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/hex-conservative/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Rust Payjoin](https://github.com/payjoin/rust-payjoin)

14 merged PRs ([1][rust_payjoin-merged-prs-1]),
6 closed issues ([1][rust_payjoin-closed_issues-1]),
13 open issues ([1][rust_payjoin-open_issues-1])

[rust_payjoin-merged-prs-1]: https://github.com/payjoin/rust-payjoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_payjoin-closed_issues-1]: https://github.com/payjoin/rust-payjoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_payjoin-open_issues-1]: https://github.com/payjoin/rust-payjoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

5 merged PRs ([1][rust_simplicity-merged-prs-1]),
1 closed issues ([1][rust_simplicity-closed_issues-1]),
1 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_simplicity-closed_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Strict Types](https://github.com/strict-types)

1 merged PRs ([1][strict_types-merged-prs-1]),
0 closed issues,
0 open issues

[strict_types-merged-prs-1]: https://github.com/strict-types/strict-encoding/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

2 merged PRs ([1][ethers-rs-merged-prs-1]),
2 closed issues ([1][ethers-rs-closed_issues-1]),
1 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

185 merged PRs ([1][foundry-merged-prs-1], [2][foundry-merged-prs-2], [3][foundry-merged-prs-3], [4][foundry-merged-prs-4]),
185 closed issues ([1][foundry-closed_issues-1], [2][foundry-closed_issues-2]),
115 open issues ([1][foundry-open_issues-1], [2][foundry-open_issues-2], [3][foundry-open_issues-3], [4][foundry-open_issues-4])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-merged-prs-2]: https://github.com/foundry-rs/starknet-foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-merged-prs-3]: https://github.com/foundry-rs/compilers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-merged-prs-4]: https://github.com/foundry-rs/block-explorers/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-closed_issues-2]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-open_issues-2]: https://github.com/foundry-rs/starknet-foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-open_issues-3]: https://github.com/foundry-rs/compilers/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[foundry-open_issues-4]: https://github.com/foundry-rs/block-explorers/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

46 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2], [3][lighthouse-merged-prs-3], [4][lighthouse-merged-prs-4], [5][lighthouse-merged-prs-5]),
22 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]),
13 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lighthouse-merged-prs-3]: https://github.com/sigp/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lighthouse-merged-prs-4]: https://github.com/sigp/tree_hash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lighthouse-merged-prs-5]: https://github.com/sigp/ssz_types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Polygon Zero](https://github.com/0xPolygonZero)

53 merged PRs ([1][polygon_zero-merged-prs-1], [2][polygon_zero-merged-prs-2], [3][polygon_zero-merged-prs-3], [4][polygon_zero-merged-prs-4], [5][polygon_zero-merged-prs-5], [6][polygon_zero-merged-prs-6]),
7 closed issues ([1][polygon_zero-closed_issues-1], [2][polygon_zero-closed_issues-2], [3][polygon_zero-closed_issues-3], [4][polygon_zero-closed_issues-4]),
4 open issues ([1][polygon_zero-open_issues-1], [2][polygon_zero-open_issues-2])

[polygon_zero-merged-prs-1]: https://github.com/0xPolygonZero/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-merged-prs-2]: https://github.com/0xPolygonZero/zero-bin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-merged-prs-3]: https://github.com/0xPolygonZero/proof-protocol-decoder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-merged-prs-4]: https://github.com/0xPolygonZero/plonky-block-proof-gen/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-merged-prs-5]: https://github.com/0xPolygonZero/paladin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-merged-prs-6]: https://github.com/0xPolygonZero/evm-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-closed_issues-1]: https://github.com/0xPolygonZero/plonky2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-closed_issues-2]: https://github.com/0xPolygonZero/zero-bin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-closed_issues-3]: https://github.com/0xPolygonZero/proof-protocol-decoder/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-closed_issues-4]: https://github.com/0xPolygonZero/evm-tests/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-open_issues-1]: https://github.com/0xPolygonZero/zero-bin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[polygon_zero-open_issues-2]: https://github.com/0xPolygonZero/proof-protocol-decoder/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

177 merged PRs ([1][reth-merged-prs-1]),
81 closed issues ([1][reth-closed_issues-1]),
48 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Rust Ethereum](https://github.com/rust-ethereum)

12 merged PRs ([1][rust_ethereum-merged-prs-1]),
1 closed issues ([1][rust_ethereum-closed_issues-1]),
4 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/evm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/evm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

1 merged PRs ([1][rust_web3-merged-prs-1]),
0 closed issues,
0 open issues

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

311 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3], [4][starkware-merged-prs-4]),
8 closed issues ([1][starkware-closed_issues-1]),
9 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/blockifier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[starkware-merged-prs-4]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [From Milestones to Masterstrokes: StarkWare’s Year in Review](https://medium.com/starkware/from-milestones-to-masterstrokes-starkwares-year-in-review-84d890620730)
- [Starknet Launches the ‘Devonomics’ Pilot Program](https://medium.com/starkware/starknet-launches-the-devonomics-pilot-program-22b6b0ed8d5c)

#### [zkSync Era](https://github.com/matter-labs/zksync-era)

250 merged PRs ([1][zksync_era-merged-prs-1], [2][zksync_era-merged-prs-2], [3][zksync_era-merged-prs-3], [4][zksync_era-merged-prs-4], [5][zksync_era-merged-prs-5], [6][zksync_era-merged-prs-6], [7][zksync_era-merged-prs-7], [8][zksync_era-merged-prs-8], [9][zksync_era-merged-prs-9], [10][zksync_era-merged-prs-10], [11][zksync_era-merged-prs-11], [12][zksync_era-merged-prs-12], [13][zksync_era-merged-prs-13], [14][zksync_era-merged-prs-14], [15][zksync_era-merged-prs-15], [16][zksync_era-merged-prs-16]),
6 closed issues ([1][zksync_era-closed_issues-1], [2][zksync_era-closed_issues-2], [3][zksync_era-closed_issues-3]),
15 open issues ([1][zksync_era-open_issues-1], [2][zksync_era-open_issues-2], [3][zksync_era-open_issues-3], [4][zksync_era-open_issues-4], [5][zksync_era-open_issues-5])

[zksync_era-merged-prs-1]: https://github.com/matter-labs/zksync-era/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-2]: https://github.com/matter-labs/foundry-zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-3]: https://github.com/matter-labs/era-boojum-validator-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-4]: https://github.com/matter-labs/era-consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-5]: https://github.com/matter-labs/zksync-withdrawal-finalizer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-6]: https://github.com/matter-labs/era-boojum/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-7]: https://github.com/matter-labs/franklin-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-8]: https://github.com/matter-labs/era-test-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-9]: https://github.com/matter-labs/era-shivini/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-10]: https://github.com/matter-labs/era-revm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-11]: https://github.com/matter-labs/era-zk_evm_abstractions/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-12]: https://github.com/matter-labs/era-zkevm_test_harness/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-13]: https://github.com/matter-labs/era-boojum-cuda/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-14]: https://github.com/matter-labs/era-compiler-tester/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-15]: https://github.com/matter-labs/era-cuda/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-merged-prs-16]: https://github.com/matter-labs/vise/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-closed_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-closed_issues-2]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-closed_issues-3]: https://github.com/matter-labs/era-boojum-cuda/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-open_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-open_issues-2]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-open_issues-3]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-open_issues-4]: https://github.com/matter-labs/era-boojum-validator-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot
[zksync_era-open_issues-5]: https://github.com/matter-labs/era-test-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-12-01..2023-12-31%20-author:app/dependabot

- [Click and Deploy Your Hyperchain! First Cohort of RaaS Providers Live on ZK Stack](https://zksync.mirror.xyz/IqNxihCfIMgtSPTy9orQ-EQWd-qI97fZbWT8moqHV3w)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

Jan 1-Feb 4 | Hong Kong | [The Polkadot Blockchain Academy](https://polkadot.network/development/blockchain-academy/)

Feb 2–21, 2024 | Online | [Ethereum Async hackathon: Circuit Breaker](https://ethglobal.com/events/circuitbreaker)

Feb 23-Mar 3, 2024 | Denver, US | [ETHDenver](https://www.ethdenver.com/)

Mar 15-17, 2024 | London, UK | [ETHGlobal London](https://ethglobal.com/events/london2024)

Mar 25–27, 2024 | Toronto, Canada | [RWC 2024](https://rwc.iacr.org/2024/)

Mar 26-28 | London, UK | [Rust Nation](https://www.rustnationuk.com/)

Apr 5-26, 2024 | Online | [Ethereum Async hackathon: Scaling Ethereum 2024](https://ethglobal.com/events/scaling2024)

Apr 8-12, 2024 | Paris, France | [Paris Blockchain Week](https://www.parisblockchainweek.com/)

Apr 22-25, 2024 | Athens, Greece | [EuroSys 2024](https://2024.eurosys.org/about.html)

May 3-5, 2024 | Sydney, Australia | [ETHGlobal Sydney](https://ethglobal.com/events/sydney)

May 18-19, 2024 | Brisbane, Australia | [AI + Web3 Convention](https://web3convention.com/)

May 20-Jun 20 | Singapore | [The Polkadot Blockchain Academy](https://polkadot.network/development/blockchain-academy/)

May 21-23 2024 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

May 24-26, 2024 | Berlin, Germany | [ETHBerlin](https://ethberlin.org/)

May 29-31, 2024 | Austin, US | [Consensus](https://consensus2024.coindesk.com/)

June 5-6, 2024 | Santa Clara, US | [Blockchain Expo North America](https://blockchain-expo.com/northamerica/)

Jul 4-7, 2024 | Istanbul, Turkey | [Blockchain Expo World](https://blockchainexpoworld.com/)

Jul 12–14, 2024 | Brussels, Belgium | [ETHGlobal Brussels](https://ethglobal.com/events/brussels)

Aug 18-22, 2024 | Santa Barbara, US | [Crypto 2024](https://crypto.iacr.org/2024/)

Aug 28-29, 2024 | Tokyo, Japan | [WebX 2024](https://webx-asia.com/)

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


