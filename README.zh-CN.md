# pianone-bucket

[English](README.md) | [简体中文](README.zh-CN.md)

这是一个精选 Scoop bucket，收录在 `main`、`extras` 或较成熟的社区 bucket 中尚未提供的实用软件。

本 bucket 以小而易维护为目标。搜索结果只是候选线索，不代表一定会收录。我们会综合考虑软件的实用性、来源可信度、下载地址与校验值的可靠性、安装和卸载行为是否适合 Scoop，以及长期维护成本。

## 已收录软件

| 软件 | 用途 |
| --- | --- |
| [NatPierce](https://www.natpierce.cn/) (`natpierce`) | 内网穿透与虚拟组网工具。 |

## 使用方法

添加 bucket：

```pwsh
scoop bucket add pianone-bucket https://github.com/Nliuco/pianone-bucket
```

安装软件：

```pwsh
scoop install pianone-bucket/<app-name>
```

将 `<app-name>` 替换为 manifest 名称。

## 贡献

提交软件候选前，请先确认它尚未收录在 Scoop 的 `main`、`extras` 或维护良好的社区 bucket 中。请附上项目官网和官方下载来源，并说明为什么值得在此 bucket 维护。

新增 manifest 应遵循 [Scoop 应用清单指南](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) 和 [Scoop 贡献指南](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)。
