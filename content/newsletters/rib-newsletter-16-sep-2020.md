---
title: "RiB Newsletter #16 – Secure Enclaves à la Crab"
description: "#16 - September 2020"
date: 2020-09-30
slug: "/2020-09-30-secure-enclaves-a-la-crab"
categories:
  - "newsletters"
summary: "For the last few months we've been following new zero-knowledge proof projects in Rust.
This month, with Secret Network upgrading their mainnet with secret contracts,
it seems like a good opportunity to explore Rust blockchains that are using
a completely different privacy-preserving technology: secure enclaves."

---

Welcome to the #16 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. 
[Previous: #15](/newsletters/2020-09-02-turbofish-in-the-blocksea/).

For the last few months we've been following new zero-knowledge proof projects in Rust.
This month, with [Secret Network upgrading their mainnet with secret contracts][smain],
it seems like a good opportunity to explore Rust blockchains that are using
a completely different privacy-preserving technology: secure enclaves.

[smain]: https://blog.scrt.network/upgrade-complete-secret-contracts-live-mainnet/

Secure enclaves are processes whose environment is protected from inspection by other processes,
even the kernel,
by special hardware.
This protection particularly involves the encryption of a process's memory.
Software that wants to compute in secret can put those computations inside a secure enclave and,
if everything works as expected,
neither a local user, nor the hosting provider,
can snoop on the computations being performed.
The most notable implementation of secure enclaves is Intel's [SGX] (Secure Guard Extensions).

[SGX]: https://en.wikipedia.org/wiki/Software_Guard_Extensions

Secure enclaves are an attractive way to perform private computation
primarily because they don't impose any limitations on what can be computed &mdash;
code that runs inside SGX is more-or-less just regular x86 code,
just running inside a special environment.
But depending on SGX for privacy does have some special risks:
software that runs in an SGX enclave must be signed (if transitively) by Intel's own cryptographic keys,
which means that Intel must approve of any software running in SGX,
that Intel can _revoke_ permission to use SGX,
and that there is a risk of the signing keys being compromised;
and it's not obvious that secure enclaves are actually secure,
there have already been a number of [attacks against SGX][sgxatt].
Regardless,
as of now,
hardware enclaves provide security features that aren't feasible any other way.

[sgxatt]: https://en.wikipedia.org/wiki/Software_Guard_Extensions#Attacks

There are two prominent Rust blockchains relying on SGX:

- **[Secret Network][sn]** is a programmable blockchain based on Cosmos / Tendermint
that runs smart contracts written in Rust,
and compiled to WASM,
inside of secure enclaves.

- **[MobileCoin][mc]** is a private currency that aims to integrate with [Signal],
and that uses SGX to add additional confidentiality on top of RingCT
transactions and its variant of the Stellar Consensus Protocol.

[Signal]: https://www.signal.org/
[sn]: https://github.com/enigmampc/
[mc]: https://github.com/mobilecoinofficial

Outside of the blockchain world there are some other Rust projects
using SGX, the most notable being:

- **[Teaclave SGX SDK][tea]** is an SDK for running Rust code inside SGX enclaves,
developed at Baidu, and now an Apache project.
MobileCoin uses a heavily modified fork.

- **[Fortanix][ftx]** is a provider of various Rust+SGX services,
and they provide an SGX SDK,
for which mainline Rust has some built-in support.

- **[Rust OP-TEE TrustZone SDK][tz]** is an SDK for ARM TrustZone.

[tea]: https://github.com/apache/incubator-teaclave-sgx-sdk
[ftx]: https://github.com/fortanix/rust-sgx
[tz]: https://github.com/sccommunity/rust-optee-trustzone-sdk

Whether it's secure enclaves or zk-SNARKs,
Rust blockchains are walking the bleeding edge of privacy tech.

In unrelated RiB news, we recently received two donations,
- [666 CKB in August](https://explorer.nervos.org/transaction/0x4eb46117c218482b84ce19c52ef02f642524b14ef4f39b9ad8c64bb75a8475ca)
- [500,000 CKB in September](https://explorer.nervos.org/transaction/0xdd9d3d0afaf07a3d91ff101475b3dffec0961e742c8cfdd617da3e7e9cef0c33)

Thanks so much to our anonymous donors.
We don't often receive donations,
so this was a nice surprise!
We intend to put all monetary contributions to use funding events or new contributors,
and we'll let you know what we do with the funds when we spend them.


&nbsp;

## Thanks

This edition of RiB was produced with contributions from 
[Aaron Lu][contributoral],
[Alex Chepurnoy][contributorac],
kathyjah, Paulii Good, [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue. 
Either submit a PR to the [#17 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), 
or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorac]: https://twitter.com/chepurnoy
[contributoral]: https://github.com/aalu1418
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[Aleo].

Aleo is a zero-knowledge blockchain,
with its own zero-knowledge programming language,
[Leo].

We don't have a lot to say about it,
but we think it looks cool.
We hope they blog more.

[Aleo]: https://github.com/AleoHQ/
[Leo]: https://github.com/AleoHQ/leo

&nbsp;


## Interesting Things

#### News
- [Tezos Foundation Biannual Update](https://tezos.foundation/wp-content/uploads/2020/09/tezos-foundation-biannual-update-september-2020-en.pdf)
- [Introducing the TezEdge Sandbox: Q&A with Simple Staking CEO Juraj Selep](https://tezos.foundation/tezedge-sandbox-juraj-selep/)

#### Blog Posts
- [First impressions of NEAR smart contract development in Rust](https://brson.github.io/2020/09/07/near-smart-contracts-rust)
- [ZKV’s Polkadot/Kusama Baseline Report](https://medium.com/zero-knowledge-validator/zkvs-polkadot-kusama-baseline-report-52949809719)

#### Papers
- [Lunar: a Toolbox for More Efficient Universal and Updatable zkSNARKs and Commit-and-Prove Extensions](https://eprint.iacr.org/2020/1069.pdf)
- [Mimblewimble Non-Interactive Transaction Scheme](https://eprint.iacr.org/2020/1064.pdf)
- [Foundations of Distributed Consensus and Blockchains](http://elaineshi.com/docs/blockchain-book.pdf). A complete book on distributed consensus, written by an expert.
- [Scalable and Probabilistic Leaderless BFT Consensus through Metastability](https://arxiv.org/pdf/1906.08936.pdf)
- [A Formally Verified Protocol for Log Replication with Byzantine Fault Tolerance](https://arxiv.org/pdf/2009.10664.pdf)
- [NC-Max: Breaking the Throughput Limit of Nakamoto Consensus](https://eprint.iacr.org/2020/1101.pdf)
- [Bitcoin–Monero Cross-chain Atomic Swap](https://eprint.iacr.org/2020/1126.pdf)
- [Incentives in Blockchain Design and Applications](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3657592)
- [Blockchain as a Confidence Machine: The Problem of Trusts & Challenges of Governance](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3665447)
- [A General Framework for the Security Analysis of Blockchain Protocols](https://arxiv.org/pdf/2009.09480.pdf)
- [The Velvet Path to Superlight Blockchain Clients](https://eprint.iacr.org/2020/1122.pdf)

#### Projects
- [Acala](https://github.com/AcalaNetwork/Acala).  CrossChain StableCoin platform based on Substrate. 
- [Anon](https://github.com/hicommonwealth/anon).
Substrate modules for anonymous group actions (ring signatures + merkle proofs).
- [Bitcoins-rs](https://github.com/summa-tx/bitcoins-rs). Bitcoin-oriented dev toolboxes for native and browser apps.
- [Cardano-serialization-lib](https://github.com/Emurgo/cardano-serialization-lib). A library for serialization & deserialization of data structures used in Cardano's Haskell implementation of Shelley along with useful utility functions.
- [Crust](https://github.com/crustio/crust).
Implementation of a Crust protocol node with Substrate.
- [Curv](https://github.com/ZenGo-X/curv) has built-in support for some useful operations/primitives such as verifiable secret sharing, commitment schemes, zero-knowledge proofs, and simple two-party protocols such as ECDH and coin flip.
- [Edgeware](https://github.com/hicommonwealth/edgeware-node).
Substrate node implementing Edgeware. It's an
On-chain Governed, Proof-of-Stake (PoS) Blockchain with a WASM Runtime
- [ergo-utilities-rust](https://github.com/robkorn/ergo-utilities-rust). General utilities to make writing off-chain [Ergo code](https://github.com/ergoplatform) in Rust simpler.
- [Fawkes-Crypto](https://github.com/zeropoolnetwork/fawkes-crypto)  is a lightweight framework for building circuits in bellman, using groth16 proving system and BN254 curve.
- [Hacspec](https://github.com/hacspec/hacspec). A specification language for cryptography primitives.
- [Magical Bitcoin Library](https://github.com/bitcoindevkit/bdk/tree/0.1.0-beta.1).
A modern, lightweight, descriptor-based wallet library written in Rust.
- [Phala](https://github.com/Phala-Network/phala-blockchain).
Phala Network is a TEE-Blockchain hybrid architecture implementing Confidential Contract. 
- [TezEdge](https://github.com/simplestaking/tezedge).
Tezos node/shell in Rust.

&nbsp;

## Most Active in September

[Solana](https://github.com/solana-labs/solana): 
274 merged PRs ([1][solana-merged-prs-1]),
95 closed issues ([1][solana-closed_issues-1]),
54 open issues ([1][solana-open_issues-1])

[Parity](https://github.com/paritytech): 
185 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2]),
82 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]),
63 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[Libra](https://libra.org):
204 merged PRs ([1][libra-merged-prs-1]),
24 closed issues ([1][libra-closed_issues-1]),
16 open issues ([1][libra-open_issues-1])

[COMIT](https://github.com/comit-network):
187 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]),
10 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3]), 
1 open issues ([1][comit-open_issues-1])

&nbsp;

## Project Updates


#### [Aleo](https://github.com/AleoHQ)

67 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 23 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]), 
20 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News: [Startup Aleo Wants to Help You Use the Internet Without Sacrificing Data Privacy](https://www.coindesk.com/aleo-internet-data-privacy-zero-knowledge-proofs)
- Podcast: [Aleo with Howard Wu](https://www.zeroknowledge.fm/144)
- PR: [feat(polycommit): support an upper bound on hiding bounds](https://github.com/AleoHQ/snarkOS/pull/424) by [@kobigurk](https://github.com/kobigurk)
- PR: [Hotfix: Fix import in benchmarks](https://github.com/AleoHQ/snarkOS/pull/474) by [@raychu86](https://github.com/raychu86)
- PR: [Revert "Wrap blocking operations into individual tasks"](https://github.com/AleoHQ/snarkOS/pull/463) by [@raychu86](https://github.com/raychu86)

#### [COMIT](https://github.com/comit-network)

187 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 10 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3]), 
1 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[comit-merged-prs-2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[comit-merged-prs-3]: https://github.com/comit-network/comit.network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[comit-closed_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[comit-closed_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[comit-closed_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[comit-open_issues-1]: https://github.com/comit-network/comit.network/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
		       
- Blog:
  - [Designing GitHub workflows for automated releases](https://comit.network/blog/2020/09/25/gh-release/)
  - [Setting up a ☁️ Bitcoin Full Node](https://comit.network/blog/2020/09/21/setup-bitcoin-cloud-node/)
- PR: [Move Business logic out of network behaviour](https://github.com/comit-network/comit-rs/pull/3152) by [@D4nte](https://github.com/D4nte)
- PR: [Order state uses quantity instead of percentage](https://github.com/comit-network/comit-rs/pull/3140) by [@da-kami](https://github.com/da-kami)

#### [Conflux](https://github.com/Conflux-Chain)

43 merged PRs ([1][conflux-merged-prs-1]), 21 closed issues ([1][conflux-closed_issues-1]), 
10 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News:
  - [Scaling Applications with Conflux Network](https://medium.com/conflux-network/scaling-applications-with-conflux-network-1fc0022a4c94)
  - [Conflux Network Partners With BCW To Design Next-Generation Payment Solutions](https://medium.com/conflux-network/conflux-network-partners-with-bcw-to-design-next-generation-payment-solutions-974997416bc6)
  - [MoonSwap:High speed,0 GAS AMM DEX with Ethereum and Conflux](https://medium.com/@MoonSwap/high-speed-0-gas-amm-with-ethereum-and-conflux-9422443f94ca)
  - [Unleashing Data Accessibility on Conflux Network](https://medium.com/conflux-network/unleashing-data-accessibility-on-conflux-network-c733e12b5728)
  - [Conflux Economic Model — Staking & Collateral For Storage On Conflux Network](https://medium.com/conflux-network/conflux-economic-model-staking-collateral-for-storage-on-conflux-network-cb4c8c150e3)
  - Bi-Weekly Progress Report:
    - [August 31— September 13, 2020](https://medium.com/conflux-network/bi-weekly-progress-report-august-31-september-13-2020-82ac16cc6808)
    - [August 17— August 30](https://medium.com/conflux-network/bi-weekly-progress-report-august-17-august-30-2020-c1b3cc3d7541)
- PR: [Add a new contract address scheme which use block_number in contract address calculation.](https://github.com/Conflux-Chain/conflux-rust/pull/1853) by [@yangzhe1990](https://github.com/yangzhe1990)
- PR: [Update code collateral computation.](https://github.com/Conflux-Chain/conflux-rust/pull/1868) by [@yangzhe1990](https://github.com/yangzhe1990)
- PR: [Enlarge reduced storage mpt cache space back by 1GB](https://github.com/Conflux-Chain/conflux-rust/pull/1870) by [@yangzhe1990](https://github.com/yangzhe1990)

#### [Crypto.com Chain](https://chain.crypto.com)

30 merged PRs ([1][crypto.com-merged-prs-1], [2][crypto.com-merged-prs-2]), 12 closed issues ([1][crypto.com-closed_issues-1]), 
6 open issues ([1][crypto.com-open_issues-1], [2][crypto.com-open_issues-2])

[crypto.com-merged-prs-1]: https://github.com/crypto-com/chain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[crypto.com-merged-prs-2]: https://github.com/crypto-com/chain-nodelib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[crypto.com-closed_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[crypto.com-open_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
[crypto.com-open_issues-2]: https://github.com/crypto-com/chain-nodelib/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- PR: [Problem: (CE40) Missing multiSig support.](https://github.com/crypto-com/chain-nodelib/pull/17) by [@foreseaz](https://github.com/foreseaz)
- PR: [Problem: (fix #2158)  hw wallet integration not tested](https://github.com/crypto-com/chain/pull/2217) by [@linfeng-crypto](https://github.com/linfeng-crypto)
- PR: [Problem: (fix #2249)genesis.json is not consistent with dev-conf.json…](https://github.com/crypto-com/chain/pull/2250) by [@allthatjazzleo](https://github.com/allthatjazzleo)

#### [Elrond](https://github.com/ElrondNetwork)

19 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3]), 0 closed issues, 0 open issues

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-dns-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30

- News:
  - eGold Is Now Officially Available on [Ledger](https://elrond.com/blog/egold-available-on-ledger/),
  [OKEx](https://elrond.com/blog/egold-listed-okex-exchange/),
  [SimpleSwap.io](https://elrond.com/blog/egold-on-simpleswap/),
  [Binance US](https://elrond.com/blog/egold-listed-on-binance-us/),
  [Bithumb Global](https://elrond.com/blog/egld-listing-on-bithumb-global/)
  - [eGold now available for card purchase in 180 countries and 13 fiats on Indacoin](https://elrond.com/blog/egold-on-indacoin/)
  - [The new Elrond wallet is LIVE](https://elrond.com/blog/the-new-elrond-wallet-is-live/)
  - [eGold Elite Competition](https://elrond.com/blog/egold-elite-competition/)
  - [Virtual Reality Content Platform Dvision Network to Add eGold as Currency and Work With Elrond Smart Accounts for True NFT Ownership & Maiar Integration](https://elrond.com/blog/virtual-reality-content-platform-dvision-network-to-add-egold-as-currency-and-work-with-elrond-smart-accounts-for-true-nft-ownership-maiar-integration/)
  - [Injective Protocol to Introduce eGold-based Products & Integrate Elrond Tech Into their Layer-2 DeFi Protocol](https://elrond.com/blog/injective-protocol-to-introduce-egold-based-products-integrate-elrond-tech-into-their-layer-2-defi-protocol/)
  - [Catalyst Sale on September 23: Get Your Share of 16,000 EGLD and Receive a 25% Bonus - Running on Bitfinex Token Sale Technology](https://elrond.com/blog/bitfinex-catalyst-sale-25-percent-bonus-egold/)
  - [Halo Indonesia! 2 Million New Users Get Direct Access to EGLD via IDR fiat on Indonesia's Largest Exchange Indodax](https://elrond.com/blog/halo-indonesia-2-million-new-users-get-direct-access-to-egld-via-idr-on-indonesias-largest-exchange-indodax/)
  - [Autonio Migrates to Elrond! The Token & Smart Contracts for the NIOX Automated DeFi Tools Will Be Deployed on our Mainnet](https://elrond.com/blog/autonio-migrates-to-elrond-the-token-smart-contracts-for-the-niox-automated-defi-tools-will-be-deployed-on-our-mainnet/)
  - [Mainnet Token Swap: Convert ERD into eGLD via the Elrond Swap Bridge](https://elrond.com/blog/elrond-token-swap-bridge/)
- Blog: [eGold: A Powerful Digital Currency Positioned for Global Adoption](https://elrond.com/blog/egold-a-powerful-digital-currency-positioned-for-global-adoption/)
- PR: [Rv fixes 3](https://github.com/ElrondNetwork/sc-delegation-rs/pull/20) by [@andrei-marinica](https://github.com/andrei-marinica)
- PR: [Refactoring of modify total delegation cap / change service fee](https://github.com/ElrondNetwork/sc-delegation-rs/pull/12) by [@andrei-marinica](https://github.com/andrei-marinica)
- PR: [unJail implementation](https://github.com/ElrondNetwork/sc-delegation-rs/pull/15) by [@andrei-marinica](https://github.com/andrei-marinica)

#### [Holochain](https://github.com/holochain/)

4 merged PRs ([1][holochain-merged-prs-1]), 0 closed issues, 0 open issues

[holochain-merged-prs-1]: https://github.com/holochain/holochain-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30

- News:
  - [Introducing CRISPR](https://blog.holochain.org/introducing-crispr-a-happ-hacking-lab/)
  - Holochain Dev Pulse
    - [80: A Fresh New Holochain](https://medium.com/holochain/a-fresh-new-holochain-902181bfa25b)
    - [79: How To Break a Holo App](https://medium.com/holochain/how-to-break-a-holo-app-9e23a97f7e2c)
    - [Special Announcement: New Holochain RSM Released to Public](https://medium.com/holochain/new-holochain-rsm-released-to-public-78f1c08474bf)
  - [A Big Leap Forward for Holochain & Holo](https://medium.com/h-o-l-o/a-big-leap-forward-for-holochain-holo-2efaaa54ed08)
  - [Dima Barbarchuk: Using Human-centric Design to Build Resilient & Self-developing Economies of the Future](https://medium.com/holochain/dima-barbarchuk-using-human-centric-design-to-build-resilient-self-developing-economies-of-the-ba422427e4a9)
- Videos:
  - [Holochain Ecosystem Sessions – David Atkinson interviews Architect Mike and CEO Adam from RedGrid](https://www.youtube.com/watch?v=BYcpuKBRIEs)
  - [Holo AMA No. 42 RSM - The New Holochain w/ Art Brock & David Atkinson](https://www.youtube.com/watch?v=a0FOj5YfCaQ)
  - [CRISPR – Overview Demo](https://www.youtube.com/watch?v=ENaKz0J9Gnk)
  - [CRISPR – hApp Builder Demo](https://www.youtube.com/watch?v=h0x865rbq0E)
- PR: [Add get_meta into admin interface](https://github.com/holochain/holochain-rust/pull/2207) by [@zippy](https://github.com/zippy)

#### [Libra](https://libra.org)

204 merged PRs ([1][libra-merged-prs-1]), 24 closed issues ([1][libra-closed_issues-1]), 
16 open issues ([1][libra-open_issues-1])

[libra-merged-prs-1]: https://github.com/libra/libra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News: Testnet push announcement for [09/30](https://community.libra.org/t/testnet-push-announcement-for-09-30/3151),
  [09/23](https://community.libra.org/t/testnet-push-annoucement-for-09-23/3136),
  [09/16](https://community.libra.org/t/testnet-push-annoucnement-for-09-16/3135)
- PR: [[breaking][libra-framework]  Refactor writeset prologue and epilogue](https://github.com/libra/libra/pull/6042) by [@runtian-zhou](https://github.com/runtian-zhou)
- PR: [[language] Structured logging in the VM](https://github.com/libra/libra/pull/6237) by [@dariorussi](https://github.com/dariorussi)
- PR: [[language][tools] Move CLI](https://github.com/libra/libra/pull/5913) by [@sblackshear](https://github.com/sblackshear)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)


4 merged PRs ([1][lighthouse-merged-prs-1]), 71 closed issues ([1][lighthouse-closed_issues-1]), 
33 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News: [Lighthouse Update #29](https://lighthouse.sigmaprime.io/update-29.html)
- PR: [Networking bug fixes](https://github.com/sigp/lighthouse/pull/1684) by [@blacktemplar](https://github.com/blacktemplar)
- PR: [Update boot-node and discovery](https://github.com/sigp/lighthouse/pull/1682) by [@AgeManning](https://github.com/AgeManning)
- PR: [Version bump to v0.2.13](https://github.com/sigp/lighthouse/pull/1683) by [@AgeManning](https://github.com/AgeManning)
- PR: [Update LH spadina bootnode](https://github.com/sigp/lighthouse/pull/1685) by [@AgeManning](https://github.com/AgeManning)

#### [MobileCoin](https://www.mobilecoin.com/)

68 merged PRs ([1][mobilecoin-merged-prs-1]), 1 closed issues ([1][mobilecoin-closed_issues-1]), 0 open issues

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinofficial/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinofficial/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30

- News:
  - [The MobileCoin Foundation welcomes Faisal Saeed AlMutar to the Policy Advisory Committee](https://medium.com/mobilecoin/the-mobilecoin-foundation-welcomes-faisal-saeed-almutar-da9cdcc4342d)
  - [Tiffiniy Cheng joins the MobileCoin Foundation’s Policy Advisory Committee](https://medium.com/mobilecoin/tiffiniy-cheng-joins-the-mobilecoin-foundations-policy-advisory-committee-d5957c939157)
  - [Welcome, Konstantin, to the MobileCoin technical advisory committee](https://medium.com/mobilecoin/welcome-konstantin-to-the-mobilecoin-technical-advisory-committee-f8a0eaaaf1fc)
  - [MobileCoin was featured as an Microsoft Azure customer story](https://customers.microsoft.com/en-us/story/844245-mobilecoin-banking-and-capital-markets-azure)
- Video: [Customer Panel: Applying confidential computing with Intel SGX in regulated industries](https://myignite.microsoft.com/sessions/418964c1-5312-49ec-9f53-2e2511cb7a83) 
- PR: [MCC-697 Digestible rework to use merlin](https://github.com/mobilecoinofficial/mobilecoin/pull/389) by [@garbageslam](https://github.com/garbageslam)
- PR: [MCC-959 side-channel resistant merkle proof validation](https://github.com/mobilecoinofficial/mobilecoin/pull/404) by [@garbageslam](https://github.com/garbageslam)
- PR: [Fee key env](https://github.com/mobilecoinofficial/mobilecoin/pull/438) by [@sugargoat](https://github.com/sugargoat)
- PR: [[MC-1601] Node maintains a single current slot](https://github.com/mobilecoinofficial/mobilecoin/pull/247) by [@mfaulk](https://github.com/mfaulk)

#### [NEAR](https://github.com/nearprotocol/nearcore)

59 merged PRs ([1][near-merged-prs-1]), 55 closed issues ([1][near-closed_issues-1]), 
50 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[near-closed_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[near-open_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News:
  - [Community Update: All our Node are Belong to You](https://near.org/blog/all-our-node-are-belong-to-you/). There is a bunch of learning resources.
  - [NEAR MainNet is now Community-Operated](https://near.org/blog/near-mainnet-is-now-community-operated/)
  - [The First NEAR Community Town Hall(Monday September 28th)](https://near.org/blog/the-first-near-community-town-hall-monday-september-28th/)
  - [Community Update: MainNet Phase I 🚀 , Hack the Rainbow 🌈 , OWC Demo Day](https://near.org/blog/community-update-mainnet-phase-i-%f0%9f%9a%80-hack-the-rainbow-%f0%9f%8c%88-owc-demo-day/)
  - [Transitioning NEAR MainNet to the Next Phase: It is Time to Stake, Delegate and Vote](https://near.org/blog/mainnet-phase-i/)
- Blog:
  - [Getting Started With the NEAR Wallet](https://near.org/blog/getting-started-with-the-near-wallet/)
- Discussion: [Voting criteria for the transition to Phase II](https://github.com/nearprotocol/NEPs/issues/115)
- PR: [feat: Implicit account creation](https://github.com/nearprotocol/nearcore/pull/3251) by [@evgenykuzyakov](https://github.com/evgenykuzyakov)
- PR: [feat(indexer): Explicitly add local receipts to StreamerMessage](https://github.com/nearprotocol/nearcore/pull/3311) by [@khorolets](https://github.com/khorolets)
- PR: [Limit number of transaction messages deserialized by peer actors per received block message](https://github.com/nearprotocol/nearcore/pull/3317) by [@birchmd](https://github.com/birchmd)

#### [Nervos](https://github.com/nervosnetwork)

39 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2]), 6 closed issues ([1][nervos-closed_issues-1]), 
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/rfcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News:
  - [Coinone Exchange Lists Nervos CKB for Trading in South Korea](https://medium.com/nervosnetwork/coinone-exchange-lists-nervos-ckb-for-trading-in-south-korea-dd514a8f0b2d)
  - [Nervos integrates with Linear Finance to propel DeFi development](https://medium.com/nervosnetwork/nervos-integrates-with-linear-finance-to-propel-defi-development-96b4c98805e)
  - [Nervos unveils Q4 plans in first Town Hall](https://medium.com/@nervosnetwork/nervos-unveils-q4-plans-in-first-town-hall-c45eff5fe078)
  - [Nervos to present roadmap and answer questions at Town Hall](https://medium.com/nervosnetwork/nervos-to-present-roadmap-and-answer-questions-at-town-hall-fd466bba3638)
  - [NervosHack wrap-up](https://medium.com/nervosnetwork/nervoshack-wrap-up-4370044f9866)
  - [Memecraft — Announcing the Nervos x Hxro Meme Competiton](https://medium.com/nervosnetwork/memecraft-announcing-the-nervos-x-hxro-meme-competiton-f67493426c46)
  - [Nervos attends Grin meetup and shares Mimblewimble update](https://medium.com/nervosnetwork/nervos-attends-grin-meetup-and-shares-mimblewimble-update-5f38f9f2fcb8)
  - [Grin Community Collaboration to Bring Mimblewimble to Nervos](https://medium.com/nervosnetwork/grin-community-collaboration-to-bring-mimblewimble-to-nervos-4a663df26f60)
  - [Hxro Brings Its Gamified Crypto Trading Platform to Nervos](https://medium.com/nervosnetwork/hxro-brings-its-gamified-crypto-trading-platform-to-nervos-fe264c4f5d28)
  - [6MM+ KuCoin users can begin trading $CKB September 4th](https://medium.com/nervosnetwork/6mm-kucoin-users-can-begin-trading-ckb-september-4th-60990d1214e)
  - [Nervos CKB Development Update #40](https://medium.com/nervosnetwork/nervos-ckb-development-update-40-589aeaef7cd8)
  - [Nervos Community Update: August 2020](https://medium.com/nervosnetwork/nervos-community-update-august-2020-addf1caf9b1e)
  - CKB Weekly
  [20](https://ckbweekly.substack.com/p/cross-chain-innovation-and-defi),
  [19](https://ckbweekly.substack.com/p/defi-interoperability-and-beyond),
  [18](https://ckbweekly.substack.com/p/nfts-on-ckb),
  [17](https://ckbweekly.substack.com/p/muta)
- Blog:
  - [Explained: Layer 2 DEX Designs on Nervos CKB](https://medium.com/nervosnetwork/layer-2-dex-designs-on-nervos-ckb-63e11282aaa0)
- PR: [refactor: rewrite discovery](https://github.com/nervosnetwork/ckb/pull/2236) by [@driftluo](https://github.com/driftluo)
- PR: [feat: redesign cell store](https://github.com/nervosnetwork/ckb/pull/2269) by [@zhangsoledad](https://github.com/zhangsoledad)
- PR: [feat: add nMinimumChainWork config](https://github.com/nervosnetwork/ckb/pull/2265) by [@driftluo](https://github.com/driftluo)

#### [Parity](https://github.com/paritytech)

185 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2]), 82 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 
63 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News:
  - [Writing History: The First Teams Submit Their Proposal to the Polkadot Treasury](https://polkadot.network/writing-history-the-first-teams-submit-their-proposal-to-the-polkadot-treasury-2/)
  - [Swisscom Blockchain to develop Kubernetes Operator for Kusama and Polkadot](https://polkadot.network/swisscom-blockchain-to-develop-kubernetes-operator-for-kusama-and-polkadot/)
  - [Substrate 2.0 is here](https://www.parity.io/substrate-2-0-is-here/)
  - Tech Preview: Rust IPFS + Substrate [1](https://medium.com/equilibriumco/tech-preview-rust-ipfs-and-substrate-64d277582f3c),
  [2](https://medium.com/equilibriumco/tech-preview-2-rust-ipfs-substrate-848b8a1afb26)
- Videos:
  - [Polkadot Network Live Stream](https://www.youtube.com/watch?v=WK1xj429LlA)
  - [What are Proxies?](https://www.youtube.com/watch?v=EuaM5dWAJis)
  - [Voting for Polkadot or Kusama Council](https://www.youtube.com/watch?v=837Vv3gdRzI)
  - [How to Create and Use Multisigs](https://www.youtube.com/watch?v=ZJLqszvhMyM)
  - [Substrate Seminar: Substrate 2.0](https://www.youtube.com/watch?v=unBtPOc6DZg)
  - [Substrate Seminar: Substrate Archive](https://www.youtube.com/watch?v=_bSg62jG-0g)
  - [Decentralizing the Cloud: The Promise and Potential of Distributed Storage](https://www.youtube.com/watch?v=Jbp289aMiQM)
- PR: [Allow pallet in construct_runtime to have fixed index](https://github.com/paritytech/substrate/pull/6969) by [@thiolliere](https://github.com/thiolliere)
- PR: [Tracing for wasm with bridging to native](https://github.com/paritytech/substrate/pull/6916) by [@gnunicorn](https://github.com/gnunicorn)
- PR: [Set reserved nodes with offchain worker.](https://github.com/paritytech/substrate/pull/6996) by [@kaichaosun](https://github.com/kaichaosun)
- PR: [state_machine no_std witness externalities](https://github.com/paritytech/substrate/pull/6934) by [@cheme](https://github.com/cheme)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

35 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 10 closed issues ([1][secret_network-closed_issues-1]), 
26 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[secret_network-merged-prs-2]: https://github.com/enigmampc/SafeTrace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News:
  - [Secret Raffle: Enter to Win Secrets by Using Keplr Wallet!](https://blog.scrt.network/secret-raffle-win-secrets-keplr-wallet/)
  - [SCRT 2020: Our Secret Vision for Universal Finance](https://blog.scrt.network/secret-2020-defi/)
  - [Secret Committees: Empowering Secret Agents](https://blog.scrt.network/secret-committees-empowering-secret-agents/)
  - [Upgrade Complete: Secret Contracts are LIVE on Mainnet!](https://blog.scrt.network/upgrade-complete-secret-contracts-live-mainnet/)
  - [Secret Network Ecosystem Update: August 2020](https://blog.scrt.network/ecosystem-update-august-2020/)
- Blog:
  - [Staking Secrets: A Living Guide to Staking and Delegating SCRT](https://blog.scrt.network/staking-secrets-guide-to-staking-delegating-scrt/)
  - [SecretWasm: Decentralized, Private Computation for Secret Apps](https://blog.scrt.network/secretwasm-decentralized-private-computation/)
  - [Secret Vaults: Programmable Access Control](https://blog.scrt.network/secret-vaults-programmable-access-control/)
  - [How To Build Secret Apps: An Evolving Development Guide](https://blog.scrt.network/how-to-build-secret-apps/)
- PR: [Added recursion limit of 5 to queries](https://github.com/enigmampc/SecretNetwork/pull/517) by [@reuvenpo](https://github.com/reuvenpo)
- PR: [Additional logs safety & tests](https://github.com/enigmampc/SecretNetwork/pull/523) by [@toml01](https://github.com/toml01)
- PR: [Use sent_funds in callback_sig](https://github.com/enigmampc/SecretNetwork/pull/539) by [@toml01](https://github.com/toml01)

#### [Solana](https://github.com/solana-labs/solana)

274 merged PRs ([1][solana-merged-prs-1]), 95 closed issues ([1][solana-closed_issues-1]), 
54 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News:
  - [OKEx Lists SOL](https://medium.com/solana-labs/okex-lists-sol-fb777e7d1d15)
  - [Binance.US Announces Support for SOL, making it the Second US Exchange within one day](https://medium.com/@SolanaLabs/binance-us-announces-support-for-sol-making-it-the-second-us-exchange-within-one-day-6c32a90869da)
  - [Tether to bring USDt to the Solana Network](https://medium.com/solana-labs/tether-to-bring-usdt-to-the-solana-network-77864184b20)
  - [FTX US Makes SOL Trading Available To United States Residents](https://medium.com/solana-labs/ftx-us-makes-sol-trading-available-to-united-states-residents-35696445295e)
- PR: [Persistent tower](https://github.com/solana-labs/solana/pull/10718) by [@ryoqun](https://github.com/ryoqun)
- PR: [Fix rooted accounts cleanup, simplify locking](https://github.com/solana-labs/solana/pull/12194) by [@carllin](https://github.com/carllin)
- PR: [Add sysvar to look at tx instructions](https://github.com/solana-labs/solana/pull/11943) by [@sakridge](https://github.com/sakridge)

#### [Zcash](https://z.cash/)

86 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 34 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
41 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-09-01..2020-09-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[zcash-closed_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-09-01..2020-09-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30
[zcash-open_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aopen+created%3A2020-09-01..2020-09-30

- News:
  - [Gemini becomes first regulated institution to support shielded Zcash withdrawals](https://electriccoin.co/blog/gemini-becomes-first-regulated-institution-to-support-shielded-zcash-withdrawals/)
  - [ECC welcomes the Major Grants Review Committee](https://electriccoin.co/blog/ecc-welcomes-the-major-grants-review-committee/)
  - [Refining and recommitting to the ECC mission](https://electriccoin.co/blog/refining-and-recommitting-to-the-ecc-mission/)
  - [FATF’s plans to regulate peer-to-peer transactions](https://electriccoin.co/blog/fatfs-plans-to-regulate-peer-to-peer-transactions/)
  - [Canopy security assessment complete](https://electriccoin.co/blog/canopy-security-assessment-complete/)
  - [Introducing TGPPL, a radically new type of open-source license](https://electriccoin.co/blog/introducing-tgppl-a-radically-new-type-of-open-source-license/)
- PR: [RFC: state updates](https://github.com/ZcashFoundation/zebra/pull/902) by [@hdevalence](https://github.com/hdevalence)
- PR: [Implement sighash](https://github.com/ZcashFoundation/zebra/pull/870) by [@yaahc](https://github.com/yaahc)
- PR: [ZIP-321: Payment Request URIs](https://github.com/zcash/zips/pull/395) by [@nuttycom](https://github.com/nuttycom)

&nbsp;

## Events

Oct 1-30 | Online

[ETHOnline 2020](https://www.ethonline.org/). Summits + Hackathon.

Oct 16–30 | Online

[Cosmos Hackathon: HackAtom V](https://hackatomv.devpost.com/)

Oct 21-23 | NYC, US

[ACM Advances in Financial Technologies](https://aft.acm.org/)

Oct 27-28 | Dubai

[Future Blockchain Summit](https://www.futureblockchainsummit.com/)

&nbsp;

## Careers

Aleo | San Francisco, US; Remote
- [Full-Stack Developer](https://aleo.org/jobs/full-stack-developer)
- [Backend Developer](https://aleo.org/jobs/backend-developer)
- [Senior Front-End Developer](https://aleo.org/jobs/senior-front-end-developer)

Chainlink | Remote
- [Blockchain Tools Engineer - Entry Level](https://careers.smartcontract.com/o/blockchain-tools-engineer-entry-level)

Compound | Remote
- [Rust Engineer](https://www.crypto-careers.com/jobs/39500671-rust-engineer-at-compound)

Dock | Remote
- [Rust & DevOps](https://www.cryptojobsdaily.com/job/dock-blockchain-developer-rust-devops/)

SimpleStaking | Remote
- [Rust Developer](https://stackoverflow.com/jobs/382213/rust-developer-100-remote-simplestakingcom-ltd)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#17 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft),
or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

![](../../images/2020-09-30-pumkin.jpg)

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**

