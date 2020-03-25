---
title: "Rust in Blockchain Newsletter #0"
description: "#0 - May 2019"
date: 2019-06-06
aliases:
  - /2019/06/06/rust-in-blockchain/
slug: "/2019-06-06"
categories:
  - "newsletters"
summary: Blockchain technology brings together cryptography, mathematics, game theory, and economics to create distributed systems with uniquely powerful security properties. Rust is a high-performance programming language uniquely suited to creating secure distributed systems. Every edition we bring you the latest developer news related to blockchain technology in Rust, with the ambition of building a greater developer community around this family of projects.
---

Welcome to the first edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies.

Blockchain technology brings together cryptography, mathematics, game theory, and economics to create distributed systems with uniquely powerful security properties. Rust is a high-performance programming language uniquely suited to creating secure distributed systems. Every edition we bring you the latest developer news related to blockchain technology in Rust, with the ambition of building a greater developer community around this family of projects. For more about why developers choose Rust for their blockchain projects, read [Why Rust](https://medium.com/layerscrypto/why-rust-c877fba0ca94).

&nbsp;

## Project updates

#### [**Grin**](https://github.com/mimblewimble/grin)

[Byteorder crate does not play nicely with our "non-blocking" IO #2820](https://github.com/mimblewimble/grin/issues/2820) It is entirely possible for a u64 or other multi-byte value here to cause the non-blocking IO to fail on a partial read. So comes the question, Rust IO is kind of janky as they do not get *any* type safety here in terms of blocking/non-blocking behavior.

[Consider adopting a new git branching model #2779](https://github.com/mimblewimble/grin/issues/2779) Having discussed the git branching model, the team finally, decided to stay with the current model, with an action point taken to simplify the documentation for newcomers to understand and follow.

[Db/store full (forked) blocks cleanup #2585](https://github.com/mimblewimble/grin/issues/2585) The key takeaway from this thread, was to compact the blocks db periodically to remove historical full blocks from the db older than one week (which is based on the current chain by traversing back from the head of the chain). It was also stated, that you wouldn't clean forked blocks up and the blocks will remain in the db indefinitely. Please check the thread for more discussion.

#### [**Nervos** ](https://github.com/nervosnetwork/ckb)

#### [**CKB**](https://github.com/nervosnetwork/ckb)

[Cross compile x86_64-unknown-linux-musl #903](https://github.com/nervosnetwork/ckb/issues/903) Rocksdb depends on C++ standard library heavily, which might need a real C++ for musl to work.

Static Build CKB on CentOS 7 for exchanges #626](https://github.com/nervosnetwork/ckb/issues/626) A centos 7 install guide.

[Write a tool to dump well known hashes into a readable file #562](https://github.com/nervosnetwork/ckb/issues/562) D[oitian](https://github.com/doitian) made a tool to dump various hashes into a file and commit that file into the repository.

[Memorize hash #549](https://github.com/nervosnetwork/ckb/issues/549) [Zhangsoledad](https://github.com/zhangsoledad) suggests fetching hashes from the database instead of computing them.

[Feat: Use snappy to compress large messages #859](https://github.com/nervosnetwork/ckb/pull/859) Use snappy to compress large messages ([Driftluo](https://github.com/driftluo)), which saves bandwidth with CPU overhead.

[New verification model #913](https://github.com/nervosnetwork/ckb/pull/913) Verification model changes.

[**CKB-VM**](https://github.com/nervosnetwork/ckb-vm)

[Chore: add an example named is13 #61](https://github.com/nervosnetwork/ckb-vm/pull/61) [Mohanson](https://github.com/mohanson) as a newcomer of CKB-VM contributes an example for easier starting.

[Feat: W^X initial implementation #53](https://github.com/nervosnetwork/ckb-vm/pull/53) [Xxuejie](https://github.com/xxuejie) adds initial [W^X](https://en.wikipedia.org/wiki/W^X) implementation to CKB-VM, which also fixes a memory overflow situation in the assembly based interpreter.

[Feat: shrink VM's memory from 16MB to 4MB #52](https://github.com/nervosnetwork/ckb-vm/pull/52) It reduces the load on requesting zero paged memory, providing enough time to come up with a better solution that doesn't require zero pages. Plus, 4MB is still enough for a lot of use cases.

#### [**Parity** ](https://github.com/paritytech)

#### [**Substrate**](https://github.com/paritytech/substrate)

[How to get an ordered linked_map? #2631](https://github.com/paritytech/substrate/issues/2631) [Liuchengxu](https://github.com/liuchengxu) has a use case of generating a validator set from the top candidates in the staking module. With the election algorithm which is similar to the one before phragmen, they have to sort the candidates based on their total nominations to get the top ones.

[Question: how to import `blake2_512` into runtime for wasm #2605](https://github.com/paritytech/substrate/issues/2605) [Thiolliere](https://github.com/thiolliere) explained for implementing blake2_512 for std and no_std in a similar way to blake2_256, you need to modifie sr-io/with_std, sr-io/without_std and core/executor/src/wasm_executor.

[Smart Contract deployment: Invalid transaction: FullBlock on empty block #2566](https://github.com/paritytech/substrate/issues/2566) The team increased the gas block limit to solve the smart contract deployment issue.

[Document storage key generating algorithm #2443](https://github.com/paritytech/substrate/issues/2443) A breaking change.

[**Polkadot**](https://github.com/paritytech/polkadot)

[Node-specific limit on size of parachain candidates to validate. #148](https://github.com/paritytech/polkadot/issues/148) [Rphmeier](https://github.com/rphmeier) said validate_collation should reject block_data that is too big with an error code indicating that the block data is considered invalid but due to arbitrary reason. Most of which would happen in the validation crate, except for the portion in the CLI.

#### [**Solana**](https://github.com/solana-labs/solana)

[Need better architecture for transaction forwarding #4071](https://github.com/solana-labs/solana/issues/4071) [Pgarg66](https://github.com/pgarg66) found the problem that, the current transaction forwarding logic may not keep up with leader rotation, and in turn cause unnecessary load on the network and Proposed solutions as well.

#### [**Zcash**](https://github.com/zcash/librustzcash)

[Plans for pairing and crates.io? #76](https://github.com/zcash/librustzcash/issues/76) [Afck](https://github.com/afck) said, there are several projects that use pairing and would like to contribute to it. How does Zcash deal with PRs merge?

&nbsp;

## Challenges

[Long chain attacks could disrupt the network #4336](https://github.com/solana-labs/solana/issues/4336) (Source: Solana)

Problem long chain generated with a faster ASIC could lock the node out from the real network. Proposed Solution The proposed block should be near the local generated PoH before a node considers voting for it.

&nbsp;

## Learning

[CKB Testnet First Run](https://gist.github.com/apiraino/76d878104d3b6f649e6a3db8f6510914)

Antonio shares his experience on how to start mining on CKB testnet.

[Why Blockchain is Hard](https://medium.com/@jimmysong/why-blockchain-is-hard-60416ea4c5c)

Blockchain is used way too much as a buzzword to sell a lot of useless snake oil. The faster we get rid of the hype, the better off long-term we’ll all be.

[Lessons Learned from Teaching Over 500 Developers or: Why You Should Level Up](https://medium.com/@jimmysong/lessons-learned-from-teaching-over-500-developers-or-why-you-should-level-up-ad0e48bce067)

To understand Bitcoin deeper through reading/coding/teaching.

[Instead Of Solving The ‘Blockchain Trilemma’, Focus On Building A Vibrant Cryptoeconomy](https://medium.com/@kevinmobrien1/instead-of-solving-the-blockchain-trilemma-focus-on-building-a-vibrant-cryptoeconomy-7064acb41a26)

[Blockchain-flavored WASI](https://medium.com/oasislabs/blockchain-flavored-wasi-50e3612b8eba)

General purpose computation on the blockchain using Web Assembly System Interface (WASI).

[Video] [Understanding Blockchain Programming Languages in 7 Minutes.](https://www.youtube.com/watch?v=HAOeR9Xh--A)

[Video] [Blockchain in Rust series](https://www.youtube.com/watch?v=vJdT05zl6jk&list=PL1rXPCvogp_SsWBI_JpXFypBDhbgXVrSE)

[Audio] [Rust-Bitcoin, Threats to Bitcoin & Bitcoin Data Science](https://anchor.fm/stephan-livera/episodes/SLP73-Tamas-Blummer---Rust-Bitcoin--Threats-to-Bitcoin--Bitcoin-Data-Science-e44dhk)

&nbsp;

## Events

June 6-14 | Online

[The WorkFork Online Hackathon](https://workfork.io/hackathon_dutchblockchainweek)

June 8-9 Breaking Bitcoin, Amsterdam

[Breaking Bitcoin [Training & Hackathon\]](https://breaking-bitcoin.com/)

June 14-16 | San Francisco

[BUIDL San Francisco [Blockchain Hackathon\]](https://www.eventbrite.com/e/buidl-san-francisco-blockchain-hackathon-tickets-56603971001)

June 20 | Zurich Switzerland

[Swiss Blockchain Hackathon](https://hackathon.trustsquare.ch)

June 24th - 26th | Zug, Switzerland

[Crypto Valley Conference](https://www.cryptovalleyconference.com/)

June 28-29 | Firenze FI, Italy

[RustLab](https://www.rustlab.it)

&nbsp;

## Careers

[Report]

[The Blockchain Jobs Report, 2019](https://media.consensys.net/the-blockchain-jobs-report-2019-b2b911426c34)

Cryptape 	

[Senior Rust Developer](https://twitter.com/workfork_hq/status/1133424215087042560?s=12)

Parity 		

[Blockchain Runtime Engineers](https://www.parity.io/jobs/#berlin-blockchain-runtime-engineer)

Target		

[Blockchain Engineer](https://twitter.com/adeebahmed26/status/1133843502465462274)

##Interesting things

[Rust Cryptography Working Group](https://twitter.com/bascule/status/1131266407499309056?s=21)

[Thread: wins, missteps, and next steps at Holochain and Holo.](https://twitter.com/crypto_raiturk/status/1130947989692985344)

&nbsp;

## Acknowledgments

A huge thank you to Mike, [Ash](https://twitter.com/ashchan), [Brian](https://brson.github.io/), [Alexandra](https://twitter.com/a13xndra) and [Ben](https://twitter.com/gnunicornBen) for your contributions and helping bring this newsletter to fruition. We finally made it!

**Join the action on our** [**subreddit**](https://www.reddit.com/r/RustInBlockchain/) **❤️**
