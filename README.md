# Rust Book Examples

A playground environment for examples from the rust book / general experimentation without installing the rust toolchain on your local machine

## Requirements

- Assumed OSX
- direnv (in lieu of direnv, add the `./aliases` path to your `PATH` environment variable)
- docker

## Commands

> `cargo`

Similar to running `cargo` in an environment with rust installed. The cache dir is mounted to a reusable docker volume, so caching will work but you'll need to be in docker to debug the cache.

> `rust`

Will open an interactive terminal inside a rust container with the current working directory bound in.
