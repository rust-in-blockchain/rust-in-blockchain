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
The structure here should also be reflected
in [template.md].

[config]: https://github.com/rust-in-blockchain/ribbot/blob/master/src/rib-config.toml
[template.md]: template.md


## Non-Bitcoin / Non-Ethereum

### Aleo

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
### Anoma

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

### ChainSafe

Media:

- https://medium.com/chainsafe-systems

GitHub:

- https://github.com/ChainSafe

```toml
repos = [
"ChainSafe/mina-rs",
"ChainSafe/api3-rust",
"ChainSafe/forest",
"ChainSafe/filecoindot",
]
```

### COMIT

Media:

- https://comit.network/blog
- https://twitter.com/comit_network

GitHub:

- https://github.com/comit-network

``` toml
repos = [
"comit-network/maia",
"comit-network/rendezvous-server",
"comit-network/xmr-btc-swap",
"comit-network/xtra-productivity",
"comit-network/waves",
]

```

### Concordium

Media:

- https://twitter.com/concordiumnet
- https://medium.com/concordium
- https://www.reddit.com/r/Concordium_Official/

GitHub:

- https://github.com/Concordium

``` toml
repos = [
"Concordium/concordium-rust-smart-contracts",
"Concordium/concordium-wasm-smart-contracts",
"Concordium/concordium-contracts-common",
"Concordium/concordium-rust-sdk",
"Concordium/concordium-base",
"Concordium/concordium-transaction-logger",
"Concordium/concordium-euro2ccd-service",
"Concordium/concordium-use-case-examples",
"Concordium/concordium-node",
]
```

### Conflux Network

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

### DarkFi

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

### Dfinity

Media:

- https://medium.com/dfinity

GitHub:

- https://github.com/dfinity

```toml
repos = [
"dfinity/ic",
"dfinity/sdk",
"dfinity/agent-rs",
"dfinity/icx-proxy",
"dfinity/cdk-rs",
"dfinity/candid",
"dfinity/quill",
"dfinity/experimental-minting-tool",
"dfinity/vessel",
"dfinity/bitcoin-developer-preview",
"dfinity/ic-types",
]
```

### Elrond

Media:

- https://elrond.com/
- https://elrond.com/blog/

GitHub:

- https://github.com/ElrondNetwork

```toml
repos = [
"ElrondNetwork/elrond-wasm-rs",
"ElrondNetwork/sc-dex-rs",
"ElrondNetwork/sc-nft-marketplace",
"ElrondNetwork/sc-metabonding-rs",
"ElrondNetwork/sc-bridge-elrond",
"ElrondNetwork/sc-chainlink-rs",
"ElrondNetwork/sc-delegation-rs",
"ElrondNetwork/sc-savings-account-rs",
]

```

### Espresso

Media:
- https://www.espressosys.com/
- https://www.espressosys.com/blog
- https://twitter.com/EspressoSys

github:

- https://github.com/EspressoSystems

```toml
repos = [
"EspressoSystems/jellyfish",
"EspressoSystems/cape",
"EspressoSystems/reef",
"EspressoSystems/seahorse",
"EspressoSystems/cap",
]

```

### Findora

Media:

- https://findora.org
- https://twitter.com/findoraofficial

GitHub:

- https://github.com/FindoraNetwork

```toml
repos = [
"FindoraNetwork/zei",
"FindoraNetwork/platform",
"FindoraNetwork/findora-scanner",
"FindoraNetwork/bp",
"FindoraNetwork/findora-exporter",
"FindoraNetwork/abcf",
"FindoraNetwork/bs3",
"FindoraNetwork/storage",
]
```

### Fluence

Media:

- https://fluence.network
- https://twitter.com/fluence_project

GitHub:

- https://github.com/fluencelabs

```toml
repos = [
"fluencelabs/marine",
"fluencelabs/aquavm",
"fluencelabs/fluence",
"fluencelabs/examples",
"fluencelabs/registry",
"fluencelabs/trust-graph",
"fluencelabs/aqua-ipfs",
]
```

### Fuel

Media:

- https://fuel.network
- https://twitter.com/fuellabs_

GitHub

- https://github.com/FuelLabs

```toml
repos = [
"FuelLabs/fuel-asm",
"FuelLabs/fuel-bft",
"FuelLabs/fuel-core",
"FuelLabs/fuel-crypto",
"FuelLabs/fuel-merkle",
"FuelLabs/fuel-storage",
"FuelLabs/fuel-tx",
"FuelLabs/fuel-types",
"FuelLabs/fuel-vm",
"FuelLabs/fuels-rs",
"FuelLabs/sway",
]
```

### Golem

Media:

- https://blog.golemproject.net/
- https://twitter.com/golemproject
- https://chat.golem.network/

GitHub:

- https://github.com/golemfactory


``` toml
repos = [
"golemfactory/ya-runtime-http-auth",
"golemfactory/yagna",
"golemfactory/ya-service-bus",
"golemfactory/ya-client",
"golemfactory/ya-relay",
"golemfactory/ya-runtime-sdk",
"golemfactory/ya-runtime-vm",
"golemfactory/ya-vm-file-server",
]
```

### Grin

Media:

- https://grinnews.substack.com

GitHub:

- https://github.com/mimblewimble

``` toml
repos = [
"mimblewimble/grin",
"mimblewimble/grin-wallet",
]
```

### Helium

Media:

- https://www.helium.com/
- https://blog.helium.com/
- https://twitter.com/helium

GitHub:

- https://github.com/helium

```toml
repos = [
"helium/gateway-rs",
"helium/semtech-udp",
"helium/helium-crypto-rs",
"helium/ecc608-linux-rs",
"helium/virtual-lorawan-device",
"helium/helium-wallet-rs",
"helium/helium-api-rs",
]
```

### Holochain

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
"holochain/holochain",
"holochain/absquic",
"holochain/launcher",
"holochain/holochain-client-rust",
"holochain/holochain-wasmer",
"holochain/hc-utils",
]
```

### Iota

GitHub:

- https://github.com/iotaledger

``` toml
repos = [
"iotaledger/bee",
"iotaledger/wallet.rs",
"iotaledger/iota.rs",
"iotaledger/identity.rs",
"iotaledger/cli-wallet",
"iotaledger/streams",
"iotaledger/stronghold.rs",
"iotaledger/chronicle.rs",
]
```

### Maidsafe

Media:

- https://maidsafe.net/
- https://safenetwork.tech/
- https://medium.com/safenetwork
- https://twitter.com/maidsafe
- https://twitter.com/safenetworktech

GitHub:

- https://github.com/maidsafe

```toml
repos = [
"maidsafe/sn_dbc",
"maidsafe/safe_network",
"maidsafe/qp2p",
"maidsafe/blsttc",
"maidsafe/sn_dbc_examples",
"maidsafe/sn_consensus",
"maidsafe/bls_dkg",
"maidsafe/self_encryption",
]
```

### MobileCoin

Media:

- https://www.mobilecoin.com/

GitHub:

- https://github.com/mobilecoinfoundation

``` toml
repos	= [
"mobilecoinfoundation/mobilecoin",
"mobilecoinfoundation/mc-oblivious",
"mobilecoinfoundation/fog",
]

```

### Near

Media:

- https://nearprotocol.com/blog/
- https://twitter.com/nearprotocol
- https://nearprotocol.com/community/

GitHub:

- https://github.com/near

``` toml
repos = [
"near/workspaces-rs",
"near/nearcore",
"near/near-cli-rs",
"near/near-sdk-rs",
"near/near-jsonrpc-client-rs",
"near/near-lake",
"near/near-blake2",
"near/core-contracts",
"near/near-lake-framework",
"near/borsh-rs",
"near/near-indexer-for-explorer",
"near/wasmer",
]
```

### Nervos

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
"nervosnetwork/axon",
"nervosnetwork/godwoken",
"nervosnetwork/ckb",
"nervosnetwork/godwoken-scripts",
"nervosnetwork/mercury",
"nervosnetwork/ckb-vm",
"nervosnetwork/godwoken-tests",
"nervosnetwork/ckb-cli",
"nervosnetwork/molecule",
"nervosnetwork/capsule",
"nervosnetwork/ckb-indexer",
"nervosnetwork/overlord",
]
```
### Oasis

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
"oasisprotocol/oasis-sdk",
"oasisprotocol/cipher-paratime",
"oasisprotocol/emerald-paratime",
]
```

### Parity

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
"paritytech/cumulus",
"paritytech/parity-signer",
"paritytech/smoldot",
"paritytech/ink",
"paritytech/parity-common",
"paritytech/subxt",
"paritytech/jsonrpsee",
"paritytech/frontier",
"paritytech/cargo-contract",
"paritytech/substrate-contracts-node",
"paritytech/ink-playground",
"paritytech/metadata-portal",
"paritytech/parity-bridges-common",
]
```

### Secret Network

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
"scrtlabs/snip20-reference-impl",
]
```

### Solana

Media:

- https://medium.com/solana-labs
- https://twitter.com/solana
- https://www.reddit.com/r/solana

GitHub:

- https://github.com/solana-labs

``` toml
repos = [
"solana-labs/solana",
"solana-labs/solana-program-library",
"solana-labs/solana-accountsdb-plugin-postgres",
]
```

### Spacemesh

GitHub:

- https://github.com/spacemeshos

``` toml
repos = [
"spacemeshos/svm",
]
```

### Subspace Labs

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
]
```

### TezEdge

GitHub:

- https://github.com/tezedge

``` toml
repos = [
"tezedge/tezedge",
"tezedge/tezedge-snapshots",
"tezedge/tezedge-tui",
]
```

### Zcash

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
"zcash/incrementalmerkletree",
"zcash/librustzcash",
"zcash/orchard",
"zcash/pasta_curves",
"zcash/halo2_gadgets",
]
```


---

## Rust in Bitcoin

### BDK

Media:

- https://bitcoindevkit.org

GitHub:

- https://github.com/bitcoindevkit

```toml
repos = [
"bitcoindevkit/bdk",
"bitcoindevkit/bdk-cli",
"bitcoindevkit/bdk-ffi",
"bitcoindevkit/rust-hwi",
"bitcoindevkit/rust-electrum-client",
]
```

### Bitmask

Media:

- https://bitmask.app

GitHub:

- https://github.com/diba-io/bitmask-core

```toml
repos = [
"diba-io/bitmask-core",
]
```

### Electrs

GitHub:

- https://github.com/romanz/electrs

```toml
repos = [
"romanz/electrs",
]
```

### Internet2

GitHub:

- https://github.com/Internet2-WG

```toml
repos = [
"Internet2-WG/rust-aluvm",
"Internet2-WG/rust-internet2",
"Internet2-WG/rust-microservices",
"Internet2-WG/stenc",
]
```

### LDK

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

### LNP/BP

Media:

- https://www.lnp-bp.org
- https://twitter.com/lnp_bp

GitHub:

- https://github.com/LNP-BP

```toml
repos = [
"LNP-BP/client_side_validation",
"LNP-BP/rust-lnpbp",
"LNP-BP/invoices",
"rust-amplify/rust-amplify",
"BP-WG/bp-node",
"BP-WG/bp-core",
"BP-WG/descriptor-wallet",
"BP-WG/rust-psbt",
]
```

### LNP WG

GitHub:

- https://github.com/LNP-WG


```toml
repos = [
"LNP-WG/lnp-core",
"LNP-WG/lnp-node",
"LNP-WG/lightning_encoding",
"LNP-WG/ln-types",
]
```

### MyCitadel

Media:

- https://mycitadel.io/
- https://twitter.com/mycitadel_io

GitHub:

- https://github.com/mycitadel

```toml
repos = [
"mycitadel/citadel-runtime",
"mycitadel/libcitadel",
"mycitadel/mycitadel-desktop",
"mycitadel/mycitadel-node",
]
```

### Nakamoto

GitHub:

- https://github.com/cloudhead/nakamoto

```toml
repos = [
"cloudhead/nakamoto",
]
```

### Nomic

GitHub:

- https://github.com/nomic-io

```toml
repos = [
"nomic-io/nomic",
"nomic-io/merk",
"nomic-io/orga",
"nomic-io/abci2",
"nomic-io/ed",
]
```

### RGB

Media:

- https://www.rgbfaq.com
- https://rgbex.io

GitHub:

- https://github.com/RGB-WG

```toml
repos = [
"RGB-WG/rgb-core",
"RGB-WG/rgb-node",
"RGB-WG/rust-rgb20",
]
```

### Rust Bitcoin

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

### Rust Simplicity

GitHub:

- https://github.com/ElementsProject/rust-simplicity

```toml
repos = [
"ElementsProject/rust-simplicity",
]
```

### Sapio

Media:

- https://learn.sapio-lang.org/

GitHub:

- https://github.com/sapio-lang

```toml
repos = [
"sapio-lang/sapio",
]
```

### Talaia

Media:

- https://talaia.watch

GitHub:

- https://github.com/talaia-labs

```toml
repos = [
"talaia-labs/rust-teos",
]
```


---

## Rust in Ethereum

### Ethers-rs

GitHub:

- https://github.com/gakonst/ethers-rs

```toml
repos = [
"gakonst/ethers-rs",
]
```

### Lighthouse

Media:

- https://lighthouse.sigmaprime.io/

GitHub:

- https://github.com/sigp/lighthouse

``` toml
repos = [
"sigp/lighthouse",
"sigp/discv5",
]
```

### Rust Ethereum

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

### Rust Web3

GitHub:

- https://github.com/tomusdrw/rust-web3

```toml
repos = [
"tomusdrw/rust-web3",
]
```

### zkSync

Media:

- https://medium.com/matter-labs
- https://twitter.com/zksync

GitHub:

- https://github.com/matter-labs/zksync

``` toml
repos = [
"matter-labs/zksync",
"matter-labs/compiler-solidity",
]
```

