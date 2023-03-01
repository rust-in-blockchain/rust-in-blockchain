---
title: "RiB Newsletter #45 - _TODO_"
description: "February 2023"
date: 2023-03-01
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #45 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #44](/newsletters/rib-newsletter-44/).

&nbsp;

## Thanks

Thanks to contributors:
[Dennis Zoma],
[djddo],
[François Garillot],
[Rodairos],
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Dennis Zoma]: https://github.com/wottpal
[djddo]: https://github.com/djddo
[François Garillot]: https://github.com/huitseeker
[Rodairos]: https://github.com/rodairos
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News

- [Hello, Stylus](https://offchain.medium.com/hello-stylus-6b18fecc3a22).
  Arbitrum's new programming enviroment that supports Rust, C, C++ and more.
  It's not open sourced yet.

#### Blog Posts

- [A walkthrough on the open source Aleo VM implemented with Arkworks and blockchain implemented with Tendermint](https://www.notamonadtutorial.com/open-source-aleo-vm-implemented-with-arkworks-and-blockchain-implemented-with-tendermint/)
- [What Is a zkEVM?](https://blog.chain.link/zkevm/)
- [What Is Zero-Knowledge Encryption?](https://blog.chain.link/zero-knowledge-encryption/)
- [Unveiling OlaVM Proof of Concept: The Next-Generation Full-Featured zkVM](https://medium.com/@sin7y/unveiling-olavm-proof-of-concept-the-next-generation-full-featured-zkvm-5840b27f8e4c)
- [Sangria: a Folding Scheme for PLONK](https://geometry.xyz/notebook/sangria-a-folding-scheme-for-plonk),
  a way to achieve IVC, similar to Nova, but on top of a Plonk arithmetization instead of R1CS.

#### Papers

- [Faithful Simulation of Randomized BFT Protocols on Block DAGs](https://eprint.iacr.org/2023/192)
- [Reputation-based state machine replication](https://eprint.iacr.org/2023/169)

#### Projects

- [Bonsai Starter Template](https://github.com/risc0/bonsai-starter-template).
  Starter template for writing an application using Bonsai, a general purpose zero-knowledge proof network.
- [Arti 1.1.1 released](https://blog.torproject.org/arti_111_released/).
  Arti is Tor implemented as a Rust library.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

<!-- https://github.com/rustsec/advisory-db/pulls -->
<!-- https://osv.dev/list?page=2&ecosystem=crates.io -->

- [RUSTSEC-2022-0086: Vulnerability in `slack-morphism`](https://rustsec.org/advisories/RUSTSEC-2022-0086.html).
- [RUSTSEC-2022-0087: Vulnerability in slack-morphism](https://rustsec.org/advisories/RUSTSEC-2022-0087.html).
- **[RUSTSEC-2022-0084: Vulnerability in libp2p](https://rustsec.org/advisories/RUSTSEC-2022-0084.html).**
- [RUSTSEC-2023-0004: Vulnerability in bzip2](https://rustsec.org/advisories/RUSTSEC-2023-0004.html).
- [RUSTSEC-2022-0085: Vulnerability in matrix-sdk-crypto](https://rustsec.org/advisories/RUSTSEC-2022-0085.html).
- **[RUSTSEC-2022-0083: Vulnerability in evm](https://rustsec.org/advisories/RUSTSEC-2022-0083.html).**
- [RUSTSEC-2023-0005: Unsoundness in tokio](https://rustsec.org/advisories/RUSTSEC-2023-0005.html).
- [RUSTSEC-2020-0166: Security notice about personnummer](https://rustsec.org/advisories/RUSTSEC-2020-0166.html).
- [RUSTSEC-2022-0088: Vulnerability in tauri](https://rustsec.org/advisories/RUSTSEC-2022-0088.html).
- [RUSTSEC-2022-0089: Vulnerability in aliyun-oss-client](https://rustsec.org/advisories/RUSTSEC-2022-0089.html).
- [RUSTSEC-2023-0008: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0008.html).
  - X.509 Name Constraints Read Buffer Overflow
- [RUSTSEC-2023-0013: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0013.html).
  - `NULL` dereference during PKCS7 data verification
- [RUSTSEC-2023-0010: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0010.html).
  - Double free after calling `PEM_read_bio_ex`
- [RUSTSEC-2023-0007: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0007.html).
  - Timing Oracle in RSA Decryption
- [RUSTSEC-2023-0012: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0012.html).
  - `NULL` dereference validating DSA public key
- [RUSTSEC-2023-0009: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0009.html).
  - Use-after-free following `BIO_new_NDEF`
- [RUSTSEC-2023-0006: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0006.html).
  - X.400 address type confusion in X.509 `GeneralName`
- [RUSTSEC-2023-0011: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2023-0011.html).
  - Invalid pointer dereference in `d2i_PKCS7` functions
- [RUSTSEC-2020-0167: Vulnerability in pnet_packet](https://rustsec.org/advisories/RUSTSEC-2020-0167.html).
- [RUSTSEC-2023-0014: Unsoundness in cortex-m-rt](https://rustsec.org/advisories/RUSTSEC-2023-0014.html).
- [RUSTSEC-2022-0090: Vulnerability in libsqlite3-sys](https://rustsec.org/advisories/RUSTSEC-2022-0090.html).
- [RUSTSEC-2023-0016: Unsoundness in partial_sort](https://rustsec.org/advisories/RUSTSEC-2023-0016.html).
- [RUSTSEC-2023-0015: Unsoundness in ascii](https://rustsec.org/advisories/RUSTSEC-2023-0015.html).
- [RUSTSEC-2022-0091: Vulnerability in tauri](https://rustsec.org/advisories/RUSTSEC-2022-0091.html).
- [CVE-2023-26103: Deno vulnerable to Regular Expression Denial of Service](https://github.com/advisories/GHSA-xr9w-x6gw-c9mj).
- [GHSA-p2gm-ffr3-w2xw: Nervos CKB vulnerable to low-resource flood DDoS attacks through network message](https://github.com/advisories/GHSA-p2gm-ffr3-w2xw).
- [GHSA-fjj4-2q73-jvgc: Nervos CKB calculation of program load cycles may be missed when executing in resume mode](https://github.com/advisories/GHSA-fjj4-2q73-jvgc).


&nbsp;

## Most Active in February

[Sui](https://github.com/MystenLabs):
471 merged PRs,
57 closed issues,
122 open issues

[Solana](https://github.com/solana-labs/solana):
419 merged PRs,
125 closed issues,
35 open issues

[Parity](https://github.com/paritytech):
414 merged PRs,
215 closed issues,
156 open issues

[Fuel](https://github.com/FuelLabs):
311 merged PRs,
169 closed issues,
119 open issues

[Starkware](https://github.com/starkware-libs):
286 merged PRs,
37 closed issues,
6 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

61 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4], [5][aleo-merged-prs-5]),
9 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
10 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-merged-prs-5]: https://github.com/AleoHQ/welcome/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aleo-open_issues-4]: https://github.com/AleoHQ/wagyu/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Anoma](https://github.com/anoma)

53 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
32 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2]),
29 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

241 merged PRs ([1][aptos-merged-prs-1]),
67 closed issues ([1][aptos-closed_issues-1]),
41 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Casper](https://github.com/casper-network)

68 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
66 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
67 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [COMIT](https://github.com/comit-network)

1 merged PRs ([1][comit-merged-prs-1]),
0 closed issues,
0 open issues

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

45 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
18 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]),
26 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[concordium-open_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

11 merged PRs ([1][conflux-merged-prs-1]),
1 closed issues ([1][conflux-closed_issues-1]),
3 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

6 merged PRs ([1][darkfi-merged-prs-1]),
9 closed issues ([1][darkfi-closed_issues-1]),
2 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

- [DarkFi Testnet v0.1 alpha](https://dark.fi/insights/testnet-v1a.html)

#### [Dfinity](https://github.com/dfinity)

80 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6]),
7 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]),
3 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-merged-prs-6]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Dusk Network](https://github.com/dusk-network)

21 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2]),
26 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3]),
11 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dusk_network-closed_issues-3]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Espresso Systems](https://github.com/EspressoSystems)

31 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3]),
36 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
31 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/espresso-systems-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/espresso-systems-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

191 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7]),
167 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3]),
39 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/rust-filecoin-proofs-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Findora](https://github.com/FindoraNetwork)

18 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2]),
1 closed issues ([1][findora-closed_issues-1]),
1 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

141 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6]),
0 closed issues,
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/rust-peer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

311 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8]),
169 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7]),
119 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/forc-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-merged-prs-8]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/faucet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/forc-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-7]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fuel-open_issues-8]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Golem](https://github.com/golemfactory)

10 merged PRs ([1][golem-merged-prs-1]),
24 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]),
19 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Helium](https://github.com/helium)

24 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]),
5 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2], [3][helium-closed_issues-3]),
0 open issues

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/semtech-udp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[helium-merged-prs-4]: https://github.com/helium/helium-wallet-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[helium-closed_issues-2]: https://github.com/helium/semtech-udp/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[helium-closed_issues-3]: https://github.com/helium/helium-wallet-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot

- [The Next Era of the Helium Network Begins on March 27th](https://blog.helium.com/the-next-era-of-the-helium-network-begins-on-march-27th-6d08f2b048e0)

#### [Holochain](https://github.com/holochain/)

133 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]),
11 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]),
8 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[holochain-merged-prs-3]: https://github.com/holochain/holochain-client-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

- [Holochain Dev Tools Released](https://blog.holochain.org/holochain-dev-tools-released/)

#### [IOTA](https://github.com/iotaledger)

144 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5]),
43 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2]),
34 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3])

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-closed_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-open_issues-1]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-open_issues-2]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[iota-open_issues-3]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Maidsafe](https://github.com/maidsafe)

114 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4], [5][maidsafe-merged-prs-5], [6][maidsafe-merged-prs-6]),
9 closed issues ([1][maidsafe-closed_issues-1], [2][maidsafe-closed_issues-2], [3][maidsafe-closed_issues-3]),
7 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-merged-prs-4]: https://github.com/maidsafe/blsttc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-merged-prs-5]: https://github.com/maidsafe/sn_consensus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-merged-prs-6]: https://github.com/maidsafe/self_encryption/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/sn_dbc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-closed_issues-2]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-closed_issues-3]: https://github.com/maidsafe/sn_consensus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/sn_dbc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[maidsafe-open_issues-2]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Mina](https://github.com/MinaProtocol)

0 merged PRs,
0 closed issues,
1 open issues ([1][mina-open_issues-1])

[mina-open_issues-1]: https://github.com/openmina/mina-p2p-messages-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

- [Contributing to open source projects and about learning zero-knowledge proofs](https://www.cryptologie.net/article/585/contributing-to-open-source-projects-and-about-learning-zero-knowledge-proofs/)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

39 merged PRs ([1][mobilecoin-merged-prs-1]),
13 closed issues ([1][mobilecoin-closed_issues-1]),
15 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

33 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3]),
2 closed issues ([1][multiversx-closed_issues-1]),
3 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-nft-marketplace-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[multiversx-closed_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

142 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8]),
35 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2]),
43 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Nervos](https://github.com/nervosnetwork)

68 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7]),
3 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]),
9 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-merged-prs-6]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-merged-prs-7]: https://github.com/godwokenrises/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nervos-open_issues-4]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

10 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]),
0 closed issues,
0 open issues

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[oasis-merged-prs-2]: https://github.com/oasisprotocol/emerald-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Parity](https://github.com/paritytech)

414 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14]),
215 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13]),
156 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-closed_issues-13]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

- [ink! 4.0!](https://www.parity.io/we-just-released-ink-4-0)

#### [Radix](https://github.com/radixdlt)

74 merged PRs ([1][radix-merged-prs-1], [2][radix-merged-prs-2], [3][radix-merged-prs-3]),
0 closed issues,
2 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/community-scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[radix-merged-prs-2]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[radix-merged-prs-3]: https://github.com/radixdlt/scrypto-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

28 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2], [3][secret_network-merged-prs-3]),
1 closed issues ([1][secret_network-closed_issues-1]),
0 open issues

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[secret_network-merged-prs-3]: https://github.com/scrtlabs/snip20-reference-impl/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Solana](https://github.com/solana-labs/solana)

419 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
125 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
35 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Subspace Network](https://github.com/subspace)

36 merged PRs ([1][subspace_labs-merged-prs-1]),
26 closed issues ([1][subspace_labs-closed_issues-1]),
18 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

471 merged PRs ([1][sui-merged-prs-1]),
57 closed issues ([1][sui-closed_issues-1]),
122 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Zcash](https://github.com/zcash)

56 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4]),
38 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4], [5][zcash-closed_issues-5]),
36 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4], [5][zcash-open_issues-5])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/incrementalmerkletree/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-closed_issues-5]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-open_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zcash-open_issues-5]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

23 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4], [5][bdk-merged-prs-5]),
6 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
19 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-merged-prs-5]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

3 merged PRs ([1][bitmask-merged-prs-1]),
0 closed issues,
2 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Cyphernet](https://github.com/cyphernet-dao)

7 merged PRs ([1][cyphernet-merged-prs-1], [2][cyphernet-merged-prs-2], [3][cyphernet-merged-prs-3], [4][cyphernet-merged-prs-4]),
1 closed issues ([1][cyphernet-closed_issues-1]),
4 open issues ([1][cyphernet-open_issues-1], [2][cyphernet-open_issues-2])

[cyphernet-merged-prs-1]: https://github.com/cyphernet-dao/rust-netservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[cyphernet-merged-prs-2]: https://github.com/cyphernet-dao/rust-internet2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[cyphernet-merged-prs-3]: https://github.com/cyphernet-dao/rust-microservices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[cyphernet-merged-prs-4]: https://github.com/cyphernet-dao/rust-cyphernet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[cyphernet-closed_issues-1]: https://github.com/cyphernet-dao/rust-microservices/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[cyphernet-open_issues-1]: https://github.com/cyphernet-dao/rust-netservices/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[cyphernet-open_issues-2]: https://github.com/cyphernet-dao/rust-cyphernet/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

7 merged PRs ([1][electrs-merged-prs-1]),
12 closed issues ([1][electrs-closed_issues-1]),
2 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

142 merged PRs ([1][fedimint-merged-prs-1], [2][fedimint-merged-prs-2]),
45 closed issues ([1][fedimint-closed_issues-1]),
28 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fedimint-merged-prs-2]: https://github.com/fedimint/hbbft/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

38 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2]),
14 closed issues ([1][ldk-closed_issues-1]),
12 open issues ([1][ldk-open_issues-1])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

11 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3], [4][lnp/bp-merged-prs-4]),
20 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3]),
3 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/LNP-BP/invoices/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-merged-prs-3]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-merged-prs-4]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-closed_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-closed_issues-3]: https://github.com/BP-WG/bp-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp/bp-open_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [LNP WG](https://github.com/LNP-WG)

2 merged PRs ([1][lnp_wg-merged-prs-1], [2][lnp_wg-merged-prs-2]),
0 closed issues,
2 open issues ([1][lnp_wg-open_issues-1])

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp_wg-merged-prs-2]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lnp_wg-open_issues-1]: https://github.com/LNP-WG/lightning_encoding/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

10 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]),
0 closed issues (),
2 open issues ([1][nomic-open_issues-1], [2][nomic-open_issues-2])

[nomic-merged-prs-1]: https://github.com/nomic-io/merk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nomic-open_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[nomic-open_issues-2]: https://github.com/nomic-io/merk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

4 merged PRs ([1][rgb-merged-prs-1], [2][rgb-merged-prs-2]),
16 closed issues ([1][rgb-closed_issues-1]),
2 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rgb-merged-prs-2]: https://github.com/RGB-WG/rust-rgb20/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

69 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]),
31 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]),
18 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bip39/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bip39/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

1 merged PRs ([1][rust_simplicity-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Talaia](https://github.com/talaia-labs/rust-teos)

6 merged PRs ([1][talaia-merged-prs-1]),
5 closed issues ([1][talaia-closed_issues-1]),
3 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[talaia-closed_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

59 merged PRs ([1][ethers-rs-merged-prs-1]),
14 closed issues ([1][ethers-rs-closed_issues-1]),
14 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

66 merged PRs ([1][foundry-merged-prs-1]),
75 closed issues ([1][foundry-closed_issues-1]),
95 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

35 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
18 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]),
28 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Mir Protocol](https://github.com/mir-protocol)

20 merged PRs ([1][mir_protocol-merged-prs-1], [2][mir_protocol-merged-prs-2]),
1 closed issues ([1][mir_protocol-closed_issues-1]),
2 open issues ([1][mir_protocol-open_issues-1])

[mir_protocol-merged-prs-1]: https://github.com/mir-protocol/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[mir_protocol-merged-prs-2]: https://github.com/mir-protocol/evm-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[mir_protocol-closed_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[mir_protocol-open_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

286 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2]),
37 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
6 open issues ([1][starkware-open_issues-1], [2][starkware-open_issues-2])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot
[starkware-open_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

- [Cairo 1.0-Alpha.3 — Just released!](https://starkware.medium.com/cairo-1-0-alpha-3-just-released-45ba7f2f995f)

#### [zkSync](https://github.com/matter-labs/zksync)


2 merged PRs ([1][zksync-merged-prs-1], [2][zksync-merged-prs-2]),
2 closed issues ([1][zksync-closed_issues-1]),
2 open issues ([1][zksync-open_issues-1])

[zksync-merged-prs-1]: https://github.com/matter-labs/zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zksync-merged-prs-2]: https://github.com/matter-labs/franklin-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-02-01..2023-02-28%20-author:app/dependabot
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-02-01..2023-02-28%20-author:app/dependabot

- [All Aboard zkSync Era Mainnet](https://blog.matter-labs.io/all-aboard-zksync-era-mainnet-8b8964ba7c59)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!

&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

Mar 9-19 | Online | [Holochain Dev Training for Rust Developers](https://www.holochain.org/holochain-developer-training-2/)

Mar 13 - Apr 7 | Ho Chi Minh City, Vietnam | [ZK Spring Residency in Vietnam](https://0xparc.org/blog/2023-spring-residency)

Mar 20-24 | Paris, France | [Paris Blockchain Week](https://www.parisblockchainweek.com)

Mar 26 | Tokyo, Japan | [FHE.org conference 2023](https://fhe.org/)

Mar 27-29 | Tokyo, Japan | [RWC 2023](https://rwc.iacr.org/2023/)

Apr 4 | Lisbon, Portugal | [zkSummit9](https://www.zksummit.com/)

May 1-5 | Bol, Brač, Croatia | [Financial Cryptography and Data Security 2023](https://fc23.ifca.ai/)

May 20-21 | Amsterdam, Netherlands | [ETHDam](https://www.ethdam.com/)

Jun 3-5 | Prague, Czech Republic | [Gateway to Cosmos 2023](https://gateway.events/)

Jun 17-20 | Paris, France | [EthCC](https://www.ethcc.io/)

Aug 28-30 | Palo Alto, CA, US | [The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Sep 11-13 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

Sep 12-15 | Albuquerque, NM & Online | [RustConf 2023](https://rustconf.com/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Blockstream | Remote
- [Software Engineer, iOS (Native)](https://grnh.se/cc6c514e1us)

Stellar | Remote
- [Senior Smart Contract Engineer](https://grnh.se/2e9c16074us)
- [Rust Engineer](https://grnh.se/ac41479f4us)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain
