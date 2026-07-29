# 🧱 AI Agent Infrastructure Projects

[![Contribute](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](./CONTRIBUTING.md)

A curated, vendor-neutral directory of AI agent infrastructure projects
covering agent runtimes, sandboxes, memory, identity, permissions,
observability, durable workflows, and agent protocols.

Browse the [interactive project directory](https://agent-infra-foundation.org/projects/)
or contribute updates to this open index on GitHub.

Agent infrastructure is the technical substrate that enables agents to
execute, communicate, maintain state, access tools and data under defined
authority, recover from failure, remain observable, and return control to
people when needed.

It is not a particular agent application or framework; it is the shared
foundation on which many agents can be built and operated.

## 🌟 What Agent Infra includes

| Area | What it includes |
| --- | --- |
| 🧪 **Execution Environments & Sandboxing** | Sandboxes, browsers, containers, filesystems, process isolation, and resource controls |
| 🤝 **Agent Communication & Coordination** | A2A protocols, discovery, messaging, delegation, shared context, task routing, and conflict resolution |
| 🧠 **Memory, Data & Filesystems** | Memory, metadata, artifacts, retrieval, shared state, and agent-native data primitives |
| 🔑 **Identity, Permissions & Trusted Tools** | Agent identity, delegated authority, credentials, capability-based access, and safe tool interfaces |
| 🔄 **Durable Workflows & Recovery** | State, checkpoints, retries, scheduling, persistence, and recovery |
| 🔎 **Observability, Auditability & Provenance** | Logs, traces, replay, action history, provenance, and policy decisions |
| 🙌 **Human Handoffs & Control** | Approvals, escalation, intervention, context transfer, and accountability |
| ✅ **Evaluation & Operational Reliability** | Testing, simulation, containment, recovery, consistency, and human-control evaluation |

## 📚 Project index

| Project | What it does | Focus | Links |
| --- | --- | --- | --- |
| [Brazosd](https://brazosd.com/en/) | Specialist agents and governed cloud workflows | Specialist agents · Multi-agent · Approvals · Security | [Website](https://brazosd.com/en/) |
| [Ephemeral Sandbox](https://ephemeral-sandbox.com/) | A multi-agent runtime for isolated coding workspaces | Sandbox · Filesystem · Multi-agent · Copy-on-write | [Website](https://ephemeral-sandbox.com/) · [Source](https://github.com/Ephemeral-AI-Lab/ephemeral-sandbox) |
| [NervaFS](https://nervafs.xyz/) | A governed filesystem workspace for agent runtimes | Filesystem · A2P · Identity · Memory | [Website](https://nervafs.xyz/) |
| [NoKV](https://nokv.io/) | A metadata control plane for agent workspaces | Filesystem · Metadata · Observability · Artifacts | [Website](https://nokv.io/) · [Source](https://github.com/NoKV-Lab/NoKV) |
| [ToWow](https://towow.net/) | An open protocol for agent discovery and collaboration | A2A · Agent discovery · Semantic matching · Coordination | [Website](https://towow.net/) |

## 🙌 Add, update, or remove a project

This index is maintained through pull requests.

1. Fork this repository.
2. Create a branch in your fork.
3. Edit the table above to add, update, or remove a project.
4. Open a pull request and use the provided template.

Please use neutral, factual wording and link to official sources. For a removal, explain why the entry should no longer be listed. See [CONTRIBUTING.md](./CONTRIBUTING.md) for the complete guidelines.

## ✅ How projects qualify

A project belongs in this directory when its primary contribution is a
reusable agent-infrastructure capability rather than a single agent
application, framework, or generic infrastructure product.

Maintainers review submissions for agent-infrastructure relevance,
reusability, accuracy, duplicate entries, neutral language, and reliable
primary sources.

## 📄 License

The repository content is available under the [MIT License](./LICENSE).
