---
title: "RiB Newsletter #24"
description: "#24 - May 2021"
date: 2021-06-02
slug: "/"
categories:
  - "newsletters"
summary: ""
---

Welcome to the #24 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #23](/newsletters/rewriting-in-rust/)

This month we're interested in cross-chain bridges.
With Ethereum at capacity recently,
other blockchain projects are eyeing the window
of opportunity between now and a functional Ethereum 2
to siphon away some of that chain's activity.
So there seems to be a rush to get bridges built
between Ethereum and every other chain,
not to mention between pairs of non-Ethereum chains.
It looks like we are well on our way to an internetwork of blockchains,
so now is a good time to do a survey of bridges
to Rust chains.

Thise bridges mostly support moving fungible tokens today,
and some plan to support NFTs;
contrasting with general cross-chain communications
protocols like [IBC] and [XCMP].

While the details differ between bridges and chains,
it seems that many of these bridges are their own distributed networks,
with similar behavior:

- They operate a network of validators.
- They maintain custodial contracts on each chain.
- Multisig cryptography is used by the validators to agree on
  pairs of cross-chain transactions.
- The bridge network offers cryptoeconomic incentives for node operators.
- Watchdog nodes may monitor the network for misbehavior.
- Some of these networks are themselves blockchains,
  but many are not.

For a more informed description of bridges see
[this recent blog post from Patrick McCorry][bblog].

[bblog]: https://stonecoldpat.medium.com/a-note-on-bridges-layer-2-protocols-b01f8fc22324

Some of those in the Rust world include

- [Secret · Ethereum Bridge][seb]. Between Secret Network and Ethereum.
  Mainnet.
- [Secret · Monero Bridge][smb]. Between Secret Network and Monero.
  Testnet.
  - This is particularly interesting because there are relatively few
  on/off-ramps for privacy-preserving Monero, and this is a bridge
  to another privacy chain.
- [Secret · Binance Smart Chain Bridge][sbb]. Between Secret Network and Binance Smart Chain.
  Testnet.
- [Secret · Plasm Bridge][spb]. Between Secret Network and [Plasm Network].
  Not live.
  - This one will link Secret Network to the world of Polkadot parachains,
  and to to the world of [Cosmos]/[IBC]-based chains,
  as Plasm is a Substrate chain that is intended to connect to both.
- [Near · Rainbow Bridge][nrb]. Between Near and Ethereum.
  Mainnet.
- [Solana · Wormhole][swh]. Between Solana and Ethereum.
  Mainnet.
- [Nervos · Force-Bridge][nfb]. Between Nervos CKB and Ethereum.
  Testnet.
- [Polkadot · PolkaBTC][pi]. Between Polkadot and Bitcoin.
- [Polkadot · Snowbridge][psb]. Between Polkadot and Ethereum.
  Not live.
- [Polkadot · Darwinia][pd]. Between Polkadot and Ethereum.
- [Polkadot · ChainBridge][pcb]. Between Polkadot and Ethereum.
- [Polkadot · Bifrost][pbf]. Between Polkadot and EOS.

Polkadot's family of bridges is [described here][pbridges].

[swh]: https://medium.com/solana-labs/wormhole-solana-ethereum-bridge-d5502e944acb
[pbf]: https://github.com/bifrost-finance
[pcb]: https://github.com/ChainSafe/ChainBridge
[XCMP]: https://wiki.polkadot.network/docs/en/learn-crosschain
[pd]: https://darwinia.network/
[psb]: https://snowfork.substack.com/p/a-trustless-general-purpose-polkadot
[pi]: https://polkadot.network/bitcoin-is-coming-to-polkadot/
[pbridges]: https://polkadot.network/polkadot-bridges-connecting-the-polkadot-ecosystem-with-external-networks/
[nfb]: https://medium.com/nervosnetwork/nervos-launches-force-bridge-to-connect-ethereum-dapps-users-with-ckb-24450df468f4
[nrb]: https://near.org/bridge/
[smb]: https://scrt.network/blog/secret-monero-bridge-is-live-on-testnet
[seb]: https://scrt.network/blog/secret-ethereum-bridge-privacy/
[seb2]: https://scrt.network/blog/secret-ethereum-bridge-december-2020/
[sbb]: https://scrt.network/blog/announcing-secret-binance-smart-chain-bridge
[spb]: https://scrt.network/blog/secret-plasm-bridge-cosmos-polkadot
[Plasm Network]: https://plasmnet.io/
[Cosmos]: https://cosmos.network/
[IBC]: https://ibcprotocol.org/



&nbsp;

## Thanks

Thanks to contributors:
[Júlio Santos][contributorjs],
[Max Wegman][contributormw],
[naternater][contributorna],
Tor Bair,
[Brian Anderson][contributorba], and [Aimee Zhu][contributoraz].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#25 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributorjs]: https://github.com/juliosantos
[contributormw]: https://github.com/mastermaxy
[contributorna]: https://github.com/naternater
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[TDN] (and [Chamomile]).

Trusted Distributed Network is a framework for building distributed applications,
with support for p2p communications, multiple cross-communicating blockchains,
multiple layers of blockchains, and multiple account models.
It is built on a new p2p library, Chamomile.

TDN appears to be somewhat comparable to Substrate,
and Chamomile to libp2p.

Chamomile adds to the choices available to Rust developers
for p2p networking, which already include [rust-libp2p], and [tentacle].

These projects are authored by
[@sunhauchuang]
who also created
[Awesome Rust Blockchain][arb]

[TDN]: https://github.com/cypherlink/TDN
[Chamomile]: https://github.com/cypherlink/chamomile
[rust-libp2p]: https://github.com/libp2p/rust-libp2p
[tentacle]: https://github.com/nervosnetwork/tentacle
[arb]: https://github.com/rust-in-blockchain/awesome-blockchain-rust
[@sunhauchuang]: https://github.com/sunhuachuang


&nbsp;


## Interesting Things

#### News

- [The Internet Computer’s Source Code Is Public](https://medium.com/dfinity/the-internet-computers-source-code-is-public-603a558cb6cc).
  [GitHub: Dfinity/IC](https://github.com/dfinity/ic).
  It also [Announces CHF 200 Million Program to Support the Internet Computer Developer Ecosystem](https://medium.com/dfinity/dfinity-announces-chf-200-million-program-to-support-the-internet-computer-developer-ecosystem-c65aa290548c)
- [Gnosis client development team Joins Erigon (formerly Turbo-Geth) to Release Next-Gen Ethereum Client](https://medium.com/openethereum/gnosis-joins-erigon-formerly-turbo-geth-to-release-next-gen-ethereum-client-c6708dd06dd)  
  
#### Blog Posts

- [zkSync 2.0: Hello Ethereum!](https://medium.com/matter-labs/zksync-2-0-hello-ethereum-ca48588de179)

#### Papers

- [Hours of Horus: Keyless Cryptocurrency Wallets](https://eprint.iacr.org/2021/715)
- [Hedging Against Sore Loser Attacks in Cross-Chain Transactions](https://arxiv.org/abs/2105.06322)
- [Internet Computer Consensus](https://eprint.iacr.org/2021/632.pdf)
- [SoK: Privacy-Preserving Computing in the Blockchain Era](https://eprint.iacr.org/2021/727)
- [VerLoc: Verifiable Localization in Decentralized Systems](https://arxiv.org/abs/2105.11928)
- [GoAT: File Geolocation via Anchor Timestamping](https://eprint.iacr.org/2021/697)
- [Differentially Oblivious Database Joins: Overcoming the Worst-Case Curse of Fully Oblivious Algorithms](https://eprint.iacr.org/2021/593)
- [Structured Leakage and Applications to Cryptographic Constant-Time and Cost](https://eprint.iacr.org/2021/650)
- [Reasoning about modern datacenter infrastructures using partial histories](https://sigops.org/s/conferences/hotos/2021/papers/hotos21-s11-sun.pdf)
- [OSHA: A General-purpose One-way Secure Hash Algorithm](https://eprint.iacr.org/2021/689)
- [Forward-secure Multi-user Aggregate Signatures based on zk-SNARKs](https://eprint.iacr.org/2021/567)
- [Hydra: Succinct Fully Pipelineable Interactive Arguments of Knowledge](https://eprint.iacr.org/2021/641)
- [Stealth: A Highly Secured End-to-End Symmetric Communication Protocol](https://eprint.iacr.org/2021/622)

#### Projects

- [snarkVM](https://github.com/AleoHQ/snarkVM).
  A Virtual Machine for Zero-Knowledge Executions.
- [Polkadex](https://github.com/Polkadex-Substrate/Polkadex).
  An Orderbook-based Decentralized Exchange using the Substrate Blockchain Framework.

&nbsp;

## Most Active in May

[Solana](https://github.com/solana-labs/solana):
421 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
46 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
67 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Parity](https://github.com/paritytech):
275 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
96 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
78 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[Aleo](https://github.com/AleoHQ):
100 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
41 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
42 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

100 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
41 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
42 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

- Paper: [Leo: A Programming Language for Formally Verified, Zero-Knowledge Applications](https://eprint.iacr.org/2021/651)

#### [COMIT](https://github.com/comit-network)

53 merged PRs ([1][comit-merged-prs-1]),
23 closed issues ([1][comit-closed_issues-1]), 
14 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Concordium](https://github.com/Concordium)

36 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]),
1 closed issues ([1][concordium-closed_issues-1]), 
12 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31


#### [Conflux](https://github.com/Conflux-Chain)

12 merged PRs ([1][conflux-merged-prs-1]),
5 closed issues ([1][conflux-closed_issues-1]), 
3 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Diem](https://github.com/diem)

104 merged PRs ([1][diem-merged-prs-1], [2][diem-merged-prs-2]),
21 closed issues ([1][diem-closed_issues-1]), 
10 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[diem-merged-prs-2]: https://github.com/diem/bcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Elrond](https://github.com/ElrondNetwork)

34 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3]),
0 closed issues, 
1 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-dns-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Fluence](https://github.com/fluencelabs)

31 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]),
2 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2]), 
7 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[fluence-closed_issues-2]: https://github.com/fluencelabs/rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[fluence-open_issues-2]: https://github.com/fluencelabs/rust-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Golem](https://github.com/golemfactory)

33 merged PRs ([1][golem-merged-prs-1]),
39 closed issues ([1][golem-closed_issues-1]), 
26 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Grin](https://github.com/mimblewimble/grin)

4 merged PRs ([1][grin-merged-prs-1]),
0 closed issues, 
2 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31


#### [Holochain](https://github.com/holochain/)

37 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]),
0 closed issues, 
6 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2], [3][holochain-open_issues-3])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[holochain-open_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[holochain-open_issues-2]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[holochain-open_issues-3]: https://github.com/holochain/holochain-wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Interledger](https://github.com/interledger-rs)

9 merged PRs ([1][interledger-merged-prs-1]),
2 closed issues ([1][interledger-closed_issues-1]), 
2 open issues ([1][interledger-open_issues-1])

[interledger-merged-prs-1]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[interledger-closed_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[interledger-open_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [IOTA](https://github.com/iotaledger)

41 merged PRs ([1][iota-merged-prs-1]),
17 closed issues ([1][iota-closed_issues-1]), 
1 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

21 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
8 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]), 
9 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[lighthouse-closed_issues-2]: https://github.com/sigp/beacon-fuzz/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

- News: [Lighthouse Update #36](https://lighthouse.sigmaprime.io/update-36.html)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

15 merged PRs ([1][mobilecoin-merged-prs-1]),
2 closed issues ([1][mobilecoin-closed_issues-1]), 
3 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

59 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]),
29 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
29 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[near-closed_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

- News: [Aurora launches on NEAR Protocol](https://near.org/blog/aurora-launches-near/)

#### [Nervos](https://github.com/nervosnetwork)

60 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]),
8 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3]), 
4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[nervos-closed_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[nervos-open_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

- News: [Force Bridge demo is live](https://ckbweekly.substack.com/p/force-bridge-demo-is-now-live)

#### [Parity](https://github.com/paritytech)

275 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
96 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
78 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

- News: [A Polkadot Postmortem - 24.05.2021](https://polkadot.network/a-polkadot-postmortem-24-05-2021/)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

39 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3]),
11 closed issues ([1][rust_bitcoin-closed_issues-1]), 
3 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Rust Ethereum](https://github.com/rust-ethereum)

2 merged PRs ([1][rust-ethereum-merged-prs-1]),
1 closed issues ([1][rust-ethereum-closed_issues-1]), 
2 open issues ([1][rust-ethereum-open_issues-1])

[rust-ethereum-merged-prs-1]: https://github.com/rust-ethereum/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[rust-ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[rust-ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

10 merged PRs ([1][secret_network-merged-prs-1]),
2 closed issues ([1][secret_network-closed_issues-1]), 
6 open issues ([1][secret_network-open_issues-1], [2][secret_network-open_issues-2])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[secret_network-open_issues-2]: https://github.com/enigmampc/secret-toolkit/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

- News: [Secret Monero Bridge is Live on Testnet!](https://scrt.network/blog/secret-monero-bridge-is-live-on-testnet)
- News: [Secret Binance Smart Chain Bridge is Live on Testnet!](https://scrt.network/blog/secret-binance-smart-chain-bridge-is-live-on-testnet)

#### [Solana](https://github.com/solana-labs/solana)

421 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
46 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
67 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

- Video: [Intro to the Solana Programming Model - Technical Workshop](https://www.youtube.com/watch?v=7Iitv5tMOMY)

#### [Spacemesh](https://github.com/spacemeshos)

3 merged PRs ([1][spacemesh-merged-prs-1], [2][spacemesh-merged-prs-2]),
40 closed issues ([1][spacemesh-closed_issues-1]), 
14 open issues ([1][spacemesh-open_issues-1])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/go-spacemesh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[spacemesh-merged-prs-2]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [TezEdge](https://github.com/tezedge)

18 merged PRs ([1][tezedge-merged-prs-1]),
0 closed issues, 
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31

#### [Zcash](https://github.com/zcash)

82 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
17 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
61 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-05-01..2021-05-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-05-01..2021-05-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-05-01..2021-05-31


&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

Sep 26-28 | Arlington, VA, US

[ACM Advances in Financial Technologies - AFT 2021](https://aft.acm.org/aft21/index.html)

Oct 4-8 | Darmstadt, Germany

[5th International Workshop on Cryptocurrencies and Blockchain Technology - CBT 2021](https://deic-web.uab.cat/conferences/dpm/cbt2021/)

Oct 6–8 | Darmstadt, Germany

[STM2021: The 17th International Workshop on Security and Trust Management](https://www.nics.uma.es/stm2021/)

&nbsp;

## Careers

<!--
Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)
-->

Fractal Protocol | Remote or Berlin
- [Rust and Blockchain Engineer](https://gist.github.com/juliosantos/ba6d01ffab39b5c06ea459d88b1f735f)

Kollider | Remote
- [Junior Backend Engineer](https://kollider.homerun.co/junior-backend-engineer/en)
- [Senior Backend Engineer](https://kollider.homerun.co/senior-backend-engineer/en)
- [DevOps Engineer](https://kollider.homerun.co/devops-engineer/en)

Parity Technologies | Berlin or Remote 
- [Core Rust Developer - Cross-chain Messaging (Polkadot)](https://grnh.se/dafd8e973us)
- [Core Rust Developer - Consensus (Polkadot)](https://grnh.se/470a1a623us)
- [Solution Engineer - Substrate](https://grnh.se/d7fe278f3us)
- [Rust/Core Developer - Open Application](https://grnh.se/0efc64513us)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#25 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


