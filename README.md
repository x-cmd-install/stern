# stern

[中文版本](./README.cn.md)

⎈ Multi pod and container log tailing for Kubernetes -- Friendly fork of https://github.com/wercker/stern

![stern](https://repo.x-cmd.io/stern.svg)

## Install

```sh
x install stern
```

## Code insight

Total: **5,612** lines of code across **42** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 5,525 | 328 | 601 | 30 |
| Makefile | 60 | 0 | 20 | 1 |
| Sh | 13 | 1 | 4 | 1 |
| Yaml | 9 | 0 | 0 | 9 |
| Dockerfile | 4 | 0 | 0 | 1 |

## OpenSSF Scorecard

Overall score: **4.1 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Maintained** (3/10) — 4 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 3
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## Source

- **Upstream**: <https://github.com/stern/stern>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.34.0` (2026-05-02)
- **Last commit**: 2026-08-19
- **Assets in release**: 10

## Popularity

- **Stars**: 4,858 · **Forks**: 177 · **Open issues**: 157 · **Contributors**: 58

## Totals (cumulative)

- **Releases**: 27 · **Merged PRs**: 185 · **Open PRs**: 11 · **Closed issues**: 126 · **Open issues**: 31 · **Commits**: 318

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 0 | 0 | 4 | 0 | 1 | 1 |
| last60d | 2026-07-14 | 0 | 1 | 7 | 0 | 1 | 2 |
| 90d | 2026-06-14 | 0 | 4 | 7 | 1 | 1 | 4 |
| last180d | 2026-03-16 | 1 | 10 | 8 | 1 | 1 | 10 |
| 360d | 2025-09-17 | 2 | 13 | 9 | 2 | 4 | 13 |
| last720d | 2024-09-22 | 5 | 28 | 11 | 11 | 12 | 29 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [checksums.txt](https://github.com/stern/stern/releases/download/v1.34.0/checksums.txt) | 884 B | `other` |
| [stern_1.34.0_darwin_amd64.tar.gz](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_darwin_amd64.tar.gz) | 13.7 MiB | `native/darwin/x64` |
| [stern_1.34.0_darwin_arm64.tar.gz](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_darwin_arm64.tar.gz) | 12.6 MiB | `native/darwin/arm64` |
| [stern_1.34.0_linux_amd64.tar.gz](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_linux_amd64.tar.gz) | 13.5 MiB | `native/linux/x64` |
| [stern_1.34.0_linux_arm.tar.gz](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_linux_arm.tar.gz) | 12.7 MiB | `native/linux/arm` |
| [stern_1.34.0_linux_arm64.tar.gz](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_linux_arm64.tar.gz) | 12.0 MiB | `native/linux/arm64` |
| [stern_1.34.0_windows_amd64.tar.gz](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_windows_amd64.tar.gz) | 13.9 MiB | `native/win/x64` |
| [stern_1.34.0_windows_amd64.zip](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_windows_amd64.zip) | 13.9 MiB | `native/win/x64` |
| [stern_1.34.0_windows_arm64.tar.gz](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_windows_arm64.tar.gz) | 12.1 MiB | `native/win/arm64` |
| [stern_1.34.0_windows_arm64.zip](https://github.com/stern/stern/releases/download/v1.34.0/stern_1.34.0_windows_arm64.zip) | 12.1 MiB | `native/win/arm64` |

## Distribution status

Reported by **40** distros on [repology.org](https://repology.org/project/stern). **15** are ✅ on the latest upstream release, **12** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `1.34.0` | ✅ latest |
| Homebrew | `1.34.0` | ✅ latest |
| Nix unstable | `1.34.0` | ✅ latest |
| Void | `1.34.0` | ✅ latest |
| Alpine edge | `1.33.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `1.34.0` | ✅ latest |

## Improve this data

Install metadata for stern lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `stern` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/stern.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260912.yml` · 2026-09-12T04:53:10Z._
