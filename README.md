<p align="center">
  <img src="assets/banner.svg" alt="Awesome AI Evaluation Platform Banner" width="100%" />
</p>

# 🚀 Awesome AI Evaluation Platforms & Tools (2026) 🤖✨

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a> [![Awesome](https://awesome.re/badge.svg)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome) [![Tracked Topics](https://img.shields.io/badge/Focus-LLM%20%26%20Agent%20Evals-blue)](#table-of-contents) <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

A curated list of top SaaS platforms and open-source GitHub frameworks for **AI Evaluation** 📊, **LLM-as-a-Judge** ⚖️, **RAG Metrics** 🔍, **Prompt Testing** 🧪, **Agent Trajectory Scoring** 🎯, and **CI/CD Quality Gates** 🛡️.

---

## 💡 Industry Market Overview 📈

### Market Size & Market Structure 🏛️
- **Estimated Market Size 💰**: The global AI Evaluation, Observability, and LLM Quality Assurance market is estimated at **$1.8B – $2.5B in 2026** and is projected to expand to **$8.5B+ by 2030** (CAGR ~38%), driven by production enterprise LLM deployments and autonomous agent workflows.
- **Market Dynamics 🔄**: The market is **moderately fragmented**. While specialized open-source tools dominate CI/CD developer workflows (e.g., Promptfoo, DeepEval, Langfuse), enterprise SaaS monitoring and observability show signs of consolidation (e.g., Dynatrace acquiring Arize AI for $915M, Cisco acquiring Galileo into Splunk Agent Observability, and Anthropic acquiring Humanloop). High-value enterprise features like automated red-teaming, governance, and custom LLM judge fine-tuning remain competitive ground between agile startups and incumbent observability vendors.

---

## 📋 Table of Contents 📑
- [💡 Industry Market Overview 📈](#-industry-market-overview-)
- [🏢 SaaS & Hosted AI Evaluation Platforms ☁️](#-saas--hosted-ai-evaluation-platforms-)
- [💻 Open-Source AI Evaluation Frameworks 🔓](#-open-source-ai-evaluation-frameworks-)
- [💖 Support & Community 🌟](#-support--community-)
- [📈 Star History](#-star-history)
- [🤝 How to Contribute 🛠️](#-how-to-contribute-)
- [📜 Disclaimer ⚠️](#-disclaimer-)

---

## 🏢 SaaS & Hosted AI Evaluation Platforms ☁️

The following hosted platforms provide developer dashboards, team collaboration tools, production trace scoring, and automated LLM evaluation workflows.

| Platform | Starting Price 💵 | Free Tier / Trial Limit 🎁 | Company Scale (Valuation / Raised / ARR) 🏢 | Primary Use Cases 🎯 |
| :--- | :--- | :--- | :--- | :--- |
| **[LangSmith](https://www.langchain.com/langsmith)** | $39 / seat / month (Plus Plan) | Free forever (1 seat, 5,000 base traces/mo, 14-day retention) | **$1.25B Valuation** ($260M raised, ~$12M–$16M ARR) | Observability, dataset curation, prompt hub & evaluators for LangChain & LLM apps |
| **[Arize AX](https://arize.com/)** | $50 / month (Pro Plan) | Free forever (25,000 spans/mo, 1 GB ingestion, 15-day retention) | **$915M Acquisition** (Acquired by Dynatrace; $131M raised) | Enterprise LLM tracing, online monitoring, prompt evaluation & LLM-as-judge |
| **[Braintrust](https://www.braintrust.dev/)** | $249 / month (Pro Plan) | Free forever ($0/mo, 1 GB data/mo, 10,000 scores/mo, 14-day retention) | **$800M Valuation** ($80M Series B raised in 2026) | Evaluation-first platform, prompt testing, production logging, and regression suites |
| **[Fiddler AI](https://www.fiddler.ai/)** | $0.002 / trace (Developer Plan) | Free tier available (includes baseline guardrails & evaluation features) | **~$100M Raised** ($30M Series C in 2026; ~$30M–$50M ARR) | LLM evaluation, AI guardrails, hallucination detection & predictive ML observability |
| **[Galileo AI (Splunk)](https://galileo.ai/)** | Enterprise quote (Splunk Sales) | Legacy free tier offered 5,000 traces/mo | **~$68M Raised** (Acquired by Cisco/Splunk in 2026) | Hallucination measurement, prompt evaluation, enterprise agent quality & security |
| **[HoneyHive](https://www.honeyhive.ai/)** | Enterprise quote (Contact Sales) | Start for free tier available (basic instrumentation & testing) | **$7.4M Raised** ($5.5M Seed led by Insight Partners) | AI agent evaluation, production observability, custom evaluators & prompt experimentation |
| **[Humanloop](https://humanloop.com/)** | N/A (Platform sunset) | Platform sunset following acquisition | **Acquired by Anthropic** (~$7.9M raised prior) | Prompt management, human-in-the-loop evaluation, LLM feedback loops (integrated into Anthropic) |
| **[Confident AI (DeepEval Cloud)](https://www.confident-ai.com/)** | $200 / month (Starter Plan) | Free tier available (capped at 5 test runs per week) | **$2.2M Raised** (YC W25; ~$550K ARR) | Cloud dashboard for open DeepEval framework, team dataset management & online scoring |

---

## 💻 Open-Source AI Evaluation Frameworks 🔓

Open-source frameworks provide transparent, self-hosted, and CI-friendly metrics for evaluating LLMs, RAG systems, and AI agents.

| Repository | Stars ⭐ | License 📄 | Core Focus 🎯 |
| :--- | :--- | :--- | :--- |
| **[FastChat](https://github.com/lm-sys/FastChat)** | [![FastChat Stars](https://img.shields.io/github/stars/lm-sys/FastChat?style=social&color=white)](https://github.com/lm-sys/FastChat/stargazers) | Apache-2.0 | Arena-style LLM-as-a-Judge benchmark suites (MT-Bench, Chatbot Arena) |
| **[Langfuse](https://github.com/langfuse/langfuse)** | [![Langfuse Stars](https://img.shields.io/github/stars/langfuse/langfuse?style=social&color=white)](https://github.com/langfuse/langfuse/stargazers) | MIT | Open LLM engineering platform with traces, datasets, and prompt eval |
| **[Promptfoo](https://github.com/promptfoo/promptfoo)** | [![Promptfoo Stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social&color=white)](https://github.com/promptfoo/promptfoo/stargazers) | MIT | CLI & YAML-driven eval matrix, red-teaming & CI/CD security test suites |
| **[OpenAI Evals](https://github.com/openai/evals)** | [![OpenAI Evals Stars](https://img.shields.io/github/stars/openai/evals?style=social&color=white)](https://github.com/openai/evals/stargazers) | MIT | Framework for creating and running offline benchmarks and model-graded evals |
| **[DeepEval](https://github.com/confident-ai/deepeval)** | [![DeepEval Stars](https://img.shields.io/github/stars/confident-ai/deepeval?style=social&color=white)](https://github.com/confident-ai/deepeval/stargazers) | Apache-2.0 | Pytest-style LLM evaluation framework with 50+ metrics for RAG & Agents |
| **[Ragas](https://github.com/explodinggradients/ragas)** | [![Ragas Stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=social&color=white)](https://github.com/explodinggradients/ragas/stargazers) | Apache-2.0 | Standard framework for RAG evaluation (faithfulness, context recall/precision) |
| **[LM-Evaluation-Harness](https://github.com/EleutherAI/lm-evaluation-harness)** | [![LM Evals Stars](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness?style=social&color=white)](https://github.com/EleutherAI/lm-evaluation-harness/stargazers) | MIT | Standardized framework for offline LLM benchmark evaluation (MMLU, GSM8K, etc.) |
| **[Cleanlab](https://github.com/cleanlab/cleanlab)** | [![Cleanlab Stars](https://img.shields.io/github/stars/cleanlab/cleanlab?style=social&color=white)](https://github.com/cleanlab/cleanlab/stargazers) | AGPL-3.0 | Data-centric AI evaluation for detecting LLM hallucinations & label noise |
| **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** | [![Phoenix Stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social&color=white)](https://github.com/Arize-ai/phoenix/stargazers) | ELv2 | Open notebook-first tracing, evaluation, and LLM-as-judge experimentation |
| **[Evidently](https://github.com/evidentlyai/evidently)** | [![Evidently Stars](https://img.shields.io/github/stars/evidentlyai/evidently?style=social&color=white)](https://github.com/evidentlyai/evidently/stargazers) | Apache-2.0 | Open-source ML & LLM quality monitoring, regression testing, and data drift |
| **[Argilla](https://github.com/argilla-io/argilla)** | [![Argilla Stars](https://img.shields.io/github/stars/argilla-io/argilla?style=social&color=white)](https://github.com/argilla-io/argilla/stargazers) | Apache-2.0 | Open-source curation and human feedback/eval platform for LLMs & datasets |
| **[Agenta](https://github.com/agenta-ai/agenta)** | [![Agenta Stars](https://img.shields.io/github/stars/agenta-ai/agenta?style=social&color=white)](https://github.com/agenta-ai/agenta/stargazers) | BSD-3-Clause | Developer-centric LLM evaluation, prompt management & playground framework |
| **[TruLens](https://github.com/truera/trulens)** | [![TruLens Stars](https://img.shields.io/github/stars/truera/trulens?style=social&color=white)](https://github.com/truera/trulens/stargazers) | Apache-2.0 | Instrumentation & feedback function evaluation library for RAG and agents |
| **[UpTrain](https://github.com/uptrain-ai/uptrain)** | [![UpTrain Stars](https://img.shields.io/github/stars/uptrain-ai/uptrain?style=social&color=white)](https://github.com/uptrain-ai/uptrain/stargazers) | Apache-2.0 | Open-source LLM evaluation toolkit for monitoring checks & root-cause analysis |

---

## 💖 Support & Community 🌟

Thank you for visiting this repository! If you find this curated collection of AI evaluation tools helpful, please consider showing your support:

- ⭐ **Star** this repository to help others discover it!
- 🍴 **Fork** it to keep a personal reference or contribute new findings.
- 📢 **Share** it with fellow AI engineers, researchers, and developers.
- ☕ **Buy me a coffee**: If you'd like to support ongoing maintenance and curated open-source projects, consider sponsoring via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

Your support is greatly appreciated! 🙌

---

## 📈 Star History
[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-AI-Evaluation-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-AI-Evaluation-Platform&type=date&legend=top-left)

---

## 🤝 How to Contribute 🛠️

Contributions are welcome! Please follow these steps to add or update an entry:

1. **Fork** the repository.
2. Edit `README.md` to add your platform or tool (ensure links are factual and descriptions clear).
3. If adding a SaaS product, include specific pricing, free tier details, and company backing/funding.
4. If adding an open-source repo, include the standard star badge linked to the `/stargazers` URL.
5. Open a **Pull Request** with a brief explanation.

---

## 📜 Disclaimer ⚠️

- This repository is a **community-curated list** provided for educational and research purposes.
- Valuation, funding, and pricing data are gathered from public press releases, corporate disclosures, and developer pricing pages as of 2026.
- Evaluation metrics (including LLM-as-a-Judge) are non-deterministic; always combine automated evaluation suites with domain-specific human oversight.
