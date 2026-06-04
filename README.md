# adaouat/homebrew-tap

Homebrew tap for the [`adaouat`](https://github.com/adaouat) CLI family. Each tool ships as
a **cask** wrapping a pre-built binary (raw binaries, no archive); the cask files under
[`Casks/`](Casks/) are generated and pushed by each tool's GoReleaser release — do not edit
them by hand.

## Install

```bash
brew tap adaouat/tap
brew install --cask <tool>
```

Or in one step:

```bash
brew install --cask adaouat/tap/<tool>
```

Upgrade with `brew upgrade --cask <tool>`.

## Available tools

| Tool | Description |
|------|-------------|
| _none yet_ | casks are added by each tool's first release |

<!-- As tools publish, list them here, e.g.:
| [`heraut`](https://github.com/adaouat/heraut) | Release management for git-based projects |
| [`bifrost`](https://github.com/adaouat/bifrost) | Atomic deployment CLI |
-->
