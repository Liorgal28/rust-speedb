# rust-speedb

Basic wrapper around speedb key-value storage engine.

# Usage
This binding is statically linked with a specific version of SpeeDB. If you want to build it yourself, make sure you've also cloned the SpeeDB and compression submodules:
```bash
git submodule update --init --recursive
```
# How to use:

Just add it as a dependancy under your Cargo.toml:

```bash
[dependencies.speedb]
git = "https://github.com/Liorgal28/rust-speedb.git"
rev = "2cbe8da2e18bd6a21aba9d48f072f5cc252bdf30"
default-features = false
features = ["multi-threaded-cf", "lz4"]
```

