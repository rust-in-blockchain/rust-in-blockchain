**Rust in Blockchain #3 - Aug 2019**
**#3 - Aug 2019**

Welcome to the fourth edition of Rust in Blockchain, the hypest newsletter about the hypest combination of technologies.

If you want to speak on one of our forthcoming meetups, please apply [here](https://docs.google.com/forms/d/e/1FAIpQLSdqDDPv6WylWCel8j5oorm3U5M1wtQJ7gYLsw_Ng6IcDcDSBg/viewform).


**Project updates**

#### [**Grin**](https://github.com/mimblewimble/grin)

[Improve checking for p2p connection limits #2985](https://github.com/mimblewimble/grin/pull/2985)

[Grin Newsletter](https://grinnews.substack.com/)

#### [**Near**](https://github.com/nearprotocol/nearcore)

[Fix runtime tests broken by fees. Fixes #1185 #1187](https://github.com/nearprotocol/nearcore/pull/1187): [@nearmax](https://github.com/nearmax) explains that runtime tests are too wide and assert irrelevant numbers, like they assert that the hash of the account did not change and the exact balance of the account. The unit tests are integration tests which they might should have fewer integration tests because of the maintenance cost. Instead, unit tests should be verifying one or a few specific numbers.

[Storage usage #1202](https://github.com/nearprotocol/nearcore/pull/1202): [@mikhailOK](https://github.com/mikhailOK) starts a discussion about storage usage in Near.

#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)

[Refactor: apply new serialization to all crates #1249](https://github.com/nervosnetwork/ckb/pull/1249): [@yangby-cryptape](https://github.com/yangby-cryptape) applies new serialization to all crates. The new serialization format will be used in p2p messages, database storage and hash digest. After the change, it is possible to compute transaction hash and block hash in other programming languages. We’ll publish the serialization wire format specification soon.

[Feat: difficulty adjustment rfc version #1307](https://github.com/nervosnetwork/ckb/pull/1307): [@zhangsoledad](https://github.com/zhangsoledad) updates the difficulty adjustment algorithm according to the consensus paper.

[Nervos Development Updates](https://medium.com/nervosnetwork/tagged/development-updates)

#### [**Parity** ](https://github.com/paritytech)

[**Substrate**](https://github.com/paritytech/substrate)

[Make it easier to just rebuild the WASM files #3510](https://github.com/paritytech/substrate/pull/3510): [@bkchr](https://github.com/bkchr) adds a new env variable WASM_TARGET_DIRECTORY that controls the target directory for copying the built WASM binary; adds script build-only-wasm.sh to only build the WASM binary; and further improvements to wasm-builder to reduce the number of required rebuilds.

[Implement HTTP request in offchain workers #3447](https://github.com/paritytech/substrate/pull/3447) Just give it a read.

[Refactor key management #3296](https://github.com/paritytech/substrate/pull/3296) This PR is turning into a major refactoring over the crypto and key management system.

#### [**Solana**](https://github.com/solana-labs/solana)

[Rust BPF: Panic investigation #5520](https://github.com/solana-labs/solana/issues/5520): [@jstarry](https://github.com/jstarry) found issues show that the original VM didn't expect large programs and so jump calculations were done with i16 types.

[Add datacenter node setup scripts #5517](https://github.com/solana-labs/solana/pull/5517): [@TristanDebrunner](https://github.com/TristanDebrunner) adds bash scripts that do all the setup, and the helper scripts that do parts of the setup if something breaks.


**Challenges**

[Does anybody want to build dev tutorials together?](https://github.com/rust-in-blockchain/Community-Project/issues/1#issuecomment-526813060) If there are anyone who would be willing to produce small bite-size education chunks occasionally?


**Learning**

[The Rise of Rust and Blockchain](https://domsteil.com/2019/08/08/rust-and-blockchain/)

[Rust Blockchain Tutorial: What is Rust and Why is it Important?](https://freestartupkits.com/articles/technology/cryptocurrency-news-and-tips/ultimate-rust-blockchain-tutorial/)

[Build A Decentralized Chat Using JavaScript & Rust (WebAssembly)](https://medium.com/perlin-network/build-a-decentralized-chat-using-javascript-rust-webassembly-c775f8484b52)

[Coding a P2P blockchain in Rust: Part 1](https://medium.com/@prabhueshwarla/coding-a-p2p-blockchain-in-rust-part-1-2ecc8f6005ea)

[Substrate Blockchains and Runtime Modules: An Introduction](https://medium.com/better-programming/substrate-blockchains-and-runtime-modules-an-introduction-866851b550b9)

[Libra and Exonum: A Comparison of Rust-Based Blockchain Solutions](https://medium.com/meetbitfury/libra-and-exonum-a-comparison-of-rust-based-blockchain-solutions-6963a7f4a81d)

[Exploring an essential data structure in CKB— the transaction](https://medium.com/nervosnetwork/exploring-an-essential-data-structure-in-ckb-the-transaction-a1ca8fcbfbda)


**Events**

September 6-8 | Boston, US

[EthBoston](https://eth.boston/)

September 11-12 | Tel Aviv, Israel

[Scaling Bitcoin Workshops](https://scalingbitcoin.org/)

September 14-15 | Riga, Latvia

[Baltic Honeybadger 2019](https://bh2019.hodlhodl.com/)

September 14-15 | Shanghai, China

[Wanxiang Blockchain Hackathon 2019](http://www.blockchainlabs.org/week2019/hackathon_en.html)

September 20-21 | Colorado, US

[Colorado Gold Rust](https://www.cogoldrust.com/)

October 8-11 | Osaka, Japan

[DevCon](https://devcon.org/)

October 19-20 | Berlin, Germany

[Lighting Conference](https://www.thelightningconference.com/)

October 19-20 | Berlin, Germany

[Diffusion 2019: Blockchain Hackathon](https://diffusion.events/)

October 26 | Tokyo, Japn

[Rust Tokyo](https://rust.tokyo/)

October 28 - November 3 | San Francisco & Berkeley, US

[SF Blockchain Week 2019](https://sfblockchainweek.io/)

**Careers**

TTi Global

[Senior Software Developer (OpenGL / WebGL)](https://webassemblyjobs.com/jobs/senior-software-developer-opengl-webgl)

Calliere Group

[Blockchain Developer](https://www.glassdoor.ca/job-listing/blockchain-developer-calliere-group-JV_IC2281069_KO0,20_KE21,35.htm?jl=2850712010)

RBC

[Blockchain Application Developer](https://www.glassdoor.ca/job-listing/blockchain-application-developer-rbc-JV_IC2281069_KO0,32_KE33,36.htm?jl=3317514966)

Consensys

[Systems Engineer (Rust)](https://consensys.net/open-roles/1792013/)

Parity

[Rust Core Developer](https://www.parity.io/jobs/#berlin-rust-core-developer)

[Runtime Engineer](https://www.parity.io/jobs/#berlin-blockchain-runtime-engineer)

Polymath Network

[Rust/Blockchain Developer](https://angel.co/company/polymath-network/jobs/584822-rust-blockchain-developer)

Gnosis

[Rust Developer (m/w/d)](https://stackoverflow.com/jobs/282822/rust-developer-m-w-d-gnosis-service-gmbh)

Transparent Systems

[Sr. Software Engineer - Rust, blockchain](https://jobs.lever.co/transparentsystems/dbb1afb4-0686-47bd-946a-e8bd70c755fa)


**Interesting Things**

[A thread on thinking about using RISC-V to replace WebAssembly for the execution engine.](
https://twitter.com/sorpaas/status/1153410902500270084)


**Join the action on our** [**subreddit**](https://www.reddit.com/r/RustInBlockchain/) **❤️**
