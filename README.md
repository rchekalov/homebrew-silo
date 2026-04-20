# homebrew-silo

Homebrew tap for [silo](https://github.com/rchekalov/silo) — run dev tools in isolated Apple Container VMs.

## Install

```bash
brew tap rchekalov/silo
brew install silo
```

Or as a one-liner (auto-taps):

```bash
brew install rchekalov/silo/silo
```

## Requirements

- Apple Silicon Mac (M1 or later)
- macOS 26 (Tahoe) or later
- Apple Container CLI: `brew install container`

## What's in this repo

Just `Formula/silo.rb`. The formula is bumped automatically by the release workflow in the [main repo](https://github.com/rchekalov/silo) on every tag push.

## Issues

File issues and feature requests on the main repo, not here: https://github.com/rchekalov/silo/issues.
