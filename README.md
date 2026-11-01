### Hi, I'm Manish 👋

**AI systems engineer.** I design and ship production AI end to end: retrieval, agents, evals, and inference speed and cost.

I work with startups on part-time contracts, and I'm **open to new work now**. I usually start with a 1-week fixed sprint: build an eval set on your real data, measure, fix, re-measure, and hand over a before/after report.

📫 [manishmandal192@gmail.com](mailto:manishmandal192@gmail.com) · 🌐 [manish3451.github.io](https://manish3451.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/manishmandal192/)

---

#### What I've done in production
- **Cut RAG latency ~45s → ~5s (9×)** without losing retrieval quality: learning-to-rank stage, fine-tuned BGE reranker, small-model integration.
- **Multi-agent document automation** (LangGraph) at **95% extraction and validation accuracy**.
- **Hybrid search** (BM25 + embeddings) recommendation system at **90%+ retrieval accuracy**.
- **Eval harness** for prompts and RAG that replaced ~2h of manual review per iteration with automated checks.

#### Things I've built in public
| Project | What it does | Stack |
|---|---|---|
| [**mdshrink**](https://github.com/Manish3451/mdshrink) | MCP server that turns PDFs and screenshots into compact Markdown before they reach Claude Code's context: 5–10× fewer tokens, fully local. On PyPI as `mdshrink-mcp`. | Python · MCP · PyMuPDF · OCR |
| [**CodeArena**](https://github.com/Manish3451/CoderArena) | Real-time 1v1 coding battles with a LangGraph commentary agent. A cheap model detects events and a stronger model narrates them. Evaluated offline for precision, recall, latency and cost. | FastAPI · Next.js · LangGraph · WebSockets |
| [**GPT-2 from scratch**](https://github.com/Manish3451/LLM-From-Scratch) | Full GPT-2-style model: tokenisation, multi-head attention, pretraining, then fine-tuned for spam classification at 97%+ accuracy. | PyTorch |
| [**Multi-Document RAG**](https://github.com/Manish3451/Multi_Doc_Rag) | Upload PDFs, DOCX and text, ask questions, and get answers with citations. | LangChain · ChromaDB · Streamlit |

#### How I work
**Eval first, then build.** Every number I report, I measured. I aim for systems that cite their sources, say "I don't know" when they should, and are fast and cheap enough to run.

#### Toolbox
`Python` `PyTorch` `LangGraph` `LangChain` `RAG` `Hybrid search` `Rerankers` `Evals` `MCP` `FastAPI` `Azure` `SQL`

---
<sub>Based in Hyderabad, India · Works across US, UK and EU time zones</sub>
