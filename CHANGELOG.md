# HeyCC Changelog

[English](#english) | [简体中文](#中文)

## English

HeyCC's product-level public release history. Changes are grouped by `heycc-plugin` and `heycc-cookbook`; future products will use their own `*-release/CHANGELOG.md` files.

## 中文

HeyCC 的产品级公开变更记录。模块变化按 `heycc-plugin` 和 `heycc-cookbook` 分组；未来产品使用各自的 `*-release/CHANGELOG.md`，不会合并到这里。

## [Unreleased]

### heycc-plugin / 插件模块

- Added the initial public marketplace directory structure. / 新增公开市场目录骨架。
- Added the HeyCC plugin manifest and marketplace schemas. / 新增 HeyCC 插件 Manifest 和 Marketplace Schema。
- Added a minimal plugin template and submission guidance. / 新增最小插件模板和提交说明。
- Documented the trust boundary: marketplace metadata cannot execute arbitrary install or probe commands. / 明确安全边界：市场元数据不能执行任意安装或探测命令。

### heycc-cookbook / Cookbook 模块

- Added the first plugin browsing, installation, and submission recipes. / 新增插件浏览、安装和提交配方。
- Added the iTermux Bridge platform and installation-boundary recipe. / 新增 iTermux Bridge 平台与安装边界配方。

### Documentation / 文档

- Added English and Simplified Chinese content to the public guides, recipes, issue templates, and governance documents. / 为公开指南、配方、Issue 模板和治理文档补充英文与简体中文内容。

### Security / 安全

- Documented that third-party source, licenses, fixed revisions, and platform constraints must be disclosed before publication. / 明确第三方来源、许可证、固定版本和平台限制必须在发布前披露。
