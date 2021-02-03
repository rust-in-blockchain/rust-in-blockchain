---
title: "RiB Newsletter #20"
description: "#20 - January 2021"
date: 2021-02-03
slug: "/"
categories:
  - "newsletters"
summary: ""
---

Welcome to the #20 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #19](/newsletters/rust-and-smart-contracts/).




For those wanting to stay even more in-tune with Rust blockchain developer news,
the pace of the [Telegram group][ribtg] has been picking up lately,
and the announcements and discussions there are more detailed
than the brief one-liners in the newsletter.

Representatives from Rust blockchain projects will often hop in and link to
developer tools, events, and jobs.
While we usually include these links in the newsletter,
we also generally strip out the details and nuance of the message.

This month we talked a lot about Rust smart contract platforms,
including the possibility of creating a single Rust library that abstracts
over multiple blockchain runtimes.

Still, it is a low-volume group that only permits developer-relevant content &mdash;
typical blockchain marketing spam is moderated away.


&nbsp;


## Thanks

Thanks to contributors:
[Adam Gutierrez][contributor-ag],
[Ernest Kissiedu][contributor-ek],
[Leonardo Yvens][contributor-ly],
[Paul][contributor-ps],


_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#21 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributor-ag]: https://github.com/adamisrusty
[contributor-ly]: https://github.com/leoyvens
[contributor-ps]: https://github.com/paul-schaaf
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer
[contributor-ek]: https://github.com/ernestkissiedu

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[mev-inspect](https://github.com/flashbots/mev-inspect-rs)

This is a tool for analyzing historical miner extractable value (MEV) on Ethereum.
"Miner extractable value" refers to value that can be earned by miners directly from transactions,
through e.g. mempool frontrunning,
as opposed to traditional miner rewards.
It was defined and analyzed in the [Flashboys 2.0 paper][fb2],
which claims that the phenomenon poses near-term system risk to Ethereum's
security by skewing the economic incentives of miners in unanticipated ways.
`mev-inspect` then is a tool designed to illuminate how bots
today are competing with each other to squeeze value out of Ethereum transactions.

It can introspect transactions with common DeFi applications,
including Uniswap, Aave, and Curve,
to find instances of arbitrage and other front-running activites.

It is described further in [a post on the Ethereum research forum][mevpost].

`mev-inspect` communicates with Ethereum nodes via the [ethers crate][ethers].

[fb2]: https://pdaian.com/flashboys2.pdf
[mevpost]: https://ethresear.ch/t/flashbots-frontrunning-the-mev-crisis/8251
[ethers]: https://github.com/gakonst/ethers-rs


&nbsp;


## Interesting Things

#### News

- Dfinity: [Announcing the Internet Computer “Mainnet” and a 20-Year Roadmap](https://medium.com/dfinity/announcing-internet-computer-mainnet-and-a-20-year-roadmap-790e56cbe04a)

#### Blog Posts

- [The Cost of Transparency in Public Blockchain Networks](https://aleo.org/post/what-does-transparency-cost-you)
- [Solana Development Tutorial: Things you should know before structuring your code](https://solongwallet.medium.com/solana-development-tutorial-things-you-should-know-before-structuring-your-code-807f0e2ee43)
- [Programming on Solana - An Introduction](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/)
- [Candid: A Common Language for Application Interfaces on the Internet Computer](https://medium.com/dfinity/candid-a-tool-for-interoperable-programming-languages-on-the-internet-computer-27e7085cd97f).
  Source code: [Candid](https://github.com/dfinity/candid).
- [First impressions of programming on DFINITY](https://brson.github.io/2021/01/30/dfinity-impressions)
- [An approximate introduction to how zk-SNARKs are possible](https://vitalik.ca/general/2021/01/26/snarks.html)

#### Papers

- [On Elapsed Time Consensus Protocols](https://eprint.iacr.org/2021/086)
- [SPURT: Scalable Distributed Randomness Beacon with Transparent Setup](https://eprint.iacr.org/2021/100)
- [Evolution of Bulletin Board & its application to E-Voting – A Survey](https://eprint.iacr.org/2021/047)
- [The Eye of Horus: Spotting and Analyzing Attacks on Ethereum Smart Contracts](https://deepai.org/publication/the-eye-of-horus-spotting-and-analyzing-attacks-on-ethereum-smart-contracts)
- [Horizon: A Gas-Efficient, Trustless Bridge for Cross-Chain Transactions](https://github.com/harmony-one/horizon/blob/main/horizon-whitepaper.pdf)
- [Byzantine Generals in the Permissionless Setting](https://paperswithcode.com/paper/byzantine-generals-in-the-permissionless)
- [SoK: Decentralized Finance (DeFi)](https://arxiv.org/abs/2101.08778)

#### Projects

- [Concordium](https://concordium.com)
  - This is an enterprise blockchain that [runs Rust smart contracts](https://github.com/Concordium/concordium-rust-smart-contracts) on wasm
  - [Concordium releases Testnet 4](https://medium.com/concordium/concordium-releases-testnet-4-b5c0f2895b3b)
  - They are [looking for people to test](https://medium.com/concordium/announcing-concordium-testnet-4-incentives-3b2d72fcee68) their smart contracts and network ahead of the mainnet launch in Q2.
- [DIDKit](https://github.com/spruceid/didkit) provides Verifiable Credential and Decentralized Identifier functionality across different platforms

&nbsp;

## Most Active in January

[Parity](https://github.com/paritytech):
301 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 96 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
76 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[Solana](https://github.com/solana-labs/solana):
357 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 48 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
47 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Diem](https://www.diem.com):
177 merged PRs ([1][diem-merged-prs-1]), 7 closed issues ([1][diem-closed_issues-1], [2][diem-closed_issues-2]), 
15 open issues ([1][diem-open_issues-1])

&nbsp;

## Project Updates

#### [Aleo](https://github.com/AleoHQ)
60 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 42 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]), 
22 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- PR: [cargo +nightly clippy](https://github.com/AleoHQ/leo/pull/573) by [@collinc97](https://github.com/collinc97)
- PR: [[CLI, CI] Leo add does not require login](https://github.com/AleoHQ/leo/pull/582) by [@damirka](https://github.com/damirka)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

41 merged PRs ([1][rust-bitcoin-merged-prs-1], [2][rust-bitcoin-merged-prs-2], [3][rust-bitcoin-merged-prs-3], [4][rust-bitcoin-merged-prs-4]), 15 closed issues ([1][rust-bitcoin-closed_issues-1], [2][rust-bitcoin-closed_issues-2], [3][rust-bitcoin-closed_issues-3], [4][rust-bitcoin-closed_issues-4]), 
10 open issues ([1][rust-bitcoin-open_issues-1], [2][rust-bitcoin-open_issues-2], [3][rust-bitcoin-open_issues-3])

[rust-bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[rust-bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[rust-bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[rust-bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[rust-bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[rust-bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[rust-bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[rust-bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[rust-bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[rust-bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[rust-bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- PR: [Introduce CommitmentTransactionInfo](https://github.com/rust-bitcoin/rust-lightning/pull/742) by [@devrandom](https://github.com/devrandom)
- PR: [Add GLOSSARY.md and more](https://github.com/rust-bitcoin/rust-lightning/pull/772) by [@ariard](https://github.com/ariard)

#### [COMIT](https://github.com/comit-network)

55 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 3 closed issues ([1][comit-closed_issues-1]), 
12 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[comit-merged-prs-3]: https://github.com/comit-network/blockchain-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- PR: [Refactor prod code after test refactoring](https://github.com/comit-network/xmr-btc-swap/pull/147) by [@da-kami](https://github.com/da-kami)
- PR: [Introduce "one shots"](https://github.com/comit-network/xmr-btc-swap/pull/159) by [@D4nte](https://github.com/D4nte)
- PR: [Add sequence diagram](https://github.com/comit-network/xmr-btc-swap/pull/138) by [@D4nte](https://github.com/D4nte)

#### [Fluence](https://github.com/fluencelabs)

17 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3]), 0 closed issues (), 
0 open issues ()

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/fce/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquamarine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31

- PR: [Introduce ConnectionPool & localize libp2p](https://github.com/fluencelabs/fluence/pull/1017) by [@folex](https://github.com/folex)
- PR: [Refactoring and housekeeping](https://github.com/fluencelabs/aquamarine/pull/55) by [@michaelvoronov](https://github.com/michaelvoronov)

#### [Holochain](https://github.com/holochain/)

36 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]), 3 closed issues ([1][holochain-closed_issues-1]), 
7 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- News: Holochain Dev Pulse:
  - [89: Testing, Testing, Testing (and some goodies for developers)](https://blog.holochain.org/testing-testing-testing-and-some-goodies-for-developers/)
  - [88: New Year, New Energy](https://blog.holochain.org/new-year-new-energy/)
- PR: [Add RegisterDna to conductor api and allow InstallApp to take a hash](https://github.com/holochain/holochain/pull/582) by [@zippy](https://github.com/zippy)
- PR: [Convert signal test to show  failure point while scaling](https://github.com/holochain/elemental-chat/pull/41) by [@zippy](https://github.com/zippy)

#### [Diem](https://www.diem.com)

177 merged PRs ([1][diem-merged-prs-1]), 7 closed issues ([1][diem-closed_issues-1], [2][diem-closed_issues-2]), 
15 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[diem-closed_issues-2]: https://github.com/diem/bcs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- PR: [[vm] avoid cyclic dependencies that may be introduced by module republishing](https://github.com/diem/diem/pull/7234) by [@mengxu-fb](https://github.com/mengxu-fb)
- PR: [[network] Merge PeerPubkeys and PeerAddresses](https://github.com/diem/diem/pull/7337) by [@gregnazario](https://github.com/gregnazario)
- PR: [[transaction-replay] Implement a few commands for txn-replay tool](https://github.com/diem/diem/pull/7189) by [@runtian-zhou](https://github.com/runtian-zhou)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

2 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]), 28 closed issues ([1][lighthouse-closed_issues-1]), 
4 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/beacon-fuzz/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- News: [Lighthouse Update #33](https://lighthouse.sigmaprime.io/update-33.html)
- PR: [lodestar.Dockerfile: upgrade LODESTAR_VERSION and DISCV5_VERSION to latest versions](https://github.com/sigp/beacon-fuzz/pull/96) by [@3xtr4t3rr3str14l](https://github.com/3xtr4t3rr3str14l)
- PR: [Upgrade to tokio 1.0](https://github.com/sigp/discv5/pull/57) by [@pawanjay176](https://github.com/pawanjay176)

#### [MobileCoin](https://www.mobilecoin.com/)

22 merged PRs ([1][mobilecoin-merged-prs-1]), 2 closed issues ([1][mobilecoin-closed_issues-1]), 
2 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- PR: [MCC-710 Final changes regarded FullyValidatedFogPubkey and TransactionBuilder](https://github.com/mobilecoinfoundation/mobilecoin/pull/581) by [@garbageslam](https://github.com/garbageslam)
- PR: [FOG-179 x509 Utilities](https://github.com/mobilecoinfoundation/mobilecoin/pull/684) by [@jcape](https://github.com/jcape)
- PR: [Add GetMixins to mobilecoind API](https://github.com/mobilecoinfoundation/mobilecoin/pull/680) by [@mfaulk](https://github.com/mfaulk)

#### [NEAR](https://github.com/nearprotocol/nearcore)

37 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 19 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2]), 
44 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[near-merged-prs-2]: https://github.com/near/borsh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[near-closed_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- News: [Dragonfly Capital Joins NEAR Validator Advisory Board](https://near.org/blog/dragonfly-capital/)
- Learn: [Build Apps and Earn NEAR with the NEAR Learn Pathway](https://figment.io/resources/build-apps-and-earn-near-with-the-near-learn-pathway/)
- Videos: NEAR Live Contract Review
  - [Episode 11: Low-level no_std](https://www.youtube.com/watch?v=Hy4VBSCqnsE)
  - [Episode 10: Rainbow Bridge](https://www.youtube.com/watch?v=ptmFN41igks)
  - [Episode 9: BananaSwap](https://www.youtube.com/watch?v=TkFYBEOk9pI)
- Videos: NEAR Core
  - [Episode 05: NEAR Network Routing](https://www.youtube.com/watch?v=jmdxdO0gifY)
  - [Episode 04: Network P2P Connection](https://www.youtube.com/watch?v=r6gyuUYo2tw)
  - [Episode 03: Runtime State](https://www.youtube.com/watch?v=JCkSNL4ie1U)
  - [Episode 02: Runtime Action and Data Receipts](https://www.youtube.com/watch?v=RBb3rJGtqOE)
  - [Episode 01: Runtime Overview](https://www.youtube.com/watch?v=Xi_8PapFCjo)
- PR: [[WIP] Evm phase2](https://github.com/near/nearcore/pull/3775) by [@evgenykuzyakov](https://github.com/evgenykuzyakov)
- PR: [Adding block_ordinal to BlockHeaderInnerRest](https://github.com/near/nearcore/pull/3804) by [@Kouprin](https://github.com/Kouprin)
- PR: [feat(evm): Raw Ethereum transaction relay support](https://github.com/near/nearcore/pull/3773) by [@ilblackdragon](https://github.com/ilblackdragon)

#### [Nervos](https://github.com/nervosnetwork)

46 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]), 8 closed issues ([1][nervos-closed_issues-1]), 
1 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- Blog:
  - [Nervos 2020: A Year in Review](https://medium.com/nervosnetwork/nervos-2020-a-year-in-review-3d560ed93880)
  - [Towards CKB style Lego pieces: Polyjuice on Godwoken](https://medium.com/nervosnetwork/towards-ckb-style-lego-pieces-polyjuice-on-godwoken-cbc935d77abf)
- PR: [fix: resolve rocksdb cache size issue when using `default.db-options`](https://github.com/nervosnetwork/ckb/pull/2542) by [@quake](https://github.com/quake)
- PR: [feat: add RPC get_block_median_time](https://github.com/nervosnetwork/ckb/pull/2520) by [@keroro520](https://github.com/keroro520)
- PR: [feat: provide `--overwrite-spec` to override the chain spec in storage](https://github.com/nervosnetwork/ckb/pull/2505) by [@keroro520](https://github.com/keroro520)

#### [Parity](https://github.com/paritytech)

301 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 96 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
76 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[parity-closed_issues-3]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- News: [Polkadot-js Extension Release Update](https://medium.com/polkadot-network/polkadot-js-extension-release-update-3b0d2d87edb8)
- PR: [Telemetry per node](https://github.com/paritytech/substrate/pull/7463) by [@cecton](https://github.com/cecton)
- PR: [Introduces account existence providers reference counting](https://github.com/paritytech/substrate/pull/7363) by [@gavofyork](https://github.com/gavofyork)
- PR: [Cleaner GRANDPA RPC API for proving finality](https://github.com/paritytech/substrate/pull/7339) by [@octol](https://github.com/octol)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

8 merged PRs ([1][secret_network-merged-prs-1]), 1 closed issues ([1][secret_network-closed_issues-1]), 
1 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- PR: [Fix links to quickstart topics](https://github.com/enigmampc/SecretNetwork/pull/716) by [@levackt](https://github.com/levackt)
- PR: [Update quickstart](https://github.com/enigmampc/SecretNetwork/pull/715) by [@levackt](https://github.com/levackt)

#### [Solana](https://github.com/solana-labs/solana)

357 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 48 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
47 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- Project: [Anchor](https://github.com/project-serum/anchor), a Rust eDSL for writing Solana programs.
- News: [Announcing the Solana Foundation x Serum DeFi Hackathon](https://medium.com/solana-labs/announcing-the-solana-foundation-x-serum-defi-hackathon-7e34290f8262)
- Blog: [Solana Year in Review 2020](https://medium.com/solana-labs/year-in-review-2020-c3731d1cc8a)
- PR: [Clean accounts cache before flush](https://github.com/solana-labs/solana/pull/14596) by [@carllin](https://github.com/carllin)
- PR: [Parallel cache scan](https://github.com/solana-labs/solana/pull/14544) by [@carllin](https://github.com/carllin)
- PR: [swap: Add rounding correction for deposit / withdraw](https://github.com/solana-labs/solana-program-library/pull/1061) by [@joncinque](https://github.com/joncinque)

#### [Zcash](https://z.cash/)


79 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 41 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
54 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-01-01..2021-01-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-01-01..2021-01-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-01-01..2021-01-31

- News:
  - [Announcing ZIP 224: Bringing Halo 2 to Zcash](https://electriccoin.co/blog/announcing-zip-224-bringing-halo-2-to-zcash/)
  - [Zcash Developers Update 1-8-2021](https://www.zcashcommunity.com/2021/01/08/zcash-developers-update-1-8-2021/)
- Blog:
  - [Electric Coin Co. Engineering: 2020, a year in review](https://electriccoin.co/blog/electric-coin-co-engineering-2020-a-year-in-review/)
  - [Technical explainer: Halo on Zcash](https://electriccoin.co/blog/technical-explainer-halo-on-zcash/)
- PR: [Data Access API (Low-level wallet persistence API)](https://github.com/zcash/librustzcash/pull/307) by [@nuttycom](https://github.com/nuttycom)
- PR: [New Transcript API (and modified commitment scheme)](https://github.com/zcash/halo2/pull/111) by [@ebfull](https://github.com/ebfull)
- PR: [Add sqrt_ratio implementation.](https://github.com/zcash/halo2/pull/120) by [@daira](https://github.com/daira)

&nbsp;

## Events

Feb 1-21 | Online

[Binance Hackathon: The Future Is Now](https://gitcoin.co/issue/binancex/Grant-projects/17/100024656)

Feb 6-7 | Online

[FOSDEM21](https://fosdem.org/2021/)

Feb 15-Mar 1 | Online

[Solana Foundation x Serum DeFi Hackathon](https://solana.com/defi)

&nbsp;

## Careers

Aleo | Remote

- [Community Manager](https://aleo.org/jobs/community-manager)

The Graph | Remote

- [Rust Engineer at The Graph](https://thegraph.com/jobs/rust-engineer)

Zcash | Remote

- [Open Position: Cryptography Engineer](https://www.zfnd.org/blog/open-position-cryptography-engineer/)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#21 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


