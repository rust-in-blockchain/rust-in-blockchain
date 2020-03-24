---
title: "Rust in Blockchain Newsletter #2"
description: "#2 - July 2019"
date: 2019-08-01
slug: "/2019-08-01"
categories:
  - "newsletters"
summary: The first Rust in Blockchain meetup In Rust We Trust went very well on the 17th July in San Francisco. Thanks to all the speakers and the participants! If you want to speak on one of our forthcoming meetups, please apply here.
---

Welcome to the third edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies.  [Previous #1](/newsletters/2019-07-04).

The first Rust in Blockchain meetup [In Rust We Trust](https://www.meetup.com/Rust-in-Blockchain-San-Francisco/events/262773260) went very well on the 17th July in San Francisco. Thanks to all the speakers and the participants! If you want to speak on one of our forthcoming meetups, please apply [here](https://docs.google.com/forms/d/e/1FAIpQLSdqDDPv6WylWCel8j5oorm3U5M1wtQJ7gYLsw_Ng6IcDcDSBg/viewform).


&nbsp;

## Project updates

#### [**Grin**](https://github.com/mimblewimble/grin)

[Moving wallet from one node to another loses some UTXOs #2901](https://github.com/mimblewimble/grin/issues/2901)

[Grin Newsletter](https://grinnews.substack.com/)

#### [**Near**](https://github.com/nearprotocol/nearcore)

[Account deletion #1107](https://github.com/nearprotocol/nearcore/pull/1107) @ilblackdragon: If account has less balance to support it for given number of blocks, anyone can initiate its deletion and receive reward for it.

#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)

[CKB run requires block assembler code hash must be one of the system cells #1045](https://github.com/nervosnetwork/ckb/issues/1045) If block assembler is set, it must be one of the system cells, unless command option --allow-any-ba-code-hash is given.

[Feat: Send a message to remote peer when disconnect #1246](https://github.com/nervosnetwork/ckb/pull/1246) @TheWaWaR Add a new p2p protocol StringMessageProtocol for sending simple string message; Send a message to a remote peer when disconnect.

[CKB Development Updates](https://medium.com/nervosnetwork/tagged/development-updates)

#### [**Oasis**](https://github.com/oasislabs)

[Hello World! example #142](https://github.com/oasislabs/oasis-rs/pull/142)

[Generate clients for services using imported interface definition #141](https://github.com/oasislabs/oasis-rs/pull/141)

#### [**Parity** ](https://github.com/paritytech)

[**Substrate**](https://github.com/paritytech/substrate)

[How to spawn a task in a task #2991](https://github.com/paritytech/substrate/issues/2991)

[Enable Offchain API to handle local storage race conditions better #3143](https://github.com/paritytech/substrate/issues/3143)

#### [**Solana**](https://github.com/solana-labs/solana)

[Unnecessary protobuf requirement in Libra #5251](https://github.com/solana-labs/solana/issues/5251) @garious found the problem that the libra codebase uses Google protobuf to send data to its metrics server. They stuffed Golang and protobuf into our Docker containers to move forward, but neither is actually used. Furthermore, those dependencies aren't on our benchmarking servers and not on developer machines. Until they get those dependencies out, they can't integrate Move into our top-level build.


&nbsp;

## Challenges

[Substrate][Websocket protocol errors cause full node halt/stall/crash #3124](https://github.com/paritytech/substrate/issues/3124)

&nbsp;


## Learning

VM on Blockchain

[RISC-V based CKB VM: Validation Model](https://xuejie.space/2019_07_05_introduction_to_ckb_script_programming_validation_model)

[RISC-V based CKB VM: Script Basics](https://xuejie.space/2019_07_13_introduction_to_ckb_script_programming_script_basics)

[Wasm for Blockchain 2019](https://medium.com/nearprotocol/wasm-for-blockchain-2019-d093bfeb6133)

[Video] [Pierre Krieger from Parity discuss Libp2p library with Maksym Zavershynskyi from Near](https://www.youtube.com/watch?v=_9o6RTYG_xk&t=678s)

[Video] [Decentralized App Development](https://www.youtube.com/watch?v=e_QOMBZS5gs&list=PL9tzQn_TEuFWbiHCvul76ZyiG6C_0180f)

[Video] [Cell Model - A programming model that generalizes Bitcoin's UTXO model](https://www.youtube.com/watch?v=EBoTUw4MI0k)

[Video] [In Rust We Trust Meetup 17th July, San Francisco](https://www.youtube.com/watch?v=02oVI_2zDcI&list=PLRke1-EE4VWGLXPbcpxn8fPmXlvRuZGIw)
- Rust is for Blockchain - Brian Anderson
- Towards a True Programmable Blockchain World: An Introduction to CKB VM - Xiao Xuejie
- Rust Smart Contract APIs - Maksym Zavershynskyi
- Tendermint Key Management System and Abscissa Application Framework - Tony Arcieri


&nbsp;

## Events

August 7 | Sydney, Australia

[Holochain vs. Ethereum + Latest on Blockchain & Securities](https://www.meetup.com/Sydney-Blockchain-Professionals/events/263088441)

August 19 | Berlin, Germany

[Rust for Decentralised Technology](https://www.meetup.com/Rust-Berlin/events/263390533)

August 19-21 | Berlin, Germany

[Web3 Summit 2019](https://web3summit.com/)

August 21 | Berlin, Germany

[In Rust We Trust - VM on Blockchain](https://www.meetup.com/Rust-in-Blockchain-Berlin/events/263526816)

August 21-23 | Berlin, Germany

[DappCon 2019](https://dappcon.io)

August 22-23 | Portland, US

[RustConf 2019](https://rustconf.com)

August 23-25 | Berlin, Germany

[EthBerlin 2019](https://ethberlinzwei.com)


Online Hackathons

[Blockstack: Build a Blockstack application that fits into one of the featured categories](https://blockstack-evil2.devpost.com/)

[Tezos: Bringing Decentralized Applications To The Masses](https://ideotezos.splashthat.com)

[IDEO + CoinList Hackathon: Making Blockchains Useful and Usable](https://coinlist.co/build/ideo)


&nbsp;

## Careers

Bitski

[Backend Engineer](https://angel.co/company/bitski/jobs/366874-backend-engineer)

Parity

[Blockchain Runtime Engineer](https://www.parity.io/jobs/#berlin-blockchain-runtime-engineer)

Near

[Full Stack Application Developer](https://boards.greenhouse.io/near/jobs/4290530002)

[Network Software Engineer](https://boards.greenhouse.io/near/jobs/4205573002)

Nervos

[Senior Blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

[Senior Test Manager](https://angel.co/company/nervos-1/jobs/589746-senior-test-manager)


&nbsp;

## Interesting Things

This is a call to those Rust and blockchain developers who believe in the power of community, and who want Rust to be the language of choice for blockchain projects.
[Rust & Blockchain Community - Call for Contributors](https://rustinblockchain.org/2019/07/30/call-for-contributors)



**Join the action on our** [**subreddit**](https://www.reddit.com/r/RustInBlockchain/) **❤️**
