# 🍺 rhyumiranda's Homebrew tap

A single place to install my tools and apps with Homebrew — add a formula here and it's one `brew install` away.

## Usage

```sh
brew tap rhyumiranda/tap
brew install <formula>
# or in one line:
brew install rhyumiranda/tap/<formula>
```

## Available formulae

| Formula | What it is | Install |
| --- | --- | --- |
| [`sesame`](https://github.com/rhyumiranda/sesame) | Fingerprint-gated env-secret vault for AI agents | `brew install rhyumiranda/tap/sesame` |
| [`canopy`](https://github.com/rhyumiranda/canopy) | Orchestration layer for AI coding agents | `brew install rhyumiranda/tap/canopy` |

_More coming — each new tool is just another file under `Formula/`._

## Contributing a formula

Drop `Formula/<name>.rb` into this repo. Point its `url` at the tool's release tarball and set the matching `sha256`. See the tool's own repo for its formula source and release process.
