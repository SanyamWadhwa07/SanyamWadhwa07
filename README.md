### Hi, I'm Sanyam 👋

I build AI systems and the engineering that keeps them correct: agent pipelines, retrieval, evals and the backends under them. Final year Computer Engineering at Thapar Institute, graduating 2027. **Open to 6 month internships from January 2027**, in India or remote.

[sanyamwadhwa.tech](https://sanyamwadhwa.tech) · [Blog](https://sanyamwadhwa.tech/blog) · [Resume](https://sanyamwadhwa.tech/resume) · [Open source](https://sanyamwadhwa.tech/open-source) · [LinkedIn](https://www.linkedin.com/in/sanyamwadhwa07) · [Email](mailto:sanyamwadhwa.in@gmail.com)

### Selected work

| Project | What it does | Measured |
| --- | --- | --- |
| [**PaperMind**](https://github.com/SanyamWadhwa07/PaperMind) | Multi-agent reader that turns an arXiv ID into the paper's findings, methods, datasets and figures from the full text, with Gemini → Groq → Ollama failover | Figure extraction F1 **0.972**, all **122** figures recovered across 16 papers |
| [**Duet**](https://github.com/SanyamWadhwa07/duet) | Live coding-interview room on an operational transformation sync engine written from scratch (React, Monaco, Node, PostgreSQL) | Lost keystrokes for two typists **49% → 0**, **30,000** randomized convergence tests per push |
| [**Veridex**](https://github.com/SanyamWadhwa07/Redrob-Ranker) | Candidate ranker with BM25 + FAISS retrieval and a graded auditor; every score can be rebuilt by hand | **100,000** profiles ranked in ~30 s on CPU, **3,492** keyword stuffers caught, none in the top 100 |
| [**Onramp**](https://github.com/SanyamWadhwa07/onramp) | Agent skill for Claude Code, Codex, Cursor and 60+ coding agents that builds a guided tour of any codebase, every claim cited to source lines | Checker caught **all 525** planted citation errors, zero false alarms on 200 real ones |
| [**NeoSpasm**](https://github.com/SanyamWadhwa07/Neospasm) | ML model and clinician dashboard that detects infantile spasms from raw hospital EEG | AUROC **0.96** on a 100 child cohort, **1st place** at PGIMER |
| [**KONTA**](https://github.com/aahil-khan/KONTA) | Chrome extension that turns browsing history into a searchable knowledge base, every model running in the browser via ONNX | NDCG@5 **0.47 → 0.77** with an ML re-ranker, **Samsung PRISM** winner |
| [**Pehchaan**](https://github.com/SanyamWadhwa07/Pehchaan) | Offline face verification for workers at construction site gates, fully on the phone | **97%** true accepts, under 1% false accepts, 3.8 MB quantized MobileFaceNet |

### Open source

<!-- oss starts -->
- **In review** · [fix(cli): read front matter after a byte order mark](https://github.com/atlanai/ai-registry/pull/275) in `atlanai/ai-registry`
- **In review** · [Read and write text files as UTF-8 so the corpus loads on Windows](https://github.com/atlanai/decision-bench/pull/79) in `atlanai/decision-bench`
- **Merged** · [feat(cli): report duplicate skills in status](https://github.com/atlanai/ai-registry/pull/230) in `atlanai/ai-registry`
- **Merged** · [updated app dev resources](https://github.com/MicrosoftStudentChapter/Tech-Resources/pull/14) in `MicrosoftStudentChapter/Tech-Resources`
- **Merged** · [added resources of DSA and Cyber Security](https://github.com/MicrosoftStudentChapter/Tech-Resources/pull/12) in `MicrosoftStudentChapter/Tech-Resources`
- **Merged** · [core name added](https://github.com/MicrosoftStudentChapter/mlsctiet/pull/123) in `MicrosoftStudentChapter/mlsctiet`
- **Merged** · [homepage done](https://github.com/MicrosoftStudentChapter/mlsctiet/pull/120) in `MicrosoftStudentChapter/mlsctiet`
- **Merged** · [favicon changed](https://github.com/MicrosoftStudentChapter/Linky/pull/14) in `MicrosoftStudentChapter/Linky`
<!-- oss ends -->

Updated daily by a GitHub Action. Reviews and issue work at [sanyamwadhwa.tech/open-source](https://sanyamwadhwa.tech/open-source).

### Writing

- [MCP vs CLI: I measured what each one actually costs an agent](https://sanyamwadhwa.tech/blog/mcp-vs-cli-tokens)
- [How to evaluate an agent system for bottlenecks and accuracy](https://sanyamwadhwa.tech/blog/agent-pipeline-evals)

### Experience

- **AI Research Intern, COE-UQ, Thapar** (Jun to Jul 2025): safety pipeline for a mental health chatbot. Emotion, sentiment and safety modules run in parallel ahead of a QLoRA + RLHF tuned LLaMA, tested against 50+ adversarial prompts.
- **Software Engineering Intern, Thapar** (Feb to Nov 2025): the exam datesheet generator the institute runs on, live at exams.thapar.edu. A constraint solver over 400+ variables, 3x faster generation, zero clashes by construction.
- **CTO, EvexFitness** (May to Oct 2024): led a 5 person team shipping a fitness platform with real-time exercise form checking from the camera.

### Recognition

- 🥇 1st place, Pediatric Epilepsy Research Symposium, PGIMER Chandigarh (2026), for NeoSpasm
- 🏆 Winner, Samsung PRISM Web Agent Hackathon (2026), for KONTA
- Top 200, Amazon ML Challenge, 2025 and 2026

### Stack

- **Languages**: Python, TypeScript, C++, SQL
- **AI/ML**: PyTorch, Hugging Face, LangGraph, RAG, BM25 + FAISS, LLM evals, llama.cpp, ONNX
- **Backend**: FastAPI, Node.js, PostgreSQL + pgvector, MySQL, DynamoDB, WebSockets
- **Infra**: Docker, AWS (Lambda, DynamoDB, Bedrock), GitHub Actions, Linux
