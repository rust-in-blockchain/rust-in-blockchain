# RiB Newsletter #8 - Jan 2020

**#8 - Jan 2020**

Welcome to the #8 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. [Previous: #7](https://rustinblockchain.org/2020/01/02/rust-in-blockchain-7-december-2019/).



&nbsp;


## Project spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Most Active in January

[Zcash]: https://z.cash/
[Solana]: https://github.com/solana-labs/solana
[Parity]: https://github.com/paritytech
[COMIT]: https://comit.network/
[NEAR]: https://github.com/nearprotocol/nearcore

&nbsp;



## Project updates

#### [**COMIT**](https://comit.network/)

186 merged PRs ([1][comit-mergedpr1], [2][comit-mergedpr2]), 64 closed issues ([1][comit-issue1], [2][comit-issue2]).

[comit-mergedpr1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[comit-mergedpr2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[comit-issue1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31
[comit-issue2]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- Blog: [January, 2020 - Dev Update](https://blog.coblox.tech/2020/01/31/january-dev-update.html)
- PR: [Add cache for Bitcoin and Ethereum connectors](https://github.com/comit-network/comit-rs/pull/1912)
- PR: [Encode the capability of deriving a Secret into the type system so that only Alice can do that](https://github.com/comit-network/comit-rs/pull/1795)
- PR: [Improve current logging](https://github.com/comit-network/comit-rs/pull/1786)
- PR: [Resume in progress swaps](https://github.com/comit-network/comit-rs/pull/1735)

#### [**Grin**](https://github.com/mimblewimble/grin)

[25 merged PRs][grin-mergedpr], [29 closed issues][grin-issue].

[grin-mergedpr]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[grin-issue]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- News: [Grin 2020 roadmap](https://github.com/mimblewimble/grin-rfcs/pull/38)
- News: [#83: Non-interactive transactions](https://grinnews.substack.com/p/83-non-interactive-transactions-)
- News: [#82: Security team proposed](https://grinnews.substack.com/p/82-security-team-proposed-)
- News: [#81: Grin 3.0.0](https://grinnews.substack.com/p/81-grin-300-)
- News: [#80: Hard fork imminent](https://grinnews.substack.com/p/80-hard-fork-imminent-)
- News: [#79: $77m worth of Grin mined in 2019](https://grinnews.substack.com/p/79-77m-worth-of-grin-mined-in-2019)
- PR: [Cleanup redundant AsFixedBytes and FixedLength traits](https://github.com/mimblewimble/grin/pull/3131)
- Issue: [Replace input commitment by 8 bytes MMR position](https://github.com/mimblewimble/grin/issues/2864)
- Issue: [P2P transaction building](https://github.com/mimblewimble/grin/issues/1798)
- Issue: [Consider relaxing timestamp monotonicity](https://github.com/mimblewimble/grin/issues/1486)

#### [**Interledger**](https://interledger.org/)

[18 merged PRs][interledger-mergedpr], [7 closed issues][interledger-issue].

[interledger-mergedpr]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2020-01-01..2020-01-31
[interledger-issue]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- PR: [Interledger Stream: Futures 0.3 Transition](https://github.com/interledger-rs/interledger-rs/pull/601)
- PR: [Interledger API: Futures 0.3 Transition](https://github.com/interledger-rs/interledger-rs/pull/605)
- Issue: [Unable to settle a payment between connectors](https://github.com/interledger-rs/interledger-rs/issues/581)

#### [**NEAR**](https://github.com/nearprotocol/nearcore)

[61 merged PRs][near-mergedpr], [64 closed issues][near-issue].

[near-mergedpr]: https://github.com/nearprotocol/nearcore/pulls?q=is%3Apr+is%3Amerged+merged%3A2020-01-01..2020-01-31
[near-issue]: https://github.com/nearprotocol/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2020-01-01..2020-01-31

- News: [NEAR Community Update: January 17th, 2020](https://nearprotocol.com/blog/near-community-update-january-17th-2020/)
- Blog: [Welcome to the NEAR Community!](https://nearprotocol.com/blog/nearcon-zero/)
- Blog: [We’re pausing Stake Wars](https://nearprotocol.com/blog/were-pausing-stake-wars/)
- Blog: [NEAR 2019 Year in Review](https://nearprotocol.com/blog/near2019/)
- Blog: [Introducing the ARterra Platform](https://medium.com/arterra-engagement/introducing-the-arterra-platform-fe551a99037b)
- Video: [Whiteboard Series with NEAR | Ep: 32 Tim Moreton from Celo](https://www.youtube.com/watch?v=jbSvdNj5zNc)
- Video: [Sharding Jam with Alex Skidanov](https://www.youtube.com/watch?v=tDeb0LACCag)
- Video: [Wasm Chains: Featuring NEAR Protocol](https://www.youtube.com/watch?v=75hO1j-T1LY)
- Video: [Cross-app communication (Ethereum Serenity, NEAR, Polkadot, Cosmos)](https://www.youtube.com/watch?v=EYzYAokCVgMs)
- PR: [Doomslug](https://github.com/nearprotocol/nearcore/pull/1991)
- PR: [Answer to StateRequest in parallel](https://github.com/nearprotocol/nearcore/pull/1916)
- PR: [NumBlocks, NumShards, NumSeats, HeightDelta and _seats](https://github.com/nearprotocol/nearcore/pull/1882)
- Issue: [Block fork question](https://github.com/nearprotocol/nearcore/issues/1924)
- Issue: [Unexpected error msgs in state_sync](https://github.com/nearprotocol/nearcore/issues/1824)
- Issue: [Investigate too many open files error](https://github.com/nearprotocol/nearcore/issues/1316)

#### [**Nervos**](https://github.com/nervosnetwork/ckb)


#### [**Oasis**](https://github.com/oasislabs)


#### [**Parity** ](https://github.com/paritytech)


#### [**Solana**](https://github.com/solana-labs/solana)

[364 merged pull requests][solana-mergedprs],
[47 closed issues][solana-closedissues].

[solana-mergedprs]: https://github.com/solana-labs/solana/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[solana-closedissues]: https://github.com/solana-labs/solana/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04

- Blog: [SLP1 Cluster Launch](https://medium.com/solana-labs/slp1-cluster-launch-4634848d2343).
  The "Soft Launch Phase 1" cluster is a testnet that is intended to gradually be upgraded to the Solana mainnet.
- News: [Solana launches "Tour de SOL" incentivised testnet](https://twitter.com/solana/status/1223094881540665346).
- News: [Monthly Roundup for January 20](https://chorusone.substack.com/p/monthly-roundup-jan-20)
- PR: [Propose Solana ABI management](https://github.com/solana-labs/solana/pull/7524).
  Technical solutions for catching ABI breakage in serialized structures.

#### [**Zcash**](https://z.cash/)

37 merged pull requests ([1][zcash-mergedprs1], [2][zcash-mergedprs2]),
13 closed issues ([1][zcash-closedissues1], [2][zcash-closedissues2]).

[zcash-mergedprs1]: https://github.com/ZcashFoundation/zebra/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[zcash-mergedprs2]: https://github.com/zcash/librustzcash/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A2020-01-02..2020-02-04
[zcash-closedissues1]: https://github.com/ZcashFoundation/zebra/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04
[zcash-closedissues2]: https://github.com/zcash/librustzcash/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2020-01-02..2020-02-04

- Blog: [A New Network Stack for Zcash](https://www.zfnd.org/blog/a-new-network-stack-for-zcash/). About the Rust implementation of Zcash.
- Blog: [Composable Futures-based Batch Verification](https://www.zfnd.org/blog/futures-batch-verification/)
- Paper: [Security assessments: NU3 specifications, Blossom implementation and Sapling documentation](https://electriccoin.co/blog/security-assessments-nu3-specifications-blossom-implementation-and-sapling-documentation/).
  "NU3" = "network upgrade 3", and "Blossom" is its codename. Sapling is Zcash's current zero-knowledge proof scheme that was introduced in 2018.
- Paper: [Trail of Bits Zcash whitepaper](https://github.com/trailofbits/publications/blob/master/reviews/ZcashWP.pdf).
  A new, clear, description of the Zcash protocol, including Sapling proofs. Produced for the security assessment.
- Blog: [ECC releases resources for building mobile, shielded-Zcash wallets](https://electriccoin.co/blog/ecc-releases-resources-for-building-mobile-shielded-zcash-wallets/).
  The Android SDK includes Rust code.
- PR: [Refine Ed25519 byte arrays to ed25519-zebra types](https://github.com/ZcashFoundation/zebra/pull/199)
  Introduces a [zebra-customized ed25519 crate][zced].
- PR: [ZIP 213 - Shielded coinbase transactions](https://github.com/zcash/zips/pull/217).
  This will make it possible to mine coins that are immediately private, whereas today all mined coins are public.
- Blog: [Introducing monthly Zcash community calls](https://electriccoin.co/blog/introducing-monthly-zcash-community-calls/)
- Blog: [ZIP 1014 results](https://www.zfnd.org/blog/zip-1014-poll-results/)
  About funding Zcash.
- Blog: [Dev fund poll shows consensus](https://electriccoin.co/blog/dev-fund-poll-shows-consensus/).

[zced]: https://github.com/ZcashFoundation/ed25519-zebra

&nbsp;


## Challenges


&nbsp;

## Learning


&nbsp;

## Interesting Things


&nbsp;

## Events


&nbsp;

## Careers


&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#8 draft](), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
