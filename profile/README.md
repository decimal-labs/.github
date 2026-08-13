# DecimalAI

**Skills and agents, ranked by measured effectiveness rather than by downloads.**

Most skill directories rank by stars. We benchmark. Every public skill is security-scanned
before it is published. A skill that has been A/B benchmarked against a no-skill baseline on
real tasks carries whatever that measured — including when the lift is zero or negative — and
is re-verified as models improve. A skill that has not been benchmarked is listed with no lift
number rather than an invented one. What comes out is a number you can argue with, and the
evidence behind it.

[Docs](https://docs.decimal.ai) · [App](https://app.decimal.ai) · [Registry](https://app.decimal.ai/skills)

---

### Open specifications

| | |
|---|---|
| **[agentversion](https://github.com/decimal-labs/agentversion)** | An open specification for versioning agent runtimes and keeping datasets valid across changes. Manifests, canonical hashing, compatibility diffs, and a conformance suite. `Apache-2.0` · [PyPI](https://pypi.org/project/agentversion/) |
| **[skillevaluation](https://github.com/decimal-labs/skillevaluation)** | An open specification for A/B benchmarking agent skills via declarative test suites. Defines the execution contract, the outcome taxonomy, and how lift is aggregated. `Apache-2.0` · [PyPI](https://pypi.org/project/skillevaluation/) |

Both ship architecture decision records and a conformance fixture suite, so another implementation
can prove it agrees with ours rather than taking our word for it.

### Libraries and tooling

| | |
|---|---|
| **[decimalai-python](https://github.com/decimal-labs/decimalai-python)** | The Python SDK. Trace agents, manage datasets, run evaluations, and route registry skills into your agent's context at runtime. Integrations for LangChain, LangGraph, OpenAI, Anthropic, AutoGen, ADK and the Claude Agent SDK. `MIT` · [PyPI](https://pypi.org/project/decimalai/) |
| **[regression-check](https://github.com/decimal-labs/regression-check)** | A GitHub Action that catches agent regressions before they ship — it diffs your agent's manifest against recorded production traffic on every pull request, so there are no eval cases to write. `MIT` |
| **[decimalai-mcp](https://github.com/decimal-labs/decimalai-mcp)** | An MCP server for the skills registry. Search by measured effectiveness, inspect a skill's trust and benchmark evidence, read the leaderboard. Read-only, no API key required. `MIT` · [PyPI](https://pypi.org/project/decimalai-mcp/) |

### Learning

| | |
|---|---|
| **[eval-notebooks](https://github.com/decimal-labs/eval-notebooks)** | Eight notebooks on evaluating agents: metrics, experiment tracking, curating training data from production traces, regression gates, prompt comparison, and multi-agent evals. Framework-agnostic. `MIT` |
| **[decimalai-docs](https://github.com/decimal-labs/decimalai-docs)** | Source for [docs.decimal.ai](https://docs.decimal.ai). Corrections welcome — the edit link on every page lands here. `CC-BY-4.0` |

---

### Contributing

Start with [CONTRIBUTING.md](https://github.com/decimal-labs/.github/blob/main/CONTRIBUTING.md).
For anything beyond a small fix, open an issue before writing code — especially in the two
specification repositories, where changes need agreement before they need an implementation.

Found a security issue? Please don't open a public issue —
[SECURITY.md](https://github.com/decimal-labs/.github/blob/main/SECURITY.md) has the two private
channels.

### Get in touch

[hello@decimal.ai](mailto:hello@decimal.ai)
