# Revhook

> 面向 Android 的 Xposed / LSPosed / Frida Hook 调试工具

Revhook 把脚本编写、注入调试和 AI 辅助逆向放在同一个 App 里。基于 Flutter，包名独立，可与 JsxposedX 原版同时安装。

<img src="logo.png" width="96" alt="Revhook">

## 特性

### 核心功能

- **XP / JS 与 Frida**：对着目标应用写 Hook、看日志、改进程范围
- **AI 辅助逆向**：自己配接口，写脚本、搜类、看包；提示词按功能自定义
- **APK 分析**：仓库页直接拆包看类，可按字符串搜混淆类
- **数据迁移**：从 JsxposedX 补拷，检测缺失并补迁；也可导出导入本包备份
- **完整日志**：设置里查看、复制、导出，也可发给作者

### 调试相关

- 脚本日志过滤、Logcat
- 批量导入 / 删除 XP 脚本，会话和脚本可改名
- 自定义脚本、会话命名规则
- 后台持续运行
- 适配 KernelSU 上的 Revhook Frida 模块

## 更新日志

完整记录见 [CHANGELOG.md](CHANGELOG.md)。

## 问题反馈

使用中遇到问题或有建议，请提交 [Issue](https://github.com/mob1254/revhook/issues)。

## 开源协议

本项目基于 [GPL-3.0](LICENSE) 协议开源，基于 JsxposedX 修改。
