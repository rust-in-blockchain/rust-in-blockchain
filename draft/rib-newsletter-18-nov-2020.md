---
title: "RiB Newsletter #18"
description: "#18 - November 2020"
date: 2020-12-02
slug: "/2020-12-02-"
categories:
  - "newsletters"
summary: ""
---

Welcome to the #18 edition of Rust in Blockchain,
the hypest newsletter about the hypest tech.
[Previous: #17](/newsletters/2020-11-04-trick-or-trait/).

Hope everybody stays safe and healthy.
It's time to be even more patient with
blockchain development and pandemic restrictions. 

[Oasis launched their mainnet][oasismainnet] this month,
while all the attention seems to be on [Eth2's launch][eth2].
NEAR has a [whiteboard video with the Sigma Prime team][neareth2],
who develops Lighthouse, the Eth2 client in Rust,
introduces network layer in Eth2, how the nodes communicate, and more. 

From projects we have been covered, Parity and NEAR released
many good videos this month, which are great resources for
developers to learn programming blockchain.
Meanwhile, Brian started experimenting with different layer1 blockchains
to compare the smart contract development experience among them.
There are some freshly published posts about the impression with Substrate:

- 1:
- 2:
- 3:
- 4: 

For further progress, follow the repo on GitHub:
[A comparison of Rust smart contract platforms][brsonrepo].
Suggestions are very welcome.

We open-sourced [ribbot], the script that helps us
generate engineering progress from GitHub repos.
It currently has no documentation or readability.
We plan to refactor it (slowly) and hope it can be
a general purposed program that is useful for other projects. 

RiB received emails from many organizations
with the request for advertising in the newsletter and the website.
As RiB is always a community project, we do not want to
decide for the RiB community.
We open the question here, asking your thoughts about advertising in RiB.
Please reply to this email directly, or discuss on the [Telegram group][ribtg].

[ribbot]: https://github.com/rust-in-blockchain/ribbot
[brsonrepo]: https://github.com/brson/rust-contract-comparison
[eth2]: https://twitter.com/ethereum/status/1333743998637400073

## Thanks

Thanks to contributors:
[apruden2008][contributor-ap],
[Paulii][contributor-pa],
[Stanley Jones][contributor-sj],
[Tony Arcieri][contributor-tony],
[Brian Anderson][contributorba], and [Aimee Zhu][contributoraz].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#19 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributor-sj]: https://github.com/stanleygjones
[contributor-tony]: https://github.com/tarcieri
[contributor-ap]: https://github.com/apruden2008
[contributor-pa]: https://github.com/PauliiG22
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[arkworks].

Arkworks is "an ecosystem for developing and programming with zkSNARKs"
as they said on the GitHub org page.

It has a heck bunch of Rust cryptography libraries
for designing and working with zero-knowledge succinct
non-interactive arguments (zkSNARKs), and most of them are under active development:
- [`snark`] - interfaces for zkSNARKs
- [`curves`] - implementations of popular elliptic curves
- [`algebra`] - libraries for finite field, elliptic curve, and polynomial arithmetic
- [`groth16`] - implementation of the Groth16 zkSNARK
- [`marlin`] - preprocessing zkSNARK for R1CS with universal and updatable SRS
- [`ripp`] - proofs about inner pairing products and applications built atop these

The team recently gave a talk on zkSummit6:
[zkSummit6: arkworks: A Rust Ecosystem for zkSNARKs – Pratyush Mishra](https://www.youtube.com/watch?v=zgSF_dRe4UY).


[arkworks]: https://github.com/arkworks-rs
[`snark`]: https://github.com/arkworks-rs/snark
[`curves`]: https://github.com/arkworks-rs/curves
[`algebra`]: https://github.com/arkworks-rs/algebra
[`groth16`]: https://github.com/arkworks-rs/groth16
[`marlin`]: https://github.com/arkworks-rs/marlin
[`ripp`]: https://github.com/arkworks-rs/ripp


&nbsp;


## Interesting Things

#### News

- Oasis launched its mainnet on Nov 18th.
  [Oasis Mainnet: Ushering in a New Era of Privacy and Scalability][oasismainnet]
  and its documentation: [Mainnet Overview](https://docs.oasis.dev/general/mainnet/mainnet).

[oasismainnet]: https://medium.com/oasis-protocol-project/oasis-mainnet-ushering-in-a-new-era-of-privacy-and-scalability-25379d152122

#### Blog Posts

- [Introducing the `k256` crate: a pure Rust secp256k1 library based on projective formulas](https://iqlusion.blog/k256-crate-pure-rust-projective-secp256k1-library)
- [Build your own: GPG](https://andrewhalle.github.io/build-your-own/gpg).
  Implementing one part of the PGP standard in Rust.
- [Using Bloom filters to efficiently synchronise hash graphs](https://martin.kleppmann.com/2020/12/02/bloom-filter-hash-graph-sync.html)  
- [Your Computer Isn't Yours](https://sneak.berlin/20201112/your-computer-isnt-yours/).
  An interest read about personal security. Not Rust or blockchain.


#### Papers 

- [Secure Regenerating Codes for Reducing Storage and Bootstrap Costs in Sharded Blockchains](https://arxiv.org/pdf/2011.06201.pdf)
- [Modelling Attacks in Blockchain Systems using Petri Nets](https://www.researchgate.net/publication/345864834_Modelling_Attacks_in_Blockchain_Systems_using_Petri_Nets)
- [Publicly Verifiable Zero Knowledge from (Collapsing) Blockchains](https://eprint.iacr.org/2020/1435)
- [Efficient Fully Secure Computation via Distributed Zero-Knowledge Proofs](https://eprint.iacr.org/2020/1451.pdf)
- [CommiTEE: An Efficient and Secure Commit-Chain Protocol using TEEs](https://eprint.iacr.org/2020/1486)
- [On Broadcast in Generalized Network and Adversarial Models](https://eprint.iacr.org/2020/1408)
- [Byzantine Eventual Consistency and the Fundamental Limits of Peer-to-Peer Databases](https://arxiv.org/abs/2012.00472)
- [TaiJi: Longest Chain Availability with BFT Fast Confirmation](https://arxiv.org/abs/2011.11097)

#### Projects

- [fe](https://github.com/ethereum/fe).
  Emerging smart contract language for the Ethereum blockchain.
  The language was initially created as the Rust implementation of the Vyper compiler.
- [t3rn](https://github.com/t3rn/t3rn).
  A protocol for interoperable code execution between
  multiple blockchains, which makes it safe and simple.
- [Kulupu](https://github.com/kulupu/kulupu).
  Kulupu is a pure (no pre-mine, no gadget) proof-of-work blockchain
  built on the Substrate framework, supporting on-chain
  governance and online upgrades.
  It uses ASIC-resistant mining algorithm of RandomX.

&nbsp;

## Most Active in November

[Solana](https://github.com/solana-labs/solana):
350 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
28 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
26 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Parity](https://github.com/paritytech):
219 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
103 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6]), 
69 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[Zcash](https://z.cash/):
110 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
41 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2]), 
58 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

&nbsp;

## Project Updates

#### [Aleo](https://github.com/AleoHQ)

38 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 21 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]), 
32 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[aleo-open_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News: Howard Wu [presents](https://www.youtube.com/channel/UCYWsYz5cKw4wZ9Mpe4kuM_g) Aleo at ZK Summit 6
- PR: [Implements Phase I coodinator w/ optimistic pipelining](https://github.com/AleoHQ/aleo-setup/pull/88)
- PR: [Feature/dynamic check](https://github.com/AleoHQ/leo/pull/411) by [@collinc97](https://github.com/collinc97)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)
49 merged PRs ([1][rust-bitcoin-merged-prs-1], [2][rust-bitcoin-merged-prs-2], [3][rust-bitcoin-merged-prs-3]), 13 closed issues ([1][rust-bitcoin-closed_issues-1], [2][rust-bitcoin-closed_issues-2]), 
14 open issues ([1][rust-bitcoin-open_issues-1], [2][rust-bitcoin-open_issues-2], [3][rust-bitcoin-open_issues-3], [4][rust-bitcoin-open_issues-4])

[rust-bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[rust-bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[rust-bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[rust-bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[rust-bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[rust-bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[rust-bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[rust-bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[rust-bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- PR: [Non-recursive bound checks for Miniscript fragments](https://github.com/rust-bitcoin/rust-miniscript/pull/150) by [@darosior](https://github.com/darosior)
- PR: [Tell ChannelMonitors about HTLCs fulfilled after channel close](https://github.com/rust-bitcoin/rust-lightning/pull/611) by [@valentinewallace](https://github.com/valentinewallace)
- PR: [Add "sortedmulti" descriptor support](https://github.com/rust-bitcoin/rust-miniscript/pull/171) by [@justinmoon](https://github.com/justinmoon)

#### [COMIT](https://github.com/comit-network)
84 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 1 closed issues ([1][comit-closed_issues-1]), 
1 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[comit-merged-prs-3]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[comit-open_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- PR: [Monerod](https://github.com/comit-network/xmr-btc-swap/pull/33) by [@bonomat](https://github.com/bonomat)
- PR: [No need to send Monero transfer proof from Alice to Bob](https://github.com/comit-network/xmr-btc-swap/pull/35) by [@luckysori](https://github.com/luckysori)
- PR: [XMR<>BTC user interface prototype details](https://github.com/comit-network/xmr-btc-swap/pull/42) by [@da-kami](https://github.com/da-kami)

#### [Holochain](https://github.com/holochain/)

58 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3], [4][holochain-merged-prs-4]), 4 closed issues ([1][holochain-closed_issues-1]), 
8 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[holochain-merged-prs-4]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[holochain-open_issues-2]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News: Holochain Dev Pulse:
  - [85: Networking Has Landed!](https://blog.holochain.org/networking-has-landed/)
  - [84: Real P2P Networking Coming To Holochain RSM](https://blog.holochain.org/real-p2p-networking-coming-to-holochain-rsm/)
- PR: [Use a Vec of 39 bytes for HoloHash serialization](https://github.com/holochain/holochain/pull/459) by [@maackle](https://github.com/maackle)
- PR: [[TK-05788 TK-05804 TK-05806 TK-05807] Kitsune Peer Discover Multi](https://github.com/holochain/holochain/pull/482) by [@neonphog](https://github.com/neonphog)

#### [Libra](https://libra.org)

79 merged PRs ([1][libra-merged-prs-1]), 5 closed issues ([1][libra-closed_issues-1]), 
5 open issues ([1][libra-open_issues-1])

[libra-merged-prs-1]: https://github.com/libra/libra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News: [Announcement: Libra is now Diem](https://community.diem.com/t/announcement-libra-is-now-diem/3282).
  [New Diem documentation for developers](https://developers.diem.com/docs/welcome-to-diem),
  and [Move](https://developers.diem.com/docs/move/overview/), a Rust-based language.
- PR: [[move-cli] include stdlib sources and binaries in the CLI rust binary to avoid publishing stdlib all the time](https://github.com/libra/libra/pull/6723) by [@mengxu-fb](https://github.com/mengxu-fb)
- PR: [[Consensus] Don't panic on failure to initialize LSR](https://github.com/libra/libra/pull/6671) by [@JoshLind](https://github.com/JoshLind)
- PR: [[Consensus] Improve error handling for failure to initialize safety rules](https://github.com/libra/libra/pull/6694) by [@JoshLind](https://github.com/JoshLind)
  

#### [Lighthouse](https://lighthouse.sigmaprime.io/)
18 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2], [3][lighthouse-merged-prs-3]), 82 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2], [3][lighthouse-closed_issues-3]), 
46 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[lighthouse-merged-prs-2]: https://github.com/sigp/beacon-fuzz/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[lighthouse-merged-prs-3]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[lighthouse-closed_issues-2]: https://github.com/sigp/beacon-fuzz/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[lighthouse-closed_issues-3]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[lighthouse-open_issues-2]: https://github.com/sigp/beacon-fuzz/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News: Lighthouse Update [#32](https://lighthouse.sigmaprime.io/update-32.html),
  [#31 (Deposit Contract Launch)](https://lighthouse.sigmaprime.io/update-31.html)
- PR: [Cut v1.0.1](https://github.com/sigp/lighthouse/pull/1985) by [@paulhauner](https://github.com/paulhauner)
- PR: [v1.0.0](https://github.com/sigp/lighthouse/pull/1952) by [@paulhauner](https://github.com/paulhauner)
- PR: [Add mainnet genesis state](https://github.com/sigp/lighthouse/pull/1959) by [@paulhauner](https://github.com/paulhauner)

#### [MobileCoin](https://www.mobilecoin.com/)

17 merged PRs ([1][mobilecoin-merged-prs-1]), 2 closed issues ([1][mobilecoin-closed_issues-1]), 
1 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- PR: [Set hint in bootstrap](https://github.com/mobilecoinfoundation/mobilecoin/pull/564) by [@sugargoat](https://github.com/sugargoat)
- PR: [Optionally allow change to be sent to a different subaddress](https://github.com/mobilecoinfoundation/mobilecoin/pull/551) by [@tsegaran](https://github.com/tsegaran)

#### [NEAR](https://github.com/nearprotocol/nearcore)

50 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 43 closed issues ([1][near-closed_issues-1]), 
20 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[near-merged-prs-2]: https://github.com/near/borsh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[near-merged-prs-3]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[near-open_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[near-open_issues-3]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News: [Mooniswap brings its next-generation AMM protocol by 1inch to NEAR](https://near.org/blog/mooniswap-brings-its-next-generation-amm-protocol-by-1inch-to-near/)
- Videos:
  - Whiteboard Series with NEAR
    - [Ep: 44 Adrian Manning from Sigma Prime][neareth2].
  About the network layer in Eth2, how the nodes communicate and for what reason.
    - [Ep: 42 Adin Schmahmann from Protocol Labs' IPFS](https://www.youtube.com/watch?v=J-drqD2UebM)
  - [Rust: NEAR collections, U128, build, deploy, call/view with NEAR CLI](https://www.youtube.com/watch?v=wC6CS7js-tc)
  - NEAR Live Contract Review
    - [Episode 3: Whitelist and Staking Pool Factory](https://www.youtube.com/watch?v=S6-1GokbGy0)
    - [Episode 4: Fungible Tokens](https://www.youtube.com/watch?v=GsDB_YN51SQ)
    - [Episode 5: Berry Club](https://www.youtube.com/watch?v=W_nI1C3_sQs)
- PR: [Cache compiled contracts.](https://github.com/near/nearcore/pull/3310) by [@olonho](https://github.com/olonho)
- PR: [Evm gas estimation](https://github.com/near/nearcore/pull/3299) by [@ailisp](https://github.com/ailisp)
- PR: [Pass cache to viewing contracts as well.](https://github.com/near/nearcore/pull/3607) by [@olonho](https://github.com/olonho)

[neareth2]: https://www.youtube.com/watch?v=XvWf6QMBO6k

#### [Nervos](https://github.com/nervosnetwork)

40 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2]), 8 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[nervos-open_issues-2]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News:
  - [COFFEE launches on Nervos to tokenize Starbucks coffee in China](https://medium.com/nervosnetwork/coffee-launches-on-nervos-to-tokenize-starbucks-coffee-in-china-5550485650ff)
  - [Nervos CKB Development Update #41](https://medium.com/nervosnetwork/nervos-ckb-development-update-41-2b2e88ded06)
  - [Nervos Community Update: October](https://medium.com/nervosnetwork/nervos-community-update-october-2020-2f4925d96217)
- PR: [feat: add assume valid target config](https://github.com/nervosnetwork/ckb/pull/2280) by [@driftluo](https://github.com/driftluo)
- PR: [refactor: add some utils to generate spendable cells](https://github.com/nervosnetwork/ckb/pull/2277) by [@keroro520](https://github.com/keroro520)
- PR: [refactor: single instance async runtime](https://github.com/nervosnetwork/ckb/pull/2373) by [@zhangsoledad](https://github.com/zhangsoledad)


#### [Parity](https://github.com/paritytech)

219 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 103 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6]), 
69 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[parity-closed_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[parity-closed_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- Blog:
  - [Introducing the Open Oracle Gateway for Polkadot](https://medium.com/polkadot-network/introducing-the-open-oracle-gateway-for-polkadot-1cf2e1b71c92)
  - [Building a Hot Wallet With Substrate Primitives](https://www.parity.io/building-a-hot-wallet-with-substrate-primitives/)
  - [Moonbeam: Ethereum Smart Contracts on Substrate](https://www.parity.io/ethereum-smart-contracts-on-substrate-moonbeam/)
- Videos:
  - Newly released videos in [Substrate Seminar](https://www.youtube.com/watch?v=bg9l72vvu2s&list=PLp0_ueXY_enXRfoaW7sTudeQH10yDvFOS)
  - [Sub0 Online](https://www.youtube.com/watch?v=HKNuGYk1EkE&list=PLp0_ueXY_enUZk1RuEAU9ly5h0wy5FuLs) videos.
  If you are interested in ink: [Sub0 Online: ink! 3.0: A Rust & Smart Contracts Love Story](https://www.youtube.com/watch?v=WNNJzK3dGGQ)
- PR: [Use inbound peerslot slots when a substream is received, rather than a connection](https://github.com/paritytech/substrate/pull/7464) by [@tomaka](https://github.com/tomaka)
- PR: [Approval Distribution Subsystem](https://github.com/paritytech/polkadot/pull/1951) by [@rphmeier](https://github.com/rphmeier)
- PR: [contracts: Add automated weights for wasm instructions](https://github.com/paritytech/substrate/pull/7361) by [@athei](https://github.com/athei)
- PR: [PoV Distribution optimization](https://github.com/paritytech/polkadot/pull/1990) by [@montekki](https://github.com/montekki)


#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

28 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 14 closed issues ([1][secret_network-closed_issues-1]), 
28 open issues ([1][secret_network-open_issues-1], [2][secret_network-open_issues-2])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[secret_network-merged-prs-2]: https://github.com/enigmampc/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[secret_network-open_issues-2]: https://github.com/enigmampc/secret-toolkit/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News:
  - [Announcing 'Holodeck' the Official Secret Network Testnet](https://blog.scrt.network/holodeck-secret-testnet/)
  - [Ocean and Secret: Collaborating on Access Control and Private Compute for datatokens](https://blog.scrt.network/ocean-and-secret-collaborating-on-access-control-and-private-compute-for-datatokens/)
  - [Secret Network Ecosystem Update: October 2020](https://blog.scrt.network/secret-network-ecosystem-update-october-2020/)
- Blog: [Secret Bids: Trust-Minimized Auction Contracts](https://blog.scrt.network/secret-auctions/)
- PR: [Adding SNIP20 interface](https://github.com/enigmampc/secret-toolkit/pull/6) by [@baedrik](https://github.com/baedrik)
- PR: [Add crypto crate to the toolkit](https://github.com/enigmampc/secret-toolkit/pull/4) by [@PumpkinSeed](https://github.com/PumpkinSeed)
- PR: [Added optional signer interface](https://github.com/enigmampc/SecretNetwork/pull/630) by [@Cashmaney](https://github.com/Cashmaney)

#### [Solana](https://github.com/solana-labs/solana)

350 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 28 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
26 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News:
  - [Announcing the Winners of Solana’s Inaugural Hackathon](https://medium.com/solana-labs/announcing-the-winners-of-solanas-inaugural-hackathon-66a280b33e6)
  - [Solana Foundation Grants — Wave One](https://medium.com/solana-labs/solana-foundation-grants-wave-one-14ae40338b59)
  - [Announcing the Solana Foundation Delegation Strategy](https://medium.com/solana-labs/announcing-the-solana-foundation-delegation-strategy-5bcccf9104ab)
- PR: [Stake: Support merging fully-activated stake accounts](https://github.com/solana-labs/solana/pull/13712) by [@t-nelson](https://github.com/t-nelson)
- PR: [Fix stake split rent-exempt adjustment](https://github.com/solana-labs/solana/pull/13357) by [@CriesofCarrots](https://github.com/CriesofCarrots)
- PR: [Added stable curve invariant to the token swap smart contract](https://github.com/solana-labs/solana-program-library/pull/838) by [@ysavchenko](https://github.com/ysavchenko)


#### [Zcash](https://z.cash/)

110 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 41 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2]), 
58 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-11-01..2020-11-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-11-01..2020-11-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-11-01..2020-11-30

- News:
  - Zcash developers update [11-13](https://www.zcashcommunity.com/2020/11/13/zcash-developers-update-11-13-2020/), [11-6](https://www.zcashcommunity.com/2020/11/06/zcash-developers-update-11-6-2020/)
  - Release [4.1.1](https://electriccoin.co/blog/new-release-4-1-1/).
  A hotfix release that addresses a performance regression in v4.1.0.
  - Release [4.1.0](https://electriccoin.co/blog/new-release-4-1-0/).
    Migration to Clang and static libc++; replaces libsodium BLAKE2b usage with the blake2b_simd Rust crate; and more.
  - [The Zcash ecosystem: A 2020 recap](https://electriccoin.co/blog/the-zcash-ecosystem-a-2020-recap/)
  - [Zcash is Unstoppable: Privacy-focused wallet first to integrate ECC wallet SDKs](https://electriccoin.co/blog/zcash-is-unstoppable-privacy-focused-wallet-first-to-integrate-ecc-wallet-sdks/)
- Blog:
  - [The Pasta Curves for Halo 2 and Beyond](https://electriccoin.co/blog/the-pasta-curves-for-halo-2-and-beyond/)
- PR: [Inbound `FindBlocks` and `FindHeaders`](https://github.com/ZcashFoundation/zebra/pull/1347) by [@oxarbitrage](https://github.com/oxarbitrage)
- PR: [RFC: Contextual Difficulty](https://github.com/ZcashFoundation/zebra/pull/1246) by [@teor2345](https://github.com/teor2345)
- PR: [Make transcript generic over curve point](https://github.com/zcash/halo2/pull/43) by [@therealyingtong](https://github.com/therealyingtong)
  

&nbsp;

## Events

Dec 7-11 | Online

[Asiacrypt 2020](https://asiacrypt.iacr.org/2020/)

Dec 26-27 | Shenzhen, China

[Rust China Conf 2020](https://2020conf.rustcc.cn/)

&nbsp;

## Careers

Aleo | San Francisco, CA; Remote
- [Rust Developer - Programming Languages](https://docs.google.com/document/d/1Q-5y9V6QmBBLSNiHRrYRCvNKuxFLy6EnHe4DKPESMX4/edit?usp=sharing)

DFINITY | San Francisco, CA; Palo Alto, CA; Zurich, Switzerland; Remote
- [Software Engineer, Distributed Systems](https://grnh.se/1f702d2e2us)
- [Software Engineer, Front-End](https://grnh.se/b8daa0ed2us)
- [Software Engineer, SDK](https://grnh.se/92e1344b2us)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#19 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

Join the discussion on [RiB telegram group][ribtg] **❤️**

[ribtg]: https://t.me/rustinblockchain


