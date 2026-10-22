[English](README.md) · **中文**

# 曹亚仑 · Allen Galler

阿里云 SRE，坐标深圳，2010 年注册 GitHub。

白天做云原生基础设施的稳定性，业余时间写工具、攒知识库。我写的东西大多按“读两遍”的标准来写：一遍给人看，一遍给 Agent 当 RAG 语料。

[![个人网站](https://img.shields.io/badge/allengaller.github.io-000000?style=flat-square&logo=safari&logoColor=white)](https://allengaller.github.io)
[![100+ 仓库 · 20+ 组织](https://img.shields.io/badge/100%2B_repos-20%2B_orgs-000000?style=flat-square)](https://allengaller.github.io/repos/)
[![Followers](https://img.shields.io/github/followers/allengaller?style=flat-square&logo=github)](https://github.com/allengaller?tab=followers)

## 在做什么

- **agent-up** —— Agent 持续改进的闭环：反馈 → 归因 → 发布 → 一键回滚
- **KUDIG / ResolveAgent** —— 把运维工具的运行轨迹整理成结构化、Agent 可读的知识库
- **open-geo** —— 关于生成式引擎优化（GEO）的研究笔记

## Agent 项目

| 项目 | 简介 |
|---|---|
| [resolve-agent](https://github.com/ai-guru-global/resolve-agent) | 基于 AgentScope 的生产级产品支持智能体平台：按故障特征在 FTA 故障树、Wiki 知识库、技能与代码分析之间智能路由，已落地 432 个场景 |
| [agent-up](https://github.com/ai-guru-global/agent-up) | Agent 配置全生命周期管理：编辑、审批发布、效果追踪到回滚的完整闭环，用户反馈经 AI 归因自动转化为配置变更建议 |
| docsy（私有） | 面向 Agent 时代的文档平台：把 Markdown 重构为机器可解析、可校验的研究包，14 条 Linter 规则加健康评分，实测撑住 21,000 篇文档的大仓库 |
| sokr（私有） | 运维团队的 OKR 与复盘沉淀工具：把故障复盘转化成可毕业的团队技能资产，纯浏览器运行零部署 |
| [mcp-database](https://github.com/standup-coder/mcp-database) | 自托管 MCP Server 统一框架（mcp4coder）：37 个 Server、200 多个工具收敛进一套基类，新增一个 Server 只需实现两个方法 |
| [skills-database](https://github.com/standup-coder/skills-database) | 职业技能与 Skills 技能融合平台：455 条技能覆盖 27 个职业角色，来源可溯，单文件离线可浏览 |

## AI Infra 项目

| 项目 | 简介 |
|---|---|
| [kudig-database](https://github.com/kudig-io/kudig-database) | K8s 与 AI Infra 生产运维全域知识库：4,750 篇文档覆盖 21 个技术域和 13 家云厂商，故障树引擎沉淀 16 个顶层事件、约 300 个底事件 |
| [ai-guru-database](https://github.com/ai-guru-global/ai-guru-database) | 中文 AI 全栈开源知识库：2,061 篇核心文档约 1,894 万字，700 多张概念卡，从数学基础到 Agent 生产部署 |
| [klaw](https://github.com/kudig-io/klaw) | 单二进制 K8s 智能运维平台：一个文件装下控制台、诊断引擎、ChatOps、实时告警和 SOS 语音五种能力，73 个分析器，事件推送低于 1 秒 |
| [etcd-guardian](https://github.com/kudig-io/etcd-guardian) | etcd 备份恢复的 Kubernetes Operator：补上 Velero 在托管集群够不到 etcd 数据面的盲区，对阿里云 ACK 开箱即用，可作为 module 接入 klaw |
| [kubernetes-network-master](https://github.com/kudig-io/kubernetes-network-master) | 单二进制 K8s 网络排障工具（kubectl 插件）：逐跳因果链追踪，从 DNS 一直查到 CNI 并自动标记断点，20 多个子命令，内置轻量 eBPF |

## TAM 项目

| 项目 | 简介 |
|---|---|
| [open-tam](https://github.com/open-labor/open-tam) | 基于 AgentScope 与 MCP 的多 Agent 排障系统：输出带现象、根因、处置建议的三段式报告，每一步落盘为可回放 trace，故障注册表同时就是评测集 |
| [kuba-database](https://github.com/kudig-io/kuba) | 全网重大生产故障复盘数据库：94 个 P0/P1 级真实案例，横跨 46 年、47 家公司，归纳出 12 类根因，按 SRE / CRE / FDE / SA 四种视角拆解 |
| [cmd-database](https://github.com/standup-coder/cmd-database) | 命令行语料数据库：1,100 多个命令各建一页，配套 741 篇生产最佳实践，从 YAML 单一来源生成，Go CLI 检索校验 |
| [open-arch](https://github.com/allengaller/open-arch) | 售前架构师工作显性化工具箱（AgentScope 2.0 架构设计 Copilot）：需求澄清、方案设计、架构图到评审、交付文档五步闭环 |
| [open-demo](https://github.com/open-labor/opendemo-work) | 面向售前、交付和产品经理的演示平台：959 个可运行案例覆盖 18 个技术栈，每个案例自带架构图、三千字教程和可运行产物 |
| [fde-scope](https://github.com/ai-guru-global/fde-scope) | FDE 前线部署工程师的现场操作系统：4 个阶段、18 个环节、10 道代码级门禁，其中 7 道来自 FAT、ISO 13849、CE 等工业标准 |
| [repo-database](https://github.com/allengaller/repo-database) | 面向 FDE 的优质仓库兵器库：每月扫描 1,000 多个仓库，精选沉淀 115 篇结构化档案，每篇经 CI 门禁校验 |

100+ 仓库、20+ 组织的完整索引：[allengaller.github.io/repos](https://allengaller.github.io/repos/)

## 其他地方

- [allengaller.github.io](https://allengaller.github.io) —— 大本营
- [项目](https://allengaller.github.io/projects/) · [仓库索引](https://allengaller.github.io/repos/) · [链接](https://allengaller.github.io/topic/links/)

## 合作

比较对口的方向：要真正上生产的 Agent / RAG / MCP / CLI 工具；围绕 Kubernetes、可观测性和故障分析的方案设计；把零散文档整理成能持续积累的知识库。最快的联系方式是在对应仓库开 Issue。

<sub>© 曹亚仑 · 深圳</sub>
