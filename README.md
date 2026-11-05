<div align="center">

# Hi, I'm Varsha Das 👋

**Data Scientist · PGDBA @ IIM Calcutta · IIT Kharagpur · ISI Kolkata**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/varsha-das)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:varshadba2027@email.iimcal.ac.in)


</div>

---
## 🧭 About Me

I'm a graduate student in the **PGDBA program** — a joint initiative of IIM Calcutta, IIT Kharagpur, and ISI Kolkata — working at the intersection of business strategy, machine learning, and mathematical modelling.

My work focuses on building rigorous, reproducible data science pipelines: from exploratory analysis to production-ready scripts. I care deeply about the *why* behind a model, not just the metric.

- 🎯 Interests: **Predictive Modeling · Machine Learning · Statistical Inference · Time Series Forecasting · Risk Analytics · Python · SQL · Power BI · Agentic AI**
- 💬 Ask me about: **regression and classification modelling · time series & volatility · supply-chain and logistics analytics · operations research & optimization · customer analytics · credit & portfolio risk · explainable ML · multimodal deep learning · RAG & LLM applications**

---
## 📌 Projects

### Competitions
| Project | What & Why | Stack |
|---------|------------|-------|
| [**🥈 1st Runner-Up · Trilytics '25: Farmer Income Prediction**](https://github.com/Varsha-Das/trilytics-farmer-income-prediction) | National analytics case competition (PGDBA Conclave × L&T Finance). Predicted farmer income for credit assessment of the unbanked; LightGBM + Optuna reached **20.8 % MAPE**, down from 36 % with OLS. | `LightGBM` `Optuna` `XGBoost` `SHAP` |
| [**🏁 National Finalist · The Quantum Trial: Attrition Copilot**](https://github.com/Varsha-Das/quantum-trial-attrition-copilot) | Analytics case competition at Great Lakes Gurgaon (Crest 14). Segment-wise attrition models plus a GenAI Copilot that turns risk drivers into manager talking points before the weekly 1:1. | `CatBoost` `SHAP` `GenAI` |

### Academic (PGDBA coursework)
| Project | What & Why | Stack |
|---------|------------|-------|
| [**Multimodal Semantic Pricing Engine**](https://github.com/Varsha-Das/multimodal-semantic-pricing-engine) | Amazon ML Challenge 2025: predicts product prices by fusing DeBERTa-v3 text and SigLIP-2 image embeddings. Test SMAPE 44.3 %, served through a FastAPI app. | `PyTorch` `Transformers` `FAISS` `FastAPI` |
| [**Adaptive Portfolio Risk Analytics**](https://github.com/Varsha-Das/adaptive-portfolio-risk-analytics) | Portfolio allocation that adapts to market regimes, combining hierarchical risk parity, regime switching and macro sentiment. | `Python` `HRP` `HMM` `Risk` |
| [**Aluminium Price & Volatility Forecasting**](https://github.com/Varsha-Das/aluminium-price-volatility-forecasting) | Compares ARIMA, the GARCH family, SETAR and VAR on 32 years of prices. VAR(1) with oil and USD is most accurate at 3.24 % MAPE. | `statsmodels` `arch` `VAR` |
| [**Dark-Store Logistics Optimization**](https://github.com/Varsha-Das/dark-store-logistics-optimization) | Placed 11 dark stores across São Paulo and routed deliveries and returns on one shared network. Routing cost fell **31 %** and vehicle count **34 %**. | `OR-Tools` `PuLP` `XGBoost` `K-Means` |
| [**Topological Dynamic Community Detection**](https://github.com/Varsha-Das/topological-dynamic-community-detection) | Reproduces and extends an AAAI 2024 paper on persistent-homology community detection. Node2Vec + GraphSAGE beats the paper on ACC, NMI and ARI. | `PyTorch` `GUDHI` `GNNs` |
| [**CLV RFM-Based Regression**](https://github.com/Varsha-Das/clv-rfm-regression) | Predicts customer lifetime value on Olist data using VIF checks, PCA, Elastic Net and hurdle models. R² improved from 0.54 to **0.81**. | `scikit-learn` `statsmodels` |
| [**US Airline Delay Analysis**](https://github.com/Varsha-Das/us-airline-delay-analysis) | Six Sigma DMAIC study of 7M flights. Found that 75 % of delay minutes are controllable; a model of knock-on delays reaches R² 0.70. | `statsmodels` `SciPy` `K-Means` |
| [**Pharma Cold-Chain Optimization**](https://github.com/Varsha-Das/pharma-cold-chain-optimization) | EOQ, transportation LP and Monte Carlo simulation for a vaccine and biologics cold chain, keeping service levels above 99.8 %. | `SciPy (HiGHS)` `NumPy` `Monte Carlo` |

### Havish M Consulting (internship assessment)
| Project | What & Why | Stack |
|---------|------------|-------|
| [**Copper Price Risk & Hedging**](https://github.com/Varsha-Das/copper-price-risk-hedging) | Tested ML forecasts against the naive forecast for a cable maker's copper costs. No model beat naive on tradable prices, so the work turned to risk: calibrated GARCH bands pass formal backtests and a futures hedge cuts cost variance by **73 %**. | `statsmodels` `arch` `LightGBM` `SHAP` |
| [**Predictive Maintenance for Cement Plants**](https://github.com/Varsha-Das/predictive-maintenance-cement) | Flags kiln and mill breakdowns 7 days ahead: catches **30 of 33** against 21 for tuned alarms within the same inspection budget, and also predicts the failure mode. | `LightGBM` `Isolation Forest` `SHAP` |
| [**Retail Loyalty Segmentation**](https://github.com/Varsha-Das/retail-loyalty-segmentation) | Six stable behavioural segments (ARI 0.91) explain about **3× more** of next-year behaviour than spend tiers. Combined with RFM into a targeting grid, plus LLM-drafted campaign briefs. | `scikit-learn` `k-means` `SHAP` `Groq LLM` |

### Personal
| Project | What & Why | Stack |
|---------|------------|-------|
| [**RBI Monetary Policy RAG**](https://github.com/Varsha-Das/RBI_MPR_RAG) | Q&A over several RBI Monetary Policy Reports that tracks how the policy stance changes between reports. Uses hybrid BM25 and dense retrieval with Cohere reranking, an evidence check and Llama 3.1, and cites its sources. | `LangChain` `BM25` `Cohere` `Llama 3.1` |
| [**Explainable Credit Default Risk**](https://github.com/Varsha-Das/credit-default-xai) | Credit-card default model built with XGBoost and recall-tuned thresholds. It explains its scores with SHAP and LIME, checks fairness by sex, compares against a Keras DNN and runs in a Streamlit dashboard. | `XGBoost` `SHAP` `LIME` `Streamlit` |
| [**Lead Scoring & Prioritization**](https://github.com/Varsha-Das/lead-scoring-prioritization) | Built a lead-scoring model after a leakage audit and added a decision layer that works within 200 sales calls a day. Priority leads convert **2.37×** better than average. | `scikit-learn` `Logistic Regression` |

---
## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![AMPL](https://img.shields.io/badge/AMPL-Optimization-FF6B35?style=for-the-badge&logoColor=white)

**Data & ML**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4051B5?style=for-the-badge&logoColor=white)

**Databases & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Workflow & Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Varsha-Das&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Varsha-Das&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Varsha-Das&theme=github-dark-blue&hide_border=true)](https://git.io/streak-stats)

</div>

---

<div align="center">
<sub>Built with Git · Maintained with discipline · Updated with intent</sub>
</div>
