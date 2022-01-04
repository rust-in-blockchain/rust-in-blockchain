---
title: "RiB Newsletter #31"
description: "December 2021"
date: 2022-01-05
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #31 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #30](/newsletters/rib-newsletter-30/).

&nbsp;

## Thanks

Thanks to contributors:

[Dan Shields],
[Harlan T Wood],
John Adler,
[Marcin],
[Max Wegman],
Samuel Dare,
[Squirrel],

_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Dan Shields]: Https://github.com/NukeManDan
[Harlan T Wood]: https://github.com/harlantwood
[Marcin]: https://github.com/mmagician
[Max Wegman]: https://github.com/mastermaxy
[Squirrel]: https://github.com/gilescope
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News


#### Blog Posts

- [A breakdown of different output types and their address formats](https://murch.one/2021/12/23/a-breakdown-of-different-output-types-and-their-address-formats/)
- [Disclosing Shamir’s Secret Sharing vulnerabilities and announcing ZKDocs](https://blog.trailofbits.com/2021/12/21/disclosing-shamirs-secret-sharing-vulnerabilities-and-announcing-zkdocs/)
- [SlowMist: Our review of the blockchain security industry in 2021](https://slowmist.medium.com/our-review-of-the-blockchain-security-industry-in-2021-with-global-losses-exceeding-9-8-billion-60d93efbfca3)

#### Papers

- [Alpha-Rays: Key Extraction Attacks on Threshold ECDSA Implementations](https://eprint.iacr.org/2021/1621)
- [A zk-evm specification](https://ethresear.ch/t/a-zk-evm-specification/11549)
- [Efficient and Post-Quantum Zero-Knowledge Proofs for Blockchain Confidential Transaction Protocols](https://eprint.iacr.org/2021/1674)
- [SoK: Blockchain Light Clients](https://eprint.iacr.org/2021/1657)
- [SoK: Mitigation of Front-running in Decentralized Finance](https://eprint.iacr.org/2021/1628)
- [Universal Atomic Swaps: Secure Exchange of Coins Across All Blockchains](https://eprint.iacr.org/2021/1612)
- [Verifiable Encryption from MPC-in-the-Head](https://eprint.iacr.org/2021/1704)
- [Zero-Knowledge for Homomorphic Key-Value Commitments with Applications to Privacy-Preserving Ledgers](https://eprint.iacr.org/2021/1678)

#### Projects

- [Akula](https://github.com/akula-bft/akula).
  Ethereum client written in Rust, based on [Erigon client architecture](https://github.com/ledgerwatch/interfaces).
- [arloader](https://github.com/CalebEverett/arloader).
  Rust command line application and client for uploading files to Arweave.
- [Foundry](https://github.com/gakonst/foundry/) is a blazing fast,
  portable and modular toolkit for Ethereum application development
  written in Rust.
- [Gear](https://github.com/gear-tech/gear) 
  is a Substrate-based smart-contract platform allowing anyone to run dApp in a few minutes. 
- [gp-v2-services](https://github.com/gnosis/gp-v2-services).
  Off-chain services for Gnosis Protocol v2
- [interBTC](https://github.com/interlay/interbtc).
  A trust-minimized bridge from Bitcoin to Polkadot.
- [orion](https://github.com/orion-rs/orion).
  Usable, easy and safe pure-Rust crypto.
- [Pathfinde](https://github.com/eqlabs/pathfinder).
  A StarkNet full node written in Rust.
- [RealTPS](https://github.com/Aimeedeer/realtps)
  measures the current number of transactions per second committed by various blockchains.
- [Shade Protocol](https://github.com/securesecrets/shade)
  is an array of connected privacy-preserving dApps built on Secret Network.
- [Sway](https://github.com/FuelLabs/sway)
  is a language developed for the Fuel blockchain.
  [doc: The Sway Programming Language](https://fuellabs.github.io/sway).

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust


&nbsp;

## Most Active in December

[Parity](https://github.com/paritytech):
336 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7]), 
115 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
75 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4])

[Solana](https://github.com/solana-labs/solana):
265 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
46 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
46 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])


[NEAR](https://github.com/nearprotocol/nearcore):
251 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 
51 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
62 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])


&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

110 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 
52 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
30 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Anoma](https://github.com/anoma)

26 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2]), 
22 closed issues ([1][anoma-closed_issues-1]), 
20 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[anoma-merged-prs-2]: https://github.com/anoma/ferveo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

- [Hash Functions in Plonkup](https://anoma.network/blog/hash-functions-in-plonkup/)
- [Agents of Anoma: Matchmaking Node Operators](https://anoma.network/blog/agents-of-anoma-matchmaking-node-operators/)

#### [ChainSafe](https://github.com/ChainSafe)

36 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]), 
35 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2]), 
17 open issues ([1][chainsafe-open_issues-1], [2][chainsafe-open_issues-2])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/filecoindot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/filecoindot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[chainsafe-open_issues-2]: https://github.com/ChainSafe/filecoindot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [COMIT](https://github.com/comit-network)

27 merged PRs ([1][comit-merged-prs-1]), 
5 closed issues ([1][comit-closed_issues-1]), 
7 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Concordium](https://github.com/Concordium)

17 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]), 
4 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2]), 
4 open issues ([1][concordium-open_issues-1])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Conflux](https://github.com/Conflux-Chain)

21 merged PRs ([1][conflux-merged-prs-1]), 
1 closed issues ([1][conflux-closed_issues-1]), 
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [DarkFi](https://dark.fi)

2 merged PRs ([1][darkfi-merged-prs-1]), 
5 closed issues ([1][darkfi-closed_issues-1]), 
12 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Dfinity](https://github.com/dfinity)

18 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4]), 
2 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2]), 
8 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[dfinity-merged-prs-4]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[dfinity-closed_issues-1]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[dfinity-closed_issues-2]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[dfinity-open_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[dfinity-open_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Diem](https://github.com/diem)

143 merged PRs ([1][diem-merged-prs-1]), 
20 closed issues ([1][diem-closed_issues-1]), 
16 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Elrond](https://github.com/ElrondNetwork)

41 merged PRs ([1][elrond-merged-prs-1]), 
2 closed issues ([1][elrond-closed_issues-1]), 
3 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

- [Meet Elrond Play, The Web IDE Smart Contracts Playground](https://elrond.com/blog/elrond-play-web-ide/)

#### [Findora](https://github.com/FindoraNetwork)

19 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2]), 
9 closed issues ([1][findora-closed_issues-1]), 
5 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[findora-merged-prs-2]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Fluence](https://github.com/fluencelabs)

24 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3]), 
10 closed issues ([1][fluence-closed_issues-1]), 
3 open issues ([1][fluence-open_issues-1])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[fluence-open_issues-1]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Golem](https://github.com/golemfactory)

17 merged PRs ([1][golem-merged-prs-1]), 
7 closed issues ([1][golem-closed_issues-1]), 
21 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Grin](https://github.com/mimblewimble/grin)

6 merged PRs ([1][grin-merged-prs-1]), 
4 closed issues ([1][grin-closed_issues-1]), 
3 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Holochain](https://github.com/holochain/)

26 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]), 
5 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
2 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[holochain-closed_issues-2]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Interledger](https://github.com/interledger-rs)

1 merged PRs ([1][interledger-merged-prs-1]), 
0 closed issues, 
1 open issues ([1][interledger-open_issues-1])

[interledger-merged-prs-1]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[interledger-open_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [IOTA](https://github.com/iotaledger)

10 merged PRs ([1][iota-merged-prs-1]), 
5 closed issues ([1][iota-closed_issues-1]), 
2 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

7 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]), 
5 closed issues ([1][lighthouse-closed_issues-1]), 
11 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [MobileCoin](https://github.com/mobilecoinfoundation)

19 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]), 
1 closed issues ([1][mobilecoin-closed_issues-1]), 
2 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/fog/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

251 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 
51 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
62 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[near-closed_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

- [NEAR 2021: A Year in Review](https://near.org/blog/near-2021-a-year-in-review/)
- [NEAR MetaBUILD 2: Join the Hackathon and Build an App](https://near.org/blog/near-metabuild-2-join-the-hackathon-and-build-an-app/)
- [NEAR Q4: Hackathons, Upgrades and Integrations](https://near.org/blog/near-q4-update-ecosystem-sharding-launch/)

#### [Nervos](https://github.com/nervosnetwork)

82 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]), 
6 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3], [4][nervos-open_issues-4])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[nervos-open_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[nervos-open_issues-4]: https://github.com/nervosnetwork/ckb-std/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Parity](https://github.com/paritytech)

336 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7]), 
115 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
75 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[parity-merged-prs-5]: https://github.com/paritytech/parity-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[parity-merged-prs-6]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[parity-merged-prs-7]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[parity-closed_issues-3]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[parity-open_issues-4]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
  
- [Polkadot 2021 Roundup](https://polkadot.network/blog/polkadot-2021-roundup/)
- [Parachains are Live! Polkadot Launch is Now Complete](https://polkadot.network/blog/parachains-are-live-polkadot-launch-is-now-complete/)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

49 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]), 
24 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3], [4][rust_bitcoin-closed_issues-4]), 
13 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[rust_bitcoin-merged-prs-4]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[rust_bitcoin-merged-prs-5]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[rust_bitcoin-closed_issues-4]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[rust_bitcoin-open_issues-4]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Rust Ethereum](https://github.com/rust-ethereum)

3 merged PRs ([1][rust_ethereum-merged-prs-1]), 
2 closed issues ([1][rust_ethereum-closed_issues-1]), 
0 open issues

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

2 merged PRs ([1][secret_network-merged-prs-1]), 
19 closed issues ([1][secret_network-closed_issues-1]), 
3 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

- [Shade Protocol Snapshots Completed](https://medium.com/@shadeprotocoldevs/shade-protocol-snapshots-completed-38e61ac58369)

#### [Solana](https://github.com/solana-labs/solana)

265 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
46 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
46 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

- [Solana internals Part 1: what are the native on-chain programs and why do they matter?](https://medium.com/coinmonks/solana-internals-part-1-what-are-the-native-on-chain-programs-and-why-do-they-matter-61c981483e86)

#### [Spacemesh](https://github.com/spacemeshos)

6 merged PRs ([1][spacemesh-merged-prs-1]), 
50 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
64 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Subspace Labs](https://github.com/subspace)

43 merged PRs ([1][subspace_labs-merged-prs-1]), 
14 closed issues ([1][subspace_labs-closed_issues-1]), 
2 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [TezEdge](https://github.com/tezedge)

35 merged PRs ([1][tezedge-merged-prs-1]), 
1 closed issues ([1][tezedge-closed_issues-1]), 
4 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[tezedge-closed_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [Zcash](https://github.com/zcash)

87 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
58 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
103 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-12-01..2021-12-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs, 
1 closed issues ([1][zksync-closed_issues-1]), 
6 open issues ([1][zksync-open_issues-1])

[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-12-01..2021-12-31
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2021-12-01..2021-12-31


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Dec 22, 2021 - Feb 10, 2022 | Online

[NEAR MetaBUILD Hackathon](https://metabuild.devpost.com/)

Jan 24-26, 2022 | Arrillaga Alumni Center, Stanford University

[SBC'22: The Science of Blockchain Conference 2022](https://cbr.stanford.edu/sbc22/)

Feb 5-6, 2022 | Online

[FOSDEM 2022](https://fosdem.org/2022/)

Feb 14-18, 2022 | Canada

[Financial Cryptography and Data Security 2022](http://fc22.ifca.ai/index.html)

Apr 2022 | Amsterdam

[Devconnect](https://devconnect.org/)

Apr 6-9, 2022 | Portland, OR

[dystopia Fest: Summit & Hackathon](https://q1.dystopiafest.com/)

Apr 16 - May 13th, 2022 | Online

[Scaling Ethereum](https://scaling.ethglobal.co/)


&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

DEX Labs | Remote
- [Rust Engineer](https://dex-labs.breezy.hr/p/fea339739adb)

Parity Technologies | Berlin, Lisbon, or Remote
- [Rust Core Engineer - Solidity Compiler (Solang)](https://grnh.se/a5a5c0a33us)
- [Rust Core Engineer - Smart Contract Platform](https://grnh.se/cb272e3b3us)
- [Multiple other Rust / Blockchain Engineering positions](https://www.parity.io/jobs)

Web3 Foundation | Zug or Remote
- [Technical Grants Lead](https://web3.bamboohr.com/jobs/view.php?id=99)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;


Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


