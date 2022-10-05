---
title: "RiB Newsletter #40"
description: "September 2022"
date: 2022-10-05
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #40 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #39](/newsletters/rib-newsletter-39/).

&nbsp;

## Thanks

Thanks to contributors:
[Christopher Goes],
[dandanlen],
[djddo],
[Hadi Hosseini],
Mike C,

_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Christopher Goes]: https://github.com/cwgoes
[dandanlen]: https://github.com/dandanlen
[djddo]: https://github.com/djddo
[Hadi Hosseini]: https://github.com/perlish
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News

- [Wormhole Bug Bounty Pre-Release Program Launch](https://wormholecrypto.medium.com/wormhole-bug-bounty-pre-release-program-launch-143dc4c370e2)

#### Blog Posts

- [Smart Contract Development — Move vs. Rust](https://medium.com/@kklas/smart-contract-development-move-vs-rust-4d8f84754a8f)
- [First impressions of the Move programming language](https://brson.github.io/2022/09/21/move-impressions)
- [Sin7Y Tech Review(30):Thoughts on removing Memory constraints in the ZKEVM](https://hackmd.io/@sin7y/S1Hb6FOej)
- [Ed25519 Deep Dive Addendum](https://cendyne.dev/posts/2022-09-11-ed25519-deep-dive-addendum.html)
- [Zero Knowledge Canon, part 1 & 2](https://a16zcrypto.com/zero-knowledge-canon/)
- [Area-52: Save the Cosmos While Learning CosmWasm and Rust Smart Contracts](https://blog.archway.io/area-52-save-the-cosmos-1c013d529cbb)
- [Execution and Parallelism for DAG-Based BFT Consensus](https://blog.chain.link/execution-and-parallelism-for-dag-based-bft-consensus/)
- [BFT on a DAG](https://blog.chain.link/bft-on-a-dag/)
- [ZK White Paper: Efficient ZK Proofs for Keccak](https://blog.polygon.technology/zk-white-paper-efficient-zk-proofs-for-keccak/)
- [SNARK Security and Performance](https://a16zcrypto.com/snark-security-and-performance/)
- [Trustless Bridging II: Byzantine Fault Tolerance](https://medium.com/composable-finance/trustless-bridging-ii-byzantine-fault-tolerance-591e8b2d196e)
- [The Rise of Fully Homomorphic Encryption](https://queue.acm.org/detail.cfm?id=3561800)

#### Papers

- [RedShift: Transparent SNARKs from List Polynomial Commitments](https://eprint.iacr.org/2019/1400)
- [Accountable Light Client Systems for PoS Blockchains](https://eprint.iacr.org/2022/1205)
- [Arithmetization of Functional Program Execution via Interaction Nets in Halo 2](https://eprint.iacr.org/2022/1211)
- [Knowledge Encryption and Its Applications to Simulatable Protocols With Low Round-Complexity](https://eprint.iacr.org/2022/1193)
- [Maximal Extractable Value (MEV) Protection on a DAG](https://arxiv.org/abs/2208.00940)
- [No More Attacks on Proof-of-Stake Ethereum?](https://eprint.iacr.org/2022/1171)
- [Efficient Proofs of Software Exploitability for Real-world Processors](https://eprint.iacr.org/2022/1223)
- [Flashproofs: Efficient Zero-Knowledge Arguments of Range and Polynomial Evaluation with Transparent Setup](https://eprint.iacr.org/2022/1251)
- [An ECDSA Nullifier Scheme for Unique Pseudonymity within Zero Knowledge Proofs](https://eprint.iacr.org/2022/1255)
- [zkBridge: Trustless Cross-chain Bridges Made Practical](https://rdi.berkeley.edu/zkp/zkBridge/zkBridge.html)
- [ZEBRA: Anonymous Credentials with Practical On-chain Verification and Applications to KYC in DeFi](https://eprint.iacr.org/2022/1286)
- [Bool Network: An Open, Distributed, Secure Cross-chain Notary Platform](https://eprint.iacr.org/2022/1290)


#### Projects

- [Triton VM](https://github.com/TritonVM/triton-vm).
  A virtual machine that comes with Algebraic Execution Tables (AET)
  and Arithmetic Intermediate Representations (AIR) for use in
  combination with a STARK proof system.
- [Taiga](https://github.com/anoma/taiga).
  A framework for generalized shielded state transitions.
- [Circomspect](https://github.com/trailofbits/circomspect).
  A static analyzer and linter for the Circom programming language.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

<!-- https://github.com/rustsec/advisory-db/pulls -->

- **[RUSTSEC-2022-0054: `wee_alloc` - Unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0054.html).**
  - This allocator has often been used for wasm targets.
    It has memory leaks.
    Modern Rust uses [`dlmalloc-rs`](https://github.com/alexcrichton/dlmalloc-rs) by default on wasm and is fine for most purposes.
- [RUSTSEC-2022-0055: `axum-core` - Vulnerability in axum-core](https://rustsec.org/advisories/RUSTSEC-2022-0055.html).
- [RUSTSEC-2022-0056: `clipboard` - Unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0056.html).
- [RUSTSEC-2022-0057: `badge` - Unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0057.html).
- [CVE-2022-36114: `cargo` - Cargo extracting malicious crates can fill the file system](https://github.com/advisories/GHSA-2hvr-h6gw-qrxp).
- [CVE-2022-36113: `cargo` - Cargo extracting malicious crates can corrupt arbitrary files](https://github.com/advisories/GHSA-rfj2-q3h3-hm5j).
- [CVE-2022-36086: `linked_list_allocator` - Vulnerable to out-of-bound writes on `Heap` initialization and `Heap::extend`](https://github.com/advisories/GHSA-xg8p-34w2-j49j).
- [CVE-2022-39215: `tauri` - readDir Endpoint Scope can be Bypassed With Symbolic Links](https://github.com/advisories/GHSA-28m8-9j7v-x499).
- [GHSA-v8gq-5grq-9728: `mozjpeg` - DecompressScanlines::read_scanlines is Unsound](https://github.com/advisories/GHSA-v8gq-5grq-9728).
- [GHSA-p75v-367r-2v23: `cell-project` - used incorrect variance when projecting through `&Cell<T>`](https://github.com/advisories/GHSA-p75v-367r-2v23).
- **[CVE-2022-39974: `wasm3` - WASM3 Improper Input Validation vulnerability](https://github.com/advisories/GHSA-crf8-h2wq-2h9x).**
- [GHSA-28r9-pq4c-wp3c: `personnummer` - vulnerable to Improper Input Validation](https://github.com/advisories/GHSA-28r9-pq4c-wp3c).
- [CVE-2022-39252: `matrix-sdk-crypto` - Contains potential impersonation via room key forward responses](https://github.com/advisories/GHSA-vp68-2wrm-69qm).


&nbsp;

## Most Active in September

[Aptos](https://github.com/aptos-labs):
725 merged PRs,
117 closed issues,
27 open issues

[Parity](https://github.com/paritytech):
459 merged PRs,
175 closed issues,
150 open issues

[Solana](https://github.com/solana-labs/solana):
429 merged PRs,
63 closed issues,
73 open issues

[Sui](https://github.com/MystenLabs):
332 merged PRs,
84 closed issues,
103 open issues

[Fuel](https://github.com/FuelLabs):
283 merged PRs,
190 closed issues,
146 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

76 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
41 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]),
42 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[aleo-closed_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Anoma](https://github.com/anoma)

45 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2]),
20 closed issues ([1][anoma-closed_issues-1]),
54 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[anoma-merged-prs-2]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[anoma-open_issues-2]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Aptos](https://github.com/aptos-labs)

725 merged PRs ([1][aptos-merged-prs-1]),
117 closed issues ([1][aptos-closed_issues-1]),
27 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Casper](https://github.com/casper-network)

37 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
44 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
14 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [ChainSafe](https://github.com/ChainSafe)

74 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]),
38 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2]),
27 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/mina-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [How Does The Mina Protocol Achieve Consensus?](https://blog.chainsafe.io/how-does-the-mina-protocol-achieve-consensus-f9551675048d)

#### [COMIT](https://github.com/comit-network)

4 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2]),
0 closed issues,
0 open issues

[comit-merged-prs-1]: https://github.com/comit-network/maia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30

#### [Concordium](https://github.com/Concordium)

62 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
27 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]),
13 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[concordium-open_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Conflux](https://github.com/Conflux-Chain)

13 merged PRs ([1][conflux-merged-prs-1]),
1 closed issues ([1][conflux-closed_issues-1]),
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [DarkFi](https://dark.fi)

5 merged PRs ([1][darkfi-merged-prs-1]),
4 closed issues ([1][darkfi-closed_issues-1]),
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30

#### [Dfinity](https://github.com/dfinity)

94 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7]),
11 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]),
7 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4], [5][dfinity-open_issues-5])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dfinity-merged-prs-3]: https://github.com/dfinity/icx-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dfinity-merged-prs-4]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dfinity-merged-prs-5]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dfinity-merged-prs-6]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dfinity-merged-prs-7]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[dfinity-closed_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[dfinity-open_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[dfinity-open_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[dfinity-open_issues-5]: https://github.com/dfinity/experimental-minting-tool/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [Good Practices for Canister Smart Contract Development in Motoko](https://medium.com/dfinity/good-practices-for-canister-smart-contract-development-in-motoko-c0b0713eee42)
- [Beyond Oracles: Direct HTTPS Outcalls From Canister Smart Contracts on the Internet Computer](https://medium.com/dfinity/beyond-oracles-direct-https-outcalls-from-canister-smart-contracts-on-the-internet-computer-2e4a5bcbee43)

#### [Dusk Network](https://github.com/dusk-network)

21 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5], [6][dusk_network-merged-prs-6]),
17 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3]),
6 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/microkelvin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dusk_network-merged-prs-2]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dusk_network-merged-prs-3]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dusk_network-merged-prs-4]: https://github.com/dusk-network/rusk-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dusk_network-merged-prs-5]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dusk_network-merged-prs-6]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[dusk_network-closed_issues-3]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[dusk_network-open_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Elrond](https://github.com/ElrondNetwork)

42 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2]),
0 closed issues,
1 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Espresso Systems](https://github.com/EspressoSystems)

11 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3]),
16 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3]),
6 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/reef/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Filecoin](https://github.com/filecoin-project)

129 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7]),
55 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4]),
59 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4], [5][filecoin-open_issues-5])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/blstrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[filecoin-merged-prs-2]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[filecoin-merged-prs-3]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[filecoin-merged-prs-4]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[filecoin-merged-prs-5]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[filecoin-merged-prs-7]: https://github.com/filecoin-project/rust-gpu-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[filecoin-closed_issues-1]: https://github.com/filecoin-project/bls-signatures/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[filecoin-closed_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[filecoin-closed_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[filecoin-closed_issues-4]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[filecoin-open_issues-1]: https://github.com/filecoin-project/bls-signatures/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[filecoin-open_issues-2]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[filecoin-open_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[filecoin-open_issues-4]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[filecoin-open_issues-5]: https://github.com/filecoin-project/rust-gpu-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Findora](https://github.com/FindoraNetwork)

43 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3]),
1 closed issues ([1][findora-closed_issues-1]),
2 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[findora-merged-prs-3]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [Release v0.3.30 Is on Anvil Testnet](https://medium.com/findorafoundation/findora-increases-decentralization-fdfd8a49cfc4)

#### [Fluence](https://github.com/fluencelabs)

82 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6]),
11 closed issues ([1][fluence-closed_issues-1]),
2 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fluence-merged-prs-6]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fluence-open_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fluence-open_issues-2]: https://github.com/fluencelabs/rust-peer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Fuel](https://github.com/FuelLabs)

283 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12], [13][fuel-merged-prs-13]),
190 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8], [9][fuel-closed_issues-9], [10][fuel-closed_issues-10], [11][fuel-closed_issues-11]),
146 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8], [9][fuel-open_issues-9])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-11]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-12]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-merged-prs-13]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-crypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-8]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-9]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-10]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-closed_issues-11]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[fuel-open_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-7]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-8]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[fuel-open_issues-9]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Golem](https://github.com/golemfactory)

22 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5], [6][golem-merged-prs-6]),
25 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3], [4][golem-closed_issues-4], [5][golem-closed_issues-5]),
25 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3], [4][golem-open_issues-4])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[golem-merged-prs-2]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[golem-merged-prs-3]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[golem-merged-prs-4]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[golem-merged-prs-5]: https://github.com/golemfactory/ya-runtime-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[golem-merged-prs-6]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[golem-closed_issues-1]: https://github.com/golemfactory/ya-runtime-http-auth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[golem-closed_issues-2]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[golem-closed_issues-3]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[golem-closed_issues-4]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[golem-closed_issues-5]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[golem-open_issues-2]: https://github.com/golemfactory/ya-service-bus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[golem-open_issues-3]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[golem-open_issues-4]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Grin](https://github.com/mimblewimble/grin)

1 merged PRs ([1][grin-merged-prs-1]),
2 closed issues ([1][grin-closed_issues-1]),
2 open issues ([1][grin-open_issues-1], [2][grin-open_issues-2])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[grin-open_issues-2]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Helium](https://github.com/helium)

14 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]),
8 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
2 open issues ([1][helium-open_issues-1])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[helium-merged-prs-3]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[helium-merged-prs-4]: https://github.com/helium/helium-api-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[helium-closed_issues-2]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Holochain](https://github.com/holochain/)

48 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]),
7 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
16 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [Gossip Performance Improvements](https://blog.holochain.org/gossip-performance-improvements/)

#### [IOTA](https://github.com/iotaledger)

205 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6], [7][iota-merged-prs-7], [8][iota-merged-prs-8]),
71 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5]),
21 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4], [5][iota-open_issues-5])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-merged-prs-5]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-merged-prs-6]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-merged-prs-7]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-merged-prs-8]: https://github.com/iotaledger/chronicle.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[iota-closed_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[iota-closed_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[iota-closed_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[iota-closed_issues-4]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[iota-closed_issues-5]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[iota-open_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[iota-open_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[iota-open_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[iota-open_issues-5]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Maidsafe](https://github.com/maidsafe)

51 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3]),
1 closed issues ([1][maidsafe-closed_issues-1]),
0 open issues

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30

#### [MobileCoin](https://github.com/mobilecoinfoundation)

64 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
9 closed issues ([1][mobilecoin-closed_issues-1]),
16 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [NEAR](https://github.com/nearprotocol/nearcore)

194 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10]),
92 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6]),
52 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-6]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-7]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-8]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-9]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-merged-prs-10]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[near-closed_issues-5]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[near-closed_issues-6]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[near-open_issues-5]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[near-open_issues-6]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[near-open_issues-7]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[near-open_issues-8]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Nervos](https://github.com/nervosnetwork)

55 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8]),
10 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4], [5][nervos-closed_issues-5]),
9 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4], [5][nervos-open_issues-5])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-merged-prs-3]: https://github.com/nervosnetwork/godwoken-scripts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-merged-prs-4]: https://github.com/nervosnetwork/mercury/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-merged-prs-6]: https://github.com/nervosnetwork/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-merged-prs-7]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-merged-prs-8]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[nervos-closed_issues-3]: https://github.com/nervosnetwork/mercury/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[nervos-closed_issues-4]: https://github.com/nervosnetwork/godwoken-tests/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[nervos-closed_issues-5]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[nervos-open_issues-2]: https://github.com/nervosnetwork/mercury/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[nervos-open_issues-4]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[nervos-open_issues-5]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [A Journey to the Absolute Limit: CKB-VM's LLVM AOT engine](https://xuejie.space/2022_09_08_a_journey_to_the_limit/)

#### [Oasis](https://github.com/oasisprotocol)

9 merged PRs ([1][oasis-merged-prs-1]),
1 closed issues ([1][oasis-closed_issues-1]),
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30

#### [Parity](https://github.com/paritytech)

459 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15]),
175 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13]),
150 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-13]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-14]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-merged-prs-15]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-12]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-closed_issues-13]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[parity-open_issues-13]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [Polkadot Roadmap Roundup](https://medium.com/polkadot-network/polkadot-roadmap-roundup-4ee64577a9ae)
- [Polkadot DevCamp Intake #2](https://medium.com/polkadot-network/polkadot-devcamp-intake-2-ddebc5fb9096)
- [The First KSM<>DOT Bridge](https://medium.com/composable-finance/the-first-ksm-dot-bridge-be038fdd40a0)

#### [Radix](https://github.com/radixdlt)

31 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2]),
1 closed issues ([1][radix-closed_issues-1]),
3 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[radix-merged-prs-2]: https://github.com/radixdlt/scrypto_tutorial/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

41 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]),
47 closed issues ([1][secret_network-closed_issues-1], [2][secret_network-closed_issues-2], [3][secret_network-closed_issues-3]),
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[secret_network-closed_issues-2]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[secret_network-closed_issues-3]: https://github.com/scrtlabs/snip20-reference-impl/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Solana](https://github.com/solana-labs/solana)

429 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
63 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2], [3][solana-closed_issues-3]),
73 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[solana-closed_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [Beginners guide to Solana NFTs in Rust](https://medium.com/@jacob_62353/introduction-365296716979)

#### [Subspace Labs](https://github.com/subspace)

33 merged PRs ([1][subspace_labs-merged-prs-1]),
8 closed issues ([1][subspace_labs-closed_issues-1]),
9 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

- [Gemini II Incentivized Testnet goes LIVE next week!](https://kill-the-newsletter.com/alternates/3pr8q0z6o0481nma.html)

#### [Sui](https://github.com/MystenLabs)

332 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2]),
84 closed issues ([1][sui-closed_issues-1], [2][sui-closed_issues-2]),
103 open issues ([1][sui-open_issues-1], [2][sui-open_issues-2])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[sui-merged-prs-2]: https://github.com/MystenLabs/narwhal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[sui-closed_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[sui-open_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Zcash](https://github.com/zcash)

105 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4]),
55 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]),
40 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[zcash-merged-prs-4]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

37 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4], [5][bdk-merged-prs-5]),
21 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
7 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[bdk-merged-prs-5]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Bitmask](https://github.com/diba-io/bitmask-core)

8 merged PRs ([1][bitmask-merged-prs-1]),
5 closed issues ([1][bitmask-closed_issues-1]),
2 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Electrs](https://github.com/romanz/electrs)

4 merged PRs ([1][electrs-merged-prs-1]),
0 closed issues,
1 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Internet2](https://github.com/internet2-wg/)

1 merged PRs ([1][internet2-merged-prs-1]),
1 closed issues ([1][internet2-closed_issues-1]),
1 open issues ([1][internet2-open_issues-1])

[internet2-merged-prs-1]: https://github.com/Internet2-WG/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[internet2-closed_issues-1]: https://github.com/Internet2-WG/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[internet2-open_issues-1]: https://github.com/Internet2-WG/rust-aluvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

48 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2]),
7 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
6 open issues ([1][ldk-open_issues-1])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [LNP/BP](https://github.com/LNP-BP)

0 merged PRs,
0 closed issues,
1 open issues ([1][lnp/bp-open_issues-1])

[lnp/bp-open_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [LNP WG](https://github.com/LNP-WG)

3 merged PRs ([1][lnp_wg-merged-prs-1]),
0 closed issues,
0 open issues

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30

#### [MyCitadel](https://github.com/orgs/mycitadel)

0 merged PRs,
0 closed issues,
1 open issues ([1][mycitadel-open_issues-1])

[mycitadel-open_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

3 merged PRs ([1][nakamoto-merged-prs-1]),
3 closed issues ([1][nakamoto-closed_issues-1]),
1 open issues ([1][nakamoto-open_issues-1])

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nakamoto-closed_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[nakamoto-open_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Nomic](https://github.com/nomic-io)

3 merged PRs ([1][nomic-merged-prs-1]),
0 closed issues,
2 open issues ([1][nomic-open_issues-1], [2][nomic-open_issues-2])

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[nomic-open_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[nomic-open_issues-2]: https://github.com/nomic-io/orga/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [RGB](https://github.com/rgb-wg)

8 merged PRs ([1][rgb-merged-prs-1]),
2 closed issues ([1][rgb-closed_issues-1]),
6 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[rgb-open_issues-2]: https://github.com/RGB-WG/rust-rgb20/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

55 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]),
13 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2]),
28 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5], [6][rust_bitcoin-open_issues-6])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30
[rust_bitcoin-open_issues-6]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

5 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30

#### [Sapio](https://github.com/sapio-lang/sapio)

7 merged PRs ([1][sapio-merged-prs-1]),
0 closed issues,
2 open issues ([1][sapio-open_issues-1])

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[sapio-open_issues-1]: https://github.com/sapio-lang/sapio/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Talaia](https://github.com/talaia-labs/rust-teos)

10 merged PRs ([1][talaia-merged-prs-1]),
6 closed issues ([1][talaia-closed_issues-1]),
4 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

54 merged PRs ([1][ethers-rs-merged-prs-1]),
7 closed issues ([1][ethers-rs-closed_issues-1]),
7 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Foundry](https://github.com/foundry-rs/foundry)

189 merged PRs ([1][foundry-merged-prs-1]),
145 closed issues ([1][foundry-closed_issues-1]),
60 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Lighthouse](https://github.com/sigp/lighthouse)

5 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
40 closed issues ([1][lighthouse-closed_issues-1]),
14 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Rust Ethereum](https://github.com/rust-ethereum)

0 merged PRs,
0 closed issues,
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

0 merged PRs,
0 closed issues,
3 open issues ([1][rust_web3-open_issues-1])

[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2022-09-01..2022-09-30

#### [zkSync](https://github.com/matter-labs/zksync)

9 merged PRs ([1][zksync-merged-prs-1]),
2 closed issues ([1][zksync-closed_issues-1]),
0 open issues

[zksync-merged-prs-1]: https://github.com/matter-labs/compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-09-01..2022-09-30
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-09-01..2022-09-30

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Oct 7-16 | Bogota, Colombia

[Devcon Week](https://devcon.org/)

Oct 14 - Nov 18 | Online

[Chainlink Fall 2022 Hackathon](https://chain.link/hackathon)

Oct 28-30 | Lisbon, Portugal

[ETH Lisbon](https://www.ethlisbon.org/)

Oct 31-Nov 6 | San Francisco, USA

[San Francisco Blockchain Week](https://sfblockchainweek.io/)

Nov 3 | San Francisco, USA

[Ethereum hackathon: ETH San Francisco 2022](https://nftevening.com/event/eth-san-francisco-2022-san-francisco/)

Nov 3 | San Francisco, USA

[Polkadot Summit](https://www.polkadotsummit.com/)

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

Blockstream | Remote
- [Senior Network Engineer](https://grnh.se/6ac8f7f11us)
- [Senior Product Designer](https://grnh.se/87bf94551us)

Chainflip Labs | Berlin
- [Software Engineer (Rust)](https://angel.co/company/chainflip/jobs/1644220-software-engineer-rust)
- [Blockchain Support Engineer](https://angel.co/company/chainflip/jobs/2403942-blockchain-support-engineer)
- [Ecosystem Development Manager](https://angel.co/company/chainflip/jobs/2339895-ecosystem-development-manager)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


