# Meldev CLI

Africa's Edge Computing Terminal - Upload, manage, and deploy assets directly from your terminal.

## Download

### Latest Release (v1.1.1)

| Platform | Architecture | Download |
|----------|-------------|----------|
| Linux | AMD64 | [meldev-linux-amd64](https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-linux-amd64) |
| Linux | ARM64 | [meldev-linux-arm64](https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-linux-arm64) |
| macOS | Intel | [meldev-macos-amd64](https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-macos-amd64) |
| macOS | Apple Silicon | [meldev-macos-arm64](https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-macos-arm64) |
| Windows | AMD64 | [meldev-windows-amd64.exe](https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-windows-amd64.exe) |

### Quick Install

**Linux:**
```bash
curl -L -o meldev https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-linux-amd64
chmod +x meldev
sudo mv meldev /usr/local/bin/
```

**macOS:**
```bash
curl -L -o meldev https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-macos-arm64
chmod +x meldev
sudo mv meldev /usr/local/bin/
```

**Windows:**
```powershell
curl -L -o meldev.exe https://github.com/joeygoesgrey/meldev-cli-binaries/releases/latest/download/meldev-windows-amd64.exe
```

## Features

- ⚡ **Concurrent uploads** with resume support
- 🗂️ **File versioning** - automatic versions when uploading same filename
- 💰 **Wallet integration** - check balance and transactions
- 🔄 **Self-updating** - updates from this repository
- 🎨 **Cyberpunk UI** - hacker aesthetic terminal output

## Quick Start

```bash
# Authenticate
meldev auth login --token <YOUR_API_KEY>

# Upload to Public folder
meldev push ./photos/

# Upload to Private folder
meldev stash ./secrets.txt

# List files with versions
meldev list

# Check wallet
meldev wallet balance

# Update CLI
meldev system update
```

## Documentation

Full documentation at: https://meldev.com.ng/cli

## Version History

See [GitHub Releases](https://github.com/joeygoesgrey/meldev-cli-binaries/releases) for all versions and changelogs.

## About This Repository

This is a **releases-only repository** containing pre-built binaries for the Meldev CLI. The source code is kept private.

Binaries are built automatically via GitHub Actions and published here.

## License

Copyright © 2026 Meldev. All rights reserved.
