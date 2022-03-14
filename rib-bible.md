# The Rust in Blockchain Bible

This document simply lists the places to look for content for editions of RIB.

Guidelines when looking for content:

- Topics on official blogs and tweets are probably important
- Look for interesting tags on PRs and issues
- Look for PRs and issues with many comments
- Sorting by most comments can help find important PRs

Note:
for the purposes of generating GitHub metrics,
repo information also must be duplicated
in [ribbot/src/rib-config.toml][config].

[config]: https://github.com/rust-in-blockchain/ribbot/blob/master/src/rib-config.toml

## Aleo

Media:

- https://www.aleo.org
- https://www.aleo.org/blog
- https://twitter.com/AleoHQ

GitHub:

- https://github.com/AleoHQ

```toml
repos = [
"AleoHQ/aleo",
"AleoHQ/snarkOS",
"AleoHQ/snarkVM",
"AleoHQ/leo",
]
```
## Anoma

Media:

- https://anoma.network
- https://twitter.com/anomanetwork


GitHub:

- https://github.com/anoma

```toml
repos = [
"anoma/anoma",
"anoma/ferveo",
"anoma/masp",
"anoma/plonkup-hash",
]
```

## ChainSafe

Media:

- https://medium.com/chainsafe-systems

GitHub:

- https://github.com/ChainSafe

```toml
repos = [
"ChainSafe/forest",
"ChainSafe/filecoindot",
]
```


## COMIT

Media:

- https://comit.network/blog
- https://twitter.com/comit_network

GitHub:

- https://github.com/comit-network

``` toml
repos = [
"comit-network/comit-rs",
"comit-network/xmr-btc-swap",
"comit-network/create-comit-app",
"comit-network/blockchain-contracts",
]

```

## Concordium

Media:

- https://twitter.com/concordiumnet
- https://medium.com/concordium
- https://www.reddit.com/r/Concordium_Official/

GitHub:

- https://github.com/Concordium

``` toml
repos = [
"Concordium/concordium-node",
"Concordium/concordium-base",
"Concordium/concordium-contracts-common",
"Concordium/concordium-rust-smart-contracts",
]
```

## Conflux Network

Media:

- https://twitter.com/Conflux_Network
- https://medium.com/conflux-network

GitHub:

- https://github.com/Conflux-Chain

``` toml
repos = [
"Conflux-Chain/conflux-rust",
]
```

## Crypto.com Chain

Media:

- https://blog.crypto.com

GitHub:

- https://github.com/crypto-com

``` toml
repos = [
"crypto-com/thaler",
"crypto-com/chain-nodelib",
"crypto-com/thaler-sample-wallet",
"crypto-com/sample-thaler-java-example",
"crypto-com/sample-thaler-ios-example",
]
```

## DarkFi

Media:

- https://dark.fi/
- https://twitter.com/DarkFiSquad/

GitHub:

- https://github.com/darkrenaissance/darkfi

```toml
repos = [
"darkrenaissance/darkfi",
]
```

## Dfinity

Media:

- https://medium.com/dfinity

GitHub:

- https://github.com/dfinity

```toml
repos = [
"dfinity/agent-rs",
"dfinity/candid",
"dfinity/cdk-rs",
"dfinity/ic",
"dfinity/ic-types",
"dfinity/quill",
"dfinity/vessel",
]
```

## Diem

Media:

- https://www.diem.com/

GitHub:

- https://github.com/diem

``` toml
repos = [
"diem/diem",
"diem/rosetta-proxy",
"diem/bcs",
]
```

## Elrond

Media:

- https://elrond.com/
- https://elrond.com/blog/

GitHub:

- https://github.com/ElrondNetwork

```toml
repos = [
"ElrondNetwork/sc-delegation-rs",
"ElrondNetwork/sc-band-bridge-rs",
"ElrondNetwork/mandos-rs",
"ElrondNetwork/elrond-wasm-rs",
"ElrondNetwork/sc-dns-rs",
]

```
## Findora

Media:

- https://findora.org
- https://twitter.com/findoraofficial

GitHub:

- https://github.com/FindoraNetwork

```toml
repos = [
"FindoraNetwork/platform",
"FindoraNetwork/zei",
"FindoraNetwork/merk",
"FindoraNetwork/storage",
]
```

## Fluence

Media:

- https://fluence.network
- https://twitter.com/fluence_project

GitHub:

- https://github.com/fluencelabs

```toml
repos = [
"fluencelabs/fluence",
"fluencelabs/marine",
"fluencelabs/aquavm",
"fluencelabs/marine-rs-sdk",
]
```

## Fuel

Media:

- https://fuel.network
- https://twitter.com/fuellabs_

GitHub

- https://github.com/FuelLabs

```toml
repos = [
"FuelLabs/fuel-asm",
"FuelLabs/fuel-core",
"FuelLabs/fuel-merkle",
"FuelLabs/fuel-storage",
"FuelLabs/fuel-tx",
"FuelLabs/fuel-types",
"FuelLabs/fuel-vm",
"FuelLabs/fuels-rs",
"FuelLabs/sway",
]
```

## Golem

Media:

- https://blog.golemproject.net/
- https://twitter.com/golemproject
- https://chat.golem.network/

GitHub:

- https://github.com/golemfactory


``` toml
repos = [
"golemfactory/yagna",
"golemfactory/ya-client",
]
```

## Grin

Media:

- https://grinnews.substack.com

GitHub:

- https://github.com/mimblewimble

``` toml
repos = [
"mimblewimble/grin",
]
```

## Holochain

Media:

- https://medium.com/holochain
- https://twitter.com/holochain
- https://www.reddit.com/r/holochain/
- https://forum.holochain.org/
- https://blog.holochain.org/
- https://medium.com/h-o-l-o

GitHub:

- https://github.com/holochain

``` toml
repos = [
"holochain/holochain-rust",
"holochain/holochain",
"holochain/elemental-chat",
"holochain/holochain-wasmer",
"holochain/lair",
]
```

## Interledger

Media:

- https://twitter.com/interledger
- https://lists.w3.org/Archives/Public/public-interledger/

GitHub:

- https://github.com/interledger-rs

``` toml
repos = [
"interledger-rs/interledger-rs",
]
```

## Iota

GitHub:

- https://github.com/iotaledger

``` toml
repos = [
"iotaledger/iota.rs",
]
```

## Lighthouse

Media:

- https://lighthouse.sigmaprime.io/

GitHub:

- https://github.com/sigp/lighthouse

``` toml
repos = [
"sigp/lighthouse",
"sigp/beacon-fuzz",
"sigp/discv5",
]
```

## MobileCoin

Media:

- https://www.mobilecoin.com/

GitHub:

- https://github.com/mobilecoinfoundation

``` toml
repos	= [
"mobilecoinfoundation/fog",
"mobilecoinfoundation/mobilecoin",
]

```

## Near

Media:

- https://nearprotocol.com/blog/
- https://twitter.com/nearprotocol
- https://nearprotocol.com/community/

GitHub:

- https://github.com/nearprotocol

``` toml
repos = [
"near/nearcore",
"near/borsh",
"near/core-contracts",
"near/near-evm",
]
```

## Nervos

Media:

- https://medium.com/nervosnetwork
- https://medium.com/nervosnetwork/tagged/development-updates
- https://twitter.com/nervosnetwork
- https://talk.nervos.org
- https://www.reddit.com/r/NervosNetwork/

GitHub:

- https://github.com/nervosnetwork

``` toml
repos = [
"nervosnetwork/ckb",
"nervosnetwork/ckb-vm",
"nervosnetwork/ckb-cli",
"nervosnetwork/capsule",
"nervosnetwork/ckb-std",
"nervosnetwork/force-bridge-eth",
]
```
## Oasis

Media:

- https://medium.com/oasislabs
- https://medium.com/oasis-protocol-project
- https://www.twitter.com/OasisLabs
- https://www.reddit.com/r/OasisLabs

GitHub:

- https://github.com/oasislabs
- https://github.com/oasisprotocol

``` toml
repos = [
"oasislabs/oasis-ethwasi-runtime",
"oasislabs/oasis-rs",
"oasislabs/oasis-cli",
"oasislabs/oasis-chain",
"oasisprotocol/deoxysii-rust",
]
```

## Parity

Media:

- https://www.parity.io/blog/
- https://polkadot.network/blog/
- https://twitter.com/ParityTech

GitHub:

- https://github.com/paritytech

``` toml
repos = [
"paritytech/substrate",
"paritytech/polkadot",
"paritytech/cargo-contract",
"paritytech/wasmi",
"paritytech/parity-bitcoin",
"paritytech/cumulus",
"paritytech/ink",
]
```

## Rust Bitcoin

GitHub:

- https://github.com/rust-bitcoin

```toml
repos = [
"rust-bitcoin/rust-bitcoin",
"rust-bitcoin/rust-secp256k1",
"rust-bitcoin/rust-miniscript",
"rust-bitcoin/rust-wallet",
"rust-bitcoin/rust-bitcoincore-rpc",
"rust-bitcoin/rust-bech32-bitcoin",
"rust-bitcoin/murmel",
"rust-bitcoin/rust-bip39",
"rust-bitcoin/bitcoin_hashes",
"jean-airoldie/zeromq-src-rs",
]
```

## BDK

Media:

- https://bitcoindevkit.org

GitHub:

- https://github.com/bitcoindevkit

```toml
repos = [
"bitcoindevkit/bdk",
"bitcoindevkit/bdk-cli",
"bitcoindevkit/bdk-ffi",
"bitcoindevkit/bdk-hwi",
"rust-electrum-client",
]
```

## LDK

Media:

- https://lightningdevkit.org

GitHub:

- https://github.com/lightningdevkit

```toml
repos = [
"lightningdevkit/rust-lightning",
"lightningdevkit/ldk-sample",
"lightningdevkit/ldk-c-bindings",
]
```

## Sapio

Media:

- https://learn.sapio-lang.org/

GitHub:

- https://github.com/sapio-lang

```toml
repos = [
"sapio-lang/sapio",
]
```

## LNP

Media:

- https://www.lnp-bp.org

GitHub:

- https://github.com/LNP-BP

```toml
repos = [
"LNP-BP/lnp-core",
"LNP-BP/lnp-node",
"LNP-BP/bp-node",
"LNP-BP/bp-core",
"LNP-BP/client_side_validation",
"LNP-BP/descriptor-wallet",
"LNP-BP/rust-amplify",
"LNP-BP/ln-types",
"LNP-BP/invoices",
"LNP-BP/rust-psbt",
"LNP-BP/lnp-sdk",
"LNP-BP/lbx",
]
```

## RGB

Media:

- https://www.rgbfaq.com
- https://rgbex.io

GitHub:

- https://github.com/rgb-org

```toml
repos = [
"rgb-org/rgb-core",
"rgb-org/rgb-node",
"rgb-org/rust-rgb20",
]
```

## Internet2

GitHub:

- https://github.com/internet2-org/

```toml
repos = [
"internet2-org/rust-aluvm",
"internet2-org/rust-internet2",
"internet2-org/rust-microservices",
"internet2-org/stenc",
]
```

## Electrs

GitHub:

- https://github.com/romanz/electrs

```toml
repos = [
"romanz/electrs",
]
```

## Simplicity

GitHub:

- https://github.com/ElementsProject/rust-simplicity

```toml
repos = [
"ElementsProject/rust-simplicity",
]
```

## Nakamoto

GitHub:

- https://github.com/cloudhead/nakamoto

```toml
repos = [
"cloudhead/nakamoto",
]
```

## Bitmask

Media:

- https://bitmask.app

GitHub:

- https://github.com/diba-io/bitmask-core

```toml
repos = [
"diba-io/bitmask-core",
]
```

## Nomic

GitHub:

- https://github.com/diba-io/bitmask-core

```toml
repos = [
"nomic-io/nomic",
"nomic-io/merk",
"nomic-io/orga",
"nomic-io/abci2",
"nomic-io/ed",
]
```

## Talaia

Media:

- https://talaia.watch

GitHub:

- https://github.com/talaia-labs

```toml
repos = [
"talaia-labs/rust-teos",
]
```

## Rust Ethereum

GitHub:

- https://github.com/rust-ethereum

```toml
repos = [
"rust-ethereum/ethabi",
"rust-ethereum/enr",
"rust-ethereum/devp2p",
"rust-ethereum/dnsdisc",
]
```

## Ethers-rs

GitHub:

- https://github.com/gakonst/ethers-rs

```toml
repos = [
"gakonst/ethers-rs",
]
```

## Rust Web3

GitHub:

- https://github.com/tomusdrw/rust-web3

```toml
repos = [
"tomusdrw/rust-web3",
]
```

## Secret Network

Media:

- https://blog.scrt.network
- https://twitter.com/SecretNetwork
- https://forum.scrt.network

GitHub:

- https://github.com/scrtlabs

``` toml
repos = [
"scrtlabs/SecretNetwork",
"scrtlabs/secret-toolkit",
"scrtlabs/SafeTrace",
]
```

## Solana

Media:

- https://medium.com/solana-labs
- https://twitter.com/solana
- https://www.reddit.com/r/solana

GitHub:

- https://github.com/solana-labs

``` toml
repos = [
"solana-labs/solana",
"solana-labs/rbpf",
"solana-labs/solana-program-library"
]
```

## Spacemesh

GitHub:

- https://github.com/spacemeshos

``` toml
repos = [
"spacemeshos/go-spacemesh",
"spacemeshos/svm",
]
```

## Subspace Labs

Media:

- https://subspace.network
- https://medium.com/subspace-network
- https://twitter.com/NetworkSubspace
- https://discord.com/invite/K56A6xrdw9
- https://t.me/subspace_network
- https://reddit.com/r/sub
- https://www.youtube.com/channel/UCojYRCZOtVTJHJXivOYJzeQ

GitHub:

- https://github.com/subspace

``` toml
repos = [
"subspace/subspace",
"subspace/subspace-desktop",
"subspace/sloth256-189",
]
```

## TezEdge

GitHub:

- https://github.com/tezedge

``` toml
repos = [
"tezedge/tezedge",
]
```

## Zcash

Media:

- https://z.cash/buzz/
- https://electriccoin.co/blog/
- https://www.zfnd.org/blog/
- https://www.zcashcommunity.com/
- https://forum.zcashcommunity.com/
- https://buttondown.email/zcashfoundation
- https://reddit.com/r/zec

GitHub:

- https://github.com/ZcashFoundation
- https://github.com/zcash

``` toml
repos = [
"ZcashFoundation/zebra",
"zcash/halo2",
"zcash/librustzcash",
]
```

## zkSync

Media:

- https://medium.com/matter-labs
- https://twitter.com/zksync

GitHub:

- https://github.com/matter-labs/zksync

``` toml
repos = [
"matter-labs/zksync",
]
```
