# Aditya Puttaparthi Tirumala

Principal Data Scientist | Causal Inference & Marketing Science | AI / LLM Systems

I lead a team of 8 data scientists. Most of my work is at the intersection of causal inference, marketing mix modeling, and LLM-powered decision support. The hard part in practice is not modeling—it’s turning model outputs into decisions people trust. That’s where I focus.

---

## Focus

- Marketing mix modeling and scalable incrementality testing with explicit causal structure
- Turning complex models into decision-ready insights
- Agentic LLM systems built on top of statistical models, not in place of them
- Time series modeling where interpretability is as important as accuracy

---

## SAGE — AI Copilot for Marketing Mix Modeling

[SAGE](https://github.com/adityapt/SAGE) is an AI copilot for interacting with MMMs via natural language. It addresses the insight-synthesis gap that most MMM tools leave open.

- Natural language Q&A over MMM outputs
- Automatic visualizations and diagnostics
- Budget optimization with constrained numerical solvers
- RAG-backed explanations grounded in model artifacts and docs

[Live demo](https://SAGEinsights.streamlit.app) · [Repo](https://github.com/adityapt/SAGE)

---

## Cerebro

[Cerebro](https://github.com/adityapt/cerebro) is an agentic system that generates, validates, and executes Bayesian MMM code end-to-end. Agents infer an MMM spec (channels, controls, outcome) from your CSV, then orchestrate six modules—exploration, preprocessing, modeling (NumPyro/JAX), diagnostics, optimization, visualization—with no fixed templates. Hybrid validation (static, API, JAX tracing, execution) with self-healing and optional resume from any stage. Supports modular or monolithic generation and multiple LLM backends (OpenAI-compatible, Ollama, vLLM, MLX).

[Repo](https://github.com/adityapt/cerebro)

---

## llm-copilot

[llm-copilot](https://github.com/adityapt/llm-copilot) is an experimental project on LLM-orchestrated analytical workflows around MMMs: tool-calling and orchestration, RAG over model outputs and benchmarks, scoped code execution, and integration with Databricks, Snowflake, BigQuery. Modular by design—where I test ideas before they become products.

---

## DeepCausalMMM

Creator and maintainer of [DeepCausalMMM](https://github.com/adityapt/deepcausalmmm), an open-source Python package for MMM that combines deep learning with causal structure. Design principle: interpretability and causal structure over black-box accuracy.

- GRU-based temporal modeling for adstock and lag effects
- DAG-based causal graphs for channel interactions
- Hill-type response curves for saturation and optimization
- Multi-region modeling with shared structure and local effects

`pip install deepcausalmmm` · [Docs](https://deepcausalmmm.readthedocs.io)

A JOSS paper is under review.

---

## Background

**Causal inference:** MMM, DAGs, causal discovery (NOTEARS, PC, GES), treatment effects, counterfactual reasoning, budget allocation under uncertainty.

**ML & time series:** GRU/LSTM, Bayesian and frequentist methods, diagnostics and failure analysis.

**LLM systems:** Agentic architectures and tool calling, RAG and vector search, evaluation and guardrails for analytical use cases.

[ORCID](https://orcid.org/0009-0008-9495-3932)

---

## Current interests

Multi-agent LLM systems for analytics, hybrid RAG (structured + unstructured), causal discovery in high-dimensional time series, uncertainty quantification in decision-focused ML, privacy-aware and federated MMMs.

---

Good models explain why something happened. Great systems help people decide what to do next. That’s the bar I aim for.

---

**Contact**

- [LinkedIn](https://www.linkedin.com/in/adityapt/)
- [GitHub](https://github.com/adityapt)
- [puttaparthy.aditya@gmail.com](mailto:puttaparthy.aditya@gmail.com)

Open to collaboration on LLM systems for analytics, causal inference in production, and open-source data science tooling.
