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
"AleoHQ/leo",
"AleoHQ/snarkOS",
"AleoHQ/snarkVM",
"AleoHQ/aleo-rust",
"AleoHQ/aleo-std",
"AleoHQ/sdk",
"AleoHQ/aleo-setup-integration-test",
"howardwu/wagyu",
"howardwu/wagyu-zcash-parameters",
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
"anoma/namada",
"anoma/namada-sdk-starter",
"anoma/taiga",
"anoma/zkp-compiler-shootout",
"anoma/masp",
"anoma/vamp-ir",
"anoma/namada-masp-verification",
"anoma/namada-masp-params",
"anoma/anoma",
"anoma/ethereum-bridge-e2e-tests",
"anoma/ferveo",
"anoma/anoma-wasm-multitoken",
"anoma/using-namada-sdk-poc",
"anoma/building-namada-sdk-to-wasm",
"anoma/using-namada-sdk-poc-2",
"anoma/masp-mpc",
"anoma/verify-beacon",
]
```

### Aptos

Media:
- https://aptoslabs.com/
- https://twitter.com/aptoslabs
- https://aptoslabs.medium.com/

GitHub:
- https://github.com/aptos-labs

```toml
repos = [
"aptos-labs/aptos-core",
"aptos-labs/aptos-indexer-processors",
"aptos-labs/move",
"aptos-labs/bcs",
]
```

### Casper

Media:
- https://casper.network
- https://twitter.com/Casper_Network

GitHub:
- https://github.com/casper-network

```toml
repos = [
"casper-network/casper-node",
"casper-network/casper-node-launcher",
"casper-network/casper-db-utils",
]
```

### Chainflip

GitHub:
- https://github.com/chainflip-io

```toml
repos = [
"chainflip-io/chainflip-backend",
"chainflip-io/rust-zmq",
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
"comit-network/xmr-btc-swap",
"comit-network/rendezvous-server",
"comit-network/maia",
"comit-network/malax",
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
"Concordium/concordium-base",
"Concordium/concordium-misc-tools",
"Concordium/concordium-rust-sdk",
"Concordium/concordium-smart-contract-tools",
"Concordium/concordium-rosetta",
"Concordium/concordium-transaction-logger",
"Concordium/concordium-euro2ccd-service",
"Concordium/voting-workshop",
"Concordium/concordium-use-case-examples",
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
"Conflux-Chain/cfx-evm",
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
"dfinity/nns-dapp",
"dfinity/canister-profiling",
"dfinity/sdk",
"dfinity/ic",
"dfinity/agent-rs",
"dfinity/ICRC-1",
"dfinity/internet-identity",
"dfinity/stable-structures",
"dfinity/ic-websocket-poc",
"dfinity/bitcoin-canister",
"dfinity/experimental-minting-tool",
"dfinity/cdk-rs",
"dfinity/response-verification",
"dfinity/idl2json",
"dfinity/dfx-extensions",
"dfinity/ic-repl",
"dfinity/ic-wasm",
"dfinity/candid",
"dfinity/erc20-icp",
"dfinity/cns",
"dfinity/motoko.rs",
"dfinity/vessel",
"dfinity/exchange-rate-canister",
"dfinity/test-state-machine-client",
"dfinity/bitcoin-developer-preview",
"dfinity/icx-nns",
"dfinity/quill",
"dfinity/ic-quickjs-demo",
"dfinity/verify-bls-signatures",
"dfinity/ic-docutrack",
"dfinity/metrics-encoder",
"dfinity/miracl_core_bls12381",
"dfinity/ic-mo-vm",
]
```

### Dusk Network

Media:
- https://dusk.network/
- https://twitter.com/duskfoundation
- https://dusk.network/pages/all-posts
- https://www.reddit.com/r/DuskNetwork/

GitHub:
- https://github.com/dusk-network

```toml
repos = [
"dusk-network/rusk",
"dusk-network/wallet-cli",
"dusk-network/piecrust",
"dusk-network/wallet-core",
"dusk-network/kadcast",
"dusk-network/plonk",
"dusk-network/merkle",
"dusk-network/phoenix-core",
"dusk-network/Poseidon252",
"dusk-network/schnorr",
"dusk-network/dusk-pki",
"dusk-network/Hades252",
"dusk-network/phoenix",
"dusk-network/bls12_381-sign",
"dusk-network/microkelvin",
"dusk-network/nstack",
"dusk-network/rusk-vm",
"dusk-network/ranno",
]
```

### Espresso

Media:
- https://www.espressosys.com/
- https://www.espressosys.com/blog
- https://twitter.com/EspressoSys

GitHub:
- https://github.com/EspressoSystems

```toml
repos = [
"EspressoSystems/reef",
"EspressoSystems/HotShot",
"EspressoSystems/seahorse",
"EspressoSystems/espresso-sequencer",
"EspressoSystems/hyperplonk",
"EspressoSystems/commit",
"EspressoSystems/hotshot-query-service",
"EspressoSystems/espresso-polygon-zkevm-demo",
"EspressoSystems/cape",
"EspressoSystems/discord-faucet",
"EspressoSystems/espresso",
"EspressoSystems/jellyfish",
"EspressoSystems/async-compatibility-layer",
"EspressoSystems/espresso-macros",
"EspressoSystems/tide-disco",
"EspressoSystems/surf-disco",
"EspressoSystems/net",
"EspressoSystems/tagged-base64",
"EspressoSystems/espresso-systems-common",
"EspressoSystems/arbitrary-wrappers",
"EspressoSystems/cap",
"EspressoSystems/atomicstore",
"EspressoSystems/key-set",
"EspressoSystems/veri-zexe",
]
```

### Filecoin

Media:
- https://filecoin.io/

GitHub:
- https://github.com/filecoin-project

```toml
repos = [
"filecoin-project/builtin-actors",
"filecoin-project/ref-fvm",
"filecoin-project/filecoin-ffi",
"filecoin-project/rust-fil-proofs",
"filecoin-project/rust-filecoin-proofs-api",
"filecoin-project/rust-sha2ni",
"filecoin-project/blstrs",
"filecoin-project/bls-signatures",
"filecoin-project/builtin-actors-bundler",
"filecoin-project/rust-gpu-tools",
"filecoin-project/ec-gpu",
"filecoin-project/fil-sppark",
"filecoin-project/fvm-bench",
"filecoin-project/rust-fil-logger",
"filecoin-project/taupipp",
"filecoin-project/filecoin-phase2",
"ChainSafe/forest",
"ChainSafe/filecoindot",
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
"FindoraNetwork/rt-evm",
"FindoraNetwork/platform-lib-noah",
"FindoraNetwork/platform-lib-utils",
"FindoraNetwork/zkcard-mini-sdk",
"FindoraNetwork/platform-lib-sparse-merkle",
"FindoraNetwork/enterprise-web3",
"FindoraNetwork/noah",
"FindoraNetwork/eth-utils",
"FindoraNetwork/generate_secp256k1_priv_validator_key",
"FindoraNetwork/findorad-past",
"FindoraNetwork/platform-lib-credentials",
"FindoraNetwork/platform-lib-merkle",
"FindoraNetwork/platform-lib-bitmap",
"FindoraNetwork/ark-ed-on-bn254-mixed-radix",
"FindoraNetwork/ark-bn254-mixed-radix",
"FindoraNetwork/export-setup-parameters",
"FindoraNetwork/storage",
"FindoraNetwork/findora-poker",
"FindoraNetwork/web3-rpc-core",
"FindoraNetwork/ark-bulletproofs",
"FindoraNetwork/bulletproofs",
"FindoraNetwork/platform-lib-slidingset",
"FindoraNetwork/platform-lib-cryptohash",
"FindoraNetwork/zei",
"FindoraNetwork/findora-exporter",
"FindoraNetwork/tendermint-abci",
"FindoraNetwork/tendermint-rs",
"FindoraNetwork/fmerk",
"FindoraNetwork/prikey2keystore",
"FindoraNetwork/eip1962",
"FindoraNetwork/platform",
"FindoraNetwork/nft-issue-transaction",
"FindoraNetwork/findora-scanner",
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
"fluencelabs/nox",
"fluencelabs/spell",
"fluencelabs/decider",
"fluencelabs/registry",
"fluencelabs/aquavm",
"fluencelabs/marine-rs-sdk",
"fluencelabs/examples",
"fluencelabs/aqua-ipfs",
"fluencelabs/trust-graph",
"fluencelabs/fRPC-Substrate",
"fluencelabs/marine-rs-sdk-test",
"fluencelabs/marine",
"fluencelabs/benchmark-service",
"fluencelabs/release-flow-demo",
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
"FuelLabs/faucet",
"FuelLabs/forc-wallet",
"FuelLabs/fuel-bft",
"FuelLabs/fuel-core",
"FuelLabs/fuel-debugger",
"FuelLabs/fuel-indexer",
"FuelLabs/fuel-vm",
"FuelLabs/fuels-rs",
"FuelLabs/fuelup",
"FuelLabs/sway",
"FuelLabs/sway-standards",
"FuelLabs/sway-libs",
"FuelLabs/releasy",
"FuelLabs/sway-applications",
"FuelLabs/fuel-block-committer",
"FuelLabs/fuel-abi-types",
"FuelLabs/sway-by-example-lib",
"FuelLabs/fuel-canary-watchtower",
"FuelLabs/bridge-message-executor",
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
"golemfactory/erc20_payment_lib",
"golemfactory/ansible-role-ya-requestor",
"golemfactory/ya-runtime-wasi",
"golemfactory/gvmkit-build-rs",
"golemfactory/devops-ya-relay-e2e-test",
"golemfactory/ya-self-test-img",
"golemfactory/golem-certificate",
"golemfactory/ya-packet-trace",
"golemfactory/ya-vpn-connector",
"golemfactory/ya-runtime-outbound",
"golemfactory/ya-runtime-outbound-gateway",
"golemfactory/g-flite",
"golemfactory/gwasm-runner",
"golemfactory/ProofOfDevice",
"golemfactory/gudot",
"golemfactory/munin-plugin-pgp-expiration",
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
"mimblewimble/mwixnet",
"mimblewimble/grin-gui",
"mimblewimble/grin-miner",
"mimblewimble/rust-secp256k1-zkp",
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
"helium/oracles",
"helium/xorf-generator",
"helium/gateway-rs",
"helium/helium-crypto-rs",
"helium/helium-wallet-rs",
"helium/account-compression-anchor-gen",
"helium/helium-data",
"helium/ecc608-linux-rs",
"helium/etl-extract",
"helium/helium-config-service-cli",
"helium/virtual-lorawan-device",
"helium/gateway-mfr-rs",
"helium/gwmp-mux",
"helium/semtech-udp",
"helium/helium-packet-router-ingest",
"helium/gateway-security-rs",
"helium/lorawan-h3",
"helium/cortex-mpu",
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
"holochain/holochain-client-rust",
"holochain/holochain-wasmer",
"holochain/hackathon-happs",
"holochain/scaffolding",
"holochain/app-store-dnas",
"holochain/tx5",
"holochain/hc-test-utils",
"holochain/hc-zome-lib",
"holochain/hc-utils",
"holochain/deepkey",
"holochain/nix-cache-check",
"holochain/devhub-dnas",
"holochain/lair",
"holochain/holochain-serialization",
"holochain/influxive",
"holochain/portal-dna",
"holochain/spike-influx",
"holochain/ametrics",
"holochain/hc-tel",
"holochain/ghost_actor",
"holochain/sodoken",
"holochain/task-motel-rs",
"holochain/integrity-template",
"holochain/absquic",
"holochain/launcher",
]
```

### Iota

GitHub:
- https://github.com/iotaledger

``` toml
repos = [
"iotaledger/iota-sdk",
"iotaledger/inx-chronicle",
"iotaledger/identity.rs",
"iotaledger/common-rs",
"iotaledger/ledger.rs",
"iotaledger/wallet.rs",
"iotaledger/iota.rs",
"iotaledger/stronghold.rs",
"iotaledger/crypto.rs",
"iotaledger/streams",
"iotaledger/chronicle.rs",
"iotaledger/bee",
"iotaledger/cli-wallet",
]
```

### Lurk

Media:
- https://lurk-lang.org
- https://blog.lurk-lang.org/posts
- https://twitter.com/LurkLab
- https://zulip.lurk-lab.com

GitHub:
- https://github.com/lurk-lab

```toml
repos = [
"lurk-lab/lurk-rs",
"lurk-lab/arecibo",
"lurk-lab/neptune",
"lurk-lab/bellpepper",
"lurk-lab/bellpepper-gadgets",
"lurk-lab/grumpkin-msm",
"lurk-lab/solidity-verifier",
"lurk-lab/circom-scotia",
"lurk-lab/abomonation_derive",
"lurk-lab/elsa",
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
"maidsafe/safe_network",
"maidsafe/sn-testnet-deploy",
"maidsafe/sn_dbc",
"maidsafe/self_encryption",
"maidsafe/safeup",
"maidsafe/sn_nodejs",
"maidsafe/sn_authd",
"maidsafe/temp_safe_network",
"maidsafe/sn_consensus",
"maidsafe/sn_sdkg",
"maidsafe/qp2p",
"maidsafe/stableset-experiments",
"maidsafe/sn_launch_tool",
"maidsafe/blsttc",
"maidsafe/rfcs",
]
```

### Mina

Media:
- https://minaprotocol.com/

GitHub:
- https://github.com/MinaProtocol
- https://github.com/openmina

```toml
repos = [
"openmina/openmina",
"openmina/mina-p2p-messages-rs",
"openmina/openmina-archive",
"openmina/redux-rs",
"openmina/openmina-poc",
"openmina/mina-ci",
"openmina/mina-network-debugger",
"openmina/snark-coordinator-rs",
"openmina/internal-tracing-rs",
"openmina/mina-logs-service",
"openmina/alloc-test",
"openmina/mina-gossip-rs",
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
"mobilecoinfoundation/sgx",
"mobilecoinfoundation/rust-mbedtls",
"mobilecoinfoundation/attestation",
"mobilecoinfoundation/mc-oblivious",
"mobilecoinfoundation/sgx-std",
"mobilecoinfoundation/build-rs",
"mobilecoinfoundation/sgx-sigstruct",
"mobilecoinfoundation/protobufs",
"mobilecoinfoundation/rand",
"mobilecoinfoundation/serial",
"mobilecoinfoundation/from-random",
"mobilecoinfoundation/compliance",
"mobilecoinfoundation/chronometer",
"mobilecoinfoundation/oblivious-aes-gcm",
]

```

### MultiversX

Media:
- https://multiversx.com/

GitHub:
- https://github.com/multiversx

```toml
repos = [
"multiversx/mx-subscription-fee-rs",
"multiversx/mx-exchange-tools-sc",
"multiversx/mx-metabonding-sc",
"multiversx/mx-contracts-rs",
"multiversx/mx-exchange-sc",
"multiversx/mx-sdk-rs",
"multiversx/mx-nft-collection-minter-sc",
"multiversx/mx-reproducible-contract-build-example-sc",
"multiversx/mx-vm-executor-rs",
"multiversx/mx-bridge-eth-sc-rs",
"multiversx/mx-ping-pong-sc",
"multiversx/mx-launchpad-sc",
"multiversx/mx-liquid-staking-sc",
"multiversx/mx-human-sc",
"multiversx/mx-lend-sc",
"multiversx/mx-dns-sc",
"multiversx/mx-nft-marketplace-sc",
"multiversx/mx-energy-competition-winners-extraction-sc",
"multiversx/mx-delegation-sc",
"multiversx/mx-band-bridge-sc",
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
"near/near-workspaces-rs",
"near/nearcore",
"near/near-cli-rs",
"near/borsh-rs",
"near/near-sdk-rs",
"near/read-rpc",
"near/near-microindexers",
"near/neardevhub-contract",
"near/pagoda-relayer-rs",
"near/near-indexer-for-explorer",
"near/cargo-near",
"near/near-abi-rs",
"near/near-memory-tracker",
"near/near-lake-indexer",
"near/core-contracts",
"near/near-lake-framework-rs",
"near/near-jsonrpc-client-rs",
"near/near-account-id",
"near/bos-loader",
"near/wasmer",
"near/near-linkdrop",
"near/near-enhanced-api-server",
"near/dkim-auth",
"near/sdk-rs-gas-benchmark",
"near/near-sdk-abi",
"near/near-abi-client-rs",
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
"nervosnetwork/ckb",
"nervosnetwork/ckb-light-client",
"nervosnetwork/ckb-vm",
"nervosnetwork/ckb-standalone-debugger",
"nervosnetwork/ckb-integration-test",
"nervosnetwork/ckb-sdk-rust",
"nervosnetwork/ckb-cli",
"nervosnetwork/ckb-std",
"nervosnetwork/faster-hex",
"nervosnetwork/overlord",
"nervosnetwork/molecule",
"nervosnetwork/ckb-x64-simulator",
"nervosnetwork/merkle-mountain-range",
"nervosnetwork/wasm-secp256k1-test",
"nervosnetwork/sparse-merkle-tree",
"nervosnetwork/capsule",
"nervosnetwork/mercury",
"nervosnetwork/ckb-indexer",
"nervosnetwork/force-bridge-btc",
"nervosnetwork/golomb-coded-set",
"godwokenrises/godwoken",
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
"oasisprotocol/keymanager-paratime",
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
"paritytech/polkadot-sdk",
"paritytech/zombienet-sdk",
"paritytech/ink",
"paritytech/cargo-contract",
"paritytech/xcm",
"paritytech/trappist",
"paritytech/parity-signer",
"paritytech/parity-scale-codec",
"paritytech/substrate-dex",
"paritytech/jsonrpsee",
"paritytech/parity-bridges-common",
"paritytech/mixnet",
"paritytech/staking-miner-v2",
"paritytech/pvf-checker",
"paritytech/polkadot-introspector",
"paritytech/subxt",
"paritytech/subport",
"paritytech/substrate-telemetry",
"paritytech/frontier",
"paritytech/extended-parachain-template",
"paritytech/trie",
"paritytech/polkadot-sdk-docs",
"paritytech/subxt-explorer",
"paritytech/parity-publish",
"paritytech/reed-solomon-novelpoly",
"paritytech/substrate-curves",
"paritytech/ark-substrate",
"paritytech/try-runtime-cli",
"paritytech/wasmi",
"paritytech/soketto",
"paritytech/frame-metadata",
"paritytech/substrate-contracts-node",
"paritytech/parachain-utils",
"paritytech/smart-bench",
"paritytech/parity-common",
"paritytech/orchestra",
"paritytech/ink-playground",
"paritytech/diener",
"paritytech/ink-examples",
"paritytech/frontier-parachain-template",
"paritytech/wasm-instrument",
"paritytech/pvf-executor",
"paritytech/parity-db",
"paritytech/prdoc",
"paritytech/unsigned-varint",
"paritytech/scale-decode",
"paritytech/polkadot-stps",
"paritytech/ss58-registry",
"paritytech/verifiable",
"paritytech/polkapobal",
"paritytech/parity-processbot",
"paritytech/subpub",
"paritytech/reref",
"paritytech/scale-info",
"paritytech/libsecp256k1",
"paritytech/parity-tokio-ipc",
"paritytech/polkadot-identicon-rust",
"paritytech/scale-value",
"paritytech/scale-encode",
"paritytech/squink-splash-beginner",
"paritytech/co2-passport",
"paritytech/finality-grandpa",
"paritytech/ink-waterfall",
"paritytech/pallet-contracts-xcm",
"paritytech/appsec_ctf_playground",
"paritytech/desub",
"paritytech/polkadot-developer-data",
"paritytech/blockstats",
"paritytech/scale-bits",
"paritytech/parity-bitcoin",
"paritytech/banana-recovery-rust",
"paritytech/banana_split",
"paritytech/secret-store",
"paritytech/rustc-codesize-min",
"paritytech/polkadot-interaction-examples-rs",
"paritytech/substrate-test-runner",
"paritytech/smoldot",
"paritytech/cargo-unleash",
"paritytech/substrate-template-generator",
"paritytech/metadata-portal",
]
```

### Radix

Media:
- https://www.radixdlt.com/

GitHub:
- https://github.com/radixdlt

```toml
repos = [
"radixdlt/radixdlt-scrypto",
"radixdlt/scrypto-examples",
"radixdlt/community-scrypto-examples",
"radixdlt/radix-engine-toolkit",
"radixdlt/create-scrypto-dapp",
"radixdlt/babylon-ledger-app",
"radixdlt/scrypto101-exercises",
"radixdlt/scrypto-challenges",
"radixdlt/scrypto-demos",
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
"scrtlabs/examples",
"scrtlabs/snip20-reference-impl",
"scrtlabs/secret-toolkit",
"scrtlabs/ibc-hooks-snip20-auto-wrap-proxy-contract",
"scrtlabs/shielded-voting",
"scrtlabs/tm-secret-enclave",
"scrtlabs/seed-rotation-service",
"scrtlabs/secretSCRT",
"scrtlabs/secret-vrf-challenge-contract",
"scrtlabs/random-ibc-example",
"scrtlabs/unstoppable-secrets",
"scrtlabs/ics20-for-axelar",
"scrtlabs/SecretSwap",
"scrtlabs/mobile-video-example",
"scrtlabs/crosschain-contract-demo",
"scrtlabs/MillionaireProblemTutorial",
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
"solana-labs/cargo-run-solana-tests",
"solana-labs/solana-accountsdb-plugin-postgres",
"solana-labs/interns-codehub",
"solana-labs/governance-program-library",
"solana-labs/solana-accountsdb-plugin-postgres",
"solana-labs/perpetuals",
]
```

### Soroban

GitHub:
- https://github.com/stellar

```toml
repos = [
"stellar/rs-soroban-sdk",
"stellar/rs-soroban-env",
"stellar/scaffold-soroban",
"stellar/soroban-tools",
"stellar/xdrgen",
"stellar/soroban-example-dapp",
"stellar/rs-stellar-strkey",
"stellar/rs-stellar-xdr",
"stellar/soroban-examples",
"stellar/soroban-quest",
"stellar/fca00c-asteroids",
"stellar/soroflare",
"stellar/bytes-lit",
"stellar/crate-git-revision",
"stellar/soroban-name-service",
]
```

### Spacemesh

GitHub:
- https://github.com/spacemeshos

``` toml
repos = [
"spacemeshos/post-rs",
"spacemeshos/spacemesh-sdk",
"spacemeshos/scrypt-jane-rs",
"spacemeshos/spacemesh-rs",
]
```

### Subspace Network

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
"subspace/pulsar",
"subspace/subspace-sdk",
"subspace/layerzero_testnet_bridge",
]
```

### Sui

Media:
- https://sui.io/
- https://twitter.com/mysten_labs
- https://medium.com/mysten-labs

GitHub:
- https://github.com/MystenLabs

```toml
repos = [
"MystenLabs/sui",
"MystenLabs/narwhal",
"MystenLabs/fastcrypto",
"MystenLabs/dapol",
"MystenLabs/mysten-sim",
"MystenLabs/ed25519-unsafe-libs",
"MystenLabs/base64pemkey",
]
```

### TezEdge

GitHub:
- https://github.com/tezedge

``` toml
repos = [
"tezedge/tezedge",
"tezedge/tezedge-snapshots",
]
```

### Vara

GitHub:
- https://github.com/gear-tech

``` toml
repos = [
"https://github.com/gear-tech/gear",
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
"zcash/librustzcash",
"zcash/incrementalmerkletree",
"zcash/orchard",
"zcash/pasta_curves",
"zcash/halo2",
"zcash/halo2_legacy_pdqsort",
"ZcashFoundation/zebra",
"ZcashFoundation/reddsa",
"ZcashFoundation/frost",
"ZcashFoundation/ed25519-zebra",
"ZcashFoundation/frost-zcash-demo",
"ZcashFoundation/zcash-sync",
"ZcashFoundation/redjubjub",
]
```

---

## Rust in Bitcoin

### AluVM

GitHub:
- https://github.com/AluVM

```toml
repos = [
"AluVM/rust-aluvm",
"AluVM/aluasm",
"AluVM/alure",
]
```

### BDK

Media:
- https://bitcoindevkit.org

GitHub:
- https://github.com/bitcoindevkit

```toml
repos = [
"bitcoindevkit/rust-esplora-client",
"bitcoindevkit/bdk",
"bitcoindevkit/rust-hwi",
"bitcoindevkit/bdk-ffi",
"bitcoindevkit/bdk-cli",
"bitcoindevkit/rust-electrum-client",
"bitcoindevkit/bdk-reserves",
"bitcoindevkit/elephant",
]
```

### Bitcoin Protocol

GitHub:
- https://github.com/BP-WG

```toml
repos = [
"BP-WG/bitcoin_foundation",
"BP-WG/bp-core",
"BP-WG/descriptor-wallet",
"BP-WG/bp-node",
"BP-WG/bp-wallet",
"BP-WG/bp-std",
"BP-WG/bitcoin_hwi",
]
```

### BitMask

Media:
- https://bitmask.app

GitHub:
- https://github.com/diba-io/bitmask-core

```toml
repos = [
"diba-io/bitmask-core",
]
```

### Bitswap

GitHub:
- https://github.com/BitSwap-BiFi

```toml
repos = [
"BitSwap-BiFi/Bitswap-core",
]
```

### CivKit

GitHub:
- https://github.com/civkit

```toml
repos = [
"civkit/civkit-node",
"civkit/orage",
"civkit/staking-credentials",
]
```

### Cyphernet

GitHub:
- https://github.com/cyphernet-dao

```toml
repos = [
"cyphernet-dao/rust-netservices",
"cyphernet-dao/rust-internet2",
"cyphernet-dao/rust-microservices",
"cyphernet-dao/rust-cyphernet",
"cyphernet-dao/nsh",
"cyphernet-dao/ssi",
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

### Fedimint

GitHub:
- https://github.com/fedimint

```toml
repos = [
"fedimint/fedimint",
"fedimint/fedimint-custom-modules-example",
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
"lightningdevkit/ldk-node",
"lightningdevkit/ldk-lsp-client",
"lightningdevkit/vss-rust-client",
"lightningdevkit/rapid-gossip-sync-server",
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

Media:
- https://www.turbofish.org/blog

GitHub:
- https://github.com/nomic-io
- https://github.com/turbofish-org

```toml
repos = [
"nomic-io/nomic",
"turbofish-org/merk",
"turbofish-org/orga",
"turbofish-org/abci2",
"turbofish-org/ed",
"turbofish-org/node-merk",
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
"RGB-WG/rgb",
"RGB-WG/rgb-wallet",
"RGB-WG/rgb-schemata",
]
```

### Rust Bitcoin

GitHub:
- https://github.com/rust-bitcoin

```toml
repos = [
"rust-bitcoin/rust-bitcoin",
"rust-bitcoin/rust-miniscript",
"rust-bitcoin/rust-bech32",
"rust-bitcoin/rust-bip39",
"rust-bitcoin/rust-bitcoincore-rpc",
"rust-bitcoin/hex-conservative",
"rust-bitcoin/rust-wallet",
"rust-bitcoin/rust-bech32-bitcoin",
"rust-bitcoin/rust-secp256k1",
]
```

### Rust Payjoin

GitHub:
- https://github.com/payjoin/rust-payjoin

```toml
repos = [
"payjoin/rust-payjoin",
]
```

### Rust Simplicity

GitHub:
- https://github.com/BlockstreamResearch/rust-simplicity

```toml
repos = [
"BlockstreamResearch/rust-simplicity",
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

### Strict types

GitHub:
- https://github.com/strict-types

```toml
repos = [
"strict-types/strict-types",
"strict-types/strict-encoding",
"strict-types/stenc",
"strict-types/encoding_derive_helpers",
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

### Foundry

Media:
- https://getfoundry.sh

GitHub:
- https://github.com/foundry-rs/foundry

```toml
repos = [
"foundry-rs/foundry",
"foundry-rs/starknet-foundry",
"foundry-rs/foundry-rust-template",
]
```

### Lighthouse

Media:
- https://lighthouse.sigmaprime.io/

GitHub:
- https://github.com/sigp/lighthouse

```toml
repos = [
"sigp/lighthouse",
"sigp/discv5",
"sigp/enr",
"sigp/eleel",
"sigp/milhouse",
"sigp/tree_hash",
"sigp/metastruct",
"sigp/ssz_types",
"sigp/gossipsub-testground",
"sigp/ethereum_serde_utils",
]
```

### Polygon Zero

Media:
- https://mirprotocol.org/

GitHub:
- https://github.com/0xPolygonZero

```toml
repos = [
"0xPolygonZero/plonky2",
"0xPolygonZero/evm-tests",
"0xPolygonZero/proof-protocol-decoder",
"0xPolygonZero/plonky-edge-block-trace-parser",
"0xPolygonZero/plonky2-u32",
"0xPolygonZero/plonky2-ecdsa",
"0xPolygonZero/plonky-block-proof-gen",
"0xPolygonZero/eth_trie_utils",
"0xPolygonZero/system-zero",
"0xPolygonZero/plonky2-insertion",
"0xPolygonZero/plonky2-waksman",
]
```

### Reth

GitHub:
- https://github.com/paradigmxyz/reth

```toml
repos = [
"paradigmxyz/reth",
]
```

### Rust Ethereum

GitHub:
- https://github.com/rust-ethereum

```toml
repos = [
"rust-ethereum/ethabi",
"rust-ethereum/ethash",
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

### Starkware

GitHub:
- https://github.com/starkware-libs

```toml
repos = [
"starkware-libs/cairo",
"starkware-libs/papyrus",
"starkware-libs/blockifier",
"starkware-libs/starknet-api",
]
```

### zkSync Era

Media:
- https://medium.com/matter-labs
- https://twitter.com/zksync

GitHub:
- https://github.com/matter-labs/zksync-era

``` toml
repos = [
"matter-labs/demo-circuit",
"matter-labs/eip1962",
"matter-labs/era-boojum",
"matter-labs/era-boojum-cuda",
"matter-labs/era-boojum-validator-cli",
"matter-labs/era-circuit_testing",
"matter-labs/era-compiler-llvm-context",
"matter-labs/era-compiler-llvm-builder",
"matter-labs/era-compiler-solidity",
"matter-labs/era-compiler-tester",
"matter-labs/era-compiler-vyper",
"matter-labs/era-compiler-common",
"matter-labs/era-heavy-ops-service",
"matter-labs/era-revm",
"matter-labs/era-shivini",
"matter-labs/era-sync_vm",
"matter-labs/era-test-node",
"matter-labs/era-zkevm_opcode_defs",
"matter-labs/era-zkevm_test_harness",
"matter-labs/era-zk_evm",
"matter-labs/era-zk_evm_abstractions",
"matter-labs/era-zkEVM-assembly",
"matter-labs/era-zkevm_circuits",
"matter-labs/era-zkevm_tester",
"matter-labs/foundry-zksync",
"matter-labs/franklin-crypto",
"matter-labs/hodor",
"matter-labs/rescue-poseidon",
"matter-labs/risc_v_simulator",
"matter-labs/schnorr-musig",
"matter-labs/snark-wrapper",
"matter-labs/vise",
"matter-labs/zksync-era",
"matter-labs/zksync",
"matter-labs/zk_os",
]
```
