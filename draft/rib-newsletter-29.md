---
title: "RiB Newsletter #29 - _TODO_"
description: "#29 - October 2021"
date: 2021-11-03
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #29 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #28](/newsletters/rib-newsletter-28/).

With [total value locked (TVL)][tvl] measurements going up, up, up across the
blockchain world, Ethereum extremely congested, and liquidity providers fleeing
to blockchains with high yields and low fees, there are huge efforts on many
chains to get dapps out fast and attract market share. In the Rust world some
notable developments:

- NEAR [launched an $800 million ecosystem fund][nf] and has been quietly
  climbing up the DeFi TVL charts.
- Secret Network can now bridge to multiple chains and its [SecretSwap] has enough
  liquidity that it will soon be a viable route for discreetely moving assets
  between the burgeoning multi-chain ecosystem.
- The Internet Computer (previously DFINITY) has been cranking out [blog posts][dfb],
  both about technical matters and partnerships. They are running a developer
  grants program.
- Nervos has [launched their Force Bridge][fb] to connect to Ethereum, and is
  working to add [EVM compatibility][nevm].
- Polkadot has been running a high-profile [auction for parachain slots][ps] on
  its canary network, Kusama, and will soon begin auctions for the main Polkadot
  network. Some of the Kusama parachains, notably [Moonriver], are already up
  and running and attracting EVM-compatible dapps like Sushi.
- Solana has turned into a bit of a juggernaut, with huge financial backing, and
  TVL only behind Ethereum and Binance Smart Chain. Itt has been attracting
  dapps and protocols that were previously EVM-only, like [Lido] and [RenVM],
  and Solana is not an EVM chain. But it also has a strong stable of its own
  Solana-native dapps.

[nevm]: https://docs.nervos.org/docs/essays/polyjuice
[fb]: https://www.nervos.org/blog/force-bridge-mainnet/
[SecretSwap]: https://www.secretswap.io/
[sbr]: https://bridge.scrt.network/
[tvl]: https://coinmarketcap.com/alexandria/glossary/total-value-locked-tvl
[Lido]: https://lido.fi/
[RenVM]: https://renproject.io/
[Moonriver]: https://moonbeam.network/networks/moonriver/
[ps]: https://polkadot.network/blog/kusama-batch-2-auctions-report/
[dfb]: https://medium.com/dfinity-network-blog
[nf]: https://near.org/blog/near-announces-800-million-in-funding-initiatives-to-support-ecosystem-growth/

In RiB news, this month we've added a "Security Advisories" section, summarizing
all the Rust security advisories of the month from [RustSec], and [GitHub
Advisories]. Seeing them all in one place is revealing: lots of
security-relevant bugs in crates used in, or created by, the blockchain
industry.

This month, [upon prompting][zcp], we added a Zcash donation address, and
immediately received 3 donations. Thanks to the Zcash twitter community! RiB
donations are 100% earmarked for supporting developers through event
sponsorships, etc. The donation addresses can be found on the sidebar of
[the website][ribweb].

[zcp]: https://twitter.com/rust_blockchain/status/1448396267172900868
[ribweb]: https://rustinblockchain.org/

&nbsp;

## Thanks

Thanks to contributors:
[Adam Dossa],
[Awa Sun Yin],
[bbyleggo123],
[Dan Shields],
[KΞlchΞ⟠],
[Squirrel],
[Brian Anderson] and
[Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Adam Dossa]: https://github.com/adamdossa
[Awa Sun Yin]: https://github.com/awasunyin
[bbyleggo123]: https://github.com/bbyleggo123
[Dan Shields]: https://github.com/NukeManDan
[KΞlchΞ⟠]: https://github.com/kelcheone
[Squirrel]: https://github.com/gilescope
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[mina-rs].

[Mina] is a new blockchain protocol that uses zero-knowledge proofs to validate
the state of the chain without access to a full blockchain, but instead only a
tiny (~22k) proof. This should enable even mobile devices to participate in the
network as full validators, requiring less trust than today's situation where
most clients are connecting to other peoples' full nodes hosted in the cloud.
They are calling this style of chain a "succinct blockchain", and have caught
the attention of a number of other projects, forming partnerships to bring the
idea to other chains.

[mina-rs] is an implementation of Mina in Rust, developed by [ChainSafe]. It is
developed not only with mobile environments in mind, but WASM too, which
suggests we'll be able to embed a full node directly in the browser.

[mina-rs]: https://github.com/ChainSafe/mina-rs
[Mina]: https://minaprotocol.com/
[ChainSafe]: https://chainsafe.io/

Some recent blog posts about Mina / mina-rs:

- [Rising Tides: How the Mina Protocol can benefit Web 3.0](https://medium.com/chainsafe-systems/mina-wasm-benefits-for-web-3-0-3d25991c3b75)
- [22kB-Sized Blockchain &mdash; A Technical Reference](https://minaprotocol.com/blog/22kb-sized-blockchain-a-technical-reference)
- [Mina Product Priorities & Mina Foundation Mission](https://minaprotocol.com/blog/mina-protocol-product-priorities-mina-foundation-mission)

&nbsp;


## Interesting Things

#### Blog Posts

- [Rudra: Finding Memory Safety Bugs in Rust at the Ecosystem Scale](https://www.micahlerner.com/2021/10/31/rudra-finding-memory-safety-bugs-in-rust-at-the-ecosystem-scale.html)
- [Anatomy of a STARK](https://aszepieniec.github.io/stark-anatomy/)
- [FROST: Flexible Round-Optimized Schnorr Threshold Signatures](https://blog.coinbase.com/frost-flexible-round-optimized-schnorr-threshold-signatures-b2e950164ee1)
- [Sharding](https://adlrocha.substack.com/p/adlrocha-sharding)
- [Counter-Strike: Threshold Attack](https://medium.com/velasblockchain/counter-strike-threshold-attack-87f3b456b1e0)
- [A Guide to AppliedZKP zkEVM Circuit Code](https://medium.com/@sin7y/sin7y-tech-review-12-a-guide-to-appliedzkp-zkevm-circuit-code-3e0691056b48)

#### Papers

- [Plumo: An Ultralight Blockchain Client](https://eprint.iacr.org/2021/1361)
- [Encryption to the Future: A Paradigm for Sending Secret Messages to Future (Anonymous) Committees](https://eprint.iacr.org/2021/1423)
- [On the security of ECDSA with additive key derivation and presignatures](https://eprint.iacr.org/2021/1330)
- [How to Prove Schnorr Assuming Schnorr: Security of Multi- and Threshold Signatures](https://eprint.iacr.org/2021/1375)
- [Zero-knowledge Proofs in Embedded systems](https://eprint.iacr.org/2021/1382)

#### Projects

- [Shade Protocol](https://github.com/securesecrets/shade)
  is an array of connected privacy-preserving dApps built on Secret Network.

&nbsp;

## Security Advisories

Monthly security advisories, from [RustSec], and [GitHub Advisories].
Bold entries here are especially relevant to blockchain projects.

[RustSec]: https://rustsec.org/advisories/
[GitHub Advisories]: https://github.com/advisories?query=ecosystem%3Arust

- [RUSTSEC-2021-0120: Unsoundness in abomonation](https://rustsec.org/advisories/RUSTSEC-2021-0120.html).
  abomonation transmutes &T to and from &[u8] without sufficient constraints.
- **[RUSTSEC-2021-0121: Unsoundness in crypto2](https://rustsec.org/advisories/RUSTSEC-2021-0121.html).**
  Non-aligned u32 read in Chacha20 encryption and decryption.
- [CVE-2021-20319: coreos installer improperly verifies GPG signature when decompressing gzipped artifact](https://github.com/advisories/GHSA-3r3g-g73x-g593).
  coreos-installer fails to correctly verify GPG signatures when decompressing
  gzip-compressed artifacts. This allows bypass of signature verification in
  cases where coreos-installer decompresses a downloaded OS image, allowing an
  attacker who can modify the OS image to compromise a newly-installed system.
- **[CVE-2020-26281: Async-h1 request smuggling possible with long unread bodies](https://github.com/advisories/GHSA-4vr9-8cjf-vf9c).**
  This vulnerability affects any webserver that uses async-h1 behind a reverse proxy, including all such Tide applications.
- **[CVE-2021-41138: Validity check missing in Frontier](https://github.com/advisories/GHSA-vj62-g63v-f8mf).**
  In the newly introduced signed Frontier-specific extrinsic for
  pallet-ethereum, a large part of transaction validation logic was only called
  in transaction pool validation, but not in block execution. Malicious
  validators can take advantage of this to put invalid transactions into a
  block.
- [CVE-2021-41149: Improper sanitization of target names](https://github.com/advisories/GHSA-x3r5-q6mj-m485).
  The tough library, prior to 0.12.0, does not properly sanitize target names
  when caching a repository, or when saving specific targets to an output
  directory. When targets are cached or saved, files could be overwritten with
  arbitrary content anywhere on the system.
- [CVE-2021-41150: Improper sanitization of delegated role names](https://github.com/advisories/GHSA-r56q-vv3c-6g9c).
  The tough library, prior to 0.12.0, does not properly sanitize delegated role
  names when caching a repository, or when loading a repository from the
  filesystem. When the repository is cached or loaded, files ending with the
  .json extension could be overwritten with role metadata anywhere on the
  system.
- **[CVE-2021-41153: Specification non-compliance in JUMPI](https://github.com/advisories/GHSA-pvh2-pj76-4m96).**
  In evm crate < 0.31.0, JUMPI opcode's condition is checked after the
  destination validity check. However, according to Geth and OpenEthereum, the
  condition check should happen before the destination validity check.
- **[GHSA-v935-pqmr-g8v9: Unexpected panics in num-bigint](https://github.com/advisories/GHSA-v935-pqmr-g8v9).**
  Two scenarios were reported where BigInt and BigUint multiplication may unexpectedly panic.


&nbsp;



## Most Active in October

[Parity](https://github.com/paritytech):
291 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5]), 
105 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
112 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[Solana](https://github.com/solana-labs/solana):
275 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
42 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
68 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Diem](https://github.com/diem):
183 merged PRs ([1][diem-merged-prs-1]), 
14 closed issues ([1][diem-closed_issues-1]), 
24 open issues ([1][diem-open_issues-1])

&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

119 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4]), 
35 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4]), 
29 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/aleo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[aleo-merged-prs-4]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[aleo-closed_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[aleo-closed_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[aleo-open_issues-1]: https://github.com/AleoHQ/aleo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[aleo-open_issues-4]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31


#### [Anoma](https://github.com/anoma)

52 merged PRs ([1][anoma-merged-prs-1]), 
20 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2]), 
16 open issues ([1][anoma-open_issues-1])

[anoma-merged-prs-1]: https://github.com/anoma/anoma/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[anoma-closed_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[anoma-closed_issues-2]: https://github.com/anoma/ferveo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[anoma-open_issues-1]: https://github.com/anoma/anoma/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31


#### [ChainSafe](https://github.com/ChainSafe)

29 merged PRs ([1][chainsafe-merged-prs-1], [2][chainsafe-merged-prs-2]), 
25 closed issues ([1][chainsafe-closed_issues-1], [2][chainsafe-closed_issues-2]), 
15 open issues ([1][chainsafe-open_issues-1], [2][chainsafe-open_issues-2])

[chainsafe-merged-prs-1]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[chainsafe-merged-prs-2]: https://github.com/ChainSafe/filecoindot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[chainsafe-closed_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[chainsafe-closed_issues-2]: https://github.com/ChainSafe/filecoindot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[chainsafe-open_issues-1]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[chainsafe-open_issues-2]: https://github.com/ChainSafe/filecoindot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [Mina-rs Update: Some Rust serialization tricks with Serde](https://medium.com/chainsafe-systems/mina-rs-update-some-rust-serialization-tricks-with-serde-153518830f97)
- [ChainSafe launches Forest, the Rust Filecoin Client](https://medium.com/chainsafe-systems/chainsafe-launches-forest-the-rust-filecoin-client-d94534f86bbe)
- [Gossamer: Into the Polkadot-verse Pt. 3](https://medium.com/chainsafe-systems/gossamer-into-the-polkadot-verse-pt-3-6bd1447932aa)

#### [COMIT](https://github.com/comit-network)

21 merged PRs ([1][comit-merged-prs-1]), 
11 closed issues ([1][comit-closed_issues-1]), 
6 open issues ([1][comit-open_issues-1])

[comit-merged-prs-1]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[comit-open_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Concordium](https://github.com/Concordium)

21 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4]), 
4 closed issues ([1][concordium-closed_issues-1]), 
8 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[concordium-open_issues-1]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[concordium-open_issues-2]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[concordium-open_issues-3]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Conflux](https://github.com/Conflux-Chain)

2 merged PRs ([1][conflux-merged-prs-1]), 
2 closed issues ([1][conflux-closed_issues-1]), 
0 open issues

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31


#### [Dfinity](https://github.com/dfinity)

25 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]), 
4 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2]), 
8 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3], [4][dfinity-open_issues-4])

[dfinity-merged-prs-1]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[dfinity-merged-prs-2]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[dfinity-merged-prs-4]: https://github.com/dfinity/ic-types/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[dfinity-closed_issues-1]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[dfinity-closed_issues-2]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[dfinity-open_issues-1]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[dfinity-open_issues-2]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[dfinity-open_issues-3]: https://github.com/dfinity/quill/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[dfinity-open_issues-4]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [Optimizing the Internet Computer Memory System’s Performance](https://medium.com/dfinity/optimizing-the-internet-computer-memory-systems-performance-c0253e94f60)
- [Secure Scalability: The Internet Computer’s Peer-to-Peer Layer](https://medium.com/dfinity/secure-scalability-the-internet-computers-peer-to-peer-layer-6662d451f2cc)
- [Resumption: How Internet Computer Nodes Quickly Catch Up to the Blockchain’s Latest State](https://medium.com/dfinity/resumption-how-internet-computer-nodes-quickly-catch-up-to-the-blockchains-latest-state-5af6e53e2a7)

#### [Diem](https://github.com/diem)

183 merged PRs ([1][diem-merged-prs-1]), 
14 closed issues ([1][diem-closed_issues-1]), 
24 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Elrond](https://github.com/ElrondNetwork)

48 merged PRs ([1][elrond-merged-prs-1]), 
1 closed issues ([1][elrond-closed_issues-1]), 
3 open issues ([1][elrond-open_issues-1])

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[elrond-open_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Fluence](https://github.com/fluencelabs)

22 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]), 
8 closed issues ([1][fluence-closed_issues-1], [2][fluence-closed_issues-2], [3][fluence-closed_issues-3]), 
22 open issues ([1][fluence-open_issues-1], [2][fluence-open_issues-2], [3][fluence-open_issues-3])

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/marine-rs-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[fluence-closed_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[fluence-closed_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[fluence-closed_issues-3]: https://github.com/fluencelabs/marine-rs-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[fluence-open_issues-1]: https://github.com/fluencelabs/fluence/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[fluence-open_issues-2]: https://github.com/fluencelabs/aquavm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[fluence-open_issues-3]: https://github.com/fluencelabs/marine-rs-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Golem](https://github.com/golemfactory)

26 merged PRs ([1][golem-merged-prs-1]), 
20 closed issues ([1][golem-closed_issues-1]), 
13 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Holochain](https://github.com/holochain/)

77 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]), 
2 closed issues ([1][holochain-closed_issues-1]), 
4 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[holochain-merged-prs-3]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[holochain-closed_issues-1]: https://github.com/holochain/lair/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [IOTA](https://github.com/iotaledger)

17 merged PRs ([1][iota-merged-prs-1]), 
3 closed issues ([1][iota-closed_issues-1]), 
3 open issues ([1][iota-open_issues-1])

[iota-merged-prs-1]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[iota-closed_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[iota-open_issues-1]: https://github.com/iotaledger/iota.rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Lighthouse](https://github.com/sigp/lighthouse)

19 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]), 
21 closed issues ([1][lighthouse-closed_issues-1]), 
15 open issues ([1][lighthouse-open_issues-1])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [How-To: Update a Lighthouse Node](https://lighthouse.sigmaprime.io/How-To:%20Update%20a%20Lighthouse%20Node.html)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

38 merged PRs ([1][mobilecoin-merged-prs-1]), 
2 closed issues ([1][mobilecoin-closed_issues-1]), 
3 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [NEAR](https://github.com/nearprotocol/nearcore)

133 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3]), 
56 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
43 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[near-merged-prs-3]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[near-closed_issues-2]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[near-open_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[near-open_issues-3]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Nervos](https://github.com/nervosnetwork)

77 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4]), 
4 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3]), 
3 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[nervos-merged-prs-4]: https://github.com/nervosnetwork/ckb-std/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[nervos-closed_issues-3]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/force-bridge-eth/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [Force Bridge Now Live on Mainnet](https://www.nervos.org/blog/force-bridge-mainnet/)

#### [Parity](https://github.com/paritytech)

291 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5]), 
105 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
112 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[parity-merged-prs-4]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[parity-closed_issues-3]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[parity-open_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[parity-open_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [Polkadot Is Ready for Parachain Launch, Auction Dates Proposed](https://medium.com/polkadot-network/polkadot-is-ready-for-parachain-launch-auction-dates-proposed-112e9721e5e6)
- [Polkadot Hackathons Are Going Global, Starting in Asia Pacific](https://medium.com/polkadot-network/polkadot-hackathons-go-global-starting-in-apac-oct-22-cde53ad9113b)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

27 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3]), 
6 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2]), 
17 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Rust Ethereum](https://github.com/rust-ethereum)

2 merged PRs ([1][rust_ethereum-merged-prs-1]), 
0 closed issues, 
1 open issues ([1][rust_ethereum-open_issues-1])

[rust_ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[rust_ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

4 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]), 
0 closed issues, 
2 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [Secret Feature: Shade Protocol & Silk](https://scrt.network/blog/shade-protocol-silk-privacy-preserving-stablecoin)
- [Altermail is LIVE on Mainnet!](https://scrt.network/blog/altermail-live-on-mainnet)
- [Secret Feature: SiennaSwap Launches on Mainnet!](https://scrt.network/blog/secret-feature-sienna-siennaswap-live)

#### [Solana](https://github.com/solana-labs/solana)

275 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 
42 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
68 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [Reflections on Solana's Sept 14 outage](https://jumpcrypto.com/reflections-on-the-sept-14-solana-outage/)

#### [Spacemesh](https://github.com/spacemeshos)

7 merged PRs ([1][spacemesh-merged-prs-1]), 
23 closed issues ([1][spacemesh-closed_issues-1], [2][spacemesh-closed_issues-2]), 
29 open issues ([1][spacemesh-open_issues-1], [2][spacemesh-open_issues-2])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[spacemesh-closed_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[spacemesh-open_issues-2]: https://github.com/spacemeshos/svm/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

#### [TezEdge](https://github.com/tezedge)

18 merged PRs ([1][tezedge-merged-prs-1]), 
2 closed issues ([1][tezedge-closed_issues-1]), 
0 open issues

[tezedge-merged-prs-1]: https://github.com/tezedge/tezedge/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[tezedge-closed_issues-1]: https://github.com/tezedge/tezedge/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31

#### [Zcash](https://github.com/zcash)

108 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 
65 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
30 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-10-01..2021-10-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [Public Report – Zcash NU5 Cryptography Review](https://research.nccgroup.com/2021/11/02/public-report-zcash-nu5-cryptography-review/)
- [Zebra 1.0.0-beta.0 release](https://mailchi.mp/zfnd.org/zebra-beta-release-is-here).

#### [zkSync](https://github.com/matter-labs/zksync)

0 merged PRs, 
1 closed issues ([1][zksync-closed_issues-1]), 
4 open issues ([1][zksync-open_issues-1])

[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-10-01..2021-10-31
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2021-10-01..2021-10-31

- [UniSync: a port of Uniswap V2 on the zkEVM](https://medium.com/matter-labs/unisync-a-port-of-uniswap-v2-on-the-zkevm-b12954748504)

&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

Nov 11 - Dec 8 | Online

[Cosmos HackAtom VI ](https://hackatom.org/)

Nov 15-19 | Online

[ACM CCS 2021](https://www.sigsac.org/ccs/CCS2021/)

Nov 18-19 | Online

[Tokenomics 2021: 3rd International Conference on Blockchain Economics, Security and Protocols](https://sites.google.com/nyu.edu/tokenomics2021)

Dec 1-3 | Seoul, Korea

[ICISC: The 24th Annual International Conference on information Security and Cryptology](http://www.icisc.org/)

Dec 14-15 | Online

[18th IMA International Conference on Cryptography and Coding](https://ima.org.uk/16366/online-event-18th-ima-international-conference-on-cryptography-and-coding/)

Jan 24-26, 2022 | Arrillaga Alumni Center, Stanford University

[SBC'22: The Science of Blockchain Conference 2022](https://cbr.stanford.edu/sbc22/)

Feb 14-18, 2022 | Canada

[Financial Cryptography and Data Security 2022](http://fc22.ifca.ai/index.html)

&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->

Anoma | Berlin, Remote
- [Senior Rust Engineer](https://heliax.dev/jobs/senior-rust-engineer/)
- [Rust P2P Networking Engineer](https://heliax.dev/jobs/rust-p2p-networking-engineer)
- [Technical Engineering Manager](https://heliax.dev/jobs/technical-engineering-manager/)
- [Zero-Knowledge Cryptographer & Protocol Developer](https://heliax.dev/jobs/zero-knowledge-cryptographer-protocol-developer/)
- [Distributed Systems Research Engineer](https://heliax.dev/jobs/distributed-systems-research-engineer/)

Aurora | Remote
- [Blockchain/Bridge Engineer](https://docs.google.com/document/d/1xXMEeQffOv2rfPT4jpipwkjo4osmfyAp4eEl51j3dt4/edit?usp=sharing)

NEAR | Remote
- [Low-Level Developer, Contract Runtime](https://docs.google.com/document/d/18HEwef-HDPZ2FPYfaHWpsd-kSF8E4zNpeQVulqhfFSk/edit?usp=sharing)


More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#30 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


