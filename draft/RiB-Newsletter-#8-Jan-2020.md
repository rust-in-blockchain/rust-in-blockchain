# RiB Newsletter #8 - Jan 2020

**#8 - Jan 2020**

Welcome to the #8 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #7](https://rustinblockchain.org/2020/01/02/rust-in-blockchain-7-december-2019/).

There have been some updates recently to the [awesome-blockchain-rust] project that collects notable Rust blockchain links. Contributions welcome.

[awesome-blockchain-rust]: https://github.com/rust-in-blockchain/awesome-blockchain-rust

&nbsp;


## Thanks

This edition of RiB was produced with contributions from [Park Juhyung][contributorpar], [Adria Massanet][contributoradr], Paulii Good, [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

RiB needs help keeping up with Rust blockchain projects. To contribute to the next issue, submit a PR to the [#9 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/blob/master/draft/RiB-Newsletter-%239-Feb-2020.md), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorpar]: https://github.com/majecty
[contributoradr]: https://github.com/adria0
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer


&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[Za!](https://github.com/adria0/za)

_Za!_ is a simple zk-SNARK circuit compiler, a Rust port of the [circom] compiler. Circom is a high level language for writing zero knowledge proofs, making this tool a convenient way to learn about and experiment with the subject. One can get started by reading the [circom tutorial].

[circom]: https://github.com/iden3/circom
[circom tutorial]: https://github.com/iden3/circom/blob/master/TUTORIAL.md

&nbsp;


## Most Active in January

[Solana]: [364 merged PRs][solana-mergedprs], [47 closed issues][solana-closedissues].

[Parity]: 259 merged PRs ([1][parity-mergedpr1], [2][parity-mergedpr2]), 54 closed issues ([1][parity-issue1], [2][parity-issue2]).

[COMIT]: 186 merged PRs ([1][comit-mergedpr1], [2][comit-mergedpr2]), 64 closed issues ([1][comit-issue1], [2][comit-issue2]).

[Nervos]: 148 merged PRs ([1][nervos-mergedpr1], [2][nervos-mergedpr2], [3][nervos-mergedpr3], [4][nervos-mergedpr4], [5][nervos-mergedpr5]), 9 closed issues ([1][nervos-issue1], [2][nervos-issue2], [3][nervos-issue3], [4][nervos-issue4], [5][nervos-issue5]).

[Solana]: https://github.com/solana-labs/solana
[Parity]: https://github.com/paritytech
[COMIT]: https://comit.network/
[Nervos]: https://github.com/nervosnetwork

&nbsp;



## Project Updates

#### [**CodeChain**](https://codechain.io)

[17 merged PRs][codechain-mergedprs],
[6 closed issues][codechain-closedissues].

[codechain-mergedprs]: https://github.com/CodeChain-io/codechain/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[codechain-closedissues]: https://github.com/CodeChain-io/codechain/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04

- Blog: [Tenderand: Randomized leader election in Tendermint](https://medium.com/codechain/tenderand-randomized-leader-election-in-tendermint-a3663d863479)
- Blog: [IBC and ICS](https://medium.com/codechain/ibc-and-ics-116e636e57aa)
  On interop between blockchains. IBC = "Interblockchain communication" protocol. ICS = "Interchain standard".
- Blog: [VeriSync - A Fast and VERIfiable SYNC Method for Blockchains](https://medium.com/codechain/verisync-baf0583ade47)
- Video: [Monthly CodeChain TechTalk - November 2019](https://medium.com/codechain/monthly-codechain-tecktalk-november-2019-73ad0fa2e7f5)
- Video: [Monthly CodeChain TechTalk - January 2020](https://medium.com/codechain/monthly-codechain-techtalk-january-2020-b00a0a020200)


#### [**COMIT**](https://comit.network/)

186 merged PRs ([1][comit-mergedpr1], [2][comit-mergedpr2]), 64 closed issues ([1][comit-issue1], [2][comit-issue2]).

[comit-mergedpr1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[comit-mergedpr2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[comit-issue1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31
[comit-issue2]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- Blog: [January, 2020 - Dev Update](https://blog.coblox.tech/2020/01/31/january-dev-update.html)
- PR: [Add cache for Bitcoin and Ethereum connectors](https://github.com/comit-network/comit-rs/pull/1912)
- PR: [Encode the capability of deriving a Secret into the type system so that only Alice can do that](https://github.com/comit-network/comit-rs/pull/1795)
- PR: [Improve current logging](https://github.com/comit-network/comit-rs/pull/1786)
- PR: [Resume in progress swaps](https://github.com/comit-network/comit-rs/pull/1735)


#### [**Grin**](https://github.com/mimblewimble/grin)

[25 merged PRs][grin-mergedpr], [29 closed issues][grin-issue].

[grin-mergedpr]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[grin-issue]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- News: [Grin 2020 roadmap](https://github.com/mimblewimble/grin-rfcs/pull/38)
- News: [#83: Non-interactive transactions](https://grinnews.substack.com/p/83-non-interactive-transactions-)
- News: [#82: Security team proposed](https://grinnews.substack.com/p/82-security-team-proposed-)
- News: [#81: Grin 3.0.0](https://grinnews.substack.com/p/81-grin-300-)
- News: [#80: Hard fork imminent](https://grinnews.substack.com/p/80-hard-fork-imminent-)
- News: [#79: $77m worth of Grin mined in 2019](https://grinnews.substack.com/p/79-77m-worth-of-grin-mined-in-2019)
- PR: [Cleanup redundant AsFixedBytes and FixedLength traits](https://github.com/mimblewimble/grin/pull/3131)
- Issue: [Replace input commitment by 8 bytes MMR position](https://github.com/mimblewimble/grin/issues/2864)
- Issue: [P2P transaction building](https://github.com/mimblewimble/grin/issues/1798)
- Issue: [Consider relaxing timestamp monotonicity](https://github.com/mimblewimble/grin/issues/1486)


#### [**Holochain**](github.com/holochain/)

[30 merged PRs][holochain-mergedpr],
[0 closed issues][holochain-closedissues].

[holochain-mergedpr]: https://github.com/holochain/holochain-rust/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[holochain-closedissues]: https://github.com/holochain/holochain-rust/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04

- Blog: [Privacy and Security on the Holo Network](https://blog.holochain.org/privacy-and-security-on-the-holo-network/)
- Blog: [Holo and Holochain Weekly Roundup - January 10](https://medium.com/h-o-l-o/holo-holochain-weekly-roundup-january-10-11f699dbfb99)
- Blog: [Holo and Holochain Weekly Roundup - January 17](https://medium.com/h-o-l-o/holo-holochain-weekly-roundup-january-17-6b469276ccbf)
- Docs: [What is Holochain?](https://developer.holochain.org/docs/what-is-holochain/)

#### [**Interledger**](https://interledger.org/)

[18 merged PRs][interledger-mergedpr], [7 closed issues][interledger-issue].

[interledger-mergedpr]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[interledger-issue]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- PR: [Interledger Stream: Futures 0.3 Transition](https://github.com/interledger-rs/interledger-rs/pull/601)
- PR: [Interledger API: Futures 0.3 Transition](https://github.com/interledger-rs/interledger-rs/pull/605)
- Issue: [Unable to settle a payment between connectors](https://github.com/interledger-rs/interledger-rs/issues/581)


#### [**NEAR**](https://github.com/nearprotocol/nearcore)

[61 merged PRs][near-mergedpr], [64 closed issues][near-issue].

[near-mergedpr]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Amerged+merged%3A2020-01-01..2020-01-31
[near-issue]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- News: [NEAR Community Update: January 17th, 2020](https://nearprotocol.com/blog/near-community-update-january-17th-2020/)
- Blog: [Welcome to the NEAR Community!](https://nearprotocol.com/blog/nearcon-zero/)
- Blog: [We’re pausing Stake Wars](https://nearprotocol.com/blog/were-pausing-stake-wars/)
- Blog: [NEAR 2019 Year in Review](https://nearprotocol.com/blog/near2019/)
- Blog: [Introducing the ARterra Platform](https://medium.com/arterra-engagement/introducing-the-arterra-platform-fe551a99037b)
- Video: [Whiteboard Series with NEAR | Ep: 32 Tim Moreton from Celo](https://www.youtube.com/watch?v=jbSvdNj5zNc)
- Video: [Sharding Jam with Alex Skidanov](https://www.youtube.com/watch?v=tDeb0LACCag)
- Video: [Wasm Chains: Featuring NEAR Protocol](https://www.youtube.com/watch?v=75hO1j-T1LY)
- Video: [Cross-app communication (Ethereum Serenity, NEAR, Polkadot, Cosmos)](https://www.youtube.com/watch?v=EYzYAokCVgMs)
- PR: [Doomslug](https://github.com/nearprotocol/nearcore/pull/1991)
- PR: [Answer to StateRequest in parallel](https://github.com/nearprotocol/nearcore/pull/1916)
- PR: [NumBlocks, NumShards, NumSeats, HeightDelta and _seats](https://github.com/nearprotocol/nearcore/pull/1882)
- Issue: [Block fork question](https://github.com/nearprotocol/nearcore/issues/1924)
- Issue: [Unexpected error msgs in state_sync](https://github.com/nearprotocol/nearcore/issues/1824)
- Issue: [Investigate too many open files error](https://github.com/nearprotocol/nearcore/issues/1316)


#### [**Nervos**](https://github.com/nervosnetwork)

148 merged PRs ([1][nervos-mergedpr1], [2][nervos-mergedpr2], [3][nervos-mergedpr3], [4][nervos-mergedpr4], [5][nervos-mergedpr5]), 9 closed issues ([1][nervos-issue1], [2][nervos-issue2], [3][nervos-issue3], [4][nervos-issue4], [5][nervos-issue5]).

[nervos-mergedpr1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[nervos-mergedpr2]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[nervos-mergedpr3]: https://github.com/nervosnetwork/overlord/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[nervos-mergedpr4]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[nervos-mergedpr5]: https://github.com/nervosnetwork/neuron/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[nervos-issue1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31
[nervos-issue2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31
[nervos-issue3]: https://github.com/nervosnetwork/overlord/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31
[nervos-issue4]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31
[nervos-issue5]: https://github.com/nervosnetwork/neuron/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- News: [Nervos Network Will Hand Out $30M to Encourage Third-Party Development](https://www.coindesk.com/nervos-network-dedicates-30m-for-grants-to-encourage-third-party-development)
- News: [Nervos CKB Development Update #28](https://medium.com/nervosnetwork/nervos-ckb-development-update-28-5c85be7a599e) The team has deployed Duktape (a Javascript VM) and mruby to testnet.
- News: [Nervos CKB Development Update #27](https://medium.com/nervosnetwork/nervos-ckb-development-update-27-d48918df00c5) The team is currently working on: Animagus — an AST contract framework, Randao — a random number generator and Godwoken — a layer 1.5 framework for Optimistic Rollup or Zk Rollup.
- News: [Announcing the Nervos Ecosystem Grants Program](https://medium.com/nervosnetwork/announcing-the-nervos-ecosystem-grants-program-ffba2806fa68)
- News: [The Grants Program is Now Open—–Nervos Bi-weekly Report #27](https://talk.nervos.org/t/the-grants-program-is-now-open-nervos-bi-weekly-report-27/4147)
- News: [Happy New Year!—–Nervos Bi-weekly Report #26](https://talk.nervos.org/t/happy-new-year-nervos-bi-weekly-report-26/4082)
- News: [Nervos Community Update: December, 2019](https://medium.com/nervosnetwork/nervos-community-update-c19a2a228fcb)
- Blog: [Crypto-Economic Design for Scalability and Sustainability](https://medium.com/nervosnetwork/crypto-economic-design-for-scalability-and-sustainability-e83481951c5a)
- Blog: [How the Nervos CKByte Gets its Value](https://medium.com/nervosnetwork/how-the-nervos-ckbyte-gets-its-value-f0bd43333035)  
- Blog: [ Introduction to CKB Script Programming 6: Type ID ](https://xuejie.space/2020_02_03_introduction_to_ckb_script_programming_type_id/)
- Blog: [CKBytes in UDT transfer](https://talk.nervos.org/t/ckbytes-in-udt-transfer/4140)
- Blog: [Rust contract, part 2 - Write contract with ckb-contract-std](https://talk.nervos.org/t/rust-contract-part-2-write-contract-with-ckb-contract-std/4089)
- Blog: [A Programming Idea on CKB – Energize Data [2]](https://talk.nervos.org/t/a-programming-idea-on-ckb-energize-data-2/4090)
- Blog: [Open Tx Protocol Brainstorm: (2) Design a Practical Protocol on CKB](https://talk.nervos.org/t/open-tx-protocol-brainstorm-2-design-a-practical-protocol-on-ckb/4091)
- Blog: [Open Tx Protocol Brainstorm: (3) Scenarios Analyzing on CKB](https://talk.nervos.org/t/open-tx-protocol-brainstorm-3-scenarios-analyzing-on-ckb/4144)
- Discussion: [Nervos Grants RFCs](https://talk.nervos.org/tags/grant-rfc)
- PR: [Add a new json rpc method `get_block_economic_state`](https://github.com/nervosnetwork/ckb/pull/1848)
- PR: [2 phase dao](https://github.com/nervosnetwork/ckb-cli/pull/159)
- PR: [Add step mode for AsmMachine](https://github.com/nervosnetwork/ckb-vm/pull/93)

#### [**Parity** ](https://github.com/paritytech)

259 merged PRs ([1][parity-mergedpr1], [2][parity-mergedpr2]), 54 closed issues ([1][parity-issue1], [2][parity-issue2]).

[parity-mergedpr1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Amerged+merged%3A2020-01-01..2020-01-31
[parity-mergedpr2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Amerged+merged%3A2020-01-01..2020-01-31
[parity-issue1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31
[parity-issue2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- News: [A few questions for Gavin Wood](https://medium.com/block-street-journal/a-few-questions-for-gavin-wood-6699f991d34c)
- News: [Polkascan Development Update #5](https://polkadot.network/polkascan-development-update-5)
- News: [Kusama Upgrade Bulletin (1032-1037)](https://polkadot.network/kusama-upgrade-bulletin-1032-1037/)
- Blog: [Kusama’s First Adventure](https://polkadot.network/kusamas-first-adventure/)
- Blog: [Polkadot’s Messaging Scheme](https://medium.com/web3foundation/polkadots-messaging-scheme-b1ec560908b7)
- Podcast: [Designing Universal Basic Income and Trusted Execution Environments](https://relaychain.fm/13-designing-universal-basic-income)
- Video: [Sub0.1: Storage on Substrate - Shawn Tabrizi](https://www.youtube.com/watch?v=kKKOL20FdII)
- Video: [Sub0.1: Wasm and Substrate - Sergei Shulepov](https://www.youtube.com/watch?v=lCjbpryZ7LA)
- Video: [Sub0.1: Behold, the Future Is Upon Us - Benjamin Kampmann](https://www.youtube.com/watch?v=H1bfZcq7OVg)
- Video: [Sub0.1: KILT. Why the heck did we choose Substrate? - Maud Nalpas](https://www.youtube.com/watch?v=d0zF3ghAdVI)
- Video: [Sub0.1: ink! Smart Contracts on Substrate - Robin Freyler](https://www.youtube.com/watch?v=d0zF3ghAdVI)
- Video: [Sub0.1: Cumulus - Robert Habermeier, co-founder of Polkadot](https://www.youtube.com/watch?v=qZacXdTFIh0)
- Video: [Sub0.1: AMA with Gavin Wood, founder of Polkadot](https://www.youtube.com/watch?v=k_sZQPknRy0)
- Video: [The Internet Rebooted (Wood, Isaac) | DLD Munich 20](https://www.youtube.com/watch?v=kKKOL20FdII)
- Video: [Intro to Substrate codebase and FRAME pallet deep-dive with Joe Petrowski and Shawn Tabrizi](https://www.youtube.com/watch?v=5PSllaWbYag)
- Repo: [Substrate-developer-hub/utxo-workshop](https://github.com/substrate-developer-hub/utxo-workshop)
- PR: [Pallet-contracts: Refactor and comment `rent` module](https://github.com/paritytech/substrate/pull/4733)
- PR: [RPC api for offchain storage](https://github.com/paritytech/substrate/pull/4694)
- PR: [CLI API refactoring and improvement](https://github.com/paritytech/substrate/pull/4692)
- PR: [Switch GrandPa to std futures (replaces #3909)](https://github.com/paritytech/substrate/pull/4612)
- PR: [A Social Account Recovery Pallet](https://github.com/paritytech/substrate/pull/4531)
- PR: [Allow updating configuration of changes tries](https://github.com/paritytech/substrate/pull/3201)
- PR: [Update tokio to 0.2 again and remove `TaskExecutor`s](https://github.com/paritytech/polkadot/pull/786)
- PR: [Support both polkadot and kusama runtimes](https://github.com/paritytech/polkadot/pull/704)
- PR: [Switch parachain interface to new `runtime_interface` macro](https://github.com/paritytech/polkadot/pull/665)


#### [**Solana**](https://github.com/solana-labs/solana)

[364 merged PRs][solana-mergedprs],
[47 closed issues][solana-closedissues].

[solana-mergedprs]: https://github.com/solana-labs/solana/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[solana-closedissues]: https://github.com/solana-labs/solana/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04

- Blog: [SLP1 Cluster Launch](https://medium.com/solana-labs/slp1-cluster-launch-4634848d2343).
  The "Soft Launch Phase 1" cluster is a testnet that is intended to gradually be upgraded to the Solana mainnet.
- News: [Solana launches "Tour de SOL" incentivised testnet](https://twitter.com/solana/status/1223094881540665346)
- News: [Monthly Roundup for January 20](https://chorusone.substack.com/p/monthly-roundup-jan-20)
- PR: [Propose Solana ABI management](https://github.com/solana-labs/solana/pull/7524).
  Technical solutions for catching ABI breakage in serialized structures.


#### [**Zcash**](https://z.cash/)

37 merged PRs ([1][zcash-mergedprs1], [2][zcash-mergedprs2]),
13 closed issues ([1][zcash-closedissues1], [2][zcash-closedissues2]).

[zcash-mergedprs1]: https://github.com/ZcashFoundation/zebra/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[zcash-mergedprs2]: https://github.com/zcash/librustzcash/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[zcash-closedissues1]: https://github.com/ZcashFoundation/zebra/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04
[zcash-closedissues2]: https://github.com/zcash/librustzcash/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04

- News: [Zcash Foundation Update • December 14, 2019 – January 31, 2020](https://news.zfnd.org/archive/zcash-foundation-update-december-14-2019-january/)
- News: [January 31, 2020 - Weekly Forum Update](https://forum.zcashcommunity.com/t/january-31-2020-weekly-forum-update/35905)
- Blog: [A New Network Stack for Zcash](https://www.zfnd.org/blog/a-new-network-stack-for-zcash/). About the Rust implementation of Zcash.
- Blog: [Composable Futures-based Batch Verification](https://www.zfnd.org/blog/futures-batch-verification/)
- Blog: [Building for ZCash](https://thevantageproject.github.io/buidl-labs-blog/buidling-for-zcash)
- Blog: [Introducing monthly Zcash community calls](https://electriccoin.co/blog/introducing-monthly-zcash-community-calls/)
- Blog: [ZIP 1014 results](https://www.zfnd.org/blog/zip-1014-poll-results/)
  About funding Zcash.
- Blog: [Dev fund poll shows consensus](https://electriccoin.co/blog/dev-fund-poll-shows-consensus/)
- Blog: [ECC releases resources for building mobile, shielded-Zcash wallets](https://electriccoin.co/blog/ecc-releases-resources-for-building-mobile-shielded-zcash-wallets/).
  The Android SDK includes Rust code.
- Paper: [Security assessments: NU3 specifications, Blossom implementation and Sapling documentation](https://electriccoin.co/blog/security-assessments-nu3-specifications-blossom-implementation-and-sapling-documentation/).
  "NU3" = "network upgrade 3", and "Blossom" is its codename. Sapling is Zcash's current zero-knowledge proof scheme that was introduced in 2018.
- Paper: [Trail of Bits Zcash whitepaper](https://github.com/trailofbits/publications/blob/master/reviews/ZcashWP.pdf).
  A new, clear, description of the Zcash protocol, including Sapling proofs. Produced for the security assessment.
- PR: [Refine Ed25519 byte arrays to ed25519-zebra types](https://github.com/ZcashFoundation/zebra/pull/199)
  Introduces a [zebra-customized ed25519 crate][zced]
- PR: [ZIP 213 - Shielded coinbase transactions](https://github.com/zcash/zips/pull/217).
  This will make it possible to mine coins that are immediately private, whereas today all mined coins are public.

[zced]: https://github.com/ZcashFoundation/ed25519-zebra


&nbsp;

## Learning

[What Is Web 3.0 & Why It Matters](https://medium.com/fabric-ventures/what-is-web-3-0-why-it-matters-934eb07f3d2b)

[‘One Network, Many Chains’ – The Case for Blockchain Interoperability](https://www.coindesk.com/one-network-many-chains-the-case-for-blockchain-interoperability)

Video: [Data Security and the Rise of Crypto](https://www.youtube.com/watch?v=flV82tFjyZY&list=PLM4u6XbiXf5qXKZixrDpN3ZSwH_8UabPq)

&nbsp;


## Interesting Things

Post: [An OS prototype where binaries are WASM, run in ring 0](https://www.reddit.com/r/rust/comments/ekingn/tomakaredshirt_an_os_prototype_where_binaries_are)

Tweet: [How far behind rust-libp2p is compared to go-libp2p and js-libp2p](https://twitter.com/tomaka17/status/1224313756458590208?s=20)

Project: [lib3h](https://github.com/holochain/lib3h). Holochain's p2p library

Project: [Za!](https://github.com/adria0/za).
  A zk-SNARK circuit compiler that supports a variant of the [circom] language.

Project: [tesseracts](https://github.com/adria0/tesseracts).
  A blockchain explorer for geth PoAs.

[circom]: https://github.com/iden3/circom

&nbsp;


## Events

Feb 12-16 | San Francisco, US

[DeveloperWeek 2020 & Hackathon](https://www.developerweek.com/)

Feb 19-21 | Stanford University, US

[The Stanford Blockchain Conference 2020](https://cbr.stanford.edu/sbc20/)

Feb 29 | San Francisco, US

[World Blockchain Hackathon](https://www.eventbrite.com/e/world-blockchain-hackathon-san-francisco-tickets-70815243299)

Mar 4-11 | London, UK

[London Blockchain Week](https://www.blockchainweek.com/)

Mar 7-8 | MIT Campus, US

[MIT Bitcoin Expo 2020](https://mitbitcoinexpo.org/)

Mar 31 - Apr 1 | Paris, France

[Paris Blockchain Week Summit](https://www.pbwsummit.com/)

Apr 13-16 | Oxford, UK

[IEEE DAPPS 2020](https://ieeedapps.net/)

&nbsp;


## Careers

ARK | Remote

[Senior Developer/Blockchain Core Developer](https://cryptocurrencyjobs.co/engineering/ark-senior-developer-blockchain-core-developer/)

Consensys | Europe; United States; Remote

[Systems Engineer (Rust)](https://consensys.net/open-roles/1792013/)

Cosmian | Paris, France; Remote

[Developer (Rust/Cryptography)](https://cosmian.com/were-hiring-developer-rust-cryptography-m-w-x/)

imToken | Singapore; Hangzhou, China

[Blockchain Development Engineer](https://token.im/careers#jobs)

Nervos | San Francisco; Hangzhou, China; Remote

[Senior Blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

Protocol Labs | Remote

[Research Scientist, Cryptography](https://jobs.lever.co/protocol/f6413901-cf6c-43be-af0e-d1a68adddada)

Sigma Prime | Sydney, Australia; Remote

[Experienced Rust Developer](https://lighthouse.sigmaprime.io/hiring-dec-2019.html)

Spacemesh | NYC, US

[Blockchain Developer](https://spacemesh.io/blockchain-dev-nyc/)


&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#9 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/blob/master/draft/RiB-Newsletter-%239-Feb-2020.md), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
