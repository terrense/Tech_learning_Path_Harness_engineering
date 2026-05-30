# Tech Learning Path: Harness Engineering

This repository is the source-of-truth workspace for long-form technical writing about Harness Engineering.

## Series Positioning

This series now uses the following structure:

- Lessons 001-002 are the evaluation and evidence-engineering foundation. They explain the broader test/evaluation harness tradition and provide a Python evaluation harness baseline.
- Lesson 003 is the conceptual correction and transition point. From there, the series focuses on AI Agent Harness Engineering: the runtime systems around autonomous, tool-using agents.
- Lessons 004-005 move into agent runtime design, evaluation loops, observability, human gates, and autonomy governance.
- Lesson 006 deepens the runtime discussion into context engineering: retrieval, memory selection, compaction, prompt-cache-aware layout, budget governance, and context evals inside an agent harness.
- Lesson 007 turns from context to tool-use architecture: schema contracts, MCP/tool brokers, risk tiers, permission gates, sandboxed execution, side-effect control, and traceable tool evals.
- Lesson 008 makes agent evaluation operational: trajectory datasets, deterministic tool stubs, rubric scoring, trace grading, regression dashboards, and release gates for agent harness changes.
- Lesson 009 moves the series into production AgentOps: observability, agent SLOs, behavior drift detection, rollback, audit, incident response, and continuous improvement loops for deployed agent harnesses.
- Lesson 010 extends production AgentOps into multi-agent harnesses: delegation topology, context isolation, capability leases, coordination protocols, cross-agent trace evaluation, and collaborative release governance.
- Lesson 011 formalizes release governance for agent harnesses: release bundles, evidence gates, safety cases, staged rollout, version compatibility, rollback readiness, and policy-as-code promotion rules.
- Lesson 012 makes memory management a governed harness subsystem: lifecycle control, typed memory records, provenance lineage, retrieval authorization, decay, consolidation, privacy retention, deletion proof, and memory evals.
- Lesson 013 turns long-running agent work into durable workflow orchestration: state machines, checkpoints, leases, idempotent tools, retry budgets, compensation, human gates, handoffs, trace replay, and workflow release governance.
- Lesson 014 makes policy governance explicit: policy hierarchy, conflict resolution, enforcement points, exception workflows, audit evidence ledgers, policy evals, and cross-team ownership.

## Article Index

| No. | Title | Focus |
|---:|---|---|
| 001 | [🧩 Harness Engineering：面向复杂系统验证、评估与运维的工程化方法论](articles/harness-engineering/001-harness-engineering-overview.md) | Evaluation harness foundation, evidence loop, maturity model |
| 002 | [🧪 Harness Engineering 实战：从零实现一个可复现的 Python Evaluation Harness](articles/harness-engineering/002-python-evaluation-harness-from-zero.md) | Python evaluation harness, runner, adapter, evaluator, artifacts, CI/CD |
| 003 | [🧭 第三课：真正的 Agent Harness Engineering：从 Prompt、Context 到 Agent 运行时外骨骼](articles/harness-engineering/003-agent-harness-engineering-for-ai-agents.md) | Concept correction, prompt/context/harness evolution, agent runtime map |
| 004 | [🛠️ 第四课：Agent Harness Runtime Design：工具、权限、沙箱、Session、Memory 与 Context Builder](articles/harness-engineering/004-agent-harness-runtime-design.md) | Tool registry, permission model, sandbox, session, memory, context builder |
| 005 | [📈 第五课：Agent Harness 的验证闭环：Eval、Trajectory、Observability、Human Gate 与自治成熟度](articles/harness-engineering/005-agent-harness-evaluation-feedback-ops.md) | Agent eval, trajectory trace, observability, human gate, feedback loop, autonomy maturity |
| 006 | [🧵 第六课：Context Engineering Inside Agent Harness：检索、记忆选择、压缩、预算与上下文治理](articles/harness-engineering/006-context-engineering-inside-agent-harness.md) | Context builder, retrieval, memory selection, compaction, context budget, prompt caching, context evals |
| 007 | [🧰 第七课：Tool Use Architecture for Agent Harness：Schema、MCP、权限门、风险分层与副作用控制](articles/harness-engineering/007-tool-use-architecture-for-agent-harness.md) | Tool schema contracts, MCP/tool broker, risk tiers, permission gates, side-effect control, tool evals |
| 008 | [🧪 第八课：Agent Evals In Practice：Trajectory Dataset、Deterministic Stub、Rubric Scoring 与 Regression Dashboard](articles/harness-engineering/008-agent-evals-in-practice.md) | Trajectory datasets, deterministic stubs, rubric scoring, trace grading, regression dashboards, release gates |
| 009 | [🚀 第九课：Production Agent Operations：监控、回滚、审计、事故响应与持续改进](articles/harness-engineering/009-production-agent-operations.md) | Production AgentOps, observability, SLOs, drift detection, rollback, audit, incident response, continuous improvement |
| 010 | [🧬 第十课：Multi-Agent Harnesses：委派、上下文隔离、协同协议与跨 Agent Trace 评估](articles/harness-engineering/010-multi-agent-harnesses.md) | Multi-agent delegation, context isolation, capability leases, coordination protocols, cross-agent trace evals |
| 011 | [🛡️ 第十一课：Agent Release Governance：分阶段发布、策略评审、安全论证、版本治理与回滚就绪](articles/harness-engineering/011-agent-release-governance.md) | Release bundles, evidence gates, safety cases, staged rollout, version governance, rollback readiness |
| 012 | [🧠 第十二课：Agent Memory Management：生命周期、来源谱系、衰减、隐私治理与可遗忘性](articles/harness-engineering/012-agent-memory-management.md) | Memory lifecycle, provenance lineage, retrieval authorization, decay, privacy retention, deletion proof, memory evals |
| 013 | [🧭 第十三课：Workflow Orchestration for Agent Harness：持久执行、重试、补偿、人类检查点与轨迹回放](articles/harness-engineering/013-workflow-orchestration-for-agent-harness.md) | Durable execution, checkpoints, leases, idempotency, retry budgets, compensation, human gates, handoffs, trace replay |
| 014 | [🏛️ 第十四课：Agent Policy Governance：策略层级、例外处理、审计证据与跨团队所有权](articles/harness-engineering/014-agent-policy-governance.md) | Policy hierarchy, conflict resolution, enforcement points, exception workflows, audit ledgers, policy evals |

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
    006-context-engineering-inside-agent-harness.md
    007-tool-use-architecture-for-agent-harness.md
    008-agent-evals-in-practice.md
    009-production-agent-operations.md
    010-multi-agent-harnesses.md
    011-agent-release-governance.md
    012-agent-memory-management.md
    013-workflow-orchestration-for-agent-harness.md
    014-agent-policy-governance.md
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
    006/
      context-builder-control-plane.svg
      memory-retrieval-selection-pipeline.svg
      context-budget-governance-map.svg
      prompt-cache-aware-context-layout.svg
    007/
      tool-schema-contract-map.svg
      permission-risk-gate-lattice.svg
      mcp-tool-broker-topology.svg
      side-effect-control-loop.svg
    008/
      agent-eval-dataset-lifecycle.svg
      trajectory-fixture-taxonomy.svg
      rubric-scoring-pipeline.svg
      regression-dashboard-topology.svg
    009/
      agentops-control-loop.svg
      agentops-observability-stack.svg
      rollback-incident-lifecycle.svg
      continuous-improvement-flywheel.svg
    010/
      delegation-topology.svg
      context-isolation-boundaries.svg
      coordination-protocol-state-machine.svg
      cross-agent-trace-evaluation.svg
    011/
      release-governance-control-plane.svg
      safety-case-evidence-graph.svg
      staged-rollout-ladder.svg
      rollback-readiness-matrix.svg
    012/
      memory-lifecycle-control-plane.svg
      memory-provenance-lineage-graph.svg
      consolidation-decay-pipeline.svg
      privacy-retention-governance-matrix.svg
    013/
      durable-workflow-control-plane.svg
      retry-compensation-state-machine.svg
      checkpoint-human-gate-topology.svg
      orchestration-trace-replay-loop.svg
    014/
      policy-governance-control-plane.svg
      policy-hierarchy-lattice.svg
      exception-review-workflow.svg
      audit-evidence-ledger.svg
templates/
  article-template.md
```

## Writing Direction

The writing style of this repository is:

- long-form Markdown articles;
- serious, scientific third-person technical exposition;
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

- 🔒 Agent Sandboxing and Capability Isolation: filesystem, network, identity, secrets, tool leases, and blast-radius reduction.
- 📦 Agent Release Artifacts and Evidence Packaging: signed bundles, provenance, SBOM-like manifests, and rollback compatibility.
- 🧮 Agent Cost, Latency, and Capacity Governance: budget policies, queueing, rate limits, and adaptive model routing.

## Author Contact

Terrence Shen  
Email: slamshenxin@gmail.com  
Located in China