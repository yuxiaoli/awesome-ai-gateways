# Awesome AI Gateways

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

**English** | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-HK.md)

A curated collection of AI and LLM API gateways, provider aggregators, model routers, and protocol proxies for unified access to AI models.

## General-Purpose LLM Gateways

Multi-provider gateways that consolidate model or upstream API services behind a unified interface, offering routing, API compatibility, or operational controls.

- [Octopus](https://github.com/bestruirui/octopus) - Personal LLM API aggregation gateway with multiple upstream channels, protocol conversion, model groups, and automatic failover.
- [Metapi](https://github.com/cita-777/metapi) - Meta-gateway that combines AI relay services and compatible endpoints into one API entry, with model discovery and cost-aware routing.
- [LiteLLM](https://github.com/BerriAI/litellm) - LLM SDK and deployable AI gateway with a unified API for many providers, load balancing, virtual keys, spend tracking, and guardrails.
- [FreeLLMAPI](https://github.com/tashfeenahmed/freellmapi) - Aggregates free-tier and custom LLM endpoints behind an OpenAI-compatible API, with provider failover, usage tracking, and encrypted keys.

## AI Coding Tool Gateways & Proxies

Routing and proxy tools for connecting AI coding assistants to model providers or subscriptions, including protocol translation, account management, and fallback.

- [9Router](https://github.com/decolua/9router) - Routes AI coding tools to multiple model providers through an OpenAI-compatible endpoint, with automatic fallback and token-saving features.
- [CC Switch](https://github.com/farion1231/cc-switch) - Desktop provider manager with optional local request routing, API format conversion, failover, and aggregation for AI coding tools.
- [Antigravity Tools](https://github.com/lbjlaq/Antigravity-Manager) - Multi-account manager with an AI API proxy exposing OpenAI- and Anthropic-compatible endpoints, model mapping, and account dispatch.
- [CLI Proxy API](https://github.com/router-for-me/CLIProxyAPI) - Proxy server exposing OpenAI-, Gemini-, Claude-, Codex-, and Grok-compatible APIs for CLI-based model accounts, with multi-account load balancing.
- [Code Switch](https://github.com/daodao97/code-swtich) - Claude Code and Codex provider manager using a local HTTP proxy for request forwarding, provider priorities, and automatic failover.
