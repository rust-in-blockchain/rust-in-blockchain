# RiB Newsletter #9 - Don't Panic

**#9 - Feb 2020**

Welcome to the #9 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #8](https://rustinblockchain.org/2020/02/05/rib-newsletter-8-looking-forward-to-2020/).

Because of coronavirus, some offline conferences have been canceled, and came with more online events. Developers and tech companies start to share remote working experience and encourage the remote-first culture. Nick shares his experience at Remote work [part 1][remote1], [part 2][remote2], [part 3][remote3].

[remote1]: https://www.ncameron.org/blog/remote-work-part-1/
[remote2]: https://www.ncameron.org/blog/remote-work-part-2/
[remote3]: https://www.ncameron.org/blog/remote-work-part-3/

This month, we covered fewer projects in order to save time, but new pull requests about other uncovered projects are welcome!

&nbsp;

## Thanks

This edition of RiB was produced with contributions from [SeungMin Lee][contributorsl], [Alex Gluchowski][contributorag], [María Paula][contributormp], Paulii Good, [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

RiB needs help keeping up with Rust blockchain projects, or, if you find something interesting and beneficial to the Rust & blockchain community, please contribute to the next issue, submit a PR to the [#10 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/blob/master/draft/RiB-Newsletter-%239-Feb-2020.md), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorsl]: https://github.com/somniumism
[contributorag]: https://github.com/gluk64
[contributormp]: https://twitter.com/MPtherealMVP
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[gMorph](https://github.com/golemfactory/gMorph)

gMorph is a [fully homomorphic encryption][fhe] library. Fully homomorphic
encryption allows for arbitrary computation on encrypted data. For an example of
gMorph in practice, see the [gudot] project, which performs linear regression on
[golem].

Golem has [a number of interesting Rust projects][grust].

[fhe]: https://en.wikipedia.org/wiki/Homomorphic_encryption
[gudot]: https://github.com/golemfactory/gudot
[golem]: https://github.com/golemfactory
[grust]: https://github.com/golemfactory?utf8=%E2%9C%93&q=&type=&language=rust

&nbsp;

## Most Active in Feburary

[Solana]: [380 merged PRs][solana-mergedprs], [38 closed issues][solana-closedissues]

[Parity]: 221 merged PRs ([1][parity-mergedpr1], [2][parity-mergedpr2]), 71 closed issues ([1][parity-issue1], [2][parity-issue2]).

[COMIT]: 173 merged PRs ([1][comit-mergedpr1], [2][comit-mergedpr2]), 28 closed issues ([1][comit-issue1], [2][comit-issue2]).

[NEAR]: [67 merged PRs][near-mergedpr], [61 closed issues][near-issue].

[Solana]: https://github.com/solana-labs/solana
[Parity]: https://github.com/paritytech
[COMIT]: https://comit.network/
[NEAR]: https://github.com/nearprotocol/nearcore

&nbsp;

## Project updates

#### [**CodeChain**](https://github.com/codeChain-io/)

72 merged PRs([1][codechain-mergedpr1], [2][codechain-mergedpr2], [3][codechain-mergedpr3], [4][codechain-mergedpr4]),
20 closed issues([1][codechain-issue1], [2][codechain-issue2], [3][codechain-issue3], [4][codechain-issue4]).

[codechain-mergedpr1]: https://github.com/CodeChain-io/codechain/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[codechain-mergedpr2]: https://github.com/CodeChain-io/foundry/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[codechain-mergedpr3]: https://github.com/CodeChain-io/rust-merkle-trie/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[codechain-mergedpr4]: https://github.com/CodeChain-io/rust-codechain-crypto/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[codechain-issue1]: https://github.com/CodeChain-io/codechain/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[codechain-issue2]: https://github.com/CodeChain-io/foundry/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[codechain-issue3]: https://github.com/CodeChain-io/rust-merkle-trie/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[codechain-issue4]: https://github.com/CodeChain-io/rust-codechain-crypto/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- New release: [CodeChain SDK in Python](https://medium.com/codechain/codechain-sdk-in-python-fe46938adbf8)
  - [Github Repository](https://github.com/CodeChain-io/codechain-sdk-python)
- Blog: [CodeChain SDK in Golang](https://medium.com/codechain/codechain-sdk-in-golang-da9dbd7b1fd)
- Blog: [Adapting BLS Signature Aggregation to CodeChain Foundry](https://medium.com/codechain/adapting-bls-signature-aggregation-to-codechain-foundry-7767d6656e5b)
- Blog: [Blockchain Light Client](https://medium.com/codechain/blockchain-light-client-1171dfa1269a)
- Blog: [Front-Running Attacks on Blockchain](https://medium.com/codechain/front-running-attacks-on-blockchain-1f5ba28cd42b)
- PR: [Introduce BLS signature aggregation scheme](https://github.com/CodeChain-io/foundry/pull/151)
- PR: [Replace the rust-crypto crate to other crates](https://github.com/CodeChain-io/rust-codechain-crypto/pull/8)
- PRs: [Interchain Standards; ICS](https://github.com/CodeChain-io/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03+label%3Aics)
- Issue: [Implement ICS](https://github.com/CodeChain-io/foundry/issues/105)
- Issue: [Implement basic RPCs for ICS](https://github.com/CodeChain-io/foundry/issues/192)
- Issue: [Implement light client](https://github.com/CodeChain-io/foundry/issues/126)
- Issue: [Implement Merkle proof for the ICS entries in the state DB](https://github.com/CodeChain-io/foundry/issues/112)


#### [**COMIT**](https://comit.network/)

173 merged PRs ([1][comit-mergedpr1], [2][comit-mergedpr2]), 28 closed issues ([1][comit-issue1], [2][comit-issue2]).

[comit-mergedpr1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[comit-mergedpr2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[comit-issue1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[comit-issue2]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- News: [February, 2020 - Dev Update](https://comit.network/blog/2020/03/02/february-dev-update/)
- PR: [Re-design the matching_transaction logic for Ethereum](https://github.com/comit-network/comit-rs/pull/2039)
- PR: [Unroll some implementations generic over ledger::Bitcoin](https://github.com/comit-network/comit-rs/pull/1992)
- PR: [Bitcoin matching transactions refactor](https://github.com/comit-network/comit-rs/pull/2098)
- Issue: [Minimal viable ledger configuration strategy](https://github.com/comit-network/comit-rs/issues/1844)

#### [**Grin**](https://github.com/mimblewimble/grin)

[28 merged PRs][grin-mergedpr], [12 closed issues][grin-issue].

[grin-mergedpr]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[grin-issue]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- News: [87: Grin v3.1.0 released](https://grinnews.substack.com/p/87-grin-v310-released-)
- News: [86: New node release in the works](https://grinnews.substack.com/p/86-new-node-release-in-the-works)
- News: [85: RFC activity](https://grinnews.substack.com/p/86-new-node-release-in-the-works)
- News: [84: Preparations for Wallet v3.1.0](https://grinnews.substack.com/p/84-preparations-for-wallet-v310-)
- PR: [Block input bitmap rework](https://github.com/mimblewimble/grin/pull/3236)
- PR: [Attempt to read ipv4-mapped ipv6 to ipv4 if possible](https://github.com/mimblewimble/grin/pull/3221)
- Issue: [The block was not credited](https://github.com/mimblewimble/grin/issues/3257)
- Issue: [100% cpu load on all nodes](https://github.com/mimblewimble/grin/issues/3237)

#### [**Holochain**](https://github.com/holochain/)

[30 merged PRs][holochain-mergedpr],
[2 closed issues][holochain-closedissues].

[holochain-mergedpr]: https://github.com/holochain/holochain-rust/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[holochain-closedissues]: https://github.com/holochain/holochain-rust/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- News: [Holochain Dev Pulse 65](https://blog.holochain.org/the-community-runs-with-the-ball/)
- News: [Holochain Dev Pulse 64](https://blog.holochain.org/integration-efforts-5000-nodes/)
- News: [Monthly Roundup for Holo & Holochain](https://medium.com/h-o-l-o/monthly-roundup-for-holo-holochain-1c31f2c0b841)
- Blog: [Why CAL is Important To The End User?](https://medium.com/holochain/why-cal-is-important-to-the-end-user-aec58b2ff730)
- PR: [Tracing pt. 1](https://github.com/holochain/holochain-rust/pull/1925)
- Issue: [Unable to access child (to!) links when parent is updated](https://github.com/holochain/holochain-rust/issues/2106)

#### [**NEAR**](https://github.com/nearprotocol/nearcore)

[67 merged PRs][near-mergedpr], [61 closed issues][near-issue].

[near-mergedpr]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Amerged+merged%3A2020-02-01..2020-03-03
[near-issue]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- New Release: [The Open Web Collective Incubator and Accelerator](https://openwebcollective.com/)
- News: [NEAR Community Update: February 28th, 2020](https://nearprotocol.com/blog/near-community-update-february-28th-2020/)
- News: [NEAR Community Update: February 14th, 2020](https://nearprotocol.com/blog/near-community-update-february-14th-2020/)
- News: [“Into the Open Web”, China Community AMA](https://nearprotocol.com/blog/openwebchinaama/)
- Blog: [Running Ethereum Applications On NEAR](https://nearprotocol.com/blog/running-ethereum-applications-on-near/)
- Blog: [Doomslug vs PBFT, Tendermint, and Hotstuff](https://nearprotocol.com/blog/doomslug-comparison/)
- Blog: [How do Randomness Beacons based on Threshold Signatures work?](https://nearprotocol.com/blog/randomness-threshold-signatures/)
- Discussion: [How to stop shard congestion attack  ](https://github.com/nearprotocol/nearcore/issues/2196)
- PR: [Block production summary in 100 node](https://github.com/nearprotocol/nearcore/pull/1876)
- PR: [feat(runtime): Validate incoming receipts](https://github.com/nearprotocol/nearcore/pull/2155)
- Issue: [Use master branch for development](https://github.com/nearprotocol/nearcore/issues/2165)

#### [**Nervos**](https://github.com/nervosnetwork)

112 merged PRs ([1][nervos-mergedpr1], [2][nervos-mergedpr2], [3][nervos-mergedpr3], [4][nervos-mergedpr4], [5][nervos-mergedpr5]), 6 closed issues ([1][nervos-issue1], [2][nervos-issue2], [3][nervos-issue3], [4][nervos-issue4], [5][nervos-issue5]).

[nervos-mergedpr1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-02-29
[nervos-mergedpr2]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[nervos-mergedpr3]: https://github.com/nervosnetwork/overlord/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[nervos-mergedpr4]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[nervos-mergedpr5]: https://github.com/nervosnetwork/neuron/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[nervos-issue1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[nervos-issue2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[nervos-issue3]: https://github.com/nervosnetwork/overlord/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[nervos-issue4]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[nervos-issue5]: https://github.com/nervosnetwork/neuron/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- News: [Huobi Finance Chain Launches Public Beta](https://medium.com/nervosnetwork/huobi-finance-chain-launches-public-beta-8391fd5a5dac). The high-performance decentralized finance (DeFi) chain is now live for beta testing by developers, enterprises, regulators, miners, and the rest of the blockchain ecosystem.
- News: [Nervos Network: First Ecosystem Grants Awarded](https://medium.com/nervosnetwork/nervos-network-first-ecosystem-grants-awarded-dd32b377dbb2)
- News: [You can now post your Grant Program submission directly on Nervos Talk.](https://twitter.com/NervosNetwork/status/1233544920452853762)
- News: [Community Chat with Obsidian Labs Co-founder Rose Ren](https://medium.com/nervosnetwork/community-chat-with-obsidian-labs-co-founder-rose-ren-550c136fe6e3)
- News: [Community Chat with Summa Founder James Prestwich](https://medium.com/nervosnetwork/community-chat-with-summa-founder-james-prestwich-7cb4f55afd97)
- News: [Nervos CKB Development Update #29](https://medium.com/nervosnetwork/nervos-ckb-development-update-29-6172a71b985f). Released CKB v0.28.0 and Neuron v0.28.0. An example of molecule plugin: [Go plugin](https://github.com/driftluo/moleculec-go).
- News: [Nervos CKB Development Update #28](https://medium.com/nervosnetwork/nervos-ckb-development-update-28-5c85be7a599e)
- Podcast: [Epicenter: Nervos – Scaling Smart Contact Blockchains With Proof of Work and Generalized UTXO](https://epicenter.tv/episodes/326/)
- Blog: [Animagus Part 1: Introduction](https://medium.com/nervosnetwork/https-medium-com-nervosnetwork-animagus-part-1-introduction-66fa8ce27ccd-cfb361a7d883). Animagus is a special built tool, an account layer for CKB, to enable the CKB potential. The name comes from the Harry Potter series.
- Blog: [An optimized compacted sparse merkle tree](https://justjjy.com/An-optimized-compact-sparse-merkle-tree)
- Blog: [Introduction to CKB Script Programming 8: Performant WASM](https://xuejie.space/2020_03_03_introduction_to_ckb_script_programming_performant_wasm/)
- Blog: [Introduction to CKB Script Programming 7: Advanced Duktape Examples](https://xuejie.space/2020_02_21_introduction_to_ckb_script_programming_advanced_duktape_examples/)
- Blog: [Let's Build a Minimal Blockchain 2: Ultimate Upgradability](https://xuejie.space/2020_02_08_lets_build_a_minimal_blockchain_ultimate_upgradability/)
- Blog: [Introduction to CKB Script Programming 6: Type ID ](https://xuejie.space/2020_02_03_introduction_to_ckb_script_programming_type_id/)
- Wiki: [Handle Complex Transaction](https://github.com/nervosnetwork/ckb-cli/wiki/Handle-Complex-Transaction), explains how to construct complex transaction using ckb-cli.
- PR: [AOT mode changes](https://github.com/nervosnetwork/ckb-vm/pull/96)
- PR: [Feat: Reject new scripts with known bugs](https://github.com/nervosnetwork/ckb/pull/1915)
- PR: [Feat: Define StatusCode to indicate the result of sync operation](https://github.com/nervosnetwork/ckb/pull/1856)
- Issue: [A utility to run CKB VM scripts](https://github.com/nervosnetwork/ckb/issues/1943)

#### [**Parity** ](https://github.com/paritytech)

221 merged PRs ([1][parity-mergedpr1], [2][parity-mergedpr2]), 71 closed issues ([1][parity-issue1], [2][parity-issue2]).

[parity-mergedpr1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Amerged+merged%3A2020-02-01..2020-03-03
[parity-mergedpr2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Amerged+merged%3A2020-02-01..2020-03-03
[parity-issue1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[parity-issue2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- News: [Major Milestone Achieved: Polkadot and Chainlink Integration Using Substrate](https://polkadot.network/chainlink-reaches-milestone-with-polkadot)
- News: [Polkadot will feature layer two scaling thanks to Celer Network](https://cointelegraph.com/news/polkadot-will-feature-layer-two-scaling-thanks-to-celer-network)
- Blog: [Write Wasm smart contracts with ink! 2.0](https://www.parity.io/write-wasm-smart-contracts-with-ink-2-0/)
- Blog: [Built on Substrate: KILT Protocol](https://www.parity.io/built-on-substrate-kilt-protocol/)
- Blog: [Contributors Join OpenEthereum](https://www.parity.io/contributors-join-openethereum/)
- Blog: [The Path of a Parachain Block](https://polkadot.network/the-path-of-a-parachain-block/)
- Video: [Web3 Builders: Polymesh](https://www.crowdcast.io/e/polkadot-web3-polymath-polymesh-builders)
- Video: [Sub0.1: Gavin Wood presents Polkadot's cross-chain messaging (XCMP) scheme](https://www.youtube.com/watch?v=wrA9vlPjVPE)
- Video: [Solving the NPoS Problem with Phragmen -- Substrate Seminar 25 February 2020](https://www.youtube.com/watch?v=MjOvVhc1oXw)
- Video: [Built on Substrate: What it's like building on Substrate blockchain framework](https://www.youtube.com/watch?v=WFbUc15ZhgU)
- PR: [Offchain Workers: Example Pallet](https://github.com/paritytech/substrate/pull/4989)
- PR: [A more comprehensive model for PoV-Blocks and Candidate receipts](https://github.com/paritytech/polkadot/pull/843)
- Issue: [Inflation 10% higher than set](https://github.com/paritytech/substrate/issues/4964)
- Issue: [RPC method state_nextKey](https://github.com/paritytech/substrate/issues/4717)
- Issue: [Link to llvm on Mac OSX in README](https://github.com/paritytech/substrate/issues/1454)

#### [**Solana**](https://github.com/solana-labs/solana)

[380 merged PRs][solana-mergedprs], [38 closed issues][solana-closedissues].

[solana-mergedprs]: https://github.com/solana-labs/solana/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[solana-closedissues]: https://github.com/solana-labs/solana/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- Release: [Solana released version 1.0](https://github.com/solana-labs/solana/releases/tag/v1.0.0)
- Blog: [Solana: You can’t turn back the hands of time](https://medium.com/dokia/solana-you-cant-turn-back-the-hands-of-time-e80b2d280fe1)
- Podcast: [Vinny Lingham - CEO of Civic / General Partner at Multicoin Capital Ep #16](https://podcast.solana.com/episodes/vinny-lingham-ceo-of-civic-general-partner-at-multicoin-capital-ep-16-SGiLlm94)
- Podcast: [Jill Carlson - Partner at Slow Ventures / Co-Founder Of The Open Money Initiative Ep #15](https://podcast.solana.com/episodes/jill-carlson-partner-at-slow-ventures-co-founder-of-the-open-money-initiative-Mi_Y_MzG)
- Podcast: [Meher Roy & Reisen - Co-Founders of Chorus One Ep #14](https://podcast.solana.com/episodes/meher-roy-reisen-co-founders-of-chorus-one-ep-14-jqjbaRT9)
- PR: [Hack to skip cleanup_dead_slots upon snapshot load](https://github.com/solana-labs/solana/pull/8561)
- PR: [Do periodic inbound cleaning for rooted slots](https://github.com/solana-labs/solana/pull/8436)
- PR: [Ledger hardware wallet integration](https://github.com/solana-labs/solana/pull/8068)
- Issue: [PoH on SLP2 is going very slowly](https://github.com/solana-labs/solana/issues/8445)
- Issue: [CLI exposes implementation detail "lamports"](https://github.com/solana-labs/solana/issues/8296)
- Issue: [TdS consensus lost at slot 797572](https://github.com/solana-labs/solana/issues/8189)

#### [**Zcash**](https://z.cash/)

39 merged PRs ([1][zcash-mergedprs1], [2][zcash-mergedprs2]),
15 closed issues ([1][zcash-closedissues1], [2][zcash-closedissues2]).

[zcash-mergedprs1]: https://github.com/ZcashFoundation/zebra/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[zcash-mergedprs2]: https://github.com/zcash/librustzcash/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-02-01..2020-03-03
[zcash-closedissues1]: https://github.com/ZcashFoundation/zebra/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03
[zcash-closedissues2]: https://github.com/zcash/librustzcash/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-02-01..2020-03-03

- News: [ECC scaling research: 2019 research & development milestones](https://electriccoin.co/blog/ecc-scaling-research-2019-research-development-milestones/)
- News: [Funding of Zcash from November: ZIP 1014 is final](https://www.crypto-news-flash.com/funding-of-zcash-from-november-zip-1014-is-final/)
- News: [Zcash Foundation Update • February 1 – March 3, 2020](https://news.zfnd.org/archive/zcash-foundation-update-february-1-march-3-2020/)
- News: [TOR Browser To Recieve $50000 From Zcash](https://cryptosyringe.com/tor-browser-to-recieve-50000-from-zcash/8488/)
- News: [Q1 2020 Livestream Video + Q&A](https://forum.zcashcommunity.com/t/q1-2020-livestream-video-q-a/36038)
- News: [New Releases: 2.1.1 and hotfix 2.1.1-1](https://electriccoin.co/blog/new-releases-2-1-1-and-hotfix-2-1-1-1/)
- News: [ECC Engineering flight plan: Mid-horizon update](https://electriccoin.co/blog/ecc-engineering-flight-plan-mid-horizon-update/)
- Blog: [Dev Fund poll shows consensus](https://electriccoin.co/blog/dev-fund-poll-shows-consensus/)
- Blog: [What is Zcash (ZEC)? — 'The ‘Hidden’ Bitcoin…' — Beginner's Guide](https://www.publish0x.com/the-crypto-enthusiast-blog-intro/what-is-zcash-zec-the-hidden-bitcoin-beginners-guide-xqzgwq)
- Blog: [A brief history of Zcash decentralization](https://forum.zcashcommunity.com/t/a-brief-history-of-zcash-decentralization/35935)
- Blog: [Search & Destroy](https://www.zcashcommunity.com/2020/02/07/search-destroy/)
- Blog: [Decoding Bitcoin Messages with Tokio Codecs](https://www.zfnd.org/blog/decoding-bitcoin-messages-with-tokio-codecs/)
- Video: [Zcash Foundation’s Josh Cincinnati on the Governance Vote](https://www.youtube.com/watch?v=hCNGhm-gDr0)
- PR: [Memo type, existing EncryptedCiphertext types for Sprout and Sapling](https://github.com/ZcashFoundation/zebra/pull/249)
- Issue: [Research Spike: Design work on Data Access API](https://github.com/zcash/librustzcash/issues/150)
- Issue: [Add `secp256k1` and possibly wrap its types](https://github.com/ZcashFoundation/zebra/issues/264)

&nbsp;

## Learning

[Token Engineering Learning Program](https://www.tannrallard.tech/token-engineering-learning-program/)

[Onboarding to Bitcoin Core](https://medium.com/@amitiu/onboarding-to-bitcoin-core-7c1a83b20365)

[Programs, life cycles, and laws of software evolution](https://blog.acolyer.org/2020/02/14/programs-life-cycles-laws/)

&nbsp;

## Interesting Things

[lalotai/rust-blockchain](https://github.com/lalotai/rust-blockchain). A simple blockchain in Rust.

[Super Bowl mentioned Rust](https://twitter.com/TedMielczarek/status/1229130460929888258)

&nbsp;

## Events

Mar 4-11 | London, UK

[London Blockchain Week](https://www.blockchainweek.com/)

Mar 7-8 | MIT Campus, US

[MIT Bitcoin Expo 2020](https://mitbitcoinexpo.org/)

Mar 31 - Apr 1 | Paris, France

[Paris Blockchain Week Summit](https://www.pbwsummit.com/)

Apr 13-16 | Oxford, UK

[IEEE DAPPS 2020](https://ieeedapps.net/)

&nbsp;

## Careers

imToken | Singapore; Hangzhou, China

[Blockchain Development Engineer](https://token.im/careers#jobs)

Nervos | Remote

[Developer Relations](https://angel.co/company/nervos-1/jobs/710826-developer-relations)

Nervos | Hangzhou, China; Remote

[Senior blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

PureStake | Boston, US

[Blockchain Engineer](https://www.linkedin.com/jobs/view/1745360752/)


&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#10 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/blob/master/draft/RiB-Newsletter-%2310-Mar-2020.md), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
