<div align="center">
  <img src="assets/teapot-mark.svg" width="116" alt="Teapot Router — a clay seal with a forest-green teapot" />
</div>

<h3 align="center">Teapot Router</h3>

<p align="center">
  <strong>Stability-first AI gateway for Claude Code and GPT.</strong><br/>
  One key, both protocols. Pay-as-you-go. Balance never expires.<br/>
  <sub>快，到处都有。稳，很少见。</sub>
</p>

<p align="center">
  <a href="https://teapotrouter.com">Website</a> ·
  <a href="https://teapotrouter.com/en/docs">Docs</a> ·
  <a href="https://teapotrouter.com/api/pricing">Pricing JSON</a> ·
  <a href="https://teapotrouter.com/en/status">Status</a> ·
  <a href="https://teapotrouter.com/en/blog">Blog</a>
</p>

---

## Connect in two lines

**Claude Code** — point two env vars at the gateway:

```bash
export ANTHROPIC_BASE_URL="https://api.teapotrouter.com"
export ANTHROPIC_AUTH_TOKEN="rl_your_token"
```

**OpenAI SDK / Codex** — change one base URL:

```python
client = OpenAI(
  base_url="https://api.teapotrouter.com/v1",
  api_key="rl_your_token",
)
```

Ready-made config files: **[teapot-router-config](https://github.com/teapot-router/teapot-router-config)**.

## What you get

| | |
|---|---|
| 🔀 **Dual protocol** | Anthropic-format clients (Claude Code) and OpenAI-format clients (SDK, Codex) hit the same key |
| 🛟 **Automatic failover** | If an upstream channel fails, requests retry on a configured backup |
| 🧾 **Per-request cost ledger** | Model, tokens, rate and charge logged for every request — reconcilable |
| 💳 **Pay-as-you-go** | Prepaid balance, no subscription, **balance never expires** |
| 🔬 **Model Lab** | Test models on real tasks before committing budget — free demo workspace, no account needed |
| 🌍 **Seven languages** | 中文 / EN / 日本語 / 한국어 / Español / Français / Português |

条款是我们最在意的产品部分：按剩余余额退款（手续费平台承担）、价格表与机读接口全公开。

## Multilingual landing repos

| Language | Repo |
|---|---|
| 日本語 | [teapot-router-ja](https://github.com/teapot-router/teapot-router-ja) |
| 한국어 | [teapot-router-ko](https://github.com/teapot-router/teapot-router-ko) |
| Español | [teapot-router-es](https://github.com/teapot-router/teapot-router-es) |
| Français | [teapot-router-fr](https://github.com/teapot-router/teapot-router-fr) |
| Português | [teapot-router-pt](https://github.com/teapot-router/teapot-router-pt) |

## About the forks

本 org 名下的 fork（awesome-* 系列等）均为向对应开源清单**提交收录 PR** 所需的工作副本，与上游项目无关；Teapot Router 自身的核心服务闭源运行于 [teapotrouter.com](https://teapotrouter.com)。

桌面端配套：**[Keyway](https://github.com/anmutu/keyway)** — AI CLI 的本地网关（开源，Rust + Tauri）。

---

<p align="center">
  <sub>The name tips its hat to HTTP status code <b>418 “I'm a teapot”</b> 🫖 — a teapot doesn't grow tea, it pours it.<br/>
  <a href="https://teapotrouter.com/zh/418">418 小史</a> · RFC 2324, the 1998 April Fools' easter egg</sub>
</p>
