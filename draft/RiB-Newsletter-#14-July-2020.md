#Rust in Blockchain Newsletter #14 -- July, 2020

Welcome to the #14 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #13](/newsletters/2020-07-01-stuck-inside-hacking-away/).

We published a late [one-year anniversary blog post][anniv].
It has some reflection on the changes to, and growth of, RiB over the last year.

[anniv]: https://rustinblockchain.org/blogposts/2020-07-30-rib-is-one-year-old/

The [Awesome Blockchain Rust][abr] project,
which is maintained by [@sunhuachuang] under the [rust-in-blockchain GitHub org][riborg],
has received a stream of updates recently,
and is now published [as a page on rustinblockchain.org][abr-rib].

It's a pretty good resource for finding blockchain-related Rust projects,
with links to many of the more prominant and mature projects noted in the RiB newsletter.
It could use more eyes on it though.

[abr]: https://github.com/rust-in-blockchain/awesome-blockchain-rust
[riborg]: https://github.com/rust-in-blockchain/awesome-blockchain-rust
[@sunhuachuang]: https://github.com/sunhuachuang
[abr-rib]: https://rustinblockchain.org/awesome-blockchain-rust/


&nbsp;

## Thanks

This edition of RiB was produced with contributions from [Calvin Lau][contributorcl],[Darosior][contributorda], [EnforSys][contributorenforsys], Paulii Good, [Sol][contributorsol],[Tony Arcieri][contributorta], [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

Also, [Awesome-RiB][awesome-rib] has been updated. Thanks to the awesome contributors: [Alfredo Garcia][contributorag], [Andy Nogueira][contributoran], [ChainSafe Systems][contributorchain], [Lane Rettig][contributorlr], [Michael Sproul][contributorms]!

RiB needs help to keep up with Rust blockchain projects. If you follow a particular project, or otherwise find information that is beneficial to the Rust & blockchain community, please contribute to the next issue. Either submit a PR to the [#15 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[awesome-rib]: https://github.com/rust-in-blockchain/awesome-blockchain-rust
[contributorcl]: https://github.com/calvinlauco
[contributorda]: https://github.com/darosior
[contributorenforsys]: https://twitter.com/SysEnfor
[contributorsol]: https://twitter.com/Sol68635937
[contributorta]: https://github.com/tarcieri
[contributoran]: https://github.com/andynog
[contributorag]: https://github.com/oxarbitrage
[contributorchain]: https://github.com/ChainSafeSystems
[contributorlr]: https://github.com/lrettig
[contributorms]: https://github.com/michaelsproul
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[ethers.rs]

`ethers.rs` is an Ethereum &amp; [Celo] library and wallet implementation,
implemented as a port of the [ethers.js] library to Rust.

Ethereum client programming is usually done in JavaScript with either [web3.js] or [ethers.js],
with ethers.js being the newer of the two.
These clients communicate to an Ethereum node, typically via JSON-RPC
(or, when in the browser, via an "injected" client provider that follows [EIP-1193], like [MetaMask]).

`ethers.rs` then provides a strongly-typed alternative for
writing software that interacts with the Ethereum network.

As of now it is only suited for non-browser use cases,
but if you prefer hacking in Rust to JavaScript,
as some of us surely do,
it is worth looking into for your next Ethereum project.

The author of `ethers.rs`, [@gakonst],
[accepts donations][ethers-donate] to sponsor work on `ethers.rs`.

Note that there is also a Rust alternative to web3.js, [rust-web3].

[MetaMask]: https://metamask.io/
[EIP-1193]: https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1193.md
[ethers.rs]: https://github.com/gakonst/ethers-rs
[Celo]: https://github.com/celo-org/celo-blockchain
[ethers.js]: https://docs.ethers.io/v5/
[web3.js]: https://web3js.readthedocs.io/
[rust-web3]: https://github.com/tomusdrw/rust-web3/
[@gakonst]: https://github.com/gakonst
[ethers-donate]: https://twitter.com/gakonst/status/1278216215345889286

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

152 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3], [4][comit-merged-prs-4]), 22 closed issues ([1][comit-closed_issues-1], [2][comit-closed_issues-2], [3][comit-closed_issues-3], [4][comit-closed_issues-4]), 
8 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2], [3][comit-open_issues-3])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[comit-merged-prs-2]: https://github.com/comit-network/comit-js-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[comit-merged-prs-3]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[comit-merged-prs-4]: https://github.com/comit-network/comit.network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[comit-closed_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[comit-closed_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[comit-closed_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[comit-closed_issues-4]: https://github.com/comit-network/comit.network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[comit-open_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[comit-open_issues-2]: https://github.com/comit-network/comit-js-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[comit-open_issues-3]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04


- PR: [Add request/response take order NB](https://github.com/comit-network/comit-rs/pull/2938) by [@tcharding](https://github.com/tcharding)
- PR: [Enable cnd to run over Tor](https://github.com/comit-network/comit-rs/pull/2917) by [@tcharding](https://github.com/tcharding)
- PR: [Add configurable ledger to ordebook](https://github.com/comit-network/comit-rs/pull/2952) by [@tcharding](https://github.com/tcharding)

#### [Crypto.com Chain](https://chain.crypto.com)

118 merged PRs ([1][crypto.com-merged-prs-1], [2][crypto.com-merged-prs-2], [3][crypto.com-merged-prs-3]), 89 closed issues ([1][crypto.com-closed_issues-1]), 
33 open issues ([1][crypto.com-open_issues-1], [2][crypto.com-open_issues-2])

[crypto.com-merged-prs-1]: https://github.com/crypto-com/chain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[crypto.com-merged-prs-2]: https://github.com/crypto-com/chain-nodelib/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[crypto.com-merged-prs-3]: https://github.com/crypto-com/sample-chain-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[crypto.com-closed_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[crypto.com-open_issues-1]: https://github.com/crypto-com/chain/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[crypto.com-open_issues-2]: https://github.com/crypto-com/chain-nodelib/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- News: [Crypto.com Chain Dev Update #10](https://blog.crypto.com/crypto-com-chain-dev-update-10)
  - Open sourcing [Chain Indexing Service](https://github.com/crypto-com/chain-index). It can index on chain data into structured records for query.
  - [Successfully complied chain core written in Rust into WebAssembly](https://github.com/crypto-com/chain/blob/master/chain-core/BUILD-WASM.md).
- News: Released Thaler Testnet [Block Explorer 2.0](https://chain.crypto.com/explorer) and [Faucet](https://chain.crypto.com/faucet)
- News: Revamped [Chain Website](https://chain.crypto.com) with brand new [Products and Releases Page](https://chain.crypto.com/releases) for developers engagement.
- News: [Node.js library](https://github.com/crypto-com/chain-nodelib) supports latest Testnet
- Promotion: [Calling for validators and staking pools to join Crypto.com Thaler Testnet](https://twitter.com/cryptocom/status/1276424962186735616?s=20).
- PR: [Problem (Fix #2040): mls implementation not up with latest spec draft](https://github.com/crypto-com/chain/pull/2059) by [@yihuang](https://github.com/yihuang)
- PR: [Problem: Transaction builder is accepting unnecessary data](https://github.com/crypto-com/chain-nodelib/pull/208) by [@calvinlauco](https://github.com/calvinlauco)

#### [Holochain](https://github.com/holochain/)

5 merged PRs ([1][holochain-merged-prs-1]), 0 closed issues (), 
0 open issues ()

[holochain-merged-prs-1]: https://github.com/holochain/holochain-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04

- News: Dev Pulse [76](https://blog.holochain.org/speedy-improved-holochain-release-unblocks-all-the-things/), [75](https://blog.holochain.org/holofuel-enters-community-testing-phase/)
- News: [The Host Release of HoloFuel](https://medium.com/h-o-l-o/the-host-release-of-holofuel-6fc36003e373)
- News: [Monthly Roundup for Holo & Holochain](https://medium.com/h-o-l-o/monthly-roundup-for-holo-holochain-18cb9f69c5df)
- Blog: [Mutual Credit, Part 1: A New Type of Cryptocurrency, As Old As Civilisation](https://blog.holochain.org/mutual-credit-part-1-a-new-type-of-cryptocurrency-as-old-as-civilisation/)
- PR: [Validation timeout fixes](https://github.com/holochain/holochain-rust/pull/2199) by [@zippy](https://github.com/zippy)
- PR: [Cache validation packages](https://github.com/holochain/holochain-rust/pull/2202) by [@zippy](https://github.com/zippy)

#### [Libra](https://libra.org)

30 merged PRs ([1][libra-merged-prs-1]), 26 closed issues ([1][libra-closed_issues-1]), 
55 open issues ([1][libra-open_issues-1])

[libra-merged-prs-1]: https://github.com/libra/libra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [[move prover] improvements to pure move function call feature](https://github.com/libra/libra/pull/5416) by [@emmazzz](https://github.com/emmazzz)
- PR: [[executor] fuzzing for execute_and_commit_chunk](https://github.com/libra/libra/pull/4714) by [@mimoo](https://github.com/mimoo)
- PR: [[db-bootstrapper] support commit genesis with waypoint at startup](https://github.com/libra/libra/pull/5459) by [@zekun000](https://github.com/zekun000)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

29 merged PRs ([1][lighthouse-merged-prs-1]), 37 closed issues ([1][lighthouse-closed_issues-1]), 
33 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [Write new blocks and states to the database atomically](https://github.com/sigp/lighthouse/pull/1285) by [@adaszko](https://github.com/adaszko)
- PR: [swap out rust-crypto for RustCrypto libraries for key management](https://github.com/sigp/lighthouse/pull/1270) by [@realbigsean](https://github.com/realbigsean)
- PR: [Fix race condition in VC block proposal service](https://github.com/sigp/lighthouse/pull/1282) by [@michaelsproul](https://github.com/michaelsproul)

#### [MobileCoin](https://www.mobilecoin.com/)

83 merged PRs ([1][mobilecoin-merged-prs-1]), 2 closed issues ([1][mobilecoin-closed_issues-1]), 
1 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinofficial/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinofficial/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[mobilecoin-open_issues-1]: https://github.com/mobilecoinofficial/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [Mob url](https://github.com/mobilecoinofficial/mobilecoin/pull/242) by [@garbageslam](https://github.com/garbageslam)
- PR: [Initial fog authority key signature with schnorrkel](https://github.com/mobilecoinofficial/mobilecoin/pull/246) by [@sugargoat](https://github.com/sugargoat)
- PR: [Mc sig](https://github.com/mobilecoinofficial/mobilecoin/pull/292) by [@garbageslam](https://github.com/garbageslam)

#### [NEAR](https://github.com/nearprotocol/nearcore)

83 merged PRs ([1][near-merged-prs-1]), 44 closed issues ([1][near-closed_issues-1]), 
32 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[near-closed_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[near-open_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [feat: Network indexer](https://github.com/nearprotocol/nearcore/pull/2651) by [@khorolets](https://github.com/khorolets)
- PR: [Mocknet load testing (#2899)](https://github.com/nearprotocol/nearcore/pull/2922) by [@birchmd](https://github.com/birchmd)
- PR: [fix: prevent repetitive initialization on node start](https://github.com/nearprotocol/nearcore/pull/3035) by [@bowenwang1996](https://github.com/bowenwang1996)

#### [Nervos](https://github.com/nervosnetwork)

49 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2]), 12 closed issues ([1][nervos-closed_issues-1]), 
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[nervos-merged-prs-2]: https://github.com/nervosnetwork/rfcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[nervos-open_issues-3]: https://github.com/nervosnetwork/rfcs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [refactor: use a new method to detect headers sync timeout](https://github.com/nervosnetwork/ckb/pull/1988) by [@yangby-cryptape](https://github.com/yangby-cryptape)
- PR: [feat: add sync state rpc](https://github.com/nervosnetwork/ckb/pull/2188) by [@driftluo](https://github.com/driftluo)
- PR: [improvement: don't cache all data of header map in memory during IBD](https://github.com/nervosnetwork/ckb/pull/2147) by [@yangby-cryptape](https://github.com/yangby-cryptape)

#### [Parity](https://github.com/paritytech)

275 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]), 105 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3]), 
87 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[parity-merged-prs-3]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[parity-closed_issues-3]: https://github.com/paritytech/parity-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[parity-open_issues-3]: https://github.com/paritytech/parity-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [CandidateBackingSubsystem](https://github.com/paritytech/polkadot/pull/1312) by [@montekki](https://github.com/montekki)
- PR: [Make a test crate to make the runtime-test usable](https://github.com/paritytech/polkadot/pull/1258) by [@cecton](https://github.com/cecton)
- PR: [Add a back-pressure-friendly alternative to NetworkService::write_notifications 🎉](https://github.com/paritytech/substrate/pull/6692) by [@tomaka](https://github.com/tomaka)
- PR: [Downward & Upward messages](https://github.com/paritytech/polkadot/pull/1266) by [@bkchr](https://github.com/bkchr)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

61 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 32 closed issues ([1][secret_network-closed_issues-1]), 
14 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[secret_network-merged-prs-2]: https://github.com/enigmampc/SafeTrace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [Implement query_chain()](https://github.com/enigmampc/SecretNetwork/pull/392) by [@assafmo](https://github.com/assafmo)
- PR: [Node auth error messages - take 3](https://github.com/enigmampc/SecretNetwork/pull/397) by [@reuvenpo](https://github.com/reuvenpo)

#### [Solana](https://github.com/solana-labs/solana)

252 merged PRs ([1][solana-merged-prs-1]), 24 closed issues ([1][solana-closed_issues-1]), 
43 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [fix rewards points](https://github.com/solana-labs/solana/pull/10914) by [@rwalker-com](https://github.com/rwalker-com)
- PR: [Use BlockCommitmentCache for RPC slots](https://github.com/solana-labs/solana/pull/11103) by [@garious](https://github.com/garious)
- PR: [Add replay votes to gossip vote tracking](https://github.com/solana-labs/solana/pull/11119) by [@carllin](https://github.com/carllin)

#### [Zcash](https://z.cash/)

144 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 74 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
58 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-07-01..2020-08-04
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[zcash-closed_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-07-01..2020-08-04
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04
[zcash-open_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aopen+created%3A2020-07-01..2020-08-04

- PR: [Start work on new Amount type](https://github.com/ZcashFoundation/zebra/pull/554) by [@yaahc](https://github.com/yaahc)
- PR: [Command execution tests](https://github.com/ZcashFoundation/zebra/pull/690) by [@oxarbitrage](https://github.com/oxarbitrage)
- PR: [sync: add backpressure to syncer](https://github.com/ZcashFoundation/zebra/pull/707) by [@hdevalence](https://github.com/hdevalence)

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

