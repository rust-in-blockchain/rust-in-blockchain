---
title: "RiB Newsletter #39"
description: "August 2022"
date: 2022-09-07
categories:
  - "newsletters"
summary: "Welcome to the #39 edition of Rust in Blockchain.
This month we spotlight `automerge-rs`.
Automerge is a popular JavaScript library for working with conflict-free replicated datatypes (CRDTs)."
---

Welcome to the #39 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #38](/newsletters/rib-newsletter-38/).

&nbsp;

## Thanks

Thanks to contributors:
Dan Shields,
[djddo],
[Eli Corrales],
Ganzaro,
[Hunter Trujillo],
Mayoeba Yabureru,
[Paul],
[Piotr Dziubecki],
[Rodairos],
[Brian Anderson], and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[djddo]: https://github.com/djddo
[Eli Corrales]: https://github.com/elicorrales
[Paul]: https://github.com/ChengYueJia
[Piotr Dziubecki]: https://github.com/piotr-dziubecki
[Rodairos]: https://github.com/rodairos
[Hunter Trujillo]: https://github.com/cryptoquick
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[automerge-rs](https://github.com/automerge/automerge-rs).

[Automerge] is a popular JavaScript library for working with [conflict-free replicated datatypes][crdts] (CRDTs).
CRDTs allow multiple parties to independently make changes to a shared data structure,
while guaranteeing that those changes can all be resolved unambiguously in the future.
The most commonly-understood use of CRDTs is in collaborative document editing.
Automerge is network-protocol agnostic and can be used in asynchronous contexts.

`automerge-rs` is a re-implementation, by the original authors, in Rust,
and is wasm-compatible.

[Automerge]: https://automerge.org/
[crdts]: https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type

&nbsp;


## Interesting Things

#### News

- [Plonky2 is Now Open-Source](https://blog.polygon.technology/plonky2-is-now-open-source/).

#### Blog Posts

- [The noname language, a toy DSL for zkapps](https://www.cryptologie.net/article/568/the-noname-language-a-toy-dsl-for-zkapps/)
- [Measuring SNARK performance: Frontends, backends, and the future](https://a16zcrypto.com/measuring-snark-performance-frontends-backends-and-the-future/)
- [The Problem of Scalable Privacy](https://neptune.cash/blog/scalable-privacy-problem/)
- Tutorial: [BrainSTARK](https://aszepieniec.github.io/stark-brainfuck/)
- [Decentralized Application (dApp) Blockchain Tutorials (NEAR,Solana,Substrate)](https://github.com/elicorrales/blockchain-tutorials)
- [Sin7Y Tech Review(29): Design Principles of Private Transactions in Aleo & Zcash](https://hackmd.io/@sin7y/rkxFXLkgs)
- [The different types of ZK-EVMs](https://vitalik.eth.limo/general/2022/08/04/zkevm.html)
- [How consensus and data availability impact decentralized scalability of blockchains](https://kabat.substack.com/p/how-consensus-and-data-availability)
- [On-chain trusted setup ceremony](https://a16zcrypto.com/on-chain-trusted-setup-ceremony/)

#### Papers

- [The inspection model for zero-knowledge proofs and efficient Zerocash with secp256k1 keys](https://eprint.iacr.org/2022/1079)
- [Orbis Specification Language: a type theory for zk-SNARK programming](https://eprint.iacr.org/2022/1003)
- [Orion: Zero Knowledge Proof with Linear Prover Time](https://eprint.iacr.org/2022/1010)
- [Zswap: zk-SNARK Based Non-Interactive Multi-Asset Swaps](https://eprint.iacr.org/2022/1002)
- [PESCA: A Privacy-Enhancing Smart-Contract Architecture](https://eprint.iacr.org/2022/1119)
- [Paras - A Private NFT Protocol](https://eprint.iacr.org/2022/976)
- [Pikachu: Securing PoS Blockchains from Long-Range Attacks by Checkpointing into Bitcoin PoW using Taproot](https://arxiv.org/abs/2208.05408)

#### Projects

- [Open TSS](https://github.com/LatticeX-Foundation/opentss).
  An ECDSA threshold signature algorithm implemented in Rust.
- [Triton VM](https://github.com/TritonVM/triton-vm).
  A virtual machine that comes with Algebraic Execution Tables (AET)
  and Arithmetic Intermediate Representations (AIR) for use in
  combination with a STARK proof system.
- [Bundle Generator](https://github.com/Alcibiades-Capital/mev_bundle_generator).
  An MEV bundle generator written in Rust.
- [Plonky2 & more](https://github.com/mir-protocol/plonky2).
  A SNARK implementation based on techniques from PLONK and FRI.
- [Automerge RS](https://github.com/automerge/automerge-rs).
  Rust implementation of Automerge, the conflict free replicated datatype (CRDT) system.
- [Zero-Knowledge University](https://zku.one/)

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

- [RUSTSEC-2022-0045: `oqs` - Post-Quantum Key Encapsulation Mechanism SIKE broken](https://rustsec.org/advisories/RUSTSEC-2022-0045.html).
- [RUSTSEC-2022-0050: `interledger-packet` is unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0050.html).
  - interledger-rs appears to be no more.
- [RUSTSEC-2022-0049: `iana-time-zone` - Use after free in MacOS / iOS implementation](https://rustsec.org/advisories/RUSTSEC-2022-0049.html).
- [RUSTSEC-2022-0053: `mapr` is unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0053.html).
- **[RUSTSEC-2022-0051: `lz4-sys` vulnerability in lz4-sys](https://rustsec.org/advisories/RUSTSEC-2022-0051.html).**
- [RUSTSEC-2022-0052: `os_socketaddr` unsoundness](https://rustsec.org/advisories/RUSTSEC-2022-0052.html).
- [CVE-2022-36124: `apache-avro` - Apache Avro Rust SDK's Reader could consume memory beyond allowed constraints](https://github.com/advisories/GHSA-wcm8-86x6-8mv3).
- [CVE-2022-35724: `apache-avro` - Apache Avro Rust SDK vulnerable to reader looping in cycle endlessly, consuming CPU](https://github.com/advisories/GHSA-v456-chpw-6mmw).
- [CVE-2022-36125: `apache-avro` - Apache Avro Rust SDK corrupted data read can cause crash](https://github.com/advisories/GHSA-3w5g-989p-35r8).
- **[GHSA-9qxh-258v-666c: `owning_ref` - multiple soundness issues](https://github.com/advisories/GHSA-9qxh-258v-666c).**
  - This popular crate appears to be completely unsound and should not be used.
- [GHSA-qrqq-9c63-xfrg: `tower-http` - tower-http's improper validation of Windows paths could lead to directory traversal attack](https://github.com/advisories/GHSA-qrqq-9c63-xfrg).
- [GHSA-2jq9-6xx7-3h29: `temporary` - uninitialized memory](https://github.com/advisories/GHSA-2jq9-6xx7-3h29).
- **[GHSA-xpp3-xrff-w6rh: `rust-rocksdb` - out-of-bounds read](https://github.com/advisories/GHSA-xpp3-xrff-w6rh).**
- [GHSA-h864-m8vm-3xvj: oqs's Post-Quantum Signature scheme Rainbow level I parametersets broken](https://github.com/advisories/GHSA-h864-m8vm-3xvj).
- [CVE-2022-36008: `frontier` - Incorrect parsing of EVM reversion exit reason in RPC](https://github.com/advisories/GHSA-mjvm-mhgc-q4gp).
- [CVE-2022-25888: `opcua` - Uncontrolled Resource Consumption in opcua](https://github.com/advisories/GHSA-8mx2-gqx9-rm7f).
- [CVE-2022-25903: `opcua` - opcua Vulnerable to Out-of-bounds Write](https://github.com/advisories/GHSA-hgxq-hcrm-c5pm).

&nbsp;

## Most Active in August

[Aptos](https://github.com/aptos-labs):
888 merged PRs,
174 closed issues,
90 open issues

[Solana](https://github.com/solana-labs/solana):
502 merged PRs,
86 closed issues,
91 open issues

[Sui](https://github.com/MystenLabs):
452 merged PRs,
211 closed issues,
204 open issues

[Parity](https://github.com/paritytech):
439 merged PRs,
209 closed issues,
135 open issues

[Fuel](https://github.com/FuelLabs):
253 merged PRs,
193 closed issues,
139 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

111 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
28 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]),
25 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[aleo-closed_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Anoma](https://github.com/anoma)

1 merged PRs ([1][anoma-merged-prs-1]),
0 closed issues,
0 open issues

[anoma-merged-prs-1]: https://github.com/anoma/ferveo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31

#### [Aptos](https://github.com/aptos-labs)

888 merged PRs ([1][aptos-merged-prs-1]),
174 closed issues ([1][aptos-closed_issues-1]),
90 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Casper](https://github.com/casper-network)

50 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
64 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
41 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [ChainSafe](https://github.com/ChainSafe)

61 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]),
52 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2]),
16 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/mina-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [COMIT](https://github.com/comit-network)

9 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2]),
13 closed issues ([1][comit-closed_issues-1]),
3 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2])

[comit-merged-prs-1]: https://github.com/comit-network/maia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[comit-open_issues-1]: https://github.com/comit-network/maia/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[comit-open_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Concordium](https://github.com/Concordium)

69 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7], [8][concordium-merged-prs-8]),
36 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4], [5][concordium-closed_issues-5], [6][concordium-closed_issues-6]),
13 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-use-case-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-merged-prs-8]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[concordium-closed_issues-5]: https://github.com/Concordium/concordium-use-case-examples/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[concordium-closed_issues-6]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Conflux](https://github.com/Conflux-Chain)

3 merged PRs ([1][conflux-merged-prs-1]),
0 closed issues,
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31

#### [DarkFi](https://dark.fi)

2 merged PRs ([1][darkfi-merged-prs-1]),
4 closed issues ([1][darkfi-closed_issues-1]),
2 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Dfinity](https://github.com/dfinity)

144 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7], [8][dfinity-merged-prs-8]),
18 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5]),
17 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-merged-prs-3]: https://github.com/dfinity/icx-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-merged-prs-4]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-merged-prs-5]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-merged-prs-6]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-merged-prs-7]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-merged-prs-8]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[dfinity-closed_issues-2]: https://github.com/dfinity/icx-proxy/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[dfinity-closed_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[dfinity-closed_issues-5]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[dfinity-open_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[dfinity-open_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [BTC<>ICP Integration Beta Release: The Bitcoin Testnet API Is Now Available](https://medium.com/dfinity/btc-icp-integration-beta-release-the-bitcoin-testnet-api-is-now-available-bab84c378c1e)
- [IC Internals: The XNet Protocol for Subnets](https://medium.com/dfinity/ic-internals-the-xnet-protocol-for-subnets-c4035dac7d2c)

#### [Dusk Network](https://github.com/dusk-network)

14 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3]),
10 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2]),
10 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dusk_network-merged-prs-2]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dusk_network-merged-prs-3]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[dusk_network-open_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Elrond](https://github.com/ElrondNetwork)

15 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3]),
1 closed issues ([1][elrond-closed_issues-1]),
2 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-nft-marketplace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Espresso Systems](https://github.com/EspressoSystems)

28 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5]),
20 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4]),
12 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/reef/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/cap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Filecoin](https://github.com/filecoin-project)

97 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7], [8][filecoin-merged-prs-8], [9][filecoin-merged-prs-9], [10][filecoin-merged-prs-10]),
54 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5]),
39 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4], [5][filecoin-open_issues-5])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/blstrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-2]: https://github.com/filecoin-project/bls-signatures/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-3]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-4]: https://github.com/filecoin-project/builtin-actors-bundler/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-5]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-6]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-7]: https://github.com/filecoin-project/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-8]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-9]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-merged-prs-10]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[filecoin-closed_issues-2]: https://github.com/filecoin-project/filecoin-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[filecoin-closed_issues-3]: https://github.com/filecoin-project/neptune/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[filecoin-closed_issues-4]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[filecoin-closed_issues-5]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[filecoin-open_issues-1]: https://github.com/filecoin-project/blstrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[filecoin-open_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[filecoin-open_issues-3]: https://github.com/filecoin-project/filecoin-phase2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[filecoin-open_issues-4]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[filecoin-open_issues-5]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Findora](https://github.com/FindoraNetwork)

87 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4], [5][findora-merged-prs-5]),
8 closed issues ([1][findora-closed_issues-1]),
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[findora-merged-prs-2]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[findora-merged-prs-3]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[findora-merged-prs-4]: https://github.com/FindoraNetwork/findora-exporter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[findora-merged-prs-5]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31

#### [Fluence](https://github.com/fluencelabs)

32 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6]),
2 closed issues ([1][fluence-closed_issues-1]),
3 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fluence-merged-prs-6]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fluence-open_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fluence-open_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fluence-open_issues-3]: https://github.com/fluencelabs/examples/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Fuel](https://github.com/FuelLabs)

253 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12]),
193 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8], [9][fuel-closed_issues-9], [10][fuel-closed_issues-10], [11][fuel-closed_issues-11]),
139 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8], [9][fuel-open_issues-9])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-11]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-merged-prs-12]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[fuel-closed_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-2]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-crypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-8]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-9]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-10]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-closed_issues-11]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[fuel-open_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-7]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-8]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[fuel-open_issues-9]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Golem](https://github.com/golemfactory)

27 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4]),
47 closed issues ([1][golem-closed_issues-1]),
21 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3], [4][golem-open_issues-4])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[golem-merged-prs-2]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[golem-merged-prs-3]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[golem-merged-prs-4]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[golem-open_issues-1]: https://github.com/golemfactory/ya-runtime-http-auth/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[golem-open_issues-2]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[golem-open_issues-3]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[golem-open_issues-4]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Grin](https://github.com/mimblewimble/grin)

1 merged PRs ([1][grin-merged-prs-1]),
0 closed issues,
1 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Helium](https://github.com/helium)

12 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4], [5][helium-merged-prs-5]),
16 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
5 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[helium-merged-prs-3]: https://github.com/helium/virtual-lorawan-device/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[helium-merged-prs-4]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[helium-merged-prs-5]: https://github.com/helium/helium-api-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[helium-closed_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[helium-open_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Holochain](https://github.com/holochain/)

31 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]),
7 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
2 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[holochain-merged-prs-3]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [IOTA](https://github.com/iotaledger)

142 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6], [7][iota-merged-prs-7]),
39 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5]),
19 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4], [5][iota-open_issues-5], [6][iota-open_issues-6])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[iota-merged-prs-5]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[iota-merged-prs-6]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[iota-merged-prs-7]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[iota-closed_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[iota-closed_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[iota-closed_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[iota-closed_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[iota-closed_issues-5]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[iota-open_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[iota-open_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[iota-open_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[iota-open_issues-5]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[iota-open_issues-6]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Maidsafe](https://github.com/maidsafe)

96 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4]),
1 closed issues ([1][maidsafe-closed_issues-1]),
5 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[maidsafe-merged-prs-3]: https://github.com/maidsafe/bls_dkg/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[maidsafe-merged-prs-4]: https://github.com/maidsafe/self_encryption/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[maidsafe-open_issues-2]: https://github.com/maidsafe/qp2p/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [MobileCoin](https://github.com/mobilecoinfoundation)

34 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
7 closed issues ([1][mobilecoin-closed_issues-1]),
22 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

216 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8]),
51 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5]),
30 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-merged-prs-5]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-merged-prs-6]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-merged-prs-7]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-merged-prs-8]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[near-closed_issues-4]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[near-closed_issues-5]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[near-open_issues-4]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[near-open_issues-5]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[near-open_issues-6]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Nervos](https://github.com/nervosnetwork)

67 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8], [9][nervos-merged-prs-9]),
7 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4], [5][nervos-closed_issues-5]),
5 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/godwoken-scripts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/mercury/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-6]: https://github.com/nervosnetwork/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-7]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-8]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-merged-prs-9]: https://github.com/nervosnetwork/ckb-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[nervos-closed_issues-3]: https://github.com/nervosnetwork/godwoken-scripts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[nervos-closed_issues-4]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[nervos-closed_issues-5]: https://github.com/nervosnetwork/ckb-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[nervos-open_issues-3]: https://github.com/nervosnetwork/godwoken-tests/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Oasis](https://github.com/oasisprotocol)

14 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]),
1 closed issues ([1][oasis-closed_issues-1]),
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[oasis-merged-prs-2]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31

#### [Parity](https://github.com/paritytech)

439 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15]),
209 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13], [14][parity-closed_issues-14], [15][parity-closed_issues-15]),
135 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-13]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-14]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-merged-prs-15]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-13]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-14]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-closed_issues-15]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[parity-open_issues-13]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Radix](https://github.com/radixdlt)

76 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3]),
3 closed issues ([1][radix-closed_issues-1]),
2 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[radix-merged-prs-2]: https://github.com/radixdlt/scrypto-challenges/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

44 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]),
41 closed issues ([1][secret_network-closed_issues-1]),
4 open issues ([1][secret_network-open_issues-1], [2][secret_network-open_issues-2])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[secret_network-open_issues-2]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [Beyond ZK: The Definitive Guide to Web3 Privacy (Part 1)](https://scrt.network/blog/beyond-zk-guide-to-web3-privacy-part-1)
- [Secret Deep Dive: Unlocking Web3 Streaming with Secret NFTs](https://scrt.network/blog/secret-deep-dive-unlocking-web3-movies-with-secret-nfts)

#### [Solana](https://github.com/solana-labs/solana)

502 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]),
86 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
91 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [Monthly Community Update | August 2022](https://solana.com/news/monthly-community-update-august-2022)
- [Validator Health Report: August 2022](https://solana.com/news/validator-health-report-august-2022)
- [8/2/2022 Slope Wallet Incident Update](https://solana.com/news/8-2-2022-application-wallet-incident)

#### [Subspace Labs](https://github.com/subspace)

46 merged PRs ([1][subspace_labs-merged-prs-1]),
16 closed issues ([1][subspace_labs-closed_issues-1]),
3 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Sui](https://github.com/MystenLabs)

452 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2]),
211 closed issues ([1][sui-closed_issues-1], [2][sui-closed_issues-2]),
204 open issues ([1][sui-open_issues-1], [2][sui-open_issues-2])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[sui-merged-prs-2]: https://github.com/MystenLabs/narwhal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[sui-closed_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[sui-open_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Zcash](https://github.com/zcash)

62 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4]),
66 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]),
30 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4], [5][zcash-open_issues-5])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[zcash-closed_issues-3]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[zcash-open_issues-5]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

&nbsp;

### Rust in Bitcoin

Lots of activity in BDK and LDK this week. Be sure to scroll down to their respective sections for links to details on the new developments. LNP/BP also did a number of talks recently, but no recordings have been published yet. Also, rust-bitcoin 0.29 was released, with BIP-152 support, and it's now using Rust 2018 and enables clippy support in CI, which will make it easier to make contributions in the future.

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

45 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4], [5][bdk-merged-prs-5]),
19 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3], [4][bdk-closed_issues-4]),
25 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[bdk-merged-prs-5]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[bdk-closed_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [BDK 0.21 is out](https://twitter.com/bitcoindevkit/status/1558113984028491784)
- [Summer of Bitcoin - Improving coin selection in BDK](https://blog.summerofbitcoin.org/improving-coin-selection-bdk/)
- [Verify signatures after creating them (BIP 340)](https://github.com/bitcoindevkit/bdk/pull/718)
- [Separate balances by pending / maturity](https://github.com/bitcoindevkit/bdk/pull/640)
- [Specify Taproot spend paths](https://github.com/bitcoindevkit/bdk/pull/645)
- [Add method to override dust limit](https://github.com/bitcoindevkit/bdk/issues/689)
- [Add hardware wallet support](https://github.com/bitcoindevkit/bdk/pull/682)

#### [Bitmask](https://github.com/diba-io/bitmask-core)

4 merged PRs ([1][bitmask-merged-prs-1]),
0 closed issues,
0 open issues

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31

#### [Electrs](https://github.com/romanz/electrs)

3 merged PRs ([1][electrs-merged-prs-1]),
2 closed issues ([1][electrs-closed_issues-1]),
4 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Internet2](https://github.com/internet2-wg/)

0 merged PRs,
0 closed issues,
1 open issues ([1][internet2-open_issues-1])

[internet2-open_issues-1]: https://github.com/Internet2-WG/rust-internet2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

29 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
8 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
16 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [Announcing Rapid Gossip Sync](https://twitter.com/lightningdevkit/status/1564689476059906050)
- [Onion Messages with Reply Paths](https://github.com/lightningdevkit/rust-lightning/pull/1652)

#### [LNP/BP](https://github.com/LNP-BP)

0 merged PRs,
0 closed issues,
1 open issues ([1][lnp/bp-open_issues-1])

[lnp/bp-open_issues-1]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [Presentation at Baltic Honey Badger 2022](https://twitter.com/lnp_bp/status/1566116669415739392)

#### [LNP WG](https://github.com/LNP-WG)

0 merged PRs,
1 closed issues ([1][lnp_wg-closed_issues-1]),
0 open issues

[lnp_wg-closed_issues-1]: https://github.com/LNP-WG/lnp-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

3 merged PRs ([1][nakamoto-merged-prs-1]),
0 closed issues,
1 open issues ([1][nakamoto-open_issues-1])

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nakamoto-open_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Nomic](https://github.com/nomic-io)

9 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]),
2 closed issues ([1][nomic-closed_issues-1], [2][nomic-closed_issues-2]),
3 open issues ([1][nomic-open_issues-1], [2][nomic-open_issues-2])

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nomic-merged-prs-2]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[nomic-closed_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[nomic-closed_issues-2]: https://github.com/nomic-io/orga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[nomic-open_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[nomic-open_issues-2]: https://github.com/nomic-io/merk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [RGB](https://github.com/rgb-wg)

2 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2]),
0 closed issues,
2 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[rgb-open_issues-2]: https://github.com/RGB-WG/rust-rgb20/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

34 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
15 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]),
29 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [rust-bitcoin 0.29 released](https://github.com/rust-bitcoin/rust-bitcoin/blob/110b5d89630d705e5d5ed0541230923eb4fc600f/CHANGELOG.md#029---2022-07-20-edition-2018-release)

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

4 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31

#### [Sapio](https://github.com/sapio-lang/sapio)

1 merged PRs ([1][sapio-merged-prs-1]),
0 closed issues,
0 open issues

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31

#### [Talaia](https://github.com/talaia-labs/rust-teos)

12 merged PRs ([1][talaia-merged-prs-1]),
10 closed issues ([1][talaia-closed_issues-1]),
7 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

74 merged PRs ([1][ethers-rs-merged-prs-1]),
13 closed issues ([1][ethers-rs-closed_issues-1]),
2 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Foundry](https://github.com/foundry-rs/foundry)

243 merged PRs ([1][foundry-merged-prs-1]),
243 closed issues ([1][foundry-closed_issues-1]),
72 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

4 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
26 closed issues ([1][lighthouse-closed_issues-1]),
37 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [Merge Migration](https://lighthouse-book.sigmaprime.io/merge-migration.html)
- [High-priority release: Unity](https://github.com/sigp/lighthouse/releases/tag/v3.1.0)
- [High-priority release: Rick Prime](https://github.com/sigp/lighthouse/releases/tag/v3.0.0)

#### [Rust Ethereum](https://github.com/rust-ethereum)

3 merged PRs ([1][rust_ethereum-merged-prs-1], [2][rust_ethereum-merged-prs-2]),
0 closed issues,
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[rust_ethereum-merged-prs-2]: https://github.com/rust-ethereum/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

0 merged PRs,
0 closed issues,
1 open issues ([1][rust_web3-open_issues-1])

[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

#### [zkSync](https://github.com/matter-labs/zksync)

10 merged PRs ([1][zksync-merged-prs-1]),
2 closed issues ([1][zksync-closed_issues-1]),
2 open issues ([1][zksync-open_issues-1])

[zksync-merged-prs-1]: https://github.com/matter-labs/compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-08-01..2022-08-31
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-08-01..2022-08-31
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2022-08-01..2022-08-31

- [Project Registration Is Now Open for zkSync 2.0 Mainnet Alpha](https://blog.matter-labs.io/project-registration-is-now-open-for-zksync-2-0-mainnet-alpha-43616acd422d)
- [zkSync 2.0 Update: Dynamic Fees Milestone Completed](https://blog.matter-labs.io/zksync-2-0-update-dynamic-fees-milestone-completed-c6620a3d2618)
- [The Ethereum Merge: How It Affects zkSync](https://blog.matter-labs.io/the-ethereum-merge-how-it-affects-zksync-ba3f00b8542b)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Sep 2-28 | Online

[ETHGlobal Hackathon](https://online.ethglobal.com/)

Sep 12-14 | Radialsystem, Berlin

[Developer Conference for Ethereum Infrastructure and Dapps](https://www.dappcon.io/)

Sep 11-14 | Lisbon, Portugal

[NEARCON](https://nearcon.org/)

Sep 15 | Berlin, Germany

[zkSummit 8](https://www.zksummit.com/)

Sep 18-21 | Leuven, Belgium

[CHES 2022](https://ches.iacr.org/2022/registration.php)

Sep 28-29 | Online, NYC, US

[SmartCon 2022](https://smartcon.chain.link/)

Sep 30 - Oct 2 | Berlin, Germany

[RustFi Hackathon](https://rustfi.keyrock.com/)

Oct 7-16 | Bogota, Colombia

[Devcon Week](https://devcon.org/)

Oct 28-30 | Lisbon, Portugal

[ETH Lisbon](https://www.ethlisbon.org/)

Nov 3 | San Francisco, USA

[Ethereum hackathon: ETH San Francisco 2022](https://nftevening.com/event/eth-san-francisco-2022-san-francisco/)

Nov 7-10 | Chicago, USA

[TCC 2022](https://tcc.iacr.org/2022/)

Nov 10-11 | Dubai, United Arab Emirates

[ICSCB 2022: 16. International Conference on Smart Contracts and Blockchain](https://waset.org/smart-contracts-and-blockchain-conference-in-november-2022-in-dubai)

Nov 14-17 | Istanbul, Turkey

[Istanbul Blockchain Week](https://istanbulblockchainweek.com/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Stellar Development Foundation | USA / CAN / Remote
- [Senior Engineering Manager, Smart Contracts](https://boards.greenhouse.io/stellar/jobs/4606832004)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain
