# ClashFlow 安装包

本仓库分发原生 macOS 安装包和独立 React 桌面预览版；React/Tauri 源码仅在 [Gitee desktop 分支](https://gitee.com/striveba/clash-flow/tree/desktop) 维护，GitHub 不同步应用源码。

原生 Mac 当前版本：**0.1.5-alpha.4**（预览版）。

[下载 macOS 安装包（arm64）](https://github.com/apiao671/ClashFlowApp/releases/download/v0.1.5-alpha.4/ClashFlow-0.1.5-alpha.4-arm64.dmg) · [查看发行说明](https://github.com/apiao671/ClashFlowApp/releases/tag/v0.1.5-alpha.4)

需要 macOS 13 或更新版本，实际支持架构以发行附件为准。DMG 用于手动安装，ZIP 用于应用内更新；SHA-256 校验值保存在公开 `latest.json` 中，无需单独下载校验附件。

从仍使用 Gitee 更新源的旧版本迁移时，需要手动安装一次 GitHub 更新源版本；之后可在“设置 → 更新”中检查、下载并安装重启，无需登录 GitHub 或填写令牌。

当前安装包使用本地签名，尚未经过 Apple 公证。

## React 桌面预览版

当前版本：**0.1.0-alpha.3**。请选择与你的系统和处理器对应的安装包：

- [Windows x64 安装包（.exe）](https://github.com/apiao671/ClashFlowApp/releases/download/desktop-v0.1.0-alpha.3/ClashFlow-Desktop-0.1.0-alpha.3-windows-x64-setup.exe) · [Windows SHA-256](https://github.com/apiao671/ClashFlowApp/releases/download/desktop-v0.1.0-alpha.3/SHA256SUMS-windows-x64.txt)。Intel / AMD 64 位电脑运行 `.exe` 安装即可。安装包未做 Windows Authenticode 签名，可能显示“未知发布者”；`.exe.sig` 供 Desktop 更新器使用。
- [macOS 13+ / Apple Silicon（arm64）DMG](https://github.com/apiao671/ClashFlowApp/releases/download/desktop-v0.1.0-alpha.3/ClashFlow-Desktop-0.1.0-alpha.3-macos-arm64.dmg) · [macOS SHA-256](https://github.com/apiao671/ClashFlowApp/releases/download/desktop-v0.1.0-alpha.3/SHA256SUMS.txt)。将 DMG 内的 ClashFlow Desktop Preview.app 拖入 Applications；此包使用本地 ad-hoc 签名，尚未经过 Apple 公证。

[预览版发行说明](https://github.com/apiao671/ClashFlowApp/releases/tag/desktop-v0.1.0-alpha.3) · [desktop 源码（Gitee）](https://gitee.com/striveba/clash-flow/tree/desktop)。桌面预览版使用独立应用身份、数据目录和更新签名，不替换原生版；桌面更新清单为 `desktop/latest.json`，原生版继续使用根目录 `latest.json`。尚未提供 Intel Mac、Windows ARM64 原生或 Linux 安装包。
