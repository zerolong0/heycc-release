# Contributing to HeyCC Release

[English](#english) | [简体中文](#中文)

## English

Thank you for helping build an open HeyCC plugin ecosystem. This repository accepts public ecosystem content, not HeyCC's private product source code.

### What you can submit

- HeyCC plugins
- Plugin usage recipes and integration examples
- Reproducible bug reports
- Product requests, plugin requests, and ecosystem proposals
- Improvements to the Manifest, Schema, and public collaboration workflow

### Minimum plugin requirements

Every plugin must:

- use a stable, unique kebab-case `name`;
- include `heyplugin.json` and a README;
- describe its author, source, version, permissions, and platform limits;
- declare a license;
- contain no secrets, tokens, personal data, or private product source code;
- contain no arbitrary `installCommand`, `probeCommand`, or implicit shell script in its Manifest;
- disclose fixed repositories, Tags/SHAs, and license status for external dependencies;
- pass static checks without executing unknown scripts.

### Submission flow

1. Start from [`heycc-plugin/templates/minimal-plugin/`](heycc-plugin/templates/minimal-plugin/).
2. Add the plugin under `heycc-plugin/plugins/<plugin-id>/`.
3. Add its entry to `heycc-plugin/.heycc-plugin/marketplace.json`.
4. Record the change in the `heycc-plugin` section of `CHANGELOG.md`.
5. Open a Pull Request describing permissions, platforms, sources, and tests.

### Requests and discussions

- Concrete, actionable requests: use Feature Request.
- Plugin proposals: use Plugin Submission.
- Open-ended design discussions: use GitHub Discussions.
- Security issues: report them privately according to the [Security Policy](SECURITY.md).

## 中文

感谢你帮助 HeyCC 建立开放的插件生态。这里收的是公开生态内容，不是 HeyCC 私有产品源代码。

### 可以提交什么

- HeyCC 插件
- 插件使用配方和集成案例
- 可复现的 Bug 报告
- 产品需求、插件需求和生态建议
- Manifest、Schema 和公开协作流程的改进

### 插件提交最低要求

每个插件必须：

- 使用稳定、唯一的 kebab-case `name`；
- 提供 `heyplugin.json` 和 README；
- 明确作者、来源、版本、权限和平台限制；
- 声明许可证；
- 不包含密钥、Token、个人数据或私有产品源代码；
- 不在 Manifest 中携带任意 `installCommand`、`probeCommand` 或隐式 shell 脚本；
- 对外部依赖提供固定的仓库、Tag/SHA 和许可证状态；
- 能在不执行未知脚本的情况下被静态检查。

### 提交流程

1. 从 [`heycc-plugin/templates/minimal-plugin/`](heycc-plugin/templates/minimal-plugin/) 开始。
2. 在 `heycc-plugin/plugins/<plugin-id>/` 添加插件内容。
3. 在 `heycc-plugin/.heycc-plugin/marketplace.json` 增加目录项。
4. 在 `CHANGELOG.md` 的 `heycc-plugin` 小节记录变化。
5. 提交 Pull Request，并说明权限、平台、来源和测试方式。

### 需求和讨论

- 具体、可执行的需求：使用 Feature Request。
- 插件提案：使用 Plugin Submission。
- 开放式设计讨论：使用 GitHub Discussions。
- 安全问题：按照 [Security Policy](SECURITY.md) 私下报告。
