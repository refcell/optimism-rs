## optimism-rs &nbsp;:orange_circle::o::purple_circle::white_circle::black_circle::yellow_circle::green_circle::large_blue_circle::brown_circle::red_circle:

[![build](https://github.com/refcell/optimism-rs/actions/workflows/test.yml/badge.svg)](https://github.com/refcell/optimism-rs/actions/workflows/test.yml)
[![license: MIT](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://opensource.org/license/mit/)
[![chat](https://img.shields.io/badge/chat-discord-blue)](https://discord.gg/optimism)
[![version](https://img.shields.io/badge/version-v0.1.0-ff69b4)](https://github.com/refcell/optimism-rs/releases/tag/v0.1.0)
[![core](https://img.shields.io/badge/core-rust-orange.svg)](https://www.rust-lang.org/)
[![contracts](https://img.shields.io/badge/contracts-huff-purple.svg)](https://github.com/huff-language/)

> Shoot for the moon. Even if you miss, you'll land among the stars - Norman Vincent Peale

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

_NOTE: We add [op-erigon](https://github.com/testinprod-io/op-erigon) as a submodule to include alternative execution client implementations despite it not being written in rust._

<pre>

├── 🟠 <a href="https://github.com/a16z/magi">magi</a>: Rollup consensus-layer client.
├── ⭕ <a href="https://github.com/clabby/op-reth">op-reth</a>: Reth execution client for post-bedrock upgrade (a rust alternative to op-geth and op-erigon).
├── 🟣 <a href="https://github.com/testinprod-io/op-erigon">op-erigon</a>: Erigon execution client for post-bedrock upgrade (a golang alternative to op-geth and op-reth).
├── ⚪ <a href="https://github.com/clabby/substratum">substratum</a>: Smart Contracts and Associated Tools for Optimism.
├── ⚫ <a href="https://github.com/refcell/archon">archon</a>: Service for submitting batches of transactions and results to L1.
├── 🟡 <a href="https://github.com/refcell/varro">varro</a>: L2-Output Submitter, submits proposals to L1.
├── 🟢 <a href="https://github.com/ncitron/op-e2e">op-e2e</a>: End-to-End testing of all bedrock components in Rust.
├── 🔵 ???
├── 🟤 <a href="https://github.com/clabby/op-challenger">op-challenger</a>: A challenge agent for Permissionless Output Proposals.
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
