# Discover Enterprise Agent

Discover and define the right enterprise AI agents from real business processes.

`discover-enterprise-agent` is a reusable product-management skill for finding enterprise AI agent scenarios, defining agent roles, deciding when capabilities should stay together or split, and designing decision–management–execution agent families.

## Why this skill

Enterprise agent planning often starts with model capabilities, chat interfaces, or isolated ideas. This skill starts with the real workflow:

```text
Business process → Role → Outcome → Validation → Evolution
```

It helps product managers answer:

- Where should an enterprise build an AI agent?
- Is this a real agent role, a capability, a feature, or only an interface?
- Should several capabilities belong to one agent or multiple agents?
- What should the agent produce, and where does human responsibility remain?
- How can a single agent evolve into a decision-, management-, and execution-layer framework?

## 中文简介

这是一个帮助企业产品经理从真实业务流程中发现、定义和规划 AI Agent 的可复用 Skill。

它不会从“大模型能做什么”开始罗列场景，而是先梳理企业现有流程、人员职责和核心业务产物，再判断：

- 企业真正需要建设什么 Agent；
- 哪些能力应组合成一个角色；
- 哪些能力应拆分为不同 Agent；
- 一期应该验证哪条真实任务链；
- 如何进一步形成决策层、管理层和执行层 Agent 体系。

## Core outputs

- Process–output–capability mapping
- Agent role definition
- Agent consolidation/split judgment
- “Who I am – Where I come from – Where I go” build instance
- First-release validation plan
- Decision–management–execution role-family matrix

## Install

Clone the repository:

```bash
git clone https://github.com/daweicoco/discover-enterprise-agent.git
```

Copy `skills/discover-enterprise-agent` into your Codex or compatible agent skills directory.

## Example prompt

```text
Use $discover-enterprise-agent to analyze this real business process,
identify the enterprise AI agent roles worth building,
and explain which capabilities should be combined or separated.
```

中文示例：

```text
使用 $discover-enterprise-agent，基于这套真实业务流程，
发现并定义适合建设的企业 AI Agent，
并说明各项能力应该合并为一个角色还是拆分。
```

## Repository structure

```text
skills/discover-enterprise-agent/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── prove-method.md
    ├── role-family-framework.md
    ├── output-templates.md
    ├── example-sales-process.md
    └── evaluation-cases.md
```

PROVE is retained as the internal reasoning method. The public skill name remains direct and searchable: `discover-enterprise-agent`.
