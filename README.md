# Homebrew Tap for nihostt

This is the official Homebrew tap for [nihostt](https://github.com/ekhodzitsky/nihostt) — a local Japanese speech-to-text server.

## Install

```bash
brew tap ekhodzitsky/nihostt
brew install nihostt
```

## Usage

```bash
nihostt download  # one-time model download (~155 MB)
nihostt serve     # start server on http://127.0.0.1:9876
```

## Uninstall

```bash
brew uninstall nihostt
brew untap ekhodzitsky/nihostt
```

## Updating

```bash
brew update && brew upgrade nihostt
```

---

This tap is automatically updated by the [nihostt release workflow](https://github.com/ekhodzitsky/nihostt/blob/main/.github/workflows/homebrew.yml).
