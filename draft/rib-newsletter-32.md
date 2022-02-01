---
title: "RiB Newsletter #32"
description: "January 2022"
date: 2022-02-02
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #32 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #31](/newsletters/rib-newsletter-31/).

&nbsp;

## Thanks

Thanks to contributors:
[bbyleggo123],
[Daniel Lubarov],
[Dan Shields],
[John Adler],
[Philip Glazman],
[PopcornPaws],
[Squirrel],
[TannrA],
[Brian Anderson],
[Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[bbyleggo123]: https://github.com/bbyleggo123
[Daniel Lubarov]: https://github.com/dlubarov
[Dan Shields]: Https://github.com/NukeManDan
[John Adler]: https://github.com/adlerjohn
[Philip Glazman]: https://github.com/philipglazman
[PopcornPaws]: https://github.com/PopcornPaws
[Squirrel]: https://github.com/gilescope
[TannrA]: https://github.com/WilfredTA
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[Trampoline].

Trampoline is a Rust-based smart contract framework for the UTXO-based Nervos network.
Whereas most smart contract platforms are account-based,
with a programming model that is relatively easy to reason about in the imperative style,
there are comparatively few smart contracts of any complexity written for UTXO blockchains.
This project is an attempt to make writing UTXO-based contracts more accessible.

[Trampoline]: https://github.com/WilfredTA/trampoline

&nbsp;


## Interesting Things

#### News

- [The great renaming: what happened to Eth2?](https://blog.ethereum.org/2022/01/24/the-great-eth2-renaming/)
- [Statement by Diem CEO Stuart Levey on the Sale of the Diem Group’s Assets to Silvergate](https://www.diem.com/en-us/updates/stuart-levey-statement-diem-asset-sale/)

#### Blog Posts

- [Electric Capital Developer Report (2021)](https://medium.com/electric-capital/electric-capital-developer-report-2021-f37874efea6d)
- [Part 1: The life of an optimization barrier](https://blog.trailofbits.com/2022/01/26/part-1-the-life-of-an-optimization-barrier/)
- [Part 2: Improving crypto code in Rust using LLVM’s optnone](https://blog.trailofbits.com/2022/02/01/part-2-rusty-crypto/)

#### Papers

- [An Introduction to Secret-Sharing-Based Secure Multiparty Computation](https://eprint.iacr.org/2022/062)
- [Non-Interactive Zero-Knowledge Proofs to Multiple Verifiers](https://eprint.iacr.org/2022/063)
- [PlonKup: Reconciling PlonK with plookup](https://eprint.iacr.org/2022/086)
- [Titanium: A Metadata-Hiding File-Sharing System with Malicious Security](https://eprint.iacr.org/2022/051)
- [LedgerHedger: Gas Reservation for Smart-Contract Security](https://eprint.iacr.org/2022/056)
- [Broken Proofs of Solvency in Blockchain Custodial Wallets and Exchanges](https://eprint.iacr.org/2022/043)
- [XCC: Theft-Resilient and Collateral-Optimized Cryptocurrency-Backed Assets](https://eprint.iacr.org/2022/113)
- [Preparation for Post-Quantum era: a survey about blockchain schemes from a post-quantum perspective](https://eprint.iacr.org/2022/026)

#### Projects

- [Plonky2](https://github.com/mir-protocol/plonky2)
  is a SNARK implementation based on techniques from PLONK and FRI.
  The announcement: [Introducing Plonky2](https://blog.polygon.technology/introducing-plonky2/).
- [Schnorrkel](https://github.com/w3f/schnorrkel)
  implements Schnorr signature on Ristretto compressed Ed25519 points,
  as well as related protocols like HDKD, MuSig, and a verifiable
  random function (VRF).
- [ref-fvm](https://github.com/filecoin-project/ref-fvm).
  Reference implementation of the Filecoin Virtual Machine [v0, pre-alpha].
- [Scrt-RNG](https://github.com/DDT5/scrt-rng).
  Secret Oracle - RNG will be a decentralized source of private
  randomness on Secret Network.
- [stable-swap](https://github.com/saber-hq/stable-swap).
  The source for the Saber stableswap AMM on Solana.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

- [RUSTSEC-2021-0133: cargo-download is unmaintained](https://rustsec.org/advisories/RUSTSEC-2021-0133.html).
- [RUSTSEC-2021-0134: rental is unmaintained](https://rustsec.org/advisories/RUSTSEC-2021-0134.html).
- [RUSTSEC-2022-0004: Vulnerability in rustc-serialize](https://rustsec.org/advisories/RUSTSEC-2022-0004.html).
- [RUSTSEC-2022-0001: lmdb is unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0001.html).
- [RUSTSEC-2022-0002: Vulnerability in dashmap](https://rustsec.org/advisories/RUSTSEC-2022-0002.html).
- **[CVE-2022-21658: Vulnerability in std](https://rustsec.org/advisories/CVE-2022-21658.html).**
  Time-of-check time-of-use race condition can allow attacker to delete files they do not have access to delete.
- [RUSTSEC-2022-0003: Vulnerability in ammonia](https://rustsec.org/advisories/RUSTSEC-2022-0003.html).
- [RUSTSEC-2022-0005: ftd2xx-embedded-hal is unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0005.html).
- [RUSTSEC-2022-0006: Vulnerability in thread_local](https://rustsec.org/advisories/RUSTSEC-2022-0006.html).
- [RUSTSEC-2022-0007: Unsoundness in qcell](https://rustsec.org/advisories/RUSTSEC-2022-0007.html).
- **[CVE-2022-21685: Integer underflow in Frontier](https://github.com/advisories/GHSA-cjg2-2fjg-fph4).**
  Frontier is an ethereum compatibility for substrate
- [CVE-2021-39480: Denial of service in bingrep](https://github.com/advisories/GHSA-gm68-g349-gxgg).
- **[CVE-2021-46102: Integer overflow in solana_rbpf](https://github.com/advisories/GHSA-xwqr-xmgg-j69q).**


&nbsp;

## Most Active in January

[Solana](https://github.com/solana-labs/solana):
332 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
51 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
55 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Parity](https://github.com/paritytech):
304 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
108 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6]), 
90 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[NEAR](https://github.com/nearprotocol/nearcore):
184 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2]), 
54 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4]), 
57 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

&nbsp;

## Project Updates

#### [Aleo](https://github.com/AleoHQ)

129 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]), 
28 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
36 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [Intro to Leo Programming Language](https://www.aleo.org/post/leo-programming-language)

#### [Anoma](https://github.com/anoma)

42 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2]), 
33 closed issues ([1][anoma-closed_issues-1]), 
38 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[anoma-merged-prs-2]: https://github.com/anoma/ferveo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [An Introduction to zk-SNARK: Plonkup](https://anoma.network/blog/an-introduction-to-zk-snark-plonkup/)

#### [ChainSafe](https://github.com/ChainSafe)

53 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]), 
45 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2]), 
18 open issues ([1][chainsafe-open_issues-1], [2][chainsafe-open_issues-2])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/filecoindot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/filecoindot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[chainsafe-open_issues-2]: https://github.com/ChainSafe/filecoindot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [COMIT](https://github.com/comit-network)

5 merged PRs ([1][comit-merged-prs-1]), 
5 closed issues ([1][comit-closed_issues-1]), 
4 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [ItchySats - Unpacking the CFD protocol](https://comit.network/blog/2022/01/11/cfd-protocol-explained/)

#### [Concordium](https://github.com/Concordium)

13 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]), 
3 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2]), 
9 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [Alpha Centauri 3.0 — Mainnet- Release notes](https://medium.com/concordium/alpha-centauri-3-0-mainnet-release-notes-2ae9a2d7e111)

#### [Conflux](https://github.com/Conflux-Chain)

98 merged PRs ([1][conflux-merged-prs-1]), 
6 closed issues ([1][conflux-closed_issues-1]), 
7 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [DarkFi](https://dark.fi)

6 merged PRs ([1][darkfi-merged-prs-1]), 
10 closed issues ([1][darkfi-closed_issues-1]), 
10 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Dfinity](https://github.com/dfinity)

28 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]), 
8 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3]), 
4 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[dfinity-merged-prs-4]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[dfinity-closed_issues-1]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[dfinity-closed_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[dfinity-closed_issues-3]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[dfinity-open_issues-1]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[dfinity-open_issues-3]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [‘The Internet Computer for Geeks’: A New DFINITY White Paper](https://medium.com/dfinity/the-internet-computer-for-geeks-a-new-dfinity-white-paper-ecb075b2d525)

#### [Elrond](https://github.com/ElrondNetwork)

38 merged PRs ([1][elrond-merged-prs-1]), 
2 closed issues ([1][elrond-closed_issues-1]), 
1 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Findora](https://github.com/FindoraNetwork)

24 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3]), 
1 closed issues ([1][findora-closed_issues-1]), 
2 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[findora-merged-prs-2]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[findora-merged-prs-3]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Fluence](https://github.com/fluencelabs)

7 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3]), 
1 closed issues ([1][fluence-closed_issues-1]), 
1 open issues ([1][fluence-open_issues-1])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Fuel](https://github.com/FuelLabs)

165 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9]), 
78 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7]), 
108 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7])

[fuel-merged-prs-1]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-merged-prs-9]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-types/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[fuel-open_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[fuel-open_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Golem](https://github.com/golemfactory)

12 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2]), 
13 closed issues ([1][golem-closed_issues-1]), 
12 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[golem-open_issues-2]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Grin](https://github.com/mimblewimble/grin)

8 merged PRs ([1][grin-merged-prs-1]), 
8 closed issues ([1][grin-closed_issues-1]), 
0 open issues ()

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31

#### [Holochain](https://github.com/holochain/)

27 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]), 
6 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
2 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[holochain-merged-prs-2]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[holochain-closed_issues-2]: https://github.com/holochain/holochain-wasmer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [IOTA](https://github.com/iotaledger)

8 merged PRs ([1][iota-merged-prs-1]), 
1 closed issues ([1][iota-closed_issues-1]), 
5 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

1 merged PRs ([1][lighthouse-merged-prs-1]), 
34 closed issues ([1][lighthouse-closed_issues-1]), 
18 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [New releases v2.1.2](https://github.com/sigp/lighthouse/releases/tag/v2.1.2)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

76 merged PRs ([1][mobilecoin-merged-prs-1]), 
2 closed issues ([1][mobilecoin-closed_issues-1]), 
46 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

184 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2]), 
54 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4]), 
57 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[near-merged-prs-2]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[near-closed_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[near-closed_issues-3]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [NEAR Launches Stake Farming To Unlock Ecosystem Rewards](https://near.org/blog/near-launches-stake-farming-to-unlock-ecosystem-rewards/)
- [An Update On the NEAR Validator Upgrade](https://near.org/blog/an-update-on-the-near-validator-upgrade/)
- [NEAR Enhances Decentralization with Validator Upgrade](https://near.org/blog/near-validators-upgrade-decentralization/)

#### [Nervos](https://github.com/nervosnetwork)

35 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5]), 
2 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
2 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-std/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [A Beginner's Guide To Nervos](https://jackylhh.notion.site/jackylhh/A-Beginner-s-Guide-To-Nervos-c3e0ed3fd9284263a033018ef554fa37)

#### [Parity](https://github.com/paritytech)

304 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
108 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6]), 
90 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[parity-closed_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[parity-closed_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[parity-open_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[parity-open_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [Polkadot v1.0: Sharding and Economic Security](https://medium.com/polkadot-network/polkadot-v1-0-sharding-and-economic-security-e03099b4fa81)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

72 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5], [6][rust_bitcoin-merged-prs-6]), 
37 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]), 
27 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[rust_bitcoin-merged-prs-4]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[rust_bitcoin-merged-prs-5]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[rust_bitcoin-merged-prs-6]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[rust_bitcoin-closed_issues-3]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[rust_bitcoin-open_issues-3]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[rust_bitcoin-open_issues-4]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Rust Ethereum](https://github.com/rust-ethereum)

3 merged PRs ([1][rust_ethereum-merged-prs-1]), 
1 closed issues ([1][rust_ethereum-closed_issues-1]), 
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

13 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 
1 closed issues ([1][secret_network-closed_issues-1]), 
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[secret_network-closed_issues-1]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [Secret Feature: Secret Oracles](https://scrt.network/blog/secret-feature-secret-oracles)
- [Secret Griptape Hackathon](https://scrt.network/blog/secret-griptape-hackathon)

#### [Solana](https://github.com/solana-labs/solana)

332 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
51 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
55 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [solana-pay](https://github.com/solana-labs/solana-pay).
  A new standard for decentralized payments.
- Open issue: [Consider adding user specified fees to prioritize txs propagation to the leader/block #22820](https://github.com/solana-labs/solana/issues/22820)
- [Solana Internals Part 2: How Is a Solana Program Deployed and Upgraded](https://www.soteria.dev/post/solana-internals-part-2-how-is-a-solana-program-deployed-and-upgraded)
- [Solana Internals Part 3: The Transaction Processing Unit (TPU)](https://www.soteria.dev/post/solana-internals-part-3-the-transaction-processing-unit-tpu)
- [Solana Internals Part 4: The Bank — A Key Component](https://www.soteria.dev/post/solana-internals-part-4-the-bank-a-key-component)
- [A technical overview of developing gold.xyz on Solana](https://mirror.xyz/goldxyz.eth/cP4BqSyI_xP04VgRSsAtdDyDkvDcfUG_ZFgWYILDhjQ?123)
- Events: [Introducing the Solana Hacker House Inaugural World Tour](https://solana.com/news/solana-hacker-house-world-tour).

#### [Spacemesh](https://github.com/spacemeshos)

2 merged PRs ([1][spacemesh-merged-prs-1]), 
58 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
14 open issues ([1][spacemesh-open_issues-1])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Subspace Labs](https://github.com/subspace)

13 merged PRs ([1][subspace_labs-merged-prs-1], [2][subspace_labs-merged-prs-2]), 
2 closed issues ([1][subspace_labs-closed_issues-1], [2][subspace_labs-closed_issues-2]), 
1 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[subspace_labs-merged-prs-2]: https://github.com/subspace/subspace-desktop/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[subspace_labs-closed_issues-2]: https://github.com/subspace/subspace-desktop/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [Archiving Kusama on the Subspace Aries Test Network](https://medium.com/subspace-network/archiving-kusama-on-the-subspace-aries-test-network-48b554c43d55)

#### [TezEdge](https://github.com/tezedge)

15 merged PRs ([1][tezedge-merged-prs-1]), 
2 closed issues ([1][tezedge-closed_issues-1]), 
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[tezedge-closed_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

#### [Zcash](https://github.com/zcash)

77 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
61 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
63 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-01-01..2022-01-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-01-01..2022-01-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [New Release 4.6.0-1](https://electriccoin.co/blog/new-release-4-6-0-1/)

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs (), 
0 closed issues (), 
1 open issues ([1][zksync-open_issues-1])

[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2022-01-01..2022-01-31

- [On Managing Secure Upgradability](https://blog.matter-labs.io/upgradability3-934db4433b0c)


&nbsp;

## Events

Feb 5-6 | Online

[FOSDEM 2022](https://fosdem.org/2022/)

Feb 11-20 | Denver

[ETHDenver 2022](https://www.ethdenver.com/)

Apr 16 - May 13th | Online

[Scaling Ethereum](https://scaling.ethglobal.co/)

Apr 18-25 | Amsterdam

[Devconnect](https://devconnect.org/)

May 2-6 | Canada

[Financial Cryptography and Data Security 2022](http://fc22.ifca.ai/index.html)

Jun 13-17 | Šibenik, Croatia

[Summer school on real-world crypto and privacy](https://summerschool-croatia.cs.ru.nl/2022/)

Aug 29-31 | Arrillaga Alumni Center, Stanford University

[SBC'22: The Science of Blockchain Conference 2022](https://cbr.stanford.edu/sbc22/)


&nbsp;

## Careers

Aurora | Remote
- [Blockchain/EVM Engineer](https://docs.google.com/document/d/1VkaXInjgSczOL_R3aKMOnXKv7lFvvL1z__SlZQLfR78/edit?usp=sharing)

Fluence | Remote
- [Rust Engineer (AquaVM)](https://docs.google.com/document/d/1941617PiUwIUSccQVS-5UDX8kRitp36mTLBgzVtspfQ/edit?usp=sharing)

NEAR | Remote
- [Core Engineer](https://docs.google.com/document/d/1b5oJAM37_B2-stUsJ-xtAIsPnqMwdD0wu30ITvylCHk/edit?usp=sharing)

Pine Street Labs | San Francisco or Remote
- [Custody Engineer](https://www.linkedin.com/hiring/jobs/2863929634/detail/)

Polygon Zero | Remote
- [Senior Protocol Engineer](https://mirprotocol.org/careers/protocol-engineer)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


