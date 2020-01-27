# Rust in Blockchain #7 - Dec 2019

**#7 - Dec 2019**

Welcome to the #7 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #6](https://rustinblockchain.org/2019/12/05/rust-in-blockchain-6-nov-2019/).

This month we see a trend, in blockchain and across the Rust ecosystem, of projects quickly picking up stable async/await support and migrating to tokio 0.2.

For those interested in a great overview of the future distributed-web landscape, Kyle Samani of Multicoin Capital published a new edition of their ["The Web3 Stack"][w3]. Not Rust-specific, but an evocative, illustrated, piece describing their vision of what a distributed world-wide-web, built on blockchain technology, could look like.

Rust in Blockchain has been expanding our coverage steadily over the months, and this month we begin covering [Zcash], and [COMIT][comit].

With so many Rust blockchain projects of note it is increasingly challenging to report on all of them. If you are a passionate observer of any Rust blockchain project we need your help to gather the monthly updates. Please contact us on the [Telegram group][tg], or email us directly at hello@rustinblockchain.org if you are willing to donate an hour of your time each month.

Happy blockchain new year, Rustaceans!

[Zcash]: https://z.cash/
[tg]: https://t.me/rustinblockchain
[w3]: https://multicoin.capital/2019/12/13/the-web3-stack-2019-edition/

&nbsp;


## Project spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[Zebra](https://github.com/ZcashFoundation/zebra).

Zebra is an implementation of Zcash in Rust. It also appears to be the future of Zcash.

Originally developed by Parity, based off [their bitcoin client][pbt], for the Zcash Foundation, [Zebra was announced][zan] in July 2019. In late August development was begun from scratch, to take advantage of modern Rust idioms, to divorce the design from that of bitcoin, and to use a different license. The current version of Zebra is developed by [Deirdre Connolly] and [Henry de Valence] (who also co-authors a number of high-profile Rust cryptography libraries).

[Deirdre Connolly]: https://github.com/dconnolly

So now there are _two_ Rust implementations of Zcash, including [parity-zcash] (which presumably inherits the original Zebra codebase).

According to the [Zcash Foundation roadmap][zcr], in the future Zebra will be "the bedrock of our engineering output". So it seems like Zcash is all-in on Rust!

Rust is awesome for blockchain, y'all.

[pbt]: https://github.com/paritytech/parity-bitcoin
[zan]: https://www.prnewswire.com/news-releases/parity-releases-zebra-the-first-alternative-zcash-client-to-the-zcash-foundation-300869620.html
[Henry de Valence]: https://github.com/hdevalence
[parity-zcash]: https://github.com/paritytech/parity-zcash
[zcr]: https://www.zfnd.org/blog/eng-roadmap-2020/

&nbsp;


## Most Active in December

[Solana][solana]: [343 merged PRs][solana-mergedpr], [88 closed issues][solana-issue].

[Parity][parity]: 192 merged PRs ([1][parity-mergedpr1], [2][parity-mergedpr2]), 69 closed issues ([1][parity-issue1], [2][parity-issue2]).

[COMIT][comit]: 113 merged PRs ([1][comit-mergedpr1], [2][comit-mergedpr2]), 40 closed issues ([1][comit-issue1], [2][comit-issue2]).

[NEAR][near]: [61 merged PRs][near-mergedpr], [18 closed issues][near-issue].

[solana]: https://github.com/solana-labs/solana
[parity]: https://github.com/paritytech
[comit]: https://comit.network/
[near]: https://github.com/nearprotocol/nearcore

&nbsp;



## Project updates

#### [**COMIT**](https://comit.network/)

113 merged PRs ([1][comit-mergedpr1], [2][comit-mergedpr2]), 40 closed issues ([1][comit-issue1], [2][comit-issue2]).

[comit-mergedpr1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[comit-mergedpr2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[comit-issue1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31
[comit-issue2]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [Blog: Vision and Mission + 2020 goals](https://blog.coblox.tech/2019/12/05/2020-COMIT-goals.html)
- [PR: Make more use of async/await](https://github.com/comit-network/create-comit-app/pull/305)
- [PR: Refactor toward more idiomatic async code](https://github.com/comit-network/create-comit-app/pull/253)
- [PR: Use clarity instead of emerald-rs](https://github.com/comit-network/create-comit-app/pull/286)


#### [**Enigma**](https://enigma.co/)

[16 merged PRs][enigma-mergedpr], [1 closed issue][enigma-issue].

[enigma-mergedpr]: https://github.com/enigmampc/enigma-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[enigma-issue]: https://github.com/enigmampc/enigma-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [Announcing the Launch of Enigma’s First Networked Testnet!](https://blog.enigma.co/announcing-the-launch-of-enigmas-first-networked-testnet-359fd816cb69)
- [PR: Implement local signing of ethereum transactions inside the KM enclave](https://github.com/enigmampc/enigma-core/pull/252)

#### [**Grin**](https://github.com/mimblewimble/grin)

[16 merged PRs][grin-mergedpr], [4 closed issues][grin-issue].

[grin-mergedpr]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[grin-issue]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [News: #78: Floonet hard fork successful](https://grinnews.substack.com/p/78-floonet-hard-fork-successful-)
- [News: #77: ASIC friendly > resistant](https://grinnews.substack.com/p/77-asic-friendly-resistant-)
- [News: #76: v3.0.0 betas are out](https://grinnews.substack.com/p/76-v300-betas-are-out-)
- [News: 2019Q3 Funding Transparency Report](https://github.com/mimblewimble/grin-pm/blob/master/financials/reports/funding_transparency_2019Q3.md)
- [News: We just donated ~.3BTC to the grin general development fund.](https://twitter.com/TMGOX/status/1208590955692969984)
- [Discussion: Could Bitcoin's privacy benefit from Litecoin's EB MimbleWimble proposal?](https://www.reddit.com/r/Bitcoin/comments/e65vdf/could_bitcoins_privacy_benefit_from_litecoins_eb/f9olxfy/)
- [PR: fix(TUI): selected column and row of table are now preserved during update](https://github.com/mimblewimble/grin/pull/3161) by [@JosephGoulden](https://github.com/JosephGoulden)
- [PR: fix(TUI): Fixed panic when changing order of items in TableView](https://github.com/mimblewimble/grin/pull/3160) by [@JosephGoulden](https://github.com/JosephGoulden)

#### [**Interledger**](https://interledger.org/)

[23 merged PRs][interledger-mergedpr], [45 closed issues][interledger-issue].

[interledger-mergedpr]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[interledger-issue]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [Blog: Interledger 2020: Access](https://coil.com/p/sharafian/Interledger-2020-Access/ddUXfDobj)
- [Blog: Interledger 2020 - The Protocol to Connect Them All](https://coil.com/p/kenmelendez/Interledger-2020-The-Protocol-to-Connect-Them-All/F_HowAg-9)
- [PR: Make Redis fully optional for ilp-node](https://github.com/interledger-rs/interledger-rs/pull/551) by [@bstrie](https://github.com/bstrie)
- [PR: Make HTTP and BTP outgoing tokens symmetric to incoming tokens](https://github.com/interledger-rs/interledger-rs/pull/553) by [@gakonst](https://github.com/gakonst)

#### [**NEAR**](https://github.com/nearprotocol/nearcore)

[61 merged PRs][near-mergedpr], [18 closed issues][near-issue].

[near-mergedpr]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Amerged+merged%3A2019-12-01..2019-12-31
[near-issue]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [News: Our Last Update in 2019](https://nearprotocol.com/blog/our-last-update-december-13th-2019/)
- [Blog: Open Web](https://reading.supply/post/0fac829a-c0a5-4d47-922d-060e808edeea)
- [Blog: 200 years of Advertising, Original Sin of the Internet & Impeding No Ads Society](https://reading.supply/@alexhudzilin/200-years-of-advertising-original-sin-of-the-internet-and-impeding-no-ads-society-PWMony)
- [Video: Sharding vs No Sharding fireside chat: NEAR Protocol & Solana](https://www.youtube.com/watch?v=ZyIxWutfZ-U)
- [Video: "Layer 1 Blockchain Architecture": NEAR Protocol Overview](https://www.youtube.com/watch?v=-hOWM-o7N5k)
- [Video: App Chains vs. dApps on shards: Cosmos and NEAR](https://www.youtube.com/watch?v=TSsMfg_NsO8)
- [Video: Blockchain Gaming: 2019 lessons and what to expect in 2020](https://www.youtube.com/watch?v=NqKuEojt3ZM)
- [Video: Early Days in Blockchain App Layer](https://www.youtube.com/watch?v=haG6lwaSUO0)
- [Video: NEAR Lunch and Learn Ep. 07: Nightshade: Finality Gadget](https://www.youtube.com/watch?v=fU7hLt8nJUk)
- [Video: NEAR Lunch and Learn Ep. 06: Pricing Model](https://www.youtube.com/watch?v=vB3oQGW1ydI)
- [Video: NEAR Lunch and Learn Ep. 05: Accounts and Runtime](https://www.youtube.com/watch?v=2_Ekz7w6Eo4s)
- [Video: Whiteboard Series with NEAR | Ep: 31 Kevin Davis from Kava Labs](https://www.youtube.com/watch?v=TAnLaeiRNTA)
- [Video: Whiteboard Series with NEAR | Ep: 30 David Vorick from Sia](https://www.youtube.com/watch?v=YCH3M-DV9i8)
- [PR: Replace sodium with ed25519_dalek and sha2](https://github.com/nearprotocol/nearcore/pull/1816) by [@ailisp](https://github.com/ailisp)
- [PR: Add minimum gas price](https://github.com/nearprotocol/nearcore/pull/1819) by [@bowenwang1996](https://github.com/bowenwang1996)
- [PR: Retry failed parallel test sequentially](https://github.com/nearprotocol/nearcore/pull/1856) by [@ailisp](https://github.com/ailisp)

#### [**Nervos**](https://github.com/nervosnetwork)

[28 merged PRs][nervos-mergedpr], [5 closed issues][nervos-issue].

[nervos-mergedpr]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[nervos-issue]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [News: Nervos Roadmap 2020](https://www.nervos.org/roadmap-2020/)
- [News: Our Investment in Nervos](https://medium.com/dragonfly-research/our-investment-in-nervos-27df40dac7c9)
- [News: ABC Wallet supports CKB!](https://twitter.com/abc_wallet/status/1209105738162794498)
- [News: RFC: Nervos Ecosystem Grants Program](https://talk.nervos.org/t/rfc-nervos-ecosystem-grants-program/4038)
- [News: Nervos CKB Development Update #26](https://medium.com/nervosnetwork/nervos-ckb-development-update-26-c4adcf386945). CKB v0.26.1 has released; Released Neuron v0.26.0 bundle with embedded CKB node; Released alpha version Golang SDK.
- [News: CKB Developer AMA #1 with Tannr](https://medium.com/nervosnetwork/ckb-developer-ama-1-with-tannr-6e6d05e8ad24)
- [Blog: Nervos’s Multi-Layer Architecture: Designed with Scalability in Mind](https://medium.com/nervosnetwork/nervoss-multi-layer-architecture-designed-with-scalability-in-mind-7655910d9828)
- [Blog: The LatAm Community: a Growing Force in Blockchain](https://medium.com/nervosnetwork/ckb-developer-ama-1-with-tannr-6e6d05e8ad24)
- [Blog: Understanding the Nervos DAO and Cell Model](https://medium.com/nervosnetwork/understanding-the-nervos-dao-and-cell-model-d68f38272c24)
- [Blog: How Nervos CKB Could Facilitate Non-Fungible Tokens](https://medium.com/nervosnetwork/how-nervos-ckb-could-facilitate-non-fungible-tokens-6d0e94605efc)
- [Blog: The Smart Contract Risk in DeFi](https://medium.com/nervosnetwork/the-smart-contract-risk-in-defi-c28e53b92f03s)
- [Video: How To Stake Nervos CKBytes | CKB DAO Tutorial](https://www.youtube.com/watch?v=fN4wn7udaeM)
- [Video: How To Mine Nervos CKB | No More GPU Mining - FPGA Mining Tutorial & Staking](https://www.youtube.com/watch?v=GQ_4vWSbiv0)
- [PR: Informational: CKB Transaction Structure](https://github.com/nervosnetwork/rfcs/pull/134) by [@doitian](https://github.com/doitian)
- [PR: Doc: add W^X Memory and exec syscall for CKB VM](https://github.com/nervosnetwork/rfcs/pull/102) by [@xxuejie](https://github.com/xxuejie)

#### [**Oasis**](https://github.com/oasislabs)

8 merged PRs ([1][oasis-mergedpr2], [2][oasis-mergedpr2]), 0 closed issues ([1][oasis-issue1], [2][oasis-issue2]).

[oasis-mergedpr1]: https://github.com/oasislabs/oasis-runtime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[oasis-issue1]: https://github.com/oasislabs/oasis-runtime/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31
[oasis-mergedpr2]: https://github.com/oasislabs/oasis-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[oasis-issue2]: https://github.com/oasislabs/oasis-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [News: Join the Oasis DevAccelerator Program](https://medium.com/oasislabs/oasis-dev-accelerator-program-4840bfea129e)
- [Blog: What is My Data Worth?](https://medium.com/oasislabs/what-is-my-data-worth-b7e2f1a8717f) An article by Ruoxi Jia that discusses methods proposed in our recent AISTATS and VLDB papers that attempt to answer this question in the machine learning context.
- [Blog: Developer Spotlight: Matt Johnson](https://medium.com/oasislabs/developer-spotlight-matt-johnson-b2588c79c849)

#### [**Parity** ](https://github.com/paritytech)

192 merged PRs ([1][parity-mergedpr1], [2][parity-mergedpr2]), 69 closed issues ([1][parity-issue1], [2][parity-issue2]).

[parity-mergedpr1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Amerged+merged%3A2019-12-01..2019-12-31
[parity-issue1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31
[parity-mergedpr2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Amerged+merged%3A2019-12-01..2019-12-31
[parity-issue2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [News: Polymesh — Flexibility through Smart Extensions](https://blog.polymath.network/polymesh-flexibility-through-smart-extensions-c461f1504ce9). Polymath and Parity collaborate on extending Substrate to provide rich interoperability between base layer runtime modules, and dynamically deployed smart contracts.
- [News: The Foundation of a New Internet](https://medium.com/cornellblockchain/the-foundation-of-a-new-internet-86d72d3074eb). A look at Web 3.0 with Polkadot — Cornell Blockchain.
- [News: Kusama Upgrade Bulletin](https://polkadot.network/kusama-upgrade-bulletin-2/). Kusama is about to get a new logic core. Runtime version: 1031; Supported natively by Polkadot v0.7.10.
- [News: We are planning to move Parity Ethereum to a DAO ownership & maintainer model](https://twitter.com/ParityTech/status/1206657981288456193). OpenEthereum will provide the basis for cross-org collaboration to ensure the codebase gets the attention it needs to realize its full potential.
- [News: PolkaWorld Interview House to feature guest speakers and A look at Web 3.0 with Polkadot](https://medium.com/paradigm-fund/polkadot-polkaworld-interview-house-to-feature-guest-speakers-and-a-look-at-web-3-0-with-polkadot-5971256018bb)
- [News: The Inspiration Behind Web3 Grant Winner Attic Lab's Substrate Plugin](https://commonwealth.im/edgeware/proposal/discussion/168-the-inspiration-behind-web3-grant-winner-attic-labs-substrate-plugin)
- [Blog: Have a TEE with Polkadot](https://polkadot.network/have-a-tee-with-polkadot)
- [Blog: Polkadot 2019](https://polkadot.network/polkadot-2019-year-in-review/)
- [Blog: Secure and Decentralized Polkadot Domain Name System](https://medium.com/@chainx_org/secure-and-decentralized-polkadot-domain-name-system-e06c35c2a48d)
- Blog: Polkadot Consensus [Part 1: Introduction](https://polkadot.network/polkadot-consensus-part-1-introduction), [Part 2: GRANDPA](https://polkadot.network/polkadot-consensus-part-2-grandpa/), [Part 3: BABE](https://polkadot.network/polkadot-consensus-part-3-babe/), [Part 4: Security](https://polkadot.network/polkadot-consensus-part-4-security/).
- [Video: Sub0.1: Substrate Ecosystem Overview - Fredrik Harryson](https://www.youtube.com/watch?v=dg50O_wurME)
- [Video: Participating in Kusama with Logan Saether](https://www.youtube.com/watch?v=EqRM11XU9mA&feature=youtu.be)
- [Podcast: How can non money tokens accrue value in crypto](https://podcasts.apple.com/us/podcast/how-can-non-money-tokens-accrue-value-in-crypto-jack/id1350649166) | Jack Platt, Polkadot.
- [Repo: substrate-client-cli](https://github.com/docknetwork/substrate-client-cli). Example command line utility for querying latest state from a substrate based chain.
- [Slides: Plasm Network at Sub0.1](https://speakerdeck.com/sotawatanabe/plasm-network-at-sub0-dot-1-summit). Plasm Network slide deck at Sub0.1. The Plasm team describes what they are working on and what they will implement on Plasm Network.

#### [**Solana**](https://github.com/solana-labs/solana)

[343 merged PRs][solana-mergedpr], [88 closed issues][solana-issue].

[solana-mergedpr]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[solana-issue]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

- [Blog: Solana in 2019: Growth, Development, and the Road to Mainnet](https://medium.com/solana-labs/solana-in-2019-growth-development-and-the-road-to-mainnet-16b642fd7fb1)
- [Podcast: How Solana Works with Anatoly Yakovenko Ep #2](https://podcasts.apple.com/us/podcast/how-solana-works-with-anatoly-yakovenko-ep-2/id1476353378?i=1000446769632)
- [Video: Solana & SKALE live podcast recording - Jack O'Holleran & Anatoly Yakovenko](https://www.youtube.com/watch?v=fmVuXfwG6eY&feature=youtu.be)
- [Video: Layer 1 Event ft. Solana, NEAR, Harmony, CODA, Nervos](https://www.youtube.com/watch?v=LEKcBeDcEAY)
- [PR: Stabilize fn coverage by creating a clean room](https://github.com/solana-labs/solana/pull/7576) by [@ryoqun](https://github.com/ryoqun)
- [PR: Check for incorrect hash value on snapshot ingest](https://github.com/solana-labs/solana/pull/7559) by [@ryoqun](https://github.com/ryoqun)
- [PR: Improve bench-tps stability](https://github.com/solana-labs/solana/pull/7537) by [@jstarry](https://github.com/jstarry)
- [PR: Update "limit-ledger-size" to use DeleteRange for much faster deletes](https://github.com/solana-labs/solana/pull/7515) by [@sagar-solana](https://github.com/sagar-solana)
- [PR: Strictly sanitize mmapped AppendVec file contents](https://github.com/solana-labs/solana/pull/7464) by [@ryoqun](https://github.com/ryoqun)
- [PR: Add SystemInstruction::CreateAccountWithSeed](https://github.com/solana-labs/solana/pull/7390) by [@rob-solana](https://github.com/rob-solana)

#### [**Zcash**](https://z.cash/)

28 merged PRs ([1][zcash-mergedpr1], [2][zcash-mergedpr2]), 12 closed issues ([1][zcash-issue1], [2][zcash-issue2]).

[zcash-mergedpr1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[zcash-mergedpr2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[zcash-issue1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31
[zcash-issue2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

The news this month is dominated by a poll on how to fund future Zcash development.

- [Blog: ZF Grants 2.0](https://www.zfnd.org/blog/zf-grants-refresh/). Zcash loves Rust. Zcash has grants.
- [Blog: Zcash developers update 12-6-19](https://www.zcashcommunity.com/2019/12/06/zcash-developers-update-12-6-19/)
- [News: Cryptocurrency 101 in the Bronx](https://www.newyorker.com/magazine/2019/12/09/cryptocurrency-101-in-the-south-bronx?verso=true). From The New Yorker.
- [News: Zcash Foundation update November 21 - December 13, 2019](https://news.zfnd.org/archive/zcash-foundation-update-november-21-december-13/)
- [Blog: Blossom upgrade improves speed, scalability, and compatibility](https://electriccoin.co/blog/blossom-upgrade-improves-speed-scalability-capacity/)
- [Blog: Community sentiment polling results](https://www.zfnd.org/blog/community-sentiment-collection-results/). Results of polling the community on funding future Zcash development.
- [Blog: Supporting a path for NU4](https://www.zfnd.org/blog/nu4-next-steps/). More about funding.
- [Blog: Presenting a modified ZIP 1012](https://www.zfnd.org/blog/proposed-nu4-zip/). More about funding. [ZIP 1012](https://zips.z.cash/zip-1012) is the proposal to continue funding Zcash.
- [Blog: ECC response to Zcash community polling](https://electriccoin.co/blog/ecc-response-to-zcash-community-polling-results/). On the future of Zcash funding.
- [Blog: Dev Funds Should Be in Zcash, not United States Dollars](https://electriccoin.co/blog/dev-funds-should-be-in-zcash-not-united-states-dollars/). From the Electric Coin Company re the recent funding proposal.
- [Blog: ECC transparency report for Q2 2019](https://electriccoin.co/blog/ecc-transparency-report-for-q2-2019/)
- [PR: Update transaction definition](https://github.com/ZcashFoundation/zebra/pull/105)
- [PR: Use redjubjub types in zebra-chain](https://github.com/ZcashFoundation/zebra/pull/142). [redjubjub](https://github.com/ZcashFoundation/redjubjub) is another Zcash Rust project, part of the Zcash protocol.
- [PR: Upgrade tokio, futures, hyper to released versions](https://github.com/ZcashFoundation/zebra/pull/145). Zebra is async/await.
- [PR: Add ZIP 1014, based on ZIP 1012](https://github.com/zcash/zips/pull/308). An updated funding ZIP.

&nbsp;

## Learning

[The Web3 Stack, 2019 Edition](https://multicoin.capital/2019/12/13/the-web3-stack-2019-edition/). Updates the Web3 stack based on the [2018 edition](https://multicoin.capital/2018/07/10/the-web3-stack/).

&nbsp;

## Interesting Things

[Mark Zuckerberg has a big Libra problem](https://www.wired.co.uk/article/libra-ethereum-web-3) by Gavin Wood. Libra is too closely tied to megacorporations to succeed. Platforms built to be open and free will outperform Libra.

[Hold Tight, Here Come the Blockchain Wars](https://www.coindesk.com/hold-tight-here-come-the-blockchain-wars) by Gavin Wood.

&nbsp;

## Events

Jan 8, 2020 | San Francisco, US

[Hack Night @NEAR](https://www.meetup.com/SF-NEAR-Protocol-Developers-Group/events/jrqdlrybccbtb/)

Jan 15, 2020 | Online

[Data Economy challenge](https://oceanprotocol.devpost.com/)

Feb 1-2 | Brussels

[FOSDEM 2020](https://fosdem.org/2020/)

Feb 29 | San Francisco, US

[World Blockchain Hackathon](https://www.eventbrite.com/e/world-blockchain-hackathon-san-francisco-tickets-70815243299)

&nbsp;

## Careers

Centrifuge | Berlin, Germany; Remote

[Rust Engineer](https://centrifuge.breezy.hr/p/20af596b9ffb01-rust-engineer-centrifuge-chain/)

Consensys | Europe; United States; Remote

[Systems Engineer - Rust](https://consensys.net/open-roles/1792013/)

CyberCoders | Boston, San Francisco

[Senior Software Engineer - Blockchain Solution](https://www.cybercoders.com/senior-software-engineer-job-506965)

imToken | Singapore; Hangzhou, China

[Blockchain Development Engineer](https://token.im/careers)

Interledger | San Francisco, US; Remote

[Senior Software Engineer, Rust](https://www.ripple.com/company/careers/all-jobs#senior-software-engineer-rust)

IOHK | Europe

[Software Engineer - Rust](https://iohk.io/careers/#op-345001-software-engineer-rust)

Jsgenesis | Oslo, Europe; Remote

[Senior Blockchain Developer](https://www.jsgenesis.com/jobs/blockchain-developer)

Kraken | Berlin, Germany; Remote

[Backend Engineer - Crypto/Payments](https://jobs.lever.co/kraken/4c18a043-3f9f-4005-a715-7455aaa64b11)

Leger | Paris, France

[C++ / Rust Software Engineer](https://jobs.lever.co/ledger/8555a86e-fbf4-4701-95cb-190a76445bb8)

MixBytes | Remote available

[Rust Developer](https://mixbytes.io/career)

NEAR | Remote, San Francisco, New York, Berlin, Moscow

[Software Engineer, Expert in WebAssembly and Compilers](https://boards.greenhouse.io/near/jobs/4563917002)

Nervos | San Francisco; Hangzhou, China; Remote

[Senior Test Manager](https://angel.co/company/nervos-1/jobs/589746-senior-test-manager)

[Senior Blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

OneinaMil | New York City; Remote

[Blockchain RUST/WASM Developer](https://apply.workable.com/oneinamil/j/E74222BB58/)

Parity | Berlin, Germany

[Rust/Core Developer](https://www.parity.io/jobs/#berlin-rust-core-developer)



&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#8 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/blob/master/draft/Rust%20in%20Blockchain%20%238%20-%20Jan%202020.md), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
