---
title: "RiB Newsletter #21"
description: "#21 - Feb 2021"
date: 2021-03-02
slug: "/"
categories:
  - "newsletters"
summary: ""
---

Welcome to the #21 edition of Rust in Blockchain,
the hypest newsletter about the hypest tech.
[Previous: #20](/newsletters/old-fashioned-chill/).

&nbsp;

## Thanks

Thanks to contributors:
[apruden2008][contributor-ap],

_TODO_

Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#22 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributor-ap]: https://github.com/apruden2008
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News

#### Blog Posts

- [Serving up zero-knowledge proofs](https://blog.trailofbits.com/2021/02/19/serving-up-zero-knowledge-proofs/)
- [Confessions of a smart contract paper reviewer](https://blog.trailofbits.com/2021/02/05/confessions-of-a-smart-contract-paper-reviewer/)

#### Papers

- [Efficient State Management in Distributed Ledgers](https://eprint.iacr.org/2021/183)
- [Smart Contracts for Incentivized Outsourcing of Computation](https://eprint.iacr.org/2021/174)
- [Peer-to-Peer Content Delivery via Blockchain](https://arxiv.org/abs/2102.04685)
- [A Security Framework for Distributed Ledgers](https://eprint.iacr.org/2021/145)
- [IPDL: A Simple Framework for Formally Verifying Distributed Cryptographic Protocols](https://eprint.iacr.org/2021/147)
- [Group Signatures with User-Controlled and Sequential Linkability](https://eprint.iacr.org/2021/181)
- [smartFHE: Privacy-Preserving Smart Contracts from Fully Homomorphic Encryption](https://eprint.iacr.org/2021/133)
- [OptSmart: A Space Efficient Optimistic Concurrent Execution of Smart Contracts](https://arxiv.org/abs/2102.04875)
- [FPPW: A Fair and Privacy Preserving Watchtower For Bitcoin](https://eprint.iacr.org/2021/117)
- [MAKE: a Matrix Action Key Exchange](https://eprint.iacr.org/2021/116)


#### Projects

- [europa](https://github.com/patractlabs/europa).
  A sandbox to run and debug smart contracts for FRAME Contracts pallet and also a sandbox framework for Substrate runtime.
- [ethabi](https://github.com/rust-ethereum/ethabi). Encode and decode smart contract invocations.

&nbsp;

## Most Active in January

&nbsp;

## Project Updates

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

30 merged PRs ([1][rust-bitcoin-merged-prs-1], [2][rust-bitcoin-merged-prs-2], [3][rust-bitcoin-merged-prs-3]),
13 closed issues ([1][rust-bitcoin-closed_issues-1], [2][rust-bitcoin-closed_issues-2], [3][rust-bitcoin-closed_issues-3], [4][rust-bitcoin-closed_issues-4]), 
8 open issues ([1][rust-bitcoin-open_issues-1], [2][rust-bitcoin-open_issues-2])

[rust-bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[rust-bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[rust-bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [ChannelManager persistence](https://github.com/rust-bitcoin/rust-lightning/pull/752) by [@valentinewallace](https://github.com/valentinewallace)
- PR: [SPV client utility for syncing a lightning node](https://github.com/rust-bitcoin/rust-lightning/pull/791) by [@jkczyz](https://github.com/jkczyz)
- PR: [HTTP-based block source clients](https://github.com/rust-bitcoin/rust-lightning/pull/774) by [@jkczyz](https://github.com/jkczyz)

#### [Rust Ethereum](https://github.com/rust-ethereum)

2 merged PRs ([1][rust-ethereum-merged-prs-1], [2][rust-ethereum-merged-prs-2]),
0 closed issues, 
1 open issues ([1][rust-ethereum-open_issues-1])

[rust-ethereum-merged-prs-1]: https://github.com/rust-ethereum/enr/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-ethereum-merged-prs-2]: https://github.com/rust-ethereum/devp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[rust-ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Remove libsecp256k1, bump dependencies, fix warnings](https://github.com/rust-ethereum/enr/pull/27) by [@vorot93](https://github.com/vorot93)
- PR: [Bump ethereum-types](https://github.com/rust-ethereum/devp2p/pull/26) by [@frostRed](https://github.com/frostRed)

#### [Aleo](https://github.com/AleoHQ)

92 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3]),
69 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]), 
20 open issues ([1][aleo-open_issues-1])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[aleo-merged-prs-3]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- Blog: [The Future of Zero Knowledge with Aleo](https://aleo.org/post/the-future-of-zero-knowledge-with-aleo)
- PR: [Upgrade to the Constraint System for Marlin](https://github.com/AleoHQ/snarkVM/pull/66) by [@howardwu](https://github.com/howardwu)
- PR: [Add 'leo clone' command and add integration test with Aleo Package Manager](https://github.com/AleoHQ/leo/pull/686) by [@damirka](https://github.com/damirka)
- PR: [Update POSW Implementation](https://github.com/AleoHQ/snarkOS/pull/630) by [@raychu86](https://github.com/raychu86)

#### [COMIT](https://github.com/comit-network)

58 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2]),
34 closed issues ([1][comit-closed_issues-1]), 
6 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Replace bitcoind wallet with bdk wallet](https://github.com/comit-network/xmr-btc-swap/pull/178) by [@da-kami](https://github.com/da-kami)
- PR: [Use libp2p-async-await to improve API of execution setup phase](https://github.com/comit-network/xmr-btc-swap/pull/173) by [@D4nte](https://github.com/D4nte)
- PR: [Nectar](https://github.com/comit-network/xmr-btc-swap/pull/177) by [@D4nte](https://github.com/D4nte)

#### [Fluence](https://github.com/fluencelabs)

37 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]),
2 closed issues ([1][fluence-closed_issues-1]), 
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-merged-prs-2]: https://github.com/fluencelabs/fce/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquamarine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-merged-prs-4]: https://github.com/fluencelabs/rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28

- PR: [Support numbers and booleans](https://github.com/fluencelabs/aquamarine/pull/64) by [@michaelvoronov](https://github.com/michaelvoronov)
- PR: [New mounted binaries interface](https://github.com/fluencelabs/fce/pull/64) by [@michaelvoronov](https://github.com/michaelvoronov)

#### [Holochain](https://github.com/holochain/)

43 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]),
5 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
3 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[holochain-merged-prs-3]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[holochain-closed_issues-2]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[holochain-open_issues-2]: https://github.com/holochain/elemental-chat/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [hApp Bundles pt 3: Documentation, finishing touches, et al.](https://github.com/holochain/holochain/pull/651) by [@maackle](https://github.com/maackle)
- PR: [Allows a hc to reliably call while another hc is running the same setup](https://github.com/holochain/holochain/pull/642) by [@freesig](https://github.com/freesig)
- PR: [Improve compatibility of holochain types with Zome WASM, unify Timestamp type](https://github.com/holochain/holochain/pull/617) by [@pjkundert](https://github.com/pjkundert)

#### [Diem](https://www.diem.com)

195 merged PRs ([1][diem-merged-prs-1]),
38 closed issues ([1][diem-closed_issues-1]), 
39 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [[State Sync] Complete unit test skeleton for coordinator, better error support and clean up code.](https://github.com/diem/diem/pull/7444) by [@JoshLind](https://github.com/JoshLind)
- PR: [[move-lang] parser and typing for the public(script) visibility modifier](https://github.com/diem/diem/pull/7497) by [@mengxu-fb](https://github.com/mengxu-fb)
- PR: [Add PeerRole to identify known peers in the network](https://github.com/diem/diem/pull/7391) by [@gregnazario](https://github.com/gregnazario)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

5 merged PRs ([1][lighthouse-merged-prs-1]), 13 closed issues ([1][lighthouse-closed_issues-1]), 
5 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Auto-coerce to ping response to ipv4 when possible](https://github.com/sigp/discv5/pull/63) by [@paulhauner](https://github.com/paulhauner)
- PR: [Add mitigation for ipv6 loop](https://github.com/sigp/discv5/pull/62) by [@paulhauner](https://github.com/paulhauner)
- PR: [Add a `disconnect_node` public method](https://github.com/sigp/discv5/pull/59) by [@pawanjay176](https://github.com/pawanjay176)

#### [MobileCoin](https://www.mobilecoin.com/)

30 merged PRs ([1][mobilecoin-merged-prs-1]),
4 closed issues ([1][mobilecoin-closed_issues-1]), 
1 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [FOG-275 Fog Signature Scheme](https://github.com/mobilecoinfoundation/mobilecoin/pull/711) by [@jcape](https://github.com/jcape)
- PR: [Support reloading of GRPC services certificate/key files](https://github.com/mobilecoinfoundation/mobilecoin/pull/726) by [@eranrund](https://github.com/eranrund)

#### [NEAR](https://github.com/nearprotocol/nearcore)

86 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]),
42 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4]), 
35 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[near-merged-prs-2]: https://github.com/near/near-evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-closed_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-closed_issues-3]: https://github.com/near/near-evm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[near-open_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[near-open_issues-3]: https://github.com/near/near-evm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [rewrite graph struct to be 200 times faster](https://github.com/near/nearcore/pull/3882) by [@pmnoxx](https://github.com/pmnoxx)
- PR: [refactor(jsonrpc): Structured errors for `GetChunk` ViewClient handler and backward compatible response from JSON RPC](https://github.com/near/nearcore/pull/3861) by [@khorolets](https://github.com/khorolets)

#### [Nervos](https://github.com/nervosnetwork)

45 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]),
2 closed issues ([1][nervos-closed_issues-1]), 
1 open issues ([1][nervos-open_issues-1])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[nervos-open_issues-1]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [feat: customize chain spec for dev chains and update few preset params](https://github.com/nervosnetwork/ckb/pull/2503) by [@yangby-cryptape](https://github.com/yangby-cryptape)
- PR: [Integrate dynamic loading functions from C library](https://github.com/nervosnetwork/ckb-std/pull/12) by [@XuJiandong](https://github.com/XuJiandong)

#### [Parity](https://github.com/paritytech)

263 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]),
138 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
88 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[parity-open_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Migration testing runtime API/Bot](https://github.com/paritytech/substrate/pull/8038) by [@kianenigma](https://github.com/kianenigma)
- PR: [Decouple Staking and Election - Part 2 Unsigned Phase](https://github.com/paritytech/substrate/pull/7909) by [@kianenigma](https://github.com/kianenigma)
- PR: [contracts: Charge rent for code storage](https://github.com/paritytech/substrate/pull/7935) by [@athei](https://github.com/athei)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

6 merged PRs ([1][secret_network-merged-prs-1]), 29 closed issues ([1][secret_network-closed_issues-1]), 
4 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [fix typo in app.go](https://github.com/enigmampc/SecretNetwork/pull/728) by [@vitocchi](https://github.com/vitocchi)
- PR: [added support for debug-print in secret contracts.](https://github.com/enigmampc/SecretNetwork/pull/717) by [@reuvenpo](https://github.com/reuvenpo)

#### [Solana](https://github.com/solana-labs/solana)

350 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]),
21 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
50 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Add limit and shrink policy for recycler](https://github.com/solana-labs/solana/pull/15320) by [@carllin](https://github.com/carllin)
- PR: [Various postponed fixes and changes to the stake pool program](https://github.com/solana-labs/solana-program-library/pull/1200) by [@atticlab](https://github.com/atticlab)
- PR: [Warn lastValidSlot with some terminology tweaks](https://github.com/solana-labs/solana/pull/15081) by [@ryoqun](https://github.com/ryoqun)

#### [Zcash](https://z.cash/)

128 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
55 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
47 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-02-01..2021-02-28
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-02-01..2021-02-28
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-02-01..2021-02-28

- PR: [Refactor `connection.rs` to make `fail_with` errors impossible](https://github.com/ZcashFoundation/zebra/pull/1721) by [@yaahc](https://github.com/yaahc)
- PR: [Multi-proof prover](https://github.com/zcash/halo2/pull/143) by [@therealyingtong](https://github.com/therealyingtong)
- PR: [Hash verification key into transcript](https://github.com/zcash/halo2/pull/173) by [@therealyingtong](https://github.com/therealyingtong)

&nbsp;

## Events


&nbsp;

## Careers

Aleo | San Francisco, USA or Remote
* [Senior Protocol Engineer](https://aleo.org/jobs/senior-protocol-engineer)
* [Senior Compiler Engineer](https://aleo.org/jobs/senior-compiler-engineer)
* [Full-Stack Developer](https://aleo.org/jobs/full-stack-developer)
* [Interface Designer](https://aleo.org/jobs/interface-designer)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#22 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


