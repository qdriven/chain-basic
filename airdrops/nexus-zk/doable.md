# README


## Setup

```sh
rustup target add riscv32i-unknown-none-elf
cargo install --git https://github.com/nexus-xyz/nexus-zkvm cargo-nexus --tag 'v0.2.4'
curl https://cli.nexus.xyz/ | sh
brew install protobuff
```

## Setup Node and Project

```sh
cargo nexus --help
cargo nexus new <project_name>
cargo nexus run
cargo nexus prove
cargo nexus verify
```
