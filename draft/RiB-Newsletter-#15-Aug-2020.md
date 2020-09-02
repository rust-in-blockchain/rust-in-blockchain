RiB Newsletter #15 - So Long and Thanks for All the Turbofish
 - Aug 2020"

date: 2020-09-02

Welcome to the #15 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. 
[Previous: #14](/newsletters/2020-08-05-are-we-smart-contract-yet/).

The big news this month is that [Mozilla laid off all but one of its full-time
Rust employees][mozlay]. There are a few other people left at Mozilla who
actively contribute to Rust as part of their role in Firefox, but this mostly
ends Mozilla's committment to Rust's development.

There's no need to worry though. Rust was intentionally designed to outlive
Mozilla's withdrawal, and the project will continue nearly
unaffected. Most of Rust's development and leadership comes from outside Mozilla
already, and no doubt all of those who lost there jobs will be re-hired quickly,
and some will continue to contribute to Rust. Rust's legal responsibilities
[will be transferred to a foundation independent from Mozilla][rustfound].

So long, Mozilla, and thanks. We'll take it from here.

That said, Rust always needs to strengthen its paid contributor base, and
this is an opportunity for invested companies to step up and help the project,
possibly while hiring some of the best Rust developers in the world.

[mozlay]: https://news.ycombinator.com/item?id=24120336
[rustfound]: https://blog.rust-lang.org/2020/08/18/laying-the-foundation-for-rusts-future.html

Naturally,
Rust blockchain development continued at its typical blistering pace,
and again its impossible to follow everything going on.

This month we see continued advancement in zero-knowledge computing,
an obvious focus from the entire blockchain industry on the DeFi phenomenon,
an encouraging trend towards Rust smart contracts,
and a proliferation of hackathons with opportunities for Rust developers.

TODO


&nbsp;

## Thanks

This edition of RiB was produced with contributions from 
 -- TODO -- 

Andrew Miller, 
[Calvin Lau][contributorcl], 
[James Waugh][contributorjamesw], 
[Jane Wu][contributorjw], 
Kevin McCloskey, 
/*Paulii Good,*/
Taylor Lee,
[Moonbeam][org-moonbean],
[Fluence][org-fluence], 


[Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. 
And [Awesome Blockchain Rust][repo-awesome] contributors [Matt Bell][contributormb]
-- TODO --

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue. 
Either submit a PR to the [#16 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), 
or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorcl]: https://github.com/calvinlauco
[contributormb]:https://github.com/mappum
[contributorjw]: https://twitter.com/janewuco
[contributorjamesw]: https://github.com/jlwaugh

[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer
[repo-awesome]: https://github.com/rust-in-blockchain/awesome-blockchain-rust
[org-moonbean]: https://twitter.com/MoonbeamNetwork
[org-fluence]: https://twitter.com/fluence_project


&nbsp;


## Project Spotlight

&nbsp;

## Interesting Things

#### News

- [James Waugh][contributorjamesw] shared big news from Secret Network.
>Privacy-preserving smart contracts are going live on Secret Network Tuesday, September 15! 
>Now developers can build and deploy “secret contracts” with encrypted inputs, outputs, and state.
- [Welcome to Aleo.](https://www.aleo.org/post/welcome-to-aleo)
- [Coinbase: zkSNARKS and Cryptographic Accumulators](https://blog.coinbase.com/zksnarks-and-cryptographic-accumulators-f840da0b61c6)
- [Flux is Live on Mainnet](https://medium.com/@fluxmarket/flux-is-live-on-mainnet-741cf2dbe126)
- [Flux — decentralizing mainnet](https://medium.com/@fluxmarket/flux-decentralizing-mainnet-e97df35e421a)


#### Blog Posts

- [Ethereum is a Dark Forest](https://medium.com/@danrobinson/ethereum-is-a-dark-forest-ecc5f0505dff)
- [zkSNARKS and Cryptographic Accumulators](https://blog.coinbase.com/zksnarks-and-cryptographic-accumulators-f840da0b61c6?gi=edbf393c1af2)
- [Write your Own Virtual Machine](https://justinmeiners.github.io/lc3-vm/)
- [Write your Own Proof-of-Work Blockchain](https://justinmeiners.github.io/tiny-blockchain/)
- [What is a Cryptographic Hash Function?](https://decentralizedthoughts.github.io/2020-08-28-what-is-a-cryptographic-hash-function/)

#### Papers 

- [Consensus Redux: Distributed Ledgers in the Face of Adversarial Supremacy](https://eprint.iacr.org/2020/1021.pdf)
- [Polynomial IOPs for Linear Algebra Relations](https://eprint.iacr.org/2020/1022.pdf)
- [RANDCHAIN: Decentralised Randomness Beacon from Sequential Proof-of-Work](https://eprint.iacr.org/2020/1033.pdf)

#### Projects

- [Crust](https://github.com/crustio/crust). Official Rust implementation of the Crust protocol.
- [Fluence](https://github.com/fluencelabs/fluence). Peer-to-peer computing protocol and licensing system.
- [Fluence Compute Engine](https://github.com/fluencelabs/fce). FCE is intended to run various Wasm binaries. 
  At now, it is in the heavily developing phase. Docs and tutorials are also in the work-in-progress state.
- [Zcash Halo2](https://github.com/zcash/halo2)
- [Moonbeam](https://github.com/PureStake/moonbeam). Moonbeam provides an Ethereum-compatible smart contract platform that makes it easy to build natively interoperable applications.
- [Nomic](https://github.com/nomic-io/nomic). Rust implementation of the Nomic Bitcoin sidechain.
- [Openlimits](https://github.com/nash-io/openlimits). A Rust high performance cryptocurrency trading API with support for multiple exchanges and language wrappers.
- [PLONK](https://github.com/dusk-network/plonk). Pure Rust implementation of the PLONK ZKProof System done by the Dusk-Network team.
- [Rio Chain](https://github.com/RioDefi/riochain). 
  Rio DeFi is the blockchain technology company that developed Rio Chain, 
  featuring robust security, speed, scalability, and interoperability with existing blockchains.
- [Rusk](https://github.com/dusk-network/rusk). Dusk's Smart Contract Platform. 
- [Rusk VM](https://github.com/dusk-network/rusk-vm). The Dusk Rust WASM VM implementation.
- [SnarkOS](https://github.com/AleoHQ/snarkOS) is a decentralized operating system for private applications. It forms the backbone of Aleo and enables applications to verify and store state in a publicly verifiable manner.
- [ZEXE](https://github.com/scipr-lab/zexe). Zero knowledge EXEcution is a Rust library for decentralized private computation.

#### Podcasts and Videos

- [Introduction to zkSync](https://medium.com/matter-labs/introduction-to-zksync-16f3753ac96c)
- [WebAssembly Migration with Nicolo Davis](https://softwareengineeringdaily.com/2020/09/01/webassembly-migration-with-nicolo-davis/) 
  and its [script](https://softwareengineeringdaily.com/wp-content/uploads/2020/08/SED1126-WebAssembly-Migration.pdf)
- [ZKPodcast: Aleo with Howard Wu](https://www.zeroknowledge.fm/144)

&nbsp;

## Most Active in August


&nbsp;

## Project Updates

#### [COMIT](https://github.com/comit-network)

140 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]), 
14 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3]), 
0 open issues

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[comit-merged-prs-2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[comit-merged-prs-3]: https://github.com/comit-network/comit.network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[comit-closed_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[comit-closed_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[comit-closed_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01

- PR: [Standardized COMIT Expiry Times](https://github.com/comit-network/comit-rs/pull/3055) by [@tcharding](https://github.com/tcharding)
- PR: [Save orders to the DB and allow them to be fetched again](https://github.com/comit-network/comit-rs/pull/3089) by [@thomaseizinger](https://github.com/thomaseizinger)
- PR: [Handle deploy for ERC20](https://github.com/comit-network/comit-rs/pull/3105) by [@tcharding](https://github.com/tcharding)
- PR: [Several refactoring patches as a preparation for the re-design of the orderbook in the context of tantalus + some cool features](https://github.com/comit-network/comit-rs/pull/3066) by [@thomaseizinger](https://github.com/thomaseizinger)
- PR: [Geth v1.9.18 instead of parity, upgrade to rust web3 0.13](https://github.com/comit-network/create-comit-app/pull/819) by [@da-kami](https://github.com/da-kami)

#### [Crypto.com Chain](https://chain.crypto.com)

100 merged PRs ([1][crypto.com-merged-prs-1], [2][crypto.com-merged-prs-2], [3][crypto.com-merged-prs-3]), 59 closed issues ([1][crypto.com-closed_issues-1], [2][crypto.com-closed_issues-2]), 
20 open issues ([1][crypto.com-open_issues-1], [2][crypto.com-open_issues-2])

[crypto.com-merged-prs-1]: https://github.com/crypto-com/chain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[crypto.com-merged-prs-2]: https://github.com/crypto-com/chain-nodelib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[crypto.com-merged-prs-3]: https://github.com/crypto-com/sample-chain-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[crypto.com-closed_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[crypto.com-closed_issues-2]: https://github.com/crypto-com/sample-chain-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[crypto.com-open_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01
[crypto.com-open_issues-2]: https://github.com/crypto-com/chain-nodelib/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: [Crypto.com Chain Dev Update #11](https://blog.crypto.com/crypto-com-chain-dev-update-11)
  - [Technical whitepaper](https://chain.crypto.com/chain_technical_whitepaper.pdf) and [General whitepaper](https://crypto.com/images/crypto_com_whitepaper.pdf) have been updated
  - Our [technical documentation site](https://chain.crypto.com/docs/getting-started/) is revamped along with our new [GitHub Activities page](https://chain.crypto.com/releases)
- News: [Microsoft Azure "one-click" Deployment](https://chain.crypto.com/docs/getting-started/thaler-testnet-azure-1click.html) is available to provide easy deployment option
- News: [Node.js Library](https://github.com/crypto-com/chain-nodelib) Available on NPM
- PR: [Problem: no tx-validation enclave attested TLS listener for receiving secrets from TDBE (fixes #1994)](https://github.com/crypto-com/chain/pull/2189) by [@tomtau](https://github.com/tomtau)
- PR: [Problem: Missing runner for TDBE + No persistence of TDBE fetched transactions](https://github.com/crypto-com/chain/pull/2177) by [@devashishdxt](https://github.com/devashishdxt)

#### [Holochain](https://github.com/holochain/)
1 merged PRs ([1][holochain-merged-prs-1]), 
0 closed issues, 
0 open issues

[holochain-merged-prs-1]: https://github.com/holochain/holochain-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01

- News: 
  - [Dev Pulse 78 - HoloFuel Progress Report](https://blog.holochain.org/holofuel-progress-report/)
  - [Dev Pulse 77 - Bugfix Releases Of Holochain & HoloFuel, Dev Community Keeps Getting Awesomer](https://blog.holochain.org/minor-bugfixes-in-holochain-and-holofuel/)
- Videos: 
  - [Hosted hApps - First Demo of a dApp Hosted on Holo](https://youtu.be/QNryquWbOVM)
  - [HoloPort Nano Demo](https://youtu.be/ctlShbwKQAw)
  - Holochain Ecosystem Sessions: 
    [hummHive](https://www.youtube.com/watch?v=NnoUCV7DUIk), 
    [Junto](https://youtu.be/XGFBEn-L614)
- PR: [fix for failed publish of authored entries](https://github.com/holochain/holochain-rust/pull/2206) by [@zippy](https://github.com/zippy)

#### [Libra](https://libra.org)

213 merged PRs ([1][libra-merged-prs-1]), 38 closed issues ([1][libra-closed_issues-1]), 
45 open issues ([1][libra-open_issues-1])

[libra-merged-prs-1]: https://github.com/libra/libra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: Testnet push announcement for 
  [08/26](https://community.libra.org/t/testnet-push-announcement-for-8-26/3095), 
  [08/20](https://community.libra.org/t/testnet-push-announcement-for-08-20/3081),
  [08/06](https://community.libra.org/t/testnet-push-annoucement-for-08-06/3058)
- PR: [[move-prover] Enhanced governance-related specs](https://github.com/libra/libra/pull/5810) by [@junkil-park](https://github.com/junkil-park)
- PR: [[network][handshake protocol] refactoring and implementing test/fuzzing](https://github.com/libra/libra/pull/5776) by [@mimoo](https://github.com/mimoo)
- PR: [[network] Random hardening](https://github.com/libra/libra/pull/5689) by [@davidiw](https://github.com/davidiw)
- PR: [[breaking][bugfix][vm] Charge gas for emit_event](https://github.com/libra/libra/pull/5719) by [@tzakian](https://github.com/tzakian)
- PR: [[network] [breaking] enable onchain and encryption and vector of addresses](https://github.com/libra/libra/pull/5731) by [@davidiw](https://github.com/davidiw)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

1 merged PRs ([1][lighthouse-merged-prs-1]), 40 closed issues ([1][lighthouse-closed_issues-1]), 
28 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: [Lighthouse Update #28](https://lighthouse.sigmaprime.io/update-28.html)
- Blog: [Setup Ethereum 2.0 Validator Node with Lighthouse on Meddala, Goerli](https://medium.com/coinmonks/how-to-setup-ethereum-2-0-validator-node-lighthouse-meddala-goerli-4f0b85d5c8f)
- PR: [[Merged by Bors] - Update score decay behaviour](https://github.com/sigp/lighthouse/pull/1442) by [@AgeManning](https://github.com/AgeManning)

#### [MobileCoin](https://www.mobilecoin.com/)
75 merged PRs ([1][mobilecoin-merged-prs-1]), 
0 closed issues, 
0 open issues 

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinofficial/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01

- PR: [MCC-959 side-channel resistant merkle proof validation](https://github.com/mobilecoinofficial/mobilecoin/pull/404) by [@garbageslam](https://github.com/garbageslam)
- PR: [Make slog actually work inside of sgx enclave/impl crates](https://github.com/mobilecoinofficial/mobilecoin/pull/358) by [@garbageslam](https://github.com/garbageslam)
- PR: [TxManager traits, mocks, and tests](https://github.com/mobilecoinofficial/mobilecoin/pull/346) by [@mfaulk](https://github.com/mfaulk)

#### [NEAR](https://github.com/nearprotocol/nearcore)

81 merged PRs ([1][near-merged-prs-1]), 60 closed issues ([1][near-closed_issues-1]), 
71 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[near-closed_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[near-open_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: 
  - [ETH-NEAR Rainbow Bridge](https://near.org/blog/eth-near-rainbow-bridge/)
  - [Hack the Rainbow 🌈 – NEAR’s first Massive Open Online Hackathon](https://near.org/blog/hack-the-rainbow-%f0%9f%8c%88-nears-first-massive-open-online-hackathon-aka-mooh/)
  - [Flux Has Arrived: Why The Time For Open Prediction Markets Starts Now](https://www.nearguilds.com/post/flux-has-arrived-why-the-time-for-decentralized-decision-markets-starts-now-by-4nts)
  - [Off to the Races: ZEST Launches on the NEAR Mainnet](https://near.org/blog/off-to-the-races-zest-launches-on-the-near-mainnet/)
  - [The NEAR Token Sale and Unforkable Community](https://near.org/blog/the-near-token-sale-and-unforkable-community/)
  - [Announcing NEAR Validator Advisory Board](https://near.org/blog/nvab/)
- News: Community Update
  - [ZEST & Flux on MainNet, Hack the Rainbow, EDU@NEAR](https://near.org/blog/community-update-zest-hack-the-rainbow/)
  - [Community Token Sale, Mintbase, Flux Phase 1.0, 🌈 Rainbow Bridge](https://near.org/blog/community-update-community-token-sale-mintbase-flux-phase-1-0-%f0%9f%8c%88-rainbow-bridge/)
- Blog: [The Rainbow Bridge: FAQs and Answers By 4NTS](https://www.nearguilds.com/post/the-rainbow-bridge-faqs-and-answers-by-4nts)  
- Blog: [A primer on Flux liquidity incentives](https://medium.com/@fluxmarket/a-primer-on-flux-liquidity-incentives-403696f72c60)
- Video: [Whitepaper Circle: Nightshade NEAR Protocol Sharding Design](https://www.youtube.com/watch?v=9Hdt3JcV5EM)
- PR: [feat: implement gas profiler.](https://github.com/nearprotocol/nearcore/pull/3038) by [@olonho](https://github.com/olonho)
- PR: [fix (runtime): Finishing adding wasmtime support](https://github.com/nearprotocol/nearcore/pull/3074) by [@willemneal](https://github.com/willemneal)
- PR: [fix(store): Fix refcount logic slowness](https://github.com/nearprotocol/nearcore/pull/3123) by [@mikhailOK](https://github.com/mikhailOK)
- PR: [feat(rosettarpc): Data API implementation](https://github.com/nearprotocol/nearcore/pull/2940) by [@frol](https://github.com/frol)
- PR: [feat(indexer): Extend the NEAR Indexer API with an ability to communicate the starting point of streaming](https://github.com/nearprotocol/nearcore/pull/3236) by [@khorolets](https://github.com/khorolets)
- PR: [feat(indexer): NEAR Indexer can init configs](https://github.com/nearprotocol/nearcore/pull/3082) by [@khorolets](https://github.com/khorolets)
- PR: [fix: Use both version and oldest_supported version](https://github.com/nearprotocol/nearcore/pull/3016) by [@mfornet](https://github.com/mfornet)
  <!-- ^ comments: 11 -->
- PR: [feat(client): Extended query to be able to refer to the genesis and the earliest [oldest] available blocks](https://github.com/nearprotocol/nearcore/pull/3127) by [@frol](https://github.com/frol)
  <!-- ^ comments: 10 -->
- PR: [fix(network): Verify edge on separate thread](https://github.com/nearprotocol/nearcore/pull/3145) by [@mfornet](https://github.com/mfornet)
  <!-- ^ comments: 10 -->
- PR: [fix(gc): address slowness in forks cleaning](https://github.com/nearprotocol/nearcore/pull/3121) by [@bowenwang1996](https://github.com/bowenwang1996)
  <!-- ^ comments: 9 -->
- PR: [fix(runtime-params-estimator): disable rocksdb thread in it](https://github.com/nearprotocol/nearcore/pull/3091) by [@ailisp](https://github.com/ailisp)
  <!-- ^ comments: 7 -->
- PR: [test: Various stress.py changes](https://github.com/nearprotocol/nearcore/pull/3189) by [@SkidanovAlex](https://github.com/SkidanovAlex)
  <!-- ^ comments: 6 -->
- PR: [fix: Properly handling stalls due to 1-height differences](https://github.com/nearprotocol/nearcore/pull/3175) by [@SkidanovAlex](https://github.com/SkidanovAlex)
  <!-- ^ comments: 5 -->
- PR: [feat: delay detector](https://github.com/nearprotocol/nearcore/pull/3126) by [@bowenwang1996](https://github.com/bowenwang1996)
  <!-- ^ comments: 5 -->
- PR: [fix: remove sync head](https://github.com/nearprotocol/nearcore/pull/3255) by [@bowenwang1996](https://github.com/bowenwang1996)
  <!-- ^ comments: 4 -->
- PR: [fix(network_drop_package): Process was starving](https://github.com/nearprotocol/nearcore/pull/3210) by [@mfornet](https://github.com/mfornet)
  <!-- ^ comments: 4 -->
- PR: [Revert "Revert "feat(store): Refcounted DB columns (#3215)" (#3226)" ](https://github.com/nearprotocol/nearcore/pull/3230) by [@mikhailOK](https://github.com/mikhailOK)
  <!-- ^ comments: 4 -->
- PR: [Refcounted DB columns](https://github.com/nearprotocol/nearcore/pull/3215) by [@mikhailOK](https://github.com/mikhailOK)
  <!-- ^ comments: 4 -->
- PR: [fix: skip signature verification in produce_chunk](https://github.com/nearprotocol/nearcore/pull/3224) by [@bowenwang1996](https://github.com/bowenwang1996)

#### [Nervos](https://github.com/nervosnetwork)

44 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]), 9 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
3 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[nervos-merged-prs-3]: https://github.com/nervosnetwork/rfcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: 
  - [Nervos CKB Development Update #39](https://medium.com/nervosnetwork/ckb-development-update-39-45b25b50abf2)
  - [Trail of Bits selected to audit Nervos’ smart contract security](https://medium.com/nervosnetwork/trail-of-bits-selected-to-audit-nervos-smart-contract-security-213e71a531c8)
  - [Nervos researcher Dr. Ren Zhang invited to join NDSS Special Committee of Blockchain Reviewers](https://medium.com/nervosnetwork/nervos-researcher-dr-ren-zhang-invited-to-join-ndss-special-committee-of-blockchain-reviewers-1db076b2fc7f)
  - [Want to deposit CKB into Nervos DAO via Ledger? Here’s how](https://medium.com/nervosnetwork/want-to-deposit-ckb-into-nervos-dao-via-ledger-heres-how-3382f120720)
  - [Crypto exchange HitBTC lists Nervos CKB for trading](https://medium.com/nervosnetwork/crypto-exchange-hitbtc-lists-nervos-ckb-for-trading-5dc9e1a951aa)
  - [The Nervos community releases new development tools for BSN integration](https://medium.com/nervosnetwork/nervos-community-releases-development-tools-supporting-bsn-promoting-a-new-experience-of-bsn-414dc914a677)
  - [Nervos Integrates Band Protocol to Bring Scalable Oracle Technology & Extensive Real-World Data To DApps](https://medium.com/nervosnetwork/nervos-begins-integration-with-band-protocol-4d173dec9eb1)
  - [Integrating Chainlink’s Widely Used Oracles into Nervos to Secure Off-Chain Connectivity](https://medium.com/nervosnetwork/integrating-chainlinks-oracles-into-nervos-to-secure-off-chain-connectivity-3ceef863bdfa)
  - [Portal Wallet: Enabling CKB to connect with wallets around the world](https://medium.com/@nervosnetwork/portal-wallet-launches-on-nervos-423c86618133)
  - [Nervos Quarterly Letter: Updates & Highlights from Q2](https://medium.com/nervosnetwork/nervos-quarterly-letter-updates-highlights-from-q2-d226023c59b8)
  - [Nervos approves Obsidian Labs grant for Windows and browser-based IDE](https://medium.com/nervosnetwork/nervos-approves-obsidian-labs-grant-for-windows-and-browser-based-ide-bbb7053eda18)
  - [How Tocial plans to help cosplayers monetize with Nervos’ help](https://medium.com/nervosnetwork/how-tocial-helps-cosplayers-monetize-with-nervos-help-94f64eeda125)
  - [Grin Community Collaboration to Bring Mimblewimble to Nervos](https://medium.com/nervosnetwork/grin-community-collaboration-to-bring-mimblewimble-to-nervos-4a663df26f60)
  - [Nervos Community Update: July 2020](https://medium.com/nervosnetwork/nervos-community-update-july-2020-f9232aa71dd0)
- News: CKB Weekly [16](https://ckbweekly.substack.com/p/github-decentralized),
  [15](https://ckbweekly.substack.com/p/failed-transactions-still-charge),
  [14](https://ckbweekly.substack.com/p/migrating-web-20-users-to-web-30)
- Blog: [Nervos Episode IV — A New Hope (for DeFi)](https://medium.com/nervosnetwork/nervos-epsiode-iv-a-new-hope-for-defi-e6b1ce1bf04f)
- Video: 
  - Dapps with CKB Workshop | Lecture [4](https://www.youtube.com/watch?v=9U23hrzCAiM),
  [3-2](https://www.youtube.com/watch?v=TJ2bnSFUpPQ),
  [3-1](https://www.youtube.com/watch?v=7ob-WL1eWrQ),
  [2](https://www.youtube.com/watch?v=NcN3NiBuJbo),
  [1-2](https://www.youtube.com/watch?v=iVjccs3z5q0),
  [1-1](https://www.youtube.com/watch?v=6nYyYikSZj0)
  - [PW-Core Programming Walkthrough](https://www.youtube.com/watch?v=E2AYuRaeP9Q)  
  - [How to Develop a CKB DApp with Keypering (Chinese + English Subtitles)](https://www.youtube.com/watch?v=i-gQ0enK5cY)
  - [CKB Studio Tutorial](https://www.youtube.com/watch?v=lOxXrVIfT2Y)
  - [Understanding the Token Sale Lock Script](https://www.youtube.com/watch?v=ysUbx4FAKlE)
- PR: [Feat: lazy initialization memory](https://github.com/nervosnetwork/ckb-vm/pull/107) by [@mohanson](https://github.com/mohanson)
- PR: [feat: add metrics service](https://github.com/nervosnetwork/ckb/pull/2199) by [@yangby-cryptape](https://github.com/yangby-cryptape)
  <!-- ^ comments: 16 -->
- PR: [feat: add more fields to rpc `get_peers`](https://github.com/nervosnetwork/ckb/pull/2196) by [@quake](https://github.com/quake)
  <!-- ^ comments: 7 -->
- PR: [refactor: Rewrite ping](https://github.com/nervosnetwork/ckb/pull/2229) by [@driftluo](https://github.com/driftluo)
  <!-- ^ comments: 4 -->
- PR: [feat: support to control memory usage for header map](https://github.com/nervosnetwork/ckb/pull/2239) by [@yangby-cryptape](https://github.com/yangby-cryptape)
  <!-- ^ comments: 4 -->
- PR: [Introduce version and fix various bugs](https://github.com/nervosnetwork/ckb-vm/pull/99) by [@xxuejie](https://github.com/xxuejie)
  <!-- ^ comments: 4 -->
- PR: [refactor: replace logs by metrics for memory tracker](https://github.com/nervosnetwork/ckb/pull/2201) by [@yangby-cryptape](https://github.com/yangby-cryptape)

#### [Oasis](https://github.com/oasislabs)

3 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2]), 
0 closed issues, 
0 open issues

[oasis-merged-prs-1]: https://github.com/oasislabs/oasis-ethwasi-runtime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[oasis-merged-prs-2]: https://github.com/oasislabs/oasis-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01

- News: 
  - [The Biggest University Program on a Layer 1 Network Just Launched on the Oasis Network](https://medium.com/oasis-protocol-project/the-biggest-university-program-on-a-blockchain-network-just-launched-on-the-oasis-network-2a3c3a0dec1d)
  - [Oasis Labs Joins Forces with Binance to Launch CryptoSafe Alliance and Decentralized Platform for Combatting Crypto Fraud](https://medium.com/oasislabs/oasis-labs-joins-forces-with-binance-to-launch-cryptosafe-alliance-and-decentralized-platform-for-db3efa182e37)
- Blog: [Programming Data and Money: The Data Market Yield](https://medium.com/oasis-protocol-project/programming-data-and-money-the-data-market-yield-ad27a8b35c10). 
  How the Oasis Network can enable not just programmable money — like other blockchains — but tokenized data that can help users be fairly compensated for their data and personal information.
- Blog: [The Journey of a Transaction](https://medium.com/oasis-protocol-project/the-journey-of-a-transaction-ad85a94d0a5b). 
  A story illustrating how transactions are processed by the Oasis Network, and how it's first-of-its-kind design allows data to remain confidential, private, and highly available on the network.
- Blog: [The Internet’s Untapped Potential](https://medium.com/oasis-protocol-project/the-internets-untapped-potential-4d16b5107a50)
  The Oasis Foundation's proposal for a new ethos for digital stewardship, 
  and how with the right technology and the right guiding principles, 
  we can create a society that handles data and individuals rights more responsibly.

- PR: [Add custom section with version info to WASM](https://github.com/oasislabs/oasis-cli/pull/159) by [@mitjat](https://github.com/mitjat)
  <!-- ^ comments: 7 -->
- PR: [revert testing commit](https://github.com/oasislabs/oasis-ethwasi-runtime/pull/1009) by [@ptrus](https://github.com/ptrus)
- PR: [Update to oasis-core 20.9](https://github.com/oasislabs/oasis-ethwasi-runtime/pull/1008) by [@ptrus](https://github.com/ptrus)

<!-- total GitHub calls: 15, new GitHub calls: 15 -->


#### [Parity](https://github.com/paritytech)

204 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]), 95 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2]), 
85 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[parity-merged-prs-3]: https://github.com/paritytech/parity-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01
[parity-open_issues-3]: https://github.com/paritytech/parity-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News:
  - [Polkascan Development Update #7](https://medium.com/polkadot-network/polkascan-development-update-7-36b5f814dc8b)
  - [GRANDPA Equivocation and sysinfo Process Collection Results In Slashing on Kusama Network: a Post-Mortem.](https://polkadot.network/grandpa-equivocation-and-sysinfo-process-collection-results-in-slashing-on-kusama-network-a-post-mortem/)
  - [Transferability and Redenomination Public Notice](https://polkadot.network/transferability-and-redenomination-public-notice/)
  - [Denomination Day: Ecosystem Project Guidance](https://polkadot.network/denomination-day-ecosystem-project-guidance/)
  - [Introducing Rococo: Polkadot’s Parachain Testnet](https://polkadot.network/introducing-rococo-polkadots-parachain-testnet/)
- Videos:
  - [Picking Validators to Nominate (Stake) in Polkadot](https://www.youtube.com/watch?v=ZMzhM1m4I-k)
  - [Polkadot Redenomination](https://www.youtube.com/watch?v=xXIcnBV4uUE)
  - Hackusama Webinar Series: 
    [Week 6 | Status update, Parachain Economics, WanXiang](https://www.youtube.com/watch?v=7uW2L-ojtTM),
    [Week 5 | Status update, Account Primitives, DoraHacks, PolkaBase](https://www.youtube.com/watch?v=6Eik4TPC2iw)
- PR: [Merge Subkey into sc-cli](https://github.com/paritytech/substrate/pull/4954) by [@seunlanlege](https://github.com/seunlanlege)
  <!-- ^ comments: 199 -->
- PR: [Initial guide text for approvals and especially approvals assignments ](https://github.com/paritytech/polkadot/pull/1518) by [@burdges](https://github.com/burdges)
  <!-- ^ comments: 93 -->
- PR: [impl availability distribution](https://github.com/paritytech/polkadot/pull/1460) by [@drahnr](https://github.com/drahnr)
  <!-- ^ comments: 93 -->
- PR: [Implement request-responses protocols](https://github.com/paritytech/substrate/pull/6634) by [@tomaka](https://github.com/tomaka)
  <!-- ^ comments: 68 -->
- PR: [Add Subscription RPC for Grandpa Finality](https://github.com/paritytech/substrate/pull/5732) by [@HCastano](https://github.com/HCastano)
  <!-- ^ comments: 64 -->
- PR: [Add a `LightSyncState` field to the chain spec](https://github.com/paritytech/substrate/pull/6894) by [@expenses](https://github.com/expenses)
  <!-- ^ comments: 62 -->
- PR: [Add a DirectedGossip struct](https://github.com/paritytech/substrate/pull/6803) by [@tomaka](https://github.com/tomaka)
  <!-- ^ comments: 48 -->
- PR: [implement provisioner](https://github.com/paritytech/polkadot/pull/1473) by [@coriolinus](https://github.com/coriolinus)
  <!-- ^ comments: 47 -->
- PR: [Add async test helper to timeout and provide a task_executor automatically](https://github.com/paritytech/substrate/pull/6651) by [@cecton](https://github.com/cecton)
  <!-- ^ comments: 45 -->
- PR: [Implementer's guide: downward messages and HRMP, take 2](https://github.com/paritytech/polkadot/pull/1503) by [@pepyakin](https://github.com/pepyakin)
  <!-- ^ comments: 37 -->
- PR: [Implementer's Guide: Flesh out more details for upward messages](https://github.com/paritytech/polkadot/pull/1556) by [@pepyakin](https://github.com/pepyakin)
  <!-- ^ comments: 30 -->
- PR: [implement collation generation subsystem](https://github.com/paritytech/polkadot/pull/1557) by [@coriolinus](https://github.com/coriolinus)
  <!-- ^ comments: 29 -->
- PR: [seal: Fix and improve error reporting](https://github.com/paritytech/substrate/pull/6773) by [@athei](https://github.com/athei)
  <!-- ^ comments: 27 -->
- PR: [RpcHandlers Refactorings](https://github.com/paritytech/substrate/pull/6846) by [@seunlanlege](https://github.com/seunlanlege)
  <!-- ^ comments: 25 -->
- PR: [Add RPC Builder to Substrate Node Template](https://github.com/paritytech/substrate/pull/6808) by [@Meuko](https://github.com/Meuko)
  <!-- ^ comments: 25 -->
- PR: [initial prometheus metrics](https://github.com/paritytech/polkadot/pull/1536) by [@ordian](https://github.com/ordian)
  <!-- ^ comments: 24 -->
- PR: [Implementer's Guide: Incorporate HRMP to TransientValidationData ](https://github.com/paritytech/polkadot/pull/1588) by [@pepyakin](https://github.com/pepyakin)
  <!-- ^ comments: 23 -->
- PR: [Dynamic Benchmarking DB Whitelist](https://github.com/paritytech/substrate/pull/6815) by [@shawntabrizi](https://github.com/shawntabrizi)
  <!-- ^ comments: 19 -->
- PR: [guide: validation data refactoring](https://github.com/paritytech/polkadot/pull/1576) by [@rphmeier](https://github.com/rphmeier)
  <!-- ^ comments: 18 -->
- PR: [Update to libp2p-0.23.](https://github.com/paritytech/substrate/pull/6870) by [@romanb](https://github.com/romanb)
  <!-- ^ comments: 17 -->
- PR: [proposer: wait for a hash to be in the active-leaves set](https://github.com/paritytech/polkadot/pull/1616) by [@ordian](https://github.com/ordian)
  <!-- ^ comments: 16 -->
- PR: [Improve Benchmark Writer: Remove Unused Components, Remove Multiply by Zero, Files Split by Pallet](https://github.com/paritytech/substrate/pull/6785) by [@shawntabrizi](https://github.com/shawntabrizi)
  <!-- ^ comments: 14 -->
- PR: [add generated weight info for pallet-collective](https://github.com/paritytech/substrate/pull/6789) by [@apopiak](https://github.com/apopiak)
  <!-- ^ comments: 13 -->
- PR: [Custom Codec Implementation for NPoS Election](https://github.com/paritytech/substrate/pull/6720) by [@kianenigma](https://github.com/kianenigma)
  <!-- ^ comments: 13 -->
- PR: [Add release checklist](https://github.com/paritytech/polkadot/pull/1316) by [@shawntabrizi](https://github.com/shawntabrizi)
  <!-- ^ comments: 13 -->
- PR: [Network bridge refactoring impl](https://github.com/paritytech/polkadot/pull/1537) by [@rphmeier](https://github.com/rphmeier)
  <!-- ^ comments: 13 -->
- PR: [Add SyncOracle to network's Service](https://github.com/paritytech/polkadot/pull/1543) by [@cecton](https://github.com/cecton)
  <!-- ^ comments: 13 -->
- PR: [Companion PR for `Move subcommands from sc-cli to nodes #6948 `](https://github.com/paritytech/polkadot/pull/1635) by [@expenses](https://github.com/expenses)
  <!-- ^ comments: 12 -->
- PR: [Implement validation data refactor](https://github.com/paritytech/polkadot/pull/1585) by [@rphmeier](https://github.com/rphmeier)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

63 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 42 closed issues ([1][secret_network-closed_issues-1], [2][secret_network-closed_issues-2]), 
12 open issues ([1][secret_network-open_issues-1], [2][secret_network-open_issues-2])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[secret_network-merged-prs-2]: https://github.com/enigmampc/SafeTrace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[secret_network-closed_issues-2]: https://github.com/enigmampc/SafeTrace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01
[secret_network-open_issues-2]: https://github.com/enigmampc/SafeTrace/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: 
  - [The Secret is Out: Announcing the Secret Contracts Mainnet!](https://blog.scrt.network/secret-contracts-mainnet/)
  - [Secret Games Update: Incentivized Testnet Phase 2](https://blog.scrt.network/secret-games-update-incentivized-testnet-phase-2/)
- Blog: [Secret Staking Derivatives: Liquidity Meets Privacy](https://blog.scrt.network/secret-staking-derivatives/)
- Blog: [Secret Tokens: Programmable Privacy for DeFi](https://blog.scrt.network/secret-tokens-programmable-privacy-for-defi/)
- PR: [Verification of msg.sender](https://github.com/enigmampc/SecretNetwork/pull/413) by [@toml01](https://github.com/toml01)
  <!-- ^ comments: 66 -->
- PR: [New and improved input validation](https://github.com/enigmampc/SecretNetwork/pull/419) by [@Cashmaney](https://github.com/Cashmaney)
  <!-- ^ comments: 65 -->
- PR: [CosmWasm v0.10](https://github.com/enigmampc/SecretNetwork/pull/477) by [@reuvenpo](https://github.com/reuvenpo)
  <!-- ^ comments: 32 -->
- PR: [Refactor output encryption](https://github.com/enigmampc/SecretNetwork/pull/445) by [@toml01](https://github.com/toml01)
  <!-- ^ comments: 23 -->
- PR: [Attestation advisories](https://github.com/enigmampc/SecretNetwork/pull/484) by [@Cashmaney](https://github.com/Cashmaney)
  <!-- ^ comments: 18 -->
- PR: [Secret-secret cli](https://github.com/enigmampc/SecretNetwork/pull/495) by [@Cashmaney](https://github.com/Cashmaney)
  <!-- ^ comments: 15 -->
- PR: [WIP: Gov querier & handler + TESTS](https://github.com/enigmampc/SecretNetwork/pull/498) by [@Cashmaney](https://github.com/Cashmaney)
  <!-- ^ comments: 15 -->
- PR: [Platform info](https://github.com/enigmampc/SecretNetwork/pull/448) by [@Cashmaney](https://github.com/Cashmaney)
  <!-- ^ comments: 11 -->
- PR: [Parameter verification fixes](https://github.com/enigmampc/SecretNetwork/pull/494) by [@toml01](https://github.com/toml01)
  <!-- ^ comments: 9 -->
- PR: [Fixed secretd/cli version in testnet builds](https://github.com/enigmampc/SecretNetwork/pull/492) by [@Cashmaney](https://github.com/Cashmaney)
  <!-- ^ comments: 6 -->
- PR: [Enclave tests](https://github.com/enigmampc/SecretNetwork/pull/431) by [@reuvenpo](https://github.com/reuvenpo)
  <!-- ^ comments: 5 -->
- PR: [Update azuredeploy.json](https://github.com/enigmampc/SecretNetwork/pull/435) by [@Cashmaney](https://github.com/Cashmaney)
  <!-- ^ comments: 5 -->
- PR: [Make query gas limit configurable for nodes](https://github.com/enigmampc/SecretNetwork/pull/437) by [@assafmo](https://github.com/assafmo)

#### [Solana](https://github.com/solana-labs/solana)

271 merged PRs ([1][solana-merged-prs-1]), 20 closed issues ([1][solana-closed_issues-1]), 
52 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: [Coinbase Custody Now Supports Solana](https://medium.com/solana-labs/coinbase-custody-now-supports-solana-7e3ca5fb4713)
- Video: [The Future of DeFi](https://www.youtube.com/watch?v=UpaHUb-Lf-0)
- Podcast: [Justin Drake - Ethereum 2.0 Researcher Ep #25](https://podcast.solana.com/episodes/justin-drake-ethereum-20-researcher-ep-25)
- Podcast: [Sam Bankman-Fried - CEO of FTX, Co-founder of Serum Ep #24](https://podcast.solana.com/episodes/sam-bankman-fried-ceo-of-ftx-co-founder-of-serum-ep-24)
- PR: [Switch programs activation to whole-set based gating](https://github.com/solana-labs/solana/pull/11750) by [@jackcmay](https://github.com/jackcmay)
  <!-- ^ comments: 22 -->
- PR: [Return token amounts as floats](https://github.com/solana-labs/solana/pull/11370) by [@CriesofCarrots](https://github.com/CriesofCarrots)
  <!-- ^ comments: 17 -->
- PR: [Decode native-program and sysvar accounts](https://github.com/solana-labs/solana/pull/11463) by [@CriesofCarrots](https://github.com/CriesofCarrots)
  <!-- ^ comments: 15 -->
- PR: [Ensure that the spl-token 2 native mint account is owned by the spl-token 2 program](https://github.com/solana-labs/solana/pull/11966) by [@mvines](https://github.com/mvines)
  <!-- ^ comments: 14 -->
- PR: [explorer: Auto-update transactions until they reach max confirmation](https://github.com/solana-labs/solana/pull/11841) by [@oJshua](https://github.com/oJshua)
  <!-- ^ comments: 14 -->
- PR: [Submit a vote timestamp every vote](https://github.com/solana-labs/solana/pull/10630) by [@mvines](https://github.com/mvines)
  <!-- ^ comments: 14 -->
- PR: [Add StakeInstruction::AuthorizeWithSeed](https://github.com/solana-labs/solana/pull/11700) by [@garious](https://github.com/garious)
  <!-- ^ comments: 11 -->
- PR: [Update instruction encoding format](https://github.com/solana-labs/solana/pull/11363) by [@CriesofCarrots](https://github.com/CriesofCarrots)
  <!-- ^ comments: 6 -->
- PR: [Add tests for the Debug and activation Vecs](https://github.com/solana-labs/solana/pull/11926) by [@ryoqun](https://github.com/ryoqun)
  <!-- ^ comments: 6 -->
- PR: [Update epoch gating](https://github.com/solana-labs/solana/pull/11880) by [@jackcmay](https://github.com/jackcmay)
  <!-- ^ comments: 6 -->
- PR: [Add SystemInstruction::CreateAccount support to CPI](https://github.com/solana-labs/solana/pull/11649) by [@jackcmay](https://github.com/jackcmay)
  <!-- ^ comments: 5 -->
- PR: [Vote timestamp may equal previous timestamp](https://github.com/solana-labs/solana/pull/11715) by [@CriesofCarrots](https://github.com/CriesofCarrots)

#### [Zcash](https://z.cash/)

120 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 88 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
45 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-08-01..2020-09-01
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[zcash-closed_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-08-01..2020-09-01
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01
[zcash-open_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aopen+created%3A2020-08-01..2020-09-01

- News: 
  - [ECC releases code for Halo 2](https://electriccoin.co/blog/ecc-releases-code-for-halo-2/)
  - [Explaining Halo 2](https://electriccoin.co/blog/explaining-halo-2/)
  - [Luxor mines the first shielded coinbase](https://electriccoin.co/blog/luxor-mines-the-first-shielded-coinbase/)
  - [Celebrating Canopy and Community](https://electriccoin.co/blog/celebrating-canopy-and-community/)
  - [Zcash Foundation Obligations to ZIP1014 and the MGRC](https://www.zfnd.org/blog/zf-mgrc-obligations/)
  - [August 18 Community Call on MGRC Structure](https://www.zfnd.org/blog/mgrc-community-call-august-2020/)
  - [Expanding Membership to the Zcash Community Advisory Panel](https://www.zfnd.org/blog/expanding-cap/)
- Report: [Zcash Network Privacy: An Assessment of Current State and Future Work.](https://www.zfnd.org/blog/zf-network-privacy-assessment/)
- PR: [Notes, commitments, nullifiers, etc](https://github.com/ZcashFoundation/zebra/pull/596) by [@yaahc](https://github.com/yaahc)
- PR: [ZIP212 implementation](https://github.com/zcash/librustzcash/pull/258) by [@therealyingtong](https://github.com/therealyingtong)
- PR: [rfc: Parallel Verification](https://github.com/ZcashFoundation/zebra/pull/763) by [@teor2345](https://github.com/teor2345)
  <!-- ^ comments: 72 -->
- PR: [ZIP400 - informational wallet db format](https://github.com/zcash/zips/pull/372) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 57 -->
- PR: [Implement group and pairing traits for bls12_381 and jubjub crates](https://github.com/zcash/librustzcash/pull/245) by [@str4d](https://github.com/str4d)
  <!-- ^ comments: 50 -->
- PR: [Setup tracing-flame for use profiling zebrad](https://github.com/ZcashFoundation/zebra/pull/436) by [@yaahc](https://github.com/yaahc)
  <!-- ^ comments: 47 -->
- PR: [Command execution tests](https://github.com/ZcashFoundation/zebra/pull/690) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 42 -->
- PR: [zebra-state: Add support for temporary sled databases](https://github.com/ZcashFoundation/zebra/pull/939) by [@vramana](https://github.com/vramana)
  <!-- ^ comments: 40 -->
- PR: [Implement Inventory Tracking RFC](https://github.com/ZcashFoundation/zebra/pull/963) by [@yaahc](https://github.com/yaahc)
  <!-- ^ comments: 37 -->
- PR: [Add async script RFC](https://github.com/ZcashFoundation/zebra/pull/868) by [@hdevalence](https://github.com/hdevalence)
  <!-- ^ comments: 27 -->
- PR: [Migrate to bls12_381 and jubjub crates](https://github.com/zcash/librustzcash/pull/272) by [@str4d](https://github.com/str4d)
  <!-- ^ comments: 27 -->
- PR: [Remove in-memory state service](https://github.com/ZcashFoundation/zebra/pull/974) by [@yaahc](https://github.com/yaahc)
  <!-- ^ comments: 24 -->
- PR: [Valid generated config acceptance test](https://github.com/ZcashFoundation/zebra/pull/859) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 24 -->
- PR: [feature: Implement CompactDifficulty to Work](https://github.com/ZcashFoundation/zebra/pull/838) by [@teor2345](https://github.com/teor2345)
  <!-- ^ comments: 24 -->
- PR: [Make zebra-script wrap the C++ script implementation in zcashconsensus](https://github.com/ZcashFoundation/zebra/pull/708) by [@yaahc](https://github.com/yaahc)
  <!-- ^ comments: 22 -->
- PR: [Use transcript in consensus chain tests](https://github.com/ZcashFoundation/zebra/pull/858) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 18 -->
- PR: [Use transcripts in block verify tests](https://github.com/ZcashFoundation/zebra/pull/675) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 17 -->
- PR: [Implement Add for Work](https://github.com/ZcashFoundation/zebra/pull/894) by [@teor2345](https://github.com/teor2345)
  <!-- ^ comments: 16 -->
- PR: [Make sync ignore known hashes](https://github.com/ZcashFoundation/zebra/pull/853) by [@teor2345](https://github.com/teor2345)
  <!-- ^ comments: 16 -->
- PR: [Update sha2@0.9.1](https://github.com/ZcashFoundation/zebra/pull/938) by [@vramana](https://github.com/vramana)
  <!-- ^ comments: 15 -->
- PR: [Refactor acceptance serialized_tests](https://github.com/ZcashFoundation/zebra/pull/920) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 15 -->
- PR: [Bytes read and bytes written metrics](https://github.com/ZcashFoundation/zebra/pull/901) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 15 -->
- PR: [Fix sync algorithm.](https://github.com/ZcashFoundation/zebra/pull/887) by [@hdevalence](https://github.com/hdevalence)
  <!-- ^ comments: 15 -->
- PR: [Remove environment variables in favor of documented config options.](https://github.com/ZcashFoundation/zebra/pull/827) by [@hdevalence](https://github.com/hdevalence)
  <!-- ^ comments: 14 -->
- PR: [Make more checks in non server acceptance tests](https://github.com/ZcashFoundation/zebra/pull/860) by [@oxarbitrage](https://github.com/oxarbitrage)
  <!-- ^ comments: 11 -->
- PR: [bellman: add VerificationError](https://github.com/zcash/librustzcash/pull/254) by [@hdevalence](https://github.com/hdevalence)

&nbsp;

## Events

Sep 7-27 | Online

[Chainlink Hackathon](https://hack.chain.link/)

Sep 15-16 | Online

[Crypto Privacy Conference](https://fcatalyst.com/events/sept2020/crypto_privacy_conference)

Sep 15-30 | Online

[NEAR Hackathon: Hack The Rainbow](https://near.org/rainbow/)

Sep 17-18 | Surrey, UK

[4th International Workshop on Cryptocurrencies and Blockchain Technology - CBT 2020](https://deic-web.uab.cat/cbt/cbt2020/)

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

Casper Labs | Remote
- [Core Engineer: dApp Development](https://apply.workable.com/casperlabs/j/F9076101B3/)
- [Rust Core Engineer](https://apply.workable.com/casperlabs/j/85A300F063/)

Findora | Beijing, China; Menlo Park, CA, US
- [Cryptography Engineer](https://jobs.lever.co/findora/082d76ed-3371-4374-b5f5-25be99df2bdb)
- [Director of Engineering](https://jobs.lever.co/findora/d1981ece-fb53-4b41-96d9-346b1974a7d8)
- [Senior Systems Engineer](https://jobs.lever.co/findora/e89e2e02-622c-41da-a14d-c12d854a25b5)
 
Moonbeam | Boston, MA USA; Madrid, Spain; Remote
- [Senior Blockchain Engineer](https://www.purestake.com/about/careers/openings/?jobId=d2VA-4HA7Iw6)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#16 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**

