---
title: "RiB Newsletter #42"
description: "November 2022"
date: 2022-12-07
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #42 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #41](/newsletters/rib-newsletter-41/).

It was a bonanza of a month for blockchain Rust,
with many new projects appearing
and blogging about their work,
including
a new HotStuff derivative, [HotShot],
a new Ethereum light client, [Helios],
a new Ethereum full node implementation, [reth],
a new ZKVM, [OlaVM],
and a [Rust SDK for Avalanche][ava].
We also heard more about the [Plonky2 zero-knowledge prover][p2].

[HotShot]: https://www.espressosys.com/blog/espresso-hotshot-consensus-designed-for-rollups
[Helios]: https://a16zcrypto.com/building-helios-ethereum-light-client/
[reth]: https://www.paradigm.xyz/2022/12/reth
[OlaVM]: https://hackmd.io/@sin7y/H1yPj_J8i
[ava]: https://medium.com/avalancheavax/rust-vm-sdk-build-custom-virtual-machines-on-avalanche-using-rust-8334f2ae3c0b
[p2]: https://polygon.technology/blog/plonky2-a-deep-dive

In recent months we've noticed a steady trickle of security advisories
relevant to Rust blockchains, with [new advisories this month][natm]
for `wasmtime` and `libp2p`.
We hope everybody is running [`cargo-audit`] regularly,
but note that `cargo-audit` references only the [RustSec advisory
database][rsad], and some vulnerabilities reported to the [GitHub advisory
database][ghad] are not in the RustSec advisory database. Neither the `wasmtime`
nor `libp2p` advisories published this month are currently in the RustSec
database.

[natm]: #security-advisories
[`cargo-audit`]: https://crates.io/crates/cargo-audit
[rsad]: https://github.com/RustSec/advisory-db
[ghad]: https://github.com/advisories?query=ecosystem%3Arust

In other security news,
Secret Network's trusted execution environment [was completely compromised][sgx1].
Fortunately it was done by whitehat researchers,
but it's more bad news about SGX and secure enclaves.

[sgx1]: https://sgx.fail/


&nbsp;

## Thanks

Thanks to contributors:

[Dominic Wörner],
Tko,
[Brian Anderson], and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Dominic Wörner]: https://github.com/domwoe
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[OlaVM](https://github.com/Sin7Y/olavm).

As described in their [recent blog post](https://hackmd.io/@sin7y/H1yPj_J8i),
OlaVM is a zero-knowledge virtual machine

&nbsp;


## Interesting Things

#### News

- [SGX attacks](https://sgx.fail)

#### Blog Posts

- [Minority Corruption Resilience in Byzantine Generals With Unknown and Fluctuating Participation](https://blog.chain.link/minority-corruption-resilience-in-byzantine-generals-with-unknown-and-fluctuating-participation/)
- [The Latest View on View Synchronization](https://blog.chain.link/view-synchronization/)
- [Leader Election from Randomness Beacons and Other Strategies](https://a16zcrypto.com/leader-election-from-randomness-beacons-and-other-strategies/)
- [Upgradable Smart Contracts: What They Are and How To Deploy Your Own](https://blog.chain.link/upgradable-smart-contracts/)
- [Designing Secure Access Control For Smart Contracts](https://halborn.com/designing-secure-access-control-for-smart-contracts/)
- [Specialized Zero-Knowledge Proof failures](https://blog.trailofbits.com/2022/11/29/specialized-zero-knowledge-proof-failures/)
- [Unique Pseudonymity on Ethereum: Verifiably Deterministic Signatures on ECDSA](https://blog.aayushg.com/posts/nullifier/)
- [Decentralization of ZK Rollups](https://delendum.xyz/2022/11/27/decentralization-of-zk-rollups.html)
- [Constructing ZK SNARK Circuits](https://jtriley.substack.com/p/constructing-zk-snark-circuits)
- [How to transform code into arithmetic circuits](https://www.entropy1729.com/how-to-transform-code-into-arithmetic-circuits/)
- [CESC ‘22: Field Notes from the Zero Knowledge Workshop](https://a16zcrypto.com/cesc-22-field-notes-from-the-zkp-workshop/)
- [Theory of Cryptography Conference ‘22: Field Notes](https://a16zcrypto.com/theory-of-cryptography-conference-22-field-notes/)
- [Parse, don't validate — correctness in smart contract development](https://dev.to/0xtko/parse-dont-validate-correctness-in-smart-contract-development-1h5f)
- [Plonky2: A deep dive](https://polygon.technology/blog/plonky2-a-deep-dive).
  More about the zero knolwedge prover from [Mir protocol](https://github.com/mir-protocol).
- [DLC on Lightning](https://medium.com/crypto-garage/dlc-on-lightning-cb5d191f6e64).
  A description of the first [discreet log contract](https://dci.mit.edu/smart-contracts)
  on the Lightning network, written with [`rust-dlc`](https://github.com/p2pderivatives/rust-dlc/tree/feature/split-tx-manager-2).
- These two recent posts provide a good overview of the ecosystems building on Bitcoin,
  some of which are developed in Rust:
  - [Building on Bitcoin: a Comparison of Bitcoin Projects](https://www.hiro.so/blog/building-on-bitcoin-project-comparison)
  - [A Guide to Web3 Programming Languages for Bitcoin Apps](https://www.hiro.so/blog/bitcoin-ecosystem-a-guide-to-programming-languages-for-bitcoin-smart-contracts)

#### Papers

- [Folding Schemes with Selective Verification](https://eprint.iacr.org/2022/1576)
- [Practical Settlement Bounds for Longest-Chain Consensus](https://eprint.iacr.org/2022/1571)
- [An Auditable Confidentiality Protocol for Blockchain Transactions](https://eprint.iacr.org/2022/1672)
- [Linear-map Vector Commitments and their Practical Applications](https://eprint.iacr.org/2022/705)
- [Ligero: Lightweight Sublinear Arguments Without a Trusted Setup](https://eprint.iacr.org/2022/1608)
- [Extensible Decentralized Secret Sharing and Application to Schnorr Signatures](https://eprint.iacr.org/2022/1551)
- [Vortex: Building a Lattice-based SNARK scheme with Transparent Setup](https://eprint.iacr.org/2022/1633)

#### Projects

- [HotShot](https://github.com/EspressoSystems/HotShot).
  A BFT consensus protocol based off of HotStuff, with the addition of proof-of-stake and VRF committee elections.
  Blog: [Espresso HotShot: Consensus Designed for Rollups](https://www.espressosys.com/blog/espresso-hotshot-consensus-designed-for-rollups).
- [Helios](https://github.com/a16z/helios).
  A fast, secure, and portable light client for Ethereum.
  Blog post: [Building Helios: Fully trustless access to Ethereum](https://a16zcrypto.com/building-helios-ethereum-light-client/)
- [avalanche-types](https://github.com/ava-labs/avalanche-types-rs).
  Avalanche primitive types in Rust.
  It provides an SDK library for developing subnets in Rust and there are two VMs,
  [timestampvm-rs](https://github.com/ava-labs/timestampvm-rs) and
  [spacesvm-rs](https://github.com/ava-labs/spacesvm-rs), are built with the SDK.
  - Blog: [Rust VM SDK: Build Custom Virtual Machines on Avalanche using Rust](https://medium.com/avalancheavax/rust-vm-sdk-build-custom-virtual-machines-on-avalanche-using-rust-8334f2ae3c0b).
  - Doc: [How to Build a Simple Rust VM](https://docs.avax.network/subnets/create-a-simple-rust-vm).
- [decaf377](https://github.com/penumbra-zone/decaf377).
  A prime-order group designed for use in SNARKs over BLS12-377.
  Blog post: [Introducing Poseidon377, our instantiation of a SNARK-friendly hash](https://penumbra.zone/blog/poseidon377).
- [miniSTARK](https://github.com/andrewmilson/ministark).
  GPU accelerated STARK prover and verifier.
- [Nova-Scotia](https://github.com/nalinbhardwaj/Nova-Scotia).
  Middleware to compile Circom circuits to Nova prover.
- [OlaVM](https://github.com/Sin7Y/olavm).
  A new ZKVM.
  Blog post: [Hello, OlaVM!](https://hackmd.io/@sin7y/H1yPj_J8i).
- [reth](https://github.com/paradigmxyz/reth).
  A new Ethereum full node implementation in Rust.
  Blog post: [Introducing Reth](https://www.paradigm.xyz/2022/12/reth).
- [Shinobi](https://github.com/shinobi-protocol/secret-btc).
  A private bridge from Bitcoin to Secret Network.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

<!-- https://github.com/rustsec/advisory-db/pulls -->
<!-- https://osv.dev/list?page=2&ecosystem=crates.io -->

- [RUSTSEC-2022-0067: `lzf` - Unsoundness](https://rustsec.org/advisories/RUSTSEC-2022-0067.html)
- [RUSTSEC-2021-0145: `atty` - Unsoundness](https://rustsec.org/advisories/RUSTSEC-2021-0145.html)
- [RUSTSEC-2022-0068: `capnp` - Vulnerability](https://rustsec.org/advisories/RUSTSEC-2022-0068.html)
- [RUSTSEC-2022-0069: `hyper-staticfile` - Vulnerability](https://rustsec.org/advisories/RUSTSEC-2022-0069.html)
- **[RUSTSEC-2022-0070: `secp256k1` - Unsoundness](https://rustsec.org/advisories/RUSTSEC-2022-0070.html)**.
  Related to usage of `Secp256k1::preallocated_gen_new`.
- [GHSA-9mfc-chwf-7whf: `ckb` - Large dep group requires a lot of resources to process but the cost to commit the transaction is very low](https://github.com/advisories/GHSA-9mfc-chwf-7whf)
- [GHSA-7fw6-6mfj-g3q2: `ckb` - Transaction header_deps validation issue (network forking)](https://github.com/advisories/GHSA-7fw6-6mfj-g3q2)
- [GHSA-mcmr-49x3-4jqm: `ckb` - type_id script resume may randomly fail](https://github.com/advisories/GHSA-mcmr-49x3-4jqm)
- [CVE-2022-41874: `tauri` - Tauri Filesystem Scope can be Partially Bypassed](https://github.com/advisories/GHSA-q9wv-22m9-vhqh)
- **[CVE-2022-39392: `wasmtime` - out of bounds read/write with zero-memory-pages configuration](https://github.com/advisories/GHSA-44mr-8vmm-wjhg)**
- **[CVE-2022-39393: `wasmtime` - may have data leakage between instances in the pooling allocator](https://github.com/advisories/GHSA-wh6w-3828-g9qf)**
- [CVE-2022-39397: `alyun-oss-client` - Leakage Aliyun KeySecret](https://github.com/advisories/GHSA-3w3h-7xgx-grwc)
- **[CVE-2022-23486: `libp2p` - DoS vulnerability from lack of resource management](https://github.com/advisories/GHSA-jvgw-gccv-q5p8)**


&nbsp;

## Most Active in November

[Parity](https://github.com/paritytech):
439 merged PRs,
186 closed issues,
124 open issues

[Sui](https://github.com/MystenLabs):
395 merged PRs,
160 closed issues,
170 open issues

[Solana](https://github.com/solana-labs/solana):
264 merged PRs,
53 closed issues,
31 open issues

[Fuel](https://github.com/FuelLabs):
247 merged PRs,
165 closed issues,
137 open issues

[Filecoin](https://github.com/filecoin-project):
224 merged PRs,
131 closed issues,
92 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

114 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
30 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
17 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Introducing Provers in Aleo Testnet 3](https://www.aleo.org/post/launching-testnet-3-2-provers)
- [Testnet 3 Incentives Kickoff](https://www.aleo.org/post/testnet-3-incentives-kickoff)

#### [Anoma](https://github.com/anoma)

84 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3], [4][anoma-merged-prs-4]),
33 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
32 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-merged-prs-4]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

213 merged PRs ([1][aptos-merged-prs-1]),
132 closed issues ([1][aptos-closed_issues-1]),
62 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Casper](https://github.com/casper-network)

59 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
72 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
19 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

7 merged PRs ([1][comit-merged-prs-1]),
2 closed issues ([1][comit-closed_issues-1]),
3 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

65 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]),
33 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
11 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-euro2ccd-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

9 merged PRs ([1][conflux-merged-prs-1]),
1 closed issues ([1][conflux-closed_issues-1]),
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

4 merged PRs ([1][darkfi-merged-prs-1]),
3 closed issues ([1][darkfi-closed_issues-1]),
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

59 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
7 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2]),
6 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dfinity-open_issues-4]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [How to Migrate Canister Smart Contracts from Motoko to Rust](https://medium.com/dfinity/how-to-migrate-canister-smart-contracts-from-motoko-to-rust-3446a4b0c2ff)

#### [Dusk Network](https://github.com/dusk-network)

9 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2]),
7 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3]),
4 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Testnet DayLight | Release Cycle Update #12](https://dusk.network/news/testnet-daylight-release-cycle-update-12)

#### [Elrond](https://github.com/ElrondNetwork)

95 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3], [4][elrond-merged-prs-4]),
8 closed issues ([1][elrond-closed_issues-1]),
0 open issues

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-nft-marketplace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[elrond-merged-prs-4]: https://github.com/ElrondNetwork/sc-metabonding-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/sc-dex-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

55 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5], [6][espresso_systems-merged-prs-6], [7][espresso_systems-merged-prs-7]),
92 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4], [5][espresso_systems-closed_issues-5]),
79 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4], [5][espresso_systems-open_issues-5], [6][espresso_systems-open_issues-6], [7][espresso_systems-open_issues-7], [8][espresso_systems-open_issues-8])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/reef/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-merged-prs-6]: https://github.com/EspressoSystems/espresso/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-merged-prs-7]: https://github.com/EspressoSystems/espresso-systems-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-closed_issues-5]: https://github.com/EspressoSystems/espresso/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-5]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-6]: https://github.com/EspressoSystems/espresso/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-7]: https://github.com/EspressoSystems/espresso-systems-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[espresso_systems-open_issues-8]: https://github.com/EspressoSystems/atomicstore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Espresso HotShot: Consensus Designed for Rollups](https://www.espressosys.com/blog/espresso-hotshot-consensus-designed-for-rollups)
- [Decentralizing Rollups: Announcing the Espresso Sequencer](https://www.espressosys.com/blog/decentralizing-rollups-announcing-the-espresso-sequencer)
- [Releasing Espresso Testnet 1: Americano](https://www.espressosys.com/blog/releasing-espresso-testnet-1-americano)

#### [Filecoin](https://github.com/filecoin-project)

224 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7]),
131 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5], [6][filecoin-closed_issues-6], [7][filecoin-closed_issues-7], [8][filecoin-closed_issues-8]),
92 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4], [5][filecoin-open_issues-5], [6][filecoin-open_issues-6])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/blstrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/filecoin-project/neptune/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-6]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-7]: https://github.com/filecoin-project/rust-gpu-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-closed_issues-8]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/blstrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/ec-gpu/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-open_issues-5]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[filecoin-open_issues-6]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [The Filecoin Spacenet goes live](https://research.protocol.ai/blog/2022/the-filecoin-spacenet-goes-live/)
- [Filecoin Network v17 Shark Upgrade](https://filecoin.io/blog/posts/filecoin-network-v17-shark-upgrade/)
- Paper: [Temporary Block Withholding Attacks on Filecoin's Expected Consensus](https://eprint.iacr.org/2022/1629)

#### [Findora](https://github.com/FindoraNetwork)

67 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]),
1 closed issues ([1][findora-closed_issues-1]),
1 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[findora-merged-prs-4]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Postmortem Report | Nov 15, 2022](https://medium.com/findorafoundation/findora-incident-postmortem-0-3-30-d844a476c21b)

#### [Fluence](https://github.com/fluencelabs)

49 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6]),
1 closed issues ([1][fluence-closed_issues-1]),
1 open issues ([1][fluence-open_issues-1])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fluence-open_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

247 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10]),
165 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
137 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8], [9][fuel-open_issues-9], [10][fuel-open_issues-10])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-merged-prs-10]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-crypto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-9]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fuel-open_issues-10]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [The Fuel Virtual Machine Architecture](https://jtriley.substack.com/p/the-fuel-virtual-machine-architecture)
- [Exploring the FuelVM](https://medium.com/blockchain-capital-blog/exploring-the-fuelvm-86cf9ccdc159)

#### [Golem](https://github.com/golemfactory)

40 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]),
48 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3], [4][golem-closed_issues-4]),
29 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3], [4][golem-open_issues-4], [5][golem-open_issues-5])

[golem-merged-prs-1]: https://github.com/golemfactory/ya-runtime-http-auth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-merged-prs-5]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-closed_issues-4]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-service-bus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-open_issues-3]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-open_issues-4]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[golem-open_issues-5]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Helium](https://github.com/helium)

9 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]),
6 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
0 open issues

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/ecc608-linux-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[helium-closed_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

24 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]),
8 closed issues ([1][holochain-closed_issues-1]),
11 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Hackathon, Tool Upgrades, hREA](https://blog.holochain.org/hackathon-tool-upgrades-hrea/)
- [Holochain Beta Approaching](https://blog.holochain.org/holochain-beta-approaching/)

#### [IOTA](https://github.com/iotaledger)

141 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6]),
49 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5]),
32 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4])

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-merged-prs-6]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-closed_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-closed_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-closed_issues-5]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[iota-open_issues-4]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

80 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4], [5][maidsafe-merged-prs-5]),
3 closed issues ([1][maidsafe-closed_issues-1], [2][maidsafe-closed_issues-2]),
14 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/blsttc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[maidsafe-merged-prs-5]: https://github.com/maidsafe/sn_consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[maidsafe-closed_issues-2]: https://github.com/maidsafe/blsttc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

44 merged PRs ([1][mobilecoin-merged-prs-1]),
8 closed issues ([1][mobilecoin-closed_issues-1]),
11 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

161 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6]),
41 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8]),
37 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-7]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-closed_issues-8]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Auditing Projects on the NEAR Blockchain: From Zero to Hero](https://blog.pessimistic.io/auditing-projects-on-the-near-blockchain-from-zero-to-hero-9c5400507c80)

#### [Nervos](https://github.com/nervosnetwork)

87 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8]),
14 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4], [5][nervos-closed_issues-5]),
10 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-merged-prs-7]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-merged-prs-8]: https://github.com/godwokenrises/godwoken-scripts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/nervosnetwork/ckb-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-closed_issues-5]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [CKB Soft Fork process & Light Client Soft Fork](https://www.nervos.org/blog/ckb-soft-fork-process-light-client-soft-fork)

#### [Oasis](https://github.com/oasisprotocol)

9 merged PRs ([1][oasis-merged-prs-1]),
3 closed issues ([1][oasis-closed_issues-1]),
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

439 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15]),
186 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13]),
124 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-merged-prs-15]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-closed_issues-13]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-13]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[parity-open_issues-14]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Radix](https://github.com/radixdlt)

51 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3]),
0 closed issues,
4 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/scrypto-challenges/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

20 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]),
2 closed issues ([1][secret_network-closed_issues-1], [2][secret_network-closed_issues-2]),
0 open issues

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[secret_network-closed_issues-2]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Notice: Successful Resolution of xAPIC Vulnerability on Secret Network](https://scrt.network/blog/notice-successful-resolution-of-xapic-vulnerability).
  Secret Network's TEE was completely compromised. More at the [researcher's site](https://sgx.fail/).

#### [Solana](https://github.com/solana-labs/solana)

264 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]),
53 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
31 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Neon Synthetic Load Test Report](https://medium.com/neon-labs/neon-synthetic-load-test-report-d53212711556)
- [Neon EVM Set to Go Live on Mainnet](https://medium.com/neon-labs/neon-evm-set-to-go-live-on-mainnet-welcome-to-a-new-era-of-ethereum-scalability-on-solana-63b25bcc77a3)

#### [Subspace Labs](https://github.com/subspace)

61 merged PRs ([1][subspace_labs-merged-prs-1]),
16 closed issues ([1][subspace_labs-closed_issues-1]),
8 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

395 merged PRs ([1][sui-merged-prs-1]),
160 closed issues ([1][sui-closed_issues-1]),
170 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Cryptography in Sui: Agility](https://tech.mystenlabs.com/cryptography-in-sui-agility/)
- [Cryptography in Sui](https://tech.mystenlabs.com/cryptography-in-sui/)
- [Building the Capy Prototype on Sui](https://tech.mystenlabs.com/building-the-capy-prototype-on-sui/)

#### [Zcash](https://github.com/zcash)

93 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4]),
46 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]),
42 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

3 merged PRs ([1][aluvm-merged-prs-1]),
1 closed issues ([1][aluvm-closed_issues-1]),
2 open issues ([1][aluvm-open_issues-1])

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aluvm-closed_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[aluvm-open_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

28 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]),
36 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
21 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

10 merged PRs ([1][bitmask-merged-prs-1]),
2 closed issues ([1][bitmask-closed_issues-1]),
4 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Cyphernet](https://github.com/Cyphernet-WG)

4 merged PRs ([1][cyphernet-merged-prs-1], [2][cyphernet-merged-prs-2]),
0 closed issues,
0 open issues

[cyphernet-merged-prs-1]: https://github.com/Cyphernet-WG/rust-internet2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[cyphernet-merged-prs-2]: https://github.com/Cyphernet-WG/rust-netservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

7 merged PRs ([1][electrs-merged-prs-1]),
11 closed issues ([1][electrs-closed_issues-1]),
4 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

84 merged PRs ([1][fedimint-merged-prs-1]),
29 closed issues ([1][fedimint-closed_issues-1]),
15 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

45 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2]),
17 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
16 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

22 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3], [4][lnp/bp-merged-prs-4], [5][lnp/bp-merged-prs-5], [6][lnp/bp-merged-prs-6]),
25 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3], [4][lnp/bp-closed_issues-4]),
33 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2], [3][lnp/bp-open_issues-3], [4][lnp/bp-open_issues-4], [5][lnp/bp-open_issues-5], [6][lnp/bp-open_issues-6])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/LNP-BP/rust-lnpbp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-merged-prs-3]: https://github.com/LNP-BP/invoices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-merged-prs-4]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-merged-prs-5]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-merged-prs-6]: https://github.com/BP-WG/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-closed_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-closed_issues-3]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-closed_issues-4]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-open_issues-2]: https://github.com/LNP-BP/rust-lnpbp/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-open_issues-3]: https://github.com/LNP-BP/invoices/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-open_issues-4]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-open_issues-5]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp/bp-open_issues-6]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [LNP WG](https://github.com/LNP-WG)

1 merged PRs ([1][lnp_wg-merged-prs-1]),
1 closed issues ([1][lnp_wg-closed_issues-1]),
1 open issues ([1][lnp_wg-open_issues-1])

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp_wg-closed_issues-1]: https://github.com/LNP-WG/lnp-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lnp_wg-open_issues-1]: https://github.com/LNP-WG/lnp-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

4 merged PRs ([1][nakamoto-merged-prs-1]),
0 closed issues,
0 open issues

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

6 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2], [3][rgb-merged-prs-3]),
25 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2], [3][rgb-closed_issues-3]),
6 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2], [3][rgb-open_issues-3])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-merged-prs-3]: https://github.com/RGB-WG/rust-rgb20/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-closed_issues-3]: https://github.com/RGB-WG/rust-rgb20/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-open_issues-2]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rgb-open_issues-3]: https://github.com/RGB-WG/rust-rgb20/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Contractum](https://www.contractum.org/).
  A new smart contract language for RGB.

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

68 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
40 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4], [5][rust_bitcoin-closed_issues-5], [6][rust_bitcoin-closed_issues-6]),
25 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-5]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-6]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

2 merged PRs ([1][rust_simplicity-merged-prs-1]),
1 closed issues ([1][rust_simplicity-closed_issues-1]),
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_simplicity-closed_issues-1]: https://github.com/ElementsProject/rust-simplicity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Sapio](https://github.com/sapio-lang/sapio)

1 merged PRs ([1][sapio-merged-prs-1]),
0 closed issues,
0 open issues

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

12 merged PRs ([1][talaia-merged-prs-1]),
6 closed issues ([1][talaia-closed_issues-1]),
3 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

51 merged PRs ([1][ethers-rs-merged-prs-1]),
26 closed issues ([1][ethers-rs-closed_issues-1]),
11 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

86 merged PRs ([1][foundry-merged-prs-1]),
59 closed issues ([1][foundry-closed_issues-1]),
58 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

20 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
15 closed issues ([1][lighthouse-closed_issues-1]),
29 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

- [Optimising Attestation Packing](https://lighthouse-blog.sigmaprime.io/optimising-attestation-packing.html)
- [Lighthouse Update #41](https://lighthouse-blog.sigmaprime.io/update-41.html)

#### [Rust Ethereum](https://github.com/rust-ethereum)

7 merged PRs ([1][rust_ethereum-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

#### [zkSync](https://github.com/matter-labs/zksync)

2 merged PRs ([1][zksync-merged-prs-1]),
3 closed issues ([1][zksync-closed_issues-1]),
1 open issues ([1][zksync-open_issues-1])

[zksync-merged-prs-1]: https://github.com/matter-labs/franklin-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-11-01..2022-11-30%20-author:app/dependabot
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2022-11-01..2022-11-30%20-author:app/dependabot

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Dec 15 | Online

[Secret Summit 2022](https://scrt.network/summit)

Feb 24 — Mar 5, 2023 | Denver, USA

[ETHDenver 2023](https://www.ethdenver.com)

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


