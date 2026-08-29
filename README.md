# HeyCC Release

[English](#english) | [简体中文](#中文)

## English

HeyCC's public release channel for plugins, runnable Cookbook recipes, release notes, and user feedback.

GitHub owner: `zerolong0`.

This is not the HeyCC product source repository. The HeyCC app, services, and internal implementations remain private. This repository publishes only content explicitly approved for public distribution: plugin contracts, marketplace metadata, recipes, and collaboration rules.

### Contents

- [`heycc-plugin/`](heycc-plugin/) — marketplace directory, Manifest schemas, templates, and official/community plugin entry points
- [`heycc-cookbook/`](heycc-cookbook/) — runnable usage and integration recipes
- [`CHANGELOG.md`](CHANGELOG.md) — HeyCC's product-level public release history

### Start here

1. Browse plugins: open [`heycc-plugin/`](heycc-plugin/).
2. Learn how to use HeyCC: open [`heycc-cookbook/`](heycc-cookbook/).
3. Request a feature: submit a [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md).
4. Submit a plugin: read the [Plugin Submission guide](.github/ISSUE_TEMPLATE/plugin_submission.md).
5. Report a security issue: read the [Security Policy](SECURITY.md). Do not post sensitive details in public issues.

### Boundaries

- One product has one Release repository; HeyCC's public changes live here.
- `heycc-plugin` and `heycc-cookbook` are modules in this repository rather than separate scattered top-level repositories.
- Marketplace Manifests declare plugin metadata and capabilities; they do not deliver arbitrary install or probe scripts.
- Installing a plugin and installing a computer-side Companion/Bridge are separate states.
- Upstream code is not bundled or auto-installed until its license, signature, fixed revision, and security review are complete.

### Status

This is the first public-channel scaffold for HeyCC. The first production-ready plugin will be added after its public code boundary, license, pinned source, and security review are complete.

## 中文

HeyCC 的公开发布频道，用于承载插件、可执行 Cookbook 配方、版本记录和用户需求收集。

GitHub Owner：`zerolong0`。

本仓库不是 HeyCC 产品源代码仓库。HeyCC 主产品、服务端和内部实现继续保持 Private；这里只发布明确允许公开的插件契约、市场元数据、使用配方和社区协作规则。

### 目录

- [`heycc-plugin/`](heycc-plugin/) —— 插件市场目录、Manifest Schema、模板和官方/社区插件入口
- [`heycc-cookbook/`](heycc-cookbook/) —— 可以照着执行的使用与集成配方
- [`CHANGELOG.md`](CHANGELOG.md) —— HeyCC 产品级公开变更记录

### 从这里开始

1. 浏览插件：进入 [`heycc-plugin/`](heycc-plugin/)。
2. 学习使用方式：进入 [`heycc-cookbook/`](heycc-cookbook/)。
3. 提出需求：提交 [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)。
4. 提交插件：阅读[插件提交说明](.github/ISSUE_TEMPLATE/plugin_submission.md)。
5. 报告安全问题：阅读 [Security Policy](SECURITY.md)，不要在公开 Issue 中发布敏感细节。

### 设计边界

- 一个产品对应一个 Release 仓库；HeyCC 的公开变更集中在这里。
- `heycc-plugin` 和 `heycc-cookbook` 是本仓库内的模块，不单独制造一批零散顶层仓库。
- Marketplace Manifest 只描述插件元数据和能力声明，不下发任意安装脚本或探测脚本。
- 插件安装与电脑端 Companion/Bridge 安装是两个独立状态。
- 在许可证、签名、固定版本和安全审查完成前，不直接打包或自动安装上游代码。

### 当前状态

这是 HeyCC 公开频道的第一版骨架。首个可正式发布的插件会在完成代码公开范围、许可证、来源固定和安全审查后加入市场目录。
