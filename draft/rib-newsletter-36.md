---
title: "RiB Newsletter #36"
description: "May 2022"
date: 2022-06-01
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #36 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #35](/newsletters/rib-newsletter-35/).

There are quite a few security advisories this month that might impact
blockchain projects. If you are using OpenSSL, crossbeam, or hyper you should
see if you need to upgrade.

&nbsp;

## Thanks

Thanks to contributors:

[Aadz],
Dan Shields,
[John Adler],
[keymakercasa],
[Piotr Dziubecki],
[thewinfred],
[Brian Anderson] and [Aimee Zhu].

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Aadz]: https://github.com/aadz1
[John Adler]: https://github.com/adlerjohn
[keymakercasa]: https://github.com/keymakercasa
[Piotr Dziubecki]: https://github.com/piotr-dziubecki
[thewinfred]: https://github.com/thewinfred
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[`cargo-supply-chain`](https://github.com/rust-secure-code/cargo-supply-chain).

This project lists the authors, as registered with crates.io, of every crate in your dependency graph.axsn

&nbsp;


## Interesting Things

#### Blog Posts

- [Sin7Y Tech Review (23): Verkle Tree For ETH](https://hackmd.io/@sin7y/rJZZy_mD9#Sin7Y-Tech-Review-23-Verkle-Tree-For-ETH)
- [Security advisory: malicious crate rustdecimal](https://blog.rust-lang.org/2022/05/10/malicious-crate-rustdecimal.html)
- [Blockchain Scalability: Execution, Storage, and Consensus](https://blog.chain.link/blockchain-scalability-approaches/)

#### Papers

- [Pre-print of Casper's new consensus solution](https://arxiv.org/abs/2205.06314)
- [Marlin: Two-Phase BFT with Linearity](https://eprint.iacr.org/2022/551)
- [Distributed Shuffling in Adversarial Environments](https://eprint.iacr.org/2022/560)
- [ROAST: Robust Asynchronous Schnorr Threshold Signatures](https://eprint.iacr.org/2022/550)
- [Ponyta: Foundations of Side-Contract-Resilient Fair Exchange](https://eprint.iacr.org/2022/582)
- [TenderTee: Secure Tendermint](https://eprint.iacr.org/2022/599)
- [Distributed Blockchain Price Oracle](https://eprint.iacr.org/2022/603)
- [The Generals’ Scuttlebutt: Byzantine-Resilient Gossip Protocols](https://eprint.iacr.org/2022/541)
- [RSK: A Bitcoin sidechain with stateful smart-contracts](https://eprint.iacr.org/2022/684)

#### Projects

- [sta-rs](https://github.com/brave/sta-rs).
  Rust workspace for implementing basic functionality of
  [STAR: Distributed Secret-Sharing for Threshold Aggregation Reporting](https://arxiv.org/abs/2109.10074).

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

- **[RUSTSEC-2022-0027: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2022-0027.html).**
  - `OCSP_basic_verify` may incorrectly verify the response signing certificate
- **[RUSTSEC-2022-0026: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2022-0026.html).**
  - Incorrect MAC key used in the RC4-MD5 ciphersuite
- **[RUSTSEC-2022-0025: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2022-0025.html).**
  - Resource leakage when decoding certificates and keys
- [RUSTSEC-2022-0018: Vulnerability in totp-rs](https://rustsec.org/advisories/RUSTSEC-2022-0018.html).
  - Timing attack.
- [RUSTSEC-2022-0019: Unsoundness in crossbeam-channel](https://rustsec.org/advisories/RUSTSEC-2022-0019.html).
  - Channel creates zero value of any type
- [RUSTSEC-2022-0020: Unsoundness in crossbeam](https://rustsec.org/advisories/RUSTSEC-2022-0020.html).
  - `SegQueue` creates zero value of any type
- [RUSTSEC-2022-0021: Unsoundness in crossbeam-queue](https://rustsec.org/advisories/RUSTSEC-2022-0021.html).
  - `SegQueue` creates zero value of any type
- [RUSTSEC-2022-0022: Unsoundness in hyper](https://rustsec.org/advisories/RUSTSEC-2022-0022.html).
  - Parser creates invalid uninitialized value
- [RUSTSEC-2022-0028: Vulnerability in neon](https://rustsec.org/advisories/RUSTSEC-2022-0028.html).
  - Use after free in Neon external buffers
- [CVE-2022-23066: Incorrect Calculation in solana_rbpf](https://github.com/advisories/GHSA-9qmm-4mfr-r3wj).
- [CVE-2022-31264: Integer overflow in solana_rbpf](https://github.com/advisories/GHSA-ffx3-8qvm-pq3j).


&nbsp;

## Most Active in May

[Parity](https://github.com/paritytech):
605 merged PRs, 180 closed issues, 167 open issues

[Solana](https://github.com/solana-labs/solana):
559 merged PRs, 110 closed issues, 114 open issues

[Sui](https://github.com/MystenLabs):
489 merged PRs, 146 closed issues, 169 open issues

[Fuel](https://github.com/FuelLabs):
352 merged PRs, 195 closed issues, 145 open issues

[IOTA](https://github.com/iotaledger):
226 merged PRs, 53 closed issues, 41 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

118 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 
27 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
28 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Anoma](https://github.com/anoma)

11 merged PRs ([1][anoma-merged-prs-1]), 
13 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2]),
22 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[anoma-closed_issues-2]: https://github.com/anoma/masp/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Aptos](https://github.com/aptos-labs)

307 merged PRs ([1][aptos-merged-prs-1]), 
48 closed issues ([1][aptos-closed_issues-1]),
64 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Casper](https://casper.network)

96 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]), 
91 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
108 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [Technical Release Memo for v1.4.6](https://casper.network/network/blog/technical-release-and-changelog-for-v146)

#### [ChainSafe](https://github.com/ChainSafe)

8 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]), 
10 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2]),
8 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/mina-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/api3-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/api3-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [Lodestar v0.37.0: Bopsten-ready Release](https://blog.chainsafe.io/lodestar-v0-37-0-bopsten-ready-release-231d185e3e1e)
- [How to Become a Web3 Developer](https://blog.chainsafe.io/how-to-become-a-web3-developer-8849ab20b686)

#### [COMIT](https://github.com/comit-network)

4 merged PRs ([1][comit-merged-prs-1]), 
0 closed issues,
2 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2])

[comit-merged-prs-1]: https://github.com/comit-network/maia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[comit-open_issues-1]: https://github.com/comit-network/maia/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[comit-open_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Concordium](https://github.com/Concordium)

45 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]), 
46 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4], [5][concordium-closed_issues-5], [6][concordium-closed_issues-6]),
48 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4], [5][concordium-open_issues-5], [6][concordium-open_issues-6])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-euro2ccd-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[concordium-closed_issues-5]: https://github.com/Concordium/concordium-transaction-logger/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[concordium-closed_issues-6]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[concordium-open_issues-4]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[concordium-open_issues-5]: https://github.com/Concordium/concordium-use-case-examples/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[concordium-open_issues-6]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [Sirius Release NOW Available on Testnet](https://medium.com/concordium/sirius-release-now-available-aa39cec4bd5d)

#### [Conflux](https://github.com/Conflux-Chain)

16 merged PRs ([1][conflux-merged-prs-1]), 
1 closed issues ([1][conflux-closed_issues-1]),
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [DarkFi](https://dark.fi)

1 merged PRs ([1][darkfi-merged-prs-1]), 
1 closed issues ([1][darkfi-closed_issues-1]),
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31

#### [Dfinity](https://github.com/dfinity)

99 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7]), 
23 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5]),
13 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4], [5][dfinity-open_issues-5], [6][dfinity-open_issues-6])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dfinity-merged-prs-3]: https://github.com/dfinity/icx-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dfinity-merged-prs-4]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dfinity-merged-prs-5]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dfinity-merged-prs-6]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dfinity-merged-prs-7]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dfinity-closed_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dfinity-closed_issues-3]: https://github.com/dfinity/icx-proxy/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dfinity-closed_issues-4]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dfinity-closed_issues-5]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dfinity-open_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dfinity-open_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dfinity-open_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dfinity-open_issues-5]: https://github.com/dfinity/bitcoin-developer-preview/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dfinity-open_issues-6]: https://github.com/dfinity/ic-types/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [The Internet Computer for Ethereum Developers](https://medium.com/dfinity/the-internet-computer-for-ethereum-developers-3331b50db31b)

#### [Dusk Network](https://github.com/dusk-network)

21 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5], [6][dusk_network-merged-prs-6], [7][dusk_network-merged-prs-7]), 
34 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4], [5][dusk_network-closed_issues-5], [6][dusk_network-closed_issues-6]),
26 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3], [4][dusk_network-open_issues-4], [5][dusk_network-open_issues-5])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/dusk-hamt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dusk_network-merged-prs-2]: https://github.com/dusk-network/microkelvin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dusk_network-merged-prs-3]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dusk_network-merged-prs-4]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dusk_network-merged-prs-5]: https://github.com/dusk-network/rusk-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dusk_network-merged-prs-6]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dusk_network-merged-prs-7]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[dusk_network-closed_issues-1]: https://github.com/dusk-network/dusk-hamt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dusk_network-closed_issues-2]: https://github.com/dusk-network/microkelvin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dusk_network-closed_issues-3]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dusk_network-closed_issues-4]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dusk_network-closed_issues-5]: https://github.com/dusk-network/rusk-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dusk_network-closed_issues-6]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[dusk_network-open_issues-1]: https://github.com/dusk-network/microkelvin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dusk_network-open_issues-2]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dusk_network-open_issues-3]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dusk_network-open_issues-4]: https://github.com/dusk-network/rusk-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[dusk_network-open_issues-5]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Elrond](https://github.com/ElrondNetwork)

77 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3], [4][elrond-merged-prs-4], [5][elrond-merged-prs-5], [6][elrond-merged-prs-6], [7][elrond-merged-prs-7]), 
1 closed issues ([1][elrond-closed_issues-1]),
4 open issues ([1][elrond-open_issues-1], [2][elrond-open_issues-2])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-nft-marketplace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[elrond-merged-prs-4]: https://github.com/ElrondNetwork/sc-metabonding-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[elrond-merged-prs-5]: https://github.com/ElrondNetwork/sc-bridge-elrond/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[elrond-merged-prs-6]: https://github.com/ElrondNetwork/sc-chainlink-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[elrond-merged-prs-7]: https://github.com/ElrondNetwork/sc-savings-account-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[elrond-open_issues-2]: https://github.com/ElrondNetwork/sc-dex-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Espresso Systems](https://github.com/EspressoSystems)

101 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5]), 
48 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4]),
19 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/reef/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/cap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Findora](https://github.com/FindoraNetwork)

29 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]), 
1 closed issues ([1][findora-closed_issues-1]),
3 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[findora-merged-prs-2]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[findora-merged-prs-3]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[findora-merged-prs-4]: https://github.com/FindoraNetwork/findora-exporter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Fluence](https://github.com/fluencelabs)

39 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3]), 
23 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2], [3][fluence-closed_issues-3], [4][fluence-closed_issues-4]),
4 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fluence-closed_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fluence-closed_issues-3]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fluence-closed_issues-4]: https://github.com/fluencelabs/examples/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fluence-open_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fluence-open_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fluence-open_issues-3]: https://github.com/fluencelabs/trust-graph/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Fuel](https://github.com/FuelLabs)

352 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10], [11][fuel-merged-prs-11], [12][fuel-merged-prs-12], [13][fuel-merged-prs-13]), 
195 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7], [8][fuel-closed_issues-8], [9][fuel-closed_issues-9], [10][fuel-closed_issues-10]),
145 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-10]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-11]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-12]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-merged-prs-13]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[fuel-closed_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-7]: https://github.com/FuelLabs/fuel-types/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-8]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-9]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-closed_issues-10]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fuel-open_issues-7]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[fuel-open_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Golem](https://github.com/golemfactory)

25 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]), 
13 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3]),
10 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[golem-merged-prs-3]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[golem-merged-prs-4]: https://github.com/golemfactory/ya-runtime-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[golem-merged-prs-5]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[golem-closed_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[golem-closed_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[golem-open_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[golem-open_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Grin](https://github.com/mimblewimble/grin)

2 merged PRs ([1][grin-merged-prs-1]), 
1 closed issues ([1][grin-closed_issues-1]),
1 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[grin-closed_issues-1]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Helium](https://github.com/helium)

16 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4], [5][helium-merged-prs-5]), 
10 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
3 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2], [3][helium-open_issues-3])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[helium-merged-prs-2]: https://github.com/helium/semtech-udp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[helium-merged-prs-3]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[helium-merged-prs-4]: https://github.com/helium/virtual-lorawan-device/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[helium-merged-prs-5]: https://github.com/helium/helium-api-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[helium-closed_issues-2]: https://github.com/helium/virtual-lorawan-device/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[helium-open_issues-2]: https://github.com/helium/virtual-lorawan-device/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[helium-open_issues-3]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Holochain](https://github.com/holochain/)

27 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]), 
4 closed issues ([1][holochain-closed_issues-1]),
5 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[holochain-merged-prs-2]: https://github.com/holochain/hc-utils/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[holochain-closed_issues-1]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[holochain-open_issues-1]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [IOTA](https://github.com/iotaledger)

226 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6], [7][iota-merged-prs-7], [8][iota-merged-prs-8]), 
53 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5]),
41 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4], [5][iota-open_issues-5], [6][iota-open_issues-6], [7][iota-open_issues-7])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-merged-prs-5]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-merged-prs-6]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-merged-prs-7]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-merged-prs-8]: https://github.com/iotaledger/chronicle.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[iota-closed_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[iota-closed_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[iota-closed_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[iota-closed_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[iota-closed_issues-5]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[iota-open_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[iota-open_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[iota-open_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[iota-open_issues-5]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[iota-open_issues-6]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[iota-open_issues-7]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [Energy Consumption of IOTA 2.0](https://blog.iota.org/energy-consumption-of-iota-2-0/)

#### [Maidsafe](https://github.com/maidsafe)

51 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4]), 
10 closed issues ([1][maidsafe-closed_issues-1]),
5 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[maidsafe-merged-prs-3]: https://github.com/maidsafe/sn_consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[maidsafe-merged-prs-4]: https://github.com/maidsafe/bls_dkg/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[maidsafe-open_issues-2]: https://github.com/maidsafe/sn_consensus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [MobileCoin](https://github.com/mobilecoinfoundation)

135 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]), 
25 closed issues ([1][mobilecoin-closed_issues-1]),
24 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [MobileCoin launches Bounties on Gitcoin](https://mobilecoin.com/news/mobilecoin-launches-bounties-on-gitcoin)

#### [NEAR](https://github.com/nearprotocol/nearcore)

194 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9]), 
49 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7]),
42 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-6]: https://github.com/near/near-lake/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-7]: https://github.com/near/near-lake-framework/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-8]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-merged-prs-9]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[near-closed_issues-5]: https://github.com/near/near-lake/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[near-closed_issues-6]: https://github.com/near/near-lake-framework/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[near-closed_issues-7]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[near-open_issues-5]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[near-open_issues-6]: https://github.com/near/near-lake-framework/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[near-open_issues-7]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Nervos](https://github.com/nervosnetwork)

180 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8]), 
3 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3]),
3 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/axon/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/godwoken-scripts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-merged-prs-5]: https://github.com/nervosnetwork/mercury/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-merged-prs-6]: https://github.com/nervosnetwork/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-merged-prs-7]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-merged-prs-8]: https://github.com/nervosnetwork/ckb-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/mercury/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/axon/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [The Nervos Layer 1 – Major Protocol Upgrade with Chief Architect Jan Xie – Highlights](https://www.nervos.org/blog/the-nervos-layer-1-major-protocol-upgrade-with-chief-architect-jan-xie-highlights)
- [The Nervos Address Format Upgrade](https://www.nervos.org/blog/the-nervos-address-format-upgrade)
- [Virtual Machine Improvements](https://www.nervos.org/blog/virtual-machine-improvements)

#### [Oasis](https://github.com/oasisprotocol)

49 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]), 
1 closed issues ([1][oasis-closed_issues-1]),
3 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[oasis-merged-prs-2]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Parity](https://github.com/paritytech)

605 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14]), 
180 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13], [14][parity-closed_issues-14]),
167 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14], [15][parity-open_issues-15])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-7]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-8]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-9]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-10]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-11]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-12]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-13]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-merged-prs-14]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-7]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-8]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-12]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-13]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-closed_issues-14]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-13]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-14]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[parity-open_issues-15]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

12 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]), 
10 closed issues ([1][secret_network-closed_issues-1], [2][secret_network-closed_issues-2], [3][secret_network-closed_issues-3]),
0 open issues

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[secret_network-closed_issues-2]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[secret_network-closed_issues-3]: https://github.com/scrtlabs/snip20-reference-impl/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31

- [Shockwave Alpha Mainnet Upgrade is Complete!](https://scrt.network/blog/shockwave-alpha-mainnet-upgrade-complete)

#### [Solana](https://github.com/solana-labs/solana)

559 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]), 
110 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2], [3][solana-closed_issues-3]),
114 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[solana-closed_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [Scaffold Series - Part 1 Wallet Adapter](https://solana.com/news/solana-scaffold-part-1-wallet-adapter)
- [Scaffold Series - Part 2 Wallet Balance](https://solana.com/news/solana-scaffold-part-2-wallet-balance)
- [Scaffold Series - Part 3 Sending SOL](https://solana.com/news/solana-scaffold-part-3-sending-sol)

#### [Subspace Labs](https://github.com/subspace)

94 merged PRs ([1][subspace_labs-merged-prs-1]), 
13 closed issues ([1][subspace_labs-closed_issues-1]),
4 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Sui](https://github.com/MystenLabs)

489 merged PRs ([1][sui-merged-prs-1], [2][sui-merged-prs-2]), 
146 closed issues ([1][sui-closed_issues-1], [2][sui-closed_issues-2]),
169 open issues ([1][sui-open_issues-1], [2][sui-open_issues-2])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[sui-merged-prs-2]: https://github.com/MystenLabs/narwhal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[sui-closed_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[sui-open_issues-2]: https://github.com/MystenLabs/narwhal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [TezEdge](https://github.com/tezedge)

20 merged PRs ([1][tezedge-merged-prs-1]), 
0 closed issues,
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Zcash](https://github.com/zcash)

175 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5], [6][zcash-merged-prs-6]), 
86 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4], [5][zcash-closed_issues-5]),
34 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4], [5][zcash-open_issues-5])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zcash-merged-prs-6]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[zcash-closed_issues-3]: https://github.com/zcash/incrementalmerkletree/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[zcash-closed_issues-4]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[zcash-closed_issues-5]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[zcash-open_issues-5]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

- [Zcash Proof-of-Stake Research](https://electriccoin.co/blog/zcash-proof-of-stake-research/)
- [NU5 activates on mainnet, eliminating trusted setup and launching a new era for Zcash](https://electriccoin.co/blog/nu5-activates-on-mainnet-eliminating-trusted-setup-and-launching-a-new-era-for-zcash/)
- [New Release 5.0.0](https://electriccoin.co/blog/new-release-5-0-0/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc] .

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

25 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]), 
21 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3], [4][bdk-closed_issues-4]),
12 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[bdk-closed_issues-4]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Bitmask](https://github.com/diba-io/bitmask-core)

3 merged PRs ([1][bitmask-merged-prs-1]), 
1 closed issues ([1][bitmask-closed_issues-1]),
0 open issues

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31

#### [Electrs](https://github.com/romanz/electrs)

8 merged PRs ([1][electrs-merged-prs-1]), 
0 closed issues,
2 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Internet2](https://github.com/internet2-wg/)

1 merged PRs ([1][internet2-merged-prs-1]), 
0 closed issues,
0 open issues

[internet2-merged-prs-1]: https://github.com/Internet2-WG/rust-internet2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

40 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2]), 
18 closed issues ([1][ldk-closed_issues-1]),
10 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [LNP/BP](https://github.com/LNP-BP)

8 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3]), 
8 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2]),
0 open issues

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[lnp/bp-merged-prs-2]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[lnp/bp-merged-prs-3]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[lnp/bp-closed_issues-2]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31

#### [LNP WG](https://github.com/LNP-WG)

1 merged PRs ([1][lnp_wg-merged-prs-1]), 
0 closed issues,
0 open issues

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31

#### [MyCitadel](https://github.com/orgs/mycitadel)

4 merged PRs ([1][mycitadel-merged-prs-1]), 
6 closed issues ([1][mycitadel-closed_issues-1]),
12 open issues ([1][mycitadel-open_issues-1])

[mycitadel-merged-prs-1]: https://github.com/mycitadel/mycitadel-desktop/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[mycitadel-closed_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[mycitadel-open_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

1 merged PRs ([1][nakamoto-merged-prs-1]), 
0 closed issues,
0 open issues

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31

#### [Nomic](https://github.com/nomic-io)

0 merged PRs,
0 closed issues,
2 open issues ([1][nomic-open_issues-1])

[nomic-open_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [RGB](https://github.com/rgb-wg)

2 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2]), 
1 closed issues ([1][rgb-closed_issues-1]),
2 open issues ([1][rgb-open_issues-1], [2][rgb-open_issues-2])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rgb-merged-prs-2]: https://github.com/RGB-WG/rgb-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[rgb-open_issues-2]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

57 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5], [6][rust_bitcoin-merged-prs-6]), 
11 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4], [5][rust_bitcoin-closed_issues-5], [6][rust_bitcoin-closed_issues-6]),
15 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/rust-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rust_bitcoin-merged-prs-6]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rust_bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rust_bitcoin-closed_issues-5]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rust_bitcoin-closed_issues-6]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Sapio](https://github.com/sapio-lang/sapio)

6 merged PRs ([1][sapio-merged-prs-1]), 
1 closed issues ([1][sapio-closed_issues-1]),
0 open issues

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[sapio-closed_issues-1]: https://github.com/sapio-lang/sapio/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31

#### [Talaia](https://github.com/talaia-labs/rust-teos)

2 merged PRs ([1][talaia-merged-prs-1]), 
1 closed issues ([1][talaia-closed_issues-1]),
3 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!

&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

97 merged PRs ([1][ethers-rs-merged-prs-1]), 
26 closed issues ([1][ethers-rs-closed_issues-1]),
10 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

10 merged PRs ([1][lighthouse-merged-prs-1]), 
21 closed issues ([1][lighthouse-closed_issues-1]),
14 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [Rust Ethereum](https://github.com/rust-ethereum)

4 merged PRs ([1][rust_ethereum-merged-prs-1]), 
0 closed issues,
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

2 merged PRs ([1][rust_web3-merged-prs-1]), 
1 closed issues ([1][rust_web3-closed_issues-1]),
9 open issues ([1][rust_web3-open_issues-1])

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[rust_web3-closed_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31
[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2022-05-01..2022-05-31

#### [zkSync](https://github.com/matter-labs/zksync)

5 merged PRs ([1][zksync-merged-prs-1], [2][zksync-merged-prs-2]), 
2 closed issues ([1][zksync-closed_issues-1]),
0 open issues

[zksync-merged-prs-1]: https://github.com/matter-labs/zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zksync-merged-prs-2]: https://github.com/matter-labs/compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-05-01..2022-05-31
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-05-01..2022-05-31

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!

&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->


Jun 9-12 | Austin, TX, US

[Consensus](https://www.coindesk.com/consensus2022/)

Jun 13-17 | Šibenik, Croatia

[Summer school on real-world crypto and privacy](https://summerschool-croatia.cs.ru.nl/2022/)

Jun 20-23 | New York, US

[NFT.NYC](https://www.nft.nyc/)

Jun 29-30 | Online, multiple cities

[Polkadot Decoded](https://decoded.polkadot.network/)

Aug 7-9 | Online, Las Vegas, US

[Zcon3](https://zfnd.org/zcon3/)

Aug 13-18 | Santa Barbara, CA, US

[Crypto 2022](https://crypto.iacr.org/2022/)

Aug 29-31 | Arrillaga Alumni Center, Stanford University

[SBC'22: The Science of Blockchain Conference 2022](https://cbr.stanford.edu/sbc22/)

Oct 7-16 | Bogota, Colombia

[Devcon Week](https://devcon.org/)

&nbsp;

## Careers

<!--
Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)
-->

Blockstream | Remote
- [Software Library Engineer (C++)](https://grnh.se/69d260dc1us)
- [Senior Network Engineer](https://grnh.se/6ac8f7f11us)
- [Senior Product Manager](https://grnh.se/11354dd01us)
- [Product Manager](https://grnh.se/1bdd2ced1us)
- [Technical Project Manager](https://grnh.se/ca7b51b81us)
- [Lead Engineer, Blockstream Mining](https://grnh.se/e128bb9b1us)
- [QA Engineer](https://grnh.se/ce2891871us)
- [Qt Engineer](https://grnh.se/2bf5f9981us)
- [Junior Operations Manager](https://grnh.se/f1c289141us)
- [Don't see a role that fits? Apply here!](https://grnh.se/e53608a01us)

Casa | Remote
- [Senior Backend Software Engineer](https://tinyurl.com/Sr-Backend-RiB)
- [Engineering Manager, Backend](https://tinyurl.com/Casa-EngMgr-RiB)
- [Director of Partnerships](https://tinyurl.com/Casa-Dir-Partnerships-RiB)

IO Global (IOHK) | Remote
- [Software Engineer - Rust (Jormungandr)](https://apply.workable.com/io-global/j/9278186849/)
- [Technical Architect (Rust) - Lead Governance](https://apply.workable.com/io-global/j/C2F607EEF5/)
- [Technical Architect (Catalyst)](https://apply.workable.com/io-global/j/3DDB40A962/)

Zcash Foundation | Remote
- [Core Rust Engineer](https://cryptojobslist.com/jobs/core-engineer-zcash-foundation-no-restrictions)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain
