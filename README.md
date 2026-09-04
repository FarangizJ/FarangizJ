# Farangiz Jurakhonova

**Data scientist — forecasting, data pipelines, applied AI.**
M.Sc. Business Analytics, Central European University (Vienna).

![Ex-ante is the honest headline](https://raw.githubusercontent.com/FarangizJ/capstone-project/main/outputs/forecast_scoreboard_exante.png)

<sub>Six demand-forecast specifications on one shared hold-out. The hollow markers are the
conditional backcast — the flattering number. The bars are ex-ante error, which is what you
actually get when the model has to forecast its own drivers. Every single-country model posts a
**negative** R²; only the pooled four-country panel with fixed effects generalises, at
**6.08% MAPE, R² +0.10**. That is the number I put in front of stakeholders.
[See the analysis →](https://github.com/FarangizJ/capstone-project)</sub>

---

## What I actually do

Most of the difficulty in analytics is upstream of the model. I spend my time reconciling
disconnected source systems, building the validation that stops bad records reaching a
dashboard, and making sure the number that reaches a decision-maker is the defensible one
rather than the impressive one.

Three things I care about, with the evidence attached:

**Pipelines that fail loudly.** Four disconnected source systems plus 10+ APIs merged into one
governed dataset with automated quality gates and column-level lineage — every field documented
with its meaning, its source and its owner. Shipped as a containerised application that
auto-releases on commit.

**Scale without losing the thread.** 16.2M intraday trade records across 15,140 fragmented
files consolidated into one integrity-verified dataset, then an automated anomaly detector that
surfaces *systematic* failure modes instead of one-off outliers.

**Measurement that doesn't flatter itself.** Competing specifications benchmarked on a shared
hold-out, uncertainty quantified with bootstrapping and Monte Carlo, drivers attributed with
SHAP and permutation importance rather than coefficient size.

---

## Selected work

### [Forecasting Uzbekistan's Power-Sector Transition to 2040](https://github.com/FarangizJ/capstone-project)
`Python` · `scikit-learn` · `Plotly Dash` · `Docker` — **[▶ live dashboard](https://huggingface.co/spaces/feyajk/uzbekistan-power-tracker)**

Demand, generation mix, CO₂ pathways and supply-adequacy signals to 2040, built with ILF
Consulting Engineers. An 84-column master dataset assembled from IEA, IRENA, World Bank, Ember
and StatSUZ, with a provenance table tracing every derived field back to source. Six model
specifications benchmarked; three scenarios; a bilingual Dash application containerised and
deployed. The result senior stakeholders used to prioritise capital investment — including a
planned 500 MW data-centre load.

### [Weather and forecast error in EPEX SPOT intraday power markets](https://github.com/FarangizJ/intraday-power-analysis)
`Python` · `pandas` · `CatBoost` · `ENTSO-E` · `Open-Meteo`

As wind and solar take a larger share of the mix, prices in the hours before delivery are set
less by demand than by the *error* in the forecast the market already priced in. 16.2M trade
records across the German and Austrian bidding zones, joined to weather at delivery-hour
resolution using a documented wind-speed extrapolation method, with feature attribution over
forecast-error asymmetry.

### [Near-real-time sentiment scoring on AWS](https://github.com/FarangizJ/aws-news-sentiment-analysis)
`AWS Bedrock` · `Lambda` · `S3` · `Python`

News ingestion and sentiment pipeline on Bedrock, S3 and Lambda. Built for the CEU Hackathon
for Social Impact, City of Vienna challenge.

**Also:**
[spark-delta-lake-vehicle-market-analysis](https://github.com/FarangizJ/spark-delta-lake-vehicle-market-analysis) — distributed processing with Delta Lake storage ·
[energy-forecasting-austria](https://github.com/FarangizJ/energy-forecasting-austria) — time-series benchmarking on Austrian demand ·
[airbnb-eu-price](https://github.com/FarangizJ/airbnb-eu-price) — which listing attributes actually move price across European cities

---

## Stack

| | |
|---|---|
| **Languages** | Python · R · SQL (PostgreSQL, MySQL, DuckDB) · Advanced Excel + VBA |
| **Data engineering** | ETL design · Apache Spark · Delta Lake · dbt · Docker · CI auto-release · quality gates and column-level lineage |
| **Modelling** | scikit-learn · time-series forecasting · SHAP and permutation importance · bootstrapped and Monte Carlo uncertainty · TimeSeriesSplit |
| **Cloud** | AWS — Bedrock, S3, Lambda |
| **Applied AI** | GenAI copilots in daily engineering work, with independent verification · prompt engineering · graduate coursework in AI Engineering and LLM Integration |
| **Visualisation** | Plotly Dash · Tableau · Power BI |
| **Governance** | Data Governance Certificate (IE University, 100/100) · DAMA-DMBOK |

---

## Teaching

I founded my university's first analytics programme as head of the RStudio Analytics Club and
ran hands-on workshops for **50+ students**. I also publish a Power BI course on YouTube in
Uzbek — most analytics material simply doesn't exist in my first language, and that seemed like
a fixable problem.

---

📍 **Bellevue, WA** — open to data science, analytics and data engineering roles in the Seattle area.
🌐 English · Russian · Uzbek · German · Persian

[LinkedIn](https://www.linkedin.com/in/farangiz-jurakhonova/) · [abdumalikovaf18@gmail.com](mailto:abdumalikovaf18@gmail.com)
