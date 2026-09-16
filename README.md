# 🤖 Awesome DevOps AI

> **Curated list of AI tools, skills, and resources for DevOps/SRE teams.** The intersection of AI and infrastructure operations.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Inspired by [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted), [awesome-sre](https://github.com/dastergon/awesome-sre), and the explosion of AI coding assistants in 2025-2026.

## Why this list exists

AI coding assistants (Claude Code, Cursor, Copilot) are incredible at writing React components. But ask them to review a Kubernetes manifest for security issues, or write a Prometheus alert rule that doesn't cause alert fatigue, and they give you generic advice.

This list curates the tools, skills, and resources that bridge the gap between AI assistants and real infrastructure operations.

---

## Contents

- [🤖 AI Skills & Prompts](#-ai-skills--prompts)
- [🧠 AI-Powered Monitoring](#-ai-powered-monitoring)
- [🚨 AI Incident Response](#-ai-incident-response)
- [🔐 AI Security Tools](#-ai-security-tools)
- [🏗 IaC + AI](#-iac--ai)
- [📝 AI Documentation](#-ai-documentation)
- [🔌 MCP Servers for Infrastructure](#-mcp-servers-for-infrastructure)
- [📚 Learning Resources](#-learning-resources)

---

## 🤖 AI Skills & Prompts

Curated skills, rules files, and prompt packs that make AI coding assistants better at DevOps tasks.

- [ops-skills](https://github.com/tomlen045/ops-skills) — 10 battle-tested AI skills for DevOps/SRE: incident response, k8s security, Linux hardening, Prometheus, Terraform review, log analysis, Docker, postmortem, runbook, diagram gen.
- [awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) — Curated .cursorrules files for different frameworks and languages.
- [Claude-Code-Instructions](https://github.com/anthropics/claude-code) — Official Claude Code documentation including custom instructions.
- [ai-tone-remover](https://github.com/) — An AI-tone removal skill grounded in a corpus study. Makes AI-written docs sound human.

## 🧠 AI-Powered Monitoring

Tools that use AI/ML to improve monitoring, alerting, and observability.

- [Keep](https://github.com/keephq/keep) — Open-source alert management with AI-powered alert enrichment and deduplication.
- [Robusta](https://github.com/robusta-dev/robusta) — Kubernetes observability with AI-powered root cause analysis.
- [HolmesGPT](https://github.com/robusta-dev/holmesgpt) — Your 24/7 AI-powered DevOps teammate. Investigates alerts, queries data, suggests fixes.
- [k8sgpt](https://github.com/k8sgpt-ai/k8sgpt) — AI-powered Kubernetes debugging. Scans clusters and diagnoses issues in plain English.
- [OpenTelemetry AI Processor](https://github.com/) — Community efforts to add AI enrichment to OTel pipelines.

## 🚨 AI Incident Response

AI tools that help during and after production incidents.

- [incident.io](https://incident.io/) — AI-powered incident management platform (SaaS).
- [FireHydrant](https://firehydrant.com/) — Incident response with AI-suggested action items.
- [Rootly](https://rootly.com/) — AI-assisted incident management and retrospectives.
- [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) — Event intelligence and auto-remediation.
- [Postmortem AI](https://github.com/) — Auto-generate postmortem drafts from incident timelines.

## 🔐 AI Security Tools

AI-enhanced security scanning, threat detection, and compliance.

- [Semgrep AI](https://semgrep.dev/) — Static analysis with AI-powered findings prioritization.
- [Snyk DeepCode AI](https://snyk.io/platform/deepcode-ai/) — AI-powered SAST with fix suggestions.
- [CrowdStrike Falcon AI](https://www.crowdstrike.com/platform/ai-powered-security/) — AI-native endpoint detection.
- [Trivy AI](https://trivy.dev/) — Container/IaC scanning with AI context.

## 🏗 IaC + AI

AI-assisted Infrastructure as Code generation, review, and management.

- [Terraform CDK AI](https://github.com/) — AI-assisted CDKTF stack generation.
- [Pulumi AI](https://www.pulumi.com/ai/) — Generate cloud infrastructure from natural language.
- [Firefly](https://firefly.ai/) — AI-powered cloud asset inventory and drift detection.
- [env0 AI](https://www.env0.com/) — AI-assisted Terraform state management and drift remediation.
- [ControlMonkey](https://controlmonkey.io/) — AI-powered Terraform automation and drift detection.

## 📝 AI Documentation

AI tools that generate and maintain technical documentation.

- [Swimm AI](https://swimm.io/) — AI-coupled documentation that stays in sync with code.
- [Mintlify Writer](https://mintlify.com/writer) — AI-powered documentation generation from code.
- [Backstage + AI](https://backstage.io/) — Community efforts to add AI-powered service catalog intelligence.
- [ADR-Gen](https://github.com/) — Auto-generate Architecture Decision Records from git history.

## 🔌 MCP Servers for Infrastructure

Model Context Protocol (MCP) servers that give AI assistants access to infrastructure tools.

- [MCP Kubernetes](https://github.com/) — MCP server for kubectl/helm interactions.
- [MCP Terraform](https://github.com/) — MCP server for Terraform state and plan management.
- [MCP Prometheus](https://github.com/) — MCP server for PromQL queries and metric exploration.
- [MCP AWS](https://github.com/) — MCP server for AWS CLI/SDK interactions.
- [MCP Grafana](https://github.com/) — MCP server for Grafana dashboard queries.

## 📚 Learning Resources

Courses, guides, and books at the intersection of AI and DevOps.

- [Prompt Engineering for DevOps](https://github.com/) — Practical guide to writing effective prompts for infra tasks.
- [AI for SRE](https://www.oreilly.com/) — O'Reilly book on AI-assisted site reliability engineering.
- [LLM Ops](https://github.com/) — Operationalizing LLMs in production: the infra perspective.

---

## Contributing

Found a tool that belongs here? PR it!

Requirements:
1. Must be at the intersection of AI and DevOps/Infrastructure
2. Must be actively maintained (last commit < 6 months ago) OR be a stable reference
3. Include a one-line description that explains WHY it's useful
4. Star count is nice but not required — quality over popularity

## License

CC0 1.0 (Public Domain)
---

<div align="center">

### 🫰 点击关注「小薅薅」

**年轻人的赛博工具箱** · 每天发现一个好玩的开源项目，为你节省 1 小时

📱 微信搜索公众号 **「小薅薅」** · 后台回复「工具」获取全部工具离线合集


</div>

> 💡 如果你懒得一个个翻项目，直接关注微信公众号 **小薅薅**，后台对话聊天就行了：
> - 回复「**运维**」→ 推荐运维/安全相关的开源项目
> - 回复「**工具**」→ 获取全部工具离线合集
> - 回复「**加群**」→ 加入交流群，一起搞事情

---

### 🔗 更多作品 · 点下方卡片查看

| 项目 | 描述 | 链接 |
|:---|:---|:---|
| **🛡 ops-skills** | 10个AI运维技能包，让Claude Code变成SRE专家 | [GitHub](https://github.com/tomlen045/ops-skills) · [Gitee](https://gitee.com/tomlen/ops-skills) |
| **🩺 ops-doctor** | 一条命令给Linux服务器做全套体检+健康分 | [GitHub](https://github.com/tomlen045/ops-doctor) · [Gitee](https://gitee.com/tomlen/ops-doctor) |
| **🔮 shellmbti** | 你的终端历史暴露了你是谁——Shell MBTI人格测试 | [GitHub](https://github.com/tomlen045/shellmbti) · [Gitee](https://gitee.com/tomlen/shellmbti) |
| **🧋 naicha-mbti** | 8道题测出你的奶茶人格，生成分享卡片 | [GitHub](https://github.com/tomlen045/naicha-mbti) · [在线玩](https://tomlen045.github.io/naicha-mbti/) |
| **🔥 fafa-generator** | 发疯文学生成器——一键生成发疯文案+卡片 | [GitHub](https://github.com/tomlen045/fafa-generator) · [在线玩](https://tomlen045.github.io/fafa-generator/) |
| **⏳ life-progress** | 人生进度条——把你的时间摆在眼前 | [GitHub](https://github.com/tomlen045/life-progress) · [在线玩](https://tomlen045.github.io/life-progress/) |
| **🪵 gongde-tap** | 电子木鱼功德计数器——赛博积德 | [GitHub](https://github.com/tomlen045/gongde-tap) · [在线玩](https://tomlen045.github.io/gongde-tap/) |
| **💞 mbti-match** | MBTI灵魂配对——神仙组合还是塑料同窗 | [GitHub](https://github.com/tomlen045/mbti-match) · [在线玩](https://tomlen045.github.io/mbti-match/) |

---

<div align="center">

**🎯 更多宝藏工具 · 手机点开即玩**

[🧋 奶茶MBTI](https://tomlen045.github.io/naicha-mbti/) | [🔥 发疯文学](https://tomlen045.github.io/fafa-generator/) | [⏳ 人生进度条](https://tomlen045.github.io/life-progress/) | [🪵 电子功德](https://tomlen045.github.io/gongde-tap/) | [💞 MBTI配对](https://tomlen045.github.io/mbti-match/)

**⭐ 觉得有用？给个 Star 让更多人看到 →**

[![GitHub](https://img.shields.io/github/stars/tomlen045?style=social)](https://github.com/tomlen045)

</div>
