## optimism-rs &nbsp;:red_circle::large_blue_circle::orange_circle::purple_circle::green_circle::black_circle::white_circle:

[![build](https://github.com/refcell/optimism-rs/actions/workflows/test.yml/badge.svg)](https://github.com/refcell/optimism-rs/actions/workflows/test.yml)
[![license: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://opensource.org/license/agpl-v3/)
[![chat](https://img.shields.io/badge/chat-discord-blue)](https://discord-gateway.optimism.io/)

Scaling Ethereum, but this time in rust.

## What is Optimism?

Optimism is a low-cost and lightning-fast Ethereum L2 blockchain.

Optimism is the technical foundation for [the Optimism Collective](https://app.optimism.io/announcement), a band of communities, companies, and citizens united by a mutually beneficial pact to adhere to the axiom of **impact=profit** — the principle that positive impact to the collective should be rewarded with profit to the individual.
We're trying to solve some of the most critical coordination failures facing the crypto ecosystem today.

**We're particularly focused on creating a sustainable funding stream for the public goods and infrastructure upon which the ecosystem so heavily relies but has so far been unable to adequately reward.**
We'd love for you to check out [The Optimistic Vision](https://www.optimism.io/vision) to understand more about why we do what we do.

Optimism has been open-source from the start, and the predominant implementation is developed in the [ethereum-optimism/optimism](https://github.com/ethereum-optimism/optimism) github repository, written in Go and Solidity.

This is intended to be an alternative implementation, written primarily in [Rust](https://www.rust-lang.org/) and [Huff](https://huff.sh/). Hopefully, this implementation can prove to be an efficient substitute to the official implementation.

## Navigation

<pre>
├── <a href="./packages">packages</a>
│   ├── <a href="./packages/common-ts">common-ts</a>: Common tools for building apps in TypeScript
│   ├── <a href="./packages/contracts">contracts</a>: L1 and L2 smart contracts for Optimism
│   ├── <a href="./packages/contracts-periphery">contracts-periphery</a>: Peripheral contracts for Optimism
│   ├── <a href="./packages/core-utils">core-utils</a>: Low-level utilities that make building Optimism easier
│   ├── <a href="./packages/data-transport-layer">data-transport-layer</a>: Service for indexing Optimism-related L1 data
│   ├── <a href="./packages/chain-mon">chain-mon</a>: Chain monitoring services
│   ├── <a href="./packages/fault-detector">fault-detector</a>: Service for detecting Sequencer faults
│   ├── <a href="./packages/message-relayer">message-relayer</a>: Tool for automatically relaying L1<>L2 messages in development
│   ├── <a href="./packages/replica-healthcheck">replica-healthcheck</a>: Service for monitoring the health of a replica node
│   └── <a href="./packages/sdk">sdk</a>: provides a set of tools for interacting with Optimism
├── <a href="./batch-submitter">batch-submitter</a>: Service for submitting batches of transactions and results to L1
├── <a href="./bss-core">bss-core</a>: Core batch-submitter logic and utilities
├── <a href="./gas-oracle">gas-oracle</a>: Service for updating L1 gas prices on L2
├── <a href="./indexer">indexer</a>: indexes and syncs transactions
├── <a href="./infra/op-replica">infra/op-replica</a>: Deployment examples and resources for running an Optimism replica
├── <a href="./integration-tests">integration-tests</a>: Various integration tests for the Optimism network
├── <a href="./l2geth">l2geth</a>: Optimism client software, a fork of <a href="https://github.com/ethereum/go-ethereum/tree/v1.9.10">geth v1.9.10</a>  (deprecated for BEDROCK upgrade)
├── <a href="./l2geth-exporter">l2geth-exporter</a>: A prometheus exporter to collect/serve metrics from an L2 geth node
├── <a href="./op-exporter">op-exporter</a>: A prometheus exporter to collect/serve metrics from an Optimism node
├── <a href="./proxyd">proxyd</a>: Configurable RPC request router and proxy
└── <a href="./technical-documents">technical-documents</a>: audits and post-mortem documents
</pre>

## Documentation

If you want to build on top of Optimism, take a look at the extensive documentation on the [Optimism Community Hub](http://community.optimism.io/).
If you want to build Optimism, check out the [Protocol Specs](./specs/).

## Community

General discussion happens most frequently on the [Optimism discord](https://discord.gg/optimism).
Governance discussion can also be found on the [Optimism Governance Forum](https://gov.optimism.io/).

## Contributing

This codebase is an amalgamation of github repositories, joined using submodules. To contribute to the codebase, it's recommended to read the contribution guidelines in each repository's respective documentation.

For contributing to the peripheral code in this repo, read through [CONTRIBUTING.md](./CONTRIBUTING.md). Then check out our list of [good first issues](https://github.com/ethereum-optimism/optimism/contribute) to find something fun to work on!

## License

All files within this repository are licensed under the [MIT License](https://github.com/ethereum-optimism/optimism/blob/master/LICENSE) unless explicitly stated otherwise.

