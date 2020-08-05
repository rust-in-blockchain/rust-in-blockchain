#Rust in Blockchain Newsletter #14 -- July, 2020

Welcome to the #14 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #13](/newsletters/2020-07-01-stuck-inside-hacking-away/).

&nbsp;

## Thanks

This edition of RiB was produced with contributions from TODO (awesome-rib contributors), [EnforSys][contributorenforsys], Paulii Good, Sol, [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. If you follow a particular project, or otherwise find information that is beneficial to the Rust & blockchain community, please contribute to the next issue. Either submit a PR to the [#15 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorenforsys]: https://twitter.com/SysEnfor
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project Spotlight

Ethers-rs
- https://twitter.com/gakonst/status/1278216215345889286
- https://docs.rs/ethers/0.1.3/ethers/

&nbsp;

## Interesting Things

#### News
- [Rust Crypto](https://twitter.com/RustCryptoOrg/status/1282847432787685376) The `k256` crate (pure Rust secp256k1 elliptic curve implementation) just landed an impressive new scalar/field arithmetic backend inspired by bitcoin-core's libsecp256k1 Party popper.
- [NIST’s Post-Quantum Cryptography Program Enters ‘Selection Round’](https://www.nist.gov/news-events/news/2020/07/nists-post-quantum-cryptography-program-enters-selection-round)
- [Rust is now a top 20 language in all of the 5 most major language popularity listings](https://www.reddit.com/r/rust/comments/hz7dfp/rust_is_now_a_top_20_language_in_all_of_the_5/)
- Microsoft open sources [Spartan](https://github.com/microsoft/Spartan): High-speed zkSNARKs without trusted setup.
- [Elrond](https://github.com/elrondnetwork), a sharded blockchain, whose mainnet went live in July, has several Rust projects.
  - Tutorial: The Crowdfunding Smart Contract [(part 1)](https://docs.elrond.com/developers/dev-tutorials/the-crowdfund-smartcontract),
  [(part 2)](https://docs.elrond.com/developers/dev-tutorials/the-crowdfunding-smart-contract-part-2)
  - Blog: [My first smart contract in Rust on Elrond VM](https://hiddentao.com/archives/2020/07/17/my-first-smart-contract-in-rust-on-elrond-vm)


#### Blog Posts
- [What's It Good For?](https://www.etherean.org/blockchain/web3/software/2020/07/25/whats-it-good-for.html)
- [NEAR Accounts and Access Keys as Identities for Textile Integration](https://vitalpoint.ai/near-textile-integration/)
- [Distaff VM: approaching Turing-completeness](https://ethresear.ch/t/distaff-vm-approaching-turing-completeness/7757)
- [Hunting down a non-determinism-bug in our Rust Wasm build](https://dev.to/gnunicorn/hunting-down-a-non-determinism-bug-in-our-rust-wasm-build-4fk1)


#### Papers

#### Projects
- Elrond's Rust smart contracts:
  - [elrond-wasm-rs](https://github.com/ElrondNetwork/elrond-wasm-rs). Rust smart contract library designed for Elrond's Arwen VM. Also provides a debugging mode with mocks.
  - [sc-bitswing-rs](https://github.com/ElrondNetwork/sc-bitswing-rs). BitSwing smart contract by Band Protocol.
  - [sc-busd-rs](https://github.com/ElrondNetwork/sc-busd-rs). BUSD stablecoin smart contract implementation and tests.
  - [sc-delegation-rs](https://github.com/ElrondNetwork/sc-delegation-rs). Smart contract for managing staking delegation in Elrond.
  - [sc-dns-rs](https://github.com/ElrondNetwork/sc-dns-rs). Elrond DNS smart contract, written in Rust.
- [flux-protocol](https://github.com/fluxprotocol/flux-protocol). Open market protocol build on NEAR protocol.
- [Forest](https://github.com/ChainSafe/forest). Rust Filecoin Node Implementation.
- [Graph Node](https://github.com/graphprotocol/graph-node) indexes data from blockchains such as Ethereum and serves it over GraphQL.
- [Minsc](https://github.com/shesek/minsc), a Miniscript-based scripting language for Bitcoin contracts.
- [Neptune](https://github.com/filecoin-project/neptune) is a Rust implementation of the Poseidon hash function tuned for Filecoin.
- [Polymesh](https://github.com/PolymathNetwork/Polymesh). Polymesh is a blockchain for regulated securities and open finance.
- [rusty-blockparser](https://github.com/gcarq/rusty-blockparser). Bitcoin Blockchain Parser written in Rust.
- [rust-fil-proofs](https://github.com/filecoin-project/rust-fil-proofs). The Filecoin Proving Subsystem (or FPS) provides the storage proofs required by the Filecoin protocol. It is implemented entirely in Rust, as a series of partially inter-dependent crates – some of which export C bindings to the supported API.
- [Shuffler](https://github.com/roynalnaruto/shuffler) uses StarkWare's VeeDo VDF to seed a seedable RNG, and shuffle a randomisable list of items.
- SputnikVM: Rust Ethereum Virtual Machine Implementation
https://twitter.com/rust_blockchain/status/1278851897961545728
- [Stacks 2.0](https://github.com/blockstack/stacks-blockchain) is an open-membership replicated state machine produced by the coordination of a non-enumerable set of peers.
- [Tezos node/shell in Rust](https://github.com/simplestaking/tezedge)
- [Yew](https://github.com/yewstack/yew). Rust / Wasm framework for building client web apps.
- [zeroize.rs](https://github.com/iqlusioninc/crates/tree/develop/zeroize). Securely zero memory while avoiding compiler optimizations.
- [ZoKrates](https://github.com/Zokrates/ZoKrates). A toolbox for zkSNARKs on Ethereum.

#### Podcasts and Videos
- [Dan Guido: Trail of Bits – The Evolution of Smart Contract Security #346](https://www.youtube.com/watch?v=fOkQuNzVn_Q)
- [Hashing It Out #87-Informal Systems Ethan Buchman](http://thebitcoinpodcast.com/hashing-it-out-87/)
- [Trail of Bits (Dan Guido) – The Evolution of Smart Contract Security](https://epicenter.tv/episodes/346)

&nbsp;

## Most Active in July

&nbsp;

## Project Updates

#### [COMIT](https://github.com/comit-network)

#### [Crypto.com Chain](https://chain.crypto.com)

- News: [Crypto.com Chain Dev Update #10](https://blog.crypto.com/crypto-com-chain-dev-update-10)
  - Open sourcing [Chain Indexing Service](https://github.com/crypto-com/chain-index). It can index on chain data into structured records for query.
  - [Successfully complied chain core written in Rust into WebAssembly](https://github.com/crypto-com/chain/blob/master/chain-core/BUILD-WASM.md)
- News: Released Thaler Testnet [Block Explorer 2.0](https://chain.crypto.com/explorer) and [Faucet](https://chain.crypto.com/faucet)
- News: Revamped [Chain Website](https://chain.crypto.com) with brand new [Products and Releases Page](https://chain.crypto.com/releases) for developers engagement.
- News: [Node.js library](https://github.com/crypto-com/chain-nodelib) supports latest Testnet
- Promotion: [Calling for validators and staking pools to join Crypto.com Thaler Testnet](https://twitter.com/cryptocom/status/1276424962186735616?s=20).

#### [Holochain](https://github.com/holochain/)

- News: Dev Pulse [76](https://blog.holochain.org/speedy-improved-holochain-release-unblocks-all-the-things/), [75](https://blog.holochain.org/holofuel-enters-community-testing-phase/)
- News: [The Host Release of HoloFuel](https://medium.com/h-o-l-o/the-host-release-of-holofuel-6fc36003e373)
- News: [Monthly Roundup for Holo & Holochain](https://medium.com/h-o-l-o/monthly-roundup-for-holo-holochain-18cb9f69c5df)
- Blog: [Mutual Credit, Part 1: A New Type of Cryptocurrency, As Old As Civilisation](https://blog.holochain.org/mutual-credit-part-1-a-new-type-of-cryptocurrency-as-old-as-civilisation/)

#### [Libra](https://libra.org)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

#### [MobileCoin](https://www.mobilecoin.com/)

#### [NEAR](https://github.com/nearprotocol/nearcore)


#### [Nervos](https://github.com/nervosnetwork)

#### [Parity](https://github.com/paritytech)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

#### [Solana](https://github.com/solana-labs/solana)

#### [Zcash](https://z.cash/)

&nbsp;

## Events

Aug 9-11 | Online

[Community Ethereum Development Conference](https://edcon.io/)

Aug 15 | Online

[ACAS2020](https://sites.google.com/zkproof.org/acas2020/).
2nd Workshop on Advanced Cryptography Applications and Standards

Aug 20, 2020 | Online

[RustConf 2020](https://rustconf.com/)

Aug 28-29 | Online

Chainlink’s [Smart Contract Virtual Summit #0](https://www.smartcontractsummit.io/)

Oct 2-30 | Online

[ETHOnline 2020](https://www.ethonline.org/). Summits + Hackathon.

Oct 21-23 | NYC, US

[ACM Advances in Financial Technologies](https://aft.acm.org/)


&nbsp;

## Careers

Equilibrium | Remote
- [Senior Software Engineer Rust/Go](https://www.notion.so/Hiring-Senior-Software-Engineer-Rust-Go-e6c94ccc261f426c80a483c7fc642412)

Findora | Menlo Park, CA
- [Senior Systems Engineer](https://jobs.lever.co/findora/e89e2e02-622c-41da-a14d-c12d854a25b5)

Informal Systems | Berlin, Toronto, Remote
- [Senior Distributed Systems Engineer](https://informal.systems/careers/senior-distributed-systems-engineer/)

Kraken | Remote
- [Backend Engineer - Rust](https://jobs.lever.co/kraken/4019a818-4a7b-46ef-9225-c53c7a7f238c)
- [Senior Backend Engineer - Rust](https://jobs.lever.co/kraken/4c864c8f-bde6-443d-b521-dd90df0e9105)
- [Backend Engineer - Crypto/Payments](https://jobs.lever.co/kraken/39031c44-2060-467d-8991-79f23deacbb8)
- [Backend Engineer, Data Processing – Rust](https://jobs.lever.co/kraken/246f7fd2-000a-4f61-8f53-b1cc783d51cb)

NEAR | Remote
- [General Purpose Full-time Engineer - Rust](https://twitter.com/mzavershynskyi/status/1286056901914968065?s=20)

Protocol Labs | Remote
- [Software Engineer, Cryptography & Systems](https://jobs.lever.co/protocol/9afbc1c9-8b3b-4c03-856d-6b0cb5518eaa)
- [Software Engineer, Peer-to-Peer Networks](https://jobs.lever.co/protocol/e4a469e4-c420-4ae5-acea-44c33a03dbd2)
- [Sr. Software Engineer, libp2p](https://jobs.lever.co/protocol/8c03a123-4890-4265-96e1-0427bd7ec193)
- [Sr. Software Engineer, Filecoin](https://jobs.lever.co/protocol/3490e571-4d47-487e-a47f-b02f08668290)

[Revault](mailto:darosior@protonmail.com) | Portugal or Remote
- Build a [Bitcoin vault architecture](https://github.com/re-vault/practical-revault/blob/master/revault.pdf)

Solana | (Probably)Remote
- [Front End Engineer](https://solana.com/frontend-eng-jd.pdf)

Soramitsu | Remote
- [Senior Rust Developer](https://soramitsu.freshteam.com/jobs/ifK-X2sHqXp6/rust-developer-senior-remote)

Trail of Bits | Remote
- [Cryptography Analyst](https://jobs.lever.co/trailofbits/56af8506-3205-4c7b-b28d-ba8292bd1a47)
- [Application Security Engineer](https://jobs.lever.co/trailofbits/8b7f7fc1-efb0-4e89-b406-784c3a2d77e4)


&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#15 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**

