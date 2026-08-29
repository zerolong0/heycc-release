# Security Policy

[English](#english) | [简体中文](#中文)

## English

Do not publish keys, tokens, complete command lines, private addresses, or detailed exploit material in a public Issue, Pull Request, or Discussion.

### Plugin security boundaries

- Marketplace files are public catalogs, not arbitrary command-execution entry points.
- Plugins must declare their required permissions and target platforms.
- Untrusted Manifests must not deliver install scripts, probe scripts, or silent remote side effects.
- Bridges, MCP Servers, and other external components must disclose their source, version, license, and trust boundary separately.

### Reporting

Prefer GitHub's private vulnerability reporting entry point. If it is not enabled yet, use the maintainer contact shown on the `zerolong0` profile and do not disclose sensitive details publicly.

## 中文

请不要在公开 Issue、Pull Request 或 Discussion 中发布密钥、Token、完整命令行、私有地址或可利用漏洞的详细复现材料。

### 插件安全边界

- Marketplace 文件是公开目录，不是任意命令执行入口。
- 插件必须明确声明所需权限和目标平台。
- 安装脚本、探测脚本和远程副作用不能由不可信 Manifest 自行下发。
- Bridge、MCP Server 和其他外部组件必须单独披露来源、版本、许可证和信任边界。

### 报告方式

优先使用 GitHub 的私密漏洞报告入口。如果仓库尚未启用，请通过 `zerolong0` 个人主页显示的维护者联系方式联系，不要公开发布敏感细节。
