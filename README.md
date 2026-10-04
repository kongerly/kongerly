<h1 align="center">Kongerly</h1>

<p align="center">
  <strong>后端开发 · AI 工程</strong><br />
  用 Go、Python 和 C#/.NET 构建小而完整、可测试的系统
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C%23%20%2F%20.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C# / .NET" />
</p>

---

## 👋 关于我

我在学习后端开发与 AI 工程，关注 API 设计、日志、测试、CI 和清晰的系统边界。除了从零搭建可测试的服务端项目，也通过一个 Windows 桌面工具练习从实现、测试到打包发布、隐私边界与更新分发的完整链路。

## 🚀 项目

### [ArgusGate](https://github.com/kongerly/ArgusGate) <sub>Go · v0.1 · Phase 1 进行中</sub>

兼容 OpenAI 接口的 AI 推理网关，位于 AI 应用与 llama.cpp、vLLM 等独立推理服务之间。基础服务已完成：严格 JSON 配置加载与校验、`GET /healthz`、Request ID、结构化请求日志、信号驱动的优雅关闭和 CI。Phase 1 的单后端非流式代理组件（请求体限长读取、请求探针校验、上游请求转发与 header 过滤）已实现并通过单元测试，尚在接入 `/v1/chat/completions`。

### [TalosDesk](https://github.com/kongerly/TalosDesk) <sub>C# · .NET 10 · Windows</sub>

面向 Windows 的本地项目运行工作台：保存常用命令，一键运行，集中查看状态与输出。包含命令分组与批量启动、服务命令的本机 TCP 就绪探测、本机加密保存的敏感环境变量、按批次保留的日志策略，以及默认关闭的更新检查和只存本机的崩溃诊断。已发布内置 .NET 运行时的便携包，最新稳定版 **v0.2.0**；源码正在推进 v0.3.0。

### [AetherLab](https://github.com/kongerly/AetherLab) <sub>Python · FastAPI · Pre-Alpha</sub>

模块化 AI 工程平台。Phase 0 已完成并通过本地及远端 CI 验收：FastAPI 服务、健康检查、配置校验、统一错误响应、请求 ID、结构化 JSON 日志和 GitHub Actions 工作流；LLM、RAG 与 Agent 能力仍在路线图中。

## 🧭 关注方向

`后端工程`　`AI 基础设施`　`Go`　`Python`　`C# / .NET`
