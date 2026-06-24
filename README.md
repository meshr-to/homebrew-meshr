# Homebrew Tap — Meshr

Zero-trust WireGuard mesh for your devices, SSH, and services — macOS app.

## Install

```bash
brew install --cask meshr-to/tap/meshr
```

Or tap first, then install:

```bash
brew tap meshr-to/tap
brew install --cask meshr
```

## What's included

- **Meshr.app** — desktop app with menubar control (notarized; the
  background daemon is registered via the system on first launch)
- **meshr** — CLI tool, symlinked to `/usr/local/bin/meshr`

## Usage

```bash
meshr login -t <setup-key>
meshr up
meshr status
```

## Uninstall

```bash
brew uninstall --cask meshr
```

## Links

- Website: https://meshr.to
- Dashboard: https://app.meshr.to
- Docs: https://docs.meshr.to
