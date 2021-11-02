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
"rust-bitcoin/rust-lightning",
"rust-bitcoin/rust-miniscript",
"rust-bitcoin/rust-bitcoincore-rpc",
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
