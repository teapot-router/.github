# Teapot Router

**Stability-first AI gateway for Claude Code and GPT — 快，到处都有。稳，很少见。**

One key, both protocols: Claude Code connects via `ANTHROPIC_BASE_URL` + `ANTHROPIC_AUTH_TOKEN`, OpenAI SDK / Codex via `base_url /v1`. Pay-as-you-go, public pricing, automatic upstream failover, per-request cost ledger.

条款是我们最在意的产品部分：**余额永不过期**、按剩余余额退款（手续费平台承担）、价格表与机读接口全公开。

## 链接 / Links

- 官网 Website: [teapotrouter.com](https://teapotrouter.com)（中文 / EN / 日本語 / 한국어 / Español / Français / Português）
- 接入模板 Config templates: [teapot-router-config](https://github.com/teapot-router/teapot-router-config) — Claude Code / OpenAI SDK 两行环境变量接入
- 价格（免登录机读 JSON）: [teapotrouter.com/api/pricing](https://teapotrouter.com/api/pricing)
- 文档 Docs: [teapotrouter.com/zh/docs](https://teapotrouter.com/zh/docs)（注册→建 Key→首次调用，全流程排错）
- 桌面端配套 Desktop companion: [Keyway](https://github.com/anmutu/keyway) — AI CLI 的本地网关（开源，Rust + Tauri）

## 语言落地页 / Multilingual landing repos

| Language | Repo |
|---|---|
| 日本語 | [teapot-router-ja](https://github.com/teapot-router/teapot-router-ja) |
| 한국어 | [teapot-router-ko](https://github.com/teapot-router/teapot-router-ko) |
| Español | [teapot-router-es](https://github.com/teapot-router/teapot-router-es) |
| Français | [teapot-router-fr](https://github.com/teapot-router/teapot-router-fr) |
| Português | [teapot-router-pt](https://github.com/teapot-router/teapot-router-pt) |

## 关于本 org 的 forks / About the forks

本 org 名下的 fork（awesome-* 系列等）均为向对应开源清单**提交收录 PR** 所需的工作副本，与上游项目无关；Teapot Router 自身的核心服务闭源运行于 [teapotrouter.com](https://teapotrouter.com)。

名字与 logo 源自 HTTP 状态码 418 "I'm a teapot" 🫖 —— [418 小史](https://teapotrouter.com/zh/418)
