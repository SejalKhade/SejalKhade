# Hi, I'm Sejal 👋

**AI Engineer — LLM Applications, RAG & Agent Reliability | Data Engineering background**

I build systems that let people query and trust data through natural language —
and the guardrails that keep those systems safe when they're wrong. My recent
work sits at the intersection of applied GenAI and production reliability:
retrieval-augmented generation, agentic AI, and the validation/observability
layers that make LLM systems safe to actually ship.

---

### ⭐ Featured project

**[NL-to-SQL Analytics Agent](https://github.com/SejalKhade/NL-to-SQL-Agent)**
An AI-powered analytics tool that turns plain-English questions into validated
DuckDB SQL — so non-technical users can query 750K+ records directly. RAG
retrieval over schema/business docs grounds a Claude-generated query, which
then passes through an automated guardrail layer that blocks unsafe or invalid
SQL (destructive statements, hallucinated tables/columns, unbounded scans)
*before* it ever touches the database.
`Python` `LangChain` `RAG` `Claude` `DuckDB` `Streamlit`

---

### 🛡️ AI Agent Safety & Reliability

The theme running through my recent projects: LLM systems fail in specific,
predictable ways — so I build the layer that catches that before it reaches
production.

- **[AgentGuard](https://github.com/SejalKhade/AgentGuard)** — pre-execution risk scorer for agentic AI actions. Intercepts LLM agent tool calls, scores blast radius, and enforces human-approval gates before risky actions run.
- **[EnterpriseAI-Handoff-Kit](https://github.com/SejalKhade/EnterpriseAI-Handoff-Kit)** — post-deployment observability for RAG systems: retrieval quality, vector store drift, and integration reliability monitoring.
- **[greptile-noise-filter](https://github.com/SejalKhade/greptile-noise-filter)** — filters noisy AI-generated PR review comments using Claude.

### 🛠️ Data Engineering

- **[Power-Outage-Risk-Pipeline](https://github.com/SejalKhade/Power-Outage-Risk-Pipeline)** — end-to-end ML pipeline predicting high-risk electric utilities across 50 US states, combining EIA-861 + NOAA Storm Events data. Deployed via FastAPI + Docker, with CI through GitHub Actions.

### 📊 Data Analysis & ML

- **[Retail-sales-forecasting](https://github.com/SejalKhade/Retail-sales-forecasting-)** — demand forecasting model for retail sales.
- **[Spotify-Vibe-Shift-A-B-Test-Analysis](https://github.com/SejalKhade/Spotify-Vibe-Shift-A-B-Test-Analysis)** — statistical A/B test analysis on listening behavior.
- **[Heart-Disease-Prediction](https://github.com/SejalKhade/Heart-Disease-Prediction-using-Machine-Learning)** — classification model for disease risk prediction.

More on my [repositories tab →](https://github.com/SejalKhade?tab=repositories)

---

### 🧰 Tech I work with

`Python` `SQL` `LangChain` `Anthropic Claude` `RAG` `DuckDB` `FastAPI` `Docker`
`GitHub Actions` `pandas` `scikit-learn` `Streamlit` `Power BI`

### 📫 Reach me

Open to AI Engineer / GenAI Engineer roles — feel free to connect via a repo issue or my resume contact details.
