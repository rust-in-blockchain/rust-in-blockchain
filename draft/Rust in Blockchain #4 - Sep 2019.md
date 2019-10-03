**Rust in Blockchain #4 - Sep 2019**
**#4 - Sep 2019**

Welcome to the fourth edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies. [Previous #3](https://rustinblockchain.org/2019/09/05/rust-in-blockchain-3-august-2019/).

September featured Berlin Blockchain week, one of the biggest blockchain events of the year, and a number of Rust blockchain projects
were there. We held Rust in Blockchain events in Berlin as well as in Hangzhou, the videos for which (in Chinese) are linked below in the "learning" section.

Rust in Blockchain has a new logo, and there are [stickers][stick]! They will probably be found at various events...

[Signer]: https://www.parity.io/signer/
[stick]: https://twitter.com/Aimee_Z_/status/1176279394748268545/photo/1
[nervos-1]: https://github.com/nervosnetwork/rfcs/pull/138


&nbsp;


**Project updates**

#### [**Grin**](https://github.com/mimblewimble/grin)

- [News: Experimental Tor Integration and Testing](https://github.com/mimblewimble/grin-wallet/pull/226)
- [News: A New Journey with MimbleWimble](https://www.grin-forum.org/t/a-new-journey-with-mimblewimble/6058)
- [Issue: Invalid Root #3016](https://github.com/mimblewimble/grin/issues/3016)
- [PR: Fix reading POW for edge bits 59 and higher](https://github.com/mimblewimble/grin/pull/3069) by [@hashmap](https://github.com/hashmap)
- [PR: Fix finding common header between the header chain and the current body chain](https://github.com/mimblewimble/grin/pull/3033) by [@garyyu](https://github.com/garyyu)

[Grin Newsletter](https://grinnews.substack.com/)


#### [**Near**](https://github.com/nearprotocol/nearcore)

- [PR: Adding merkle proof to prev chunk header](https://github.com/nearprotocol/nearcore/pull/1353) by [@Kouprin](https://github.com/Kouprin)
- [PR: Runtime asynchrony tests](https://github.com/nearprotocol/nearcore/pull/1283) by [@nearmax](https://github.com/nearmax)
- [PR: Contract rewards](https://github.com/nearprotocol/nearcore/pull/1258) by [@ evgenykuzyakov](https://github.com/evgenykuzyakov)
- [Video: Benny Giang from Dapper Labs](https://www.youtube.com/watch?v=Ww8XDdpw2Pk)
- [Video: Taylor Wei from Top Network](https://www.youtube.com/watch?v=PXLjORNlqlE)
- [Video: Jaynti Kanani from Matic](https://www.youtube.com/watch?v=P0hDzOzwzYw)
- [Blog: Use Case - Distributed Identity Solutions](https://nearprotocol.com/blog/use-case-distributed-identity-solutions/) by [@Anais Urlichs](https://twitter.com/urlichsanais)
- [Blog: Long Range Attacks, and a new Fork Choice Rule](https://nearprotocol.com/blog/long-range-attacks-and-a-new-fork-choice-rule/) by [@Alex Skidanov](https://twitter.com/alexskidanov)

#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)

- [News: Nervos CKB Development Update #19][nervos-dev]. Changes to consensus rules. Version 0.21.0.
- [News: Meet the team behind the project][nervos-team]
- [News: The 5th and Final Round of our Mining Competition: Stage 1][nervos-comp]
- [News: Nervos positioning paper][nervos-pos]. Nervos is "developing the only PoW, multi-asset & store of value blockchain in the world today", as described in [RFC 0001][nervos-01].
- [News: Nervos CKByte public sale announcement][nervos-ann]. CKB will sell on [CoinList] on October 16th.
- [Video: Matt Quinn discusses the testnet, token sale][nervos-vid]

[Nervos CKB Development Update](https://medium.com/nervosnetwork/tagged/development-updates)

[nervos-vid]: https://www.youtube.com/watch?v=SbGO2n3PTBE&t=938s
[CoinList]: https://coinlist.co/nervos
[nervos-ann]: https://medium.com/nervosnetwork/nervos-ckbyte-public-sale-date-announcement-b5be874e0646
[nervos-01]: https://github.com/nervosnetwork/rfcs/blob/79a6774eb16f5077617f3eef580653316fbdcb16/rfcs/0001-positioning/0001-positioning.md
[nervos-pos]: https://medium.com/nervosnetwork/nervos-positioning-paper-4de6443bbfb8
[nervos-comp]: https://medium.com/nervosnetwork/the-5th-and-final-round-of-our-mining-competition-stage-1-62f7ce4fb7c5
[nervos-dev]: https://medium.com/nervosnetwork/nervos-ckb-development-update-19-4c08c740e66b
[nervos-team]: https://medium.com/nervosnetwork/nervos-meet-the-team-behind-the-project-5f5b64473956


#### [**Parity** ](https://github.com/paritytech)

- [News: Preparing for Istanbul: New Parity Ethereum release][parity-istanbul]. This release is compatible with the [Istanbul hardfork][istanbul].
- [News: Hacktoberfest 2019][parity-hack]. It's easy to get involved in Parity during Hacktoberfest.
- [News: Parity Signer 3.0 Beta is here!][parity-signer]. Parity Signer is a mobile application that turns your old smartphone into a hardware wallet.
- [News: Peter @ Parity discusses ongoing maintenance of their Ethereum client][parity-peter]

[parity-istanbul]: https://www.parity.io/preparing-for-istanbul-parity-ethereum/
[parity-hack]: https://www.parity.io/hacktoberfest-2019-parity/
[parity-signer]: https://www.parity.io/parity-signer-v3-0-beta-is-here/
[parity-peter]: https://twitter.com/PAMauric/status/1176209384386568192

[istanbul]: https://eips.ethereum.org/EIPS/eip-1679


[**Substrate**](https://github.com/paritytech/substrate)

- [Video: Substrate: One Year Later][substrate-year] by Shawn Tabrizi. From Web3 Summit.
- [PR: Add proof-of-work consensus][substrate-3473] by [@sorpass]
- [PR: Make staking inflation curve configurable][substrate-3644] by [@thiolliere]
- [PR: Explicit sync API for downloading important, possibly orphaned, forks][substrate-3633] by [@rphmeier]

[substrate-year]: https://www.youtube.com/watch?v=2JxjGZ3fsi4
[substrate-3644]: https://github.com/paritytech/substrate/pull/3644
[substrate-3473]: https://github.com/paritytech/substrate/pull/3473
[substrate-3633]: https://github.com/paritytech/substrate/pull/3633
[@sorpass]: https://github.com/sorpaas
[@thiolliere]: https://github.com/thiolliere
[@rphmeier]: https://github.com/rphmeier


[**Polkadot**](https://github.com/paritytech/polkadot)

- [Video: Parathreads on Polkadot][polkadot-para] by Joe Petrowski
- [News: The Polkadot wiki is upgraded][polkadot-wiki]
- [Blog: How to upgrade a Kusama CC1 validator to CC2][polkadot-kusama] by Francesco Cremona. Kusama is a Polkadot testnet.

[polkadot-kusama]: https://medium.com/simply-vc/how-to-upgrade-a-kusama-cc1-validator-to-cc2-4c334c92b10b
[polkadot-wiki]: https://www.reddit.com/r/dot/comments/dbra21/polkadots_wiki_has_been_upgraded_check_it_out/
[polkadot-para]: https://youtu.be/BIydDBZsjVg

[**Parity Ethereum**](https://github.com/paritytech/parity-ethereum)

- [v2.5.9 was released][parity-eth-259]
- [v2.5.8 was released][parity-eth-258]

[parity-eth-259]: https://github.com/paritytech/parity-ethereum/releases/tag/v2.5.9
[parity-eth-258]: https://github.com/paritytech/parity-ethereum/releases/tag/v2.5.8


#### [**Solana**](https://github.com/solana-labs/solana)

- [PR: Clippy work towards Rust 1.38](https://github.com/solana-labs/solana/pull/6219) by [@mvines](https://github.com/mvines)
- [PR: Bench-tps: flush tx queue when too old](https://github.com/solana-labs/solana/pull/6201) by [@CriesofCarrots](https://github.com/CriesofCarrots)
- [PR: BPF programs use single threaded LLD](https://github.com/solana-labs/solana/pull/6088) by [@jackcmay](https://github.com/jackcmay)
- [PR: Require stake, vote and executable accounts to be rent exempt](https://github.com/solana-labs/solana/pull/5928) by [@ParthDesai](https://github.com/ParthDesai)
- [PR: A new data-structure in shreds for partial deserialization](https://github.com/solana-labs/solana/pull/5915) by [@ pgarg66](https://github.com/pgarg66)
- [PR: Rust BPF programs depend on Solana SDK](https://github.com/solana-labs/solana/pull/5819) by [@jackcmay](https://github.com/jackcmay)

&nbsp;

**Challenges**

[Grin: Allow nodes to (manually) recover from dreaded "Already Spent" error #3018](https://github.com/mimblewimble/grin/issues/3018)
[Near: Better `tx` RPC API #1299](https://github.com/nearprotocol/nearcore/issues/1299)

&nbsp;

**Learning**

[Blockchain Tutorial in Rust](https://github.com/ibaryshnikov/blockchain-tutorial)

[Introduction to Nervos CKB Script Programming 3: UDT](https://xuejie.space/2019_09_06_introduction_to_ckb_script_programming_udt/)

[Video] [Rust for Decentralized Technology Berlin Meetup](https://www.youtube.com/watch?v=Aoc0UE2Mlb4&feature=youtu.be)

[Video] [WASM on the blockchain](https://www.youtube.com/watch?v=Cj6nOyBnQiY)

[Video] [In Chinese] [Cell Model and Logic Programming](https://www.youtube.com/watch?v=0rytag5Jktw&t=34s)

[Video] [In Chinese] [Wallet’s cross platform practice in Rust](https://youtu.be/OQQiiYTtyc8)

&nbsp;

**Interesting Things**

[If you Run a Small Business Park In the Back of the Parking Lot](https://twitter.com/xxuejie/status/1177060948441362433?s=12)

&nbsp;

**Events**

October 1-31 | Online

[Hacktoberfest](https://hacktoberfest.digitalocean.com/)

October 1 | Seoul, South Korea

[Polkadot Meetup with Gavin Wood](https://www.meetup.com/Polkadot-Seoul/events/264756518/)

October 8-11 | Osaka, Japan

[DevCon](https://devcon.org/)

October 19-20 | Berlin, Germany

[Lighting Conference](https://www.thelightningconference.com/)

October 19-20 | Berlin, Germany

[Diffusion 2019: Blockchain Hackathon](https://diffusion.events/)

October 26 | Tokyo, Japan

[Rust Tokyo](https://rust.tokyo/)

October 28 - November 3 | San Francisco & Berkeley, US

[SF Blockchain Week 2019](https://sfblockchainweek.io/)

October 30 | San Francisco, US

[Rust in Blockchain Workshops](https://www.meetup.com/Rust-in-Blockchain-San-Francisco/events/265362152)

&nbsp;

**Careers**

Centrifuge | Berlin, Germany; Remote

[Rust Engineer](https://centrifuge.breezy.hr/p/20af596b9ffb01-rust-engineer-centrifuge-chain/)

Chainlink | Remote

[Senior Software Engineer](https://remotive.io/remote-jobs/software-dev/senior-software-engineer-18917)

Commonwealth | San Francisco; Remote

[Blockchain Engineer](https://angel.co/company/commonwealth-labs/jobs/454577-commonwealth-blockchain-engineer)

Consensys | Europe; United States; Remote

[Systems Engineer - Rust](https://consensys.net/open-roles/1792013/)

imToken | Singapore; Hangzhou, China

[Blockchain Development Engineer](https://token.im/careers)

IOHK | Europe

[Software Engineer - Rust](https://iohk.io/careers/#op-345001-software-engineer-rust)

Jsgenesis | Oslo, Europe; Remote

[Senior Blockchain Developer](https://www.jsgenesis.com/jobs/blockchain-developer)

Kraken | Berlin, Germany; Remote

[Software Engineer, Crypto/Payments](https://jobs.lever.co/kraken/4c18a043-3f9f-4005-a715-7455aaa64b11)

MXC Foundation | Berlin, Germany

[Rust Engineer](https://www.linkedin.com/jobs/view/1455662885/?refId=3445947911569942562383&trk=d_flagship3_company)

Nervos | San Francisco; Hangzhou, China; Remote

[Senior Test Manager](https://angel.co/company/nervos-1/jobs/589746-senior-test-manager)

[Senior blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

Parity | Berlin, Germany

[Rust/Core Developer](https://www.parity.io/jobs/#berlin-rust-core-developer)

&nbsp;

**Join the action on our** [**subreddit**](https://www.reddit.com/r/RustInBlockchain/) **❤️**
