# Hi, I'm Sejal 👋

**Data professional building data engineering pipelines and applied AI
systems out of messy, real-world data.**

🎓 MS in Data Science, University of Texas at Arlington

🎯 Open to full-time and internship roles in Data Engineering, Data/Business
Analytics, and AI/GenAI Engineering.

📍 Open to relocating anywhere in the US for the right role.

Across my projects I follow the same process: pull in real, often messy,
multi-source data, build a pipeline that holds up against edge cases and
bad inputs, and ship something a non-technical stakeholder can actually use
to make a decision. That shows up as production pipelines and AI systems,
as Power BI, SQL, and Excel dashboards that turn raw data into a decision a
business owner can act on, and as the same process applied to supply chain
and operations problems, from transportation cost modeling to delivery
performance diagnostics.

---

### ⭐ Featured project

**[NL-to-SQL Analytics Agent](https://github.com/SejalKhade/NL-to-SQL-Agent)**

An AI-powered analytics tool that turns plain-English business questions
into validated DuckDB SQL over 750K+ records, so non-technical users can
query the data themselves. RAG retrieval over schema and business
documentation grounds a Claude-generated query, which then passes through
an automated guardrail layer that blocks unsafe or invalid SQL, including
destructive statements, hallucinated tables or columns, and unbounded
scans, before it ever touches the database.

`Python` `LangChain` `RAG` `Claude` `DuckDB` `Streamlit`

---

### 🤖 AI/GenAI Systems & Agent Reliability

- **[NL-to-SQL Analytics Agent](https://github.com/SejalKhade/NL-to-SQL-Agent)** turns plain-English questions into validated DuckDB SQL over 750K+ records, using RAG retrieval combined with an automated guardrail layer that blocks unsafe or invalid SQL before execution. See the featured section above for details.
- **[AgentGuard](https://github.com/SejalKhade/AgentGuard)** is a pre-execution risk scorer for agentic AI actions. It intercepts LLM agent tool calls, scores their blast radius, and enforces human-approval gates before risky actions run.
- **[EnterpriseAI-Handoff-Kit](https://github.com/SejalKhade/EnterpriseAI-Handoff-Kit)** provides post-deployment observability for RAG systems, monitoring retrieval quality, vector store drift, and integration reliability.
- **[Voice QA Harness](https://github.com/SejalKhade/voice-bot-patient-impersonation)** is an automated red-teaming tool that calls a live AI voice agent, drives the conversation with a Claude-powered patient persona designed to probe for weaknesses, and produces evidence-backed defect reports. Every candidate defect passes four verification gates before it can affect a score, and the tool reports what it discarded and why alongside what it kept.
- **[greptile-noise-filter](https://github.com/SejalKhade/greptile-noise-filter)** filters noisy AI-generated PR review comments using Claude, backed by grounding checks and a full audit trail per comment.

### 🛠️ Data Engineering & Infrastructure

- **[Power-Outage-Risk-Pipeline](https://github.com/SejalKhade/Power-Outage-Risk-Pipeline)** is an end-to-end ML pipeline that predicts high-risk electric utilities across all 50 US states, processing 3.44 million raw records from EIA-861 and NOAA Storm Events data down to 1,677 utility-level rows across 28 tracked MLflow experiments. The first models scored a suspicious ROC-AUC of 1.0; tracing it to leakage from SAIDI-derived features and removing them corrected the score to an honest 0.668. Deployed with FastAPI and Docker, with continuous integration through GitHub Actions.
- **[DFW Commercial Rooftop Solar Energy & Grid Readiness Analysis](https://github.com/SejalKhade/DFW-Commercial-Rooftop-Solar-Energy-and-Grid-Readiness-Analysis-)** is a geospatial pipeline that assesses rooftop solar potential across 8,612 commercial and industrial buildings in 11 DFW counties, integrating OSMnx, Census ACS, EPA eGRID, and NREL data. It modeled 15.71 million MWh per year of energy potential and $19.56 billion in installation cost, delivered through an interactive Folium map and a Power BI dashboard.

### 📈 Data Analysis & Business Intelligence

- **[Sales Data Analysis: SQL + Power BI](https://github.com/SejalKhade/Sales-analysis-dashboard_Sql)** builds a sales analytics pipeline from scratch: PostgreSQL for database design, data cleaning, and validation, then Power BI and DAX for an interactive dashboard covering sales performance, team efficiency, and customer behavior.
- **[E-Commerce Sales Analysis Dashboard](https://github.com/SejalKhade/Sales-Analysis-Dashboard-Excel)** answers a defined set of business requirements in Excel, including total sales by region and segment over 12 months and category-wise profit analysis.
- **[HR Analytics Dashboard](https://github.com/SejalKhade/Excel-HR_Analytics)** is an interactive Excel dashboard covering employee demographics, attrition analysis, job satisfaction, and education level, built for HR decision-making.
- **[Spotify Vibe Shift: A/B Test Analysis](https://github.com/SejalKhade/Spotify-Vibe-Shift-A-B-Test-Analysis)** is a product analytics study testing whether emotionally opposite music recommendations increase user engagement and discovery on a streaming platform.

### 📦 Supply Chain, Logistics & Transportation Analytics

- **[Tier Deep](https://github.com/SejalKhade/tier-deep)** is a four-agent LangGraph pipeline that maps a company's Tier 2 and Tier 3 supplier network from public data, anchored on Tesla for a runnable demo. A discovery agent extracts supplier relationships with source citations, a verification agent cross-references each claim against a second source, and an uncertainty agent scores every inferred relationship with a calibrated confidence score, surfacing concentration-risk chokepoints (like shared sub-tier suppliers) and flagging weakly-sourced claims instead of stating them as fact.
- **[Texas HSR + Robotaxi: Transportation Supply Cost Analysis](https://github.com/SejalKhade/Texas-HSR-Robotaxi-Transportation-Supply-Cost-Analysis)** quantifies the cost, emissions, and demand impact of High-Speed Rail paired with autonomous robotaxi first- and last-mile service across three Texas corridors. It ingests seven government datasets (TxDOT, BTS, ERCOT, EPA, Census), validates them with Pandera schema checks, and runs a 1,000-trial Monte Carlo simulation on CO₂ avoidance, backed by 29 passing tests and CI. See the [live dashboard](https://texas-hsr-robotaxi-transportation-supply-cost-analysis-ybo8p2r.streamlit.app/).
- **[Delivery Insights: Identifying Drivers of Delays](https://github.com/SejalKhade/Delivery-Insights-Identifying-Drivers-of-Delays)** diagnoses why on-time delivery rates vary across markets, examining order size, cuisine type, time of day, and dasher-to-order ratio, then translates the findings into operational recommendations.

### 📊 Also worth a look

A few more BI dashboards (Amazon Prime Video, customer/product sales) and
classical ML work, including retail sales forecasting, heart disease risk
classification, and bioinformatics problem sets. See the full list on my
[repositories tab](https://github.com/SejalKhade?tab=repositories).

---

### 🧰 Tech I work with

`Python` `SQL` `pandas` `scikit-learn` `LangChain` `Anthropic Claude` `RAG`
`DuckDB` `FastAPI` `Docker` `GitHub Actions` `Streamlit` `Power BI` `DAX`
`Excel` `GeoPandas`

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/sejallk/) · `[Portfolio URL — fill in]`
