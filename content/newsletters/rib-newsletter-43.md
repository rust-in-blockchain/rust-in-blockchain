---
title: "RiB Newsletter #43"
description: "December 2022"
date: 2023-01-04
categories:
  - "newsletters"
summary: "Welcome to the #43 edition of Rust in Blockchain,
This month we spotlight `anemo`, the p2p networking library used by Sui, running over QUIC."
---

Welcome to the #43 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #42](/newsletters/rib-newsletter-42/).

&nbsp;

## Thanks

Thanks to contributors:
[Erwan],
[Hunter Beast],
[Brian Anderson], and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Erwan]: https://github.com/erwanor
[Hunter Beast]: https://github.com/cryptoquick
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[anemo](https://github.com/mystenlabs/anemo).

This is the p2p networking library used by Sui,
running over QUIC.
It looks to be much simpler than [rust-libp2p](https://github.com/libp2p/rust-libp2p),
though presumably less powerful.

&nbsp;

## Interesting Things

#### Blog Posts

- [Accelerating zk-SNARKs - MSM and NTT algorithms on FPGAs with Hardcaml](https://blog.janestreet.com/zero-knowledge-fpgas-hardcaml/)
- [Solutions to Delay Attacks on Rollups](https://offchain.medium.com/solutions-to-delay-attacks-on-rollups-434f9d05a07a)
- [ZK Email](https://blog.aayushg.com/posts/zkemail/)
- [What are zk-SNARKs?](https://halborn.com/what-are-zk-snarks/)
- [An audited implementation of Poseidon377, a SNARK-friendly hash function used in Penumbra (private DEX)](https://twitter.com/penumbrazone/status/1599891715770425370)
- [Accelerating Penumbra's Merkle Tree by up to 4,000,000x](https://penumbra.zone/blog/tiered-commitment-tree/)

#### Papers

- [SuperNova: Proving universal machine executions without universal circuits](https://eprint.iacr.org/2022/1758)
- [SoK: Decentralized Finance (DeFi) Attacks](https://eprint.iacr.org/2022/1773)
- [Glimpse: On-Demand, Cross-Chain Communication for Efficient DeFi Applications on Bitcoin-based Blockchains](https://eprint.iacr.org/2022/1721)
- [Dory: Asynchronous BFT with Reduced Communication and Improved Efficiency](https://eprint.iacr.org/2022/1709)
- [Asymptotically Optimal Message Dissemination with Applications to Blockchains](https://eprint.iacr.org/2022/1723)

#### Projects

- [zkOS](https://github.com/starkoracles/zkos).
  A new cross-proof-system execution layer.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

<!-- https://github.com/rustsec/advisory-db/pulls -->
<!-- https://osv.dev/list?page=2&ecosystem=crates.io -->

- [RUSTSEC-2022-0071: `rusoto_credential` is unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0071.html).
- [RUSTSEC-2022-0072: Vulnerability in `hyper-staticfile`](https://rustsec.org/advisories/RUSTSEC-2022-0072.html).
- [RUSTSEC-2022-0073: `alloc-cortex-m` is unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0073.html).
- [RUSTSEC-2022-0074: Unsoundness in prettytable-rs](https://rustsec.org/advisories/RUSTSEC-2022-0074.html).
- [GHSA-8r76-fr72-j32w: Creator Verification Error when Bubblegum Activate](https://github.com/advisories/GHSA-8r76-fr72-j32w).
- [GHSA-9v25-r5q2-2p6w: Candy Machine Set Collection During Mint Missing Check](https://github.com/advisories/GHSA-9v25-r5q2-2p6w).
- [CVE-2022-23523: linux-loader reading beyond EOF could lead to infinite loop](https://github.com/advisories/GHSA-52h2-m2cf-9jh6).
- **[CVE-2022-23507: Tendermint light client verification not taking into account chain ID](https://github.com/advisories/GHSA-xqqc-c5gw-c5r5).**
- [CVE-2022-46171: Tauri Filesystem Scope Glob Pattern is too Permissive](https://github.com/advisories/GHSA-6mv3-wm7j-h4w5).


&nbsp;

## Most Active in December

[Parity](https://github.com/paritytech):
363 merged PRs,
146 closed issues,
124 open issues

[Sui](https://github.com/MystenLabs):
359 merged PRs,
63 closed issues,
62 open issues

[Solana](https://github.com/solana-labs/solana):
325 merged PRs,
127 closed issues,
36 open issues

[Fuel](https://github.com/FuelLabs):
226 merged PRs,
147 closed issues,
122 open issues

[Filecoin](https://github.com/filecoin-project):
193 merged PRs,
134 closed issues,
114 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

33 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
44 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]),
24 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-closed_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Anoma](https://github.com/anoma)

74 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
12 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2]),
15 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

181 merged PRs ([1][aptos-merged-prs-1]),
114 closed issues ([1][aptos-closed_issues-1]),
39 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [Securing Move](https://medium.com/aptoslabs/securing-move-f81099f5e08c)
- [The Path to 10x Lower Gas Fees on Aptos with Community-Driven Feedback](https://medium.com/aptoslabs/the-path-to-10x-lower-gas-fees-on-aptos-with-community-driven-feedback-7cca875a513f)

#### [Casper](https://github.com/casper-network)

78 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
56 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
29 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

6 merged PRs ([1][comit-merged-prs-1]),
1 closed issues ([1][comit-closed_issues-1]),
0 open issues

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

29 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5]),
22 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]),
10 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

15 merged PRs ([1][conflux-merged-prs-1]),
2 closed issues ([1][conflux-closed_issues-1]),
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

1 merged PRs ([1][darkfi-merged-prs-1]),
5 closed issues ([1][darkfi-closed_issues-1]),
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

55 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
6 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5]),
6 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-closed_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-closed_issues-5]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Dusk Network](https://github.com/dusk-network)

6 merged PRs ([1][dusk_network-merged-prs-1]),
19 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2]),
8 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3], [4][dusk_network-open_issues-4])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[dusk_network-open_issues-4]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Elrond](https://github.com/ElrondNetwork)

113 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3]),
3 closed issues ([1][elrond-closed_issues-1]),
1 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-metabonding-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[elrond-open_issues-1]: https://github.com/ElrondNetwork/sc-dex-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

42 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5], [6][espresso_systems-merged-prs-6], [7][espresso_systems-merged-prs-7]),
36 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4]),
11 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/cap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/espresso/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-6]: https://github.com/EspressoSystems/espresso-systems-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-merged-prs-7]: https://github.com/EspressoSystems/atomicstore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/espresso-systems-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/espresso/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

193 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7]),
134 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5], [6][filecoin-closed_issues-6]),
114 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4], [5][filecoin-open_issues-5], [6][filecoin-open_issues-6], [7][filecoin-open_issues-7])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/filecoin-project/rust-filecoin-proofs-api/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-closed_issues-6]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/filecoin-project/rust-filecoin-proofs-api/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-open_issues-5]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-open_issues-6]: https://github.com/filecoin-project/rust-gpu-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[filecoin-open_issues-7]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [Hacking the Filecoin Ethereum Virtual Machine (FEVM)](https://filecoin.io/blog/posts/hacking-the-filecoin-ethereum-virtual-machine-fevm/)
- [Business Models on the FVM](https://medium.com/tldrfilecoin/business-models-on-the-fvm-23cd71fdd3f1)

#### [Findora](https://github.com/FindoraNetwork)

34 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4], [5][findora-merged-prs-5]),
0 closed issues,
1 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/bulletproofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[findora-merged-prs-4]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[findora-merged-prs-5]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

62 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5]),
3 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2]),
1 open issues ([1][fluence-open_issues-1])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fluence-closed_issues-2]: https://github.com/fluencelabs/rust-peer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fluence-open_issues-1]: https://github.com/fluencelabs/registry/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

226 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9]),
147 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
122 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8], [9][fuel-open_issues-9])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fuel-open_issues-9]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

15 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3]),
19 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3], [4][golem-closed_issues-4]),
26 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-service-bus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-closed_issues-4]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-service-bus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[golem-open_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Grin](https://github.com/mimblewimble/grin)

1 merged PRs ([1][grin-merged-prs-1]),
1 closed issues ([1][grin-closed_issues-1]),
0 open issues

[grin-merged-prs-1]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[grin-closed_issues-1]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

13 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]),
4 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2], [3][helium-closed_issues-3]),
0 open issues

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/virtual-lorawan-device/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[helium-closed_issues-2]: https://github.com/helium/helium-crypto-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[helium-closed_issues-3]: https://github.com/helium/virtual-lorawan-device/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

38 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]),
6 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
4 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [Dependencies In Progress For Beta-RC](https://blog.holochain.org/dependencies-in-progress-for-beta-rc/)

#### [IOTA](https://github.com/iotaledger)

68 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3]),
35 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3]),
25 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3])

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-closed_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

124 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4]),
6 closed issues ([1][maidsafe-closed_issues-1]),
7 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/sn_consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

0 merged PRs,
0 closed issues,
0 open issues

- [Solving for Blockchain’s Critical Security Flaw](https://minaprotocol.com/blog/solving-for-blockchains-security-flaw)
- [How to Design a Compliant, Privacy-Preserving Fiat Stablecoin via Zero-Knowledge Proofs](https://www.etonec.com/post/how-to-design-a-compliant-privacy-preserving-fiat-stablecoin-via-zero-knowledge-proofs)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

24 merged PRs ([1][mobilecoin-merged-prs-1]),
14 closed issues ([1][mobilecoin-closed_issues-1]),
16 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

102 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9]),
29 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6]),
58 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-merged-prs-9]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [NEAR 2022: A Year in Review](https://near.org/blog/near-2022-a-year-in-review/)

#### [Nervos](https://github.com/nervosnetwork)

63 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]),
3 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]),
6 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [Nervos, Beyond Account Abstraction](https://www.nervos.org/blog/nervos-beyond-account-abstraction)

#### [Oasis](https://github.com/oasisprotocol)

11 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]),
0 closed issues,
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[oasis-merged-prs-2]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

363 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12]),
146 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11]),
124 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [Polkadot 2022 Roundup](https://medium.com/polkadot-network/polkadot-2022-roundup-d98ccf69df50)

#### [Radix](https://github.com/radixdlt)

65 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2]),
4 closed issues ([1][radix-closed_issues-1]),
1 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

15 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]),
1 closed issues ([1][secret_network-closed_issues-1]),
1 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

325 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
127 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
36 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [Looking forward: What the Solana community will tackle in 2023 and beyond](https://solana.com/news/looking-forward-what-the-solana-community-will-tackle-in-2023-and-beyond)
- [Solana Network Upgrades](https://solana.com/news/solana-network-upgrades)
- [Neon EVM’s Mainnet Launch: Community Update](https://medium.com/neon-labs/neon-evms-mainnet-launch-community-update-eeef3aea02a2)
- [Detailed Post-Mortem and Next Steps](https://raydium.medium.com/detailed-post-mortem-and-next-steps-d6d6dd461c3e)
- [Solana rBPF Vulnerability Case Study](https://blog.audit.haechi.io/solana_rbpf_vulnerability_casestudy)

#### [Subspace Labs](https://github.com/subspace)

52 merged PRs ([1][subspace_labs-merged-prs-1]),
14 closed issues ([1][subspace_labs-closed_issues-1]),
13 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

359 merged PRs ([1][sui-merged-prs-1]),
63 closed issues ([1][sui-closed_issues-1]),
62 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [Cryptography in Sui: Cross-chain Signature Verification](https://tech.mystenlabs.com/cryptography-in-sui-cross-chain-signature-verification/)

#### [Zcash](https://github.com/zcash)

55 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5], [6][zcash-merged-prs-6]),
36 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]),
39 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-merged-prs-6]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/incrementalmerkletree/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[zcash-open_issues-4]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

- [ZecSec: Security Audit Process](https://zecsec.com/posts/security-audit-process/)

&nbsp;

### Rust in Bitcoin

Happy New Year! Last month, the RGB team released version 0.9 of all their core crates. In 0.10, there are some consensus-breaking changes planned for RGB contracts, and in 0.11, WASM support is planned. [RGB also has a new info site](https://rgb.info/wallets/), in addition to [developer documentation](http://rgb.tech). The RGB project is also busy rewriting their specs in Contractum, and RGB nodes will soon have the ability to run [generalized contract interfaces](https://twitter.com/lnp_bp/status/1606385243203768335). Nostr has started making a really big showing as the social layer for Bitcoin, much like Lightning is Bitcoin's payments layer, and it has an [excellent relay implementation in Rust](https://github.com/scsibug/nostr-rs-relay). There's a new Lightning node that can run within a mobile browser: [mutiny-web](https://github.com/BitcoinDevShop/mutiny-web-poc).

Rust Bitcoin has better methods for calculating tx input and output weight unit calculation, [see this PR](https://github.com/rust-bitcoin/rust-bitcoin/pull/1467/files). It also added the [Kani verifier](https://github.com/model-checking/kani) to prove certain math ops are safe with [this PR](https://github.com/rust-bitcoin/rust-bitcoin/pull/1415/files).

LDK released version 0.113, and they're hard at work towards getting support for BOLT-12 Offers ("invoice requests") implemented.

For discussion join the [Rust in Bitcoin Telegram group][ribtc]. We've gotten a lot of newcomers lately! Definitely feel free to introduce yourself and ask questions.

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

28 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3]),
17 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
10 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4], [5][bdk-open_issues-5])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bdk-open_issues-5]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

9 merged PRs ([1][bitmask-merged-prs-1]),
1 closed issues ([1][bitmask-closed_issues-1]),
0 open issues

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

5 merged PRs ([1][electrs-merged-prs-1]),
2 closed issues ([1][electrs-closed_issues-1]),
2 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

90 merged PRs ([1][fedimint-merged-prs-1]),
20 closed issues ([1][fedimint-closed_issues-1]),
29 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

32 merged PRs ([1][ldk-merged-prs-1]),
9 closed issues ([1][ldk-closed_issues-1]),
7 open issues ([1][ldk-open_issues-1])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

6 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3]),
10 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3], [4][lnp/bp-closed_issues-4]),
11 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/LNP-BP/invoices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-merged-prs-3]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-closed_issues-2]: https://github.com/LNP-BP/invoices/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-closed_issues-3]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-closed_issues-4]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/invoices/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lnp/bp-open_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

1 merged PRs ([1][nomic-merged-prs-1]),
0 closed issues (),
0 open issues ()

[nomic-merged-prs-1]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

8 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2], [3][rgb-merged-prs-3]),
0 closed issues,
3 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rgb-merged-prs-3]: https://github.com/RGB-WG/rust-rgb20/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rgb-open_issues-2]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

75 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
44 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4], [5][rust_bitcoin-closed_issues-5]),
38 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/jean-airoldie/zeromq-src-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-5]: https://github.com/jean-airoldie/zeromq-src-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

2 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

8 merged PRs ([1][talaia-merged-prs-1]),
7 closed issues ([1][talaia-closed_issues-1]),
1 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

49 merged PRs ([1][ethers-rs-merged-prs-1]),
6 closed issues ([1][ethers-rs-closed_issues-1]),
9 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

76 merged PRs ([1][foundry-merged-prs-1]),
50 closed issues ([1][foundry-closed_issues-1]),
65 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

37 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
13 closed issues ([1][lighthouse-closed_issues-1]),
17 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [Rust Ethereum](https://github.com/rust-ethereum)

1 merged PRs ([1][rust_ethereum-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-12-01..2022-12-31%20-author:app/dependabot
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-12-01..2022-12-31%20-author:app/dependabot

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs,
0 closed issues,
0 open issues

- [A Year of Growth for zkSync](https://blog.matter-labs.io/a-year-of-growth-for-zksync-bb117d1b4f0c)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->


Feb 24 — Mar 5 | Denver, USA

[ETHDenver 2023](https://www.ethdenver.com)

Mar 20-24 | Paris, France

[Paris Blockchain Week](https://www.parisblockchainweek.com)


Mar 26 | Tokyo, Japan

[FHE.org conference 2023](https://fhe.org/)

Mar 27-29 | Tokyo, Japan

[RWC 2023](https://rwc.iacr.org/2023/)

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


