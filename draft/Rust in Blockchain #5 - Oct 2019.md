**Rust in Blockchain #5 - Oct 2019**
**#5 - Oct 2019**

Welcome to the fifth edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies. [Previous: #4](https://rustinblockchain.org/2019/10/03/rust-in-blockchain-4-september-2019/).

The highlight this month was [San Francisco Blockchain Week][sfbw]. This was a huge series of events, with representation from a number of Rust blockchain projects. Several projects, [Interledger], [Near], [Nervos], [Oasis], and [Parity] came together for a day of [Rust in Blockchain workshops][ribw].

[sfbw]: https://sfblockchainweek.io
[Interledger]: https://interledger.org/
[Near]: https://nearprotocol.com/
[Nervos]: https://www.nervos.org
[Oasis]: https://www.oasislabs.com/
[Parity]: https://www.parity.io/
[ribw]: https://twitter.com/rust_blockchain/status/1189263450058493953

That wasn't the only big event in October though. [DevCon] in Tokyo also included several Rust blockchain projects, from which several of Parity's talks are linked below.

[DevCon]: https://devcon.org/

&nbsp;


**Project updates**

#### [**Grin**](https://github.com/mimblewimble/grin)

- [Video: Special Guest Charlie Lee on MimbleWimble Extension Blocks on LTC, Fungibility and Grin][grin-video-guest]
- [Video: Interview with Grin Developer David Burkett][grin-interview]
- [Podcast: ZK - MimbleWimble pt 1: Grin with Daniel Lehnberg][grin-podcast]
- [PR: Support for Homebrew][grin-pr-homebrew] by [@quentinlesceller](https://github.com/quentinlesceller)
- [PR: Improved Wallet State Management][grin-pr-walletmanage] by [@yeastplume](https://github.com/yeastplume)
- [PR: Enable faster sync][grin-pr-sync] by [@antiochp](https://github.com/antiochp)
- [Grin Newsletter](https://grinnews.substack.com/)

[grin-video-guest]: https://www.youtube.com/watch?v=J37rUzQZ64k
[grin-interview]: https://www.youtube.com/watch?v=OyEfz6ZqDSw
[grin-podcast]: https://www.zeroknowledge.fm/97
[grin-pr-homebrew]: https://github.com/Homebrew/homebrew-core/pull/45833
[grin-pr-walletmanage]: https://github.com/mimblewimble/grin-rfcs/pull/30
[grin-pr-sync]: https://github.com/mimblewimble/grin-rfcs/pull/29

#### [**InterLedger**](https://github.com/interledger-rs/interledger-rs)

#### [**Near**](https://github.com/nearprotocol/nearcore)

- [News: Stake Wars, NEAR Protocol’s incentivized testnet program][near-stakewars]
- [News: The Future of Blockchain Hackathon – Applications still open!][near-hackathon]
- [Video: NEAR Lunch and Learn Ep. 01: Cross Shard Transactions with One Block Delay][near-video-crosshhard]
- [Video: NEAR Lunch & Learn Ep. 02: Economics in a Sharded Blockchain][near-video-economics]
- [Video: Building NEAR Live][near-video-tv]
- [PR: Early work on chaos monkey][near-pr-1]
- [PR: New networking API][near-pr-2]
- [PR: Sodiumoxide vulnerability fix][near-pr-3]. [Update your sodiumoxide deps][sodium].
- [Blog: Near Community Update][near-blog]

[sodium]: https://www.reddit.com/r/rust/comments/dguqt3/vulnerability_in_sodiumoxide_generichashdigesteq/
[near-pr-3]: https://github.com/nearprotocol/nearcore/pull/1452
[near-pr-2]: https://github.com/nearprotocol/nearcore/pull/1312
[near-pr-1]: https://github.com/nearprotocol/nearcore/pull/1438
[near-hackathon]: https://nearprotocol.com/blog/the-future-of-blockchain-hackathon/
[near-stakewars]: https://nearprotocol.com/blog/stake-wars-registration-is-now-open/
[near-video-crosshhard]: https://www.youtube.com/watch?v=mhJXsOKoSdg
[near-video-economics]: https://www.youtube.com/watch?v=QhQi2nAd-r0
[near-video-tv]: https://www.twitch.tv/nearprotocol/
[near-blog]: https://nearprotocol.com/blog/goodbye-san-francisco-november-1st-2019/

#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)
- [News: Nervos CKB Development Update #22][nervos-dev]. Version 0.24.0. New RFC [PR#142][nervos-pr-142] describing deposit and withdrawal transactions in the Nervos DAO.
- [News: Nervos CKB Security Audit Complete][nervos-audit]
- [News: Bug Bounty][nervos-challenges]
- [News: Mining Competition Round 5][nervos-mining]
- [News: BTC.com Open Source CKB Mining Pool][nervos-mining-pool]
- [News: A Decentralized Mainnet Launch for Nervos CKB][nervos-mainnet]
- [PR: Use molecule to serialize witnesses][nervos-pr-1739] by [@jjyr](https://github.com/jjyr)
- [PR: Resolved uncles hash calculation issue][nervos-pr-1707] by [@quake](https://github.com/quake)
- [PR: Adapt to 2-phase Nervos DAO implementation][nervos-pr-1769] by [@xxuejie](https://github.com/xxuejie)
- [Video: Nervos CKB bringing back GPU Mining?! Dual Mine Ethereum and CKB][nervos-mining-video]
- [Video: Nervos CKB and the Multi-asset, Store of Value Security Model][nervos-intro]
- [Blog: Introduction to CKB Script Programming 4: WebAssembly on CKB](nervos-blog-wasm)
- [Blog: Introduction to CKB Script Programming 5: Debugging](nervos-blog-debugging)
- [Blog: Let's Build a Minimal Blockchain 1: Dawn](nervos-blog-minimalchain)
- [Nervos CKB Development Update][nervos-community-dev]
- [Nervos Community Update][nervos-community]

[nervos-dev]: https://medium.com/nervosnetwork/nervos-ckb-development-update-22-97bb2c943364
[nervos-pr-142]: https://github.com/nervosnetwork/rfcs/blob/2aa14e142397570778f300468de2bb427e485507/rfcs/0000-dao-deposit-withdraw/0000-dao-deposit-withdraw.md
[nervos-audit]: https://medium.com/nervosnetwork/nervos-ckb-security-audit-complete-1e7a7561cfb6
[nervos-challenges]: https://medium.com/nervosnetwork/announcing-the-nervos-bug-bounty-ab8ef5a2fc9e
[nervos-mainnet]: https://medium.com/nervosnetwork/a-decentralized-mainnet-launch-for-nervos-ckb-9cb119d15540
[nervos-mining-pool]: https://medium.com/nervosnetwork/btc-com-open-source-ckb-mining-pool-c3ea7809d532
[nervos-mining]: https://medium.com/nervosnetwork/announcing-mining-competition-round-5-stage-three-4861bd1f0b88
[nervos-mining-video]: https://www.youtube.com/watch?time_continue=1&v=bMQwylHiqQw
[nervos-intro]: https://www.youtube.com/watch?v=AXTvoSJo8Cg&t=2s
[nervos-pr-1739]: https://github.com/nervosnetwork/rfcs/blob/2aa14e142397570778f300468de2bb427e485507/rfcs/0000-dao-deposit-withdraw/0000-dao-deposit-withdraw.md
[nervos-pr-1707]: https://github.com/nervosnetwork/ckb/pull/1707
[nervos-pr-1769]: https://github.com/nervosnetwork/ckb/pull/1769
[nervos-blog-wasm]: https://xuejie.space/2019_10_09_introduction_to_ckb_script_programming_wasm_on_ckb/
[nervos-blog-debugging]: https://xuejie.space/2019_10_18_introduction_to_ckb_script_programming_debugging/
[nervos-blog-minimalchain]: https://xuejie.space/2019_10_21_lets_build_a_minimal_blockchain_dawn/
[nervos-community-dev]: https://medium.com/nervosnetwork/tagged/development-updates
[nervos-community]: https://medium.com/nervosnetwork/nervos-community-update-6e9cced395ff

#### [**Oasis**](https://github.com/oasislabs)

- [Blog: CHURP: Dynamic-committee proactive secret sharing][oasis-blog-1].
- The [tutorials][oasis-tut] gained two new examples: [dice-game] and [rock-paper-scissors].

[rock-paper-scissors]: https://github.com/oasislabs/tutorials/tree/master/rock-paper-scissors
[dice-game]: https://github.com/oasislabs/tutorials/tree/master/dice-game
[oasis-tut]: https://github.com/oasislabs/tutorials/pulls
[oasis-blog-1]: https://medium.com/oasislabs/churp-dynamic-committee-proactive-secret-sharing-5b0446061663

#### [**Parity** ](https://github.com/paritytech)

Summary: Parity had many talks at the events this month, and videos for some are available. The first Polkadot network, [Kusama], launched. Substrate continues to be under heavy development, with 198 PRs landed in October.

[Kusama]: https://kusama.network/

- [Video: Toward backward compatible Ethereum upgrades][par-vid-1]. Wei Tang, from DevCon.

[par-vid-1]: https://slideslive.com/38920073/lessons-learned-to-build-a-dapp-on-a-light-client

[**Substrate**](https://github.com/paritytech/substrate)

- [Blog: Gather: A decentralized alternative to meetup.com built on substrate][sub-blog-1]
- [Blog: SubRogue][sub-blog-3]. A blockchain [Rogue-like] game built with Substrate.
- [Blog: People of Parity: Benjamin Kampmann][sub-blog-2]
- [Podcast: Mentorship and Values in Open-Source Development][sub-pod-1]. Another interview w/ Ben Kampmann.
- [PR: Substrate EVM][sub-pr-1]. Run Ethereum contracts on Substrate.
- [Video: Building Ethereum 2.0 on Substrate][sub-vid-1]. Wei Tang, from DevCon.

[Rogue-like]: https://en.wikipedia.org/wiki/Roguelike
[sub-blog-3]: https://medium.com/@edward.thomson/subrogue-8c0a537f02d4
[sub-vid-1]: https://slideslive.com/38920039/building-ethereum-20-on-substrate
[sub-pr-1]: https://github.com/paritytech/substrate/pull/3927
[sub-blog-1]: https://www.parity.io/gather-why-a-decentralized-blockchain-platform-is-the-only-sustainable-answer-to-the-meetup-com-pricing-hike/
[sub-blog-2]: https://www.parity.io/people-of-parity-benjamin-kampmann/
[sub-pod-1]: https://relaychain.fm/7-mentorship-values-open-source

[**Polkadot**](https://github.com/paritytech/polkadot)

- [News: Announcement of Polkadot ecosystem fund][polk-news-1]
- [Blog: How to create and manage a new DAppNode package (with Polkadot)][polk-blog-1]. [DAppNode] is a tool for managing decentralized infrastructure.
- [Video: Polkadot's Data Availability and Validity Scheme: An Approach to Security at Scale ][polk-vid-1]. Alistair Stewart, from DevCon.
- [News: Kusama network is live][polk-news-2]. Kusama is the first live Polkadot network.
- [Video: Intro to Nominated Proof of Stake][polk-vid-2].
- [Video: The Tip of the Polkadot R&D Iceberg][polk-vid-3]. Rob Habermeier. Web3 Summit.
- [News: Polkadot runs its first Substrate-based parachain][polk-news-2]

[polk-news-2]: https://twitter.com/gavofyork/status/1186646273685884930
[polk-vid-3]: https://www.youtube.com/watch?v=4_Ao-nvPIZI
[polk-vid-2]: https://www.youtube.com/watch?v=l3IoHHxZoX0
[polk-news-2]: https://twitter.com/a4fri/status/1188939968531615745
[polk-vid-1]: https://slideslive.com/38920004/polkadots-data-availability-and-validity-scheme-an-approach-to-security-at-scale
[polk-news-1]: https://polkadot.network/announcing-the-polkadot-ecosystem-fund/
[DAppNode]: https://dappnode.io/
[polk-blog-1]: https://medium.com/luguslabs/how-to-create-and-manage-a-new-dappnode-package-b23460b4449

#### [**Solana**](https://github.com/solana-labs/solana)

Summary: Solana development is strikingly active, landing 403 PRs in October. They are [renaming their runtime to "sealevel"][solana-pr-3] as part of an effort to make their code reusable by other projects.

- [Blog: Inside Solana's internal scalability test][solana-blog-1].
- [Blog: A blockchain dilemma: chain forks, catastrophic re-orgs, and insurance][solana-blog-2].
- [Podcast: No Sharding #8: Censorship Free Companies on Chain. Unstoppable Domains Founder Brad Kam][solana-pod]
- [PR: Rename solana-runtime to sealevel][solana-pr-3]. Part of an effort to make the solana runtime embeddable by other projects. Note that it has been temporarily reverted due to infrastructure issues.
- [PR: Make executable, vote, and stake accounts rent-exempt][solana-pr-1]
- [PR: Add vest program][solana-pr-2]
- [PR: Implement nightly performance tests][solana-pr-4]
- [PR: Add solana-ledger crate][solana-pr-5]

[solana-pr-5]: https://github.com/solana-labs/solana/pull/6415
[solana-blog-2]: https://medium.com/solana-labs/a-blockchain-dilemma-chain-forks-catastrophic-re-orgs-and-insurance-3b88a2fbd2ba
[solana-blog-1]: https://medium.com/solana-labs/inside-solanas-internal-scalability-test-cce13aa8c859
[solana-pod]: https://solana.com/censorship-free-companies-on-chain-unstoppable-domains-founder-brad-kam-episode-8-no-sharding-podcast/
[solana-pr-4]: https://github.com/solana-labs/solana/pull/6140
[solana-pr-3]: https://github.com/solana-labs/solana/pull/6239
[solana-pr-2]: https://github.com/solana-labs/solana/pull/5987
[solana-pr-1]: https://github.com/solana-labs/solana/pull/6017

&nbsp;

**Challenges**

[Nervos Bug Bounty](https://bounty.nervos.org/)

[RFP - Minimal parachain development kit](https://github.com/w3f/Web3-collaboration/issues/204)

&nbsp;

**Learning**

[Podcast (in Chinese): ForkIt: chat with Tang Wei from Parity and Xiao Xuejie from Nervos](https://forkit.fm/9)

&nbsp;

**Interesting Things**

[Ferris Fencing: An eternal duel between programmable crabs with swords.](http://www.ferrisfencing.org/) It is a showcase of CKB-VM, a simple implementation of the RISC-V instruction set, written in the Rust programming language.

[Reddit discussion on Rust & Blockchain](https://www.reddit.com/r/rust/comments/dpakxq/rust_2020_more_or_less/f5tpnkx)

&nbsp;

**Events**

November 9-12 | Barcelona, Spain

[RustFest Barcelona](https://barcelona.rustfest.eu/)

November 22 | Berlin, Germany

[Annual Grin Developer Conference](https://grincon.org/)

&nbsp;

**Careers**

Centrifuge | Berlin, Germany; Remote

[Rust Engineer](https://centrifuge.breezy.hr/p/20af596b9ffb01-rust-engineer-centrifuge-chain/)

Chainlink | Remote

[Senior Software Engineer](https://remotive.io/remote-jobs/software-dev/senior-software-engineer-18917)

Consensys | Europe; United States; Remote

[Systems Engineer - Rust](https://consensys.net/open-roles/1792013/)

imToken | Singapore; Hangzhou, China

[Blockchain Development Engineer](https://token.im/careers)

IOHK | Europe

[Software Engineer - Rust](https://iohk.io/careers/#op-345001-software-engineer-rust)

Jsgenesis | Oslo, Europe; Remote

[Senior Blockchain Developer](https://www.jsgenesis.com/jobs/blockchain-developer)

Kraken | Berlin, Germany; Remote

[Backend Engineer - Crypto/Payments](https://jobs.lever.co/kraken/4c18a043-3f9f-4005-a715-7455aaa64b11)

Leger | Paris, France

[C++ / Rust Software Engineer](https://jobs.lever.co/ledger/8555a86e-fbf4-4701-95cb-190a76445bb8)

MXC Foundation | Berlin, Germany

[Senior Go / Rust Engineer](https://www.linkedin.com/jobs/view/1455662885/?refId=3445947911569942562383&trk=d_flagship3_company)

Nervos | San Francisco; Hangzhou, China; Remote

[Senior Test Manager](https://angel.co/company/nervos-1/jobs/589746-senior-test-manager)

[Senior blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

Parity | Berlin, Germany

[Rust/Core Developer](https://www.parity.io/jobs/#berlin-rust-core-developer)

&nbsp;

**Join the action on our** [**subreddit**](https://www.reddit.com/r/RustInBlockchain/) **❤️**
