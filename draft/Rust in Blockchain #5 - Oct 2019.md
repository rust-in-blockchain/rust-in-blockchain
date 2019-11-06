**Rust in Blockchain #5 - Oct 2019**
**#5 - Oct 2019**

Welcome to the #5 edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies. [Previous #3](https://rustinblockchain.org/2019/10/03/rust-in-blockchain-4-september-2019/).

The highlight this month was [San Francisco Blockchain Week][sfbw]. This was a huge series of events, with representation from a number of Rust blockchain projects, including [Cosmos], [Nervos], [Parity], [Solana],
TODO more companies, summary links.

That wasn't the only big event in October though. [DevCon] in Tokyo also featured a number of Rust blockchain projects. TODO

[sfbw]: https://sfblockchainweek.io

&nbsp;


**Project updates**

#### [**Grin**](https://github.com/mimblewimble/grin)

[Grin Newsletter](https://grinnews.substack.com/)

#### [**InterLedger**](https://github.com/interledger-rs/interledger-rs)

#### [**Near**](https://github.com/nearprotocol/nearcore)

- [News: Stake Wars, NEAR Protocol’s incentivized testnet program][near-stakewars]
- [News: The Future of Blockchain Hackathon – Applications still open!][near-hackathon]
- [Video: NEAR Lunch and Learn Ep. 01: Cross Shard Transactions with One Block Delay][near-video-crosshhard]
- [Video: NEAR Lunch & Learn Ep. 02: Economics in a Sharded Blockchain][near-video-economics]

[near-hackathon]: https://nearprotocol.com/blog/the-future-of-blockchain-hackathon/
[near-stakewars]: https://nearprotocol.com/blog/stake-wars-registration-is-now-open/
[near-video-crosshhard]: https://www.youtube.com/watch?v=mhJXsOKoSdg
[near-video-economics]: https://www.youtube.com/watch?v=QhQi2nAd-r0

#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)
- [News: Nervos CKB Development Update #22][nervos-dev]. Version 0.24.0. New RFC [PR#142][nervos-pr-142] describing deposit and withdrawal transactions in the Nervos DAO.
- [News: Nervos Community Update][nervos-community]
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
- [Nervos CKB Development Update](https://medium.com/nervosnetwork/tagged/development-updates)

[nervos-dev]: https://medium.com/nervosnetwork/nervos-ckb-development-update-22-97bb2c943364
[nervos-pr-142]: https://github.com/nervosnetwork/rfcs/blob/2aa14e142397570778f300468de2bb427e485507/rfcs/0000-dao-deposit-withdraw/0000-dao-deposit-withdraw.md
[nervos-community]: https://medium.com/nervosnetwork/nervos-community-update-6e9cced395ff
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

#### [**Oasis**](https://github.com/oasislabs)

#### [**Parity** ](https://github.com/paritytech)

[**Substrate**](https://github.com/paritytech/substrate)

[**Polkadot**](https://github.com/paritytech/polkadot)

#### [**Solana**](https://github.com/solana-labs/solana)

Summary: Solana development is strikingly active, landing 403 PRs in October. They have [renamed their runtime to "sealevel"][solana-pr-3] as part of an effort to make their code reusable by other projects.

- [Blog: Inside Solana's internal scalability test][solana-blog-1].
- [Blog: A blockchain dilemma: chain forks, catastrophic re-orgs, and insurance][solana-blog-2].
- [Podcast: No Sharding #8: Censorship Free Companies on Chain. Unstoppable Domains Founder Brad Kam][solana-pod]
- [PR: Rename solana-runtime to sealevel][solana-pr-3]. Part of an effort to make the solana runtime embeddable by other projects.
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

&nbsp;

**Learning**

[Podcast (in Chinese): ForkIt: chat with Tang Wei from Parity and Xiao Xuejie from Nervos](https://forkit.fm/9)

&nbsp;

**Interesting Things**

[Ferris Fencing: An eternal duel between programmable crabs with swords.](http://www.ferrisfencing.org/) It is a showcase of CKB-VM, a simple implementation of the RISC-V instruction set, written in the Rust programming language.

[Reddit discussion on Rust & Blockchain](https://www.reddit.com/r/rust/comments/dpakxq/rust_2020_more_or_less/f5tpnkx?utm_source=share&utm_medium=web2x)

&nbsp;

**Events**

&nbsp;

**Careers**

&nbsp;

**Join the action on our** [**subreddit**](https://www.reddit.com/r/RustInBlockchain/) **❤️**
