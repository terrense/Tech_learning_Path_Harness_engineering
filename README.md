# Tech Learning Path: Harness Engineering

This repository is the source-of-truth workspace for long-form technical writing about Harness Engineering.

## Article Index

| No. | Title | Focus |
|---:|---|---|
| 001 | [🧩 Harness Engineering：面向复杂系统验证、评估与运维的工程化方法论](articles/harness-engineering/001-harness-engineering-overview.md) | Methodology, architecture, evidence loop, maturity model |
| 002 | [🧪 Harness Engineering 实战：从零实现一个可复现的 Python Evaluation Harness](articles/harness-engineering/002-python-evaluation-harness-from-zero.md) | Python implementation, runner, adapter, evaluator, artifacts, CI/CD |

## Repository Structure

```text
README.md
articles/
  harness-engineering/
    001-harness-engineering-overview.md
    002-python-evaluation-harness-from-zero.md
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
templates/
  article-template.md
```

## Writing Direction

The writing style of this repository is:

- long-form Markdown articles;
- serious, scientific, third-person technical exposition;
- expressive headings with sticker-style emoji markers;
- many diagrams, Mermaid charts, tables, and runnable code examples;
- reusable examples for engineering teams, AI systems, DevOps, testing, and evaluation workflows.

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

- 🧬 Harness Engineering for LLM Evaluation: golden sets, schema validation, safety gates, and regression metrics.
- 🔁 Harness Engineering for CI/CD: pull request gates, nightly regression, artifact retention, and release policy.
- 📊 Harness Observability: metrics, traces, dashboards, and evidence quality.
- 🧯 Flaky Scenario Governance: quarantine, ownership, diagnosis, and restoration.

## Author Contact

Terrence Shen  
Email: slamshenxin@gmail.com  
Located in China
