# HeyCC Plugin

HeyCC 的公开插件市场目录和插件契约。

## 目录

```text
heycc-plugin/
├── .heycc-plugin/
│   └── marketplace.json       # 机器读取的市场目录
├── plugins/                   # HeyCC 官方插件
├── external_plugins/          # 社区/合作方插件入口
├── schemas/                   # Manifest 和 marketplace Schema
├── templates/                 # 新插件模板
└── README.md
```

## 当前状态

初始版本先发布目录、契约、模板和安全边界，市场目录暂不放入未经公开审查的插件实现。这样可以先让 HeyCC 设置页有稳定的公开 Catalog 来源，同时不泄露产品源代码。

## Manifest 约束

- 插件 ID 使用稳定的 kebab-case，发布后不要随意改名。
- `heyplugin.json` 描述元数据、权限和贡献能力。
- `requiredPermissions` 必须最小化，并在 README 中解释。
- Manifest 不能携带任意 `installCommand` 或 `probeCommand`。
- 外部依赖必须披露仓库、固定版本、许可证和平台限制。
- 插件安装不等于电脑端 Companion/Bridge 已安装或已运行。

Schema 见 [`schemas/heyplugin.schema.json`](schemas/heyplugin.schema.json) 和 [`schemas/marketplace.schema.json`](schemas/marketplace.schema.json)。

## Bridge 类插件

需要电脑端 Companion 的插件必须把 Companion 作为独立状态展示。以 iTermux Bridge 为例，它只支持 macOS + iTerm2；Windows 和 Linux 不应显示假的安装入口。V0 只提供安装指引和只读状态检测，不自动运行市场下发脚本。
