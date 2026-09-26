# Awesome-AI-Evaluation-Platform

# Top AI Evaluation Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LLM & Agent Evals, RAG Metrics, Prompt Testing, CI Gates, LLM-as-Judge & Continuous Quality Scoring*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Evaluation**. These systems measure quality of LLM apps and agents—faithfulness, relevance, toxicity, task success, trajectory correctness—via offline datasets, online production scoring, and CI regression gates.

**Examples** include Braintrust, LangSmith, Humanloop, Galileo, Arize Phoenix, DeepEval, Ragas, Confident AI, Fiddler AI, TruLens, Patronus AI, and HoneyHive (the category leaders).

**Open-source emphasis**: Evaluation has outstanding open frameworks. **DeepEval**, **Ragas**, **Promptfoo**, **TruLens**, **Phoenix**, and related libraries are the backbone of most CI and research eval stacks. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Braintrust](https://www.braintrust.dev/)**  
  Evaluation-first platform for logging, scoring, experiments, and production feedback loops on LLM and agent applications.

- **[LangSmith](https://www.langchain.com/langsmith)**  
  Observability and evaluation hub for LangChain/LangGraph—datasets, evaluators, annotation queues, and trajectory scoring.

- **[Humanloop, Galileo, HoneyHive, Patronus AI](https://humanloop.com/)**  
  Platforms focused on prompt evaluation, human feedback, agent quality, and continuous improvement of generative applications.

- **[Arize Phoenix / Arize AX](https://arize.com/)**  
  Open Phoenix plus enterprise Arize for tracing, experiments, and evaluation of LLM and agent systems.

- **[Confident AI (DeepEval Cloud)](https://www.confident-ai.com/)**  
  Hosted collaboration and online evals built around the open DeepEval framework.

- **[Fiddler AI & broader ML/LLM eval platforms](https://www.fiddler.ai/)**  
  Model performance and evaluation tools spanning classical ML and generative AI quality monitoring.

- **[Other commercial AI evaluation platforms](https://www.braintrust.dev/)**  
  Additional solutions for offline/online evals, red teaming, and quality dashboards.

## Open-Source GitHub Projects

- **[DeepEval](https://github.com/confident-ai/deepeval)**  
  Leading open-source (Apache 2.0) LLM evaluation framework—pytest-style metrics for agents, RAG, chat, safety; CI-friendly with 50+ metrics and G-Eval-style judges.

- **[Ragas](https://github.com/explodinggradients/ragas)**  
  Open-source (Apache 2.0) RAG-focused evaluation library—faithfulness, answer relevance, context precision/recall, and related retrieval metrics.

- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  
  Open-source (MIT) config-driven eval and red-teaming CLI—YAML test matrices, prompt comparison, security tests, and CI gates with no vendor account required.

- **[TruLens](https://github.com/truera/trulens)**  
  Open evaluation and feedback framework for LLM apps—RAG and agent feedback functions, instrumentation, and experiment tracking.

- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  
  Open-source tracing and evaluation toolkit—datasets, experiments, LLM-as-judge evals, and trajectory analysis (Elastic License 2.0).

- **[OpenAI Evals](https://github.com/openai/evals)**  
  Open evaluation framework and registry of evals—completion protocols and model-graded YAML for offline testing.

- **[Langfuse evals & datasets](https://github.com/langfuse/langfuse)**  
  Open LLM engineering platform with datasets, scores, and experiment features usable for evaluation workflows.

- **[Evidently & custom metric libraries](https://github.com/evidentlyai/evidently)**  
  Open monitoring/eval metrics adaptable to generative quality, drift, and regression testing.

### Additional Strong Open-Source Options

- **CI gates**: DeepEval (pytest) and Promptfoo (YAML/CLI) for merge-blocking eval suites.
- **RAG quality**: Ragas as the standard open RAG metric suite.
- **Agent trajectories**: DeepEval and Phoenix for step-level and path evaluation.
- **Security evals**: Promptfoo for jailbreak and policy regression tests.
- **Composable stacks**: Promptfoo/DeepEval in CI + Phoenix/Langfuse for production online scoring.
- Commercial platforms still lead in team collaboration, annotation queues, and managed online evals.

**Frameworks for building custom systems**:  
**DeepEval**, **Ragas**, and **Promptfoo** form the core open evaluation toolkit.  
**TruLens** and **Phoenix** add instrumentation and experiment UX.  
Commercial platforms (Braintrust, LangSmith, Humanloop, Galileo, Confident AI, Patronus, HoneyHive, etc.) provide hosted datasets, human review, and production scoring.  
Best practice: open frameworks for offline CI gates; optional commercial platform for online evals and team workflows. Fully open evaluation pipelines are production-ready for most teams.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Evaluation scores (including LLM-as-judge) are approximate and can be biased or gamed. Use multiple metrics, human review for critical decisions, and continuous recalibration as models and prompts change.
- Open-source tools offer transparency and data control but require you to design suites and interpret results. Commercial platforms shift operational burden to the vendor. Neither replaces domain expertise for high-stakes applications.

---

**Made for AI engineers, eval leads, and teams shipping reliable LLM and agent products.**  
Let's expand open, rigorous AI evaluation while recognizing the collaboration and online-scoring depth that leading commercial platforms deliver.
