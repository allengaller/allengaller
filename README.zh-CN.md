[English](README.md) · **中文**

# 曹亚仑 · Allen Galler

阿里云 SRE，坐标深圳。2010 年注册 GitHub，至今 700+ 个公开仓库、20+ 个组织。

白天保障云原生基础设施的稳定性，业余时间都在做一个长期实验：把运维经验变成工具和知识库，人能读，Agent 也能直接拿去当 RAG 语料。

几个对应的数字：一个知识库里沉淀了 4,750 篇生产运维文档；432 个支持场景端到端自动化；94 个真实 P0/P1 故障复盘案例；959 个可运行的架构演示。

**时间紧的话，先看这三个：** [resolve-agent](https://github.com/ai-guru-global/resolve-agent)（干真实支持工作的 Agent）、[klaw](https://github.com/kudig-io/klaw)（一个二进制装下一整套 K8s 运维）、[kudig-database](https://github.com/kudig-io/kudig-database)（其他项目都在读的知识库）。

## 在做什么

- **agent-up**：反馈 → 归因 → 发布 → 回滚，一条在生产环境里跑通的 Agent 改进闭环
- **KUDIG / ResolveAgent**：把运维工具的运行轨迹整理成结构化、Agent 可读的知识
- **open-geo**：生成式引擎优化（GEO）的研究笔记

## Agent 项目

| 项目 | 简介 |
|---|---|
| [resolve-agent](https://github.com/ai-guru-global/resolve-agent) | 基于 AgentScope 的支持智能体：按故障特征在 FTA 故障树、Wiki、技能和代码分析之间路由，432 个场景已在生产运行 |
| [agent-up](https://github.com/ai-guru-global/agent-up) | Agent 配置全生命周期：编辑、审批、发布、追踪、回滚。用户反馈经 AI 归因自动变成配置变更建议 |
| docsy（私有） | 面向 Agent 时代的文档平台。Markdown 变成机器可校验的研究包，14 条 Linter 规则加健康评分，在 21,000 篇文档的仓库上实测稳定 |
| sokr（私有） | 运维团队的 OKR 与复盘工具。故障复盘沉淀成可毕业的团队技能资产。零部署，浏览器里直接跑 |
| [mcp-database](https://github.com/standup-coder/mcp-database) | 自托管 MCP Server 框架（mcp4coder）。37 个 Server、200 多个工具共用一套基类，新增 Server 只要实现两个方法 |
| [skills-database](https://github.com/standup-coder/skills-database) | 455 条岗位胜任力技能，覆盖 27 个职业角色。来源可溯，单文件离线可浏览 |

## AI Infra 项目

| 项目 | 简介 |
|---|---|
| [kudig-database](https://github.com/kudig-io/kudig-database) | K8s + AI Infra 运维知识库：4,750 篇文档，21 个技术域，13 家云厂商，外加一个 16 顶层事件、约 300 底事件的故障树引擎 |
| [ai-guru-database](https://github.com/ai-guru-global/ai-guru-database) | 中文 AI 全栈知识库。2,061 篇核心文档约 1,894 万字，700 多张概念卡，从数学基础一路写到 Agent 生产部署 |
| [klaw](https://github.com/kudig-io/klaw) | 一个二进制里装着控制台、诊断引擎、ChatOps 机器人、实时告警和 SOS 语音。73 个分析器，事件推送低于 1 秒 |
| [etcd-guardian](https://github.com/kudig-io/etcd-guardian) | etcd 备份恢复 Operator，补上 Velero 在托管集群够不到 etcd 数据面的盲区。阿里云 ACK 开箱即用，可作为 module 接入 klaw |
| [kubernetes-network-master](https://github.com/kudig-io/kubernetes-network-master) | 单二进制 K8s 网络排障（kubectl 插件）。从 DNS 逐跳因果链一直查到 CNI 并自动标记断点，20 多个子命令，内置轻量 eBPF |

## TAM 项目

| 项目 | 简介 |
|---|---|
| [open-tam](https://github.com/open-labor/open-tam) | 基于 AgentScope + MCP 的多 Agent 排障。输出现象、根因、处置建议三段式报告；每一步都是可回放 trace，故障注册表同时就是评测集 |
| [kuba-database](https://github.com/kudig-io/kuba) | 94 个真实 P0/P1 故障复盘，横跨 46 年、47 家公司，归纳出 12 类根因，每个案例按 SRE、CRE、FDE、SA 四种视角拆解 |
| [cmd-database](https://github.com/standup-coder/cmd-database) | 命令行语料数据库：1,100 多个命令各建一页，配套 741 篇生产实践。从单一 YAML 来源生成，Go CLI 负责检索校验 |
| [open-arch](https://github.com/allengaller/open-arch) | 售前架构师 Copilot（AgentScope 2.0）：澄清、设计、画图、评审、交付五步走完。知识以可审计的 Markdown 技能包存在 |
| [open-demo](https://github.com/open-labor/opendemo-work) | 959 个可运行演示，覆盖 18 个技术栈，给售前、交付和产品经理用。每个案例自带架构图、完整教程和可运行产物 |
| [fde-scope](https://github.com/ai-guru-global/fde-scope) | FDE 前线部署工程师的现场操作系统：4 个阶段、18 个环节、10 道代码级门禁，其中 7 道来自 FAT、ISO 13849、CE |
| [repo-database](https://github.com/allengaller/repo-database) | FDE 的仓库兵器库。每月扫描 1,000 多个仓库，沉淀 115 篇结构化档案，每篇都有 CI 门禁把关 |

其余 700+ 个公开仓库的完整索引：[allengaller.github.io/repos](https://allengaller.github.io/repos/)

## 其他地方

- [allengaller.github.io](https://allengaller.github.io) —— 大本营
- [项目](https://allengaller.github.io/projects/) · [仓库索引](https://allengaller.github.io/repos/) · [链接](https://allengaller.github.io/topic/links/) · [RSS](https://allengaller.github.io/feed.xml)

## 聊聊

生产环境里的 Agent、Kubernetes 故障分析、GEO，这些话题都欢迎交流。项目相关的问题直接在对应仓库开 Issue，我都会看。公开仓库都欢迎 PR；如果哪个项目帮你省了时间，给它点个 star 就是最好的反馈。合作上比较对口的：要真正上生产的 Agent / RAG / MCP / CLI 工具，以及把零散文档沉淀成持续产生价值的知识库。

<sub>© 曹亚仑 · 深圳</sub>
