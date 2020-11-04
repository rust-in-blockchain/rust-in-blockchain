# RiB Newsletter #17

Publish on 4th Nov, 2020

Welcome to the #17 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. 
[Previous: #16](/newsletters/2020-09-30-secure-enclaves-a-la-crab/).



&nbsp;

## Thanks

Contributors.

[ashput][contributor-ashput],
[Daniel Karzel][contributor-dakami],

Awesome contributors: [Damascene][contributor-damascene],
[Mikko Ohtamaa][contributor-miohtama],


RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue. 
Either submit a PR to the [#18 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), 
or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributor-ashput]: https://github.com/ashput
[contributor-dakami]: https://github.com/da-kami
[contributor-damascene]: https://github.com/damascene
[contributor-miohtama]: https://github.com/miohtama

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News


#### Blog Posts

- [Rusty Chains: A Basic Blockchain Implementation Written in Pure Rust](https://hackernoon.com/rusty-chains-a-basic-blockchain-implementation-written-in-pure-rust-gk2m3uri)
- [Towards formal semantics of the beacon chain’s pyspec](https://ethresear.ch/t/towards-formal-semantics-of-the-beacon-chains-pyspec/8181)
- [Rust no-std FAQ](https://justjjy.com/Rust-no-std). Basic and useful.
- [Rust after the honeymoon](http://dtrace.org/blogs/bmc/2020/10/11/rust-after-the-honeymoon/).
  It isn't blockchain related.
  The write features some that also very useful for blockchain developers.
- [People of Parity: Bastian Köcher](https://www.parity.io/people-of-parity-bastian-koecher/).
  Besides technology, Parity also creates lovely developer stories.

#### Papers 

- [Proofs, Arguments, and Zero-Knowledge](http://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf)

#### Projects

- [Curve on Zinc](https://github.com/matter-labs/curve-zinc).
  The Curve Stableswap smart contract implementation in Zinc v0.2.0.
- [Marlin](https://github.com/o1-labs/marlin) contains
  various zk-SNARK protocol implementations for
  recursive SNARK composition.
- [Oak](https://github.com/project-oak/oak).
  Meaningful control of data in distributed systems.
- [Rust-lnpbp](https://github.com/LNP-BP/rust-lnpbp).
  A rust library implementing LNP/BP specifications.
  It can be used to simplify development of layer 2 & 3 solutions
  on top of Lightning Network and Bitcoin blockchain.
- [Rust-Lightning](https://github.com/rust-bitcoin/rust-lightning)
  is a Bitcoin Lightning library written in Rust.
  The main crate, lightning, does not handle networking,
  persistence, or any other I/O. Thus, it is runtime-agnostic,
  but users must implement basic networking logic,
  chain interactions, and disk storage.
- [Rust-miniscript](https://github.com/rust-bitcoin/rust-miniscript).
  Support for Miniscript and Output Descriptors for rust-bitcoin.
- [Rust-amplify](https://github.com/LNP-BP/rust-amplify). 
  Amplifying Rust language capabilities: multiple generic trait implementations, 
  type wrappers, derive macros
- [Serum-dex](https://github.com/project-serum/serum-dex).
- [BTC-Parachain](https://github.com/interlay/BTC-Parachain).
  BTC-Parachain: Trustless Bitcoin on Polkadot (Mirror).

#### Podcasts and Videos


&nbsp;

## Most Active in October


&nbsp;

## Project Updates


#### [Aleo](https://github.com/AleoHQ)

#### [Conflux](https://github.com/Conflux-Chain)

#### [COMIT](https://github.com/comit-network)

58 merged PRs([1][comit-rs], [2][xmr-btc-swaps], [3][ambrosia]),

[comit-rs]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31+NOT+bump
[xmr-btc-swaps]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31+NOT+bump
[ambrosia]: https://github.com/comit-network/ambrosia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31+NOT+bump

- R&D: [XMR-BTC swaps](https://comit.network/blog/2020/10/06/monero-bitcoin)
- News: [Trade Bitcoin and DAI with COMIT - Alpha version of our non-custodial trading UI released](https://comit.network/blog/2020/10/12/ambrosia-alpha-release)
- News: [Designing GitHub workflows for automated releases](https://comit.network/blog/2020/09/25/gh-release)

#### [Holochain](https://github.com/holochain/)

#### [Libra](https://libra.org)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

- News: [Lighthouse Update #30](https://lighthouse.sigmaprime.io/update-30.html)

#### [MobileCoin](https://www.mobilecoin.com/)

#### [NEAR](https://github.com/nearprotocol/nearcore)

- News:
  - [TrustToken Bridges TUSD to NEAR](https://near.org/blog/trusttoken-bridges-tusd-to-near/)
  - [NEAR joins FlamingoDAO](https://near.org/blog/near-joins-flamingodao-%f0%9f%a6%a9/)
  - [Balancer’s DeFi Protocol is bringing Programmable Liquidity to NEAR](https://near.org/blog/balancers-defi-protocol-is-bringing-programmable-liquidity-to-near/)
  - [NEAR Developer Research: Validating the NEAR DevX Tech Stack – Round 2](https://near.org/blog/near-developer-research-validating-the-near-devx-tech-stack-round-2/)
  - [The NEAR MainNet is now Unrestricted and Decentralized](https://near.org/blog/near-mainnet-phase-2-unrestricted-decentralized/)
  - [Community Update – Beyond Launch](https://near.org/blog/community-update-beyond-launch/)
- Blog:
  - [How the NEAR Foundation is Supporting Network Decentralization](https://near.org/blog/how-the-near-foundation-is-supporting-network-decentralization/)
  - [Getting Started With the NEAR Wallet](https://near.org/blog/getting-started-with-the-near-wallet/)

#### [Nervos](https://github.com/nervosnetwork)

- News:
  - [Bitpie builds stablecoin bridge between Ethereum and CKB](https://medium.com/nervosnetwork/bitpie-builds-stablecoin-bridge-between-ethereum-and-ckb-d6a4b30cc92)
  - [Advanced CKB mining infrastructure with Insight](https://medium.com/nervosnetwork/grant-approved-advanced-ckb-mining-infrastructure-with-insight-956146955dc5)
- Blog:
  - [Session with #NervosHack winners SECBIT, NerBRos, and LeapDAO](https://medium.com/nervosnetwork/q-a-session-with-nervoshack-winners-secbit-nerbros-and-leapdao-1b22a92cebaf)
  - [Portal Wallet and pw-sdk: Connecting blockchain users around the world](https://medium.com/nervosnetwork/portal-wallet-and-pw-sdk-connecting-blockchain-users-around-the-world-78027e0860e7)

#### [Oasis](https://github.com/oasislabs)

#### [Parity](https://github.com/paritytech)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

#### [Solana](https://github.com/solana-labs/solana)

- News:
  - [October Newsletter](https://medium.com/solana-labs/october-newsletter-2bca800ed41c)
  - [September Newsletter](https://medium.com/solana-labs/september-newsletter-4d2c341035)
- Blog:
  - [Why Solana?](https://medium.com/solana-labs/why-solana-8c927d58ba06)

#### [Zcash](https://z.cash/)


&nbsp;

## Events


&nbsp;

## Careers

Parity Technologies | Berlin or Remote 
- [Rust Blockchain Bridge Engineer](https://www.parity.io/apply/?gh_jid=4170674003)
- [Rust Core Engineer](https://www.parity.io/apply/?gh_jid=4030037003)
- [WASM Compiler Engineer](https://www.parity.io/apply/?gh_jid=4170712003)

Zama | Paris, Partial remote authorized
- [Senior Engineer - Rust](https://www.welcometothejungle.com/en/companies/zama/jobs/senior-engineer-rust_paris)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#18 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft),
or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**


