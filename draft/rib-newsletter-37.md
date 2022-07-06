---
title: "RiB Newsletter #37"
description: "June 2022"
date: 2022-07-06
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #37 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #36](/newsletters/rib-newsletter-36/).

&nbsp;

## Thanks

Thanks to contributors:
[djddo],
[Hunter Trujillo],
[keymakercasa],
[kn0wmad],
[mradkov],
[Piotr Dziubecki],
Samuel Dare,
[Brian Anderson], and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[djddo]: https://github.com/djddo
[Hunter Trujillo]: https://github.com/cryptoquick
[keymakercasa]: https://github.com/keymakercasa
[kn0wmad]: https://github.com/kn0wmad
[mradkov]: https://github.com/mradkov
[Piotr Dziubecki]: https://github.com/piotr-dziubecki
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### Blog Posts

- [DAG Meets BFT - The Next Generation of BFT Consensus](https://decentralizedthoughts.github.io/2022-06-28-DAG-meets-BFT/)
- [Are blockchains decentralized?](https://blog.trailofbits.com/2022/06/21/are-blockchains-decentralized/)
- [Smart Contract Security: A Simple Checklist for Web3 Development](https://a16zcrypto.com/smart-contract-security-checklist-web3-development/)
- [New PQC NIST standards announced](https://arstechnica.com/information-technology/2022/07/nist-selects-quantum-proof-algorithms-to-head-off-the-coming-cryptopocalypse/)
- [Zero Knowledge Proof — Deep into zkEVM source code (MPT Circuit)](https://starli.medium.com/zero-knowledge-proof-deep-into-zkevm-source-code-mpt-circuit-fb2dba6e8ba3)
- [Zero Knowledge Proof — Deep into zkEVM source code (State Circuit)](https://starli.medium.com/zero-knowledge-proof-deep-into-zkevm-source-code-state-circuit-b3175b937fea)

#### Papers

- [Cross Chain Atomic Swaps in the Absence of Time via Attribute Verifiable Timed Commitments](https://eprint.iacr.org/2022/717)
- [End-to-End Security for Distributed Event-Driven Enclave Applications on Heterogeneous TEEs](https://arxiv.org/abs/2206.01041)
- [Safe Permissionless Consensus](https://eprint.iacr.org/2022/796)
- [Round Efficient Byzantine Agreement from VDFs](https://eprint.iacr.org/2022/823)
- [VERI-ZEXE: Decentralized Private Computation with Universal Setup](https://eprint.iacr.org/2022/802)
- [Hertzbleed: Turning Power Side-Channel Attacks Into Remote Timing Attacks on x86](https://www.hertzbleed.com)
- [Curve Trees: Practical and Transparent Zero-Knowledge Accumulators](https://eprint.iacr.org/2022/756)
- [On the Anonymity Guarantees of Anonymous Proof-of-Stake Protocols](https://eprint.iacr.org/2021/409)
- [Nova: Recursive Zero-Knowledge Arguments from Folding Schemes](https://eprint.iacr.org/2021/370)

#### Projects

- [Cleopatra Cairo](https://github.com/lambdaclass/cleopatra_cairo).
  A Rust implementation of the Cairo VM. Cairo is a programming
  language for writing provable programs, where one party can prove to
  another that a certain computation was executed correctly. Cairo and
  similar proof systems can be used to provide scalability to
  blockchains.
- [Rust Discrete Log Contracts](https://github.com/p2pderivatives/rust-dlc). 
  DLCs are a means of creating derivatives, futures, and stablecoin contracts on Bitcoin. For more, see the [DLC specs](https://github.com/discreetlogcontracts/dlcspecs). It makes use of the rust-lightning (LDK) and rust-bitcoin crates.
- [arkworks::algebra](https://github.com/arkworks-rs/algebra).
  Libraries for finite field, elliptic curve, and polynomial arithmetic
- [Circuits for zkEVM](https://github.com/privacy-scaling-explorations/zkevm-circuits).
- [Lurk](https://github.com/lurk-lang/lurk-rs).
  A Turing-complete programming language for Zero-Knowledge Proofs.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

- [RUSTSEC-2022-0033: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2022-0033.html).
  - Heap memory corruption with RSA private key operation.
- [RUSTSEC-2022-0032: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2022-0032.html).
  - AES OCB fails to encrypt some bytes.
- [RUSTSEC-2022-0029: Vulnerability in crossbeam](https://rustsec.org/advisories/RUSTSEC-2022-0029.html).
  - `MsQueue` `push`/`pop` use the wrong orderings
- [CVE-2021-41641: Link following in Deno](https://github.com/advisories/GHSA-67hm-27mx-9cg7).
- [CVE-2022-31100: Reachable assertion in rulex](https://github.com/advisories/GHSA-8v9w-p43c-r885).
- [CVE-2022-31099: Uncontrolled recursion in rulex](https://github.com/advisories/GHSA-v78m-2q7v-fjqp).
- [CVE-2022-31104: Miscompilation of `i8x16.swizzle` and `select` with v128 inputs in `cranelift`](https://github.com/advisories/GHSA-jqwc-c49r-4w2x).

GitHub issued a large set of advisories on a single day in June,
but it seems to be a result of importing old RustSec advisories.

&nbsp;

## Most Active in June

[Parity](https://github.com/paritytech):
557 merged PRs,
152 closed issues,
130 open issues

[Solana](https://github.com/solana-labs/solana):
501 merged PRs,
95 closed issues,
103 open issues

[Sui](https://github.com/MystenLabs):
343 merged PRs,
155 closed issues,
140 open issues

[Fuel](https://github.com/FuelLabs):
339 merged PRs,
214 closed issues,
180 open issues

[Aptos](https://github.com/aptos-labs):
290 merged PRs,
81 closed issues,
32 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

50 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 
25 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]),
14 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Anoma](https://github.com/anoma)

19 merged PRs ([1][anoma-merged-prs-1]), 
10 closed issues ([1][anoma-closed_issues-1]),
28 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Aptos](https://github.com/aptos-labs)

290 merged PRs ([1][aptos-merged-prs-1]), 
81 closed issues ([1][aptos-closed_issues-1]),
32 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Casper](https://github.com/casper-network)

69 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]), 
79 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
41 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [ChainSafe](https://github.com/ChainSafe)

45 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]), 
91 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2], [3][chainsafe-closed_issues-3]),
20 open issues ([1][chainsafe-open_issues-1], [2][chainsafe-open_issues-2])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/mina-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/api3-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[chainsafe-closed_issues-3]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[chainsafe-open_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[chainsafe-open_issues-2]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [COMIT](https://github.com/comit-network)

4 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 
0 closed issues,
3 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2])

[comit-merged-prs-1]: https://github.com/comit-network/maia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[comit-merged-prs-3]: https://github.com/comit-network/xtra-productivity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[comit-open_issues-1]: https://github.com/comit-network/maia/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[comit-open_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Concordium](https://github.com/Concordium)

38 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7], [8][concordium-merged-prs-8]), 
49 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4], [5][concordium-closed_issues-5], [6][concordium-closed_issues-6], [7][concordium-closed_issues-7]),
34 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4], [5][concordium-open_issues-5], [6][concordium-open_issues-6])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-euro2ccd-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-use-case-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-merged-prs-8]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[concordium-closed_issues-5]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[concordium-closed_issues-6]: https://github.com/Concordium/concordium-use-case-examples/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[concordium-closed_issues-7]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[concordium-open_issues-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[concordium-open_issues-3]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[concordium-open_issues-4]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[concordium-open_issues-5]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[concordium-open_issues-6]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Conflux](https://github.com/Conflux-Chain)

16 merged PRs ([1][conflux-merged-prs-1]), 
0 closed issues,
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30

#### [DarkFi](https://dark.fi)

2 merged PRs ([1][darkfi-merged-prs-1]), 
2 closed issues ([1][darkfi-closed_issues-1]),
2 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Dfinity](https://github.com/dfinity)

92 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7], [8][dfinity-merged-prs-8]), 
34 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5], [6][dfinity-closed_issues-6], [7][dfinity-closed_issues-7]),
7 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-merged-prs-3]: https://github.com/dfinity/icx-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-merged-prs-4]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-merged-prs-5]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-merged-prs-6]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-merged-prs-7]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-merged-prs-8]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dfinity-closed_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dfinity-closed_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dfinity-closed_issues-5]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dfinity-closed_issues-6]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dfinity-closed_issues-7]: https://github.com/dfinity/ic-types/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[dfinity-open_issues-3]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Dusk Network](https://github.com/dusk-network)

27 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5]), 
27 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4]),
7 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3], [4][dusk_network-open_issues-4])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/dusk-hamt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dusk_network-merged-prs-2]: https://github.com/dusk-network/microkelvin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dusk_network-merged-prs-3]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dusk_network-merged-prs-4]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dusk_network-merged-prs-5]: https://github.com/dusk-network/rusk-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[dusk_network-closed_issues-1]: https://github.com/dusk-network/microkelvin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dusk_network-closed_issues-2]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dusk_network-closed_issues-3]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dusk_network-closed_issues-4]: https://github.com/dusk-network/rusk-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[dusk_network-open_issues-1]: https://github.com/dusk-network/dusk-zerocaf/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[dusk_network-open_issues-2]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[dusk_network-open_issues-3]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[dusk_network-open_issues-4]: https://github.com/dusk-network/rusk-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Elrond](https://github.com/ElrondNetwork)

37 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3], [4][elrond-merged-prs-4], [5][elrond-merged-prs-5]), 
15 closed issues ([1][elrond-closed_issues-1], [2][elrond-closed_issues-2]),
3 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-nft-marketplace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[elrond-merged-prs-4]: https://github.com/ElrondNetwork/sc-metabonding-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[elrond-merged-prs-5]: https://github.com/ElrondNetwork/sc-bridge-elrond/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[elrond-closed_issues-2]: https://github.com/ElrondNetwork/sc-dex-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [Elrond Incident and Recovery Report](https://elrond.com/blog/incident-and-recovery-report/)

#### [Espresso Systems](https://github.com/EspressoSystems)

68 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3]), 
46 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
23 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/reef/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Findora](https://github.com/FindoraNetwork)

36 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]), 
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[findora-merged-prs-2]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[findora-merged-prs-3]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[findora-merged-prs-4]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30

#### [Fluence](https://github.com/fluencelabs)

52 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7]), 
27 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2], [3][fluence-closed_issues-3], [4][fluence-closed_issues-4]),
3 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fluence-merged-prs-3]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fluence-merged-prs-4]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fluence-merged-prs-5]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fluence-merged-prs-6]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fluence-merged-prs-7]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fluence-closed_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fluence-closed_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fluence-closed_issues-3]: https://github.com/fluencelabs/examples/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fluence-closed_issues-4]: https://github.com/fluencelabs/registry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fluence-open_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fluence-open_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Fuel](https://github.com/FuelLabs)

339 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12]), 
214 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8], [9][fuel-closed_issues-9]),
180 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-bft/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-11]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-merged-prs-12]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-bft/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-8]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-closed_issues-9]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-bft/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fuel-open_issues-7]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[fuel-open_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Golem](https://github.com/golemfactory)

42 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5], [6][golem-merged-prs-6]), 
42 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]),
22 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3])

[golem-merged-prs-1]: https://github.com/golemfactory/ya-runtime-http-auth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[golem-merged-prs-2]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[golem-merged-prs-3]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[golem-merged-prs-4]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[golem-merged-prs-5]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[golem-merged-prs-6]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[golem-closed_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[golem-open_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[golem-open_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Grin](https://github.com/mimblewimble/grin)

2 merged PRs ([1][grin-merged-prs-1], [2][grin-merged-prs-2]), 
0 closed issues,
3 open issues ([1][grin-open_issues-1], [2][grin-open_issues-2])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[grin-merged-prs-2]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[grin-open_issues-2]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Helium](https://github.com/helium)

8 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]), 
9 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
2 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[helium-merged-prs-2]: https://github.com/helium/semtech-udp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[helium-merged-prs-3]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[helium-merged-prs-4]: https://github.com/helium/helium-api-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[helium-closed_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[helium-open_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [Helium Wallet App Now Available for Download](https://blog.helium.com/helium-wallet-app-now-available-for-download-b25e9c7ebedd)
- [Helium x Streamr](https://blog.helium.com/helium-x-streamr-ea89c4b61a14)

#### [Holochain](https://github.com/holochain/)

40 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]), 
3 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
5 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[holochain-merged-prs-2]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[holochain-merged-prs-3]: https://github.com/holochain/hc-utils/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [IOTA](https://github.com/iotaledger)

242 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6], [7][iota-merged-prs-7]), 
65 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5], [6][iota-closed_issues-6]),
42 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4], [5][iota-open_issues-5], [6][iota-open_issues-6], [7][iota-open_issues-7], [8][iota-open_issues-8])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[iota-merged-prs-5]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[iota-merged-prs-6]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[iota-merged-prs-7]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[iota-closed_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[iota-closed_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[iota-closed_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[iota-closed_issues-4]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[iota-closed_issues-5]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[iota-closed_issues-6]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[iota-open_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[iota-open_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[iota-open_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[iota-open_issues-5]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[iota-open_issues-6]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[iota-open_issues-7]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[iota-open_issues-8]: https://github.com/iotaledger/chronicle.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Maidsafe](https://github.com/maidsafe)

75 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4], [5][maidsafe-merged-prs-5], [6][maidsafe-merged-prs-6]), 
8 closed issues ([1][maidsafe-closed_issues-1]),
6 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2], [3][maidsafe-open_issues-3])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[maidsafe-merged-prs-4]: https://github.com/maidsafe/blsttc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[maidsafe-merged-prs-5]: https://github.com/maidsafe/sn_consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[maidsafe-merged-prs-6]: https://github.com/maidsafe/bls_dkg/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[maidsafe-open_issues-2]: https://github.com/maidsafe/sn_consensus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[maidsafe-open_issues-3]: https://github.com/maidsafe/self_encryption/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [MobileCoin](https://github.com/mobilecoinfoundation)

110 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]), 
26 closed issues ([1][mobilecoin-closed_issues-1]),
14 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [NEAR](https://github.com/nearprotocol/nearcore)

202 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10]), 
49 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8]),
52 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-6]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-7]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-8]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-9]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-merged-prs-10]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-closed_issues-4]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-closed_issues-5]: https://github.com/near/near-lake-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-closed_issues-6]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-closed_issues-7]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-closed_issues-8]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[near-open_issues-4]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[near-open_issues-5]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[near-open_issues-6]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [NEAR Foundation Launches Smart Contract Audit Program](https://near.org/blog/near-foundation-launches-smart-contract-audit-program/)

#### [Nervos](https://github.com/nervosnetwork)

179 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8], [9][nervos-merged-prs-9]), 
9 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/axon/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-4]: https://github.com/nervosnetwork/mercury/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-6]: https://github.com/nervosnetwork/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-7]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-8]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-merged-prs-9]: https://github.com/nervosnetwork/ckb-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/axon/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[nervos-closed_issues-2]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[nervos-closed_issues-4]: https://github.com/nervosnetwork/ckb-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/axon/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [Major Protocol Upgrade – Diving Into CKB-VM V1](https://www.nervos.org/blog/major-protocol-upgrade-diving-into-ckb-vm-v1)

#### [Oasis](https://github.com/oasisprotocol)

42 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2], [3][oasis-merged-prs-3]), 
4 closed issues ([1][oasis-closed_issues-1], [2][oasis-closed_issues-2]),
1 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[oasis-merged-prs-2]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[oasis-merged-prs-3]: https://github.com/oasisprotocol/emerald-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[oasis-closed_issues-2]: https://github.com/oasisprotocol/cipher-paratime/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Parity](https://github.com/paritytech)

557 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15]), 
152 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13], [14][parity-closed_issues-14]),
130 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-13]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-14]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-merged-prs-15]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-12]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-13]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-closed_issues-14]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-13]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[parity-open_issues-14]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

5 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 
3 closed issues ([1][secret_network-closed_issues-1], [2][secret_network-closed_issues-2]),
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[secret_network-closed_issues-2]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Solana](https://github.com/solana-labs/solana)

501 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]), 
95 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
103 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [Solana Network Upgrades](https://solana.com/news/solana-network-upgrades)
- [Solana Mobile debuts Saga, a flagship Android phone for web3](https://solana.com/news/page/2)
- [The reality behind Solana's claimed 50K TPS](https://www.reddit.com/r/solana/comments/vd6805/the_reality_behind_solanas_claimed_50k_tps)

#### [Subspace Labs](https://github.com/subspace)

68 merged PRs ([1][subspace_labs-merged-prs-1]), 
38 closed issues ([1][subspace_labs-closed_issues-1]),
12 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Sui](https://github.com/MystenLabs)

343 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2]), 
155 closed issues ([1][sui-closed_issues-1], [2][sui-closed_issues-2]),
140 open issues ([1][sui-open_issues-1], [2][sui-open_issues-2])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[sui-merged-prs-2]: https://github.com/MystenLabs/narwhal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[sui-closed_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[sui-open_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [TezEdge](https://github.com/tezedge)

47 merged PRs ([1][tezedge-merged-prs-1], [2][tezedge-merged-prs-2]), 
0 closed issues,
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[tezedge-merged-prs-2]: https://github.com/tezedge/tezedge-snapshots/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Zcash](https://github.com/zcash)

110 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4]), 
90 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4], [5][zcash-closed_issues-5]),
34 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[zcash-merged-prs-4]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[zcash-closed_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[zcash-closed_issues-5]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

&nbsp;

### Rust in Bitcoin

BDK 0.19 was released with experimental Taproot support, including `tr()` descriptors, taproot PSBTs, signing key and script spend taproot PSBTs, and `tr()` in `descriptor!` macros. Lots of activity from the RGB team this month as they released rgb 0.7 and are working hard on finishing 0.8, which is currently available pre-release, and includes work on Tapret on-chain Deterministic Bitcoin Contracts. Once the rgb-core 0.8 release is finalized, mainnet support for RGB20 tokens should be ready. Activity around LDK is also picking up, with their recent 0.108 and 0.109 releases.

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

28 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4], [5][bdk-merged-prs-5]), 
17 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3], [4][bdk-closed_issues-4], [5][bdk-closed_issues-5]),
18 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4], [5][bdk-open_issues-5])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[bdk-merged-prs-5]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[bdk-closed_issues-4]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[bdk-closed_issues-5]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[bdk-open_issues-5]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [0.19 Released with Taproot support](https://twitter.com/bitcoindevkit/status/1535307506880114688)
- [rust-hwi version 0.2.0 is out!](https://github.com/bitcoindevkit/rust-hwi/releases/tag/v0.2.0)
- [bdk-swift version 0.4.0 is ready, including bdk 0.19.0 with experimental tr() descriptor support](https://github.com/bitcoindevkit/bdk-swift/releases/tag/0.4.0)

#### [Bitmask](https://github.com/diba-io/bitmask-core)

8 merged PRs ([1][bitmask-merged-prs-1]), 
2 closed issues ([1][bitmask-closed_issues-1]),
1 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Electrs](https://github.com/romanz/electrs)

8 merged PRs ([1][electrs-merged-prs-1]), 
4 closed issues ([1][electrs-closed_issues-1]),
4 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Internet2](https://github.com/internet2-wg/)

4 merged PRs ([1][internet2-merged-prs-1], [2][internet2-merged-prs-2]), 
2 closed issues ([1][internet2-closed_issues-1]),
2 open issues ([1][internet2-open_issues-1], [2][internet2-open_issues-2])

[internet2-merged-prs-1]: https://github.com/Internet2-WG/rust-internet2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[internet2-merged-prs-2]: https://github.com/Internet2-WG/rust-microservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[internet2-closed_issues-1]: https://github.com/Internet2-WG/rust-internet2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[internet2-open_issues-1]: https://github.com/Internet2-WG/rust-internet2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[internet2-open_issues-2]: https://github.com/Internet2-WG/rust-microservices/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

43 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]), 
15 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
15 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [rust-lightning 0.0.109 released](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.109)
- [The story behind LDK, where they are, and where they're going](https://lightningdevkit.org/blog/ldk-an-sdk-for-the-lightning-network/)
- [LDK adds anti-fee sniping measures to channel funding transactions](https://github.com/lightningdevkit/rust-lightning/pull/1531)
  - [See this article for more on fee-sniping](https://bitcoinops.org/en/topics/fee-sniping/)

#### [LNP/BP](https://github.com/LNP-BP)

18 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3]), 
10 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3]),
2 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[lnp/bp-merged-prs-2]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[lnp/bp-merged-prs-3]: https://github.com/BP-WG/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[lnp/bp-closed_issues-2]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[lnp/bp-closed_issues-3]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[lnp/bp-open_issues-1]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[lnp/bp-open_issues-2]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [LNP WG](https://github.com/LNP-WG)

2 merged PRs ([1][lnp_wg-merged-prs-1]), 
0 closed issues,
0 open issues

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30

#### [MyCitadel](https://github.com/orgs/mycitadel)

0 merged PRs,
0 closed issues,
1 open issues ([1][mycitadel-open_issues-1])

[mycitadel-open_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

0 merged PRs,
0 closed issues,
1 open issues ([1][nakamoto-open_issues-1])

[nakamoto-open_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Nomic](https://github.com/nomic-io)

5 merged PRs ([1][nomic-merged-prs-1]), 
0 closed issues,
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30

#### [RGB](https://github.com/rgb-wg)

7 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2]), 
42 closed issues ([1][rgb-closed_issues-1]),
5 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

79 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]), 
30 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4], [5][rust_bitcoin-closed_issues-5]),
19 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rust_bitcoin-closed_issues-5]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

3 merged PRs ([1][rust_simplicity-merged-prs-1]), 
0 closed issues,
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30

#### [Sapio](https://github.com/sapio-lang/sapio)

8 merged PRs ([1][sapio-merged-prs-1]), 
0 closed issues,
0 open issues

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30

#### [Talaia](https://github.com/talaia-labs/rust-teos)

2 merged PRs ([1][talaia-merged-prs-1]), 
1 closed issues ([1][talaia-closed_issues-1]),
5 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!

&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

87 merged PRs ([1][ethers-rs-merged-prs-1]), 
11 closed issues ([1][ethers-rs-closed_issues-1]),
6 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [Lighthouse](https://github.com/sigp/lighthouse)

3 merged PRs ([1][lighthouse-merged-prs-1]), 
12 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]),
17 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

- [Lighthouse Release v2.3.1 (Butter Robot)](https://github.com/sigp/lighthouse/releases/tag/v2.3.1)

#### [Rust Ethereum](https://github.com/rust-ethereum)

3 merged PRs ([1][rust_ethereum-merged-prs-1]), 
2 closed issues ([1][rust_ethereum-closed_issues-1]),
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30


#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

0 merged PRs,
5 closed issues ([1][rust_web3-closed_issues-1]), 
3 open issues ([1][rust_web3-open_issues-1])

[rust_web3-closed_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-06-01..2022-06-30
[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

#### [zkSync](https://github.com/matter-labs/zksync)

4 merged PRs ([1][zksync-merged-prs-1]), 
0 closed issues,
2 open issues ([1][zksync-open_issues-1])

[zksync-merged-prs-1]: https://github.com/matter-labs/compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-06-01..2022-06-30
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2022-06-01..2022-06-30

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Aug 7-9 | Online, Las Vegas, US

[Zcon3](https://zfnd.org/zcon3/)

Aug 10-12 | Matsue city, Shimane, Japan

[The 4th International Conference on Science of Cyber Security (SciSec 2022)](https://scisec.org/)

Aug 13-18 | Santa Barbara, CA, US

[Crypto 2022](https://crypto.iacr.org/2022/)

Aug 29-31 | Arrillaga Alumni Center, Stanford University

[SBC'22: The Science of Blockchain Conference 2022](https://cbr.stanford.edu/sbc22/)

Sep 12-14 | Radialsystem, Berlin

[Developer Conference for Ethereum Infrastructure and Dapps](https://www.dappcon.io/)

Sep 15 | Berlin, Germany

[zkSummit 8](https://www.zksummit.com/)

Sep 28-29 | Online, NYC, US

[SmartCon 2022](https://smartcon.chain.link/)

Oct 7-16 | Bogota, Colombia

[Devcon Week](https://devcon.org/)

Oct 28-30 | Lisbon, Portugal

[ETH Lisbon](https://www.ethlisbon.org/)

Nov 7-10 | Chicago, USA

[TCC 2022](https://tcc.iacr.org/2022/)

Nov 10-11 | Dubai, United Arab Emirates

[ICSCB 2022: 16. International Conference on Smart Contracts and Blockchain](https://waset.org/smart-contracts-and-blockchain-conference-in-november-2022-in-dubai)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Casper Labs | Remote
- [Project Manager (China)](https://casperlabs.io/careers#)
- [React Developer](https://casperlabs.io/careers#)
- [Director of Product Marketing](https://casperlabs.io/careers#)
- [Rust Developer](https://casperlabs.io/careers#)
- [Typescript Developer](https://casperlabs.io/careers#)
- [Core Engineer : dAPP Dev](https://casperlabs.io/careers#)
- [Full Stack Developer](https://casperlabs.io/careers#)

Start9 Labs | Denver, USA / Remote
- [Backend Developer (Rust)](https://start9.com/latest/about/jobs#backend-developer-rust)
- [Frontend Developer (JS)](https://start9.com/latest/about/jobs#frontend-developer-js)
- [Product Designer](https://start9.com/latest/about/jobs#product-designer)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


