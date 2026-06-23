# Nexus

### ⚠️ This project has moved to [niki914/agentic-nexus](https://github.com/niki914/agentic-nexus)

If you like it, please give us a [Star](https://github.com/niki914/agentic-nexus) ⭐

For the old Breeno Source Changer source code, see the [breeno-source-changer](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/tree/breeno-source-changer) branch

Telegram Community: [Telegram](https://t.me/+ZPX2xtSl6RwyZGNl)

> Plug your own model into your phone's voice assistant, and let it actually get things done for you

[![stars](https://img.shields.io/github/stars/Xposed-Modules-Repo/com.niki914.nexus.agentic?label=stars)](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic)
[![release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.niki.breeno.openai?include_prereleases)](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic)
[![downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.niki.breeno.openai/total)](https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic)

<table align="center">
<tr>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/gh_mcp.gif?raw=true" alt="gh_mcp" width="200"/></td>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/hyper.gif?raw=true" alt="hyper" width="200"/></td>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/magisk.gif?raw=true" alt="magisk" width="200"/></td>
</tr>
</table>

Nexus hands the voice assistant you use every day back to you: you decide which model it runs, how it thinks, and what it can do. It is no longer a fixed program that can only check the weather or set alarms, but an Agent that truly belongs to you — say a single sentence, and it can orchestrate your entire phone to get it done.

> Currently in Beta — capabilities and stability are being continuously improved. Source code is not yet public.

### Why It's Worth Trying

It's an Agent. Ordinary AI apps stop at "swap the model's answers." What Nexus is doing is different —

<table align="center">
<tr>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/agentic/termux_long_en.jpg?raw=true" alt="termux" width="200"/></td>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/agentic/headless_cc_en.jpg?raw=true" alt="cc" width="200"/></td>
<td align="center" valign="middle"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.nexus.agentic/blob/main/res/agentic/skill_long_en.jpg?raw=true" alt="skill" width="200"/></td>
</tr>
</table>

- **Skills System**: The gateway to Agent applications — bringing more possibilities to your assistant
- **MCP**: Freely plug in tool sets — Notion, GitHub, HomeKit... your resources define the ceiling
- **Takeover Rules**: You define when the Agent should step in and take over, and when to let the system assistant set alarms
- **Memory System**: Remembers your preferences, even across new conversations
- **Conversation History**: Browse and replay any conversation. Every step of your Agent's growth is traceable

**Built Deeply into Android**

This is where Nexus pulls away from being just another ChatBot —

- **Terminal, Three Tiers**: Normal app permissions -> [Shizuku](https://github.com/rikkaapps/shizuku) -> Root
- **SSH, Bridging Two Worlds**: Connect to [Termux](https://github.com/termux/termux-app), and your Android gains a Linux environment; connect to your dev machine, and the Agent can operate your workstation

But the key isn't even these capabilities themselves — it's that **you don't need to understand the terminal**. Tell the Agent what you want to do, and it writes its own commands, executes them, and handles the results. All you need is the outcome.

This unlocks the ultimate play: **connect [claude-code](https://github.com/anthropics/claude-code) for headless AI Coding** — the Agent on your phone commands cc to do the work, code runs on the remote machine, done in a single sentence. If you know, you know.

### Technical Foundation

AI Conversations & Tooling: [s3ss10n](https://github.com/niki914/s3ss10n)
UI: Material3 × [Liquid Glass](https://github.com/Kyant0/AndroidLiquidGlass)
Shell & SSH Terminal: [libterm](https://github.com/niki914/libterm)

### Compatibility

- Adapted for mainstream voice assistants (e.g., Breeno, XiaoAi), with more adaptations ongoing
- When the current device does not yet support takeover, you can still use Nexus's built-in chat interface
- Supports DeepSeek, OpenAI, Anthropic, Google and other models, as well as compatible API endpoints
- Bring your own API key — Nexus does not bundle model accounts

### Feedback

When submitting feedback, please include the following when possible:

- Phone model and system version
- Voice assistant type in use
- Assistant version and Nexus version
- Steps to reproduce, screenshots, or screen recordings
- Relevant logs if available

Community and feedback entry points are as shown on the "About" page within the app.
