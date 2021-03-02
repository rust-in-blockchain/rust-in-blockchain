---
title: "RiB Newsletter #21"
description: "#21 - Feb 2021"
date: 2021-03-02
slug: "/rust-explosion"
categories:
  - "newsletters"
summary: "It's still a great time to be a Rust programmer."
---

Welcome to the #21 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #20](/newsletters/old-fashioned-chill/).

It's still a great time to be a Rust programmer.

This month the [Rust Foundation] was announced,
and major tech companies including Microsoft, Google, Amazon, and Facebook
have hired prominent Rust compiler developers.
Kraken, a major cryptocurrency exchange,
posted [a blog about how much they love Rust][krblog],
then immediately posted a bazillion job openings,
which we have added to the other job openings
in the "careers" section below,
and the [job board] on the website.

[Rust Foundation]: https://foundation.rust-lang.org/posts/2021-02-08-hello-world/
[krblog]: https://blog.kraken.com/post/7964/oxidizing-kraken/
[job board]: https://rustinblockchain.org/job-board/

This month [NEAR announced a grants program][ngrant],
and [so did Secret Network][sgrant].
Many other Rust blockchains have grant programs:
Polkadot [has one][pgrant],
and [so does Nervos][nvgrant],
and [so does Solana][sogrant],
and [so does Zcash][zgrant].

[ngrant]: https://near.org/blog/announcing-near-grants-pilot-program/
[sgrant]: https://scrt.network/blog/announcing-secret-network-grant-program
[pgrant]: https://github.com/w3f/General-Grants-Program
[nvgrant]: https://www.nervos.org/developer/grants/
[sogrant]: https://solana.com/grants
[zgrant]: https://www.zfnd.org/grants/

And RiB can now accept donations in NEAR at [@rib.near],
the account for which was donated to us by
Peter from the NEAR team. RiB also accepts donations
in BTC, ETH, and CKB, the addresses for which
are [on the website][ribsite].

[@rib.near]: https://explorer.near.org/accounts/rib.near
[ribsite]: https://rustinblockchain.org/

&nbsp;



## Thanks

Thanks to contributors:
[apruden2008][contributor-ap],
[Ernest Kissiedu][contributor-ek],
[Max Wegman][contributor-mw],
[Brian Anderson][contributorba], and [Aimee Zhu][contributoraz].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#22 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributor-ap]: https://github.com/apruden2008
[contributor-ek]: https://github.com/ernestkissiedu
[contributor-mw]: https://github.com/mastermaxy
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[rust-umbral](https://github.com/nucypher/rust-umbral).

Umbral is a scheme for [proxy re-encryption][pre],
by which the owner of a ciphertext, Alice,
can designate a third party (the proxy),
to re-encrypt that ciphertext to be decoded by Bob,
without ever revealing the plaintext to the proxy.

Described in [a 2018 paper][ump],
and [blog post][umbp],
Umbral is developed by the [NuCypher] project.

[pre]: https://en.wikipedia.org/wiki/Proxy_re-encryption
[ump]: https://github.com/nucypher/umbral-doc/blob/master/umbral-doc.pdf
[umbp]: https://blog.nucypher.com/unveiling-umbral/
[NuCypher]: https://www.nucypher.com/

&nbsp;

## Interesting Things

#### News

- [Leading Defi projects, wallets and exchanges invest to bring Solidity to zkSync](https://medium.com/matter-labs/leading-defi-projects-and-exchanges-invest-to-bring-solidity-to-zksync-9a3df978f824)
- [Rust Foundation](https://foundation.rust-lang.org/posts/2021-02-08-hello-world/)

#### Blog Posts

- [Oxidizing Kraken](https://blog.kraken.com/post/7964/oxidizing-kraken/)
- [Confessions of a smart contract paper reviewer](https://blog.trailofbits.com/2021/02/05/confessions-of-a-smart-contract-paper-reviewer/)
- [Serving up zero-knowledge proofs](https://blog.trailofbits.com/2021/02/19/serving-up-zero-knowledge-proofs/)

#### Podcasts

- [Arkworks SNARK libraries with Pratyush Mishra](https://www.zeroknowledge.fm/169)
- [Dan Guido - What the hell are the blockchain people doing & why isn't it a dumpster fire?](https://www.youtube.com/watch?v=wT-AmR7wtI8)

#### Papers

- [Smart Contracts for Incentivized Outsourcing of Computation](https://eprint.iacr.org/2021/174)
- [Smart Contract Security: a Practitioners' Perspective](https://paperswithcode.com/paper/smart-contract-security-a-practitioners)
- [SigVM: Toward Fully Autonomous Smart Contracts](https://arxiv.org/pdf/2102.10784.pdf)
- [smartFHE: Privacy-Preserving Smart Contracts from Fully Homomorphic Encryption](https://eprint.iacr.org/2021/133)
- [OptSmart: A Space Efficient Optimistic Concurrent Execution of Smart Contracts](https://arxiv.org/abs/2102.04875)
- [Efficient State Management in Distributed Ledgers](https://eprint.iacr.org/2021/183)
- [Peer-to-Peer Content Delivery via Blockchain](https://arxiv.org/abs/2102.04685)
- [A Security Framework for Distributed Ledgers](https://eprint.iacr.org/2021/145)
- [Verification Dilemmas, Law, and the Promise of Zero-Knowledge Proofs](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3781082)
- [IPDL: A Simple Framework for Formally Verifying Distributed Cryptographic Protocols](https://eprint.iacr.org/2021/147)
- [Group Signatures with User-Controlled and Sequential Linkability](https://eprint.iacr.org/2021/181)
- [FPPW: A Fair and Privacy Preserving Watchtower For Bitcoin](https://eprint.iacr.org/2021/117)
- [MAKE: a Matrix Action Key Exchange](https://eprint.iacr.org/2021/116)
- [GearBox: An Efficient UC Sharded Ledger Leveraging the Safety-Liveness Dichotomy](https://eprint.iacr.org/2021/211).
  From the [Concordium](https://github.com/Concordium) project.

#### Projects

- [Teleport Transactions](https://github.com/bitcoin-teleport/teleport-transactions)
  is software aiming to improve the privacy of Bitcoin.
- [Compound Chain](https://github.com/compound-finance/compound-chain).
  An interest-bearing stablecoin bridge between all DeFi chains.
- [europa](https://github.com/patractlabs/europa).
  A sandbox to run and debug smart contracts for FRAME Contracts pallet and also a sandbox framework for Substrate runtime.
- [ethabi](https://github.com/rust-ethereum/ethabi). Encode and decode smart contract invocations.
- [Hodor](https://github.com/matter-labs/hodor). Open source implementation of zkSTARKs in pure Rust.

&nbsp;

## Most Active in February

[Solana](https://github.com/solana-labs/solana):
350 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
21 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
50 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Parity](https://github.com/paritytech):
263 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
138 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
88 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[Diem](https://www.diem.com):
195 merged PRs ([1][diem-merged-prs-1]),
38 closed issues ([1][diem-closed_issues-1]), 
39 open issues ([1][diem-open_issues-1])


&nbsp;

## Project Updates

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

30 merged PRs ([1][rust-bitcoin-merged-prs-1], [2][rust-bitcoin-merged-prs-2], [3][rust-bitcoin-merged-prs-3]),
13 closed issues ([1][rust-bitcoin-closed_issues-1], [2][rust-bitcoin-closed_issues-2], [3][rust-bitcoin-closed_issues-3], [4][rust-bitcoin-closed_issues-4]), 
8 open issues ([1][rust-bitcoin-open_issues-1], [2][rust-bitcoin-open_issues-2])

[rust-bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[rust-bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [ChannelManager persistence](https://github.com/rust-bitcoin/rust-lightning/pull/752) by [@valentinewallace](https://github.com/valentinewallace)
- PR: [SPV client utility for syncing a lightning node](https://github.com/rust-bitcoin/rust-lightning/pull/791) by [@jkczyz](https://github.com/jkczyz)
- PR: [HTTP-based block source clients](https://github.com/rust-bitcoin/rust-lightning/pull/774) by [@jkczyz](https://github.com/jkczyz)

#### [Rust Ethereum](https://github.com/rust-ethereum)

2 merged PRs ([1][rust-ethereum-merged-prs-1], [2][rust-ethereum-merged-prs-2]),
0 closed issues, 
1 open issues ([1][rust-ethereum-open_issues-1])

[rust-ethereum-merged-prs-1]: https://github.com/rust-ethereum/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-ethereum-merged-prs-2]: https://github.com/rust-ethereum/devp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Remove libsecp256k1, bump dependencies, fix warnings](https://github.com/rust-ethereum/enr/pull/27) by [@vorot93](https://github.com/vorot93)
- PR: [Bump ethereum-types](https://github.com/rust-ethereum/devp2p/pull/26) by [@frostRed](https://github.com/frostRed)

#### [Aleo](https://github.com/AleoHQ)

92 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]),
69 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
20 open issues ([1][aleo-open_issues-1])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- Blog: [The Future of Zero Knowledge with Aleo](https://aleo.org/post/the-future-of-zero-knowledge-with-aleo)
- PR: [Upgrade to the Constraint System for Marlin](https://github.com/AleoHQ/snarkVM/pull/66) by [@howardwu](https://github.com/howardwu)
- PR: [Add 'leo clone' command and add integration test with Aleo Package Manager](https://github.com/AleoHQ/leo/pull/686) by [@damirka](https://github.com/damirka)
- PR: [Update POSW Implementation](https://github.com/AleoHQ/snarkOS/pull/630) by [@raychu86](https://github.com/raychu86)

#### [COMIT](https://github.com/comit-network)

58 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2]),
34 closed issues ([1][comit-closed_issues-1]), 
6 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Replace bitcoind wallet with bdk wallet](https://github.com/comit-network/xmr-btc-swap/pull/178) by [@da-kami](https://github.com/da-kami)
- PR: [Use libp2p-async-await to improve API of execution setup phase](https://github.com/comit-network/xmr-btc-swap/pull/173) by [@D4nte](https://github.com/D4nte)
- PR: [Nectar](https://github.com/comit-network/xmr-btc-swap/pull/177) by [@D4nte](https://github.com/D4nte)

#### [Fluence](https://github.com/fluencelabs)

37 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]),
2 closed issues ([1][fluence-closed_issues-1]), 
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-merged-prs-2]: https://github.com/fluencelabs/fce/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquamarine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-merged-prs-4]: https://github.com/fluencelabs/rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28

- PR: [Support numbers and booleans](https://github.com/fluencelabs/aquamarine/pull/64) by [@michaelvoronov](https://github.com/michaelvoronov)
- PR: [New mounted binaries interface](https://github.com/fluencelabs/fce/pull/64) by [@michaelvoronov](https://github.com/michaelvoronov)

#### [Holochain](https://github.com/holochain/)

43 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]),
5 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
3 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[holochain-closed_issues-2]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[holochain-open_issues-2]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- News:
  - [Elemental Chat is live!](https://medium.com/holochain/elemental-chat-is-live-68281f04450)
  - [Testing, Testing, Testing (and some goodies for developers)](https://medium.com/holochain/testing-testing-testing-and-some-goodies-for-developers-6de56a186b5c)
- Blog: [Is Holochain a Safe Haven for Dangerous Extremists or a Beacon of Hope for Accountability?](https://medium.com/holochain/is-holochain-a-safe-haven-for-dangerous-extremists-or-a-beacon-of-hope-for-accountability-fcbb8f5d38c6)
- PR: [hApp Bundles pt 3: Documentation, finishing touches, et al.](https://github.com/holochain/holochain/pull/651) by [@maackle](https://github.com/maackle)
- PR: [Allows a hc to reliably call while another hc is running the same setup](https://github.com/holochain/holochain/pull/642) by [@freesig](https://github.com/freesig)
- PR: [Improve compatibility of holochain types with Zome WASM, unify Timestamp type](https://github.com/holochain/holochain/pull/617) by [@pjkundert](https://github.com/pjkundert)

#### [Diem](https://www.diem.com)

195 merged PRs ([1][diem-merged-prs-1]),
38 closed issues ([1][diem-closed_issues-1]), 
39 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [[State Sync] Complete unit test skeleton for coordinator, better error support and clean up code.](https://github.com/diem/diem/pull/7444) by [@JoshLind](https://github.com/JoshLind)
- PR: [[move-lang] parser and typing for the public(script) visibility modifier](https://github.com/diem/diem/pull/7497) by [@mengxu-fb](https://github.com/mengxu-fb)
- PR: [Add PeerRole to identify known peers in the network](https://github.com/diem/diem/pull/7391) by [@gregnazario](https://github.com/gregnazario)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

5 merged PRs ([1][lighthouse-merged-prs-1]), 13 closed issues ([1][lighthouse-closed_issues-1]), 
5 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- News: [Lighthouse Update #34](https://lighthouse.sigmaprime.io/update-34.html)
- PR: [Auto-coerce to ping response to ipv4 when possible](https://github.com/sigp/discv5/pull/63) by [@paulhauner](https://github.com/paulhauner)
- PR: [Add mitigation for ipv6 loop](https://github.com/sigp/discv5/pull/62) by [@paulhauner](https://github.com/paulhauner)
- PR: [Add a `disconnect_node` public method](https://github.com/sigp/discv5/pull/59) by [@pawanjay176](https://github.com/pawanjay176)

#### [MobileCoin](https://www.mobilecoin.com/)

30 merged PRs ([1][mobilecoin-merged-prs-1]),
4 closed issues ([1][mobilecoin-closed_issues-1]), 
1 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [FOG-275 Fog Signature Scheme](https://github.com/mobilecoinfoundation/mobilecoin/pull/711) by [@jcape](https://github.com/jcape)
- PR: [Support reloading of GRPC services certificate/key files](https://github.com/mobilecoinfoundation/mobilecoin/pull/726) by [@eranrund](https://github.com/eranrund)

#### [NEAR](https://github.com/nearprotocol/nearcore)

86 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]),
42 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4]), 
35 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[near-merged-prs-2]: https://github.com/near/near-evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-closed_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-closed_issues-3]: https://github.com/near/near-evm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[near-open_issues-3]: https://github.com/near/near-evm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- News:
  - [NEAR Recap: ETHDenver 2021](https://near.org/blog/ethdenver2021-recap/)
  - [Flux’s Prediction Market Could Be The Key To Decentralized Insurance Markets](https://near.org/blog/prediction-market-and-insurance-with-flux/)
  - [Meet the Startups in OWC’s Batch II: Accelerating Web 3.0 Adoption](https://near.org/blog/owcbatch2/)
  - [Building New Worlds for Artists with NFTs: Paras + NEAR](https://near.org/blog/building-new-worlds-for-artists-with-nfts-paras-near/)
  - [Announcing the NEAR Foundation’s $1 Million NEAR Grants Pilot Program](https://near.org/blog/announcing-near-grants-pilot-program/)
- Blog:
  - [Berry Club: A Fun, Creative Example of a DeFi Yield Farming App on NEAR Blockchain](https://near.org/blog/funberryclub/)
  - [Berry Club Part II: How Does The Berry Club Yield Farming App Work?](https://near.org/blog/berry-club-part-ii/)
- Videos: [Fungible Token Standards (NEARly wrapped up)](https://www.youtube.com/watch?v=MQWkK3j6CPM)
- Videos: NEAR Live Contract Review
  - [Episode 14: NEAR.fm](https://www.youtube.com/watch?v=1i-HnhwoNWg)
  - [Episode 13: wNEAR - fungible token](https://www.youtube.com/watch?v=mfInOvCqLr8)
  - [Episode 12: Flux AMM](https://www.youtube.com/watch?v=MGfqwilXVuA)
- PR: [rewrite graph struct to be 200 times faster](https://github.com/near/nearcore/pull/3882) by [@pmnoxx](https://github.com/pmnoxx)
- PR: [refactor(jsonrpc): Structured errors for `GetChunk` ViewClient handler and backward compatible response from JSON RPC](https://github.com/near/nearcore/pull/3861) by [@khorolets](https://github.com/khorolets)

#### [Nervos](https://github.com/nervosnetwork)

45 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]),
2 closed issues ([1][nervos-closed_issues-1]), 
1 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[nervos-open_issues-1]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- News:
  - [Nervos Looks to Empower a Shift to DeFi with $5M Grant for Blockchain and Fintech Entrepreneurs](https://medium.com/nervosnetwork/nervos-looks-to-empower-a-shift-to-defi-with-5m-grant-for-blockchain-and-fintech-entrepreneurs-2c9bfd049a52)
  - [Nervos Quarterly Letter: A Look Back at Q4 2020](https://medium.com/nervosnetwork/nervos-quarterly-letter-a-look-back-at-q4-2020-7fe00f4c8c34)
  - [GliaDex: A Demonstration of a Universal Application at Work on Nervos](https://medium.com/nervosnetwork/gliadex-a-demonstration-of-a-universal-application-at-work-on-nervos-5ad36ceb49ff)
  - [Nervos Community Update: December 2020/January 2021](https://medium.com/nervosnetwork/nervos-community-update-december-2020-january-2021-63c5aec5de42)
- Blog:
  - [How Nervos is Tackling the State Explosion Problem Facing Smart Contract Blockchains](https://medium.com/nervosnetwork/how-nervos-is-tackling-the-state-explosion-problem-facing-smart-contract-blockchains-a9acc4c5708e)
- PR: [feat: customize chain spec for dev chains and update few preset params](https://github.com/nervosnetwork/ckb/pull/2503) by [@yangby-cryptape](https://github.com/yangby-cryptape)
- PR: [Integrate dynamic loading functions from C library](https://github.com/nervosnetwork/ckb-std/pull/12) by [@XuJiandong](https://github.com/XuJiandong)

#### [Parity](https://github.com/paritytech)

263 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
138 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
88 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Migration testing runtime API/Bot](https://github.com/paritytech/substrate/pull/8038) by [@kianenigma](https://github.com/kianenigma)
- PR: [Decouple Staking and Election - Part 2 Unsigned Phase](https://github.com/paritytech/substrate/pull/7909) by [@kianenigma](https://github.com/kianenigma)
- PR: [contracts: Charge rent for code storage](https://github.com/paritytech/substrate/pull/7935) by [@athei](https://github.com/athei)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

6 merged PRs ([1][secret_network-merged-prs-1]), 29 closed issues ([1][secret_network-closed_issues-1]), 
4 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- News:
  - [Announcing the Secret Binance Smart Chain Bridge!](https://scrt.network/blog/announcing-secret-binance-smart-chain-bridge)
  - [SecretSwap is LIVE on Mainnet!](https://scrt.network/blog/secretswap-is-live-on-mainnet)
  - [Announcing the Secret Network Grant Program](https://scrt.network/blog/announcing-secret-network-grant-program)
- PR: [fix typo in app.go](https://github.com/enigmampc/SecretNetwork/pull/728) by [@vitocchi](https://github.com/vitocchi)
- PR: [added support for debug-print in secret contracts.](https://github.com/enigmampc/SecretNetwork/pull/717) by [@reuvenpo](https://github.com/reuvenpo)

#### [Solana](https://github.com/solana-labs/solana)

350 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
21 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
50 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Add limit and shrink policy for recycler](https://github.com/solana-labs/solana/pull/15320) by [@carllin](https://github.com/carllin)
- PR: [Various postponed fixes and changes to the stake pool program](https://github.com/solana-labs/solana-program-library/pull/1200) by [@atticlab](https://github.com/atticlab)
- PR: [Warn lastValidSlot with some terminology tweaks](https://github.com/solana-labs/solana/pull/15081) by [@ryoqun](https://github.com/ryoqun)

#### [Zcash](https://z.cash/)

128 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
55 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
47 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- News:
  - [New Release 4.3.0](https://electriccoin.co/blog/new-release-4-3-0/)
  - [Network Upgrade Pipeline 2.0](https://electriccoin.co/blog/network-upgrade-pipeline-2-0/)
- PR: [Refactor `connection.rs` to make `fail_with` errors impossible](https://github.com/ZcashFoundation/zebra/pull/1721) by [@yaahc](https://github.com/yaahc)
- PR: [Multi-proof prover](https://github.com/zcash/halo2/pull/143) by [@therealyingtong](https://github.com/therealyingtong)
- PR: [Hash verification key into transcript](https://github.com/zcash/halo2/pull/173) by [@therealyingtong](https://github.com/therealyingtong)

&nbsp;

## Events

Mar 15 - Apr 11 | Online

[Chainlink Hackathon Spring 2021](https://chain.link/hackathon)

May 20 | Online

[Polkadot Decoded](https://decoded.polkadot.network/).
[Submit your proposal](https://decoded.polkadot.network/2021submission) by February 28th. 

&nbsp;

## Careers

Aleo | San Francisco, USA or Remote
- [Senior Protocol Engineer](https://aleo.org/jobs/senior-protocol-engineer)
- [Senior Compiler Engineer](https://aleo.org/jobs/senior-compiler-engineer)
- [Full-Stack Developer](https://aleo.org/jobs/full-stack-developer)
- [Interface Designer](https://aleo.org/jobs/interface-designer)

Kraken | Remote
- [Backend Engineer - Crypto Payments](https://jobs.lever.co/kraken/39031c44-2060-467d-8991-79f23deacbb8)
- [Backend Engineer - Fiat Payments](https://jobs.lever.co/kraken/bd3d0185-eb56-441e-8ceb-5757711dae8c)
- [Backend Engineer - Staking & DeFi](https://jobs.lever.co/kraken/37dbb8c2-b60c-42bd-a98f-0a3fc8657381)
- [Software Engineer - Trading Technology (Rust)](https://jobs.lever.co/kraken/4485f672-dc5f-4e49-a10b-2b0399e28a8d)
- [Backend Engineer - Rust - Core Backend](https://jobs.lever.co/kraken/4019a818-4a7b-46ef-9225-c53c7a7f238c)
- [Backend Engineer, Kraken Futures - Rust](https://jobs.lever.co/kraken/fe1e07f4-6d7c-4f65-9a8f-27cf3b3fd2b1)
- [Banking Engineer - Rust](https://jobs.lever.co/kraken/2863623f-13c9-4f50-992d-7c25736a60f9)
- [Site Reliability Engineer - Rust - Core Backend](https://jobs.lever.co/kraken/1c6b290f-e430-430d-9b40-a258d07686b0)
- [Rust QA Software Engineer](https://jobs.lever.co/kraken/d2c89216-6a99-4351-84ba-95bc9000a767)
- [Rust API SDET](https://jobs.lever.co/kraken/5ec9958a-529c-4bae-89b3-0d1a104cbd81)

Matter Labs | Berlin/Kiev or Remote
- [Junior Software Engineer](https://www.notion.so/Junior-Software-Engineer-2d062b60daf941f792ebac1958244f52)
- [Senior Software Engineer](https://www.notion.so/Senior-Software-Engineer-162f87f441214eb39619f83bdd9b3073)
- [Protocol Security Engineer](https://www.notion.so/Protocol-Security-Engineer-Blockchain-444a7d5f558c412da70c3300815a620a)
- [Tech Team Lead (Rust)](https://www.notion.so/Tech-Team-Lead-Rust-e336a6285c60426f9f95700b2da1beac)

Nucypher | Remote
- [Rust Software Engineer](https://news.ycombinator.com/item?id=26049890)

Parity Technologies | Berlin or Remote 
- [Blockchain Node Developer](https://grnh.se/a070a3c83us)
- [Rust Performance Engineer](https://grnh.se/122d55873us)
- [Core Developer - Runtime](https://grnh.se/87f802f93us)
- [Solution Engineer](https://grnh.se/d7fe278f3us)
- [Rust Developer - Tools](https://grnh.se/e1cc2c0c3us)
- [P2P Network Engineer](https://grnh.se/4e54162d3us)
- [Rust/Core Developer](https://grnh.se/0efc64513us)

Zcash | Remote
- [Core Engineer](https://www.zfnd.org/blog/opening-core-engineer/)
- [Cryptography Engineer](https://www.zfnd.org/blog/open-position-cryptography-engineer/)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#22 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


