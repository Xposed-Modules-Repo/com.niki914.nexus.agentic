# Nexus

> [!IMPORTANT]
> 本项目已迁移至 **[niki914/agentic-nexus](https://github.com/niki914/agentic-nexus)**，下载、文档与源码请前往主仓库。
>
> This project has moved to **[niki914/agentic-nexus](https://github.com/niki914/agentic-nexus)** — downloads, docs and source live in the main repo.

[![stars](https://img.shields.io/github/stars/Xposed-Modules-Repo/com.niki914.nexus.agentic?label=stars)](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic)
[![release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.niki914.nexus.agentic?include_prereleases)](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/releases/latest)
[![downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.niki914.nexus.agentic/total)](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/releases/latest)

<table align="center">
<tr>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/gh_mcp.gif?raw=true" alt="gh_mcp" width="200"/></td>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/hyper.gif?raw=true" alt="hyper" width="200"/></td>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/magisk.gif?raw=true" alt="magisk" width="200"/></td>
</tr>
</table>

> 将 Android 系统语音助手连接到你自己的模型，并赋予它调用工具、执行任务和操作设备的能力。
>
> Connect your phone's system voice assistant to your own model, and give it the ability to call tools, execute tasks, and operate your device.

Nexus 是一个面向 Android 的可扩展语音 Agent。它可以接管部分系统语音助手入口（目前适配小布助手、小爱同学，依赖 Root + [LSPosed](https://github.com/lsposed/lsposed)），将语音请求交给自定义模型处理，并通过 Skills、MCP、Shell 和 SSH 等能力完成实际任务。设备暂不支持接管时，仍可使用 Nexus 内置的对话界面与全部 Agent 能力。

Nexus is an extensible voice Agent for Android. It can take over system voice assistant entry points (currently OPPO/OnePlus/Realme Breeno and Xiaomi XiaoAi, requires Root + [LSPosed](https://github.com/lsposed/lsposed)), hand your voice requests to a custom model, and complete real tasks through Skills, MCP, Shell, and SSH. When takeover is not yet supported on your device, Nexus's built-in chat interface with full Agent capabilities still works.

- 源码 / Source: [niki914/agentic-nexus](https://github.com/niki914/agentic-nexus)
- 下载 / Download: [Releases](https://github.com/niki914/agentic-nexus/releases/latest)
- 交流群 / Community: [Telegram](https://t.me/+ZPX2xtSl6RwyZGNl)
- 旧版源码 / Legacy source: [breeno-source-changer](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/tree/breeno-source-changer)
