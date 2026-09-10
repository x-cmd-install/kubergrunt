# kubergrunt

[English version](./README.md)

Kubergrunt is a standalone go binary with a collection of commands to fill in the gaps between Terraform, Helm, and Kubectl. https://www.gruntwork.io

![kubergrunt](https://repo.x-cmd.io/kubergrunt.svg?lang=zh)

## 安装

```sh
x install kubergrunt
```

## 代码规模

合计: **8,219** 行代码（覆盖前 5 种语言、共 **92** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 7,960 | 830 | 1,295 | 83 |
| Yaml | 146 | 0 | 4 | 1 |
| Hcl | 113 | 24 | 31 | 6 |
| Markdown | 0 | 337 | 160 | 2 |

## OpenSSF Scorecard 评分

总评分: **4.3 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (-1/10) — No tokens found
- **Maintained** (2/10) — 3 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 2

## 源代码

- **上游仓库**: <https://github.com/gruntwork-io/kubergrunt>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.19.0` (2026-01-14)
- **最近提交**: 2026-09-07
- **Release 含资产**: 8 个

## 流行度

- **Star**: 564 · **Fork**: 93 · **开放 issue**: 77 · **贡献者**: 27

## 累计统计

- **发布数**: 104 · **已合并 PR**: 183 · **开放 PR**: 7 · **已关闭 issue**: 57 · **开放 issue**: 20 · **提交数**: 373

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 1 | 1 | 0 | 0 | 1 |
| last60d | 2026-07-12 | 0 | 2 | 1 | 1 | 0 | 2 |
| 90d | 2026-06-12 | 0 | 4 | 1 | 1 | 0 | 4 |
| last180d | 2026-03-14 | 0 | 6 | 6 | 1 | 0 | 6 |
| 360d | 2025-09-15 | 2 | 9 | 6 | 2 | 0 | 9 |
| last720d | 2024-09-20 | 13 | 23 | 6 | 6 | 1 | 23 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [kubergrunt_darwin_amd64](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/kubergrunt_darwin_amd64) | 57.0 MiB | `native/darwin/x64` |
| [kubergrunt_darwin_arm64](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/kubergrunt_darwin_arm64) | 55.0 MiB | `native/darwin/arm64` |
| [kubergrunt_linux_386](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/kubergrunt_linux_386) | 53.8 MiB | `other` |
| [kubergrunt_linux_amd64](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/kubergrunt_linux_amd64) | 56.3 MiB | `native/linux/x64` |
| [kubergrunt_linux_arm64](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/kubergrunt_linux_arm64) | 54.3 MiB | `native/linux/arm64` |
| [kubergrunt_windows_386.exe](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/kubergrunt_windows_386.exe) | 55.0 MiB | `native/win/x64` |
| [kubergrunt_windows_amd64.exe](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/kubergrunt_windows_amd64.exe) | 56.9 MiB | `native/win/x64` |
| [SHA256SUMS](https://github.com/gruntwork-io/kubergrunt/releases/download/v0.19.0/SHA256SUMS) | 633 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/kubergrunt) 上共有 **12** 个发行版报告此项目。**5** 个 ✅ 已是最新上游版本，**6** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `0.19.0` | ✅ latest |
| Nix unstable | `0.19.0` | ✅ latest |

## 改进这些数据

kubergrunt 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `kubergrunt` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/kubergrunt.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T21:13:13Z._
