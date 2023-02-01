---
title: "RiB Newsletter #44"
description: "January 2023"
date: 2023-02-01
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #44 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #43](/newsletters/rib-newsletter-43/).

&nbsp;

## Thanks

Thanks to contributors:
[gcharang],
[Kadan Stadelmann],
[Vid Kersic],
_TODO_
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).


[gcharang]: https://github.com/gcharang
[Kadan Stadelmann]: https://github.com/ca333
[Vid Kersic]: https://github.com/Vid201
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News


#### Blog Posts

- [Consensus canon](https://a16zcrypto.com/consensus-canon/)
- [Generating secure randomness on Ethereum using SNARKs](https://www.paradigm.xyz/2023/01/eth-rng)

#### Papers

- [The Tip5 Hash Function for Recursive STARKs](https://eprint.iacr.org/2023/107)

#### Projects

- [AES Encryption circuit](https://github.com/lambdaclass/AES_zero_knowledge_proof_circuit).
  ZK-Snark circuit to prove that a given ciphertext is the correct AES-128 encryption using a certain secret key.
- [TFHE-rs](https://github.com/zama-ai/tfhe-rs).
  A pure Rust implementation of TFHE for boolean and small integer arithmetics over encrypted data.
- [aa-bundler](https://github.com/Vid201/aa-bundler).
  EIP-4337 (Account Abstraction) - Bundler implementation in Rust.
- [merkle_patricia_tree](https://github.com/lambdaclass/merkle_patricia_tree).
  Patricia Merkle Tree implementation in Rust.
- [heimdall-rs](https://github.com/Jon-Becker/heimdall-rs).
  An advanced EVM toolkit which aims to make dealing with smart contracts on EVM based chains easier.
- [cosmwasm-vm](https://github.com/ComposableFi/cosmwasm-vm).
  Experimental, minimalistic, no_std friendly abstract virtual machine for CosmWasm contracts execution.
  Blog post: [How we built a generalized CosmWasm VM](https://medium.com/composable-finance/how-we-built-a-generalized-cosmwasm-vm-a0ac70fa8219).
- [zk-benchmarking](https://github.com/delendum-xyz/zk-benchmarking).
  A suite of benchmarks designed to compare different zero-knowledge proof libraries.
  Blog post: [ZK System Benchmarking](https://delendum.xyz/2023/01/11/zk-system-benchmarking.html).
- [ezkl](https://github.com/zkonduit/ezkl).
  A library and command-line tool for doing inference for deep
  learning models and other computational graphs in a zk-snark.
- [poseidon-circuit](https://github.com/scroll-tech/poseidon-circuit).
  Poseidon hash circuit and primitives. It integrated several poseidon
  hash schemes from zcash and iden3 and support sponge progress for
  hashing messages in any length.
- [starknet_in_rust](https://github.com/lambdaclass/starknet_in_rust).
  A Rust implementation of Starknet by LambdaClass.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

<!-- https://github.com/rustsec/advisory-db/pulls -->
<!-- https://osv.dev/list?page=2&ecosystem=crates.io -->


&nbsp;

## Most Active in January

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

#### [Anoma](https://github.com/anoma)

#### [Aptos](https://github.com/aptos-labs)

#### [Casper](https://github.com/casper-network)

#### [COMIT](https://github.com/comit-network)

#### [Concordium](https://github.com/Concordium)

#### [Conflux](https://github.com/Conflux-Chain)

#### [DarkFi](https://dark.fi)

#### [Dfinity](https://github.com/dfinity)

#### [Dusk Network](https://github.com/dusk-network)

#### [Elrond](https://github.com/ElrondNetwork)

#### [Espresso Systems](https://github.com/EspressoSystems)

#### [Filecoin](https://github.com/filecoin-project)

- [The FVM Imaginarium](https://filecoin.io/blog/posts/the-fvm-imaginarium-magmo-brings-state-channels-to-the-filecoin-virtual-machine/)
- [The Filecoin Virtual Machine Explained](https://filecoin.io/blog/posts/the-filecoin-virtual-machine-explained/)

#### [Findora](https://github.com/FindoraNetwork)

#### [Fluence](https://github.com/fluencelabs)

#### [Fuel](https://github.com/FuelLabs)

#### [Golem](https://github.com/golemfactory)

#### [Grin](https://github.com/mimblewimble/grin)

#### [Helium](https://github.com/helium)

#### [Holochain](https://github.com/holochain/)

- [Holochain 0.1.0 Is Here](https://blog.holochain.org/holochain-0-1-0-is-here/)

#### [IOTA](https://github.com/iotaledger)

#### [Maidsafe](https://github.com/maidsafe)

#### [Mina](https://github.com/MinaProtocol)

- [Four ZK Technologies You Should Know](https://minaprotocol.com/blog/four-zk-technologies-you-should-know)
- [Introducing the Web Node — an in-browser Mina node that verifies blocks and transfers funds](https://medium.com/openmina/introducing-the-web-node-an-in-browser-mina-node-that-verifies-blocks-and-transfers-funds-ebc59a57e79a).
  The source code [openmina](https://github.com/openmina/openmina).
- [zkIgnite, Cohort 1 Program Overview](https://minaprotocol.com/blog/zkignite-cohort-1-program-overview).
  A three-month program designed to help developers and entrepreneurs
  turn their innovative ideas into real-world applications and build
  successful businesses on Mina Protocol.

#### [MobileCoin](https://github.com/mobilecoinfoundation)

#### [NEAR](https://github.com/nearprotocol/nearcore)

#### [Nervos](https://github.com/nervosnetwork)

#### [Oasis](https://github.com/oasisprotocol)

#### [Parity](https://github.com/paritytech)

#### [Radix](https://github.com/radixdlt)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

#### [Solana](https://github.com/solana-labs/solana)

#### [Spacemesh](https://github.com/spacemeshos)

#### [Subspace Labs](https://github.com/subspace)

#### [Sui](https://github.com/MystenLabs)

#### [TezEdge](https://github.com/tezedge)

#### [Zcash](https://github.com/zcash)


&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

#### [BDK](https://github.com/bitcoindevkit/bdk)

#### [BitMask](https://github.com/diba-io/bitmask-core)

#### [Cyphernet](https://github.com/Cyphernet-WG)

#### [Electrs](https://github.com/romanz/electrs)

#### [Fedimint](https://github.com/fedimint/fedimint)

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

#### [LNP/BP](https://github.com/LNP-BP)

#### [LNP WG](https://github.com/LNP-WG)

#### [MyCitadel](https://github.com/orgs/mycitadel)

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

#### [Nomic](https://github.com/nomic-io)

#### [RGB](https://github.com/rgb-wg)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

#### [Sapio](https://github.com/sapio-lang/sapio)

#### [Talaia](https://github.com/talaia-labs/rust-teos)

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

#### [Foundry](https://github.com/foundry-rs/foundry)

#### [Lighthouse](https://github.com/sigp/lighthouse)

- [High-priority release: v3.4.0 (Stealy)](https://github.com/sigp/lighthouse/releases/tag/v3.4.0)

#### [Mir Protocol](https://github.com/mir-protocol)

#### [Rust Ethereum](https://github.com/rust-ethereum)

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

#### [Starkware](https://github.com/starkware-libs)

- [Papyrus: An Open-Source StarkNet Full Node](https://medium.com/starkware/papyrus-an-open-source-starknet-full-node-396f7cd90202).
  The source code:[papyrus](https://github.com/starkware-libs/papyrus).
- [Cairo 1.0 is Here](https://medium.com/starkware/cairo-1-0-is-here-7e1ac8377038)

#### [zkSync](https://github.com/matter-labs/zksync)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

Feb 15-17 | Barcelona, Spain

[European Blockchain Convention 2023](https://eblockchainconvention.com/)

Feb 24 — Mar 5 | Denver, USA

[ETHDenver 2023](https://www.ethdenver.com)

Mar 13 - Apr 7 | Ho Chi Minh City, Vietnam

[ZK Spring Residency in Vietnam](https://0xparc.org/blog/2023-spring-residency)

Mar 20-24 | Paris, France

[Paris Blockchain Week](https://www.parisblockchainweek.com)

Mar 26 | Tokyo, Japan

[FHE.org conference 2023](https://fhe.org/)

Mar 27-29 | Tokyo, Japan

[RWC 2023](https://rwc.iacr.org/2023/)

Apr 4 | Lisbon, Portugal

[zkSummit9](https://www.zksummit.com/)

May 1-5 | Bol, Brač, Croatia

[Financial Cryptography and Data Security 2023](https://fc23.ifca.ai/)

May 20-21 | Amsterdam, Netherlands

[ETHDam](https://www.ethdam.com/)

Jun 3-5 | Prague, Czech Republic

[Gateway to Cosmos 2023](https://gateway.events/)

Jun 17-20 | Paris, France

[EthCC](https://www.ethcc.io/)

Aug 28-30 | Palo Alto, CA, US

[The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Sep 11-13 | Berlin, Germany

[DappCon](https://www.dappcon.io/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->



More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


