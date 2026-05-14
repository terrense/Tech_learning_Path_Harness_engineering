# Tech Learning Path: Harness Engineering

This repository is the source-of-truth workspace for long-form technical writing about Harness Engineering.

## Series Positioning

This series now uses the following structure:

- Lessons 001-002 are the evaluation and evidence-engineering foundation. They explain the broader test/evaluation harness tradition and provide a Python evaluation harness baseline.
- Lesson 003 is the conceptual correction and transition point. From there, the series focuses on AI Agent Harness Engineering: the runtime systems around autonomous, tool-using agents.
- Lessons 004-005 move into agent runtime design, evaluation loops, observability, human gates, and autonomy governance.

## Article Index

| No. | Title | Focus |
|---:|---|---|
| 001 | [🧩 Harness Engineering：面向复杂系统验证、评估与运维的工程化方法论](articles/harness-engineering/001-harness-engineering-overview.md) | Evaluation harness foundation, evidence loop, maturity model |
| 002 | [🧪 Harness Engineering 实战：从零实现一个可复现的 Python Evaluation Harness](articles/harness-engineering/002-python-evaluation-harness-from-zero.md) | Python evaluation harness, runner, adapter, evaluator, artifacts, CI/CD |
| 003 | [🧭 第三课：真正的 Agent Harness Engineering：从 Prompt、Context 到 Agent 运行时外骨骼](articles/harness-engineering/003-agent-harness-engineering-for-ai-agents.md) | Concept correction, prompt/context/harness evolution, agent runtime map |
| 004 | [🛠️ 第四课：Agent Harness Runtime Design：工具、权限、沙箱、Session、Memory 与 Context Builder](articles/harness-engineering/004-agent-harness-runtime-design.md) | Tool registry, permission model, sandbox, session, memory, context builder |
| 005 | [📈 第五课：Agent Harness 的验证闭环：Eval、Trajectory、Observability、Human Gate 与自治成熟度](articles/harness-engineering/005-agent-harness-evaluation-feedback-ops.md) | Agent eval, trajectory trace, observability, human gate, feedback loop, autonomy maturity |

## Repository Structure

```text
README.md
articles/
  harness-engineering/
    001-harness-engineering-overview.md
    002-python-evaluation-harness-from-zero.md
    003-agent-harness-engineering-for-ai-agents.md
    004-agent-harness-runtime-design.md
    005-agent-harness-evaluation-feedback-ops.md
assets/
  harness-engineering/
    001/
      harness-layered-architecture.svg
      harness-data-loop.svg
      harness-maturity-map.svg
    002/
      python-harness-workflow.svg
      python-harness-repository-structure.svg
      python-harness-evidence-model.svg
    003/
      prompt-context-harness-evolution.svg
      agent-harness-runtime-layers.svg
      agent-harness-control-loop.svg
    004/
      tool-permission-risk-matrix.svg
      session-context-memory-flow.svg
      agent-runtime-state-machine.svg
    005/
      agent-eval-feedback-loop.svg
      agent-observability-stack.svg
      agent-autonomy-maturity-model.svg
templates/
  article-template.md
```

## Writing Direction

The writing style of this repository is:

- long-form Markdown articles;
- serious, scientific, third-person technical exposition;
- expressive headings with sticker-style emoji markers;
- many diagrams, Mermaid charts, tables, and runnable code examples;
- reusable examples for engineering teams, AI systems, DevOps, testing, evaluation workflows, and agent runtime design.

## Article Directory

Primary articles are stored in:

```text
articles/harness-engineering/
```

Shared visual assets are stored in:

```text
assets/harness-engineering/
```

## Next Topics

Potential next articles:

- 🧵 Context Engineering Inside Agent Harness: retrieval, memory selection, summarization, and context budget control.
- 🧰 Tool Use Architecture: tool schema, MCP, risk tiers, approval gates, and side-effect control.
- 🧪 Agent Evals In Practice: trajectory datasets, deterministic stubs, rubric scoring, and regression dashboards.
- 🚀 Production Agent Operations: monitoring, rollback, audit, incident response, and continuous improvement.

## Author Contact

Terrence Shen  
Email: slamshenxin@gmail.com  
Located in China
