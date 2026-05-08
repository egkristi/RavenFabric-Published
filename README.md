# RavenFabric — Pre-built Binaries

Pre-built binaries for RavenFabric, a secure remote execution and mesh networking agent.
Published automatically on each release.

## Download

Each release contains binaries for all supported platforms:

| Platform | Binary |
|----------|--------|
| Linux amd64 (glibc) | `ravenfabric-linux-amd64-{agent,relay,cli}` |
| Linux amd64 (musl) | `ravenfabric-linux-amd64-musl-{agent,relay,cli}` |
| Linux arm64 (glibc) | `ravenfabric-linux-arm64-{agent,relay,cli}` |
| Linux arm64 (musl) | `ravenfabric-linux-arm64-musl-{agent,relay,cli}` |
| Linux armv7 (musl) | `ravenfabric-linux-armv7-musl-{agent,relay,cli}` |
| macOS amd64 | `ravenfabric-darwin-amd64-{agent,relay,cli}` |
| macOS arm64 | `ravenfabric-darwin-arm64-{agent,relay,cli}` |
| Windows amd64 | `ravenfabric-windows-amd64-{agent,relay,cli}.exe` |

## Quick Install

```sh
curl -fsSL https://get.ravenfabric.io | sh
```

## Docker Images

```sh
docker pull ghcr.io/egkristi/ravenfabric-agent:latest
docker pull ghcr.io/egkristi/ravenfabric-relay:latest
docker pull ghcr.io/egkristi/ravenfabric-cli:latest
```

## Package Managers

| Manager | Command |
|---------|---------|
| Homebrew | `brew install egkristi/tap/ravenfabric` |
| Cargo | `cargo install rf-cli` |

## License

AGPL-3.0-or-later — see [LICENSE](LICENSE) and [LICENSING.md](LICENSING.md) for full details.
