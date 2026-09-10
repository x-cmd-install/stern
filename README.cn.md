# stern

[English version](./README.md)

⎈ Multi pod and container log tailing for Kubernetes -- Friendly fork of https://github.com/wercker/stern

![stern](https://repo.x-cmd.io/stern.svg?lang=zh)

## 安装

```sh
x install stern
```

## 代码规模

合计: **5,612** 行代码（覆盖前 5 种语言、共 **42** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 5,525 | 328 | 601 | 30 |
| Makefile | 60 | 0 | 20 | 1 |
| Sh | 13 | 1 | 4 | 1 |
| Yaml | 9 | 0 | 0 | 9 |
| Dockerfile | 4 | 0 | 0 | 1 |

## OpenSSF Scorecard 评分

总评分: **4.1 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Maintained** (3/10) — 4 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 3
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/stern/stern>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.34.0` (2026-05-02)
- **最近提交**: 2026-08-19
- **Release 含资产**: 10 个

## 流行度

- **Star**: 4,857 · **Fork**: 177 · **开放 issue**: 157 · **贡献者**: 58

## 累计统计

- **发布数**: 27 · **已合并 PR**: 185 · **开放 PR**: 11 · **已关闭 issue**: 126 · **开放 issue**: 31 · **提交数**: 318

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 4 | 0 | 1 | 1 |
| last60d | 2026-07-12 | 0 | 1 | 7 | 0 | 1 | 2 |
| 90d | 2026-06-12 | 0 | 4 | 7 | 1 | 1 | 4 |
| last180d | 2026-03-14 | 1 | 10 | 8 | 1 | 1 | 10 |
| 360d | 2025-09-15 | 2 | 13 | 9 | 2 | 4 | 13 |
| last720d | 2024-09-20 | 5 | 28 | 11 | 11 | 12 | 29 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 发行版状态

在 [repology.org](https://repology.org/project/stern) 上共有 **40** 个发行版报告此项目。**15** 个 ✅ 已是最新上游版本，**12** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `1.34.0` | ✅ latest |
| Homebrew | `1.34.0` | ✅ latest |
| Nix unstable | `1.34.0` | ✅ latest |
| Void | `1.34.0` | ✅ latest |
| Alpine edge | `1.33.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `1.34.0` | ✅ latest |

## 改进这些数据

stern 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `stern` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/stern.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T20:51:30Z._
