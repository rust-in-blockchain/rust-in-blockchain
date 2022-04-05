---
title: "RiB Newsletter #34 - _TODO_"
description: "March 2022"
date: 2022-04-06
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #34 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #33](/newsletters/rib-newsletter-33/).

After a fairly sleepy winter,
this month felt overwhelmingly active,
with lots of conversation in the Telegram group,
and many new projects coming to our attention.

This month we refreshed and reorganized the set of GitHub repositories we track,
and which are listed in the "project updates" section. The corresponding
[rib-bible] is likely the most comprehensive list of Rust blockchains and their
repositories on the Internet.

Thanks to [Hunter Trujillo] the project updates now have entire sections for all
Bitcoin-related projects and all Ethereum-related projects, and there are many
Bitcoin and Lightning Network projects written in Rust that we have overlooked.
Many of them are overseen by the [LNP/BP Association], which is dedicated to
building layer 2/3 technologies on top of Bitcoin and Lightning. Their GitHub
README is a good overview of their many Rust Bitcoin projects; and their are
many other Rust Bitcoin projects now listed in our project updates section.

[rib-bible]: https://github.com/rust-in-blockchain/rust-in-blockchain/blob/master/rib-bible.md
[LNP/BP Association]: https://github.com/LNP-BP


- espresso
- move / diem derivitives
- most active


&nbsp;

## Thanks

Thanks to contributors:
Ali Atiia,
Dan Shields,
[djddo],
Ganzaro,
Giles Cope,
[Hunter Trujillo],
[John Adler],
[Max Wegman],
Samuel Dare,
Tannr,
[veilgets],
[Brian Anderson], and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[djddo]: https://github.com/djddo
[Hunter Trujillo]: https://github.com/cryptoquick
[John Adler]: https://github.com/adlerjohn
[Max Wegman]: https://github.com/mastermaxy
[veilgets]: https://github.com/veilgets
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News


#### Blog Posts

- [A Comparison of Heterogeneous Blockchain Networks](https://medium.com/@arikan/a-comparison-of-heterogeneous-blockchain-networks-4bf7ff2fe279)
- [The AMM Test: A No BS Look at L1 Performance](https://medium.com/dragonfly-research/spamming-solana-a-trip-report-d05e0455a3ba)
- [Geometry presents: Slush, a proposal for Fractal scaling](https://hackmd.io/@kalmanlajko/rkgg9GLG5#Security-and-the-problem-of-iterated-exits)
- [Towards Practical Security Optimizations for Binaries](https://blog.trailofbits.com/2022/03/25/towards-practical-security-optimizations-for-binaries)
- [High Assurance Rust](https://github.com/tnballo/high-assurance-rust). A book about developing secure and robust systems software.

#### Papers

- [Constant Latency in Sleepy Consensus](https://eprint.iacr.org/2022/404)
- [Making CRDTs Byzantine Fault Tolerant](https://martin.kleppmann.com/papers/bft-crdt-papoc22.pdf)
- [Gemini: elastic SNARKs for diverse environments](https://iacr.org/cryptodb/data/paper.php?pubkey=31934)
- [Instachain: Breaking the Sharding Limits via Adjustable Quorums](https://eprint.iacr.org/2022/413)

#### Projects

- [groth16-sol-verifier](https://github.com/zkLinkProtocol/groth16-sol-verifier).
  An implementation of the Groth16 zk-SNARK proving system on Solana.
- [White Whale](https://github.com/White-Whale-Defi-Platform/contracts).
  A novel decentralised arbitrage platform built on the Terra blockchain.
- [Multicall](https://github.com/scb-10x/multicall).
  On-chain query aggregator/batcher in Terra.
- [symbolic-stack-machines](https://github.com/WilfredTA/symbolic-stack-machines).
  Library for building symbolically executable stack-based virtual machines.
- [eclipse](https://github.com/eqlabs/eclipse).
  Bridging ecosystems by storing Zero-knowledge proofs of Solana votes on the Aleo blockchain.
- [sui](https://github.com/MystenLabs/sui).
  A smart contract platform with high throughput, low latency, and an
  asset-oriented programming model powered by the Move programming
  language.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

- [RUSTSEC-2022-0013: Vulnerability in regex](https://rustsec.org/advisories/RUSTSEC-2022-0013.html).
- [RUSTSEC-2022-0014: Vulnerability in openssl-src](https://rustsec.org/advisories/RUSTSEC-2022-0014.html).
- [RUSTSEC-2022-0015: pty is unmaintained](https://rustsec.org/advisories/RUSTSEC-2022-0015.html).
- **[RUSTSEC-2022-0016: Vulnerability in wasmtime](https://rustsec.org/advisories/RUSTSEC-2022-0016.html).**
- [CVE-2022-24783: Sandbox bypass leading to arbitrary code execution in Deno](https://github.com/advisories/GHSA-838h-jqp6-cf2f).

&nbsp;

## Most Active in March

[Parity](https://github.com/paritytech):
534 merged PRs, 164 closed issues, 99 open issues

[IOTA](https://github.com/iotaledger):
261 merged PRs, 102 closed issue, 42 open issues

[Fuel](https://github.com/FuelLabs):
240 merged PRs, 135 closed issues, 112 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

103 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 
48 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
19 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Anoma](https://github.com/anoma)

28 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2]), 
26 closed issues ([1][anoma-closed_issues-1]), 
20 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[anoma-merged-prs-2]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[anoma-open_issues-2]: https://github.com/anoma/ferveo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [An Overview of Anoma's Architecture](https://anoma.network/blog/an-overview-of-anomas-architecture/)

#### [ChainSafe](https://github.com/ChainSafe)

31 merged PRs ([1][chainsafe-merged-prs-1]), 
17 closed issues ([1][chainsafe-closed_issues-1]), 
30 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [COMIT](https://github.com/comit-network)

10 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 
5 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2]), 
7 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2])

[comit-merged-prs-1]: https://github.com/comit-network/maia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[comit-merged-prs-2]: https://github.com/comit-network/rendezvous-server/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[comit-merged-prs-3]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[comit-closed_issues-1]: https://github.com/comit-network/maia/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[comit-closed_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[comit-open_issues-1]: https://github.com/comit-network/maia/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[comit-open_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Concordium](https://github.com/Concordium)

16 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]), 
1 closed issues ([1][concordium-closed_issues-1]), 
18 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-euro2ccd-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[concordium-open_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Conflux](https://github.com/Conflux-Chain)

24 merged PRs ([1][conflux-merged-prs-1]), 
13 closed issues ([1][conflux-closed_issues-1]), 
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [DarkFi](https://dark.fi)

1 merged PRs ([1][darkfi-merged-prs-1]), 
5 closed issues ([1][darkfi-closed_issues-1]), 
1 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Dfinity](https://github.com/dfinity)

96 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6]), 
9 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4], [5][dfinity-closed_issues-5]), 
8 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[dfinity-merged-prs-3]: https://github.com/dfinity/icx-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[dfinity-merged-prs-4]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[dfinity-merged-prs-5]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[dfinity-merged-prs-6]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[dfinity-closed_issues-2]: https://github.com/dfinity/icx-proxy/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[dfinity-closed_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[dfinity-closed_issues-4]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[dfinity-closed_issues-5]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[dfinity-open_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [Introducing Supernova, the First Global Internet Computer Hackathon](https://medium.com/dfinity/introducing-supernova-the-first-global-internet-computer-hackathon-dbaec18e0fb3)

#### [Elrond](https://github.com/ElrondNetwork)

121 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3], [4][elrond-merged-prs-4], [5][elrond-merged-prs-5], [6][elrond-merged-prs-6], [7][elrond-merged-prs-7]), 
3 closed issues ([1][elrond-closed_issues-1], [2][elrond-closed_issues-2]), 
2 open issues ([1][elrond-open_issues-1], [2][elrond-open_issues-2])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-nft-marketplace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[elrond-merged-prs-4]: https://github.com/ElrondNetwork/sc-metabonding-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[elrond-merged-prs-5]: https://github.com/ElrondNetwork/sc-bridge-elrond/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[elrond-merged-prs-6]: https://github.com/ElrondNetwork/sc-chainlink-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[elrond-merged-prs-7]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[elrond-closed_issues-2]: https://github.com/ElrondNetwork/sc-bridge-elrond/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[elrond-open_issues-2]: https://github.com/ElrondNetwork/sc-dex-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Espresso Systems](https://github.com/EspressoSystems)

212 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5]), 
150 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4], [5][espresso_systems-closed_issues-5]), 
91 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3], [4][espresso_systems-open_issues-4])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/reef/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/cap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/reef/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[espresso_systems-closed_issues-5]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[espresso_systems-open_issues-4]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [Introducing Espresso Systems](https://www.espressosys.com/blog/introducing-espresso-systems)
- [Releasing the Jellyfish cryptography library](https://www.espressosys.com/blog/introducing-the-jellyfish-cryptography-library)

#### [Findora](https://github.com/FindoraNetwork)

66 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]), 
2 closed issues ([1][findora-closed_issues-1]), 
2 open issues ([1][findora-open_issues-1], [2][findora-open_issues-2])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[findora-merged-prs-2]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[findora-merged-prs-3]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[findora-merged-prs-4]: https://github.com/FindoraNetwork/findora-exporter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[findora-open_issues-2]: https://github.com/FindoraNetwork/findora-exporter/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Fluence](https://github.com/fluencelabs)

28 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5]), 
5 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2], [3][fluence-closed_issues-3]), 
11 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3], [4][fluence-open_issues-4], [5][fluence-open_issues-5])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fluence-merged-prs-5]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fluence-closed_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fluence-closed_issues-3]: https://github.com/fluencelabs/registry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fluence-open_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fluence-open_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fluence-open_issues-3]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fluence-open_issues-4]: https://github.com/fluencelabs/examples/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fluence-open_issues-5]: https://github.com/fluencelabs/registry/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Fuel](https://github.com/FuelLabs)

240 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10]), 
135 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7]), 
112 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6], [7][fuel-open_issues-7], [8][fuel-open_issues-8], [9][fuel-open_issues-9])

[fuel-merged-prs-1]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-merged-prs-10]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-storage/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-asm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-bft/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-5]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-6]: https://github.com/FuelLabs/fuel-types/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-7]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-8]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[fuel-open_issues-9]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Golem](https://github.com/golemfactory)

42 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4]), 
34 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3]), 
34 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[golem-merged-prs-2]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[golem-merged-prs-3]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[golem-merged-prs-4]: https://github.com/golemfactory/ya-vm-file-server/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[golem-closed_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[golem-closed_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[golem-open_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[golem-open_issues-3]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Grin](https://github.com/mimblewimble/grin)

5 merged PRs ([1][grin-merged-prs-1], [2][grin-merged-prs-2]), 
1 closed issues ([1][grin-closed_issues-1]), 
1 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[grin-merged-prs-2]: https://github.com/mimblewimble/grin-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[grin-closed_issues-1]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Holochain](https://github.com/holochain/)

44 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]), 
3 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
3 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[holochain-closed_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [IOTA](https://github.com/iotaledger)

261 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6], [7][iota-merged-prs-7], [8][iota-merged-prs-8]), 
102 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5], [6][iota-closed_issues-6]), 
42 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4], [5][iota-open_issues-5], [6][iota-open_issues-6], [7][iota-open_issues-7])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-merged-prs-5]: https://github.com/iotaledger/cli-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-merged-prs-6]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-merged-prs-7]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-merged-prs-8]: https://github.com/iotaledger/chronicle.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[iota-closed_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[iota-closed_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[iota-closed_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[iota-closed_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[iota-closed_issues-5]: https://github.com/iotaledger/cli-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[iota-closed_issues-6]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[iota-open_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[iota-open_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[iota-open_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[iota-open_issues-5]: https://github.com/iotaledger/streams/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[iota-open_issues-6]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[iota-open_issues-7]: https://github.com/iotaledger/chronicle.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [MobileCoin](https://github.com/mobilecoinfoundation)

103 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]), 
19 closed issues ([1][mobilecoin-closed_issues-1]), 
50 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

167 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10]), 
119 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8]), 
68 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8], [9][near-open_issues-9])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-6]: https://github.com/near/near-lake/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-7]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-8]: https://github.com/near/near-lake-framework/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-9]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-merged-prs-10]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-closed_issues-5]: https://github.com/near/near-lake/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-closed_issues-6]: https://github.com/near/near-lake-framework/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-closed_issues-7]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-closed_issues-8]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-5]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-6]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-7]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-8]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[near-open_issues-9]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [NEAR’s Road to Decentralization: Building Bridges](https://near.org/blog/near-bridges-decentralization-interconnection/)

#### [Nervos](https://github.com/nervosnetwork)

174 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7], [8][nervos-merged-prs-8], [9][nervos-merged-prs-9]), 
10 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4], [5][nervos-closed_issues-5]), 
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/axon/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/godwoken-scripts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-5]: https://github.com/nervosnetwork/mercury/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-6]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-7]: https://github.com/nervosnetwork/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-8]: https://github.com/nervosnetwork/molecule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-merged-prs-9]: https://github.com/nervosnetwork/overlord/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[nervos-closed_issues-3]: https://github.com/nervosnetwork/mercury/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[nervos-closed_issues-4]: https://github.com/nervosnetwork/godwoken-tests/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[nervos-closed_issues-5]: https://github.com/nervosnetwork/molecule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[nervos-open_issues-4]: https://github.com/nervosnetwork/ckb-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Oasis](https://github.com/oasisprotocol)

40 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2], [3][oasis-merged-prs-3]), 
2 closed issues ([1][oasis-closed_issues-1], [2][oasis-closed_issues-2]), 
5 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[oasis-merged-prs-2]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[oasis-merged-prs-3]: https://github.com/oasisprotocol/emerald-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[oasis-closed_issues-2]: https://github.com/oasisprotocol/emerald-paratime/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Parity](https://github.com/paritytech)

534 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15]), 
164 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13], [14][parity-closed_issues-14]), 
99 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-13]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-14]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-merged-prs-15]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-13]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-closed_issues-14]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-9]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-10]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-11]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-12]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-13]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[parity-open_issues-14]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [Privacy on Polkadot Recap](https://medium.com/zero-knowledge-validator/privacy-on-polkadot-recap-a88ae91c5864)
- [ink! 3.0: Parity’s Rust-Based Language for WASM Smart Contracts Gets a Major Update](https://www.parity.io/blog/ink-3-0-paritys-rust-based-language-gets-a-major-update)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

6 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 
9 closed issues ([1][secret_network-closed_issues-1]), 
4 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Solana](https://github.com/solana-labs/solana)

55 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]), 
27 closed issues ([1][solana-closed_issues-1]), 
78 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [Spamming Solana: a Trip Report](https://medium.com/dragonfly-research/spamming-solana-a-trip-report-d05e0455a3ba)
- [On a $20m bug in Jet Protocol](https://medium.com/coinmonks/on-a-20m-bug-in-jet-protocol-f8581599328e)
- [CashioApp Attack — what’s the vulnerability and how Soteria detects it](https://medium.com/coinmonks/cashioapp-attack-whats-the-vulnerability-and-how-soteria-detects-it-2e96b9c6d1d3)
- [Solana programs Part 1: understanding SPL Token Mint](https://medium.com/coinmonks/solana-programs-part-1-understanding-spl-token-mint-fabd13323219)

#### [Subspace Labs](https://github.com/subspace)

25 merged PRs ([1][subspace_labs-merged-prs-1]), 
8 closed issues ([1][subspace_labs-closed_issues-1]), 
2 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [TezEdge](https://github.com/tezedge)

57 merged PRs ([1][tezedge-merged-prs-1], [2][tezedge-merged-prs-2]), 
1 closed issues ([1][tezedge-closed_issues-1]), 
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[tezedge-merged-prs-2]: https://github.com/tezedge/tezedge-snapshots/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[tezedge-closed_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Zcash](https://github.com/zcash)

109 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
84 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2]), 
37 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [Sin7Y Tech Review (20): Halo2 Circuit Development](https://hackmd.io/@sin7y/SJQpj9Fxc)

&nbsp;

### Rust in Bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

23 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]), 
9 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]), 
13 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3], [4][bdk-open_issues-4], [5][bdk-open_issues-5])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[bdk-open_issues-4]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[bdk-open_issues-5]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Bitmask](https://github.com/diba-io/bitmask-core)

6 merged PRs ([1][bitmask-merged-prs-1]), 
3 closed issues ([1][bitmask-closed_issues-1]), 
9 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Electrs](https://github.com/romanz/electrs)

1 merged PRs ([1][electrs-merged-prs-1]), 
2 closed issues ([1][electrs-closed_issues-1]), 
2 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Internet2](https://github.com/internet2-wg/)

5 merged PRs ([1][internet2-merged-prs-1]), 
7 closed issues ([1][internet2-closed_issues-1]), 
2 open issues ([1][internet2-open_issues-1], [2][internet2-open_issues-2])

[internet2-merged-prs-1]: https://github.com/Internet2-WG/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[internet2-closed_issues-1]: https://github.com/Internet2-WG/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[internet2-open_issues-1]: https://github.com/Internet2-WG/rust-aluvm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[internet2-open_issues-2]: https://github.com/Internet2-WG/rust-internet2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

48 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]), 
20 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2], [3][ldk-closed_issues-3]), 
17 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[ldk-closed_issues-3]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-sample/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [LNP/BP](https://github.com/LNP-BP)

24 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2], [3][lnp/bp-merged-prs-3], [4][lnp/bp-merged-prs-4], [5][lnp/bp-merged-prs-5]), 
11 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3]), 
4 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2], [3][lnp/bp-open_issues-3])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[lnp/bp-merged-prs-2]: https://github.com/LNP-BP/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[lnp/bp-merged-prs-3]: https://github.com/LNP-BP/rust-lnpbp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[lnp/bp-merged-prs-4]: https://github.com/LNP-BP/ln-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[lnp/bp-merged-prs-5]: https://github.com/rust-amplify/rust-amplify/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/descriptor-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[lnp/bp-closed_issues-2]: https://github.com/LNP-BP/ln-types/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[lnp/bp-closed_issues-3]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[lnp/bp-open_issues-1]: https://github.com/LNP-BP/descriptor-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[lnp/bp-open_issues-2]: https://github.com/LNP-BP/ln-types/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[lnp/bp-open_issues-3]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [LNP WG](https://github.com/LNP-WG)

1 merged PRs ([1][lnp_wg-merged-prs-1]), 
0 closed issues,
2 open issues ([1][lnp_wg-open_issues-1])

[lnp_wg-merged-prs-1]: https://github.com/LNP-WG/lnp-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[lnp_wg-open_issues-1]: https://github.com/LNP-WG/lnp-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

2 merged PRs ([1][nakamoto-merged-prs-1]), 
0 closed issues,
0 open issues

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31

#### [Nomic](https://github.com/nomic-io)

5 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]), 
1 closed issues ([1][nomic-closed_issues-1]), 
0 open issues

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nomic-merged-prs-2]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[nomic-closed_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31

#### [RGB](https://github.com/rgb-wg)

0 merged PRs,
0 closed issues,
1 open issues ([1][rgb-open_issues-1])

[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

61 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3]), 
13 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2]), 
15 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

1 merged PRs ([1][rust_simplicity-merged-prs-1]), 
0 closed issues, 
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31

#### [Sapio](https://github.com/sapio-lang/sapio)

7 merged PRs ([1][sapio-merged-prs-1]), 
1 closed issues ([1][sapio-closed_issues-1]), 
0 open issues

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[sapio-closed_issues-1]: https://github.com/sapio-lang/sapio/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31

#### [Talaia](https://github.com/talaia-labs/rust-teos)

2 merged PRs ([1][talaia-merged-prs-1]), 
0 closed issues, 
14 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

85 merged PRs ([1][ethers-rs-merged-prs-1]), 
16 closed issues ([1][ethers-rs-closed_issues-1]), 
12 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

3 merged PRs ([1][lighthouse-merged-prs-1]), 
22 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]), 
23 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

- [Lighthouse Update #40](https://lighthouse.sigmaprime.io/update-40.html)

#### [Rust Ethereum](https://github.com/rust-ethereum)

3 merged PRs ([1][rust_ethereum-merged-prs-1]), 
0 closed issues,
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

1 merged PRs ([1][rust_web3-merged-prs-1]), 
2 closed issues ([1][rust_web3-closed_issues-1]), 
3 open issues ([1][rust_web3-open_issues-1])

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[rust_web3-closed_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31
[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2022-03-01..2022-03-31

#### [zkSync](https://github.com/matter-labs/zksync)

7 merged PRs ([1][zksync-merged-prs-1], [2][zksync-merged-prs-2]), 
43 closed issues ([1][zksync-closed_issues-1]), 
0 open issues

[zksync-merged-prs-1]: https://github.com/matter-labs/zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[zksync-merged-prs-2]: https://github.com/matter-labs/compiler-solidity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-03-01..2022-03-31
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-03-01..2022-03-31

&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Apr 13-14 | Paris, France

[Paris Blockchain Week Summit](https://www.pbwsummit.com/)

Apr 16 - May 13 | Online

[Scaling Ethereum](https://scaling.ethglobal.co/)

Apr 18-25 | Amsterdam, Netherlands

[Devconnect](https://devconnect.org/)

Apr 22-24 | Amsterdam, Netherlands

[ETHAmsterdam](https://amsterdam.ethglobal.com/)

May 2-6 | Canada

[Financial Cryptography and Data Security 2022](http://fc22.ifca.ai/index.html)

May 10 - Jun 20 | Online

[Supernova: Dfinity hackthon](https://dfinity.org/supernova/)

May 29-30 | Trondheim, Norway

[CBCrypto 2022: International Workshop on Code-Based Cryptography](https://www.cb-crypto.org/)

May 30 - Jun 3 | Trondheim, Norway

[Eurocrypt 2022](https://eurocrypt.iacr.org/2022/)

Jun 13-17 | Šibenik, Croatia

[Summer school on real-world crypto and privacy](https://summerschool-croatia.cs.ru.nl/2022/)

Aug 13-18 | Santa Barbara, CA, USA

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
- [Software Library Engineer (Rust)](https://grnh.se/fc3876861us)
- [Software Library Engineer (C++)](https://grnh.se/69d260dc1us)
- [Full-Stack Software Engineer](https://grnh.se/aed921721us)
- [Network Engineer](https://grnh.se/6ac8f7f11us)
- [Sr. Product Manager](https://grnh.se/11354dd01us)
- [Product Manager](https://grnh.se/1bdd2ced1us)
- [Technical Project Manager](https://grnh.se/ca7b51b81us)

Parity Technologies
- [Parachains Engineer - Common Good](https://boards.greenhouse.io/parity/jobs/4794657003)
- [Core Runtime Engineer - Substrate](https://grnh.se/dddd76283us)
- [Rust / Core Engineer - General Posting](https://grnh.se/1cf2de503us) - engineers new to/learning Rust are very welcomed!

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


