# LINE 情感机器人 · macOS 测试版

[下载 Apple Silicon 安装包](./LINE-Emotion-Bot-0.1.0-macOS-arm64.dmg)

- 适用设备：M 系列 Mac，macOS 13.5 或更新版本。
- 下载后打开 DMG，将 `LINE 情感机器人.app` 拖入“应用程序”。
- SHA-256：`8a3060cbe0ffb874ca4f31f57c0c8e00dcadfe66838a456f13c7f8ada298eb80`
- 安装包已内置 Node 和 Python 运行组件；API Key、LINE 登录和聊天记录不包含在安装包内。

2026-10-01 更新：角色提示词改为 19 个可独立维护的字段；限制日常回复长度，并支持拆成多条短消息；加强虚拟身份相关问题与自述的拦截。旧版默认提示词中的长回复文案会精准迁移，保留其它编辑。保留此前的中转站兼容性修复。

这是未经 Apple 公证的临时签名测试版。macOS 可能阻止运行，且不保证一定出现“仍要打开”。请勿关闭 Gatekeeper；如果无法启动，请向发布者提供 macOS 版本、提示原文和 `spctl --assess --type execute -vv "/Applications/LINE 情感机器人.app"` 的输出。稳定跨设备分发需要 Developer ID 签名和 Apple 公证。
