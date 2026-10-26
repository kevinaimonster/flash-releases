# Flash for macOS

[下载最新正式版](https://github.com/kevinaimonster/flash-releases/releases/latest)

原生 macOS 语音输入应用。支持 macOS 14 及以上版本，安装包同时支持 Apple Silicon 和 Intel Mac。

## 安装

1. 打开上方下载页面，下载 `Flash-版本号.zip`。
2. 解压后，将 `Flash.app` 拖入「应用程序」文件夹，再打开。
3. 按首页提示允许麦克风和语音识别；需要自动输入时，再允许辅助功能权限。
4. 在设置中填入自己的 DeepSeek API Key 后使用 AI 文字整理；选择「原文直出」则不需要模型密钥。

轻按并松开 Fn 开始说话，再按一次完成。Flash 运行时会管理单独 Fn 的系统动作，正常退出后恢复。

## 后续升级

首次安装支持自动更新的正式包后，Flash 会在后台检查和下载新版；校验通过后在退出时安装，也可从设置或菜单栏「检查更新」手动操作。可以关闭自动检查或自动下载。

此前没有更新器的本地开发包需要手动安装正式版一次。

## 发行文件

- `Flash-版本号.zip`：完整安装包，经过 Developer ID 签名与 Apple 公证。
- `appcast.xml`：签名自动更新源，供应用读取。
- `SHA256SUMS`：文件校验和。
- `release-notes.md`：本版说明和安装指引。

发行签名团队为 **BYTE ENERGY LIMITED**。更新签名使用 Flash 独立密钥。

本仓库仅分发安装包、更新源和发布说明，不包含 Flash 源码或任何 API Key、签名私钥。API Key 保存在使用者自己的系统钥匙串；Flash 不保存录音。
