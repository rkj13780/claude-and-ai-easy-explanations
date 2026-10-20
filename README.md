# AI Automation Educational Repository

This repository contains the full content of the **Claude & AI, Properly Explained** interactive series originally hosted at https://ai-automation-with-rakesh.netlify.app.

The site is a 7‑part series covering:

| # | Topic | Description |
|---|-------|-------------|
| 1 | **APIs, Properly Explained** | The waiter‑and‑kitchen fundamentals: requests, JSON, headers, auth, Postman, and calling real APIs. |
| 2 | **AI Web vs. API Economics** | Buffet vs. à la carte: why a subscription can’t power an app, and what AI actually costs at scale. |
| 3 | **MCP (Model‑Centric Programming)** | How to think about prompting, chaining, and managing LLM output in a production‑ready way. |
| 4 | **RAG (Retrieval‑Augmented Generation)** | Techniques for grounding LLMs with external knowledge sources, vector stores, and hybrid search. |
| 5 | **Multi‑Agent Systems** | Building cooperative agents, task decomposition, and orchestration patterns. |
| 6 | **Open‑Source AI** | Overview of the ecosystem, model zoo, quantization, and running models locally. |
| 7 | **Production Readiness** | Monitoring, observability, safety guards, cost‑control, and CI/CD for AI services. |

## Repository Structure

```
educational_repo/
├─ docs/                # Extracted HTML pages for each topic
│   ├─ apis.html
│   ├─ economics.html
│   ├─ mcp.html
│   ├─ rag.html
│   ├─ agents.html
│   ├─ opensource.html
│   └─ production.html
├─ index.html           # Original home page (static snapshot)
└─ README.md            # This file
```

## How to Use

1. Open any of the HTML files in `docs/` with a web browser to view the offline version of the interactive guide.
2. The `index.html` file replicates the landing page of the original site and includes the navigation UI for the topics.
3. All external assets (fonts, images, scripts) are loaded from the original CDN URLs, so internet access is required for full rendering.

Feel free to fork, modify, or integrate these materials into your own learning resources or training programs.
