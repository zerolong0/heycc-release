# 提交一个 HeyCC 插件

## 目标

把一个可公开、可审查、可维护的插件加入 HeyCC 目录。

## 步骤

1. 复制 [`heycc-plugin/templates/minimal-plugin/`](../../../heycc-plugin/templates/minimal-plugin/) 到 `heycc-plugin/plugins/<plugin-id>/`。
2. 修改 `heyplugin.json`，填写真实的名称、版本、作者、权限和贡献能力。
3. 添加插件 README、许可证和第三方依赖说明。
4. 在 `heycc-plugin/.heycc-plugin/marketplace.json` 增加插件目录项。
5. 检查来源是固定 Tag/SHA，而不是不可追溯的浮动分支。
6. 提交 Plugin Submission，说明平台、权限、外部服务和测试结果。

## 不接受

- 私有产品源代码或凭证；
- 未披露的网络请求和外部副作用；
- Manifest 内的任意安装/探测脚本；
- 许可证不清、来源不可追溯或无法说明维护责任的依赖。
