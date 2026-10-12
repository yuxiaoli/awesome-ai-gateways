# Awesome AI 网关

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

[English](README.en.md) | **简体中文** | [繁體中文](README.zh-HK.md)

精选 AI 与大语言模型 API 网关、服务商聚合器、模型路由器和协议代理项目，用于统一接入 AI 模型。

## 通用 LLM 网关

汇聚多家模型服务商或上游 API 服务的通用网关，提供统一接口以及路由、协议兼容或运行管理能力。

- [Octopus](https://github.com/bestruirui/octopus) - 面向个人的 LLM API 聚合网关，支持多上游渠道、协议转换、模型分组和自动故障切换。
- [Metapi](https://github.com/cita-777/metapi) - 将多个 AI 中转站及兼容接口整合为统一 API 入口的元聚合网关，支持模型自动发现和成本优先路由。
- [LiteLLM](https://github.com/BerriAI/litellm) - 提供统一多模型接口的 LLM SDK 与可部署 AI 网关，支持负载均衡、虚拟密钥、费用跟踪和安全防护。
- [FreeLLMAPI](https://github.com/tashfeenahmed/freellmapi) - 将免费额度与自定义 LLM 接口汇聚为 OpenAI 兼容 API，支持服务商故障切换、用量跟踪和密钥加密存储。

## AI 编程工具网关与代理

面向 AI 编程助手的路由和代理工具，用于连接模型服务商或账号订阅，并提供协议转换、账号管理或故障回退。

- [9Router](https://github.com/decolua/9router) - 通过 OpenAI 兼容接口将 AI 编程工具连接到多个模型服务商，支持自动故障回退和节省 Token 的功能。
- [CC Switch](https://github.com/farion1231/cc-switch) - 面向 AI 编程工具的桌面服务商管理器，提供可选的本地请求路由、API 格式转换、故障回退和聚合模式。
- [Antigravity Tools](https://github.com/lbjlaq/Antigravity-Manager) - 多账号管理与 AI API 代理工具，提供 OpenAI 和 Anthropic 兼容接口、模型映射及账号调度。
- [CLI Proxy API](https://github.com/router-for-me/CLIProxyAPI) - 将 CLI 模型账号转换为 OpenAI、Gemini、Claude、Codex 和 Grok 兼容 API 的代理服务器，支持多账号负载均衡。
- [Code Switch](https://github.com/daodao97/code-swtich) - 面向 Claude Code 和 Codex 的服务商管理工具，通过本地 HTTP 代理实现请求转发、渠道优先级和自动故障回退。
