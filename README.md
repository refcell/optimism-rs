## optimism-rs &nbsp;:red_circle::large_blue_circle::orange_circle::purple_circle::green_circle::black_circle::white_circle::yellow_circle::o::brown_circle:

[![build](https://github.com/refcell/optimism-rs/actions/workflows/test.yml/badge.svg)](https://github.com/refcell/optimism-rs/actions/workflows/test.yml)
[![license: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](https://opensource.org/license/mit/)
[![chat](https://img.shields.io/badge/chat-discord-blue)](https://discord.gg/optimism)

Scaling Ethereum, but this time in rust.

> **Warning**
>
> This is not an official implementation. Please do not use until this warning has been removed. Only for demonstrative purposes, but open-sourced with ❤️.

## What is Optimism?

Optimism is a low-cost and lightning-fast Ethereum L2 blockchain.

Optimism is the technical foundation for [the Optimism Collective](https://app.optimism.io/announcement), a band of communities, companies, and citizens united by a mutually beneficial pact to adhere to the axiom of **impact=profit** — the principle that positive impact to the collective should be rewarded with profit to the individual.
We're trying to solve some of the most critical coordination failures facing the crypto ecosystem today.

**We're particularly focused on creating a sustainable funding stream for the public goods and infrastructure upon which the ecosystem so heavily relies but has so far been unable to adequately reward.**
We'd love for you to check out [The Optimistic Vision](https://www.optimism.io/vision) to understand more about why we do what we do.

Optimism has been open-source from the start, and the predominant implementation is developed in the [ethereum-optimism/optimism](https://github.com/ethereum-optimism/optimism) github repository, written in Go and Solidity.

This is intended to be an insanely ambitious alternative implementation, written primarily in [Rust](https://www.rust-lang.org/) and [Huff](https://huff.sh/). Hopefully, this implementation can prove to be an efficient substitute to the official implementation.

## Navigation

<pre>

├── 🟠 <a href="./magi">magi</a>: Rollup consensus-layer client.
├── ⭕ <a href="./op-reth">op-reth</a>: Reth execution client for post-bedrock upgrade (written in Golang - an alternative to op-geth and op-erigon).
├── 🟣 <a href="./op-erigon">op-erigon</a>: Erigon execution client for post-bedrock upgrade (written in Golang - an alternative to op-geth and op-reth).
├── ⚪ <a href="./substratum">substratum</a>: Smart Contracts and Associated Tools for Optimism.
├── ⚫ <a href="./archon">archon</a>: Service for submitting batches of transactions and results to L1.
├── 🟡 <a href="./varro">varro</a>: L2-Output Submitter, submits proposals to L1.
├── 🟢 <a href="./op-e2e">op-e2e</a>: End-to-End testing of all bedrock components in Rust.
├── 🔵 ???
├── 🟤 ???
└── 🔴 <a href="https://github.com/ethereum-optimism/optimism/tree/develop/specs">specs</a>: Specs of the rollup starting at the Bedrock upgrade [EXTERNAL].
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

