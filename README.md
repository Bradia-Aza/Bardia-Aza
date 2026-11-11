# Hi, I'm Bardia Azami

**Machine Learning Engineer · Canada**

I build AI systems and like understanding how they work under the hood. I started as an electrical engineer designing PCBs and bare-metal firmware for embedded vision devices, then moved up the stack into medical imaging, vision-transformer research, and now LLM systems engineering: RAG pipelines, agentic tooling, LLM gateways, and text-to-SQL.

Most of my recent work treats model output as untrusted input. I spend my time on the guardrails that make it safe, bounded, and testable.

[LinkedIn](https://www.linkedin.com/in/bardia-azami-a24579258/) · [Email](mailto:bard.azami@gmail.com)

---

## What I'm working on

- **AITOS**: a local runtime that sits between AI coding agents (Claude Code, Codex CLI) and LLM providers, trimming redundant context before each request goes out. I own the LLM gateway and provider interception layer. *(Proprietary, built with a team of three.)*
- **CareerFlow AI**: an LLM pipeline that tailors a LaTeX resume and cover letter to a job posting with one command, ongoing.

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| **AITOS** (2026) | LLM gateway for AI coding agents. Provider-neutral request model, event-by-event SSE forwarding, fail-open review hand-off, and a per-request capture pipeline so every saving can be audited. ~690 offline tests. | Python, FastAPI, asyncio, LiteLLM, SQLite |
| **DataMind** (2026) | Conversational BI: ask a database a question in plain language, get back an auditable answer, table, and chart. Every generated query passes an AST-based SQL guard that fails closed, tested against a hostile-input corpus as a CI hard gate. Runs on PostgreSQL, MySQL, SQL Server, and Oracle. | Python, FastAPI, React/TypeScript, SQLGlot, Docker |
| **CareerFlow AI** (2025) | Two-pass Miner→Judge requirement extraction, a constraint engine that guarantees a fixed page budget, one provider interface across Anthropic, OpenAI, and Gemini, plus a Chrome extension. 73 offline tests, no LLM calls in CI. | Python, Pydantic, FastAPI, LaTeX, pytest |
| **WW2 Historical RAG** (2024) | Semantic chunking, dense retrieval plus extractive QA, source attribution on every answer, and a confidence floor that says "not confident enough" instead of guessing. | PyTorch, Hugging Face, sentence-transformers, Gradio |
| **Ottawa Rental Market ETL** (2024) | Done with the City of Ottawa through Algonquin College. Browser-driven scraping, SHA-256 listing IDs, and snapshot diffing to derive Days-on-Market figures the source never published. | Python, Playwright, pandas |
| **Gesture-Based Robot Control** (2024) | ROS 2 stack across four packages: hand gestures drive bounded motion commands, and the robot answers with speech, all running concurrently without freezing. | ROS 2, OpenCV, Python |
| **Pistachio Analysis** (2024) | Handcrafted features fused with CNN embeddings, SMOTE inside the pipeline to avoid leakage, plus outlier detection and clustering that surfaced mislabeled samples. | scikit-learn, TensorFlow/Keras |

---

## Research

- **ViT vs. CNNs for outdoor fire detection** (University of Isfahan, 2022–2023). Benchmarked five backbones on a 10,656-image dataset I curated. The vision transformer reached 95.7% accuracy with 13 false positives, against 30–46 for the CNN baselines.
- **Edge-preserving low-dose CT reconstruction** (Behyar Sanaat Sepahan, 2021–2022). A differentiable Sobel layer and a hybrid perceptual/pixel loss to keep organ boundaries sharp, trained on 10,000+ synthetic low-dose pairs.

---

## Tech stack

**Languages:** Python, C++, SQL, Bash, MATLAB, Embedded C
**ML / DL:** PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, XGBoost, LightGBM, OpenCV
**LLM & RAG:** LangChain, LlamaIndex, FAISS, ChromaDB, vLLM, LiteLLM, OpenAI / Anthropic APIs, Pydantic
**Data:** pandas, NumPy, PySpark, Airflow, dbt, Kafka, PostgreSQL, MongoDB
**MLOps & Cloud:** AWS (SageMaker, S3, EC2, Lambda), Docker, Kubernetes, MLflow, Weights & Biases, FastAPI, GitHub Actions, pytest
**Hardware:** Altium Designer, AVR microcontrollers, UART/SPI/I2C, PCB design

---

## Background

- Graduate Certificate, AI & Software Development, Algonquin College (2025, CGPA 3.82)
- B.Sc. Electrical Engineering, University of Isfahan (2022)
- 1st place, Sharif DataDays 2022 · 3rd place, Torob Data Challenge 2023
- AWS Certified Solutions Architect Associate course (2026)
