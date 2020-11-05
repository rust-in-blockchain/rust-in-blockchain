# RiB Newsletter #17

Publish on 4th Nov, 2020

Welcome to the #17 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. 
[Previous: #16](/newsletters/2020-09-30-secure-enclaves-a-la-crab/).

Hiring for Rust blockchain developers seems to be increasing,
particulary within the Chinese Rust communities,
where we see some new blockchain startups using Rust,
including [Patract Labs], who are developing on Substrate,
and [TaiDi Tech].
A Rust conference is [being planned for December in Shanghai][rcc],
and there are likely to be talks from major Rust blockchain companies.

[rcc]: https://rustcc.cn/article?id=33c3384f-9401-481a-b508-d13f49dd7f87
[Patract Labs]: https://github.com/patractlabs
[TaiDi Tech]: http://taiditech.com/

Some changes in RiB:

We updated the [contributing](https://rustinblockchain.org/contributing) policies a bit,
and the [RiB Newsletter](https://rustinblockchain.org/newsletters) now only accepts contributions through GitHub pull requests,
not email or other means.
This will both reduce our workload, and create a proper record of who contributed what.
Thanks for your cooperation.

We are being more selective about what goes into the "Project Updates" sections,
as the volume of content there had gotten overwhelming in previous months.
Hopefully these sections will be more focused and meaningful in the future.

On the website,
we added [learning resources](https://rustinblockchain.org/learning) for new blockchain programmers.
Please contribute content as well as suggestions to this page,
and let's improve the learning experience together.

&nbsp;

## Thanks

Thanks to contributors:
[apruden2008][contributor-alex],
[ashput][contributor-ashput],
[Damascene][contributor-damascene],
[Daniel Karzel][contributor-dakami],
[David Ansermino][contributor-ansermino],
[Mikko Ohtamaa][contributor-miohtama],
[Paulii][contributor-paulii],
[Brian Anderson][contributorba], and [Aimee Zhu][contributoraz].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue. 
by submitting a PR to the [#18 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributor-alex]: https://github.com/apruden2008
[contributor-ashput]: https://github.com/ashput
[contributor-dakami]: https://github.com/da-kami
[contributor-damascene]: https://github.com/damascene
[contributor-miohtama]: https://github.com/miohtama
[contributor-ansermino]: https://github.com/ansermino
[contributor-paulii]: https://github.com/PauliiG22
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[lnp-node].

`lnp-node` is an implementation of the [Lightning Network][ln] in Rust,
created by the [LNP/BP Standards Association][lnpbp].

It's not obvious how this implementation relates to the reference implementation,
but between the [LNP-BP] GitHub org and the [rust-bitcoin] GitHub org,
which LNP-BP depends on,
there is quite a lot of development going into Bitcoin implementations in Rust.

It's active and well documented, so for Rust hackers looking to get involved
in Bitcoin layer 2 development, this seems like a promising entry point.

`lnp-node` has a modular architecture that depends on a number of other
Rust crates that look like they could be reused with relative ease:

- [`rust-lnpbp`] - the lightning network protocol
- [`rust-bitcoin`] - the bitcoin protocol (but not a full node)
- [`rust-secp256k1`] - bindings to the official implementation of bitcoin's elliptic curve
- [`rust-miniscript`] - implementation of a subset of Bitcoin Script
- [`rust-amplify`] - some rust-language helpers, including generic trait implementations, type wrappers and custom derives

[lnp-node]: https://github.com/LNP-BP/lnp-node
[ln]: https://lightning.network/
[lnpbp]: https://www.lnp-bp.org/
[LNP-BP]: https://github.com/LNP-BP
[rust-bitcoin]: https://github.com/rust-bitcoin
[`rust-lnpbp`]: https://github.com/LNP-BP/rust-lnpbp
[`rust-bitcoin`]: https://github.com/rust-bitcoin/rust-bitcoin
[`rust-secp256k1`]: https://github.com/rust-bitcoin/rust-secp256k1
[`rust-miniscript`]: https://github.com/rust-bitcoin/rust-miniscript
[`rust-amplify`]: https://github.com/LNP-BP/rust-amplify


&nbsp;


## Interesting Things

#### News

- Conflux: [Tethys Mainnet is Live](https://medium.com/conflux-network/tethys-mainnet-is-live-cd9819a96ae3)

#### Blog Posts

- [A pitfall of Rust's move/copy/drop semantics and zeroing data](https://benma.github.io/2020/10/16/rust-zeroize-move.html)
- [Rusty Chains: A Basic Blockchain Implementation Written in Pure Rust](https://hackernoon.com/rusty-chains-a-basic-blockchain-implementation-written-in-pure-rust-gk2m3uri)
- [Towards formal semantics of the beacon chain’s pyspec](https://ethresear.ch/t/towards-formal-semantics-of-the-beacon-chains-pyspec/8181)
- [Rust no-std FAQ](https://justjjy.com/Rust-no-std). Basic and useful.
- [Rust after the honeymoon](http://dtrace.org/blogs/bmc/2020/10/11/rust-after-the-honeymoon/).
  It isn't blockchain related.
  The write features some that also very useful for blockchain developers.
- [An Interview with Torben P. Pedersen](https://medium.com/asecuritysite-when-bob-met-alice/an-interview-with-torben-p-pedersen-c50b84182767)
  about the Pedersen Commitment.
- [Playing with Randomness and Interactions to Prove Theorems](https://zkproof.org/2020/10/15/randomness-and-interactions/)
- [Privacy is normal, safe and essential](https://electriccoin.co/blog/privacy-is-normal-safe-and-essential/)
- [SNARKs and the future of blockchains](https://medium.com/@RubenSomsen/snarks-and-the-future-of-blockchains-55b82012452b)
- [People of Parity: Bastian Köcher](https://www.parity.io/people-of-parity-bastian-koecher/).
  Besides technology, Parity also creates lovely developer stories.

#### Papers 

- [Towards Cross-Blockchain Smart Contracts](https://arxiv.org/pdf/2010.07352.pdf)
- [EVMPatch: Timely and Automated Patching of Ethereum Smart Contracts](https://arxiv.org/pdf/2010.00341.pdf)
  and the studies on [GitHub](https://github.com/uni-due-syssec/evmpatch-developer-study)
- [Aardvark: A Concurrent Authenticated Dictionary with Short Proofs](https://eprint.iacr.org/2020/975.pdf)
- [Incrementally Aggregatable Vector Commitments and Applications to Verifiable Decentralized Storage](https://eprint.iacr.org/2020/149.pdf)
- [CoVer: Collaborative Light-Node-Only Verification and Data Availability for Blockchains](https://arxiv.org/pdf/2010.00217.pdf)
- [Using Homomorphic hashes in coded blockchains](https://arxiv.org/pdf/2010.04607.pdf)
- [KVaC: Key-Value Commitments for Blockchains and Beyond](https://eprint.iacr.org/2020/1161.pdf)
- [Authenticated Dictionaries with Cross-Incremental Proof (Dis)aggregation](https://eprint.iacr.org/2020/1239.pdf)
- [PoSAT: Proof-of-Work Availability and Unpredictability, without the Work](https://arxiv.org/pdf/2010.08154.pdf)
- [Proofs, Arguments, and Zero-Knowledge](http://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf)
- [Post-Quantum Linkable Ring Signature Enabling Distributed Authorised Ring Confidential Transactions in Blockchain](https://eprint.iacr.org/2020/1121.pdf)
- [Global Standards Mapping Initiative: An overview of blockchain technical standards](http://www3.weforum.org/docs/WEF_GSMI_Technical_Standards_2020.pdf)
- Doc: [Cryptographic Best Practices](https://gist.github.com/atoponce/07d8d4c833873be2f68c34f9afc5a78a)


#### Projects

- [Curve on Zinc](https://github.com/matter-labs/curve-zinc).
  The Curve Stableswap smart contract implementation in Zinc v0.2.0.
- [Marlin](https://github.com/o1-labs/marlin) contains
  various zk-SNARK protocol implementations for
  recursive SNARK composition.
- [Oak](https://github.com/project-oak/oak).
  Meaningful control of data in distributed systems.
- [Serum-dex](https://github.com/project-serum/serum-dex).
- [BTC-Parachain](https://github.com/interlay/BTC-Parachain).
  BTC-Parachain: Trustless Bitcoin on Polkadot (Mirror).
- [arcturus](https://github.com/cargodog/arcturus).
  A pure rust implementation of Arcturus proofs for
  confidential transactions.
  - Its paper [Arcturus: efficient proofs for confidential
    transactions](https://eprint.iacr.org/2020/312)


&nbsp;

## Most Active in October

[Solana](https://github.com/solana-labs/solana):
240 merged PRs ([1][solana-merged-prs-1]),
29 closed issues ([1][solana-closed_issues-1]), 
31 open issues ([1][solana-open_issues-1])

[Parity](https://github.com/paritytech):
191 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]),
110 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4]), 
53 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[Libra](https://libra.org):
199 merged PRs ([1][libra-merged-prs-1]),
21 closed issues ([1][libra-closed_issues-1]), 
22 open issues ([1][libra-open_issues-1])

[Zcash](https://z.cash/):
93 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]),
25 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2]), 
30 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])


&nbsp;

## Project Updates

#### [Aleo](https://github.com/AleoHQ)

36 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2]), 3 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2]), 
5 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[aleo-open_issues-1]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31
[aleo-open_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- PR: [Use criterion in curve benchmarks](https://github.com/AleoHQ/snarkOS/pull/483) by @ljedrz
- PR: [Initial Storage Implementation for Setup Coordinator](https://github.com/AleoHQ/aleo-setup/pull/100) by @howardwu
- PR: [Implement a Verifier Instance for Setup Ceremony](https://github.com/AleoHQ/aleo-setup/pull/107) by @raychu86

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

61 merged PRs ([1][rust-bitcoin-merged-prs-1], [2][rust-bitcoin-merged-prs-2], [3][rust-bitcoin-merged-prs-3], [4][rust-bitcoin-merged-prs-4]), 12 closed issues ([1][rust-bitcoin-closed_issues-1], [2][rust-bitcoin-closed_issues-2], [3][rust-bitcoin-closed_issues-3], [4][rust-bitcoin-closed_issues-4]), 15 open issues ([1][rust-bitcoin-open_issues-1], [2][rust-bitcoin-open_issues-2], [3][rust-bitcoin-open_issues-3])

[rust-bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[rust-bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[rust-bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[rust-bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/bitcoin_hashes/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[rust-bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[rust-bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[rust-bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[rust-bitcoin-closed_issues-4]: https://github.com/rust-bitcoin/bitcoin_hashes/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[rust-bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31
[rust-bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31
[rust-bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- PR: [Refactor chain monitoring](https://github.com/rust-bitcoin/rust-lightning/pull/649) by [@jkczyz](https://github.com/jkczyz)
- PR: [Add ChannelDataPersister trait and point ChainMonitor to it.](https://github.com/rust-bitcoin/rust-lightning/pull/681) by [@valentinewallace](https://github.com/valentinewallace)
- PR: [DescriptorPublicKey, second pass](https://github.com/rust-bitcoin/rust-miniscript/pull/131) by [@darosior](https://github.com/darosior)

#### [COMIT](https://github.com/comit-network)

58 merged PRs([1][comit-rs], [2][xmr-btc-swaps], [3][ambrosia]),

[comit-rs]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31+NOT+bump
[xmr-btc-swaps]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31+NOT+bump
[ambrosia]: https://github.com/comit-network/ambrosia/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31+NOT+bump

- R&D: [XMR-BTC swaps](https://comit.network/blog/2020/10/06/monero-bitcoin)
- News: [Trade Bitcoin and DAI with COMIT - Alpha version of our non-custodial trading UI released](https://comit.network/blog/2020/10/12/ambrosia-alpha-release)
- News: [Designing GitHub workflows for automated releases](https://comit.network/blog/2020/09/25/gh-release)

#### [Holochain](https://github.com/holochain/)

0 merged PRs, 0 closed issues, 1 open issues ([1][holochain-open_issues-1])

[holochain-open_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News: Dev Pulse
  - [A Look at the Holo Hosting Infrastructure](https://blog.holochain.org/a-look-at-the-holo-testnet-coming-soon/)
  - [Migrating Your Holochain App To RSM](https://blog.holochain.org/migrating-your-holochain-app-to-rsm/)
- Blog:
  - [Building Together: RedGrid’s ‘Internet of Energy’ Mission and the Holochain Community](https://blog.holochain.org/building-together-redgrids-internet-of-energy-mission-and-the-holochain-community/)
  - [Holo Today – The Path from RSM to Beta](https://medium.com/h-o-l-o/the-path-from-rsm-to-beta-1fdca3f581a)
- Videos:
  - [Holochain Ecosystem Sessions with Acorn](https://youtu.be/qUHyxUk8mlw)
  - [Acorn Quick Demo](https://youtu.be/FBCsQHRLsGA)
  -  [Holo AMA 43](https://youtu.be/IlW4CP5HGV8)
  - [Demo First Hosted hApp Available via a Web Browser](https://youtu.be/xj2zSvLjViU)

#### [Libra](https://libra.org)

199 merged PRs ([1][libra-merged-prs-1]), 21 closed issues ([1][libra-closed_issues-1]), 
22 open issues ([1][libra-open_issues-1])

[libra-merged-prs-1]: https://github.com/libra/libra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[libra-closed_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[libra-open_issues-1]: https://github.com/libra/libra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News: [Testnet push announcement for 10/14](https://community.libra.org/t/testnet-push-announcement-for-10-14/3176)
- PR: [[network][fuzzing] Fuzz inbound `NetworkMessage` handling and fix memory leak](https://github.com/libra/libra/pull/6601) by [@phlip9](https://github.com/phlip9)
- PR: [[xbuild] cleaner install and initial pass at xbuild wiring](https://github.com/libra/libra/pull/6212) by [@rexhoffman](https://github.com/rexhoffman)
- PR: [[network] improve context and clarity of noise handshake errors](https://github.com/libra/libra/pull/6367) by [@phlip9](https://github.com/phlip9)
  
#### [Lighthouse](https://lighthouse.sigmaprime.io/)

4 merged PRs ([1][lighthouse-merged-prs-1]), 48 closed issues ([1][lighthouse-closed_issues-1]), 
30 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News: [Lighthouse Update #30](https://lighthouse.sigmaprime.io/update-30.html)
- PR: [Update blst and milagro_bls subgroup checking](https://github.com/sigp/lighthouse/pull/1793) by [@kirk-baird](https://github.com/kirk-baird)
- PR: [Staging: v0.3.0](https://github.com/sigp/lighthouse/pull/1671) by [@paulhauner](https://github.com/paulhauner)
- PR: [Upgrade discovery and restructure task execution](https://github.com/sigp/lighthouse/pull/1693) by [@AgeManning](https://github.com/AgeManning)

#### [MobileCoin](https://www.mobilecoin.com/)

49 merged PRs ([1][mobilecoin-merged-prs-1]), 1 closed issues ([1][mobilecoin-closed_issues-1]), 
0 open issues ()

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31

- PR: [Make a constant time aes-gcm decrypt and use in cryptobox](https://github.com/mobilecoinfoundation/mobilecoin/pull/434) by [@xoloki](https://github.com/xoloki)
- PR: [Make a stderr configuration of the logger module, and use it in tests](https://github.com/mobilecoinfoundation/mobilecoin/pull/537) by [@garbageslam](https://github.com/garbageslam)

#### [NEAR](https://github.com/nearprotocol/nearcore)

41 merged PRs ([1][near-merged-prs-1]), 54 closed issues ([1][near-closed_issues-1]), 
42 open issues ([1][near-open_issues-1])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

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
- Videos: Whiteboard Series with NEAR
  - [Ep: 41 Matt Luongo from Thesis](https://www.youtube.com/watch?v=vak7uyN3GtE)
  - Ep: 40 John Adler from Lazy Ledger [Part1](https://www.youtube.com/watch?v=jM-om3AqH94) [Part2](https://www.youtube.com/watch?v=MZQMObV3890)
  - [Alexey Akhunov from TurboGeth](https://www.youtube.com/watch?v=H2YLVP3jyaI)
- PR: [feat(chain): Versioned ShardChunkHeader](https://github.com/near/nearcore/pull/3463) by [@birchmd](https://github.com/birchmd)
- PR: [fix: make outcome ids ordered in storage](https://github.com/near/nearcore/pull/3529) by [@bowenwang1996](https://github.com/bowenwang1996)
- PR: [fix(genesis): Don't write genesis records on restart](https://github.com/near/nearcore/pull/3470) by [@mikhailOK](https://github.com/mikhailOK)

#### [Nervos](https://github.com/nervosnetwork)

30 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]), 6 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2]), 4 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/rfcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/rfcs/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News:
  - [Bitpie builds stablecoin bridge between Ethereum and CKB](https://medium.com/nervosnetwork/bitpie-builds-stablecoin-bridge-between-ethereum-and-ckb-d6a4b30cc92)
  - [Advanced CKB mining infrastructure with Insight](https://medium.com/nervosnetwork/grant-approved-advanced-ckb-mining-infrastructure-with-insight-956146955dc5)
- Blog:
  - [Session with #NervosHack winners SECBIT, NerBRos, and LeapDAO](https://medium.com/nervosnetwork/q-a-session-with-nervoshack-winners-secbit-nerbros-and-leapdao-1b22a92cebaf)
  - [Portal Wallet and pw-sdk: Connecting blockchain users around the world](https://medium.com/nervosnetwork/portal-wallet-and-pw-sdk-connecting-blockchain-users-around-the-world-78027e0860e7)
- PR: [docs: deny missing docs](https://github.com/nervosnetwork/ckb/pull/2313) by [@doitian](https://github.com/doitian)
- PR: [chore: upgrade rust toolchain to 1.46](https://github.com/nervosnetwork/ckb/pull/2296) by [@driftluo](https://github.com/driftluo)

#### [Parity](https://github.com/paritytech)

191 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]), 110 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4]), 
53 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[parity-merged-prs-3]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[parity-closed_issues-3]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[parity-closed_issues-4]: https://github.com/paritytech/parity-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News:
  - [Polkadot Staking: An Update](https://polkadot.network/polkadot-staking-an-update/)
  - [Bitcoin is Coming to Polkadot](https://polkadot.network/bitcoin-is-coming-to-polkadot/)
- Blog:
  - [Obtaining a Parachain Slot on Polkadot](https://polkadot.network/obtaining-a-parachain-slot-on-polkadot/)
  - [Substrate 2.0.0 Release Deep-Dive](https://www.parity.io/substrate-2-0-release-deep-dive/)
- Videos: Substrate Seminar: [Benchmarking for your Substrate Pallet](https://www.youtube.com/watch?v=Qa6sTyUqgek),
  [Substrate Analytics](https://www.youtube.com/watch?v=0CojsjfvP18)  
- PR: [Async keystore + Authority-Discovery async/await](https://github.com/paritytech/substrate/pull/7000) by [@rakanalh](https://github.com/rakanalh)
- PR: [Runtime worker threads](https://github.com/paritytech/substrate/pull/7089) by [@NikVolf](https://github.com/NikVolf)
- PR: [WASM Local-blob override](https://github.com/paritytech/substrate/pull/7317) by [@insipx](https://github.com/insipx)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

13 merged PRs ([1][secret_network-merged-prs-1]), 24 closed issues ([1][secret_network-closed_issues-1]), 
15 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[secret_network-closed_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News:
  - [SecretSCRT: Privacy Tokens are Live on Mainnet!](https://blog.scrt.network/secret-scrt-privacy-tokens-mainnet/)
  - [Secret Network Gets a Secret API!](https://blog.scrt.network/secret-api/)
  - [Secret Network Ecosystem Update: September 2020](https://blog.scrt.network/ecosystem-update-september-2020/)
- Blog:
  - [Secret NFTs: Privacy for Verifiable Goods and Experiences](https://blog.scrt.network/secret-nfts/)
  - [Secret Ethereum Bridge: Programmable Privacy for Ethereum and ERC-20s](https://blog.scrt.network/secret-ethereum-bridge-privacy/)
- PR: [secretcli update to snip20](https://github.com/enigmampc/SecretNetwork/pull/582) by [@toml01](https://github.com/toml01)
- PR: [DOC: added macos mention to work with ledger](https://github.com/enigmampc/SecretNetwork/pull/548) by [@lacabra](https://github.com/lacabra)

#### [Solana](https://github.com/solana-labs/solana)

240 merged PRs ([1][solana-merged-prs-1]), 29 closed issues ([1][solana-closed_issues-1]), 
31 open issues ([1][solana-open_issues-1])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News:
  - [October Newsletter](https://medium.com/solana-labs/october-newsletter-2bca800ed41c)
  - [September Newsletter](https://medium.com/solana-labs/september-newsletter-4d2c341035)
- Blog: [Why Solana?](https://medium.com/solana-labs/why-solana-8c927d58ba06)
- PR: [Break up AccountsIndex lock](https://github.com/solana-labs/solana/pull/12787) by [@carllin](https://github.com/carllin)
- PR: [Fix tower/blockstore unsync due to external causes](https://github.com/solana-labs/solana/pull/12671) by [@ryoqun](https://github.com/ryoqun)
- PR: [Codify breaking change guidelines](https://github.com/solana-labs/solana/pull/13066) by [@jstarry](https://github.com/jstarry)

#### [Zcash](https://z.cash/)

93 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 25 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2]), 
30 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-10-01..2020-10-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[zcash-closed_issues-2]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-10-01..2020-10-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31
[zcash-open_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aopen+created%3A2020-10-01..2020-10-31

- News:
  - [ECC Transparency Report for Q1 2020](https://electriccoin.co/blog/ecc-transparency-report-for-q1-2020/)
  - Zcash Developers Update [10-23](https://www.zcashcommunity.com/2020/10/23/zcash-developers-update-10-23-2020/)
  [10-16](https://www.zcashcommunity.com/2020/10/16/zcash-developers-update-10-16-2020/)
  [10-9](https://www.zcashcommunity.com/2020/10/09/zcash-developers-update-10-9-2020/)
  [10-2](https://www.zcashcommunity.com/2020/10/02/zcash-developers-update-10-2-2020/)
- PR: [Block Subsidy and Founders Reward Amounts](https://github.com/ZcashFoundation/zebra/pull/1051) by [@oxarbitrage](https://github.com/oxarbitrage)
- PR: [Implementation for ZIP-222 Transparent Zcash Extensions](https://github.com/zcash/librustzcash/pull/286) by [@nuttycom](https://github.com/nuttycom)

&nbsp;

## Events

Nov 7-8 | Online

[RustFest Global](https://rustfest.global/)

Nov 9-13 | Online

[ACM CCS 2020](https://www.sigsac.org/ccs/CCS2020/)

Nov 23—24 | Online

[zkSummit 6](https://www.zksummit.com/)



&nbsp;

## Careers

ChainSafe | Toronto, Remote
- [Rust Software Engineer](https://www.notion.so/chainsafe/Blockchain-Developer-Rust-0d577a2636b84511a5d4efc69454585d)

Massa Labs | Remote
- [Full remote Rust developer, long-term contract (French CDI)](https://massa.network/#jobs)

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


