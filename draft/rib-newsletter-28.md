---
title: "RiB Newsletter #28"
description: "#28 - September 2021"
date: 2021-10-06
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #28 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #27](/newsletters/rib-newsletter-27/).

&nbsp;

## Thanks

Thanks to contributors:
[Antonio Yang],
[Max Wegman],
[Shamil],
[Tommy Johnson],
[Tony Arcieri],
[Brian Anderson],
[Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Antonio Yang]: https://github.com/yanganto
[Max Wegman]: https://github.com/mastermaxy
[Shamil]: https://github.com/shamilsan
[Tommy Johnson]: https://github.com/tomjohn1028
[Tony Arcieri]: https://github.com/tarcieri
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News

- [`crypto-bigint` v0.2.6](https://twitter.com/RustCryptoOrg/status/1435640493694758915)
  adds support for natively encoding/decoding `UInt` types using Ethereum's Recursive Length Prefix (RLP) encoding.
- [Bitcoin Core 22.0 released](https://lists.linuxfoundation.org/pipermail/bitcoin-core-dev/2021-September/000104.html).

#### Blog Posts

- [zkEVM](https://hackmd.io/@yezhang/S1_KMMbGt)

#### Papers

#### Projects

- [SewUp](https://github.com/second-state/SewUp).
  A library to help you build your Ethereum webassembly contract with
  Rust and just like develop in a common backend.
- Dfinity's [NNS front-end Dapp](https://github.com/dfinity/nns-dapp).
  The Dapp of the Internet Computer's Network Nervous System.

&nbsp;

## Most Active in September

[Parity](https://github.com/paritytech):
321 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
112 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
85 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[Solana](https://github.com/solana-labs/solana):
291 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
25 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
64 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Diem](https://github.com/diem):
161 merged PRs ([1][diem-merged-prs-1]), 
19 closed issues ([1][diem-closed_issues-1]), 
21 open issues ([1][diem-open_issues-1])

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

117 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]), 
37 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]), 
27 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Anoma](https://github.com/anoma)

36 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]), 
22 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2]), 
39 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[anoma-merged-prs-2]: https://github.com/anoma/ferveo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[anoma-merged-prs-3]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[anoma-closed_issues-2]: https://github.com/anoma/ferveo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [Heterogeneous Paxos and Multi-Chain Atomic Commits](https://anoma.network/blog/heterogeneous-paxos-and-multi-chain-atomic-commits)

#### [ChainSafe](https://github.com/ChainSafe)

9 merged PRs ([1][chainsafe-merged-prs-1]), 
7 closed issues ([1][chainsafe-closed_issues-1]), 
3 open issues ([1][chainsafe-open_issues-1])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [NodeWatch: The open source node explorer for Ethereum Consensus (Eth2)](https://medium.com/chainsafe-systems/nodewatch-the-open-source-node-explorer-for-ethereum-consensus-eth2-e00057525cd7)

#### [COMIT](https://github.com/comit-network)

42 merged PRs ([1][comit-merged-prs-1]), 
18 closed issues ([1][comit-closed_issues-1]), 
13 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Concordium](https://github.com/Concordium)

41 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]), 
13 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3]), 
8 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [Protocol Update 2 - Alpha Centauri 2.0 - Transaction Memos](https://proposals.concordium.software/updates/P2.html)

#### [Conflux](https://github.com/Conflux-Chain)

5 merged PRs ([1][conflux-merged-prs-1]), 
2 closed issues ([1][conflux-closed_issues-1]), 
2 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Dfinity](https://github.com/dfinity)

33 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4]), 
4 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2]), 
10 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4], [5][dfinity-open_issues-5], [6][dfinity-open_issues-6])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[dfinity-merged-prs-4]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[dfinity-closed_issues-1]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[dfinity-closed_issues-2]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[dfinity-open_issues-1]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[dfinity-open_issues-3]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[dfinity-open_issues-4]: https://github.com/dfinity/ic-types/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[dfinity-open_issues-5]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[dfinity-open_issues-6]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [The DFINITY Canister Smart Contract SDK Is Now Open Source](https://medium.com/dfinity/the-dfinity-canister-smart-contract-sdk-is-now-open-source-54b2e5e797ad)
- [The Internet Computer’s NNS Front-End Dapp Is Now Open Source](https://medium.com/dfinity/the-internet-computers-nns-front-end-dapp-is-now-open-source-3925edc21c49)
- [The Internet Computer Community Adopts Threshold ECDSA Signatures Motion Proposal](https://medium.com/dfinity/the-internet-computer-community-approves-threshold-ecdsa-signatures-motion-proposal-65a0a3463492)

#### [Diem](https://github.com/diem)

161 merged PRs ([1][diem-merged-prs-1]), 
19 closed issues ([1][diem-closed_issues-1]), 
21 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Elrond](https://github.com/ElrondNetwork)

32 merged PRs ([1][elrond-merged-prs-1]), 
0 closed issues (), 
1 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[elrond-open_issues-1]: https://github.com/ElrondNetwork/sc-delegation-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Fluence](https://github.com/fluencelabs)

24 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]), 
5 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2], [3][fluence-closed_issues-3]), 
18 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3], [4][fluence-open_issues-4])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[fluence-merged-prs-4]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[fluence-closed_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[fluence-closed_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[fluence-closed_issues-3]: https://github.com/fluencelabs/marine-rs-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[fluence-open_issues-2]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[fluence-open_issues-3]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[fluence-open_issues-4]: https://github.com/fluencelabs/marine-rs-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Golem](https://github.com/golemfactory)

16 merged PRs ([1][golem-merged-prs-1]), 
15 closed issues ([1][golem-closed_issues-1]), 
16 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Grin](https://github.com/mimblewimble/grin)

0 merged PRs, 
2 closed issues ([1][grin-closed_issues-1]), 
0 open issues

[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30

#### [Holochain](https://github.com/holochain/)

49 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]), 
9 closed issues ([1][holochain-closed_issues-1]), 
7 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2], [3][holochain-open_issues-3])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[holochain-merged-prs-2]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[holochain-open_issues-2]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[holochain-open_issues-3]: https://github.com/holochain/lair/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [IOTA](https://github.com/iotaledger)

27 merged PRs ([1][iota-merged-prs-1]), 
9 closed issues ([1][iota-closed_issues-1]), 
4 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Lighthouse](https://github.com/sigp/lighthouse)

17 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]), 
24 closed issues ([1][lighthouse-closed_issues-1]), 
17 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [MobileCoin](https://github.com/mobilecoinfoundation)

136 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]), 
5 closed issues ([1][mobilecoin-closed_issues-1]), 
16 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/fog/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [NEAR](https://github.com/nearprotocol/nearcore)

92 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4]), 
64 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
52 open issues ([1][near-open_issues-1], [2][near-open_issues-2])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[near-merged-prs-2]: https://github.com/near/borsh/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[near-merged-prs-3]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[near-closed_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[near-open_issues-2]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [Join us at NEAR|CON Alpha](https://near.org/blog/join-us-at-nearcon-alpha-tickets-conference-lisbon/)

#### [Nervos](https://github.com/nervosnetwork)

76 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5]), 
12 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 
1 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[nervos-merged-prs-5]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-std/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [Nervos Network Protocol Upgrade](https://www.nervos.org/blog/nervos-network-protocol-upgrade/)

#### [Parity](https://github.com/paritytech)

321 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 
112 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
85 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[parity-open_issues-3]: https://github.com/paritytech/parity-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [XCM: The Cross-Consensus Message Format](https://medium.com/polkadot-network/xcm-the-cross-consensus-message-format-3b77b1373392)
- [XCM Part II: Versioning and Compatibility](https://medium.com/polkadot-network/xcm-part-ii-versioning-and-compatibility-b313fc257b83)
- [XCM Part III: Execution and Error Management](https://medium.com/polkadot-network/xcm-part-iii-execution-and-error-management-ceb8155dd166)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

52 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]), 
13 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]), 
19 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Rust Ethereum](https://github.com/rust-ethereum)

7 merged PRs ([1][rust_ethereum-merged-prs-1]), 
5 closed issues ([1][rust_ethereum-closed_issues-1]), 
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[rust_ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

2 merged PRs ([1][secret_network-merged-prs-1]), 
0 closed issues (), 
4 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Solana](https://github.com/solana-labs/solana)

291 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
25 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
64 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

- [9-14 Network Outage Initial Overview](https://solana.com/news/9-14-network-outage-initial-overview)

#### [Spacemesh](https://github.com/spacemeshos)

14 merged PRs ([1][spacemesh-merged-prs-1]), 
59 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
38 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [TezEdge](https://github.com/tezedge)

17 merged PRs ([1][tezedge-merged-prs-1]), 
0 closed issues (), 
2 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

#### [Zcash](https://github.com/zcash)

74 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
35 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
31 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-09-01..2021-09-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-09-01..2021-09-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-09-01..2021-09-30

&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

Oct 18-24 | Lisbon

[lisbonblockchainweek](https://lisbonblockchainweek.com/)

Oct 22-24 | Fintech House Lisbon

[Ethereum hackathon: ETHLisbon](https://www.ethlisbon.org/)

Oct 26 | Online

[ZK Hack](https://www.zkhack.dev/)

Oct 26-27 | Lisbon

[NEARCON Alpha](https://nearcon.org/)

Nov 15-19 | Online

[ACM CCS 2021](https://www.sigsac.org/ccs/CCS2021/)

Nov 18-19 | Online

[Tokenomics 2021: 3rd International Conference on Blockchain Economics, Security and Protocols](https://sites.google.com/nyu.edu/tokenomics2021)

Dec 1-3 | Seoul, Korea

[ICISC: The 24th Annual International Conference on information Security and Cryptology](http://www.icisc.org/)

Dec 14-15 | Online

[18th IMA International Conference on Cryptography and Coding](https://ima.org.uk/16366/online-event-18th-ima-international-conference-on-cryptography-and-coding/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

PsyOptions Inc. | Remote
- [Rust Solana Program Engineer](https://jobs.solana.com/companies/psyoptions/jobs/5215445-rust-engineer)

Parity Technologies | Berlin or Remote 
- [Rust Core Developer - Substrate SDK](https://grnh.se/6d0a8fa13us)
- [Rust Core Developer - Parachain Engineering (Polkadot)](https://grnh.se/e72723563us)
- [Rust Core Developer - Parachain Protocol (Polkadot R&D)](https://grnh.se/1c4a41f43us)
- [Rust/Core Developer - Open Application to our 10+ open Rust engineering positions](https://grnh.se/0efc64513us)

Spacemesh | Remote
- [Rust Developer](https://spacemesh.io/careers/rust-developer/)

Zcash Foundation | Remote
- [CI/CD & DevOps Engineer](https://cryptojobslist.com/jobs/ci-cd-devops-engineer-at-zcash-foundation-remote-anywhere-in-the-world)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#29 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


