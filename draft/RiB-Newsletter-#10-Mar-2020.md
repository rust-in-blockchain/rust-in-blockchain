---
title: "RiB Newsletter #10 – Keep Calm and Hack More"
description: "#10 - Mar 2020"
date: 2020-04-01
slug: "/2020-04-01-keep-calm-and-hack-more"
categories:
  - "newsletters"
summary: 
---

# RiB Newsletter #10 - Mar 2020

**#10 - Mar 2020**

Welcome to the #10 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #9](/newsletters/2020-03-04-the-month-of-working-from-home). 

How are you doing from working at home so far? What do you spend time on? We hope you find something fun, create interesting hacks and enjoy yourself. 

This month, we changed the website theme, and moved the hosting from wordpress to GitHub Pages, with hugo framework. So now it should be more straightforward to contribute to the website as well as the content. We still need a RSS, maybe also an event calendar ;)

Several offline events have been moved online -- more podcasts, online workshops, and video meetings have been scheduled. We encourage you to share your ideas, practice, and experience with our audience. So if you want to do an online workshop for our Rust and blockchain developers, please tweet at us, or submit a PR to the next draft of your event.

Stay at home, chill and hack harder.



&nbsp;


## Thanks

This edition of RiB was produced with contributions from [SeungMin Lee][contributorsl], [Mattias Nystrom][contributormn], Paulii Good, [Brian Anderson][contributorba], and [Aimee Zhu][contributoraz]. Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. If you follow a particular project, or otherwise find information that is beneficial to the Rust & blockchain community, please contribute to the next issue. Either submit a PR to the [#11 draft](/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

[contributorsl]: https://github.com/somniumism
[contributormn]: https://github.com/mat7ias
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer


&nbsp;


## Project spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Most Active in March

[Solana]: 240 merged [PRs][solana-merged-prs-1], 30 closed [issues][solana-closed_issues-1]

[NEAR]: 47 merged [PRs][near-merged-prs-1], 56 closed [issues][near-closed_issues-1]

[CodeChain]: 62 merged PRs ([1][codechain-merged-prs-1], [2][codechain-merged-prs-2]), 22 closed [issues][codechain-closed_issues-1]

[Parity]: 70 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]), 9 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3])


[Solana]: https://github.com/solana-labs/solana
[NEAR]: https://github.com/nearprotocol/nearcore
[CodeChain]: https://github.com/codeChain-io/
[Parity]: https://github.com/paritytech


&nbsp;



## Project updates

#### [**CodeChain**](https://github.com/codeChain-io/)

62 merged PRs ([1][codechain-merged-prs-1], [2][codechain-merged-prs-2]), 22 closed [issues][codechain-closed_issues-1]

[codechain-merged-prs-1]: https://github.com/CodeChain-io/codechain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[codechain-merged-prs-2]: https://github.com/CodeChain-io/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[codechain-closed_issues-1]: https://github.com/CodeChain-io/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [CodeChain Foundry ICS Implementation](https://medium.com/codechain/foundry-ics-poc-proof-of-concept-implementation-c92a8b4757da)
- PR: [Hot events for Informer API ](https://github.com/CodeChain-io/foundry/pull/219) by [@MSNTCS](https://github.com/MSNTCS)
- PR: [Replace ECDSA and Schnorr with Ed25519](https://github.com/CodeChain-io/foundry/pull/154) by [@HoOngEe](https://github.com/HoOngEe)
- PR: [Modify logic related to the Tx type for checking whether a Tx is verified or not](https://github.com/CodeChain-io/foundry/pull/257) by [@somniumism](https://github.com/somniumism)
- PR: [Implement basics of ICS 04](https://github.com/CodeChain-io/foundry/pull/210) by [@junha1](https://github.com/junha1)
- PR: [Implement module db for coordinator Context](https://github.com/CodeChain-io/foundry/pull/241) by [@HoOngEe](https://github.com/HoOngEe)


#### [**Golem**](https://golem.network/)

37 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3], [4][golem-merged-prs-4], [5][golem-merged-prs-5]), 1 closed [issues][golem-closed_issues-1]

[golem-merged-prs-1]: https://github.com/golemfactory/golem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[golem-merged-prs-2]: https://github.com/golemfactory/mandelbrot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[golem-merged-prs-3]: https://github.com/golemfactory/sp-wasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[golem-merged-prs-4]: https://github.com/golemfactory/gudot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[golem-merged-prs-5]: https://github.com/golemfactory/golem-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[golem-closed_issues-1]: https://github.com/golemfactory/golem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- Blog: [Summary of the Golem AMA March 2020: getting closer to Clay and headed towards a new paradigm](https://blog.golemproject.net/summary-of-the-golem-ama-march-2020-getting-closer-to-clay-and-headed-towards-a-new-paradigm/)
- Blog: [Scaling Golem: research on scalability alternatives update](https://blog.golemproject.net/scaling-golem-research-on-scalability-alternatives-update/)
- Blog: [gWebinars Part 1: Building on top of Golem with gWASM](https://blog.golemproject.net/gwebinars-part-1-building-on-top-of-golem-with-gwasm/)
- Blog: [Golem Hive - building a cloud with the Task API (and then some more)](https://blog.golemproject.net/golem-hive/)
- Video: [Building on top of Golem with gWASM](https://www.youtube.com/watch?v=tBbJYs4zlGY)
- PR: [BroadcastProtocol introduction](https://github.com/golemfactory/golem/pull/5109) by [@jiivan](https://github.com/jiivan)
- PR: [add an integration test that runs two simultanous tasks](https://github.com/golemfactory/golem/pull/5127) by [@shadeofblue](https://github.com/shadeofblue)
- PR: [Load app definition files from Golem releases CDN](https://github.com/golemfactory/golem/pull/5114) by [@zakaprov](https://github.com/zakaprov)

#### [**Grin**](https://github.com/mimblewimble/grin)

16 merged [PRs][grin-merged-prs-1], 8 closed [issues][grin-closed_issues-1]

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [91: New core team member](https://grinnews.substack.com/p/91-new-core-team-member-)
- News: [90: Grin Node Challenge](https://grinnews.substack.com/p/90-grin-node-challenge-)
- News: [89: Grin wallet v3.1.1 out](https://grinnews.substack.com/p/89-grin-wallet-v311-out-)
- News: [88: Add more scheduled hard forks?](https://grinnews.substack.com/p/88-add-more-scheduled-hard-forks)
- PR: [API: don't error on missing output](https://github.com/mimblewimble/grin/pull/3256) by [@jaspervdm](https://github.com/jaspervdm)
- PR: [no need to rehash with index to compare output with input spending it](https://github.com/mimblewimble/grin/pull/3260) by [@antiochp](https://github.com/antiochp)
- PR: [simplify when block_sums and spent_index are added to the db](https://github.com/mimblewimble/grin/pull/3253) by [@antiochp](https://github.com/antiochp)


#### [**Holochain**](https://github.com/holochain/)

29 merged [PRs][holochain-merged-prs-1], 1 closed [issues][holochain-closed_issues-1]

[holochain-merged-prs-1]: https://github.com/holochain/holochain-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [Holo AMA No. 36 w/ Art Brock, David Atkinson, and Mary Camacho](https://www.youtube.com/watch?v=FJ33frirb0c)
- News: [Monthly Roundup for Holo & Holochain](https://medium.com/h-o-l-o/monthly-roundup-for-holo-holochain-71fddb9b2619)
- Blog: [Bootstrap a hApp in One Command](https://medium.com/holochain/bootstrap-a-happ-in-one-command-654ee2c417df)
- Blog: [The Story of 7500 Nodes, 5 Live hApps To Try](https://medium.com/holochain/the-story-of-7500-nodes-5-live-happs-to-try-c36f0f075e37)
- Blog: [Maintaining Focus in a Rapidly Changing World](https://medium.com/h-o-l-o/maintaining-focus-in-a-rapidly-changing-world-e52b609f190d)
- Blog: [Holochain Community Hackathons](https://blog.holochain.org/holochain-community-hackathons/)
- Forum: [hAppyStory - Acorn](https://forum.holochain.org/c/projects/acorn/106) 
- PR: [trycp_manager](https://github.com/holochain/holochain-rust/pull/2123) by [@zippy](https://github.com/zippy)
- PR: [Basic start to tokio trace](https://github.com/holochain/holochain-rust/pull/2132) by [@freesig](https://github.com/freesig)
- PR: [Fix update aspects](https://github.com/holochain/holochain-rust/pull/2153) by [@maackle](https://github.com/maackle)
- PR: [Key fixes for validation](https://github.com/holochain/holochain-rust/pull/2159) by [@neonphog](https://github.com/neonphog)
- PR: [Sim2h space data remote debugging](https://github.com/holochain/holochain-rust/pull/2128) by [@lucksus](https://github.com/lucksus)

#### [**NEAR**](https://github.com/nearprotocol/nearcore)

47 merged [PRs][near-merged-prs-1], 56 closed [issues][near-closed_issues-1]

[near-merged-prs-1]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[near-closed_issues-1]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [NEAR Community Update: March 27th, 2020](https://nearprotocol.com/blog/near-community-update-march-27th-2020/)
- News: [NEAR Community Update: March 13th, 2020](https://nearprotocol.com/blog/near-community-update-march-13th-2020/)
- Video: [Whiteboard Series with NEAR | Ep: 33 Justin Drake from Ethereum Foundation](https://www.youtube.com/watch?v=8xpOUqdoyp0)
- Podcast: [Proof-of-Space-Time without VDFs](https://commonwealth.im/near/proposal/discussion/367-proofofspacetime-without-vdfs)
- Podcast: [Near Protocol + Open Web Collective - Lessons learned building a new blockchain](https://podcasts.apple.com/us/podcast/near-protocol-open-web-collective-lessons-learned-building/id1497307664?i=1000468017907)
- PR: [GC major update](https://github.com/nearprotocol/nearcore/pull/2084) by [@Kouprin](https://github.com/Kouprin)
- PR: [feat(runtime): switch to state staking](https://github.com/nearprotocol/nearcore/pull/2272) by [@ilblackdragon](https://github.com/ilblackdragon)
- PR: [fix(chain): fix garbage collection stop height](https://github.com/nearprotocol/nearcore/pull/2274) by [@bowenwang1996](https://github.com/bowenwang1996)
- PR: [feat(runtime): Expose epoch height to WASM runtime](https://github.com/nearprotocol/nearcore/pull/2053) by [@ilblackdragon](https://github.com/ilblackdragon)
- PR: [feat(runtime): Add Helper Methods and Types for Mock VM](https://github.com/nearprotocol/nearcore/pull/2136) by [@willemneal](https://github.com/willemneal)

#### [**Nervos**](https://github.com/nervosnetwork)

6 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]), 2 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/rfcs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/rfcs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [Nervos CKB Development Update #31](https://medium.com/nervosnetwork/nervos-ckb-development-update-31-7b253fdb464)
- News: [Nervos CKB Development Update #30](https://medium.com/nervosnetwork/nervos-ckb-development-update-30-e05a4ddb6ab1)
- News: [Lay2 Project Awarded Ecosystem Grant](https://medium.com/nervosnetwork/ecosystem-grants-lay2-project-awarded-6th-nervos-grant-c2ee081e3c5b)
- News: [Three New Ecosystem Grants Awarded](https://medium.com/nervosnetwork/three-new-ecosystem-grants-awarded-892b97e8bc06)
- News: [Nervos Foundation Joins Cross-Chain Group](https://medium.com/nervosnetwork/nervos-foundation-joins-cross-chain-group-ac2e6e6af9d9)
- News: [Overlord — A new consensus algorithm](https://medium.com/nervosnetwork/overlord-a-new-consensus-algorithm-3cc51690d269)
- Blog: [CKB’s Hash Function Eaglesong: Built for the Mining Ecosystem](https://medium.com/nervosnetwork/ckbs-hash-function-eaglesong-built-for-the-mining-ecosystem-c7457a52a163)
- Blog: [Bitcoin as a Store of Value is Still its Greatest Narrative](https://medium.com/nervosnetwork/bitcoin-is-still-a-store-of-value-despite-the-fact-that-everybody-has-abandoned-its-greatest-971a845ed6ae)
- Blog: [What’s Animagus Part 2: Running it For Real](https://medium.com/nervosnetwork/whats-animagus-part-2-running-it-for-real-17a48608389d)
- Blog: [What Do We Mean When We Say Account Model?](https://xuejie.space/2020_03_20_what_do_we_mean_when_we_say_account_model/)
- Blog: [Introduction to CKB Script Programming 9: Cycle Reductions in Duktape Script](https://xuejie.space/2020_03_19_cycle_reduction_in_duktape/)
- Blog: [Let's Build a Minimal Blockchain 3: What Is A Blockchain?](https://xuejie.space/2020_03_16_lets_build_a_minimal_blockchain_what_is_a_blockchain/)
- Blog: [Evolution Path to Decentralized ASICs](https://chinarelaynode.substack.com/p/evolution-path-to-decentralized-asics)
- Video: Programming CKB [Part 1](https://www.youtube.com/watch?v=HyYXzEIdF90), [Part 2](https://www.youtube.com/watch?v=Co-rzOhwuHs), [Part 3](https://www.youtube.com/watch?v=13w6Wvu9ff0)
- Video: [Story of DeFi](https://www.youtube.com/watch?v=Uh1uGDWLyiw)
- Video: [CKB P Wallet](https://www.youtube.com/watch?v=Bh7GpFerpJw)
- PR: [feat: add a feature to enable jemalloc profiling](https://github.com/nervosnetwork/ckb/pull/1940) by [@yangby-cryptape](https://github.com/yangby-cryptape)
- PR: [test: add options for integration tests and fix a bug](https://github.com/nervosnetwork/ckb/pull/1960) by [@yangby-cryptape](https://github.com/yangby-cryptape)
- PR: [Revert "perf: Tweak slot calculation algorithm"](https://github.com/nervosnetwork/ckb-vm/pull/100) by [@xxuejie](https://github.com/xxuejie)
- PR: [0022: add links to molecule and schema file](https://github.com/nervosnetwork/rfcs/pull/180) by [@doitian](https://github.com/doitian)


#### [**Parity** ](https://github.com/paritytech)

70 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3]), 9 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[parity-merged-prs-3]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31
[parity-closed_issues-3]: https://github.com/paritytech/parity-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [Announcing Substrate Delivery Partners](https://www.parity.io/announcing-substrate-delivery-partners/)
- News: [Alert - impersonated emails](https://www.parity.io/06-03-2020-alert-impersonated-emails/)
- News: [Announcing the initial participants in the Substrate Builders Program](https://www.parity.io/announcing-the-initial-participants-in-the-substrate-builders-program/)
- News: [Another blockchain project is heading to the Polkadot Network](https://www.coindesk.com/iot-app-nodle-moves-from-stellar-blockchain-to-polkadot)
- Video: [Intro to Substrate Off-Chain Workers with Joe Petrowski and Tomasz Drwięga](https://www.youtube.com/watch?v=rwzvRi1JkWU)
- Video: [Polkadot validator node setup with Joe Petrowski and Will Pankiewicz](https://www.youtube.com/watch?v=ejgPSwdLj5o)
- Video: [Build a proof of existence blockchain in 30 minutes](https://www.youtube.com/watch?v=FBPKgkC9RCo)
- Video: [The EVM Pallet and Purestake's Moonbeam](https://www.youtube.com/watch?v=lXw6GTNh73Y)
- Video: [sr-tool and Proof of Work](https://www.youtube.com/watch?v=Z-ZH7wKW094)
- Video: [PolkaHub and Totem Live](https://www.youtube.com/watch?v=D5oeAwuqGDQ)
- Video: [VuePolkadot, CLE Coin, Staking Demo](https://www.youtube.com/watch?v=eAXbcgWSzqc)
- Podcast: [Innovating Blockchain-Based Accounting with Totem](https://relaychain.fm/16-innovating-blockchain-based-accounting-with-totem)
- Podcast: [Investing in the Future of Web 3.0](https://relaychain.fm/17-investing-in-the-future-of-web3)
- PR: [Offchain Phragmén BREAKING.](https://github.com/paritytech/substrate/pull/4517) by [@kianenigma](https://github.com/kianenigma)
- PR: [Parachains double vote handler initial implementation.](https://github.com/paritytech/polkadot/pull/840) by [@montekki](https://github.com/montekki)
- PR: [Implements mocking of runtime apis](https://github.com/paritytech/substrate/pull/5448) by [@bkchr](https://github.com/bkchr)
- PR: [PoV-block gossip](https://github.com/paritytech/polkadot/pull/930) by [@rphmeier](https://github.com/rphmeier)
 

#### [**Solana**](https://github.com/solana-labs/solana)

240 merged [PRs][solana-merged-prs-1], 30 closed [issues][solana-closed_issues-1]

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [Solana Raises 1.76 Million in Sold-Out Coinlist Auction](https://medium.com/solana-labs/solana-raises-1-76-million-in-sold-out-coinlist-auction-92f71c6fec7d)
- News: [Chainlink and Solana Integration: High-Speed Price Oracle Data for Better DeFi Applications](https://medium.com/solana-labs/chainlink-and-solana-integration-high-quality-price-oracle-data-cd9fa41f6ecb)
- News: [Solana’s Community Token Sale is Now LIVE!](https://medium.com/solana-labs/solanas-community-token-sale-is-now-live-2c724f9df447)
- News: [Blockchain Startup Bison Trails Adds Support For Solana Protocol](https://blocktribune.com/blockchain-startup-bison-trails-adds-support-for-solana-protocol/)
- News: [Bison Trails to add Solana blockchain when mainnet goes live](https://decrypt.co/23598/bison-trails-add-solana-blockchain-mainnet-goes-live)
- Blog: [Tour de SOL Weekly Recaps](https://medium.com/solana-labs/tour-de-sol-weekly-recaps-a8ce2e91e1d)
- Blog: [SOL Bandits On The Run](https://medium.com/solana-labs/sol-bandits-on-the-run-696e044d20ed)
- Blog: [Validator Feature Series](https://medium.com/solana-labs/validator-feature-series-6f1c479d70b3)
- Blog: [Elastic Circuit Breakers: A Proposal for More Robust Crypto Market Infrastructure](https://medium.com/solana-labs/elastic-circuit-breakers-9229097e6acf)
- Video: [5G Use Case Explainer Video (Anatoly Yakovenko / CEO of Solana)](https://www.youtube.com/watch?v=-7c7HeMyVVM)
- Video: [Proof of History Explainer (Updated)](https://www.youtube.com/watch?v=TNJoRvshJn0)
- Video: [Vinny Lingham - CEO of Civic & General Partner at Multicoin Capital](https://www.youtube.com/watch?v=5gy8bWPB0JE)
- Video: [CoinList Chats: Solana and Scaling Solution Trade-offs](https://www.youtube.com/watch?v=EJv4TlMBUJc)
- Podcast: [Kyle Samani - Managing Partner at Multicoin Capital Ep #18](https://podcasts.apple.com/us/podcast/kyle-samani-managing-partner-at-multicoin-capital-ep-18/id1476353378?i=1000469672403)
- Podcast: [Amir Haleem - CEO of Helium Ep #17](https://podcasts.apple.com/us/podcast/amir-haleem-ceo-of-helium-ep-17/id1476353378?i=1000468823066)
- Podcast: [Coinlist Auction & Staker Price Guarantee ft. Coinlist President Andy Bromberg](https://podcasts.apple.com/us/podcast/coinlist-auction-staker-price-guarantee-ft-coinlist/id1476353378?i=1000468695817)
- Podcast: [Vinny Lingham - CEO of Civic / General Partner at Multicoin Capital Ep #16](https://podcasts.apple.com/us/podcast/vinny-lingham-ceo-civic-general-partner-at-multicoin/id1476353378?i=1000467276111)
- PR: [Add frozen account support](https://github.com/solana-labs/solana/pull/8989) by [@mvines](https://github.com/mvines)
- PR: [Strictly validate the contents of snapshot/genesis](https://github.com/solana-labs/solana/pull/8959) by [@ryoqun](https://github.com/ryoqun)
- PR: [Ledger cleanup fix](https://github.com/solana-labs/solana/pull/9131) by [@sakridge](https://github.com/sakridge)
- PR: [Add solana-stake-accounts CLI tool](https://github.com/solana-labs/solana/pull/9164) by [@garious](https://github.com/garious)

#### [**Zcash**](https://z.cash/)

24 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 15 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[zcash-merged-prs-2]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[zcash-merged-prs-3]: https://github.com/zcash/zips/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-03-01..2020-03-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31
[zcash-closed_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31
[zcash-closed_issues-3]: https://github.com/zcash/zips/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-03-01..2020-03-31

- News: [Zcash Foundation Update](https://news.zfnd.org/archive/zcash-foundation-update-march-2020/)
- Blog: [Design Tradeoffs in Privacy-Preserving Contact Tracing](https://www.zfnd.org/blog/design-tradeoffs-in-private-contact-tracing/)
- Blog: [Let's Develop Decentralized, Privacy-Preserving Contact Tracing](https://www.zfnd.org/blog/decentralized-contact-tracing/)
- Blog: [Explaining FlyClient](https://electriccoin.co/blog/explaining-flyclient/)
- Blog: [Introducing Heartwood](https://electriccoin.co/blog/introducing-heartwood/)
- PR: [[ZIP 221] FlyClient - Consensus-Layer Changes](https://github.com/zcash/zips/pull/220) by [@therealyingtong](https://github.com/therealyingtong)
- PR: [Sprout keys and addresses](https://github.com/ZcashFoundation/zebra/pull/317) by [@dconnolly](https://github.com/dconnolly)
- PR: [TransparentAddress](https://github.com/ZcashFoundation/zebra/pull/280) by [@dconnolly](https://github.com/dconnolly)
- PR: [Update manifest for zcash_history](https://github.com/zcash/librustzcash/pull/214) by [@ebfull](https://github.com/ebfull)
- PR: [ZIP 221: strengthen caveat about FlyClient security in chains with rapid difficulty adjustment, and change pseudocode so that CONSENSUS_BRANCH_ID doesn't look like a constant](https://github.com/zcash/zips/pull/335) by [@daira](https://github.com/daira)

&nbsp;

## Learning

[Open Source: From Community to Commercialization](https://a16z.com/2019/10/04/commercializing-open-source/)

[Progressive Decentralization: A Playbook for Building Crypto Applications](https://a16z.com/2020/01/09/progressive-decentralization-crypto-product-management/)

&nbsp;

## Interesting Things

Thread: [ whether we'd build SetProtocol on other chains](https://twitter.com/felix2feng/status/1130268154742026241)


&nbsp;

## Events

April-May, 2020  

[ZKProof Standards](https://zkproof.org/)

May 1-2 | Online

[DeFi Discussions: Virtual Summit](https://defi-discussions.dystopialabs.com/)

Aug 3-6, 2020 | Oxford, UK

[IEEE DAPPS 2020](https://ieeedapps.net/)

&nbsp;

## Careers

Layertwo | London, UK

[Senior Backend Engineer](https://angel.co/company/layertwo/jobs/687465-senior-backend-engineer)

[Junior Backend Engineer](https://angel.co/company/layertwo/jobs/702600-junior-full-stack-engineer)

Mythical Games | Los Angeles, CA

[Software Engineer - Blockchain](https://www.indeed.com/viewjob?jk=67ef27adc1ed8c84)

Nervos | Remote

[Developer Relations](https://angel.co/company/nervos-1/jobs/710826-developer-relations)

Nervos | Hangzhou, China; Remote

[Senior blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

Offchain Labs | NYC, US

[Senior Software Engineer](https://jobs.lever.co/offchainlabs/9b024e89-1cb7-43f3-b6f8-c7a2d78636b5)

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#11 draft](/draft), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
