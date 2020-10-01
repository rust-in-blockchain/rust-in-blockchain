# RiB Newsletter #16

Publish on 30th September, 2020

Welcome to the #16 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. 
[Previous: #15](/newsletters/2020-09-02-turbofish-in-the-blocksea/).

For the last few months we've been following new zero-knowledge proof projects in Rust.
This month, with [Secret Network upgrading their mainnet with secret contracts][smain],
it seems like a good opportunity to explore Rust blockchains that are using
a completely different privacy-preserving technology: secure enclaves.

[smain]: https://blog.scrt.network/upgrade-complete-secret-contracts-live-mainnet/

Secure enclaves are processes whose environment is protected from inspection by other processes,
even the kernel,
by special hardware.
This protection particularly involves the encryption of a process's memory.
Software that wants to compute in secret can put those computations inside a secure enclave and,
if everything works as expected,
not even the hosting provider can snoop on the computations being performed,
nor the secrets used in those computations.
The most notable implementation of secure enclaves is Intel's [SGX] (Secure Guard Extensions).

[SGX]: https://en.wikipedia.org/wiki/Software_Guard_Extensions

Secure enclaves are an attractive way to perform private computation
primarily because they don't impose any limitations on what can be computed &mdash;
code that runs inside SGX is more-or-less just regular x86 code,
just running inside a special environment.
But depending on SGX for privacy does have some important risks:
software that runs in an SGX enclave must be signed by Intel's own cryptographic keys,
which means that Intel must approve of any software running in SGX,
that Intel can _revoke_ permission to use SGX,
and that there is risk of the signing keys being compromised;
and it's not obvious that secure enclaves are actually secure,
there having already been a number of timing attacks against SGX.
If SGX is compromised at any point in the future,
it could compromise any software that depends on it,
so it's important for software relying on SGX to be designed to minimize the impact of an attack on SGX.

There are two prominent Rust blockchains relying on SGX:

- **[Secret Network][sn]** is a programmable blockchain based on Cosmos / Tendermint
that runs smart contracts written in Rust,
and compiled to WASM,
inside of secure enclaves.

- **[MobileCoin][mc]** is a private currency that uses SGX to add additional
confidentiality on top of RingCT transactions and its variant of the Stellar
Consensus Protocol.

[sn]: https://github.com/enigmampc/
[mc]: https://github.com/mobilecoinofficial

Outside of the blockchain world there are some other Rust projects
using SGX, the most notable being:

- **[Teaclave SGX SDK][tea]** is an SDK for running Rust code inside SGX enclaves,
developed at Baidu, and now an Apache project.
MobileCoin uses a heavily modified fork.

- **[Fortanix][ftx]** is a provider of various Rust+SGX services,
and they provide an SGX SDK,
for which mainline Rust has some built-in support.

**[Rust OP-TEE TrustZone SDK][tz]** is an SDK for ARM TrustZone.

[tea]: https://github.com/apache/incubator-teaclave-sgx-sdk
[ftx]: https://github.com/fortanix/rust-sgx
[tz]: https://github.com/sccommunity/rust-optee-trustzone-sdk

Whether it's secure enclaves or zk-SNARKs,
Rust blockchains are walking the bleeding edge of privacy technology.

In unrelated RiB news, we recently received two donations,
- 666 CKB in August:
>https://explorer.nervos.org/transaction/0x4eb46117c218482b84ce19c52ef02f642524b14ef4f39b9ad8c64bb75a8475ca
- 500,000 CKB in September:
>https://explorer.nervos.org/transaction/0xdd9d3d0afaf07a3d91ff101475b3dffec0961e742c8cfdd617da3e7e9cef0c33

Thanks so much to our anonymous donors.
We don't often receive donations,
so this was a nice suprise!
We intend to put all monetary contributions to use funding events or new contributors,
and we'll let you know what we do with the funds when we spend them.


&nbsp;

## Thanks

Contributors.

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue. 
Either submit a PR to the [#17 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft), 
or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

&nbsp;

## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### News


#### Blog Posts


#### Papers 

#### Projects

- [Acala](https://github.com/AcalaNetwork/Acala).  CrossChain StableCoin platform based on Substrate. 
- [Anon](https://github.com/hicommonwealth/anon).
Substrate modules for anonymous group actions (ring signatures + merkle proofs).
- [Bitcoins-rs](https://github.com/summa-tx/bitcoins-rs). Bitcoin-oriented dev toolboxes for native and browser apps.
- [Cardano-serialization-lib](https://github.com/Emurgo/cardano-serialization-lib). A library for serialization & deserialization of data structures used in Cardano's Haskell implementation of Shelley along with useful utility functions.
- [Crust](https://github.com/crustio/crust).
Implementation of a Crust protocol node with Substrate.
- [Curv](https://github.com/ZenGo-X/curv) has built-in support for some useful operations/primitives such as verifiable secret sharing, commitment schemes, zero-knowledge proofs, and simple two-party protocols such as ECDH and coin flip.
- [Edgeware](https://github.com/hicommonwealth/edgeware-node).
Substrate node implementing Edgeware. It's an
On-chain Governed, Proof-of-Stake (PoS) Blockchain with a WASM Runtime
- [Fawkes-Crypto](https://github.com/zeropoolnetwork/fawkes-crypto)  is a lightweight framework for building circuits in bellman, using groth16 proving system and BN254 curve.
- [Hacspec](https://github.com/hacspec/hacspec). A specification language for cryptography primitives.
- [Magical Bitcoin Library](https://github.com/bitcoindevkit/bdk/tree/0.1.0-beta.1).
A modern, lightweight, descriptor-based wallet library written in Rust.
- [Phala](https://github.com/Phala-Network/phala-blockchain).
Phala Network is a TEE-Blockchain hybrid architecture implementing Confidential Contract. 
- [TezEdge](https://github.com/simplestaking/tezedge).
Tezos node/shell in Rust.

#### Podcasts and Videos


&nbsp;

## Most Active in September


&nbsp;

## Project Updates


#### [Aleo](https://github.com/AleoHQ)

#### [Conflux](https://github.com/Conflux-Chain)

- News:
  - [Scaling Applications with Conflux Network](https://medium.com/conflux-network/scaling-applications-with-conflux-network-1fc0022a4c94)
  - [Conflux Network Partners With BCW To Design Next-Generation Payment Solutions](https://medium.com/conflux-network/conflux-network-partners-with-bcw-to-design-next-generation-payment-solutions-974997416bc6)
  - [MoonSwap:High speed,0 GAS AMM DEX with Ethereum and Conflux](https://medium.com/@MoonSwap/high-speed-0-gas-amm-with-ethereum-and-conflux-9422443f94ca)
  - [Unleashing Data Accessibility on Conflux Network](https://medium.com/conflux-network/unleashing-data-accessibility-on-conflux-network-c733e12b5728)
  - [Conflux Economic Model — Staking & Collateral For Storage On Conflux Network](https://medium.com/conflux-network/conflux-economic-model-staking-collateral-for-storage-on-conflux-network-cb4c8c150e3)
  - Bi-Weekly Progress Report:
    - [August 31— September 13, 2020](https://medium.com/conflux-network/bi-weekly-progress-report-august-31-september-13-2020-82ac16cc6808)
    - [August 17— August 30](https://medium.com/conflux-network/bi-weekly-progress-report-august-17-august-30-2020-c1b3cc3d7541)

#### [COMIT](https://github.com/comit-network)

#### [Crypto.com Chain](https://chain.crypto.com)

#### [Elrond](https://github.com/ElrondNetwork)

#### [Holochain](https://github.com/holochain/)

- News:
  - Holochain Dev Pulse
    - [80: A Fresh New Holochain](https://medium.com/holochain/a-fresh-new-holochain-902181bfa25b)
    - [79: How To Break a Holo App](https://medium.com/holochain/how-to-break-a-holo-app-9e23a97f7e2c)
    - [Special Announcement: New Holochain RSM Released to Public](https://medium.com/holochain/new-holochain-rsm-released-to-public-78f1c08474bf)
  - [A Big Leap Forward for Holochain & Holo](https://medium.com/h-o-l-o/a-big-leap-forward-for-holochain-holo-2efaaa54ed08)
  - [Dima Barbarchuk: Using Human-centric Design to Build Resilient & Self-developing Economies of the Future](https://medium.com/holochain/dima-barbarchuk-using-human-centric-design-to-build-resilient-self-developing-economies-of-the-ba422427e4a9)

#### [Libra](https://libra.org)

- News: Testnet push announcement for [09/30](https://community.libra.org/t/testnet-push-announcement-for-09-30/3151),
  [09/23](https://community.libra.org/t/testnet-push-annoucement-for-09-23/3136),
  [09/16](https://community.libra.org/t/testnet-push-annoucnement-for-09-16/3135)

#### [Lighthouse](https://lighthouse.sigmaprime.io/)

- News: [Lighthouse Update #29](https://lighthouse.sigmaprime.io/update-29.html)

#### [MobileCoin](https://www.mobilecoin.com/)

#### [NEAR](https://github.com/nearprotocol/nearcore)

- News:
  - [Community Update: All our Node are Belong to You](https://near.org/blog/all-our-node-are-belong-to-you/). There are a bouch of learning resources.
  - [NEAR MainNet is now Community-Operated](https://near.org/blog/near-mainnet-is-now-community-operated/)
  - [The First NEAR Community Town Hall(Monday September 28th)](https://near.org/blog/the-first-near-community-town-hall-monday-september-28th/)
  - [Community Update: MainNet Phase I 🚀 , Hack the Rainbow 🌈 , OWC Demo Day](https://near.org/blog/community-update-mainnet-phase-i-%f0%9f%9a%80-hack-the-rainbow-%f0%9f%8c%88-owc-demo-day/)
  - [Transitioning NEAR MainNet to the Next Phase: It is Time to Stake, Delegate and Vote](https://near.org/blog/mainnet-phase-i/)
- Blog:
  - [Getting Started With the NEAR Wallet](https://near.org/blog/getting-started-with-the-near-wallet/)
- Discussion: [Voting criteria for the transition to Phase II](https://github.com/nearprotocol/NEPs/issues/115)

#### [Nervos](https://github.com/nervosnetwork)

- News:
  - [Coinone Exchange Lists Nervos CKB for Trading in South Korea](https://medium.com/nervosnetwork/coinone-exchange-lists-nervos-ckb-for-trading-in-south-korea-dd514a8f0b2d)
  - [Nervos integrates with Linear Finance to propel DeFi development](https://medium.com/nervosnetwork/nervos-integrates-with-linear-finance-to-propel-defi-development-96b4c98805e)
  - [Nervos unveils Q4 plans in first Town Hall](https://medium.com/@nervosnetwork/nervos-unveils-q4-plans-in-first-town-hall-c45eff5fe078)
  - [Nervos to present roadmap and answer questions at Town Hall](https://medium.com/nervosnetwork/nervos-to-present-roadmap-and-answer-questions-at-town-hall-fd466bba3638)
  - [NervosHack wrap-up](https://medium.com/nervosnetwork/nervoshack-wrap-up-4370044f9866)
  - [Memecraft — Announcing the Nervos x Hxro Meme Competiton](https://medium.com/nervosnetwork/memecraft-announcing-the-nervos-x-hxro-meme-competiton-f67493426c46)
  - [Nervos attends Grin meetup and shares Mimblewimble update](https://medium.com/nervosnetwork/nervos-attends-grin-meetup-and-shares-mimblewimble-update-5f38f9f2fcb8)
  - [Grin Community Collaboration to Bring Mimblewimble to Nervos](https://medium.com/nervosnetwork/grin-community-collaboration-to-bring-mimblewimble-to-nervos-4a663df26f60)
  - [Hxro Brings Its Gamified Crypto Trading Platform to Nervos](https://medium.com/nervosnetwork/hxro-brings-its-gamified-crypto-trading-platform-to-nervos-fe264c4f5d28)
  - [6MM+ KuCoin users can begin trading $CKB September 4th](https://medium.com/nervosnetwork/6mm-kucoin-users-can-begin-trading-ckb-september-4th-60990d1214e)
  - [Nervos CKB Development Update #40](https://medium.com/nervosnetwork/nervos-ckb-development-update-40-589aeaef7cd8)
  - [Nervos Community Update: August 2020](https://medium.com/nervosnetwork/nervos-community-update-august-2020-addf1caf9b1e)
  - CKB Weekly
  [20](https://ckbweekly.substack.com/p/cross-chain-innovation-and-defi),
  [19](https://ckbweekly.substack.com/p/defi-interoperability-and-beyond),
  [18](https://ckbweekly.substack.com/p/nfts-on-ckb),
  [17](https://ckbweekly.substack.com/p/muta)
- Blog:
  - [Explained: Layer 2 DEX Designs on Nervos CKB](https://medium.com/nervosnetwork/layer-2-dex-designs-on-nervos-ckb-63e11282aaa0)
  

#### [Parity](https://github.com/paritytech)

- News:
  - [Substrate 2.0 is here](https://www.parity.io/substrate-2-0-is-here/)
  - Tech Preview: Rust IPFS + Substrate [1](https://medium.com/equilibriumco/tech-preview-rust-ipfs-and-substrate-64d277582f3c),
  [2](https://medium.com/equilibriumco/tech-preview-2-rust-ipfs-substrate-848b8a1afb26)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

- News:
  - [Secret Raffle: Enter to Win Secrets by Using Keplr Wallet!](https://blog.scrt.network/secret-raffle-win-secrets-keplr-wallet/)
  - [SCRT 2020: Our Secret Vision for Universal Finance](https://blog.scrt.network/secret-2020-defi/)
  - [Secret Committees: Empowering Secret Agents](https://blog.scrt.network/secret-committees-empowering-secret-agents/)
  - [Upgrade Complete: Secret Contracts are LIVE on Mainnet!](https://blog.scrt.network/upgrade-complete-secret-contracts-live-mainnet/)
  - [Secret Network Ecosystem Update: August 2020](https://blog.scrt.network/ecosystem-update-august-2020/)
- Blog:
  - [Staking Secrets: A Living Guide to Staking and Delegating SCRT](https://blog.scrt.network/staking-secrets-guide-to-staking-delegating-scrt/)
  - [SecretWasm: Decentralized, Private Computation for Secret Apps](https://blog.scrt.network/secretwasm-decentralized-private-computation/)
  - [Secret Vaults: Programmable Access Control](https://blog.scrt.network/secret-vaults-programmable-access-control/)
  - [How To Build Secret Apps: An Evolving Development Guide](https://blog.scrt.network/how-to-build-secret-apps/)

#### [Solana](https://github.com/solana-labs/solana)

- News:
  - [OKEx Lists SOL](https://medium.com/solana-labs/okex-lists-sol-fb777e7d1d15)
  - [Binance.US Announces Support for SOL, making it the Second US Exchange within one day](https://medium.com/@SolanaLabs/binance-us-announces-support-for-sol-making-it-the-second-us-exchange-within-one-day-6c32a90869da)
  - [Tether to bring USDt to the Solana Network](https://medium.com/solana-labs/tether-to-bring-usdt-to-the-solana-network-77864184b20)
  - [FTX US Makes SOL Trading Available To United States Residents](https://medium.com/solana-labs/ftx-us-makes-sol-trading-available-to-united-states-residents-35696445295e)


#### [Zcash](https://z.cash/)

- News:
  - [Gemini becomes first regulated institution to support shielded Zcash withdrawals](https://electriccoin.co/blog/gemini-becomes-first-regulated-institution-to-support-shielded-zcash-withdrawals/)
  - [ECC welcomes the Major Grants Review Committee](https://electriccoin.co/blog/ecc-welcomes-the-major-grants-review-committee/)
  - [Refining and recommitting to the ECC mission](https://electriccoin.co/blog/refining-and-recommitting-to-the-ecc-mission/)
  - [FATF’s plans to regulate peer-to-peer transactions](https://electriccoin.co/blog/fatfs-plans-to-regulate-peer-to-peer-transactions/)
  - [Canopy security assessment complete](https://electriccoin.co/blog/canopy-security-assessment-complete/)
  - [Introducing TGPPL, a radically new type of open-source license](https://electriccoin.co/blog/introducing-tgppl-a-radically-new-type-of-open-source-license/)



&nbsp;

## Events


Oct 1-30 | Online

[ETHOnline 2020](https://www.ethonline.org/). Summits + Hackathon.

Oct 16–30 | Online

[Cosmos Hackathon: HackAtom V](https://hackatomv.devpost.com/)

Oct 21-23 | NYC, US

[ACM Advances in Financial Technologies](https://aft.acm.org/)

Oct 27-28 | Dubai

[Future Blockchain Summit](https://www.futureblockchainsummit.com/)

&nbsp;

## Careers

Aleo | San Francisco, US; Remote
- [Full-Stack Developer](https://aleo.org/jobs/full-stack-developer)
- [Backend Developer](https://aleo.org/jobs/backend-developer)
- [Senior Front-End Developer](https://aleo.org/jobs/senior-front-end-developer)

Chainlink | Remote
- [Blockchain Tools Engineer - Entry Level](https://careers.smartcontract.com/o/blockchain-tools-engineer-entry-level)

Compound | Remote
- [Rust Engineer](https://www.crypto-careers.com/jobs/39500671-rust-engineer-at-compound)

Dock | Remote
- [Rust & DevOps](https://www.cryptojobsdaily.com/job/dock-blockchain-developer-rust-devops/)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#17 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft),
or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**


