# HeyCC Release

HeyCC 的公开发布入口，专门承载插件生态、可运行 Cookbook、版本记录和用户需求收集。

GitHub Owner：`zerolong0`。

这个仓库不是 HeyCC 产品源代码仓库。HeyCC 主产品、服务端和内部实现继续保持 Private；本仓库只发布明确允许公开的插件内容、Manifest 合同、使用配方和社区协作规则。

## 目录

- [`heycc-plugin/`](heycc-plugin/) — 插件市场目录、Manifest Schema、插件模板和官方/社区插件入口
- [`heycc-cookbook/`](heycc-cookbook/) — 可以照着执行的使用与集成配方
- [`CHANGELOG.md`](CHANGELOG.md) — HeyCC 产品级公开变更记录

## 从哪里开始

1. 想浏览插件：进入 [`heycc-plugin/`](heycc-plugin/)。
2. 想学习用法：进入 [`heycc-cookbook/`](heycc-cookbook/)。
3. 想提出需求：提交 [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)。
4. 想提交插件：阅读 [插件提交说明](.github/ISSUE_TEMPLATE/plugin_submission.md)。
5. 想报告安全问题：阅读 [Security Policy](SECURITY.md)，不要在公开 Issue 中发布敏感细节。

## 设计边界

- 一个产品一个 Release 仓库；HeyCC 的公开变更集中在本仓库。
- `heycc-plugin` 和 `heycc-cookbook` 是本仓库内的模块，不单独制造一批零散顶层仓库。
- Marketplace Manifest 只描述插件元数据和能力声明，不下发任意安装脚本或探测脚本。
- 插件安装与电脑端 Companion/Bridge 安装是两个独立状态。
- 未经过许可证、签名和安全审查的上游代码不会被直接打包或自动安装。

## 当前状态

这是 HeyCC 公开频道的第一版骨架。首个可正式发布的插件会在完成代码公开范围、许可证、来源固定和安全审查后加入市场目录。
