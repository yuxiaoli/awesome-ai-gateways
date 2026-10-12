# Awesome AI 網關

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

[English](README.en.md) | [简体中文](README.zh-CN.md) | **繁體中文**

精選 AI 與大型語言模型 API 網關、供應商聚合器、模型路由器及協定代理專案，協助統一存取 AI 模型。

## 通用 LLM 網關

彙集多家模型供應商或上游 API 服務的通用網關，提供統一介面，以及路由、協定相容或營運管理功能。

- [Octopus](https://github.com/bestruirui/octopus) - 面向個人使用的 LLM API 聚合網關，支援多個上游渠道、協定轉換、模型分組及自動故障切換。
- [Metapi](https://github.com/cita-777/metapi) - 將多個 AI 中轉站及相容介面整合成統一 API 入口的元聚合網關，支援自動探索模型及成本優先路由。
- [LiteLLM](https://github.com/BerriAI/litellm) - 提供統一多模型介面的 LLM SDK 及可部署 AI 網關，支援負載平衡、虛擬密鑰、費用追蹤及安全防護。
- [FreeLLMAPI](https://github.com/tashfeenahmed/freellmapi) - 將免費額度及自訂 LLM 介面彙集為 OpenAI 相容 API，支援供應商故障切換、用量追蹤及密鑰加密儲存。

## AI 程式開發工具網關與代理

面向 AI 程式開發助手的路由及代理工具，用於連接模型供應商或訂閱帳戶，並提供協定轉換、帳戶管理或故障備援。

- [9Router](https://github.com/decolua/9router) - 透過 OpenAI 相容介面將 AI 程式開發工具連接至多個模型供應商，支援自動故障備援及節省 Token 的功能。
- [CC Switch](https://github.com/farion1231/cc-switch) - 面向 AI 程式開發工具的桌面供應商管理器，提供可選的本地請求路由、API 格式轉換、故障備援及聚合模式。
- [Antigravity Tools](https://github.com/lbjlaq/Antigravity-Manager) - 多帳戶管理及 AI API 代理工具，提供 OpenAI 和 Anthropic 相容介面、模型映射及帳戶調度。
- [CLI Proxy API](https://github.com/router-for-me/CLIProxyAPI) - 將 CLI 模型帳戶轉換為 OpenAI、Gemini、Claude、Codex 及 Grok 相容 API 的代理伺服器，支援多帳戶負載平衡。
- [Code Switch](https://github.com/daodao97/code-swtich) - 面向 Claude Code 及 Codex 的供應商管理工具，透過本地 HTTP 代理實現請求轉發、渠道優先次序及自動故障備援。
