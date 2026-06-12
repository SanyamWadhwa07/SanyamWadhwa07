# Sanyam Wadhwa

3rd-year CS @ TIET · Agentic AI & LLM Engineering · Graduating 2027

I build AI systems that work in production — agents that reason, retrieve, and remember. I read papers and then ship things.

Currently targeting **agentic AI / LLM engineering internships** for Jun–Jul 2026.

[Portfolio](https://sanyamwadhwa.tech) · [LinkedIn](https://linkedin.com/in/sanyamwadhwa07) · [sanyamwadhwa.in@gmail.com](mailto:sanyamwadhwa.in@gmail.com)

---

## Work that matters

### [FlowSync](https://github.com/SanyamWadhwa07/flowsync) — Branch-aware AI memory for coding agents
MCP server giving agents persistent project context backed by AWS Bedrock + DynamoDB. Event-driven pipeline extracts decisions and risks from git diffs. Branch-aware RAG at **~1.2s p50 retrieval latency**.

### [KONTA](https://github.com/SanyamWadhwa07/KONTA) — On-device semantic search over your browsing history
Samsung PRISM hackathon winner. Chrome extension that builds a local knowledge graph from browsing — zero data leaves the device. 3-layer retrieval: BM25 → semantic embeddings → ML re-ranking. **NDCG@5: 0.91 · F1: 0.88 · 84% clustering precision.**

### [NeoSpasm](https://github.com/SanyamWadhwa07) — Multimodal infantile spasm detection
Capstone project with PGIMER clinical collaboration. Multimodal late fusion of EEG + ECG + video for detecting infantile spasms. Deploying on NVIDIA Jetson Nano. EEG pipeline uses Hjorth parameters, PAC, entropy features, GroupKFold CV.

### [Pehchaan](https://github.com/SanyamWadhwa07) — Offline workforce authentication for NHAI
MobileFaceNet fine-tuned for Indian demographics, INT8 quantized to <20MB TFLite, liveness detection (blink/head-turn/smile), cosine similarity thresholding. Works fully offline on constrained hardware.

### [AgentMem](https://github.com/SanyamWadhwa07) — Adaptive memory for mobile agentic systems
Samsung AX Hackathon submission. Three-layer memory (LSTM + GNN + Transformer) with TD3 RL for context-aware memory management. Unified two-plane memory orchestration with agent tool-graph traces.

### [Garuda AI](https://github.com/SanyamWadhwa07) — Self-hosted hardware-aware local AI agent
FastAPI + Ollama + AirLLM. Dynamically routes queries to models based on hardware constraints. PWA frontend. Runs entirely on local hardware.

---

## Stack

**Core:** Python · C++ · TypeScript · SQL  
**AI/ML:** PyTorch · LangGraph · LangChain · HuggingFace · QLoRA · TFLite · ONNX · RAG · MCP  
**Infra:** FastAPI · PostgreSQL · DynamoDB · Docker · AWS Bedrock · GitHub Actions  
**Frontend:** Next.js · React · Tailwind

---

## Research & competition

- **Kaggle** — Visual Geometry Math Challenge (Qwen2.5-VL-3B QLoRA, 0.2263 score), Instructional Delta Synthesis (T5 fine-tuning, 0.436 EWDS), Knowledge Graph QA (0.88+ F1)
- **COE-UQ AI Research Intern** — LLM safety guardrails, PyTorch, HuggingFace
- **TIET Research Lab** — Multi-agent mental health chatbot

---

## Currently

Building toward Forward Deployed Engineer roles at AI-first companies. Actively working on NeoSpasm (PGIMER clinical deployment) and pushing Kaggle leaderboards in multimodal + NLP tracks.

Open to internships where I can work on hard AI infrastructure problems, not just integrate APIs.
