---
title: "RiB Newsletter #13 – Stuck inside, hacking away"
description: "#13 - June 2020"
date: 2020-07-01
slug: "/2020-07-01-stuck-inside-hacking-away"
categories:
  - "newsletters"
summary: This month, We don't see a consistent blockchain Rust theme to highlight this month, but interesting new Rust crypto and blockchain projects continue to be launched. They are noted in the "Interesting Things" section.

---


Welcome to the #13 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #12](/newsletters/2020-06-03-zk-rustups/).

It was another month in 2020, like previous months in 2020. Stuck inside, hacking away.

We don't see a consistent blockchain Rust theme to highlight this month, but interesting new Rust crypto and blockchain projects continue to be launched. They are noted in the "Interesting Things" section.

[Oasis launched what will probably become their mainnet][oasis-1]. Congrats to them!

Ethereum 2 [keeps creeping closer][eth2-1], and it looks like [Lighthouse], in Rust, might be [the fastest implementation][eth2-2].

The Holochain team asked that we highlight the [Holochain DevCamp][hdc], running until August 27th. Now is your opportunity to learn more about the project. There are a number of other online blockchain hackathons going on this summer, noted in our "Events" section. Could be a good way to spend time this summer instead of going to the beach.

Well, anyway, keep on hacking.

[oasis-1]: https://medium.com/oasis-protocol-project/the-amber-network-is-live-1caa1289cbd8
[hdc]: https://holochain.typeform.com/to/ptZ79fac
[eth2-1]: https://hackmd.io/@benjaminion/eth2_news/https%3A%2F%2Fhackmd.io%2F%40benjaminion%2Fwnie2_200627
[Lighthouse]: https://github.com/sigp/lighthouse
[eth2-2]: https://github.com/q9f/eth2-bench-2020-06/blob/master/res/2020-06-eth2-bench.pdf

&nbsp;

## Thanks

This edition of RiB was produced with contributions from Darosior, [James Waugh][contributorjw], Ken Shamir, Paulii Good, Taylor Lee, [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. If you follow a particular project, or otherwise find information that is beneficial to the Rust & blockchain community, please contribute to the next issue. Either submit a PR to the [#14 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorjw]: https://github.com/jlwaugh
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;


&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[electrs].

`electrs` is a server for the [Electrum] Bitcoin wallet, written in Rust. Electrum is a light wallet that
needs to connect to a server to transact with the Bitcoin network. Although there are public Electrum servers,
and they are safe to transact with, they can deanonymize users, so it might be prudent to run one's own
Electrum server, like `electrs`, or [`bwt`][bwt] (also written in Rust).

As [mentioned recently in a blog post][bsblog], Blockstream, one of the primary Bitcoin developers,
uses `electrs` in its block explorer, [`esplora`], which is live at [blockstream.info].


[electrs]: https://github.com/romanz/electrs
[Electrum]: https://electrum.org/
[bwt]: https://github.com/shesek/bwt
[`esplora`]: https://github.com/Blockstream/esplora
[bsblog]: https://blockstream.com/2020/06/16/en-esplora-and-other-alternatives-to-electrumx/
[blockstream.info]: https://blockstream.info


&nbsp;

## Interesting Things

News: [Enigma partners with IBM on "SafeTrace"](https://www.ibm.com/cloud/blog/enigma-and-ibm-cloud-are-protecting-human-lives-as-well-as-data-privacy), a contact tracing app. Enigma is a Rust blockchain with private computation.

News: [Oasis](https://twitter.com/OasisProtocol) launched [The Amber Network](https://medium.com/oasis-protocol-project/the-amber-network-is-live-1caa1289cbd8), and the new white paper [The Oasis Blockchain Platform](https://docsend.com/view/aq86q2pckrut2yvq).

[New RustCrypto releases](https://www.reddit.com/r/rust/comments/h0em5n/ann_new_rustcrypto_releases_aead_blockcipher/): `aead`, `block-cipher`, `crypto-mac`, `digest`, `signature`, `stream-cipher`, and more!

Blog: [Evaluating Ethereum L2 Scaling Solutions: A Comparison Framework](https://medium.com/matter-labs/evaluating-ethereum-l2-scaling-solutions-a-comparison-framework-b6b2f410f955)

Blog: [Introducing Covalent's DeFi SDK – An integrated approach to value your digital assets with 5 lines of code](https://www.covalenthq.com/blog/covalent-defi-sdk/)

Blog: [How I checked over 1 trillion mnemonics in 30 hours to win a bitcoin.](https://medium.com/@johncantrell97/how-i-checked-over-1-trillion-mnemonics-in-30-hours-to-win-a-bitcoin-635fe051a752)

Paper: [Bulletproofs+](https://eprint.iacr.org/2020/735). A new paper with improvements to bulletproofs.

Project: [blst](https://github.com/supranational/blst/). An implementation of BLS12-381. In C, with Rust bindings.

Project: [celo-bls-snark-rs](https://github.com/celo-org/celo-bls-snark-rs). Implements SNARK-friendly BLS signatures over BLS12-377 and BW6-761.

Project: [Candid](https://github.com/dfinity/candid), an interface description language (IDL) for interacting with canisters (also known as services or actors) running on the Internet Computer.

Project: [Crate Crypto](https://github.com/crate-crypto). Open source cryptographic implementations. Mostly from IACR.

Project: [ethcontract-rs](https://github.com/gnosis/ethcontract-rs). Generate type-safe bindings for interacting with Ethereum contracts. 

Project: [Neptune](https://github.com/filecoin-project/neptune). Neptune is a Rust implementation of the Poseidon hash function tuned for Filecoin.

Project: Nervos CKB
- [ckb-std](https://github.com/nervosnetwork/ckb-std) contains serveral modules that help you write CKB contract with Rust.
- [ckb-zkp](https://github.com/sec-bit/ckb-zkp). Zero Knowledge Proofs Toolkit for CKB.

Project: [poly-commit](https://github.com/scipr-lab/poly-commit). Univariate Polynomial Commitments. A Rust library that implements (univariate) polynomial commitment schemes.

Project: [riemann-rs](https://github.com/summa-tx/riemann-rs). Bitcoin-oriented dev toolboxes for native and browser apps.

Project: [Sigma Rust](https://github.com/ergoplatform/sigma-rust). Rust implementation of ErgoScript cryptocurrency scripting language.

Project: The [Stacks 2.0](https://github.com/blockstack/stacks-blockchain) blockchain implementation, an open-membership replicated state machine produced by the coordination of a non-enumerable set of peers.

Project: [Starcoin](https://github.com/starcoinorg/starcoin). A Layered Cryptocurrency and Decentralized Blockchain System.

Video: [ZkVM: About the motocrab](https://www.youtube.com/watch?v=1i-EJykVzag). ZkVM is a zero-knowledge VM created by Stellar.

&nbsp;

## Most Active in June

[**Parity** ](https://github.com/paritytech): 
277 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2]), 122 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 84 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[**Solana**](https://github.com/solana-labs/solana): 
245 merged PRs ([1][solana-merged-prs-1]), 26 closed issues ([1][solana-closed_issues-1]), 33 open issues ([1][solana-open_issues-1])

[**COMIT**](https://comit.network/):
186 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 71 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3], [4][comit-closed_issues-4]), 15 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2], [3][comit-open_issues-3])

[**NEAR**](https://github.com/nearprotocol/nearcore):
90 merged PRs ([1][near-merged-prs-1]), 70 closed issues ([1][near-closed_issues-1]), 45 open issues ([1][near-open_issues-1])

&nbsp;

## Project Updates

#### [Bitcoin](https://github.com/rust-bitcoin)

14 merged PRs ([1][bitcoin-merged-prs-1], [2][bitcoin-merged-prs-2], [3][bitcoin-merged-prs-3], [4][bitcoin-merged-prs-4], [5][bitcoin-merged-prs-5]), 3 closed issues ([1][bitcoin-closed_issues-1], [2][bitcoin-closed_issues-2]), 5 open issues ([1][bitcoin-open_issues-1], [2][bitcoin-open_issues-2], [3][bitcoin-open_issues-3], [4][bitcoin-open_issues-4])


[bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/murmel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/rust-lightning-invoice/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[bitcoin-open_issues-2]: https://github.com/rust-bitcoin/murmel/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- PR: [Incl tx fee when calcing inbound+outbound HTLC limits on channels](https://github.com/rust-bitcoin/rust-lightning/pull/577) by [@valentinewallace](https://github.com/valentinewallace)
- PR: [Pre-C bindings cleanups (2)](https://github.com/rust-bitcoin/rust-lightning/pull/638) by [@TheBlueMatt](https://github.com/TheBlueMatt)
- PR: [Drop ChannelKeys Private Key Methods](https://github.com/rust-bitcoin/rust-lightning/pull/632) by [@TheBlueMatt](https://github.com/TheBlueMatt)


#### [CodeChain](https://github.com/codeChain-io/)

28 merged PRs ([1][codechain-merged-prs-1], [2][codechain-merged-prs-2], [3][codechain-merged-prs-3]), 6 closed issues ([1][codechain-closed_issues-1], [2][codechain-closed_issues-2]), 2 open issues ([1][codechain-open_issues-1], [2][codechain-open_issues-2])

[codechain-merged-prs-1]: https://github.com/CodeChain-io/codechain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[codechain-merged-prs-2]: https://github.com/CodeChain-io/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[codechain-merged-prs-3]: https://github.com/CodeChain-io/foundry-sandbox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[codechain-closed_issues-1]: https://github.com/CodeChain-io/codechain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[codechain-closed_issues-2]: https://github.com/CodeChain-io/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[codechain-open_issues-1]: https://github.com/CodeChain-io/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[codechain-open_issues-2]: https://github.com/CodeChain-io/foundry-sandbox/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- PR: [Fix a deadlock in miner.rs](https://github.com/CodeChain-io/codechain/pull/1968) by [@majecty](https://github.com/majecty)

#### [**COMIT**](https://github.com/comit-network)

186 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 71 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3], [4][comit-closed_issues-4]), 15 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2], [3][comit-open_issues-3])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[comit-merged-prs-2]: https://github.com/comit-network/comit-js-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[comit-merged-prs-3]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[comit-closed_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[comit-closed_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[comit-closed_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[comit-closed_issues-4]: https://github.com/comit-network/comit.network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[comit-open_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[comit-open_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[comit-open_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- PR: [Respawn feature](https://github.com/comit-network/comit-rs/pull/2790) by [@luckysori](https://github.com/luckysori)
- PR: [Add herc20-hbit and hbit-herc20](https://github.com/comit-network/comit-rs/pull/2776) by [@da-kami](https://github.com/da-kami)
- PR: [Clean up storage](https://github.com/comit-network/comit-rs/pull/2818) by [@tcharding](https://github.com/tcharding)
- PR: [Re-export rust-bitcoin from COMIT lib](https://github.com/comit-network/comit-rs/pull/2846) by [@luckysori](https://github.com/luckysori)

#### [Crypto.com Chain](https://chain.crypto.com)

73 merged PRs ([1][crypto.com-merged-prs-1], [2][crypto.com-merged-prs-2], [3][crypto.com-merged-prs-3]), 42 closed issues ([1][crypto.com-closed_issues-1]), 39 open issues ([1][crypto.com-open_issues-1])

[crypto.com-merged-prs-1]: https://github.com/crypto-com/chain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[crypto.com-merged-prs-2]: https://github.com/crypto-com/chain-nodelib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[crypto.com-merged-prs-3]: https://github.com/crypto-com/sample-chain-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[crypto.com-closed_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[crypto.com-open_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- PR: [Problem (Fix #1703): incorrect tree hashing in mls modules](https://github.com/crypto-com/chain/pull/1760) by [@yihuang](https://github.com/yihuang)
- PR: [Problem: `tx-query2-app-runner` build fails](https://github.com/crypto-com/chain/pull/1693) by [@devashishdxt](https://github.com/devashishdxt)
- PR: [Problem: no gen keypackage command in dev-utils (fix #1692)](https://github.com/crypto-com/chain/pull/1738) by [@leejw51crypto](https://github.com/leejw51crypto)


#### [Holochain](https://github.com/holochain/)

3 merged PRs ([1][holochain-merged-prs-1]), 0 closed issues, 0 open issues

[holochain-merged-prs-1]: https://github.com/holochain/holochain-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30

- News: [Holochain v0.0.49 released](https://blog.holochain.org/holochain-v0-0-49-released/)
- News: [Holochain Dev Pulse 74: Generate Your hApp's Source Code in Seconds](https://blog.holochain.org/generate-your-happs-source-code-in-seconds/)
- Video: [AMA 38 Let's Talk Tech!](https://youtu.be/gZZCjFPMMYM)
- News: [Holochain DevCamp 7](https://holochain.typeform.com/to/ptZ79fac) 
  - DevCamp 7 is a month long, community-run, online Holochain developer training program. Get hands on experience building a Holochain App with 2 live sessions every week, coding assignments, and support on our online platform!  (all sessions will be recorded and posted)
- PR: [Experimental REPL for debug purposes](https://github.com/holochain/holochain-rust/pull/2196) by [@zippy](https://github.com/zippy)

#### [Libra](https://libra.org)

1 merged PRs ([1][libra-merged-prs-1]), 35 closed issues ([1][libra-closed_issues-1]), 69 open issues ([1][libra-open_issues-1])

[libra-merged-prs-1]: https://github.com/libra/libra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [Testnet push announcement for 07/01](https://community.libra.org/t/testnet-push-announcement-for-07-01/2960)
- News: [The Libra Association appoints Sterling Daines as Chief Compliance Officer](https://libra.org/en-US/updates/cco-announcement/)
- PR: [[circle] ignore gh-pages](https://github.com/libra/libra/pull/4813) by [@rexhoffman](https://github.com/rexhoffman)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

62 merged PRs ([1][lighthouse-merged-prs-1]), 17 closed issues ([1][lighthouse-closed_issues-1]), 19 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [Lighthouse Update #26](https://lighthouse.sigmaprime.io/update-26.html)
- News: [What's new in Eth2](https://hackmd.io/@benjaminion/eth2_news/https%3A%2F%2Fhackmd.io%2F%40benjaminion%2Fwnie2_200627). Links to a [benchmark](https://github.com/q9f/eth2-bench-2020-06/blob/master/res/2020-06-eth2-bench.pdf) indicating that Lighthouse is the best-performing Ethereum 2 implementation.
- PR: [Improve tokio task execution](https://github.com/sigp/lighthouse/pull/1181) by [@pawanjay176](https://github.com/pawanjay176)
- PR: [Add error handling to iterators](https://github.com/sigp/lighthouse/pull/1243) by [@adaszko](https://github.com/adaszko)
- PR: [Add first Server Sent Events API endpoint](https://github.com/sigp/lighthouse/pull/1107) by [@adaszko](https://github.com/adaszko)
- PR: [Deposit functionality now works with IPC & RPC](https://github.com/sigp/lighthouse/pull/1211) by [@ethDreamer](https://github.com/ethDreamer)

#### [MobileCoin](https://www.mobilecoin.com/)

50 merged PRs ([1][mobilecoin-merged-prs-1]), 0 closed issues, 0 open issues

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinofficial/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30

- News: [CAST joins the ranks of the MobileCoin Foundation](https://medium.com/mobilecoin/cast-joins-the-ranks-of-the-mobilecoin-foundation-3a359583f101)
- News: [Say hello to MobileCoin Foundation board member, Sarah Novotny](https://medium.com/mobilecoin/say-hello-to-mobilecoin-foundation-board-member-sarah-novotny-a729eee18392)
- News: [Ideas Beyond Borders joins the MobileCoin Foundation](https://medium.com/mobilecoin/ideas-beyond-borders-joins-the-mobilecoin-foundation-8e5943afc9df)
- News: [Blockdaemon, Welcome to the MobileCoin Foundation](https://medium.com/mobilecoin/blockdaemon-welcome-to-the-mobilecoin-foundation-3ec199b7507f)
- Blog: [Return to Satoshi’s Pizzeria](https://medium.com/mobilecoin/return-to-satoshis-pizzeria-9b66bb883f17)
- PR: [New fields in account keys and public addresses](https://github.com/mobilecoinofficial/mobilecoin/pull/240) by [@garbageslam](https://github.com/garbageslam)
- PR: [Multiple measurements](https://github.com/mobilecoinofficial/mobilecoin/pull/188) by [@sugargoat](https://github.com/sugargoat)
- PR: [Disallow duplicate TxOut public keys](https://github.com/mobilecoinofficial/mobilecoin/pull/211) by [@eranrund](https://github.com/eranrund)

#### [NEAR](https://github.com/nearprotocol/nearcore)

90 merged PRs ([1][near-merged-prs-1]), 70 closed issues ([1][near-closed_issues-1]), 45 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[near-closed_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[near-open_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [Send NEAR to Anyone with NEAR Drops](https://near.org/blog/send-near-to-anyone-with-near-drops/)
- News: [Guild Program Launch](https://near.org/blog/guild-program-launch/)
  - [Developer Program: How to Develop on NEAR](https://near.org/developer-program/)
- News: [NEAR Token Supply and Distribution](https://near.org/blog/near-token-supply-and-distribution/)
- News: Community Update: [June 19th](https://near.org/blog/community-update-june-19th-2020/), [June 5th](https://near.org/blog/community-update-june-5th-2020/)
- Video: Whiteboard Series with NEAR
  - [Ep: 36 Muneeb Ali, Aaron Blankstein, Diwaker Gupta from Blockstack](https://www.youtube.com/watch?v=dEQFPNWaOHY)
  - [Ep: 35 Ben Jones from Optimism](https://www.youtube.com/watch?v=oahaMa3XB0k)
- PR: [feat(storage): implement its own GC method](https://github.com/nearprotocol/nearcore/pull/2802) by [@ailisp](https://github.com/ailisp)
- PR: [feat(runtime): support more than one VM.](https://github.com/nearprotocol/nearcore/pull/2853) by [@olonho](https://github.com/olonho)
- PR: [feat(chain): Upgradability functionality](https://github.com/nearprotocol/nearcore/pull/2701) by [@ilblackdragon](https://github.com/ilblackdragon)
- PR: [feat(Runtime): Dynamic gas pricing](https://github.com/nearprotocol/nearcore/pull/2813) by [@evgenykuzyakov](https://github.com/evgenykuzyakov)

#### [Nervos](https://github.com/nervosnetwork)

39 merged PRs ([1][nervos-merged-prs-1]), 5 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 3 open issues ([1][nervos-open_issues-1], [2][nervos-closed_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[nervos-closed_issues-2]: https://github.com/nervosnetwork/rfcs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [Nervos Grant Announcement: Obsidian Systems Hardware Wallet Support](https://medium.com/nervosnetwork/nervos-grant-announcement-obsidian-systems-hardware-wallet-support-c70287c73c2f)
- News: Nervos CKB Development Update [#37](https://medium.com/nervosnetwork/nervos-ckb-development-update-37-439787ee3363), [#36](https://medium.com/nervosnetwork/nervos-ckb-development-update-36-b1d19ba75488)
- Blog: [A Tale of Abstractions: the quest for better CKB developer tools](https://medium.com/nervosnetwork/a-tale-of-abstractions-the-quest-for-better-ckb-developer-tools-550aed756a91)
- PR: [Optimize scheduler](https://github.com/nervosnetwork/ckb/pull/2067) by [@driftluo](https://github.com/driftluo)
- PR: [refactor: move network protocol related variables to SupportProtocols](https://github.com/nervosnetwork/ckb/pull/2096) by [@quake](https://github.com/quake)
- PR: [feat: update last_common_header only in find_blocks_to_fetch](https://github.com/nervosnetwork/ckb/pull/2081) by [@keroro520](https://github.com/keroro520)

#### [Parity](https://github.com/paritytech)

277 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2]), 122 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 84 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [Join Hackusama - Hack on Polkadot's Wild Cousin!](https://polkadot.network/join-hackusama-hack-on-polkadots-wild-cousin/)
- News: [Kusama Treasury Funds Seven Teams in Seven Weeks](https://polkadot.network/kusama-treasury-funds-seven-teams-in-seven-weeks/)
- News: [Polkadot Research Update](https://polkadot.network/polkadot-research-update/)
- News: [Polkadot, Kusama and Gitcoin: Building the Future](https://polkadot.network/polkadot-kusama-and-gitcoin-building-the-future/)
- Blog: [Polkadot Launch: Phase 2](https://medium.com/polkadot-network/polkadot-launch-phase-2-e45c635031ef)
- Blog: [What is Polkadot? Part 2: The Vision](https://polkadot.network/what-is-polkadot-part-2-the-vision/)
- Blog: [Polkadot Governance](https://polkadot.network/polkadot-governance/)
- PR: [Implement nested storage transactions](https://github.com/paritytech/substrate/pull/6269) by [@athei](https://github.com/athei)
- PR: [Overseer](https://github.com/paritytech/polkadot/pull/1152) by [@montekki](https://github.com/montekki)
- PR: [Implement Network Bridge](https://github.com/paritytech/polkadot/pull/1280) by [@rphmeier](https://github.com/rphmeier)
- PR: [Stored call in multisig](https://github.com/paritytech/substrate/pull/6319) by [@gavofyork](https://github.com/gavofyork)
- PR: [Make transaction pool prune transactions only of canonical blocks](https://github.com/paritytech/substrate/pull/6123) by [@bkchr](https://github.com/bkchr)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

50 merged PRs ([1][secretnetwork-merged-prs-1]), 64 closed issues ([1][secretnetwork-closed_issues-1]), 35 open issues ([1][secretnetwork-open_issues-1])

[secretnetwork-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[secretnetwork-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[secretnetwork-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [Secret Contracts Update: Milestone 3 of 3 Complete!](https://blog.scrt.network/secret-contracts-update-milestone-3-of-3-is-complete)
- News: [Introducing Secret Network](https://blog.scrt.network/introducing-secret-network)
- News: [Enigma and IBM Cloud are Protecting Human Lives as Well as Data Privacy](https://www.ibm.com/cloud/blog/enigma-and-ibm-cloud-are-protecting-human-lives-as-well-as-data-privacy)
- News: [Introducing Secret Foundation](https://blog.scrt.network/introducing-secret-foundation)
- News: [Announcing the Secret Games and Incentivized Testnet](https://blog.scrt.network/announcing-the-secret-games)
- Blog: [Secret Hub: Making Privacy One With the Cosmos](https://blog.scrt.network/secret-hub)
- Blog: [Secret Network Development Update: May 2020](https://blog.scrt.network/secret-network-development-update-may-2020)
- PR: [CosmWasm 0.9](https://github.com/enigmampc/SecretNetwork/pull/262) by [@reuvenpo](https://github.com/reuvenpo)

#### [Solana](https://github.com/solana-labs/solana)

245 merged PRs ([1][solana-merged-prs-1]), 26 closed issues ([1][solana-closed_issues-1]), 33 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [May Newsletter](https://medium.com/solana-labs/may-newsletter-6961c28a4389)
- News: [The Decentralized Solana DShop Swag Store, Powered by Origin Protocol, is Now Live](https://medium.com/solana-labs/the-decentralized-solana-dshop-swag-store-powered-by-origin-protocol-is-now-live-1f1668fce4dc)
- New: [Solana Foundation Transparency Report #1](https://medium.com/solana-labs/solana-foundation-transparency-report-1-b267fe8595c0)
- News: [Solana Token (SOL) Featured In Gate.io Listing Competition](https://medium.com/solana-labs/solana-token-sol-featured-in-gate-io-listing-competition-1ab422e69c6d)
- News: [Double Rewards on Solana Liquidity Mining Campaign](https://medium.com/solana-labs/double-rewards-on-solana-liquidity-mining-campaign-95359bcf2e46)
- New: [Announcing the Formation of the Solana Foundation](https://medium.com/solana-labs/announcing-the-formation-of-the-solana-foundation-afde417afd73)
- PR: [Add staking guide to docs](https://github.com/solana-labs/solana/pull/10609) by [@danpaul000](https://github.com/danpaul000)
- PR: [Dont skip eager rent collect across gapped epochs](https://github.com/solana-labs/solana/pull/10206) by [@ryoqun](https://github.com/ryoqun)

#### [Zcash](https://z.cash/)

84 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 37 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 41 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-06-01..2020-06-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[zcash-closed_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-06-01..2020-06-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30
[zcash-open_issues-2]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aopen+created%3A2020-06-01..2020-06-30

- News: [Foundation DNS Seeders Are Live](https://www.zfnd.org/blog/foundation-dns-seeder/)
- News: ZCASH DEVELOPERS UPDATE [06-26](https://www.zcashcommunity.com/2020/06/26/zcash-developers-update-6-26-2020/), [06-19](https://www.zcashcommunity.com/2020/06/19/zcash-developers-update-6-19-2020/), [06-12](https://www.zcashcommunity.com/2020/06/12/zcash-developers-update-6-12-2020/), [06-05](https://www.zcashcommunity.com/2020/06/05/zcash-developers-update-6-5-2020/)
- Blog: [So You Want to Build an End-to-End Encrypted Web App](https://www.zfnd.org/blog/so-you-want-an-e2e-encrypted-webapp/)
- Blog: [Zcash privacy remains strongest of any cryptocurrency, even with recent Chainalysis, Elliptic support](https://electriccoin.co/blog/zcash-privacy-remains-strongest-of-any-cryptocurrency/)
- Blog: [Kubernetes and blockchains at ECC](https://electriccoin.co/blog/kubernetes-and-blockchains-at-ecc/)
- Blog: [ECC Wallet threat model and security assessment results](https://electriccoin.co/blog/ecc-wallet-threat-model-and-security-assessment-results/)
- Blog: [The upside of quadratic funding for the Zcash ecosystem](https://electriccoin.co/blog/the-upside-of-quadratic-funding-for-the-zcash-ecosystem/)
- Blog: [7 things we learned building the shielded-first ECC Wallet](https://electriccoin.co/blog/7-things-we-learned-building-the-shielded-first-ecc-wallet/)
- Blog: [Heartwood security assessment turns up no major issues](https://electriccoin.co/blog/heartwood-security-assessment-turns-up-no-major-issues/)
- Report: [ECC Transparency Report for Q4 2019](https://electriccoin.co/blog/ecc-transparency-report-for-q4-2019/)
- PR: [Block Verification Stubs](https://github.com/ZcashFoundation/zebra/pull/448) by [@teor2345](https://github.com/teor2345)
- PR: [Implement sync component for start subcommand](https://github.com/ZcashFoundation/zebra/pull/506) by [@yaahc](https://github.com/yaahc)
- PR: [Implement ff traits for bls12_381 and jubjub crates](https://github.com/zcash/librustzcash/pull/227) by [@str4d](https://github.com/str4d)
- PR: [Add serde bounds to zebra-chain structures.](https://github.com/ZcashFoundation/zebra/pull/231) by [@hdevalence](https://github.com/hdevalence)

&nbsp;

## Events

Jun - Aug | Online

[8 week online university blockchain hackathon](https://summerspark.encode.club/)

Jul 1-22 | Online

[Saigon: Online Holochain Meetup](https://www.meetup.com/Saigon-Holochain-Meetup-Group/events/271099358/)

[Cape Town: Holochain Meetup](https://www.meetup.com/Cape-Town-Holochain-Meetup-Group/events/271099363/)

More [Holochain events](https://holo.host/events/)

Jul 8, Jul 15-22 | Online

[Hacking @ Random](https://starkware.co/hacking-at-random/)

Jun 28 - Aug 27 | Online

[Holochain DevCamp 7](https://holochain.typeform.com/to/ptZ79fac)

Jun 29 - Aug 14 | Online

[Hackusama](https://github.com/Web3Foundation/hackathons/issues/1)

Jul 6 - Aug 6 | Online

[HackFS](https://hackfs.com/)

Aug 3-6, 2020 | Oxford, UK

[IEEE DAPPS 2020](https://ieeedapps.net/)

Aug 5, 2020 | Online

[DeFi Conference 2020](http://bitcoinevents.co.za/)

Oct 21-23 | NYC, US

[ACM Advances in Financial Technologies](https://aft.acm.org/)


&nbsp;

## Careers


Chainlink | Remote

[Senior Software Engineer](https://careers.smartcontract.com/o/senior-software-engineer-new-york)

[Blockchain Engineer, Integrations](https://careers.smartcontract.com/o/blockchain-engineer-integrations)

Definity | SF, US

[Software Engineer, SDK](https://boards.greenhouse.io/dfinity/jobs/4286745002)

[Senior Software Engineer - Infrastructure and Tools](https://boards.greenhouse.io/dfinity/jobs/4473085002)

Findora | CA, US

[Systems Engineer](https://jobs.lever.co/findora/88501a0d-a86d-4cd2-b0b7-8625a107b02b)

IOTA | Remote

[Software Engineer - Rust](https://iota.bamboohr.com/jobs/view.php?id=105)

Kraken | London, UK; Remote

[Backend Engineer, Kraken Futures](https://jobs.lever.co/kraken/fe1e07f4-6d7c-4f65-9a8f-27cf3b3fd2b1)

[Backend Engineer, Data Processing](https://jobs.lever.co/kraken/246f7fd2-000a-4f61-8f53-b1cc783d51cb)

Ockam | Remote

[Software Architect - Applied Cryptography in Rust](https://www.ockam.io/team/Software-Architect-Applied-Cryptography-in-Rust/61e07e82-0589-51de-b250-42dbceb31c3c)

Polymath | Ontario; Remote

[Senior Rust Engineer](https://polymath.bamboohr.com/jobs/view.php?id=96)


&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#14 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
