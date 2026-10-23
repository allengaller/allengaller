**English** · [中文](README.zh-CN.md)

# Allen Galler · 曹亚仑

SRE at Alibaba Cloud, based in Shenzhen. On GitHub since 2010, with 700+ public repos across 20+ orgs.

By day I keep cloud-native infrastructure stable. The rest of my time goes into one long experiment: turning ops experience into tools and knowledge bases that people can read and agents can consume directly as RAG corpora.

Some of the numbers behind that: 4,750 production-ops documents in a single knowledge base, 432 support scenarios automated end to end, 94 real P0/P1 incident case studies, 959 runnable architecture demos.

**Skimming? Start with these three:** [resolve-agent](https://github.com/ai-guru-global/resolve-agent) (agents doing real support work), [klaw](https://github.com/kudig-io/klaw) (one binary holding a whole K8s ops practice), [kudig-database](https://github.com/kudig-io/kudig-database) (the knowledge base everything else reads from).

## Now

- **agent-up**: feedback → attribution → release → rollback, a working loop for improving agents in production
- **KUDIG / ResolveAgent**: turning runtime traces of ops tools into structured, agent-readable knowledge
- **open-geo**: research notes on Generative Engine Optimization (GEO)

## Agent projects

| Project | What it does |
|---|---|
| [resolve-agent](https://github.com/ai-guru-global/resolve-agent) | Support agents on AgentScope that route by failure signature across FTA fault trees, wiki KBs, skills and code analysis. 432 scenarios live |
| [agent-up](https://github.com/ai-guru-global/agent-up) | Agent config lifecycle: edit, approve, release, track, roll back. User feedback is auto-attributed into config-change suggestions |
| docsy *(private)* | Docs platform for the agent era. Markdown becomes machine-checkable research packs with 14 linter rules and a health score; holds up on a 21k-doc repo |
| sokr *(private)* | OKR and postmortem tool for ops teams. Incident reviews become graduable team skill assets. Zero deploy, runs in the browser |
| [mcp-database](https://github.com/standup-coder/mcp-database) | Self-hosted MCP server framework (mcp4coder). 37 servers, 200+ tools, one base class; adding a server means implementing two methods |
| [skills-database](https://github.com/standup-coder/skills-database) | 455 job-competency skills across 27 roles. Sources traceable, browsable offline from a single file |

## AI Infra projects

| Project | What it does |
|---|---|
| [kudig-database](https://github.com/kudig-io/kudig-database) | K8s + AI Infra ops knowledge base: 4,750 docs, 21 domains, 13 cloud vendors, plus a fault-tree engine with 16 top events and ~300 bottom events |
| [ai-guru-database](https://github.com/ai-guru-global/ai-guru-database) | Chinese full-stack AI knowledge base. 2,061 core docs (~19M characters), 700+ concept cards, from math foundations to agents in production |
| [klaw](https://github.com/kudig-io/klaw) | One binary with a console, diagnostics engine, ChatOps bot, alerting and SOS voice. 73 analyzers, sub-second event push |
| [etcd-guardian](https://github.com/kudig-io/etcd-guardian) | etcd backup/restore operator that covers the managed-cluster blind spot Velero can't reach. Works out of the box on Alibaba ACK, plugs into klaw |
| [kubernetes-network-master](https://github.com/kudig-io/kubernetes-network-master) | K8s network troubleshooting in a single binary (kubectl plugin). Hop-by-hop causal tracing from DNS down to CNI, 20+ subcommands, light eBPF inside |

## TAM projects

| Project | What it does |
|---|---|
| [open-tam](https://github.com/open-labor/open-tam) | Multi-agent troubleshooting on AgentScope + MCP. Three-part reports (symptom, root cause, action); every step is a replayable trace, so the fault registry doubles as the eval set |
| [kuba-database](https://github.com/kudig-io/kuba) | 94 real P0/P1 incident reviews across 46 years and 47 companies, distilled into 12 root-cause classes, each case told from SRE, CRE, FDE and SA angles |
| [cmd-database](https://github.com/standup-coder/cmd-database) | A page per command for 1,100+ commands, plus 741 production notes. Generated from one YAML source, checked by a Go CLI |
| [open-arch](https://github.com/allengaller/open-arch) | Presales-architect copilot on AgentScope 2.0: clarify, design, diagram, review, deliver. Knowledge lives in auditable Markdown skill packs |
| [open-demo](https://github.com/open-labor/opendemo-work) | 959 runnable demos across 18 stacks for SAs, delivery and PMs. Each ships with an architecture diagram, a full tutorial and working artifacts |
| [fde-scope](https://github.com/ai-guru-global/fde-scope) | A field OS for forward-deployed engineers: 4 phases, 18 steps, 10 code-level gates, 7 of them from FAT, ISO 13849 and CE |
| [repo-database](https://github.com/allengaller/repo-database) | A curated arsenal for FDEs. 1,000+ repos scanned monthly, 115 structured dossiers kept, every entry CI-gated |

The other 700+ repos are indexed at [allengaller.github.io/repos](https://allengaller.github.io/repos/).

## Elsewhere

- [allengaller.github.io](https://allengaller.github.io) — home base
- [Projects](https://allengaller.github.io/projects/) · [Repos](https://allengaller.github.io/repos/) · [Links](https://allengaller.github.io/topic/links/) · [RSS](https://allengaller.github.io/feed.xml)

## Talk to me

Always up for conversations about agents in production, Kubernetes failure analysis, or GEO. For anything project-specific, open an Issue on that repo; I read them all. PRs are welcome on the public repos, and if something here saved you time, a star on that repo is the best way to let me know. Collaboration-wise, the best fits are Agent / RAG / MCP / CLI tools that have to survive production, and turning scattered docs into knowledge bases that keep paying off.

<sub>© Allen Galler · Shenzhen</sub>
