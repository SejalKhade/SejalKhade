# Hi, I'm Sejal 👋

**Data analyst and data engineer. I build pipelines, experiments and AI tools whose numbers hold up when someone checks them.**

🎓 M.S. Data Science, University of Texas at Arlington (May 2026)

📍 Fremont, CA · open to relocating anywhere in the US

🎯 Open to Data Analyst, Data Engineer, Analytics Engineer and AI Engineer roles

Every project here follows the same rule: messy real-world data in, tested pipeline in the middle, a decision someone can act on at the end. Where a result came out weaker than hoped, the README says so.

---

### ⭐ Start here

| If you hire for | Look at | What it shows |
|---|---|---|
| **Analytics / Marketing** | [Email Campaign Incrementality](https://github.com/SejalKhade/email-campaign-incrementality) | A real 64,000-customer randomized email test: +7.7 pt visit lift (p < 0.001), $770 incremental revenue per 1,000 emails, and a targeting rule that cuts sends 45% while keeping 89% of lift. SQL, Python, R. |
| **Data Engineering** | [Construction Job Cost Pipeline](https://github.com/SejalKhade/construction-job-cost-pipeline) | PySpark + dbt + Dagster ELT over $1.35B in budgets: 204,324 cost rows, 1,847 bad rows quarantined, 43 quality checks per run, earned value scores for 60 projects. |
| **AI Engineering** | [AgentGuard](https://github.com/SejalKhade/AgentGuard) | Pre-execution risk scorer for AI agent tool calls: 4 blast-radius tiers, human approval gates for destructive actions, 72 tests at ~99% coverage. |

---

### 📈 Analytics & Experimentation

- **[Email Campaign Incrementality](https://github.com/SejalKhade/email-campaign-incrementality)** measures what two email campaigns *caused* versus a no-email holdout on the Hillstrom randomized test. Checks randomization (SRM, covariate balance), finds the women's email only works on past women's buyers (+7.3 vs +1.1 pts), and replicates every test in R. `SQL` `Python` `R` `statsmodels` `DuckDB`
- **[Delivery Insights](https://github.com/SejalKhade/Delivery-Insights-Identifying-Drivers-of-Delays)** diagnoses on-time delivery across 197,428 DoorDash orders: Market 1 trails Market 5 by 5.7 pts (p < 0.001), with logistic regression, a KPI tree and a Tableau dashboard. `Python` `SQL` `statsmodels` `Tableau`
- **[Spotify Vibe Shift A/B Test](https://github.com/SejalKhade/Spotify-Vibe-Shift-A-B-Test-Analysis)** designs a stratified A/B test with simulated treatment effects: +9.7% engagement overall, and a skip-rate guardrail that points to a targeted launch instead of a full rollout. `Python` `SciPy` `scikit-learn`
- **[Full-Population Control Testing](https://github.com/SejalKhade/Full-Population-Control-Testing-with-Measured-GenAI-Reliability)** tests 6 access controls on all 20,000 synthetic requests instead of a sample, shows a 25-item sample has only a 45.5% chance of finding any exception, and measures Claude's reliability as audit evidence. [Live dashboard](https://sejalkhade-full-population-control-testing--dashboardapp-f337di.streamlit.app/) `Python` `SQL` `Claude` `Streamlit`
- **[Retail BI: Snowflake + dbt](https://github.com/SejalKhade/retail-bi-snowflake-dbt)** models a Snowflake star schema with dbt marts for revenue by channel, category margin and customer LTV, about 25 dbt tests, served through a Flask API to a D3.js dashboard. `Snowflake` `dbt` `SQL` `Flask` `D3.js`
- **[Moxie Field Ops Dashboard](https://github.com/SejalKhade/moxie-field-ops-dashboard)** replaces manual Excel joins across field-service tools with a DuckDB star schema and a 5-endpoint API answering ops KPIs in under 200 ms, with 28 tests and an 85% CI coverage gate. `DuckDB` `SQL` `Flask` `D3.js`

### 🛠️ Data Engineering

- **[Construction Job Cost Pipeline](https://github.com/SejalKhade/construction-job-cost-pipeline)** ingests daily field cost and schedule files with PySpark, models them in dbt, and orchestrates with Dagster. Every bad row lands in quarantine with a reason; a dbt test proves nothing is lost. `PySpark` `dbt` `Dagster` `DuckDB`
- **[Recon Sentry](https://github.com/SejalKhade/recon-sentry)** is a dbt reconciliation pipeline that detects 7 types of financial break across merchants, platform and servicers, with 48 dbt tests, runs on DuckDB and Snowflake, orchestrated in Prefect. `dbt` `DuckDB` `Snowflake` `Prefect`
- **[Power Outage Risk Pipeline](https://github.com/SejalKhade/Power-Outage-Risk-Pipeline)** reduces 3.44M utility-storm records to 1,677 utilities across 28 MLflow experiments. The first models scored a suspicious ROC-AUC of 1.0; tracing it to leakage and removing it gave an honest 0.667. FastAPI, Docker, CI. `Python` `MLflow` `FastAPI` `Docker`
- **[Battery Cell QC Pipeline](https://github.com/SejalKhade/battery-cell-qc-pipeline)** runs 49,500 simulated sensor readings through a Bronze/Silver/Gold DuckDB pipeline with SPC limits and Isolation Forest, catching 14 of 15 defective cells with no healthy cell failed. `DuckDB` `scikit-learn` `Flask` `D3.js`
- **[DFW Rooftop Solar & Grid Readiness](https://github.com/SejalKhade/DFW-Commercial-Rooftop-Solar-Energy-and-Grid-Readiness-Analysis-)** combines OpenStreetMap, Census, NREL and EPA data for 8,612 commercial buildings in 11 counties: 15.71M MWh/yr of solar potential and $19.56B install cost, shown in Folium and Power BI. `GeoPandas` `OSMnx` `Power BI`
- **[Texas HSR + Robotaxi Cost Analysis](https://github.com/SejalKhade/Texas-HSR-Robotaxi-Transportation-Supply-Cost-Analysis)** joins 7 government datasets with Pandera checks and a 1,000-run Monte Carlo: HSR saves $102 per trip vs flying. 29 tests. [Live dashboard](https://texas-hsr-robotaxi-transportation-supply-cost-analysis-ybo8p2r.streamlit.app/) `DuckDB` `Pandera` `Streamlit`

### 🤖 AI / GenAI Systems

- **[AgentGuard](https://github.com/SejalKhade/AgentGuard)** scores every AI agent tool call before it runs. Read-only calls pass with zero added latency; destructive ones wait for 1 or 2 human approvers. CI checks that it blocks the exact action behind a real 13-hour AWS outage. `FastAPI` `Claude` `Docker`
- **[NL-to-SQL Analytics Agent](https://github.com/SejalKhade/NL-to-SQL-Agent)** turns plain-English questions into SQL over 750K+ DuckDB rows using RAG on Chroma, then blocks non-SELECT, unknown-column and failed dry-run queries before execution. `LangChain` `Claude` `Chroma` `DuckDB`
- **[Tier Deep](https://github.com/SejalKhade/tier-deep)** is a 4-agent LangGraph pipeline that maps a company's sub-tier supplier network from 10-K filings and SEC EDGAR, scoring every supplier link on 5 uncertainty signals instead of stating guesses as fact. `LangGraph` `Claude` `Streamlit`
- **[Job Intelligence Agent](https://github.com/SejalKhade/job-intelligence-agent)** is a 6-node LangGraph agent that scores a resume against a job description and rewrites it, cutting per-role prep from 30-60 min to under 60 sec. `LangGraph` `Claude` `Streamlit`
- **[EnterpriseAI Handoff Kit](https://github.com/SejalKhade/EnterpriseAI-Handoff-Kit)** monitors a RAG system after handover. Freshness-aware ranking raised retrieval precision from 0.62 to 0.89 with recall unchanged, and SHA-256 checks prove when embedded text has drifted. `ChromaDB` `Python` `Node`
- **[Greptile Noise Filter](https://github.com/SejalKhade/greptile-noise-filter)** scores AI code-review comments on grounding, actionability, specificity and severity, measuring precision and recall against labeled data instead of claiming them. `Claude` `Streamlit`

### 📦 Supply Chain & Operations

- **[AB Fulfillment & Supply Defect Intelligence](https://github.com/SejalKhade/AB-Fulfillment-and-Supply-Defect-Intelligence)** detects defect anomalies in 5.54M simulated shipments with 9 SQL queries, catching all 3 seeded events with zero false positives, and outputs 18 prioritized escalations to a 13-sheet Excel report. `DuckDB` `SQL` `Excel`
- **[ERP Anomaly Detector](https://github.com/SejalKhade/ERP-anomaly-detector)** runs 5 SQL detectors on a simulated SAP MM dataset of 820 purchase orders, flagging $1M+ in anomalous spend, with a Claude NL-to-SQL app on Hugging Face. `SQL` `DuckDB` `Claude` `Streamlit`

### 📊 Also worth a look

Earlier BI work in SQL, Power BI and Excel ([sales analysis](https://github.com/SejalKhade/Sales-analysis-dashboard_Sql), [e-commerce](https://github.com/SejalKhade/Sales-Analysis-Dashboard-Excel), [HR analytics](https://github.com/SejalKhade/Excel-HR_Analytics), [Prime Video](https://github.com/SejalKhade/Amazon-Prime-Video-Dashboard-using-Power-BI)) and classical ML ([retail forecasting](https://github.com/SejalKhade/Retail-sales-forecasting-), [heart disease risk](https://github.com/SejalKhade/Heart-Disease-Prediction-using-Machine-Learning)). Full list on the [repositories tab](https://github.com/SejalKhade?tab=repositories).

---

### 🧰 Tech I work with

**Analysis & stats:** `SQL` `Python` `R` `pandas` `statsmodels` `SciPy` `scikit-learn` · A/B and incrementality testing

**Data engineering:** `dbt` `Snowflake` `DuckDB` `PySpark` `Dagster` `Prefect` `Pandera` · GitHub Actions CI

**BI:** `Tableau` `Power BI` `DAX` `Excel` `Streamlit` `D3.js`

**AI:** `Claude API` `LangChain` `LangGraph` `Chroma` `RAG` · `FastAPI` `Docker` `MLflow`

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/sejallk/)
