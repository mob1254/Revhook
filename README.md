# Revhook

[![License: GPL-3.0](https://img.shields.io/github/license/mob1254/Revhook)](LICENSE)

> 面向 Android 的 Xposed / LSPosed / Frida Hook 调试工具

<img src="logo.png" width="96" alt="Revhook">

## 简介

Revhook 在手机上编写 Hook 脚本、注入到目标应用，并查看运行日志。脚本可以走 Xposed / LSPosed，也可以走 Frida。

同一个 App 里还能本机拆 APK、查看类结构，并用自定义 AI 接口辅助写脚本、搜索类、分析应用。不依赖电脑，也不需要改目标安装包。

本项目由 AI 基于 [JsxposedX](https://jsxposed.org/) 二改。

## 特性

### 核心功能

- **Xposed / LSPosed**：编写 Hook 脚本、选择注入进程、查看运行日志
- **Frida**：同样支持脚本编写、进程选择和日志
- **APK 分析**：本机拆包查看类结构，可按字符串搜索被混淆的类
- **AI 辅助**：自定义接口和提示词，辅助写脚本、搜索类、分析应用

### 其他

- 从 JsxposedX 迁移数据，支持备份导入导出
- 脚本日志过滤、Logcat
- 批量导入 / 删除脚本，会话和脚本可改名
- 自定义命名规则
- 后台持续运行
- 完整日志查看、复制、导出

## 更新日志

详见 [CHANGELOG.md](CHANGELOG.md)。

## 问题反馈

本项目只接受 [Issue](https://github.com/mob1254/revhook/issues)，暂不接受 Pull Request。

## 致谢

感谢 [JsxposedX](https://jsxposed.org/) 与 [LINUX DO](https://linux.do/) 社区。

## 开源协议

本项目由 AI 基于 JsxposedX 二改，遵循 [GNU GPL v3](LICENSE) 协议开源。

你可以自由使用、研究、分享和改进本软件；在遵守 GPL v3 的前提下，可以再发布和/或修改。
