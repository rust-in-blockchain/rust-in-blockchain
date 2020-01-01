# Rust in Blockchain #7 - Dec 2019

**#7 - Dec 2019**

Welcome to the #7 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. <!--[Previous: #6](https://rustinblockchain.org/2019/11/07/rust-in-blockchain-5-october-2019/). -->



&nbsp;


## Project spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[Zebra](https://github.com/ZcashFoundation/zebra).

Zebra is an implementation of Zcash in Rust. It also appears to be the future of Zcash.

Originally developed by Parity, based off [their bitcoin client][pbt], for the Zcash Foundation, [Zebra was announced][zan] in July 2019. In late August development was started over from scratch, to take advantage of modern Rust idioms, to divorce the design from that of bitcoin, and to use a different license. The current version of Zebra is developed by well-known Rust cryptographer [Henry de Valence], co-author of a number of high-profile Rust cryptography libraries, and expert in zero-knowledge proofs.

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

[COMIT][comit]: 113 ([1][comit-mergedpr1], [2][comit-mergedpr2]) merged PRs, 40 ([1][comit-issue1], [2][comit-issue2]) closed issues.

[COMIT]: https://comit.network/
[comit-mergedpr1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[comit-mergedpr2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[comit-issue1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31
[comit-issue2]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

&nbsp;



## Project updates

#### [**COMIT**](https://comit.network/)

- [Blog: Vision and Mission + 2020 goals](https://blog.coblox.tech/2019/12/05/2020-COMIT-goals.html)
- [PR: Make more use of async/await](https://github.com/comit-network/create-comit-app/pull/305)
- [PR: Refactor toward more idiomatic async code](https://github.com/comit-network/create-comit-app/pull/253)
- [PR: Use clarity instead of emerald-rs](https://github.com/comit-network/create-comit-app/pull/286)


#### [**Enigma**](https://enigma.co/)


#### [**Grin**](https://github.com/mimblewimble/grin)


#### [**Interledger**](https://interledger.org/)


#### [**Near**](https://github.com/nearprotocol/nearcore)


#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)


#### [**Oasis**](https://github.com/oasislabs)


#### [**Parity** ](https://github.com/paritytech)


#### [**Solana**](https://github.com/solana-labs/solana)

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

Want to be included in the next issue? Feel free to submit a PR to the [#7 draft](), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**
