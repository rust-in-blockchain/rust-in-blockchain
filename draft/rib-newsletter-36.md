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
[John Adler],
[keymakercasa],
[Piotr Dziubecki],
[thewinfred],

_TODO_

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

#### News


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

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

#### [Anoma](https://github.com/anoma)

#### [Casper](https://casper.network)

#### [ChainSafe](https://github.com/ChainSafe)

- [Lodestar v0.37.0: Bopsten-ready Release](https://blog.chainsafe.io/lodestar-v0-37-0-bopsten-ready-release-231d185e3e1e)
- [How to Become a Web3 Developer](https://blog.chainsafe.io/how-to-become-a-web3-developer-8849ab20b686)

#### [COMIT](https://github.com/comit-network)

#### [Concordium](https://github.com/Concordium)

#### [Conflux](https://github.com/Conflux-Chain)

#### [DarkFi](https://dark.fi)

#### [Dfinity](https://github.com/dfinity)

- [The Internet Computer for Ethereum Developers](https://medium.com/dfinity/the-internet-computer-for-ethereum-developers-3331b50db31b)

#### [Dusk Network](https://github.com/dusk-network)

#### [Elrond](https://github.com/ElrondNetwork)

#### [Espresso Systems](https://github.com/EspressoSystems)

#### [Findora](https://github.com/FindoraNetwork)

#### [Fluence](https://github.com/fluencelabs)

#### [Fuel](https://github.com/FuelLabs)

#### [Golem](https://github.com/golemfactory)

#### [Grin](https://github.com/mimblewimble/grin)

#### [Helium](https://github.com/helium)

#### [Holochain](https://github.com/holochain/)

#### [IOTA](https://github.com/iotaledger)

- [Energy Consumption of IOTA 2.0](https://blog.iota.org/energy-consumption-of-iota-2-0/)

#### [Maidsafe](https://github.com/maidsafe)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

#### [NEAR](https://github.com/nearprotocol/nearcore)

#### [Nervos](https://github.com/nervosnetwork)

#### [Oasis](https://github.com/oasisprotocol)

#### [Parity](https://github.com/paritytech)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

#### [Solana](https://github.com/solana-labs/solana)

#### [Spacemesh](https://github.com/spacemeshos)

#### [Subspace Labs](https://github.com/subspace)

#### [TezEdge](https://github.com/tezedge)

#### [Zcash](https://github.com/zcash)

- [Zcash Proof-of-Stake Research](https://electriccoin.co/blog/zcash-proof-of-stake-research/)
- [NU5 activates on mainnet, eliminating trusted setup and launching a new era for Zcash](https://electriccoin.co/blog/nu5-activates-on-mainnet-eliminating-trusted-setup-and-launching-a-new-era-for-zcash/)
- [New Release 5.0.0](https://electriccoin.co/blog/new-release-5-0-0/)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc] .

[ribtc]: https://t.me/rust_in_bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

#### [Bitmask](https://github.com/diba-io/bitmask-core)

#### [Electrs](https://github.com/romanz/electrs)

#### [Internet2](https://github.com/internet2-wg/)

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

#### [LNP/BP](https://github.com/LNP-BP)

#### [LNP WG](https://github.com/LNP-WG)

#### [MyCitadel](https://github.com/orgs/mycitadel)

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

#### [Nomic](https://github.com/nomic-io)

#### [RGB](https://github.com/rgb-wg)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

#### [Sapio](https://github.com/sapio-lang/sapio)

#### [Talaia](https://github.com/talaia-labs/rust-teos)

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

#### [Lighthouse](https://github.com/sigp/lighthouse)

#### [Rust Ethereum](https://github.com/rust-ethereum)

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

#### [zkSync](https://github.com/matter-labs/zksync)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->



&nbsp;

## Careers

<!--
Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)
-->

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
