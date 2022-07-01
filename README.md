# Awesome WebAssembly Plugins [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Projects with plugin system implemented using WebAssembly


## Contents

- [Infrastructure](#infrastructure)
- [Developer Tools](#developer-tools)
- [Game Development](#game-development)
- [Other](#other)

## Infrastructure

- [RedPanda](https://github.com/redpanda-data/redpanda) – Kafka API compatible streaming data platform for developers
    - [Redpanda Wasm engine architecture](https://redpanda.com/blog/wasm-architecture)
    - [How we built our data transformation engine with the Wasm runtime](https://redpanda.com/blog/data-transformation-engine-with-wasm-runtime)
- [Istio](https://github.com/istio/istio) – Microservice proxy that can be used on the client and server side, and forms a microservice mesh
    - [Extensibility](https://istio.io/latest/docs/concepts/wasm)
    - [Istio and Envoy WebAssembly Extensibility, One Year On](https://istio.io/latest/blog/2021/wasm-progress/)
- [ScyllaDB](https://github.com/scylladb/scylla) – NoSQL data store using the seastar framework, compatible with Apache Cassandra
    - [Wasmtime: Supporting UDFs in ScyllaDB with WebAssembly](https://www.scylladb.com/2022/04/14/wasmtime)

## Developer Tools

- [SWC](https://github.com/swc-project/swc) – Rust-based platform for the Web
    - [Collecting feedback for new transform plugin interface](https://github.com/swc-project/swc/discussions/3540)
    - [Implementing a plugin](https://swc.rs/docs/plugin/ecmascript/getting-started)
- [dprint](https://github.com/dprint/dprint) – Pluggable and configurable code formatting platform written in Rust
    - [Plugins documentation](https://dprint.dev/plugins)
    - [Creating a Wasm Plugin](https://github.com/dprint/dprint/blob/main/docs/wasm-plugin-development.md)
- [Zellij](https://github.com/zellij-org/zellij) – Terminal workspace with batteries included
    - [Plugins documentation](https://zellij.dev/documentation/plugins.html)
- [Fiberplane](https://fiberplane.dev) – Collaborative notebooks for debugging your incidents
    - [How we use WebAssembly at Fiberplane](https://fiberplane.dev/blog/how-we-use-webassembly-at-fiberplane)
- [krew-wasm](https://github.com/flavio/krew-wasm) – Write and distribute kubectl plugins based on WebAssembly
    - [How It Works](https://github.com/flavio/krew-wasm/blob/main/README.md#how-it-works)

## Game Development
- [Feather](https://github.com/feather-rs/feather) – Minecraft server implementation in Rust
    - [WebAssembly-based plugin API for Minecraft servers](https://github.com/feather-rs/feather/tree/main/quill)
- [Microsoft Flight Simulator](https://www.flightsimulator.com/) – Amateur flight simulator
    - [WebAssembly modules](https://docs.flightsimulator.com/html/Programming_Tools/WASM/WebAssembly.htm)

## Other
- [Figma](https://figma.com) – Design platform for teams who build products together
    - [How to build a plugin system on the web and also sleep well at night](https://www.figma.com/blog/how-we-built-the-figma-plugin-system)
    - [An update on plugin security](https://www.figma.com/blog/an-update-on-plugin-security/)

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
