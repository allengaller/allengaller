**English** · [中文](README.zh-CN.md)

# Allen Galler · 曹亚仑

SRE at Alibaba Cloud, based in Shenzhen. On GitHub since 2010.

By day I keep cloud-native infrastructure alive. On the side I build tools and knowledge bases — most of them written to be read twice: once by people, once by agents as RAG corpora.

[![Website](https://img.shields.io/badge/allengaller.github.io-000000?style=flat-square&logo=safari&logoColor=white)](https://allengaller.github.io)
[![100+ repos · 20+ orgs](https://img.shields.io/badge/100%2B_repos-20%2B_orgs-000000?style=flat-square)](https://allengaller.github.io/repos/)
[![Followers](https://img.shields.io/github/followers/allengaller?style=flat-square&logo=github)](https://github.com/allengaller?tab=followers)

## Now

- **agent-up** — a feedback → attribution → release → rollback loop for improving agents in production
- **KUDIG / ResolveAgent** — turning runtime traces of ops tools into structured, agent-readable knowledge bases
- **open-geo** — notes and research on Generative Engine Optimization (GEO)

## Agent projects

| Project | What it does |
|---|---|
| [resolve-agent](https://github.com/ai-guru-global/resolve-agent) | Production-grade support-agent platform on AgentScope: routes by failure signature across FTA fault trees, wiki KBs, skills and code analysis; 432 scenarios live |
| [agent-up](https://github.com/ai-guru-global/agent-up) | Full lifecycle for agent configs: edit, approve, release, track, rollback — user feedback is auto-attributed into config-change suggestions |
| docsy *(private)* | Docs platform for the agent era: Markdown refactored into machine-checkable research packs, 14 linter rules, 0–100 health score; proven on a 21k-doc repo |
| sokr *(private)* | OKR + postmortem tool for ops teams: turns incident reviews into graduable team skill assets; zero-deploy, runs in the browser |
| [mcp-database](https://github.com/standup-coder/mcp-database) | Self-hosted MCP server framework (mcp4coder): 37 servers and 200+ tools on one base class — a new server takes two methods |
| [skills-database](https://github.com/standup-coder/skills-database) | 455 job-competency skills across 27 roles, every source traceable, browsable offline from a single file |

## AI Infra projects

| Project | What it does |
|---|---|
| [kudig-database](https://github.com/kudig-io/kudig-database) | K8s + AI Infra ops knowledge base: 4,750 docs across 21 domains and 13 cloud vendors, plus a fault-tree engine (16 top / ~300 bottom events) |
| [ai-guru-database](https://github.com/ai-guru-global/ai-guru-database) | Chinese AI full-stack knowledge base: 2,061 core docs, 700+ concept cards, from math foundations to agent deployment |
| [klaw](https://github.com/kudig-io/klaw) | Single-binary K8s ops platform: console, diagnostics, ChatOps, alerting and SOS voice in one file; 73 analyzers, sub-second event push |
| [etcd-guardian](https://github.com/kudig-io/etcd-guardian) | etcd backup/restore operator covering the managed-cluster blind spot Velero can't reach; works out of the box on Alibaba ACK, pluggable into klaw |
| [kubernetes-network-master](https://github.com/kudig-io/kubernetes-network-master) | Single-binary K8s network troubleshooting (kubectl plugin): hop-by-hop causal tracing from DNS to CNI, 20+ subcommands, CNI-agnostic eBPF inside |

## TAM projects

| Project | What it does |
|---|---|
| [open-tam](https://github.com/open-labor/open-tam) | Multi-agent troubleshooting on AgentScope + MCP: three-part reports (symptom / root cause / action), every step replayable — the fault registry doubles as the eval set |
| [kuba-database](https://github.com/kudig-io/kuba) | 94 real P0/P1 incident reviews spanning 46 years and 47 companies, distilled into 12 root-cause classes from SRE / CRE / FDE / SA perspectives |
| [cmd-database](https://github.com/standup-coder/cmd-database) | One page per command for 1,100+ commands plus 741 production best-practice notes, generated from a single YAML source and checked by a Go CLI |
| [open-arch](https://github.com/allengaller/open-arch) | Presales-architect copilot on AgentScope 2.0: requirement → design → diagram → review → deliverables, knowledge as auditable Markdown skill packs |
| [open-demo](https://github.com/open-labor/opendemo-work) | 959 runnable demos across 18 stacks for SAs, delivery and PMs — each with architecture diagram, 3,000+ word tutorial and runnable artifacts |
| [fde-scope](https://github.com/ai-guru-global/fde-scope) | Field OS for forward-deployed engineers: 4 phases, 18 steps, 10 code-level gates — 7 inherited from FAT, ISO 13849 and CE |
| [repo-database](https://github.com/allengaller/repo-database) | Curated repo arsenal for FDEs: 1,000+ repos scanned monthly, 115 structured dossiers kept, every entry CI-gated |

Full index of 100+ repos across 20+ orgs: [allengaller.github.io/repos](https://allengaller.github.io/repos/)

## Elsewhere

- [allengaller.github.io](https://allengaller.github.io) — home base
- [Projects](https://allengaller.github.io/projects/) · [Repos](https://allengaller.github.io/repos/) · [Links](https://allengaller.github.io/topic/links/)

## Work with me

Good fits: Agent / RAG / MCP / CLI tools that need to survive production; hands-on design around Kubernetes, observability, and failure analysis; turning scattered docs into knowledge bases that keep growing. Fastest way to reach me is a GitHub Issue on the relevant repo.

<sub>© Allen Galler · Shenzhen</sub>
