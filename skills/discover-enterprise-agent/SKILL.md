---
name: discover-enterprise-agent
description: Use when a product manager needs to discover, define, split, consolidate, or prioritize enterprise AI agents from a real business process, or design a decision-management-execution agent framework across an end-to-end process.
---

# Discover Enterprise Agent

## Overview

Discover what enterprise AI agent should be built from real workflow evidence. Use PROVE internally to connect process, role, outcome, validation, and evolution; do not lead user-facing materials with the PROVE name unless asked.

## Choose the work mode

| User need | Mode | Required references |
|---|---|---|
| Find or define one agent from a process or scenario | Single-agent discovery | `references/prove-method.md`, `references/output-templates.md` |
| Decide whether capabilities belong in one agent or several | Role boundary review | `references/prove-method.md`, `references/output-templates.md` |
| Design decision, management, and execution agents across a process | Agent role family | Above files plus `references/role-family-framework.md` |
| Demonstrate the method with a sales process | Worked example | Above files plus `references/example-sales-process.md` |

Read each listed reference completely before producing the corresponding deliverable.

## Workflow

1. **Establish process evidence.** Extract the minimum real workflow: key stages, human roles, decisions/tasks, core outputs, systems/data, pain points, and known boundaries. Separate confirmed facts, design assumptions, and open questions.
2. **Form the role.** Group adjacent capabilities by one stable mission, service object, owner, work loop, and outcome. Split roles when these differ materially; never split only because technology, data source, or process stage differs.
3. **Contract the outcome.** Define who the agent serves, what recurring result it produces, where it enters and exits the process, what it may recommend or execute, and what remains human-owned.
4. **Validate value and viability.** Select a real task, define required inputs and usable outputs, then test business adoption, evidence quality, data readiness, and risk. Treat metrics as validation instruments, not as role-definition content.
5. **Plan evolution.** Define the smallest coherent first release, maturity path, and—only when needed—the relationship to decision-, management-, and execution-layer agents.

## Non-negotiable rules

- Start from the enterprise's real process, not from a generic skill domain, model capability, system, or interface.
- For “从哪来”, default to one table with **process / core output / corresponding capability**. Add fuller diagnostics only when requested.
- Keep role, capability, feature, system, data source, and interaction carrier distinct.
- Do not invent Web, chatbot, plugin, dashboard, avatar, or other carriers before role and workflow validation.
- Do not force every process node into a separate agent. A coherent role may span adjacent stages.
- Do not combine execution monitoring or BI with a decision agent merely because the same employee views both.
- Treat AI permission boundaries and human accountability as design guardrails. Surface them when decisions, external commitments, approvals, writes, or material risk are involved; they are not mandatory headline blocks.
- Leave unassessed professional dimensions as `待评估`; do not fabricate maturity, data quality, model, compute, security, or ROI scores.
- Distinguish opportunity discovery from qualification. They can be capabilities of one agent, but they are not the same task.
- Map power-price prediction, ROI calculation, retrieval, and similar services to the business activity they support; do not promote them to top-level business processes without evidence.

## Default deliverables

Produce only what helps the current decision:

1. Evidence and assumption summary.
2. Process–output–capability table.
3. Agent role definition: mission, users, scope, core outputs, capabilities, entry/exit, exclusions, and human checkpoints.
4. Consolidate/split judgment with explicit criteria.
5. “我是谁—从哪来—到哪去” construction table when a build-instance view is requested.
6. First-release validation plan using one real task.
7. Role-family matrix only for end-to-end or multi-level planning.

Use the tables in `references/output-templates.md`. Before finalizing, run the quality cases and checklist in `references/evaluation-cases.md`.

## Common mistakes

| Mistake | Correction |
|---|---|
| Starting with a list of AI features | Reconstruct the real workflow and outputs first |
| Calling every capability an agent | Require a stable mission, user, work loop, and outcome |
| Adding all available data and BI into one assistant | Test role cohesion and split by responsibility loop |
| Treating Public Tender and qualification as synonyms | Separate discovery/structuring from go/no-go judgment |
| Filling every methodology box | Mark unsupported areas `待评估` |
| Using metrics as decorative content | Tie each metric to a validation question and baseline |
