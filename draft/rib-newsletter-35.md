---
title: "RiB Newsletter #35 - _TODO_"
description: "April 2022"
date: 2022-05-04
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #35 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #34](/newsletters/rib-newsletter-34/).

Since adding a bunch of coverage last month for Rust Bitcoin projects,
Hunter Trujillo has started a dedicated [Rust in Bitcoin][ribtc] Telegram channel.

[ribtc]: https://t.me/rust_in_bitcoin

&nbsp;

## Thanks

Thanks to contributors:
[djddo],
[Genysys],
[Ilya Tegmark],
[keymakercasa],
[Max Wegman],
[Mikerah],
[Radha]
[Hunter Trujillo].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).


[djddo]: https://github.com/djddo
[Genysys]:https://github.com/Genysys
[Ilya Tegmark]: https://github.com/ilyategmark
[keymakercasa]: https://github.com/keymakercasa
[Max Wegman]: https://github.com/mastermaxy
[Mikerah]: https://github.com/Mikerah
[Radha]: https://github.com/DrW3RK
[Hunter Trujillo]: https://github.com/cryptoquick
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things


#### News

- For Rust in Bitcoin, Taproot support has landed in
  [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) and
  [rust-miniscript](https://github.com/rust-bitcoin/rust-miniscript). In
  addition, the first release of the [MyCitadel
  Wallet](https://github.com/mycitadel) was published by the
  [LNP/BP](https://github.com/lnp-bp) team. It's fully written in Rust, supports
  hardware signers like the Ledger Nano X and BitBox, and uses GTK and
  [Relm](https://docs.rs/relm/latest/relm/).

#### Blog Posts

- [Mesa's New OpenCL Stack "Rusticl" Nearing Formal Support For OpenCL 3.0](https://www.phoronix.com/scan.php?page=news_item&px=Mesa-OpenCL-3.0-CTS-Passes)
- [The Tower of Weakenings: Memory Models For Everyone](https://gankra.github.io/blah/tower-of-weakenings/)
- [Coordinated disclosure of vulnerabilities affecting Girault, Bulletproofs, and PlonK](https://blog.trailofbits.com/2022/04/13/part-1-coordinated-disclosure-of-vulnerabilities-affecting-girault-bulletproofs-and-plonk/)
- [The Frozen Heart vulnerability in Girault’s proof of knowledge](https://blog.trailofbits.com/2022/04/14/the-frozen-heart-vulnerability-in-giraults-proof-of-knowledge/)
- [The Frozen Heart vulnerability in Bulletproofs](https://blog.trailofbits.com/2022/04/15/the-frozen-heart-vulnerability-in-bulletproofs/)
- [The Frozen Heart vulnerability in PlonK](https://blog.trailofbits.com/2022/04/18/the-frozen-heart-vulnerability-in-plonk/)
- [What's two-adicity?](https://www.cryptologie.net/article/559/whats-two-adicity/)
- [Understanding RGB Protocol](https://medium.com/@FedericoTenga/understanding-rgb-protocol-7dc7819d3059)
- [Miniscript is coming to Bitcoin, and to your Ledger Nano!](https://blog.ledger.com/miniscript-is-coming/)
- [7 Theses on a next step for BIP-119](https://rubin.io/bitcoin/2022/04/17/next-steps-bip119/)

#### Papers

- [Practical Decentralized Oracle Contracts for Cryptocurrencies](https://eprint.iacr.org/2022/499)
- [Design and analysis of a distributed ECDSA signing service](https://eprint.iacr.org/2022/506)
- [Gemini: Elastic SNARKs for Diverse Environments](https://eprint.kobi.one/2022/420)
- [Bulletproofs++](https://eprint.iacr.org/2022/510)
- [Dew: Transparent Constant-sized zkSNARKs](https://eprint.iacr.org/2022/419)

#### Projects

- [StoffelMPC: A framework for building MPC as a sidechain applications for blockchains](https://write.as/hashcloaks-blog/announcing-stoffelmpc-an-mpc-as-a-sidechain-framework)
- [oriac](https://github.com/xJonathanLEI/oriac).
  A toy Cairo VM implementation in Rust
- [RISC Zero](https://github.com/risc0/risc0)
  is a zero-knowledge verifiable general computing platform based on zk-STARKs and the RISC-V microarchitecture.
  Example: [Battleship on RISC Zero](https://www.risczero.com/docs/tutorial-examples/battleship_rust_tutorial)
- [Vulcan Signer: Software for building an embedded PSBT signing device](https://github.com/mcroad/vulcan)
- [Mori: A CLI descriptor-based wallet to be used to safely inherit bitcoin](https://github.com/BlockchainCommons/mori-cli)

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust


&nbsp;

## Most Active in April

[Solana](https://github.com/solana-labs/solana):
590 merged PRs, 105 closed issues, 88 open issues

[Parity](https://github.com/paritytech):
471 merged PRs, 145 closed issues, 154 open issues

[NEAR](https://github.com/nearprotocol/nearcore):
219 merged PRs, 51 closed issues, 45 open issues

[Fuel](https://github.com/FuelLabs):
213 merged PRs, 145 closed issues, 134 open issues

[IOTA](https://github.com/iotaledger):
187 merged PRs, 46 closed issues, 34 open issues

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

81 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]),
15 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3]),
8 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[aleo-closed_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[aleo-open_issues-3]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Anoma](https://github.com/anoma)

24 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2]),
14 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2]),
26 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[anoma-merged-prs-2]: https://github.com/anoma/masp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[anoma-closed_issues-2]: https://github.com/anoma/masp/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[anoma-open_issues-2]: https://github.com/anoma/ferveo/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[anoma-open_issues-3]: https://github.com/anoma/masp/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [ChainSafe](https://github.com/ChainSafe)

34 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2], [3][chainsafe-merged-prs-3]),
22 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2], [3][chainsafe-closed_issues-3]),
33 open issues ([1][chainsafe-open_issues-1], [2][chainsafe-open_issues-2], [3][chainsafe-open_issues-3])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/mina-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/api3-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[chainsafe-merged-prs-3]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/api3-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[chainsafe-closed_issues-3]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[chainsafe-open_issues-1]: https://github.com/ChainSafe/mina-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[chainsafe-open_issues-2]: https://github.com/ChainSafe/api3-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[chainsafe-open_issues-3]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [An Intro to the Sauron Web Framework](https://blog.chainsafe.io/an-intro-to-the-sauron-web-framework-a6093a2ac9eb)

#### [COMIT](https://github.com/comit-network)

41 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2], [3][comit-merged-prs-3]),
16 closed issues ([1][comit-closed_issues-1]),
4 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2])

[comit-merged-prs-1]: https://github.com/comit-network/maia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[comit-merged-prs-2]: https://github.com/comit-network/rendezvous-server/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[comit-merged-prs-3]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[comit-open_issues-1]: https://github.com/comit-network/rendezvous-server/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[comit-open_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Concordium](https://github.com/Concordium)

36 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]),
22 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4]),
13 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-wasm-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[concordium-open_issues-2]: https://github.com/Concordium/concordium-wasm-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[concordium-open_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[concordium-open_issues-4]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Conflux](https://github.com/Conflux-Chain)

14 merged PRs ([1][conflux-merged-prs-1]),
4 closed issues ([1][conflux-closed_issues-1]),
4 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [DarkFi](https://dark.fi)

1 merged PRs ([1][darkfi-merged-prs-1]),
6 closed issues ([1][darkfi-closed_issues-1]),
3 open issues ([1][darkfi-open_issues-1])

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[darkfi-open_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Dfinity](https://github.com/dfinity)

70 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5], [6][dfinity-merged-prs-6], [7][dfinity-merged-prs-7], [8][dfinity-merged-prs-8]),
8 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2]),
12 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-merged-prs-3]: https://github.com/dfinity/icx-proxy/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-merged-prs-4]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-merged-prs-5]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-merged-prs-6]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-merged-prs-7]: https://github.com/dfinity/vessel/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-merged-prs-8]: https://github.com/dfinity/bitcoin-developer-preview/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[dfinity-closed_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[dfinity-open_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[dfinity-open_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[dfinity-open_issues-4]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [IC Internals: Orthogonal Persistence](https://medium.com/dfinity/ic-internals-orthogonal-persistence-9e0c094aac1a)

#### [Dusk Network](https://github.com/dusk-network)

35 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3], [4][dusk_network-merged-prs-4], [5][dusk_network-merged-prs-5]),
39 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2], [3][dusk_network-closed_issues-3], [4][dusk_network-closed_issues-4]),
4 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/dusk-hamt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dusk_network-merged-prs-2]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dusk_network-merged-prs-3]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dusk_network-merged-prs-4]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dusk_network-merged-prs-5]: https://github.com/dusk-network/wallet-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[dusk_network-closed_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[dusk_network-closed_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[dusk_network-closed_issues-3]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[dusk_network-closed_issues-4]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[dusk_network-open_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[dusk_network-open_issues-2]: https://github.com/dusk-network/rusk-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[dusk_network-open_issues-3]: https://github.com/dusk-network/wallet-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Elrond](https://github.com/ElrondNetwork)

93 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2], [3][elrond-merged-prs-3], [4][elrond-merged-prs-4], [5][elrond-merged-prs-5], [6][elrond-merged-prs-6], [7][elrond-merged-prs-7], [8][elrond-merged-prs-8]),
0 closed issues,
2 open issues ([1][elrond-open_issues-1], [2][elrond-open_issues-2])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/sc-dex-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-merged-prs-3]: https://github.com/ElrondNetwork/sc-nft-marketplace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-merged-prs-4]: https://github.com/ElrondNetwork/sc-metabonding-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-merged-prs-5]: https://github.com/ElrondNetwork/sc-bridge-elrond/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-merged-prs-6]: https://github.com/ElrondNetwork/sc-chainlink-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-merged-prs-7]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-merged-prs-8]: https://github.com/ElrondNetwork/sc-savings-account-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[elrond-open_issues-2]: https://github.com/ElrondNetwork/sc-dex-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Espresso Systems](https://github.com/EspressoSystems)

89 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2], [3][espresso_systems-merged-prs-3], [4][espresso_systems-merged-prs-4], [5][espresso_systems-merged-prs-5]),
62 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2], [3][espresso_systems-closed_issues-3], [4][espresso_systems-closed_issues-4], [5][espresso_systems-closed_issues-5]),
45 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2], [3][espresso_systems-open_issues-3])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/cape/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[espresso_systems-merged-prs-3]: https://github.com/EspressoSystems/reef/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[espresso_systems-merged-prs-4]: https://github.com/EspressoSystems/seahorse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[espresso_systems-merged-prs-5]: https://github.com/EspressoSystems/cap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[espresso_systems-closed_issues-3]: https://github.com/EspressoSystems/reef/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[espresso_systems-closed_issues-4]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[espresso_systems-closed_issues-5]: https://github.com/EspressoSystems/cap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/cape/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[espresso_systems-open_issues-3]: https://github.com/EspressoSystems/seahorse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Findora](https://github.com/FindoraNetwork)

66 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4], [5][findora-merged-prs-5]),
8 closed issues ([1][findora-closed_issues-1], [2][findora-closed_issues-2]),
2 open issues ([1][findora-open_issues-1])

[findora-merged-prs-1]: https://github.com/FindoraNetwork/zei/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[findora-merged-prs-2]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[findora-merged-prs-3]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[findora-merged-prs-4]: https://github.com/FindoraNetwork/bp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[findora-merged-prs-5]: https://github.com/FindoraNetwork/findora-exporter/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[findora-closed_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[findora-closed_issues-2]: https://github.com/FindoraNetwork/findora-exporter/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[findora-open_issues-1]: https://github.com/FindoraNetwork/platform/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Fluence](https://github.com/fluencelabs)

55 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5]),
7 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2]),
10 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2])

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fluence-merged-prs-3]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fluence-merged-prs-4]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fluence-merged-prs-5]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fluence-closed_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fluence-closed_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fluence-open_issues-1]: https://github.com/fluencelabs/marine/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[fluence-open_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Fuel](https://github.com/FuelLabs)

213 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7], [8][fuel-merged-prs-8], [9][fuel-merged-prs-9], [10][fuel-merged-prs-10]),
145 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5], [6][fuel-closed_issues-6], [7][fuel-closed_issues-7]),
134 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6])

[fuel-merged-prs-1]: https://github.com/FuelLabs/fuel-asm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-crypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-merkle/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuel-storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuel-tx/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-7]: https://github.com/FuelLabs/fuel-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-8]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-9]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-merged-prs-10]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-crypto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuel-tx/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fuel-closed_issues-5]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fuel-closed_issues-6]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fuel-closed_issues-7]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-bft/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-merkle/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[fuel-open_issues-4]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[fuel-open_issues-5]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[fuel-open_issues-6]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Golem](https://github.com/golemfactory)

32 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3]),
28 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2], [3][golem-closed_issues-3]),
13 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[golem-merged-prs-3]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[golem-closed_issues-1]: https://github.com/golemfactory/ya-runtime-http-auth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[golem-closed_issues-2]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[golem-closed_issues-3]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[golem-open_issues-2]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Grin](https://github.com/mimblewimble/grin)

3 merged PRs ([1][grin-merged-prs-1]),
1 closed issues ([1][grin-closed_issues-1]),
2 open issues ([1][grin-open_issues-1], [2][grin-open_issues-2])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[grin-open_issues-2]: https://github.com/mimblewimble/grin-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Helium](https://github.com/helium)

13 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3], [4][helium-merged-prs-4]),
3 closed issues ([1][helium-closed_issues-1], [2][helium-closed_issues-2]),
4 open issues ([1][helium-open_issues-1], [2][helium-open_issues-2])

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[helium-merged-prs-2]: https://github.com/helium/semtech-udp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[helium-merged-prs-3]: https://github.com/helium/ecc608-linux-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[helium-merged-prs-4]: https://github.com/helium/helium-api-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[helium-closed_issues-2]: https://github.com/helium/ecc608-linux-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[helium-open_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[helium-open_issues-2]: https://github.com/helium/helium-crypto-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Holochain](https://github.com/holochain/)

31 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]),
0 closed issues,
1 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[holochain-merged-prs-2]: https://github.com/holochain/holochain-wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [Holochain Dev Pulse 117: External Links](https://blog.holochain.org/external-links/)

#### [IOTA](https://github.com/iotaledger)

187 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5], [6][iota-merged-prs-6]),
46 closed issues ([1][iota-closed_issues-1], [2][iota-closed_issues-2], [3][iota-closed_issues-3], [4][iota-closed_issues-4], [5][iota-closed_issues-5]),
34 open issues ([1][iota-open_issues-1], [2][iota-open_issues-2], [3][iota-open_issues-3], [4][iota-open_issues-4], [5][iota-open_issues-5])

[iota-merged-prs-1]: https://github.com/iotaledger/bee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[iota-merged-prs-2]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[iota-merged-prs-3]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[iota-merged-prs-4]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[iota-merged-prs-5]: https://github.com/iotaledger/streams/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[iota-merged-prs-6]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[iota-closed_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[iota-closed_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[iota-closed_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[iota-closed_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[iota-closed_issues-5]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[iota-open_issues-1]: https://github.com/iotaledger/bee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[iota-open_issues-2]: https://github.com/iotaledger/wallet.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[iota-open_issues-3]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[iota-open_issues-4]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[iota-open_issues-5]: https://github.com/iotaledger/stronghold.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [IOTA in Gaia-X 4 Future Mobility](https://blog.iota.org/iota-in-gaia-x-4-future-mobility/)

#### [Maidsafe](https://github.com/maidsafe)

62 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2], [3][maidsafe-merged-prs-3], [4][maidsafe-merged-prs-4], [5][maidsafe-merged-prs-5]),
5 closed issues ([1][maidsafe-closed_issues-1], [2][maidsafe-closed_issues-2]),
6 open issues ([1][maidsafe-open_issues-1], [2][maidsafe-open_issues-2])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[maidsafe-merged-prs-3]: https://github.com/maidsafe/qp2p/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[maidsafe-merged-prs-4]: https://github.com/maidsafe/blsttc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[maidsafe-merged-prs-5]: https://github.com/maidsafe/bls_dkg/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[maidsafe-closed_issues-2]: https://github.com/maidsafe/qp2p/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[maidsafe-open_issues-2]: https://github.com/maidsafe/qp2p/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [MobileCoin](https://github.com/mobilecoinfoundation)

112 merged PRs ([1][mobilecoin-merged-prs-1], [2][mobilecoin-merged-prs-2]),
25 closed issues ([1][mobilecoin-closed_issues-1]),
21 open issues ([1][mobilecoin-open_issues-1], [2][mobilecoin-open_issues-2])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[mobilecoin-merged-prs-2]: https://github.com/mobilecoinfoundation/mc-oblivious/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[mobilecoin-open_issues-2]: https://github.com/mobilecoinfoundation/mc-oblivious/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [NEAR](https://github.com/nearprotocol/nearcore)

219 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9]),
51 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8], [9][near-closed_issues-9]),
45 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7], [8][near-open_issues-8], [9][near-open_issues-9])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-6]: https://github.com/near/near-lake/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-7]: https://github.com/near/near-lake-framework/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-8]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-merged-prs-9]: https://github.com/near/wasmer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-5]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-6]: https://github.com/near/near-lake/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-7]: https://github.com/near/near-lake-framework/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-8]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-closed_issues-9]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-5]: https://github.com/near/near-jsonrpc-client-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-6]: https://github.com/near/near-lake/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-7]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-8]: https://github.com/near/near-indexer-for-explorer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[near-open_issues-9]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Nervos](https://github.com/nervosnetwork)

158 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5], [6][nervos-merged-prs-6], [7][nervos-merged-prs-7]),
2 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]),
2 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/axon/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nervos-merged-prs-2]: https://github.com/nervosnetwork/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nervos-merged-prs-4]: https://github.com/nervosnetwork/godwoken-scripts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nervos-merged-prs-5]: https://github.com/nervosnetwork/mercury/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nervos-merged-prs-6]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nervos-merged-prs-7]: https://github.com/nervosnetwork/godwoken-tests/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nervos-closed_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[nervos-open_issues-1]: https://github.com/nervosnetwork/godwoken/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[nervos-open_issues-2]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [Hashing it Out: The Highlights](https://www.nervos.org/blog/hashing-it-out-the-highlights)

#### [Oasis](https://github.com/oasisprotocol)

40 merged PRs ([1][oasis-merged-prs-1], [2][oasis-merged-prs-2], [3][oasis-merged-prs-3]),
6 closed issues ([1][oasis-closed_issues-1]),
5 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[oasis-merged-prs-2]: https://github.com/oasisprotocol/cipher-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[oasis-merged-prs-3]: https://github.com/oasisprotocol/emerald-paratime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[oasis-closed_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Parity](https://github.com/paritytech)

471 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14], [15][parity-merged-prs-15]),
145 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12], [13][parity-closed_issues-13], [14][parity-closed_issues-14]),
154 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14], [15][parity-open_issues-15])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-5]: https://github.com/paritytech/smoldot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-7]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-8]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-9]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-10]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-11]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-12]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-13]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-14]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-merged-prs-15]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-13]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-closed_issues-14]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-13]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-14]: https://github.com/paritytech/metadata-portal/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[parity-open_issues-15]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [Parity Signer 5.0 Beta: Parity’s Advanced Air-Gapped Wallet Gets a Major Update](https://www.parity.io/blog/parity-signer-gets-a-major-update)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

3 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]),
8 closed issues ([1][secret_network-closed_issues-1]),
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[secret_network-closed_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Solana](https://github.com/solana-labs/solana)

590 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]),
105 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
88 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2], [3][solana-open_issues-3])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[solana-open_issues-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [Solana restarted after seven-hour outage caused by surge of transactions](https://www.reddit.com/r/solana/comments/ug09ze/solana_restarted_after_sevenhour_outage_caused_by/)
- [04-30-22 Solana Mainnet Beta Outage Report and Mitigation](https://solana.com/news/04-30-22-solana-mainnet-beta-outage-report-mitigation)
- [Neon EVM: The Limitations for Ethereum Compatibility](https://neonlabsorg.medium.com/neon-evm-the-limitations-for-ethereum-compatibility-47d059fc1742)
- [Solana programs Part 2: understanding SPL Associated Token Account](https://medium.com/coinmonks/solana-programs-part-2-understanding-spl-associated-token-account-25082b9b5471)
- [Solana programs Part 3: understanding Metaplex Token Metadata](https://medium.com/coinmonks/solana-programs-part-3-understanding-metaplex-token-metadata-3cafde284d72)

#### [Subspace Labs](https://github.com/subspace)

74 merged PRs ([1][subspace_labs-merged-prs-1]),
18 closed issues ([1][subspace_labs-closed_issues-1]),
6 open issues ([1][subspace_labs-open_issues-1])

[subspace_labs-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[subspace_labs-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[subspace_labs-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [TezEdge](https://github.com/tezedge)

32 merged PRs ([1][tezedge-merged-prs-1], [2][tezedge-merged-prs-2]),
4 closed issues ([1][tezedge-closed_issues-1]),
1 open issues ([1][tezedge-open_issues-1])

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[tezedge-merged-prs-2]: https://github.com/tezedge/tezedge-snapshots/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[tezedge-closed_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[tezedge-open_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Zcash](https://github.com/zcash)

134 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5], [6][zcash-merged-prs-6]),
71 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4], [5][zcash-closed_issues-5], [6][zcash-closed_issues-6]),
34 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3], [4][zcash-open_issues-4])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[zcash-merged-prs-6]: https://github.com/zcash/pasta_curves/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[zcash-closed_issues-3]: https://github.com/zcash/incrementalmerkletree/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[zcash-closed_issues-4]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[zcash-closed_issues-5]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[zcash-closed_issues-6]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[zcash-open_issues-4]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [New Release 4.7.0](https://electriccoin.co/blog/new-release-4-7-0/)

&nbsp;

### Rust in Bitcoin

#### [BDK](https://github.com/bitcoindevkit/bdk)

18 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3]),
13 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3]),
19 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[bdk-open_issues-3]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [BDK v0.18.0](https://github.com/bitcoindevkit/bdk/releases/tag/v0.18.0)

#### [Bitmask](https://github.com/diba-io/bitmask-core)

7 merged PRs ([1][bitmask-merged-prs-1]),
2 closed issues ([1][bitmask-closed_issues-1]),
9 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [BitMask Chrome Extension publihsed to the Chrome Web Store!](https://chrome.google.com/webstore/detail/bitmask/momakdpclmaphlamgjcndbgfckjfpemp)

#### [Electrs](https://github.com/romanz/electrs)

8 merged PRs ([1][electrs-merged-prs-1]),
3 closed issues ([1][electrs-closed_issues-1]),
4 open issues ([1][electrs-open_issues-1])

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[electrs-open_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

36 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2], [3][ldk-merged-prs-3]),
9 closed issues ([1][ldk-closed_issues-1], [2][ldk-closed_issues-2]),
8 open issues ([1][ldk-open_issues-1])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-sample/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[ldk-merged-prs-3]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[ldk-closed_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

- [rust-lightning v0.0.106](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.106)

#### [LNP/BP](https://github.com/LNP-BP)

6 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2]),
3 closed issues ([1][lnp/bp-closed_issues-1], [2][lnp/bp-closed_issues-2], [3][lnp/bp-closed_issues-3]),
6 open issues ([1][lnp/bp-open_issues-1], [2][lnp/bp-open_issues-2])

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[lnp/bp-merged-prs-2]: https://github.com/BP-WG/descriptor-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[lnp/bp-closed_issues-2]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[lnp/bp-closed_issues-3]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[lnp/bp-open_issues-1]: https://github.com/rust-amplify/rust-amplify/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[lnp/bp-open_issues-2]: https://github.com/BP-WG/descriptor-wallet/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [LNP WG](https://github.com/LNP-WG)

0 merged PRs,
1 closed issues ([1][lnp_wg-closed_issues-1]),
3 open issues ([1][lnp_wg-open_issues-1])

[lnp_wg-closed_issues-1]: https://github.com/LNP-WG/ln-types/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[lnp_wg-open_issues-1]: https://github.com/LNP-WG/ln-types/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [MyCitadel](https://github.com/orgs/mycitadel)

0 merged PRs,
13 closed issues ([1][mycitadel-closed_issues-1]),
11 open issues ([1][mycitadel-open_issues-1])

[mycitadel-closed_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[mycitadel-open_issues-1]: https://github.com/mycitadel/mycitadel-desktop/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

2 merged PRs ([1][nakamoto-merged-prs-1]),
0 closed issues,
0 open issues

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30

#### [Nomic](https://github.com/nomic-io)

2 merged PRs ([1][nomic-merged-prs-1]),
0 closed issues,
5 open issues ([1][nomic-open_issues-1])

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[nomic-open_issues-1]: https://github.com/nomic-io/nomic/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

57 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4], [5][rust_bitcoin-merged-prs-5]),
13 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]),
18 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4], [5][rust_bitcoin-open_issues-5])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-secp256k1/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[rust_bitcoin-merged-prs-5]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[rust_bitcoin-open_issues-5]: https://github.com/rust-bitcoin/rust-bech32-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Rust Simplicity](https://github.com/ElementsProject/rust-simplicity)

1 merged PRs ([1][rust_simplicity-merged-prs-1]),
1 closed issues ([1][rust_simplicity-closed_issues-1]),
0 open issues

[rust_simplicity-merged-prs-1]: https://github.com/ElementsProject/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[rust_simplicity-closed_issues-1]: https://github.com/ElementsProject/rust-simplicity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30

#### [Sapio](https://github.com/sapio-lang/sapio)

5 merged PRs ([1][sapio-merged-prs-1]),
1 closed issues ([1][sapio-closed_issues-1]),
1 open issues ([1][sapio-open_issues-1])

[sapio-merged-prs-1]: https://github.com/sapio-lang/sapio/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[sapio-closed_issues-1]: https://github.com/sapio-lang/sapio/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[sapio-open_issues-1]: https://github.com/sapio-lang/sapio/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Talaia](https://github.com/talaia-labs/rust-teos)

3 merged PRs ([1][talaia-merged-prs-1]),
0 closed issues,
1 open issues ([1][talaia-open_issues-1])

[talaia-merged-prs-1]: https://github.com/talaia-labs/rust-teos/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[talaia-open_issues-1]: https://github.com/talaia-labs/rust-teos/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!

&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

79 merged PRs ([1][ethers-rs-merged-prs-1]),
11 closed issues ([1][ethers-rs-closed_issues-1]),
5 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Lighthouse](https://github.com/sigp/lighthouse)

1 merged PRs ([1][lighthouse-merged-prs-1]),
7 closed issues ([1][lighthouse-closed_issues-1]),
6 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Rust Ethereum](https://github.com/rust-ethereum)

1 merged PRs ([1][rust_ethereum-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2022-04-01..2022-04-30
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

0 merged PRs,
0 closed issues,
4 open issues ([1][rust_web3-open_issues-1])

[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs,
3 closed issues ([1][zksync-closed_issues-1]),
4 open issues ([1][zksync-open_issues-1])

[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2022-04-01..2022-04-30
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2022-04-01..2022-04-30

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online

[Event Sample](https://event.sample)

-->

May 10 - Jun 20 | Online

[Supernova: Dfinity hackthon](https://dfinity.org/supernova/)

May 29-30 | Trondheim, Norway

[CBCrypto 2022: International Workshop on Code-Based Cryptography](https://www.cb-crypto.org/)

May 30 - Jun 3 | Trondheim, Norway

[Eurocrypt 2022](https://eurocrypt.iacr.org/2022/)

Jun 9-12 | Austin, TX, US

[Consensus](https://www.coindesk.com/consensus2022/)

Jun 13-17 | Šibenik, Croatia

[Summer school on real-world crypto and privacy](https://summerschool-croatia.cs.ru.nl/2022/)

Jun 20-23 | New York, US

[NFT.NYC](https://www.nft.nyc/)

Jun 29-30 | Online, multiple cities

[Polkadot Decoded](https://decoded.polkadot.network/)

Aug 7-9 | Online, Las Vegas, US

[Zcon3](https://zfnd.org/zcon3/)

Aug 13-18 | Santa Barbara, CA, US

[Crypto 2022](https://crypto.iacr.org/2022/)

Aug 29-31 | Arrillaga Alumni Center, Stanford University

[SBC'22: The Science of Blockchain Conference 2022](https://cbr.stanford.edu/sbc22/)

Oct 7-16 | Bogota, Colombia

[Devcon Week](https://devcon.org/)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Blockstream | Remote
- [Software Library Engineer (Rust)](https://grnh.se/fc3876861us)
- [Software Library Engineer (C++)](https://grnh.se/69d260dc1us)
- [Network Engineer](https://grnh.se/6ac8f7f11us)
- [Sr. Product Manager](https://grnh.se/11354dd01us)
- [Product Manager](https://grnh.se/1bdd2ced1us)
- [Technical Project Manager](https://grnh.se/ca7b51b81us)
- [QA Engineer](https://grnh.se/ce2891871us)
- [Qt Engineer](https://grnh.se/2bf5f9981us)
- [Don't see a role that fits? Apply here!](https://grnh.se/e53608a01us)

Casa | Remote
- [Senior Infrastructure Engineer](https://tinyurl.com/Sr-Infra-RiB)
- [Lead Infrastructure Engineer](https://tinyurl.com/Lead-Infra-RiB)
- [Senior Backend Software Engineer](https://tinyurl.com/Sr-Backend-RiB)
- [Senior iOS Engineer](https://tinyurl.com/Sr-iOS-RiB)

Cloud-On-Chain | Moscow
- [CTO Cofounder — Rust Core Blockchain Engineer](https://itegmark.substack.com/p/cto-cofounder-rust-core-blockchain)

HashCloak | Toronto, Remote
- [Junior Research Engineer (MPC)](https://hackmd.io/@hashcloak/HJz2Xn3Z9)

Parity | Remote, Berlin, Lisbon, or United Kingdom
- [Rust / Core Engineer - Parachains Engineering](https://grnh.se/24949fb13us)
- [Rust / Core Engineer - Parachains Protocol](https://grnh.se/06ef2e673us)
- [Rust Engineer - Solidity Compiler](https://grnh.se/ea0ffdf73us)
- [Rust Engineer - General opening](https://grnh.se/1cf2de503us)

Web3 Foundation | Zug or Remote
- [Technical Grants Evaluator](https://web3.bamboohr.com/jobs/view.php?id=85)
- [Technical Educator](https://web3.bamboohr.com/jobs/view.php?id=100)
- [Spec Engineer](https://web3.bamboohr.com/jobs/view.php?id=101)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


