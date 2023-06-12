# Awesome Buck2

A collection of projects, articles and resources related to [Buck2](https://buck2.build/), Meta's official build tool.

## Projects

#### Official repositories

- [Buck2 build tool](https://github.com/facebook/buck2)
- [Prelude](https://github.com/facebook/buck2-prelude): read-only, PRs should go to [Buck2](https://github.com/facebook/buck2) repository instead.
- [Reindeer](https://github.com/facebookincubator/reindeer): Reindeer is a tool which takes Rust Cargo dependencies and generates Buck build rules. Similar to Bazel's Gazelle.

**Related Meta projects**

- [Buck](https://github.com/facebook/buck): some integration tests are re-used for Buck2.
- [Sapling](https://github.com/facebook/sapling): Meta's custom VCS originated from Mercurial.
- [Watchman](https://github.com/facebook/watchman): Meta's multi-platforms file watcher. Many dev tools integrate with it.
- [Starlark in Rust](https://github.com/facebookexperimental/starlark-rust): Starlark implementation in Rust with LSP and Type-hint support.
- [Hermit](https://github.com/facebookexperimental/hermit): A linux hermetic, isolated sandbox for test executions and chaos experiments
- [Reverie](https://github.com/facebookexperimental/reverie): An ergonomic and safe syscall interception framework for Linux.
- [OcamlRep](https://github.com/facebook/ocamlrep): libraries and tools to write applications and libraries mixing OCaml and Rust. Built with Buck2.
- [Antlir](https://github.com/facebookincubator/antlir): rules and tools to build QEMU-compatible Linux Images for VM using Buck/Buck2. Antlir2 is being rewritten using Rust.
- [Shed](https://github.com/facebookexperimental/rust-shed): Meta's Rust libraries commonly used between open source projects.
- [Gazebo](https://github.com/facebookincubator/gazebo): Meta's Rust library collection of small well-tested primitives.
- [Glean](https://github.com/facebookincubator/Glean): Meta's code intelligence platform.
- [SuperConsole](https://github.com/facebookincubator/superconsole): Buck2's terminal UI (CLI) library.

#### Community repositories

- [buck2-nix](https://github.com/thoughtpolice/buck2-nix): An experiment to integrate Buck2, Sapling, and Nix together in a harmonious way.
- [install-buck2](https://github.com/dtolnay/install-buck2): Installing buck2 into Github Action.
- [buck2.nvim](https://github.com/benbrittain/buck2.nvim): Neovim configuration to integrate with Buck2's Starlark LSP.
- [buckle](https://github.com/benbrittain/buckle): Buck2 launcher / version manager, similar to Bazel's [Bazelisk](https://github.com/bazelbuild/bazelisk).
- [NoRedInk-UI](https://github.com/NoRedInk/noredink-ui): a project which uses Buck2 to build Elm front-end application(s).

## Articles

#### Official Docs

- [Concepts](https://buck2.build/docs/concepts/concept_map/)
- [Architecture](https://buck2.build/docs/developers/architecture/buck2/)
- [Glossary](https://buck2.build/docs/concepts/glossary/)
- [Getting Started and Hello World](https://buck2.build/docs/getting_started/)
- [Remote Execution](https://buck2.build/docs/remote_execution/)

#### Community

- [Using Crates.io with Buck](https://steveklabnik.com/writing/using-cratesio-with-buck) by [@steveklabnik](https://github.com/steveklabnik)


## Resources

- [Buck2 team's Reddit AMA 05/2023](https://old.reddit.com/r/rust/comments/136qs44/hello_rrust_we_are_meta_engineers_who_created_the/)

- [Buck2 Unofficial Community Discord](https://discord.com/invite/WJj9hf6x) managed by [@steveklabnik](https://github.com/steveklabnik)
