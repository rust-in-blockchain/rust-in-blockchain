---
title: "RiB Newsletter #44"
description: "January 2023"
date: 2023-02-01
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #44 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #43](/newsletters/rib-newsletter-43/).

&nbsp;

## Thanks

Thanks to contributors:
[camilahanada],
[gcharang],
[Kadan Stadelmann],
[Vid Kersic],
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).


[camilahanada]: https://github.com/camilahanada
[gcharang]: https://github.com/gcharang
[Kadan Stadelmann]: https://github.com/ca333
[Vid Kersic]: https://github.com/Vid201
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News


#### Blog Posts

- [Consensus canon](https://a16zcrypto.com/consensus-canon/)
- [Generating secure randomness on Ethereum using SNARKs](https://www.paradigm.xyz/2023/01/eth-rng)
- [Cross-Chain Bridge Bugs: A Growing Problem](https://halborn.com/cross-chain-bridge-bugs-a-growing-problem/)
- [Role of Aggregators and Subcommittees](https://stonecoldpat.substack.com/p/role-of-aggregators-and-subcommittees)
- [Epochs, Slots and Beacon Blocks](https://stonecoldpat.substack.com/p/epochs-slots-and-beacon-blocks)


#### Papers

- [The Tip5 Hash Function for Recursive STARKs](https://eprint.iacr.org/2023/107)

#### Projects

- [AES Encryption circuit](https://github.com/lambdaclass/AES_zero_knowledge_proof_circuit).
  ZK-Snark circuit to prove that a given ciphertext is the correct AES-128 encryption using a certain secret key.
- [TFHE-rs](https://github.com/zama-ai/tfhe-rs).
  A pure Rust implementation of TFHE for boolean and small integer arithmetics over encrypted data.
- [aa-bundler](https://github.com/Vid201/aa-bundler).
  EIP-4337 (Account Abstraction) - Bundler implementation in Rust.
- [merkle_patricia_tree](https://github.com/lambdaclass/merkle_patricia_tree).
  Patricia Merkle Tree implementation in Rust.
- [heimdall-rs](https://github.com/Jon-Becker/heimdall-rs).
  An advanced EVM toolkit which aims to make dealing with smart contracts on EVM based chains easier.
- [cosmwasm-vm](https://github.com/ComposableFi/cosmwasm-vm).
  Experimental, minimalistic, no_std friendly abstract virtual machine for CosmWasm contracts execution.
  Blog post: [How we built a generalized CosmWasm VM](https://medium.com/composable-finance/how-we-built-a-generalized-cosmwasm-vm-a0ac70fa8219).
- [zk-benchmarking](https://github.com/delendum-xyz/zk-benchmarking).
  A suite of benchmarks designed to compare different zero-knowledge proof libraries.
  Blog post: [ZK System Benchmarking](https://delendum.xyz/2023/01/11/zk-system-benchmarking.html).
- [ezkl](https://github.com/zkonduit/ezkl).
  A library and command-line tool for doing inference for deep
  learning models and other computational graphs in a zk-snark.
- [poseidon-circuit](https://github.com/scroll-tech/poseidon-circuit).
  Poseidon hash circuit and primitives. It integrated several poseidon
  hash schemes from zcash and iden3 and support sponge progress for
  hashing messages in any length.
- [starknet_in_rust](https://github.com/lambdaclass/starknet_in_rust).
  A Rust implementation of Starknet by LambdaClass.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

<!-- https://github.com/rustsec/advisory-db/pulls -->
<!-- https://osv.dev/list?page=2&ecosystem=crates.io -->

- [RUSTSEC-2023-0001: `tokio` - vulnerability](https://rustsec.org/advisories/RUSTSEC-2023-0001.html).
- **[RUSTSEC-2022-0075: `wasmtime` - vulnerability](https://rustsec.org/advisories/RUSTSEC-2022-0075.html).**
- **[RUSTSEC-2022-0076: `wasmtime` - vulnerability](https://rustsec.org/advisories/RUSTSEC-2022-0076.html).**
- [RUSTSEC-2022-0077: `claim` - unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0077.html).
- [RUSTSEC-2022-0078: `bumpalo` - unsoundness](https://rustsec.org/advisories/RUSTSEC-2022-0078.html).
- [RUSTSEC-2022-0079: `elf_rs` - vulnerability](https://rustsec.org/advisories/RUSTSEC-2022-0079.html).
- [RUSTSEC-2021-0146: `twoway` - unmaintained](https://rustsec.org/advisories/RUSTSEC-2021-0146.html).
- **[RUSTSEC-2022-0080: `parity-util-mem` - unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0080.html).**
  - It contains unpatched undefined behavior.
- [RUSTSEC-2022-0081: `json` - unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0081.html).
- [RUSTSEC-2023-0003: `libgit2-sys` - vulnerability](https://rustsec.org/advisories/RUSTSEC-2023-0003.html).
- [RUSTSEC-2022-0082: `warp` - vulnerability](https://rustsec.org/advisories/RUSTSEC-2022-0082.html).
- [RUSTSEC-2021-0147: `daemonize` - unmaintained](https://rustsec.org/advisories/RUSTSEC-2021-0147.html).
- [CVE-2023-22895: `bzip2` - bzip2 allows attackers to cause a denial of service via a large file that triggers an integer overflow](https://github.com/advisories/GHSA-96jv-r488-c2rj).
- [CVE-2022-46176: `cargo` - Cargo did not verify SSH host keys](https://github.com/advisories/GHSA-r5w3-xm58-jv6j).
- [CVE-2022-45299: `webbrowser-rs` - webbrowser-rs allows attackers to access arbitrary files via supplying a crafted URL](https://github.com/advisories/GHSA-m589-mv4q-p7rj).
- [CVE-2023-22499: `deno` - Deno is vulnerable to race condition via interactive permission prompt spoofing](https://github.com/advisories/GHSA-mc52-jpm2-cqh6).

&nbsp;

## Most Active in January

[Sui](https://github.com/MystenLabs):
567 merged PRs,
94 closed issues,
124 open issues

[Parity](https://github.com/paritytech):
454 merged PRs,
150 closed issues,
149 open issues

[Starkware](https://github.com/starkware-libs):
452 merged PRs,
8 closed issues,
11 open issues

[Solana](https://github.com/solana-labs/solana):
401 merged PRs,
137 closed issues,
60 open issues

[Fuel](https://github.com/FuelLabs):
322 merged PRs,
259 closed issues,
134 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

49 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4], [5][aleo-merged-prs-5]),
114 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
11 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/aleo_vm_lambda/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-merged-prs-5]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Anoma](https://github.com/anoma)

83 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
92 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
37 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

231 merged PRs ([1][aptos-merged-prs-1]),
110 closed issues ([1][aptos-closed_issues-1]),
56 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Casper](https://github.com/casper-network)

62 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
57 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
36 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

5 merged PRs ([1][comit-merged-prs-1]),
5 closed issues ([1][comit-closed_issues-1]),
2 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

60 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5]),
23 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]),
21 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[concordium-open_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

5 merged PRs ([1][conflux-merged-prs-1]),
0 closed issues,
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

3 merged PRs ([1][darkfi-merged-prs-1]),
1 closed issues ([1][darkfi-closed_issues-1]),
1 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

94 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6]),
6 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]),
7 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Dusk Network](https://github.com/dusk-network)

22 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4]),
19 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3]),
16 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-merged-prs-4]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

31 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3]),
32 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3]),
27 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

221 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7], [8][filecoin-merged-prs-8]),
195 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4], [5][filecoin-closed_issues-5]),
153 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4], [5][filecoin-open_issues-5])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/blstrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/builtin-actors-bundler/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-merged-prs-8]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/neptune/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-closed_issues-5]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/neptune/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[filecoin-open_issues-5]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

- [The FVM Imaginarium](https://filecoin.io/blog/posts/the-fvm-imaginarium-magmo-brings-state-channels-to-the-filecoin-virtual-machine/)
- [The Filecoin Virtual Machine Explained](https://filecoin.io/blog/posts/the-filecoin-virtual-machine-explained/)

#### [Findora](https://github.com/FindoraNetwork)
21 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

119 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7]),
0 closed issues (),
2 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-open_issues-1]: https://github.com/fluencelabs/trust-graph/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fluence-open_issues-2]: https://github.com/fluencelabs/aqua-ipfs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

322 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12], [13][fuel-merged-prs-13], [14][fuel-merged-prs-14]),
259 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8]),
134 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-11]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-12]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-13]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-merged-prs-14]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-closed_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

16 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4]),
53 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3], [4][golem-closed_issues-4]),
28 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-service-bus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-merged-prs-4]: https://github.com/golemfactory/ya-runtime-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-service-bus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-closed_issues-3]: https://github.com/golemfactory/ya-runtime-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-closed_issues-4]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Helium](https://github.com/helium)

16 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3]),
9 closed issues ([1][helium-closed_issues-1]),
0 open issues ()

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Holochain](https://github.com/holochain/)

81 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4]),
16 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
6 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[holochain-merged-prs-4]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

- [Holochain 0.1.0 Is Here](https://blog.holochain.org/holochain-0-1-0-is-here/)
- [Holochain Beta Released](https://blog.holochain.org/holochain-beta-released/)

#### [IOTA](https://github.com/iotaledger)

106 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4]),
42 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2]),
39 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4], [5][iota-open_issues-5], [6][iota-open_issues-6])

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-open_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-open_issues-5]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[iota-open_issues-6]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

97 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4]),
2 closed issues ([1][maidsafe-closed_issues-1]),
8 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/sn_consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[maidsafe-open_issues-2]: https://github.com/maidsafe/sn_consensus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

0 merged PRs,
7 closed issues ([1][mina-closed_issues-1], [2][mina-closed_issues-2]),
1 open issues ([1][mina-open_issues-1])

[mina-closed_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[mina-closed_issues-2]: https://github.com/openmina/mina-p2p-messages-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[mina-open_issues-1]: https://github.com/openmina/openmina/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

- [Four ZK Technologies You Should Know](https://minaprotocol.com/blog/four-zk-technologies-you-should-know)
- [Introducing the Web Node — an in-browser Mina node that verifies blocks and transfers funds](https://medium.com/openmina/introducing-the-web-node-an-in-browser-mina-node-that-verifies-blocks-and-transfers-funds-ebc59a57e79a).
  The source code [openmina](https://github.com/openmina/openmina).
- [zkIgnite, Cohort 1 Program Overview](https://minaprotocol.com/blog/zkignite-cohort-1-program-overview).
  A three-month program designed to help developers and entrepreneurs
  turn their innovative ideas into real-world applications and build
  successful businesses on Mina Protocol.

#### [MobileCoin](https://github.com/mobilecoinfoundation)

41 merged PRs ([1][mobilecoin-merged-prs-1]),
6 closed issues ([1][mobilecoin-closed_issues-1]),
8 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

61 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3], [4][multiversx-merged-prs-4], [5][multiversx-merged-prs-5], [6][multiversx-merged-prs-6]),
5 closed issues ([1][multiversx-closed_issues-1], [2][multiversx-closed_issues-2]),
1 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-nft-marketplace-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-merged-prs-4]: https://github.com/multiversx/mx-metabonding-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-merged-prs-5]: https://github.com/multiversx/mx-bridge-eth-sc-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-merged-prs-6]: https://github.com/multiversx/mx-delegation-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-closed_issues-2]: https://github.com/multiversx/mx-exchange-sc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

160 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8]),
41 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6]),
58 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/near-lake-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-7]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[near-open_issues-8]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Nervos](https://github.com/nervosnetwork)

54 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6]),
19 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
7 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4], [5][nervos-open_issues-5])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-open_issues-4]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nervos-open_issues-5]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

7 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2], [3][oasis-merged-prs-3]),
0 closed issues (),
2 open issues ([1][oasis-open_issues-1], [2][oasis-open_issues-2])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[oasis-merged-prs-2]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[oasis-merged-prs-3]: https://github.com/oasisprotocol/emerald-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[oasis-open_issues-2]: https://github.com/oasisprotocol/emerald-paratime/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

454 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14]),
150 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12]),
149 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

- [A Year in Parachains, Part 1: DeFi](https://polkadot.network/blog/a-year-in-parachains-part-1-defi)

#### [Radix](https://github.com/radixdlt)

88 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2]),
3 closed issues ([1][radix-closed_issues-1]),
0 open issues

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[radix-closed_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

22 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]),
0 closed issues,
1 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

401 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]),
137 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
60 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Subspace Labs](https://github.com/subspace)

45 merged PRs ([1][subspace_labs-merged-prs-1]),
18 closed issues ([1][subspace_labs-closed_issues-1]),
17 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

567 merged PRs ([1][sui-merged-prs-1]),
94 closed issues ([1][sui-closed_issues-1]),
124 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Zcash](https://github.com/zcash)

64 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5]),
48 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4]),
38 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4], [5][zcash-open_issues-5])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/incrementalmerkletree/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[zcash-open_issues-5]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

1 merged PRs ([1][aluvm-merged-prs-1]),
1 closed issues ([1][aluvm-closed_issues-1]),
1 open issues ([1][aluvm-open_issues-1])

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aluvm-closed_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[aluvm-open_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

24 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]),
12 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3], [4][bdk-closed_issues-4]),
17 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-closed_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

16 merged PRs ([1][bitmask-merged-prs-1]),
5 closed issues ([1][bitmask-closed_issues-1]),
3 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Cyphernet](https://github.com/cyphernet-dao)

19 merged PRs ([1][cyphernet-merged-prs-1], [2][cyphernet-merged-prs-2]),
2 closed issues ([1][cyphernet-closed_issues-1]),
13 open issues ([1][cyphernet-open_issues-1], [2][cyphernet-open_issues-2])

[cyphernet-merged-prs-1]: https://github.com/cyphernet-dao/rust-netservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[cyphernet-merged-prs-2]: https://github.com/cyphernet-dao/rust-cyphernet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[cyphernet-closed_issues-1]: https://github.com/cyphernet-dao/rust-netservices/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[cyphernet-open_issues-1]: https://github.com/cyphernet-dao/rust-netservices/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[cyphernet-open_issues-2]: https://github.com/cyphernet-dao/rust-microservices/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

3 merged PRs ([1][electrs-merged-prs-1]),
2 closed issues ([1][electrs-closed_issues-1]),
4 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

173 merged PRs ([1][fedimint-merged-prs-1]),
95 closed issues ([1][fedimint-closed_issues-1]),
87 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

51 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
19 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2], [3][ldk-closed_issues-3]),
17 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ldk-closed_issues-3]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

8 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3], [4][lnp/bp-merged-prs-4]),
5 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3]),
3 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-merged-prs-3]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-merged-prs-4]: https://github.com/BP-WG/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-closed_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-closed_issues-3]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/rust-lnpbp/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp/bp-open_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [LNP WG](https://github.com/LNP-WG)

9 merged PRs ([1][lnp_wg-merged-prs-1], [2][lnp_wg-merged-prs-2]),
4 closed issues ([1][lnp_wg-closed_issues-1], [2][lnp_wg-closed_issues-2]),
2 open issues ([1][lnp_wg-open_issues-1], [2][lnp_wg-open_issues-2])

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp_wg-merged-prs-2]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp_wg-closed_issues-1]: https://github.com/LNP-WG/lnp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp_wg-closed_issues-2]: https://github.com/LNP-WG/lnp-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp_wg-open_issues-1]: https://github.com/LNP-WG/lnp-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lnp_wg-open_issues-2]: https://github.com/LNP-WG/lightning_encoding/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

1 merged PRs ([1][nakamoto-merged-prs-1]),
1 closed issues ([1][nakamoto-closed_issues-1]),
0 open issues

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nakamoto-closed_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

7 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2], [3][nomic-merged-prs-3]),
1 closed issues ([1][nomic-closed_issues-1]),
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/nomic-io/merk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nomic-merged-prs-3]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[nomic-closed_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

4 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2]),
11 closed issues ([1][rgb-closed_issues-1], [2][rgb-closed_issues-2]),
8 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rgb-closed_issues-2]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

48 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]),
41 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4], [5][rust_bitcoin-closed_issues-5]),
21 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-closed_issues-5]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

6 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
2 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/ElementsProject/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

12 merged PRs ([1][talaia-merged-prs-1]),
6 closed issues ([1][talaia-closed_issues-1]),
2 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot


If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

67 merged PRs ([1][ethers-rs-merged-prs-1]),
11 closed issues ([1][ethers-rs-closed_issues-1]),
12 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

96 merged PRs ([1][foundry-merged-prs-1]),
75 closed issues ([1][foundry-closed_issues-1]),
83 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

34 merged PRs ([1][lighthouse-merged-prs-1]),
13 closed issues ([1][lighthouse-closed_issues-1]),
20 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

- [High-priority release: v3.4.0 (Stealy)](https://github.com/sigp/lighthouse/releases/tag/v3.4.0)

#### [Mir Protocol](https://github.com/mir-protocol)

14 merged PRs ([1][mir_protocol-merged-prs-1]),
0 closed issues,
2 open issues ([1][mir_protocol-open_issues-1])

[mir_protocol-merged-prs-1]: https://github.com/mir-protocol/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[mir_protocol-open_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

452 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3]),
8 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
11 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-01-01..2023-01-31%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-01-01..2023-01-31%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-01-01..2023-01-31%20-author:app/dependabot

- [Papyrus: An Open-Source StarkNet Full Node](https://medium.com/starkware/papyrus-an-open-source-starknet-full-node-396f7cd90202).
  The source code [papyrus](https://github.com/starkware-libs/papyrus).
- [Cairo 1.0 is Here](https://medium.com/starkware/cairo-1-0-is-here-7e1ac8377038)


If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Feb 15-17 | Barcelona, Spain

[European Blockchain Convention 2023](https://eblockchainconvention.com/)

Feb 24 — Mar 5 | Denver, USA

[ETHDenver 2023](https://www.ethdenver.com)

Mar 9-19 | Online

[Holochain Dev Training for Rust Developers](https://www.holochain.org/holochain-developer-training-2/)

Mar 13 - Apr 7 | Ho Chi Minh City, Vietnam

[ZK Spring Residency in Vietnam](https://0xparc.org/blog/2023-spring-residency)

Mar 20-24 | Paris, France

[Paris Blockchain Week](https://www.parisblockchainweek.com)

Mar 26 | Tokyo, Japan

[FHE.org conference 2023](https://fhe.org/)

Mar 27-29 | Tokyo, Japan

[RWC 2023](https://rwc.iacr.org/2023/)

Apr 4 | Lisbon, Portugal

[zkSummit9](https://www.zksummit.com/)

May 1-5 | Bol, Brač, Croatia

[Financial Cryptography and Data Security 2023](https://fc23.ifca.ai/)

May 20-21 | Amsterdam, Netherlands

[ETHDam](https://www.ethdam.com/)

Jun 3-5 | Prague, Czech Republic

[Gateway to Cosmos 2023](https://gateway.events/)

Jun 17-20 | Paris, France

[EthCC](https://www.ethcc.io/)

Aug 28-30 | Palo Alto, CA, US

[The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Sep 11-13 | Berlin, Germany

[DappCon](https://www.dappcon.io/)

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


