---
title: "RiB Newsletter #19"
description: "#19 - December 2020"
date: 2021-01-06
slug: "/"
categories:
  - "newsletters"
summary: ""
---

Welcome to the #19 edition of Rust in Blockchain,
the hypest newsletter about the hypest tech.
[Previous: #18](/newsletters/.../).

[Aleo's Leo](https://github.com/AleoHQ/leo):
202 merged PRs ([1][aleo-merged-prs-1]),
67 closed issues ([1][aleo-closed_issues-1]), 
53 open issues ([1][aleo-open_issues-1])

[aleo-merged-prs-1]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-12-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-12-31
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2020-01-01..2020-12-31

[Parity's ink](https://github.com/paritytech):
166 merged PRs ([1][parity-merged-prs-1]), 112 closed issues ([1][parity-closed_issues-1]), 
36 open issues ([1][parity-open_issues-1])

[parity-merged-prs-1]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-12-31
[parity-closed_issues-1]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-12-31
[parity-open_issues-1]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2020-01-01..2020-12-31

[Secret Network's ](https://github.com/enigmampc):
9 merged PRs ([1][secret_network-merged-prs-1]),
0 closed issues (), 
5 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-12-31
[secret_network-open_issues-1]: https://github.com/enigmampc/secret-toolkit/issues?q=is%3Aissue+is%3Aopen+created%3A2020-01-01..2020-12-31

[Near's Rust libraries](https://github.com/near/nearcore):
76 merged PRs ([1][near-merged-prs-1]),
63 closed issues ([1][near-closed_issues-1]), 
40 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-12-31
[near-closed_issues-1]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-12-31
[near-open_issues-1]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-01-01..2020-12-31


## Thanks

Thanks to contributors:

[Adam Gutierrez][contributor-ag]

_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#20 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributor-ag]: https://github.com/adamisrusty
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…





&nbsp;


## Interesting Things

#### News

- New launch: [MobileCoin Main Net](https://medium.com/@mobilecoinfoundation/mobilecoin-main-net-8e355d82c726)

#### Blog Posts

- [A Brief Breakdown of Monero’s Ongoing Network Attacks](https://sethsimmons.me/posts/moneros-ongoing-network-attack/)
- [Understanding Peer-to-Peer Git Forges with Radicle](http://blog.vmsplice.net/2020/12/understanding-peer-to-peer-git-forges.html)
- [An Incomplete Guide to Rollups](https://vitalik.ca/general/2021/01/05/rollup.html)
- [Notes on cross-compiling Rust](https://john-millikin.com/notes-on-cross-compiling-rust)

#### Papers 

- [A Languge-Based Approach to Smart Contract Engineering](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2020/EECS-2020-220.html)
- [Freedom to (Smart) Contract: The Myth of Code and Blockchain Governance Law](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3715647)
- [VM Matters: A Comparison of WASM VMs and EVMs in the Performance of Blockchain Smart Contracts](https://arxiv.org/abs/2012.01032)
- [RouTEE: A Secure Payment Network Routing Hub using Trusted Execution Environments](https://arxiv.org/abs/2012.04254)
- [Lockable Signatures for Blockchains: Scriptless Scripts for All Signatures](https://eprint.iacr.org/2020/1613)
- [Adaptive layer-two dispute periods in blockchains](https://eprint.iacr.org/2020/1601)
- [Unifying Compilers for SNARKs, SMT, and More](https://eprint.iacr.org/2020/1586)  	    	      
- [SoK: Algorithmic Incentive Manipulation Attacks on Permissionless PoW Cryptocurrencies](https://eprint.iacr.org/2020/1614)

#### Projects

- [Zinc Framework](https://github.com/matter-labs/zinc): the ZK circuit programming language and VM.
  Zinc is designed specifically for ZK-circuits and ZKP-based smart contract development, so some differences from Rust are inevitable.
  The official [Zinc book](https://zinc.zksync.io/).
- [aquamarine](https://github.com/fluencelabs/aquamarine).
  Aquamarine is a distributed choreography language & platform.
- [MASP](https://github.com/metastatedev/masp).
  Rust crates for working with the Multi Asset Shielded Pool extensions of the Sapling circuits from Zcash.
  Intro: [A gentle introduction to the multi-asset shielded pool project](https://github.com/metastatedev/masp).
- [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs).
  Discover historic Miner Extractable Value (MEV) opportunities.
  A blog post about this project: [Flashbots: Frontrunning the MEV Crisis](https://ethresear.ch/t/flashbots-frontrunning-the-mev-crisis/8251).
- [Plasm](https://github.com/staketechnologies/Plasm).
  The Scaling DApps Platform on Polkadot using Plasma and State Channel.
- [plonkit](https://github.com/Fluidex/plonkit).
  A zkSNARK toolkit to work with circom zkp DSL in plonk proof system.
  The project announcement: [Announcing FluiDex: Building the first PLONK layer2 DEX on Ethereum](https://fluid-dex.medium.com/announcing-fluidex-building-the-first-plonk-layer2-dex-on-ethereum-e19136304a5d) and tech intro in detail:
  [Fluidex: A zkrollup layer2 DEX](https://lispc.github.io/2020/11/30/fluidex-a-zkrollup-layer2-dex).
- [Reverie](https://github.com/trailofbits/reverie).
  Reverie is an implementation (prover and verifier) of the MPC-in-the-head NIZKPoK outlined in
  [Improved Non-Interactive Zero Knowledge with Applications to Post-Quantum Signatures](https://eprint.iacr.org/2018/475). 
- [sn_client](https://github.com/maidsafe/sn_client).
  A set of libraries providing a way for developers to consume and use the Safe Network facilities.
- [sn_node](https://github.com/maidsafe/sn_node).
  An Implementation of a Safe Network Vault.
- [zkutil](https://github.com/poma/zkutil).
  A tool to work with zkSNARK circuits generated by Circom compiler.


&nbsp;

## Most Active in December

[Parity](https://github.com/paritytech):
204 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5]),
77 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
60 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[Solana](https://github.com/solana-labs/solana):
272 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
18 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
40 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Zcash](https://z.cash/):
104 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
42 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
38 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

&nbsp;

## Project Updates

#### [Aleo](https://github.com/AleoHQ)

40 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2]), 24 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]), 
15 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[aleo-open_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- Blog: [How Zero Knowledge is Rebalancing the Scales of the Internet](https://www.aleo.org/post/how-zero-knowledge-is-rebalancing-the-internet)
- PR: [Fixes conditional and early returns](https://github.com/AleoHQ/leo/pull/469) by [@collinc97](https://github.com/collinc97)
- PR: [Expression breakout](https://github.com/AleoHQ/leo/pull/478) by [@Protryon](https://github.com/Protryon)
- PR: [Improve pow & mul performance](https://github.com/AleoHQ/leo/pull/464) by [@ljedrz](https://github.com/ljedrz)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

27 merged PRs ([1][rust-bitcoin-merged-prs-1], [2][rust-bitcoin-merged-prs-2], [3][rust-bitcoin-merged-prs-3]), 5 closed issues ([1][rust-bitcoin-closed_issues-1], [2][rust-bitcoin-closed_issues-2]), 
4 open issues ([1][rust-bitcoin-open_issues-1], [2][rust-bitcoin-open_issues-2], [3][rust-bitcoin-open_issues-3])

[rust-bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[rust-bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[rust-bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[rust-bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[rust-bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[rust-bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[rust-bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[rust-bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- PR: [New PSBT global keys](https://github.com/rust-bitcoin/rust-bitcoin/pull/499) by [@dr-orlovsky](https://github.com/dr-orlovsky)
- PR: [Initiate gossip_queries](https://github.com/rust-bitcoin/rust-lightning/pull/736) by [@bmancini55](https://github.com/bmancini55)
- PR: [Make Inventory and NetworkMessage enums exhaustive](https://github.com/rust-bitcoin/rust-bitcoin/pull/496) by [@stevenroose](https://github.com/stevenroose)


#### [COMIT](https://github.com/comit-network)

68 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2]), 7 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2]), 
11 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[comit-closed_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[comit-closed_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- PR: [Resume command and global database cl-parameter](https://github.com/comit-network/xmr-btc-swap/pull/88) by [@da-kami](https://github.com/da-kami)
- PR: [T1Expired state for Bob and check expiries in states after both locked](https://github.com/comit-network/xmr-btc-swap/pull/94) by [@da-kami](https://github.com/da-kami)
- PR: [ Bob refunds swap after restart that requires communication](https://github.com/comit-network/xmr-btc-swap/pull/100) by [@D4nte](https://github.com/D4nte)


#### [Fluence](https://github.com/fluencelabs)

60 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]), 1 closed issues ([1][fluence-closed_issues-1]), 
1 open issues ([1][fluence-open_issues-1])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/fce/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquamarine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- PR: [Introduce security tetraplets](https://github.com/fluencelabs/aquamarine/pull/32) by [@michaelvoronov](https://github.com/michaelvoronov)
- PR: [Send particle.data in base64 through the wire](https://github.com/fluencelabs/fluence/pull/1008) by [@folex](https://github.com/folex)
- PR: [Implement two last fold iterable usage scenarious](https://github.com/fluencelabs/aquamarine/pull/51) by [@michaelvoronov](https://github.com/michaelvoronov)

#### [Holochain](https://github.com/holochain/)

56 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4]), 9 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2], [3][holochain-closed_issues-3]), 
5 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[holochain-merged-prs-4]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[holochain-closed_issues-2]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[holochain-closed_issues-3]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[holochain-open_issues-2]: https://github.com/holochain/lair/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News: [Holochain Dev Pulse 86](https://medium.com/holochain/steady-progress-455e932d2aa1)
- PR: [Inline zome](https://github.com/holochain/holochain/pull/512) by [@maackle](https://github.com/maackle)
- PR: [[TK-06381] Many fixes to gossip and other parts of holochain](https://github.com/holochain/holochain/pull/518) by [@freesig](https://github.com/freesig)

#### [Diem](https://www.diem.com)

157 merged PRs ([1][diem-merged-prs-1], [2][diem-merged-prs-2], [3][diem-merged-prs-3]), 7 closed issues ([1][diem-closed_issues-1]), 
9 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[diem-merged-prs-2]: https://github.com/diem/rosetta-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[diem-merged-prs-3]: https://github.com/diem/bcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- PR: [[move-lang] allow _x to bind but do not warn as unused local](https://github.com/diem/diem/pull/6786) by [@mengxu-fb](https://github.com/mengxu-fb)
- PR: [network: enable having trusted peers even in non-validator networks](https://github.com/diem/diem/pull/6878) by [@bmwill](https://github.com/bmwill)
- PR: [[State Sync] Use checked arithmetic operations to avoid over/underflows.](https://github.com/diem/diem/pull/7065) by [@JoshLind](https://github.com/JoshLind)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

0 merged PRs (), 37 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]), 
33 open issues ([1][lighthouse-open_issues-1])

[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[lighthouse-closed_issues-2]: https://github.com/sigp/beacon-fuzz/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- Blog: [Eth2 on MacOS: A beginners guide for the technically-challenged](https://lighthouse.sigmaprime.io/macos-guide.html)

#### [MobileCoin](https://www.mobilecoin.com/)

46 merged PRs ([1][mobilecoin-merged-prs-1]), 2 closed issues ([1][mobilecoin-closed_issues-1]), 
11 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News: [Mechanics of MobileCoin: Chapters 1+2](https://mobilecoinfoundation.medium.com/mechanics-of-mobilecoin-chapters-1-2-273b5a42b4e)
- PR: [Encrypt account key at rest in mobilecoind](https://github.com/mobilecoinfoundation/mobilecoin/pull/577) by [@eranrund](https://github.com/eranrund)
- PR: [Mobilecoind db encryption: Take 2](https://github.com/mobilecoinfoundation/mobilecoin/pull/585) by [@eranrund](https://github.com/eranrund)
- PR: [Wallet service](https://github.com/mobilecoinfoundation/mobilecoin/pull/594) by [@sugargoat](https://github.com/sugargoat)

#### [NEAR](https://github.com/nearprotocol/nearcore)

39 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 39 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2]), 
39 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[near-merged-prs-2]: https://github.com/near/borsh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[near-merged-prs-3]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[near-closed_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[near-open_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[near-open_issues-3]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News: [2020 NEAR In Review & Ecosystem Tour](https://near.org/blog/2020-near-in-review-ecosystem-tour/)
- Videos:
  - [Cross-contract calls in Rust](https://www.youtube.com/watch?v=971dTz6nM2g)
  - NEAR Live Contract Review
    - [Episode 8: RE STAKE token](https://www.youtube.com/watch?v=KvXfEXUbcqA)
    - [Episode 7: Berry Farm](https://www.youtube.com/watch?v=H3QvYHjunwc)
    - [Episode 6: STAKE fungible token](https://www.youtube.com/watch?v=7g6C-UeDumg)
- PR: [EVM precompile](https://github.com/near/nearcore/pull/3257) by [@ilblackdragon](https://github.com/ilblackdragon)
- PR: [add performance metrics feature](https://github.com/near/nearcore/pull/3738) by [@pmnoxx](https://github.com/pmnoxx)
- PR: [feat(testing): bridge testing infrastructure major update](https://github.com/near/nearcore/pull/3658) by [@Kouprin](https://github.com/Kouprin)

#### [Nervos](https://github.com/nervosnetwork)

65 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]), 10 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
1 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News:
  - Nervos CKB Development Dossier [#43](https://medium.com/nervosnetwork/nervos-ckb-development-43-4ab91ef0de6d),
  [#42](https://medium.com/nervosnetwork/nervos-ckb-development-dossier-42-9d6321cc5362)
  - CKB Weekly: [Exploring the Yield Dollar](https://ckbweekly.substack.com/p/exploring-the-yield-dollar)
- PR: [doc: network doc](https://github.com/nervosnetwork/ckb/pull/2369) by [@driftluo](https://github.com/driftluo)
- PR: [feat: chaos memory mode](https://github.com/nervosnetwork/ckb-vm/pull/118) by [@mohanson](https://github.com/mohanson)
- PR: [chain freezer](https://github.com/nervosnetwork/ckb/pull/2297) by [@zhangsoledad](https://github.com/zhangsoledad)

#### [Parity](https://github.com/paritytech)

204 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5]), 77 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
60 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[parity-merged-prs-4]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News: [Rococo V1 - A Holiday Gift to the Polkadot Community](https://polkadot.network/rococo-v1-a-holiday-gift-to-the-polkadot-community/)
- Blog:
  - [Polkadot 2020 Roundup](https://polkadot.network/polkadot-2020-roundup/)
  - [DeFi on Polkadot: An Ecosystem Overview](https://www.parity.io/defi-on-polkadot-an-ecosystem-overview/)
- PR: [Add `pallet` attribute macro to declare pallets](https://github.com/paritytech/substrate/pull/6877) by [@thiolliere](https://github.com/thiolliere)
- PR: [jaeger integration to debug parachains](https://github.com/paritytech/polkadot/pull/2047) by [@drahnr](https://github.com/drahnr)
- PR: [Streamline frame_system weight parametrization](https://github.com/paritytech/substrate/pull/6629) by [@tomusdrw](https://github.com/tomusdrw)
- PR: [Merkle Mountain Range pallet](https://github.com/paritytech/substrate/pull/7312) by [@tomusdrw](https://github.com/tomusdrw)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

11 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 11 closed issues ([1][secret_network-closed_issues-1]), 
7 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[secret_network-merged-prs-2]: https://github.com/enigmampc/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News: [Secret Network Tokenomics and Ecosystem Pool](https://scrt.network/blog/secret-network-tokenomics-and-ecosystem-pool)
- PR: [Add init and query calls, docstrings, and examples](https://github.com/enigmampc/secret-toolkit/pull/17) by [@baedrik](https://github.com/baedrik)
- PR: [Update secretcli.md](https://github.com/enigmampc/SecretNetwork/pull/701) by [@moonstash](https://github.com/moonstash)
- PR: [Creating macros for validator syntax extenstion](https://github.com/enigmampc/SecretNetwork/pull/689) by [@PumpkinSeed](https://github.com/PumpkinSeed)

#### [Solana](https://github.com/solana-labs/solana)

272 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 18 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
40 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News:
  - [Solana Year in Review 2020](https://medium.com/solana-labs/year-in-review-2020-c3731d1cc8a)
  - [Solana Ecosystem News](https://medium.com/solana-labs/solana-ecosystem-news-1ba12b6fb8d3)
  - [Mainnet Beta Stall - Postmortem](https://medium.com/solana-labs/mainnet-beta-stall-postmortem-ba0c6064e3)
- PR: [Add poh speed test and calibration logic](https://github.com/solana-labs/solana/pull/14292) by [@sakridge](https://github.com/sakridge)
- PR: [caches staked nodes computed from vote-accounts](https://github.com/solana-labs/solana/pull/13929) by [@behzadnouri](https://github.com/behzadnouri)
- PR: [Multi-account withdraw added the stake-pool CLI](https://github.com/solana-labs/solana-program-library/pull/895) by [@ysavchenko](https://github.com/ysavchenko)


#### [Zcash](https://z.cash/)

104 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 42 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
38 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-12-01..2020-12-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-12-01..2020-12-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-12-01..2020-12-31

- News: [ECC Transparency Report for Q2 2020](https://electriccoin.co/blog/ecc-transparency-report-for-q2-2020/)
- Blog: [Fuzzing Zcash with Kubernetes](https://electriccoin.co/blog/fuzzing-zcash-with-kubernetes/)
- PR: [Replace Tweedle curves with Pasta curves](https://github.com/zcash/halo2/pull/84) by [@ebfull](https://github.com/ebfull)
- PR: [Extract permutation argument and introduce typed challenges](https://github.com/zcash/halo2/pull/70) by [@str4d](https://github.com/str4d)
- PR: [Implement Bitcoin Merkle trees](https://github.com/ZcashFoundation/zebra/pull/1386) by [@hdevalence](https://github.com/hdevalence)

&nbsp;

## Events

`panic!()`

&nbsp;

## Careers

Aleo | San Francisco, CA; Remote
- [Rust Developer - Programming Languages](https://docs.google.com/document/d/1Q-5y9V6QmBBLSNiHRrYRCvNKuxFLy6EnHe4DKPESMX4/edit?usp=sharing)

DFINITY | San Francisco, CA; Palo Alto, CA; Zurich, Switzerland; Remote
- [Software Engineer, Distributed Systems](https://grnh.se/1f702d2e2us)
- [Software Engineer, Front-End](https://grnh.se/b8daa0ed2us)
- [Software Engineer, SDK](https://grnh.se/92e1344b2us)

Chainflip | Berlin, Germany
- [Rust/C++ Developer](https://cryptojobslist.com/jobs/rust-c-developer-at-chainflip-berlin)

Massa | Remote
- [Full remote Rust developer, long-term contract (French CDI)](https://massa.network/#jobs)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#20 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


