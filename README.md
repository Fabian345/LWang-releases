# LWang

LWang 桌面客户端下载与更新通道。此仓库仅分发安装包、更新清单和发行说明，源码保持私有。

## 下载 2.0.10 测试版

- [Windows x64 安装程序](https://github.com/Fabian345/LWang-releases/releases/download/lwang-v2.0.10/lwang-harness-2.0.10-win32-x64.exe)
- [Mac Apple Silicon（ARM64）DMG](https://github.com/Fabian345/LWang-releases/releases/download/lwang-v2.0.10/lwang-harness-2.0.10-darwin-arm64.dmg)
- [版本说明与 SHA-256 校验文件](https://github.com/Fabian345/LWang-releases/releases/tag/lwang-v2.0.10)

本次统一桌面各入口的 LWang 品牌文案。两个安装包均为未签名测试发行；Mac 尚未完成 Apple 公证，不提供 Intel Mac 包。

## 安装与更新

Windows 运行安装程序。Mac 打开 DMG，退出正在运行的 LWang 后将应用复制到 Applications；更新时替换原应用。安装包与用户数据目录分离。

2.0.9 客户端会自动检查更新，也可以手动选择“检查更新”；用户确认后才下载安装。Mac 下载后仍需手动替换应用。2.0.8 及更早版本需要手动安装一次当前版本，才能切换到此公开更新通道。

安装与更新需要联网，模型服务仍需有效的 LWang 激活授权。

## 更新通道

- 稳定通道清单：`releases/download/lwang-stable/lwang-update.json`
- 版本安装包：`releases/download/lwang-vVERSION/`

当前两个平台共用单版本清单，仅包含已验证架构。客户端校验安装包大小、格式和 SHA-256；版本安装包发布后不覆盖，通道清单在安装包可公开下载后更新。GitHub CDN 刚发布时可能短暂返回旧清单。
