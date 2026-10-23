# Future Element Homebrew tap

Install [Pinset](https://github.com/Future-Element/pinset) without cloning its repository:

```sh
brew install Future-Element/tap/pinset
```

Supported systems: Linux x64/ARM64 and macOS ARM64.

Refresh managed tool entries after installation or upgrade using the real Homebrew executable:

```sh
"$(brew --prefix pinset)/bin/pinset" self repair
"$(brew --prefix pinset)/bin/pinset" self shell
```

Use `brew upgrade pinset` for updates. Homebrew uninstall removes its package; tools, state and copied command entries in `PINSET_HOME` are retained. See the [channel lifecycle guide](https://github.com/Future-Element/pinset/blob/main/packaging/README.md).

Formula URLs and SHA-256 values are generated from published releases by Pinset's `scripts/generate_channels.py --verify-archives`.
