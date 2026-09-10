# LWang

LWang 桌面客户端下载与更新通道。此仓库仅用于分发安装包、更新清单和发行说明。

## Windows 安装

请在 [Releases](https://github.com/Fabian345/LWang-releases/releases) 下载对应版本的 Windows x64 安装程序。

2.0.8 及更早版本需要手动安装 2.0.9 一次，以切换到此公开更新通道。此后的版本会由客户端自动检查，并在用户确认后下载和启动安装程序。

当前安装程序为测试发行包，尚未配置发布者代码签名。安装与更新需要联网；模型服务仍需有效的 LWang 激活授权。

## 更新通道

- 稳定版清单：`releases/download/lwang-stable/lwang-update.json`
- 版本安装包：`releases/download/lwang-vVERSION/`

每个版本提供 SHA-256 校验文件；客户端会校验安装包大小和摘要。版本安装包发布后不覆盖；通道清单在安装包可下载后更新。
