# Loviqo Skill

[English](README.md) | 简体中文

把 Loviqo 笔记 / 录音 / 待办接到 Claude Code、Codex、Cursor、ChatGPT、Claude 等。

数据面是托管 MCP：`https://api.loviqo.com/mcp`（**默认 OAuth 浏览器登录，无需配置 API Key**）。

## 一句话安装（给终端用户复制）

```
从 https://github.com/totwoo2015-droid/loviqo-skill 安装 Loviqo 技能，并接入我的笔记库
```

1. 打开 Claude Code（桌面端）
2. 粘贴上面的指令并发送
3. 按提示在浏览器完成 Loviqo 登录授权
4. 连接成功后即可搜索和使用你的笔记库

如果首次未自动启用，可在 Skills 或工具列表中确认「Loviqo」已开启。

## MCP 地址

```
https://api.loviqo.com/mcp
```

鉴权优先 **OAuth**。仅当客户端无法打开浏览器时，才使用 App 设置页生成的 API Key。

## License

MIT
