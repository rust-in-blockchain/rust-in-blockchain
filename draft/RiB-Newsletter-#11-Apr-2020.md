
---
title: "RiB Newsletter #11 – "
description: "#11 - April 2020"
date: 2020-05-06
slug: "/2020-05-06-"
categories:
  - "newsletters"
summary:
---

# RiB Newsletter #11 - April 2020

Welcome to the #11 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. <!--[Previous: #10](/newsletters/2020-04-01-keep-calm-and-hack-more). -->

Wow, it was a huge month for blockchain Rust! It seems like we've all been
productive sitting at home hacking. We've seen so many interesting developments,
hopefully captureed them all in this report. Honestly, we were completely
overwhelmed trying to sort through all the content and contributions this month.
It's amazing!

There were significant developments for several Rust blockchain projects:

- NEAR [launched their mainnet][nmn]. Congrats to the NEAR team!
- The [Ethereum 2.0 "Schlesi" multi-client testnet launched][eth2], with the
  Rust [lighthouse][lh] client participating.
- Facebook's Libra resurfaced with a [new roadmap and whitepaper][lbr].
- [MobileCoin], a privacy-focused payment network associated with [Signal],
  open-sourced their Rust codebase. MobileCoin runs the Stellar consensus
  protocol in SGX enclaves, combined with CryptoNote ring signatures.

[lbr]: https://libra.org/en-US/blog/libra-developers-the-path-forward/
[MobileCoin]: https://github.com/mobilecoinofficial/mobilecoin
[Signal]: https://signal.org/
[nmn]: https://near.org/blog/near-mainnet-genesis/
[eth2]: https://github.com/goerli/schlesi/
[lh]: https://github.com/sigp/lighthouse

We learned of new, or new-to-us Rust blockchain and crypto projects:

- [Crypto.com Chain](https://github.com/crypto-com/chain), a new chain
  using Tinderment consensus.
- [BLAKE3](https://github.com/BLAKE3-team/BLAKE3), a new BLAKE-family hash
  function, with a Rust implementation.
- [Distaff](https://github.com/BLAKE3-team/BLAKE3), a STARK VM that runs
  encrypted computations.
- Both IPFS and FileCoin have ongoing Rust implementations: [ipfs-rust]
  and [forest].

[ipfs-rust]: https://github.com/ipfs-rust/rust-ipfs
[forest]: https://github.com/ChainSafe/forest

Virtual conferences have been flourishing. There were at least three online
blockchain conferences, the materials for which should be available:

- [Ready Layer One][rlo]. NEAR, Polkadot, and Solana represented.
- [DeFi Discussions][dfd]. Not Rust-specific, though lots of talks,
  and Enigma is represented.
- [Sub0][sub0]. A Substrate conference.

[rlo]: https://readylayer.one/
[dfd]: https://defi-discussions.dystopialabs.com/
[sub0]: https://www.crowdcast.io/e/sub0-online/

This was also a big month for RiB. Lots of people submitted news and project
updates. Thank you so much! It really improves the quality and breadth of our
project coverage.

We now have automation to collect project stats from GitHub (the "merged PR's"
etc. listed for each project, and that contribute to the "Most Active Projects"
section). This will help us reduce the effort that goes into producing each
newsletter, and as a result we no longer need help collecting those stats (we do
though very much need help choosing important news, blogs, pulls, and issues for
each project).

Since our project coverage has become quite expansive (and frankly
overwhelming), this month we have moved the "Interesting Things" section in
front of "Project Updates". This section contains links about cross-cutting
topics that we hope are of interest to the broadest technical audience. We
expect this section to expand in the future to cover subjects like cryptography,
security, consensus, WASM and other VMs, and crypto-economics, particularly as
related to Rust and the Rust blockchain ecosystem.

Let us know what you think in the [telegram group][tg].

Let's have another great month, Rusty blockchainers.

[tg]: https://t.me/rustinblockchain


&nbsp;


## Thanks

This edition of RiB was produced with contributions from [Anais Urlichs][contributorau], Calvin Lau, [Daniel Karzel][contributordk], [James Waugh][contributorjw], [mfaulk][contributormf], Paulii Good, [SeungMin Lee][contributorsl], [Tony Arcieri][contributorta], [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. If you follow a particular project, or otherwise find information that is beneficial to the Rust & blockchain community, please contribute to the next issue. Either submit a PR to the [#12 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributordk]: https://github.com/da-kami
[contributorsl]: https://github.com/somniumism
[contributorjw]: https://github.com/jlwaugh
[contributormf]: https://github.com/mfaulk
[contributorau]: https://github.com/AnaisUrlichs
[contributorta]: https://github.com/tarcieri
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[`k256`].

This is a pure-Rust implementation of [secp256k1], the elliptic curve used by
Bitcoin and many other blockchain projects. It was one of several cryptography
projects announced this month by Tony Arcieri, a maintainer of the [RustCrypto]
GitHub org, and leader of the Rust [secure code working group][scwg].

In addition to `k256`, RustCrypto also released [`p256`], an implementation of
the [NIST P-256] curve, [`signature`], a crate for generically verifying
cryptographic signatures, and [`ed25519`], an implementation of the [Ed25519]
signature scheme.

See the announcments of [`k256` and `p256`][rca1] and [`signature` and
`ed25519`][rca2] for more links and commentary.

[scwg]: https://www.rust-lang.org/governance/wgs/wg-secure-code
[`p256`]: https://github.com/RustCrypto/elliptic-curves/tree/master/p256
[`k256`]: https://github.com/RustCrypto/elliptic-curves/tree/master/k256
[`signature`]: https://github.com/RustCrypto/traits/tree/master/signature
[`ed25519`]: https://github.com/RustCrypto/signatures/tree/master/ed25519
[NIST P-256]: https://csrc.nist.gov/csrc/media/events/workshop-on-elliptic-curve-cryptography-standards/documents/papers/session6-adalier-mehmet.pdf
[secp256k1]: https://en.bitcoin.it/wiki/Secp256k1
[RustCrypto]: https://github.com/RustCrypto
[rca1]: https://www.reddit.com/r/rust/comments/gbjsr9/ann_rustcrypto_p256_and_k256_v020_pure_rust_nist/
[rca2]: https://www.reddit.com/r/rust/comments/g4w8by/ann_rustcrypto_signature_v10_and_ed25519_v10/
[Ed25519]: https://en.wikipedia.org/wiki/EdDSA#Ed25519


## Interesting Things

- Project: [Introducing Distaff: a STARK-based VM written in Rust](https://ethresear.ch/t/introducing-distaff-a-stark-based-vm-written-in-rust/7318)
- Project: [BLAKE3](https://github.com/BLAKE3-team/BLAKE3). There's another BLAKE hash! Rust
  implementation available.
- Project: [Parity's ink to write smart contracts](https://github.com/paritytech/ink)
- Project: [riemann-rs](https://github.com/summa-tx/riemann-rs). Simple UTXO transactions in Rust.
- Project: [`p256` and `k256` crates](https://www.reddit.com/r/rust/comments/gbjsr9/ann_rustcrypto_p256_and_k256_v020_pure_rust_nist/) and [`signature` and `ed25519`](https://www.reddit.com/r/rust/comments/g4w8by/ann_rustcrypto_signature_v10_and_ed25519_v10/). Rust implementations of the elliptic curves by the RustCrypto org.
- Report: [Analyzing Developers in Cryptocurrency Projects](https://blog.coincodecap.com/analyzing-developers-in-cryptocurrency-projects/)
- Blog: [When Tailwinds Vanish](https://luttig.substack.com/p/when-tailwinds-vanish)
- Blog: [Gitcoun Grants Round 5](https://vitalik.ca/general/2020/04/30/round5.html). Vitalik
  Buterin analyzes efforts to crowd-fund Ethereum projects. Not Rust-related, but interesting
  analysis about sustainable community development.
- Blog: [Crypto Fund II](https://a16z.com/2020/04/30/crypto-fund-ii/). Andreeessen Horowitz
  announced $500-million in available crypto-related funding. Not Rust.

&nbsp;

## Most Active in April

[**Solana**](https://github.com/solana-labs/solana): 513 merged [PRs][solana-merged-prs-1], 67 [closed issues][solana-closed_issues-1], 63 [open issues][solana-open_issues-1]

[**Parity** ](https://github.com/paritytech): 303 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]), 71 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 81 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[**COMIT**](https://comit.network/): 249 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3], [4][comit-merged-prs-4], [5][comit-merged-prs-5]), 97 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3], [4][comit-closed_issues-4]), 42 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2], [3][comit-open_issues-3])

[**NEAR**](https://github.com/nearprotocol/nearcore): 121 merged [PRs][near-merged-prs-1], 90 [closed issues][near-closed_issues-1], 69 [open issues][near-open_issues-1]

&nbsp;


## Project Updates

#### [**CodeChain**](https://github.com/codeChain-io/)

51 merged PRs ([1][codechain-merged-prs-1], [2][codechain-merged-prs-2]), 9 closed issues ([1][codechain-closed-issues-1]), 
6 open issues ([1][codechain-open-issues-1])

[codechain-merged-prs-1]: https://github.com/CodeChain-io/codechain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[codechain-merged-prs-2]: https://github.com/CodeChain-io/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[codechain-closed-issues-1]: https://github.com/CodeChain-io/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[codechain-open-issues-1]: https://github.com/CodeChain-io/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- Video: [Lessons learned from the ICS implementation](https://youtu.be/RseUqfpY-JA)  
    Further information: [Blog](https://medium.com/codechain/foundry-ics-poc-proof-of-concept-implementation-c92a8b4757da), [Source code](https://github.com/CodeChain-io/foundry/tree/ics-poc/core/src/ibc)
- Video: [Adpating BLS signature aggregation to CodeChain Foundry](https://youtu.be/dL-rKQJ3H2o)  
    Further information: [Blog](https://medium.com/codechain/adapting-bls-signature-aggregation-to-codechain-foundry-7767d6656e5b), [Source code](https://github.com/CodeChain-io/foundry/commits/bls-consensus-signature)
- PR: [Implement validator interface call](https://github.com/CodeChain-io/foundry/pull/260) by [@Byeongjee](https://github.com/Byeongjee)
- PR: [Cold events for Informer API](https://github.com/CodeChain-io/foundry/pull/285) by [@MSNTCS](https://github.com/MSNTCS)
- PR: [Event deregister for Informer API](https://github.com/CodeChain-io/foundry/pull/311) by [@MSNTCS](https://github.com/MSNTCS)
- PR: [Implement IPC](https://github.com/CodeChain-io/foundry/pull/305) by [@junha1](https://github.com/junha1)
- PR: [Create transactions to replace the implicit state change](https://github.com/CodeChain-io/foundry/pull/324) by [@sgkim126](https://github.com/sgkim126)

#### [**COMIT**](https://comit.network/)

249 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3], [4][comit-merged-prs-4], [5][comit-merged-prs-5]), 97 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3], [4][comit-closed_issues-4]), 
42 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2], [3][comit-open_issues-3])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[comit-merged-prs-2]: https://github.com/comit-network/comit-js-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[comit-merged-prs-3]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[comit-merged-prs-4]: https://github.com/comit-network/comit.network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[comit-merged-prs-5]: https://github.com/comit-network/a2l-poc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[comit-closed_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[comit-closed_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[comit-closed_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[comit-closed_issues-4]: https://github.com/comit-network/comit.network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[comit-open_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05
[comit-open_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05
[comit-open_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [April dev-update](https://comit.network/blog/2020/05/01/april-dev-update)
- PR: [Ether-Lightning swaps in cnd](https://github.com/comit-network/comit-rs/pull/2426)
- PR: [Integration tests for libp2p network behaviour](https://github.com/comit-network/comit-rs/pull/2479)
- Docu: [New COMIT-app tutorial](https://comit.network/docs/tutorials/write-your-first-comit-app/write-a-comit-app-setup)
- R&D: [A2L proof of concept implementation](https://github.com/comit-network/a2l-poc/)

#### [**Enigma**](https://enigma.co)

20 merged PRs ([1][enigma-merged-prs-1]), 12 closed issues ([1][enigma-closed_issues-1]), 
13 open issues ([1][enigma-open_issues-1])

[enigma-merged-prs-1]: https://github.com/enigmampc/SafeTrace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[enigma-closed_issues-1]: https://github.com/enigmampc/SafeTrace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[enigma-open_issues-1]: https://github.com/enigmampc/SafeTrace/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [April Development Update](https://blog.enigma.co/enigma-development-update-april-2020-f4938a1bee11)
- R&D: [Milestone 2 of 3 ~ CosmWasm in SGX without Encryption](https://forum.enigma.co/t/milestone-2-of-3-cosmwasm-in-sgx-without-encryption/1548)
- Blog: [Secret Zone: Making Privacy One With the Cosmos](https://blog.enigma.co/secret-zone-making-privacy-one-with-the-cosmos-20cd72551f2e)
- Blog: [Developer Tutorial: Writing contracts with Enigma Blockchain](https://forum.enigma.co/t/developer-tutorial-writing-contracts-with-enigma-blockchain/1532)
- Blog: [SafeTrace API Demo](https://forum.enigma.co/t/safetrace-api-demo/1502)
- Documentation: [Enigma Blockchain Contracts Guide](https://github.com/enigmampc/enigma-blockchain-contracts-guide)
- Issue: [Crash on find match #42](https://github.com/enigmampc/SafeTrace/issues/42)

#### [**Golem**](https://golem.network/)

25 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4]), 15 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3]) 6 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/gwasm-runner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[golem-merged-prs-2]: https://github.com/golemfactory/golem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[golem-merged-prs-3]: https://github.com/golemfactory/sp-wasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[golem-merged-prs-4]: https://github.com/golemfactory/golem-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[golem-closed_issues-1]: https://github.com/golemfactory/gwasm-runner/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[golem-closed_issues-2]: https://github.com/golemfactory/golem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[golem-closed_issues-3]: https://github.com/golemfactory/sp-wasm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[golem-open_issues-1]: https://github.com/golemfactory/golem/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [Unraveling Golem’s The Next Milestone, Part I](https://blog.golemproject.net/next-milestone/)
- News: [Clay Golem rises!](https://blog.golemproject.net/clay-golem-rises/)
- Blog: [How To Protect Yourself From Scams](https://blog.golemproject.net/how-to-protect-yourself-from-scams/)
- PR: [fix wasm tasks `restart_subtask` signature](https://github.com/golemfactory/golem/pull/5166) by [@shadeofblue](https://github.com/shadeofblue)
- PR: [Abort build if Rust > 1.38.0 is being used.](https://github.com/golemfactory/sp-wasm/pull/40) by [@marmistrz](https://github.com/marmistrz)

#### [**Holochain**](https://github.com/holochain/)

4 merged PRs ([1][holochain-merged-prs-1]), 1 closed issues ([1][holochain-closed_issues-1]), 
3 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[holochain-closed_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[holochain-open_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [Holochain Dev Pulse 70: Infrastructure Challenges, More HoloFuel Speedups, H-Wiki Goes Public](https://blog.holochain.org/infrastructure-challenges-more-holofuel-speedups-h-wiki-goes-public/)
- News: [Dev Pulse 69: CPU Bottleneck Unblocked for HoloFuel, Libraries and Tools for You](https://blog.holochain.org/cpu-bottleneck-unblocked-for-holofuel-libraries-and-tools-for-you/)
- News: Dev Pulse 68: [Part 1](https://blog.holochain.org/part-1-challenges-endured-and-wisdom-gained-building-and-testing-holofuel), [Part 2](https://blog.holochain.org/a-new-holochain-developer-release)
- Blog: [Holochain & Sustainable Energy: Energy As A Currency](https://blog.holochain.org/energy-as-a-currency-holochain-and-sustainable-energy/)
- Blog: [How to build a GraphQl - Holochain middleware](https://holochain-open-dev.github.io/blog/graphql-holochain/)
- Blog: [H-Wiki: The First Wiki Built on Holochain](https://blog.holochain.org/h-wiki-the-first-open-source-project-built-on-holochain/)
- Blog: [The Holocene Explosion (2.4): Game-Changing Possibilities in a World of Unenclosable Carriers](https://medium.com/holochain/the-holocene-explosion-2-4-game-changing-possibilities-in-a-world-of-unenclosable-carriers-cd8d39a2014c)
- Video: [Holochain RAD Tᴏᴏʟs: Hᴏᴡ ᴛᴏ Usᴇ 𝘩𝘤-𝘩𝘢𝘱𝘱-𝘤𝘳𝘦𝘢𝘵𝘦 ᴄᴏᴍᴍᴀɴᴅ](https://www.youtube.com/watch?v=tdYHT1U9qWA)
- Video: [Holo AMA No. 37 w/ Art Brock, David Atkinson, and Mary Camacho](https://www.youtube.com/watch?v=CozfmiWV3Kg)
- Podcast: [Holochain Deep Dive with Arthur Brock and Eric-Harris-Braun](https://podcast.hackernoon.com/e/holochain-deep-dive-with-arthur-brock-and-eric-haris-braun/)
- PR: [fix Async Zome Calls](https://github.com/holochain/holochain-rust/pull/2179) by [@zippy](https://github.com/zippy)
- PR: [Redux synced Future Wakers](https://github.com/holochain/holochain-rust/pull/2175) by [@lucksus](https://github.com/lucksus)

#### [Libra](https://libra.org)

0 merged PRs, 49 closed issues ([1][libra-closed_issues-1]), 
36 open issues ([1][libra-open_issues-1])

[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- Blog: [Libra developers: The path forward](https://libra.org/en-US/blog/libra-developers-the-path-forward/)
- Blog: [Libra still needs more baking](https://voxeu.org/article/libra-still-needs-more-baking)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

86 merged PRs ([1][lighthouse-merged-prs-1]), 44 closed issues ([1][lighthouse-closed_issues-1]), 
34 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [Lighthouse Update #24](https://lighthouse.sigmaprime.io/update-24.html)
- PR: [Use checked arithmetic in types and state proc](https://github.com/sigp/lighthouse/pull/1009) by [@michaelsproul](https://github.com/michaelsproul)
- PR: [Added purge subcommand to purge beacon chain db](https://github.com/sigp/lighthouse/pull/971) by [@ethDreamer](https://github.com/ethDreamer)
- PR: [Arbitrary trait for eth2/types](https://github.com/sigp/lighthouse/pull/1040) by [@kirk-baird](https://github.com/kirk-baird)

#### [**NEAR**](https://github.com/nearprotocol/nearcore)

121 merged PRs ([1][near-merged-prs-1]), 90 closed issues ([1][near-closed_issues-1]), 
69 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[near-closed_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[near-open_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [The Road to MainNet and Beyond](https://near.org/blog/mainnet-roadmap/)
- News: [Announcing NEAR Protocol’s MainNet Genesis](https://near.org/blog/near-mainnet-genesis/)
- News: [NEAR Community Update: April 24th, 2020](https://near.org/blog/community-update-april-24th-2020/)
- Blog: [A Deep Dive into Private Transactions on NEAR](https://near.org/blog/private-transactions-on-near/)
- Blog: [Introduction to NEAR Protocol’s Economics](https://near.org/blog/near-protocol-economics/)
- Video: [Monetizing through Membership with Jᵾlien Genestoux (Founder, CEO at Unlock Protocol)](https://www.youtube.com/watch?v=LoHKluLQCNM)
- Video: [DeFi Primitives with Anton Bukov from 1inch.exchange](https://www.youtube.com/watch?v=KWD0N-xWxXs)
- Video: [Whiteboard Series with NEAR | Ep: 34 Hans Moog from IOTA Foundation](https://www.youtube.com/watch?v=_c-4fQSlUW4)
- Video: [Whiteboard Series with NEAR | Ep: 33 Alex from NEAR hosted by Justin Drake from Ethereum Foundation](https://www.youtube.com/watch?v=8xpOUqdoyp0)
- PR: [feat: MainNet genesis config](https://github.com/nearprotocol/nearcore/pull/2453) by [@ilblackdragon](https://github.com/ilblackdragon)
- PR: [fix(rpc): better error handling for transaction submission](https://github.com/nearprotocol/nearcore/pull/2525) by [@bowenwang1996](https://github.com/bowenwang1996)
- PR: [fix(network): Avoid peers connecting to itself.](https://github.com/nearprotocol/nearcore/pull/2603) by [@mfornet](https://github.com/mfornet)

#### [**Nervos**](https://github.com/nervosnetwork)

38 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2]), 10 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
2 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[nervos-merged-prs-2]: https://github.com/nervosnetwork/rfcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[nervos-closed_issues-2]: https://github.com/nervosnetwork/rfcs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [Introducing CKLabs — The Nervos Incubator](https://medium.com/nervosnetwork/introducing-cklabs-the-nervos-incubator-3e5a2c443c7c)
- News: Nervos CKB Development Update [#33](https://medium.com/nervosnetwork/nervos-ckb-development-update-33-60863398563e), [#32](https://medium.com/nervosnetwork/nervos-ckb-development-update-32-bc3c282f9202)
- News: [ABC Wallet and GrowFi Join the Nervos Ecosystem](https://medium.com/nervosnetwork/abc-wallet-and-growfi-join-the-nervos-ecosystem-2613044cd83f)
- Blog: [Grant Project - ckb.pw & pw-sdk](https://medium.com/nervosnetwork/ckb-pw-pw-sdk-e60c43037305)
- Blog: [Understanding the CKByte Token Issuance Schedule](https://medium.com/nervosnetwork/understanding-the-ckbyte-token-issuance-schedule-e5bd36ba950d)
- CKB Weekly [#1: Keep Calm and Nervos Dao](https://ckbweekly.substack.com/p/1-keep-calm-and-nervos-dao), [#0: #0: 165 days, Hashrate 100X](https://ckbweekly.substack.com/p/0-165-days-hashrate-100x)
- PR: [feat: Optimize block download tasks with a simple task scheduler](https://github.com/nervosnetwork/ckb/pull/1999) by [@driftluo](https://github.com/driftluo)
- PR: [refactor: Simplify network protocols](https://github.com/nervosnetwork/ckb/pull/1968) by [@TheWaWaR](https://github.com/TheWaWaR)

#### [**Parity** ](https://github.com/paritytech)

303 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]), 71 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 
81 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[parity-merged-prs-3]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [Polkadot Launch Announcement: COVID-19 Considerations](https://polkadot.network/polkadot-launch-announcement-covid-19-considerations/)
- News: [Chorus One to Bridge Polkadot and Cosmos Ecosystems](https://polkadot.network/chorus-one-receives-web3-foundation-grant-to-bridge-polkadot-and-cosmos-ecosystems/)
- Blog: [Kusama & Polkadot: Comparing the Cousins](https://polkadot.network/kusama-polkadot-comparing-the-cousins/)
- Blog: [Social recovery on Substrate](https://www.parity.io/social-recovery-on-substrate/)
- Blog: [Built on Substrate: Centrifuge Chain](https://www.parity.io/built-on-substrate-centrifuge-chain/)
- PR: [Batch signature verification](https://github.com/paritytech/substrate/pull/5023) by [@NikVolf](https://github.com/NikVolf)
- PR: [Offchain signing](https://github.com/paritytech/substrate/pull/5182) by [@rakanalh](https://github.com/rakanalh)

#### [**Solana**](https://github.com/solana-labs/solana)

513 merged PRs ([1][solana-merged-prs-1]), 67 closed issues ([1][solana-closed_issues-1]), 
63 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [Solana Announces a Partnership With dfuse to Collaborate on a Powerful Data Solution for Its High-Throughput Blockchain](https://medium.com/solana-labs/solana-announces-a-partnership-with-dfuse-to-collaborate-on-a-powerful-data-solution-for-its-96bfcb432525)
- News: [Solana Will Reduce Its Token Supply to Account for Market Making Allocation](https://medium.com/solana-labs/solana-will-reduce-its-token-supply-to-account-for-market-making-allocation-b8366288acef)
- News: [Torus is Collaborating with Solana to Build Scalable Mainstream Applications](https://medium.com/solana-labs/torus-is-collaborating-with-solana-to-build-scalable-mainstream-applications-e348abc3828c)
- News: [Solana Partners with Terra to Build a Low-Latency Token Bridge, Bringing Stablecoins To The Solana Ecosystem](https://medium.com/solana-labs/solana-partners-with-terra-to-build-a-low-latency-token-bridge-bringing-stablecoins-to-the-solana-180d76b22a22)
- Podcast: [Zaki Manian - Co-founder of iqlusion Ep #20](https://podcast.solana.com/episodes/zaki-manian-co-founder-of-iqlusion-ep-20)
- Podcast: [Viktor Radchenko - Founder of Trust Wallet Ep #19](https://podcast.solana.com/episodes/viktor-radchenko-founder-of-trust-wallet-ep-19)
- PR: [Add Cross-program invocations](https://github.com/solana-labs/solana/pull/9582) by [@jackcmay](https://github.com/jackcmay)
- PR: [Input values are not sanitized after they are deserialized, making it far too easy for Leo to earn SOL](https://github.com/solana-labs/solana/pull/9706) by [@aeyakovenko](https://github.com/aeyakovenko)
- PR: [Proposal for deterministic program generated Pubkey's that can be used only by programs to create signatures in process_instruction.](https://github.com/solana-labs/solana/pull/8155) by [@aeyakovenko](https://github.com/aeyakovenko)

#### [**Zcash**](https://z.cash/)

32 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 27 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
5 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-04-01..2020-05-05
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[zcash-closed_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-04-01..2020-05-05
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05
[zcash-open_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aopen+created%3A2020-04-01..2020-05-05

- News: [Privacy-Preserving Contact Tracing with the TCN Coalition](https://www.zfnd.org/blog/tcn-coalition/)
- News: [The state of Zcash adoption](https://electriccoin.co/blog/the-state-of-zcash-adoption/)
- News: Zcash Developers Update [04-24](https://www.zcashcommunity.com/2020/04/24/zcash-developers-update-4-24-2020/), [04-10](https://www.zcashcommunity.com/2020/04/10/zcash-developers-update-4-10-2020/), [04-03](https://www.zcashcommunity.com/2020/04/03/zcash-developers-update-4-3-2020/)
- Blog: [Privacy Infrastructure for the Public Good](https://www.zfnd.org/blog/privacy-infrastructure-public-good/)
- Blog: [The Zcash Foundation's 2020 Q1 Report](https://www.zfnd.org/blog/q1-report-2020/)
- Blog: [Next Steps for the Major Grant Review Committee](https://www.zfnd.org/blog/major-grants-review-committee-selection-process/)
- Blog: [Assessing Mixnet Production-Readiness](https://www.zfnd.org/blog/mixnet-production-readiness/)
- Blog: [Building on Zcash: Resources and initiatives](https://electriccoin.co/blog/building-on-zcash-resources-and-initiatives/)
- PR: [Sapling keys and addresses](https://github.com/ZcashFoundation/zebra/pull/327) by [@dconnolly](https://github.com/dconnolly)
- PR: [[ZIPs 207, 214, 251] Consensus ZIPs for Zcash Development Fund](https://github.com/zcash/zips/pull/332) by [@daira](https://github.com/daira)
- PR: [Implement minimal version handshaking ](https://github.com/ZcashFoundation/zebra/pull/295) by [@gtank](https://github.com/gtank)

&nbsp;

## Events

May 6-13 | Online

[NEAR online hackathon running](https://gitcoin.co/hackathon/rl1?tab=hackathon:23)

May 29-Jun 16 | Online

[SOS Hackathon](https://soshackathon.com/)

Jun 17 | Barcelona, EU

[EthBarcelona](http://ethbarcelona.io/)

Aug 3-6, 2020 | Oxford, UK

[IEEE DAPPS 2020](https://ieeedapps.net/)

Oct 21-23 | NYC, US

[ACM Advances in Financial Technologies](https://aft.acm.org/)



&nbsp;

## Careers

Chainlink | Remote, US

[Developer Evangelist](https://careers.chain.link/o/developer-evangelist-global)

Definity | SF, US

[Software Engineer, SDK](https://boards.greenhouse.io/dfinity/jobs/4286745002)

[Senior Software Engineer - Infrastructure and Tools](https://boards.greenhouse.io/dfinity/jobs/4473085002)

Findora | CA, US

[Systems Engineer](https://jobs.lever.co/findora/88501a0d-a86d-4cd2-b0b7-8625a107b02b)

Kraken | London, UK; Remote

[Backend Engineer, Kraken Futures](https://jobs.lever.co/kraken/fe1e07f4-6d7c-4f65-9a8f-27cf3b3fd2b1)

[Backend Engineer, Data Processing](https://jobs.lever.co/kraken/246f7fd2-000a-4f61-8f53-b1cc783d51cb)

Nervos | Remote

[Developer Relations](https://angel.co/company/nervos-1/jobs/710826-developer-relations)

Ockam | Remote

[Software Architect - Applied Cryptography in Rust](https://www.ockam.io/team/Software-Architect-Applied-Cryptography-in-Rust/61e07e82-0589-51de-b250-42dbceb31c3c)

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#12 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
