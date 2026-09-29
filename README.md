# LINE 情感机器人 · macOS 测试版

[下载 Apple Silicon 安装包](./LINE-Emotion-Bot-0.1.0-macOS-arm64.dmg)

- 适用设备：M 系列 Mac，macOS 13.5 或更新版本。
- 下载后打开 DMG，将 `LINE 情感机器人.app` 拖入“应用程序”。
- SHA-256：`f8693f4312c2f3c4474d60140530ab3267caef382b69a143487f3b31eda0ec58`
- 安装包已内置 Node 和 Python 运行组件；API Key、LINE 登录和聊天记录不包含在安装包内。

2026-09-29 更新：修复自定义中转站调用 GPT-5 系列模型时的请求参数，并延长推理模型的响应等待时间。

这是未经 Apple 公证的临时签名测试版。macOS 可能阻止运行，且不保证一定出现“仍要打开”。请勿关闭 Gatekeeper；如果无法启动，请向发布者提供 macOS 版本、提示原文和 `spctl --assess --type execute -vv "/Applications/LINE 情感机器人.app"` 的输出。稳定跨设备分发需要 Developer ID 签名和 Apple 公证。
