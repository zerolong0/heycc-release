# Security Policy

请不要在公开 Issue、Pull Request 或 Discussion 中发布密钥、Token、完整命令行、私有地址或可利用漏洞的详细复现材料。

## 插件安全边界

- Marketplace 文件是公开目录，不是任意命令执行入口。
- 插件必须明确声明所需权限和目标平台。
- 安装脚本、探测脚本和远程副作用不能由不可信 Manifest 自行下发。
- Bridge、MCP Server 和其他外部组件必须单独披露来源、版本、许可证和信任边界。

## 报告方式

优先使用 GitHub Security Advisories 的私密报告入口；如果仓库尚未启用该入口，请通过 ZeroX 组织主页提供的维护者联系方式联系，不要公开发布敏感细节。
