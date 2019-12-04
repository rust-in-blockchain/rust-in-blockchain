# Rust in Blockchain #6 - Nov 2019

**#6 - Nov 2019**

Welcome to the #6 edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies. [Previous: #5](https://rustinblockchain.org/2019/11/07/rust-in-blockchain-5-october-2019/).


## Project spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[deoxysii-rust](https://github.com/oasislabs/deoxysii-rust)

This is a great example of the type of useful crates that come out of Rust blockchain projects. It implements the [Deoxys II authenticated encryption scheme][d], which was a winner of the [CAESAR cryptographic competition][c]. Authenticated ciphers ensure both the confidentiality and the authenticity of data, and have particular properties described in the [CAESAR call for submissions][c2].

[d]: https://sites.google.com/view/deoxyscipher
[c]: https://competitions.cr.yp.to/caesar-submissions.html
[c2]: https://competitions.cr.yp.to/caesar-call.html

&nbsp;


## Most Active in November

[Solana](solana): [366][solana-mergedpr] merged PRs, [74][solona-issue] closed issues

[Parity Substrate](substrate): [190][solana-mergedpr] merged PRs, [66][solona-issue] closed issues

[NEAR](near): [97](near-mergedpr) merged PRs, [76][near-issue] closed issues

[Nervos CKB](nervos): [58][nervos-mergedpr] merged PRs, [67][nervos-issue] closed issues


[solona]: https://github.com/solana-labs/solana
[solona-mergedpr]: https://github.com/solana-labs/solana/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2019-11-01..2019-11-30+
[solona-issue]: https://github.com/solana-labs/solana/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2019-11-01..2019-11-30+

[substrate]: https://github.com/paritytech/substrate
[substrate-mergedpr]: https://github.com/paritytech/substrate/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Amerged+merged%3A2019-11-01..2019-11-30
[substrate-issue]: https://github.com/paritytech/substrate/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2019-11-01..2019-11-30+

[near]: https://github.com/nearprotocol/nearcore
[near-mergedpr]: https://github.com/nearprotocol/nearcore/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Amerged+merged%3A2019-11-01..2019-11-30
[near-issue]: https://github.com/nearprotocol/nearcore/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2019-11-01..2019-11-30+

[nervos]: https://github.com/nervosnetwork/ckb
[nervos-mergedpr]:https://github.com/nervosnetwork/ckb/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2019-11-01..2019-11-30+
[nervos-issue]: https://github.com/nervosnetwork/ckb/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2019-11-01..2019-11-30+

&nbsp;


## Project updates

#### [**Enigma**](https://enigma.co/)

- [Blog: New to Enigma? Start here](https://blog.enigma.co/welcome-to-enigma-start-here-e65c8c9125ef)

#### [**Grin**](https://github.com/mimblewimble/grin)

- [PR: Hardfork2][grin-pr-1] by [@tromp](https://github.com/tromp)
- [PR: Increase IO_TIMEOUT to allow nodes on high-latency connections to sync][grin-pr-2] by [@mmgen](https://github.com/mmgen)
- [PR: Enable faster sync][grin-pr-3] by [@antiochp](https://github.com/antiochp)
- [PR: Split state validation status into kernel and rproof updates][grin-pr-4] by [@JosephGoulden](https://github.com/JosephGoulden)
- [issue: Security & Code audits][grin-issue-1]
- [Grin Newsletter](https://grinnews.substack.com/)

[grin-pr-1]: https://github.com/mimblewimble/grin/pull/3136
[grin-pr-2]: https://github.com/mimblewimble/grin/pull/3109
[grin-pr-3]: https://github.com/mimblewimble/grin/pull/3108
[grin-pr-4]: https://github.com/mimblewimble/grin/pull/3096
[grin-issue-1]: https://github.com/mimblewimble/grin/issues/1609

#### [**Near**](https://github.com/nearprotocol/nearcore)

#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)

<!-- todo - [News: Nervos CKB Development Update #24][nervos-dev-1] Aggron Testnet has been reset. Team is focusing on the performance, interfaces, tests and documentations. -->
- [News: Nervos CKB Development Update #23][nervos-dev-2] Version 0.25.2. Mainnet launch.
- [News: Nervos CKB Mainnet is Live][nervos-news-1]
- [PR: Upgrade ckb-vm to 0.18.1][nervos-pr-1] by [@xxuejie](https://github.com/xxuejie)
- [PR: Switch to mainnet][nervos-pr-2] by [@doitian](https://github.com/doitian)
- [PR: Limit tx max ancestors count][nervos-pr-3] by [@jjyr](https://github.com/jjyr)
- [PR: Tweak slot calculation algorithm][nervos-pr-4] by [@xxuejie](https://github.com/xxuejie)
- [Blog: Approach to Designing a User Defined Token Standard on CKB: Part 1][nervos-blog-1]
- [Blog: A General Method to Describe a “Smart Contract” on CKB][nervos-blog-2]
- [Podcast: Alan Szepieniec on Hash Functions & Supersonic SNARKs][nervos-podcast]
- [Nervos CKB Development Update][nervos-community-dev]
- [Nervos Community Update][nervos-community]

<!--[nervos-dev-1]: -->
[nervos-dev-2]: https://medium.com/nervosnetwork/nervos-ckb-development-update-23-6b1ee3f0f8b5
[nervos-news-1]: https://medium.com/nervosnetwork/nervos-ckb-mainnet-is-live-a028d9675dfb
[nervos-pr-1]: https://github.com/nervosnetwork/ckb/pull/1854
[nervos-pr-2]: https://github.com/nervosnetwork/ckb/pull/1824
[nervos-pr-3]: https://github.com/nervosnetwork/ckb/pull/1788
[nervos-pr-4]: https://github.com/nervosnetwork/ckb-vm/pull/90
[nervos-blog-1]: https://talk.nervos.org/t/approach-to-designing-a-user-defined-token-standard-on-ckb-part-1/3855
[nervos-blog-2]: https://talk.nervos.org/t/a-general-method-to-describe-a-smart-contract-on-ckb/3777
[nervos-podcast]: https://www.zeroknowledge.fm/105
[nervos-community-dev]: https://medium.com/nervosnetwork/tagged/development-updates
[nervos-community]: https://medium.com/nervosnetwork/nervos-community-update-6e9cced395ff


#### [**Oasis**](https://github.com/oasislabs)


#### [**Parity** ](https://github.com/paritytech)

- [Blog: Rust 2020](https://www.parity.io/rust-2020/)
- [Blog: Why Chronicled chose to build on Parity's tech stack](https://www.parity.io/chronicled-mediledger-parity/). Parity in the enterprise.
- [Blog: Hello Substrate!](https://www.parity.io/hello-substrate/)
- [Blog: Substrate EVM and Polkadot-Ethereum compatibility](https://www.parity.io/substrate-evm/)
- [Blog: Substrate off-chain workers: secure and efficient computing-intensive tasks](https://www.parity.io/substrate-off-chain-workers-secure-and-efficient-computing-intensive-tasks/)
- [Blog: Parity Ethereum goes to Istanbul](https://www.parity.io/release-parity-ethereum-goes-to-istanbul/). New releases with support for the Istanbul fork.
- [Blog: Ethereum Light Wallet Fether Completes Audit](https://www.parity.io/ethereum-light-wallet-parity-fether-completes-audit-v0-4-beta-shipped/)
- [Blog: Have a TEE with Polkadot](https://polkadot.network/have-a-tee-with-polkadot/?utm_source=twitter&utm_medium=social&utm_campaign=SubstraTEE). SubstraTEE is a framework that integrates trusted execution environments (TEEs) with Substrate-built blockchains.
- [Video: Benjamin Kamppmann & Ricardo Rius of Parity: Build fast blockchains with Substrate](https://vimeo.com/371142433)
- [Podcast: Epicenter: Substrate, Polkadot and the Case for On-Chain Governance](https://epicenter.tv/episodes/259/)
- [Substrate git repo history illustrated with "gource"](https://twitter.com/fredhrson/status/1200470649581527041)
- [Blog: Plasm testnet launch](https://medium.com/staked-technologies/plasm-testnet-launch-90d7e58328b3). A DApps plattform built on Substrate.
- [Video: Participating in Kusama](https://www.crowdcast.io/e/participating-on-kusama/). Kusama is a Polkadot testnet.
- [Blog: Secure and decentralized Polkadot domain name system](https://medium.com/@chainx_org/secure-and-decentralized-polkadot-domain-name-system-e06c35c2a48d)
- [Blog: The future of Kusama and Polkadot](https://commonwealth.im/kusama/proposal/discussion/92?utm_medium=forum&utm_source=r/dots&utm_campaign=Future%20of%20Kusama%20/%20Polkadot)
- [Blog: Polkadot v0.7.0 and Kusama CC-3](https://medium.com/polkadot-network/polkadot-v0-7-0-and-kusama-cc-3-1a121fd59f67). By Gavin Wood.
- [Blog: A comparison of Ethereum vs Polkadot](https://www.purestake.com/blog/ethereum-vs-polkadot/)
- [PR: Erasure encoding availability](https://github.com/paritytech/polkadot/pull/345)
- [PR: Recover transaction pool on light client](https://github.com/paritytech/substrate/pull/3833)


#### [**Solana**](https://github.com/solana-labs/solana)

Solana continues to have a high development velocity, with 368 closed PRs.

- [Blog: Results of Solana's security audit](https://solana.com/the-results-of-solanas-security-audit/)
- [Blog: Solana at SFBW Showed that Cooperation is Key to Blockchain Growth](https://solana.com/solana-at-sfbw-showed-that-cooperation-is-key-to-blockchain-growth/)
- [Podcast: No Sharding ep 10 - History and Future of Networks with AVA Labs founder Emin Gun Sirer](https://solana.com/ava-labs-founder-emin-gun-sirer-episode-10-no-sharding-podcast/)
- [PR: Unfork ed25519-dalek](https://github.com/solana-labs/solana/pull/6776)
- [PR: Revive the parallel bank client](https://github.com/solana-labs/solana/pull/6903). Only used in unit tests.
- [PR: ledger-tool: Automatically run dot to generate PDFs](https://github.com/solana-labs/solana/pull/6912)
- [PR: Add non-fungible token program](https://github.com/solana-labs/solana/pull/7007). SDK example.
- [PR: CLI: Support pubkey recovery from seed phrase](https://github.com/solana-labs/solana/pull/7149)
- [PR: CLI: Add offline signing](https://github.com/solana-labs/solana/pull/7104)


&nbsp;

## Challenges


&nbsp;

## Learning

[Slides and Videos for Grincon1](https://github.com/mimblewimble/grin-pm#grincon1)


&nbsp;

## Interesting Things

[Video: Layer 1 event ft. Solana, NEAR, Harmona, CODA, Nervos](https://www.youtube.com/watch?v=LEKcBeDcEAY)


&nbsp;

## Events

Dec 10 | Online

[Grin Development Meeting ](https://github.com/mimblewimble/grin-pm/issues/224)


&nbsp;

## Careers

Centrifuge | Berlin, Germany; Remote

[Rust Engineer](https://centrifuge.breezy.hr/p/20af596b9ffb01-rust-engineer-centrifuge-chain/)

Chainlink | Remote

[Senior Software Engineer](https://remotive.io/remote-jobs/software-dev/senior-software-engineer-18917)

Consensys | Europe; United States; Remote

[Systems Engineer - Rust](https://consensys.net/open-roles/1792013/)

CyberCoders | Boston, San Francisco

[Senior Software Engineer - Blockchain Solution](https://www.cybercoders.com/senior-software-engineer-job-506965)

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

MixBytes | Remote available

[Rust Developer](https://mixbytes.io/career)

MXC Foundation | Berlin, Germany

[Senior Go / Rust Engineer](https://www.linkedin.com/jobs/view/1455662885/?refId=3445947911569942562383&trk=d_flagship3_company)

Nervos | San Francisco; Hangzhou, China; Remote

[Senior Test Manager](https://angel.co/company/nervos-1/jobs/589746-senior-test-manager)

[Senior blockchain Engineer](https://angel.co/company/nervos-1/jobs/589230-senior-blockchain-engineer)

OneinaMil | New York City; Remote

[Blockchain RUST/WASM Developer](https://apply.workable.com/oneinamil/j/E74222BB58/)

Parity | Berlin, Germany

[Rust/Core Developer](https://www.parity.io/jobs/#berlin-rust-core-developer)

Interledger | San Francisco, US; Remote

[Senior Software Engineer, Rust](https://www.ripple.com/company/careers/all-jobs#senior-software-engineer-rust)

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#7 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/blob/master/draft/Rust%20in%20Blockchain%20%237%20-%20Dec%202019.md), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
