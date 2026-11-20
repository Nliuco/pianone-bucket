# pianone-bucket

[English](README.md) | [简体中文](README.zh-CN.md)

A curated Scoop bucket for useful apps not yet available in the main or popular community buckets.

This bucket aims to stay small and maintainable. Search results are leads for possible software, not a promise that an app will be added. Apps are considered based on their usefulness, trustworthy sources, reliable downloads and checksums, Scoop-compatible install and uninstall behavior, and ongoing maintenance cost.

## Available apps

| App | Description |
| --- | --- |
| [NatPierce](https://www.natpierce.cn/) (`natpierce`) | Network tunneling and virtual networking. |

## Usage

Add the bucket:

```pwsh
scoop bucket add pianone-bucket https://github.com/Nliuco/pianone-bucket
```

Install an app from it:

```pwsh
scoop install pianone-bucket/<app-name>
```

Replace `<app-name>` with the manifest name.

## Contributing

Before proposing an app, check whether it is already available in Scoop's `main`, `extras`, or a well-maintained community bucket. Please include its official project and download sources, and explain why it is useful to maintain here.

New manifests should follow the [Scoop app manifest guidelines](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) and the [Scoop contribution guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).
