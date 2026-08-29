# iTermux Bridge Platform Requirements

[English](#english) | [简体中文](#中文)

## English

### Goal

Understand the boundary between the HeyCC iTerm2 plugin and its computer-side Bridge.

### Key facts

- iTermux Bridge supports macOS + iTerm2 only.
- Windows PCs and Linux cannot use this Bridge; do not show a fake install button.
- Installing the HeyCC plugin and installing the Bridge on the target Mac are separate states.
- V0 provides instructions and read-only status checks; it does not automatically run marketplace-delivered scripts.
- A Bridge that is stopped, incompatible, unauthorized, or represented by a stale socket must not be marked Ready.

### User flow

1. Before installation, show that the target Mac needs the Bridge.
2. After plugin installation, keep showing the next-step guidance.
3. Show the target computer's Bridge state on the plugin details page.
4. After the user installs it manually, let them choose “Re-check”.
5. Allow iTerm2 control only after a real probe and protocol handshake succeed.

### Current release boundary

Do not add unreviewed Bridge code or one-click installation to the public Marketplace until a signed fork, license, pinned version, and upstream security issues are resolved.

## 中文

### 目标

理解 HeyCC 的 iTerm2 插件与电脑端 Bridge 之间的边界。

### 关键事实

- iTermux Bridge 只支持 macOS + iTerm2。
- Windows PC 和 Linux 不能使用这个 Bridge；不要显示假的安装按钮。
- HeyCC 插件安装与目标 Mac 上的 Bridge 安装是两个独立状态。
- V0 只提供安装说明和只读状态检测，不自动运行市场下发脚本。
- Bridge 未运行、版本不兼容、权限未开启或 socket 过期时，不得标记为 Ready。

### 用户流程

1. 安装前看到“需要目标 Mac 安装 Bridge”的提示。
2. 插件安装完成后继续显示下一步指引。
3. 在插件详情页查看目标电脑的 Bridge 状态。
4. 用户手动完成安装后点击“重新检查”。
5. 只有真实探测和协议握手成功，才允许使用 iTerm2 控制能力。

### 当前发布边界

在签名 Fork、许可证、固定版本和上游安全问题完成前，不把未经审查的 Bridge 代码或一键安装流程加入公开 Marketplace。
