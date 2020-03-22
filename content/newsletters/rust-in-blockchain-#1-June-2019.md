---
title: "Rust in Blockchain Newsletter #1"
description: "#1 - June 2019"
date: 2019-07-04
slug: "/2019-07-04"
type: single
categories:
  - "newsletters"
---

Welcome to the second edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies. [Previous #0](/newsletters/2019-06-06).

Rust in Blockchain starts a series of offline events in San Francisco, Berlin, and Hangzhou, the #0 meetup will be held in San Francisco on 17th July. If you are interested in speaking at our events, please apply [here](https://docs.google.com/forms/d/e/1FAIpQLSdqDDPv6WylWCel8j5oorm3U5M1wtQJ7gYLsw_Ng6IcDcDSBg/viewform). We will be super happy to receive your contributions.

Libra might be the hypest news in June, follows with non-stoping blog posts. Discussions on [Facebook just picked Rust to implement their new Libre blockchain](https://www.reddit.com/r/rust/comments/c20aed/facebook_just_picked_rust_to_implement_their_new/). Engineers care more about Move programming language, and crypto world discussed more on its business and the future. What’s your opinion?

&nbsp;

## New Adoption

[Zebra](https://github.com/ZcashFoundation/zebra), a consensus-compatible Zcash node client written in Rust.

[Libra](https://github.com/libra/libra) Core implements a decentralized, programmable database which provides a financial infrastructure that can empower billions of people.

Blockchain-based [Brave](https://news.ycombinator.com/item?id=20289966) browser announced they see the value add of rust and are already using it.

&nbsp;

## Project updates

#### [**Grin**](https://github.com/mimblewimble/grin)

[MMR Storage Optimization](https://github.com/mimblewimble/grin/issues/2873) The internal MMR implementation that would reduce the storage requirements significantly.

[Grin Newsletter](https://grinnews.substack.com/)


#### [**Nervos**](https://github.com/nervosnetwork)

[CKB](https://github.com/nervosnetwork/ckb)

[Feat: proposer reward](https://github.com/nervosnetwork/ckb/pull/922) Consensus updates: earliest transaction proposer will recieve 40% of the transaction fee as a reward; block reward finalized after proposal window close; enforce one-input one-output one-witness on cellbase.

[Feat: use recoverable signature to reduce tx size](https://github.com/nervosnetwork/ckb-system-scripts/pull/15) It replaces normal signature with recoverable signature. Instead of reading pubkey from witness, the contract recovers a pubkey from the signature, this change can reduce 33 bytes tx size for each witness.

[CKB-VM](https://github.com/nervosnetwork/ckb-vm)

[Add new AOT mode to replace experimental JIT mode](https://github.com/nervosnetwork/ckb-vm/pull/72). The benchmark shows that a secp256k1 operation can finish in the new AOT mode in under 1 ms, while the current assembly interpreter needs 5 ms at best, which results to the same order of magnitude of native code.

A full RISC-V test suite has been integrated into CKB-VM, each change will be validated against the comprehensive test suites.

[CKB Development Updates](https://medium.com/nervosnetwork/tagged/development-updates)


#### [**NEAR**](https://github.com/nearprotocol/nearcore)

[Add self call (for advanced access keys)](https://github.com/nearprotocol/nearcore/pull/1005) Self call is used when the account calls its own contract. In this case, no receipts needed, since all information is available immediately. It can be used by access keys pointed at the owner’s account to proxy transactions further.


#### [**Parity** ](https://github.com/paritytech)

**[Substrate](https://github.com/paritytech/substrate)**

[How to upgrade the earlier substrate version to new version](https://github.com/paritytech/substrate/issues/2861) [@satyamakgec](https://github.com/satyamakgec) has 7 – 8 SRML modules in the existing chain so he doesn’t want any discrepancies on the code. What is the best way to do upgrade substrate?

[Missing block timestamp in the block details](https://github.com/paritytech/substrate/issues/2811) [@satyamakgec](https://github.com/satyamakgec) was trying to access the event data and the timestamp at which events get emitted.

**[Polkadot](https://github.com/paritytech/polkadot)**

[Question about the Collator](https://github.com/paritytech/polkadot/issues/296) [@XiangyueMeng](https://github.com/XiangyueMeng) starts a conversation with the question on the Collator’s mechanism.


#### [**Solana**](https://github.com/solana-labs/solana)

[Lack of determinism in programs](https://github.com/solana-labs/solana/issues/4802) The BPF loader does not enforce determinism in the programs/instructions they support. Proposed Solution: find a way to ensure determinism in the programs.

[Bench TPS performance is lacking with real PoH](https://github.com/solana-labs/solana/issues/4722) The bench TPS client does not perform well when real PoH is turned on (hashes per tick is set to auto).


&nbsp;

## Challenges

[Project needs sweet zebra logo](https://github.com/ZcashFoundation/zebra/pull/2) 😉

[][RFC] CKB Consensus Protocol](https://github.com/nervosnetwork/rfcs/pull/124) [@Ren](https://github.com/nirenzang) submitted the consensus protocol and is calling for comments.
Bitcoin’s Nakamoto Consensus (NC) is well-received due to its simplicity and low communication overhead. The CKB consensus protocol is a variant of NC that raises its performance limit and selfish mining resistance while keeping its merits. By identifying and eliminating the bottleneck in NC’s block propagation latency, our protocol supports very short block interval without sacrificing security. The shortened block interval not only raises the throughput, but also lowers the transaction confirmation latency. By incorporating all valid blocks in the difficulty adjustment, selfish mining is no longer profitable in this protocol.


&nbsp;

## Learning

[People of Parity: Wei Tang](https://www.parity.io/people-of-parity-wei-tang/) Wei is the author of [EIP-1283](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1283.md), he wrote SputnikVM, an EVM implementation in Rust. Wei shares his programming experience from working in Parity.

[Rust Creator Graydon Hoare Talks About Security, History, and Rust](https://thenewstack.io/rust-creator-graydon-hoare-talks-about-security-history-and-rust)

[Lessons Learned from Bitcoin’s and Ethereum’s Programming Models](https://hackernoon.com/lessons-learned-from-bitcoins-and-ethereum-s-programming-models-f9fdbe1a3fdb) – Zhang Yaning

[Video] [Build Your Own Blockchain with Substrate and Rust](https://www.youtube.com/watch?v=bjWxwTA2KLw) – Bill Laboon
[Video] [What Is Web3?](https://avc.com/2019/06/video-of-the-week-what-is-web3/) [@Juan Benet](https://twitter.com/juanbenet), founder and CEO of our portfolio company [Protocol Labs](https://protocol.ai/), developer of the [IPFS](https://ipfs.io/) and [Filecoin](http://filecoin.io/) protocols, gave this talk last fall.


&nbsp;

## Events

July 17 | San Francisco

[In Rust We Trust– Rust in Blockchain meetup SF Edition](https://www.meetup.com/Rust-in-Blockchain-San-Francisco/events/262773260/)

July 19-21 | Los Angeles

[State of Scale – Ethereum scalability, hackathon, and workshop](https://www.stateofscale.com/)

July 19-21 | Brooklyn

[ConsenSys Grants hackathon](https://pages.consensys.net/consensys-grants-hackathon-new-york)

Aug 2-4 | Bangalore, India

[ETHIndia – Asia’s biggest Ethereum Hackathon](https://ethindia.co/)


## Careers

IOTA

[Senior Software Engineer (Rust)](https://iota.bamboohr.com/jobs/view.php?id=90)

Spacemesh

[Blockchain Developer: Come and build with us the Spacemesh p2p full node in Rust](https://blockchain.works-hub.com/jobs/blockchain-developer-e97)

FRG Technology Consulting

[Blockchain Developer / Rust / Solidity](https://www.goforcrypto.com/blockchain-developer-rust-solidity/)

Facebook

[Operating Systems Engineer](https://www.facebook.com/careers/jobs/679142629195287/)

Parity

[Blockchain Runtime Engineers](https://www.parity.io/jobs/#berlin-blockchain-runtime-engineer)

Crypto Bobby introduces his new plan [Proof of Talent](https://medium.com/@crypto_bobby/proofoftalent-d624d3a87e78).


&nbsp;

## Interesting things

[Thread: the value proposition of crypto assets](https://twitter.com/panekkkk/status/1142891604950339585)

This thread is my attempt to explain the value proposition of crypto assets (“crypto”) like bitcoin ($BTC) and ethereum ($ETH) to newcomers like you.

[Is Rust My Best Option?](https://www.reddit.com/r/rust/comments/c27fng/is_rust_my_best_option/)

Kally95 wants to become a blockchain developer in the future, he calls for advice on reddit and got valuable comments, which are worth reading.



**Join the action on our** [**subreddit**](https://www.reddit.com/r/RustInBlockchain/) **❤️**
