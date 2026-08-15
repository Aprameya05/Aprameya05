<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:8b5cf6,100:06b6d4&height=220&section=header&text=Aprameya%20Bharadwaj&fontSize=52&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20MLOps%20%E2%80%A2%20Healthcare%20AI%20%E2%80%A2%20CS%20%26%20Design&descAlignY=58&descSize=17&descColor=c7d2fe" width="100%"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=15&duration=3500&pause=1200&color=818CF8&center=true&vCenter=true&multiline=true&repeat=true&width=760&height=60&lines=SIH+2025+National+Winner+%7C+6+IP+India+Patents+%7C+IEEE+%26+Taylor+%26+Francis+Published;Building+production+ML+systems+that+ship+at+scale)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aprameya05)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aprameya.bharadwaj.05@gmail.com)
[![NeuralOps](https://img.shields.io/badge/NeuralOps-Live-6366f1?style=for-the-badge&logo=cloudflare&logoColor=white)](https://neuralops.pages.dev)

<img src="https://komarev.com/ghpvc/?username=Aprameya05&label=Profile%20Views&color=6366f1&style=for-the-badge" />

</div>

---

## About Me

I'm a CS and Design undergrad at DSCE (VTU, CGPA 9.0) who got tired of ML projects that live only in notebooks.

Right now I'm predicting cloudbursts for Bengaluru airport using actual IMD station data and ERA5 reanalysis, modeling drug synergy across 60 cancer cell lines with graph neural networks, and consulting for a World Bank field experiment across 1,951 farmers in 6 Karnataka districts. On the side I built NeuralOps, an open-source observability platform for AI agents that tracks cost, drift, and decision traces across multi-hop LLM pipelines.

I care about the stuff that comes *after* the model: deployment, monitoring, failure modes, and making sure the system actually works when someone's life depends on it. I also have a design background, which means I'll fight you on font choices and information hierarchy in the same week I'm tuning XGBoost hyperparameters.

**Currently open to:** research collabs, internships, and anything at the intersection of ML and real-world systems.

---

## Highlights

<div align="center">

| Achievement | Details |
|---|---|
| **SIH 2025 - National Winner** | Hardware Track at MIT-ADT, 1 of 2,587 institutions, 826,635 students |
| **MumbaiHacks 2025 Finalist** | National finalist, shipped an AI agent prototype in 24 hours |
| **Singapore-India Hackathon 2026** | Invited participant at SMU Singapore |
| **National Deep Tech Seminar** | 1st Prize, judged by the Chief Minister of Karnataka |
| **6 IP India Patents** | Domains: EV, urban systems, healthcare AI, metro, neurodegeneration, oncology |
| **IEEE I-SMAC 2025** | Attention-Enhanced Bi-LSTM + XGBoost, 98.14% accuracy, 0.982 PR-AUC |
| **Taylor & Francis AI2024** | Survey on adversarial attacks and defenses in deep learning |
| **International Academic Rep** | Represented DSCE at Georgia State University and Bradley University, USA |

</div>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Thunderstorm Nowcasting](https://github.com/Aprameya05/CSIR-Thunderstorm-Bengaluru)
**CSIR / IMD, Kempegowda International Airport**

0-6 hour storm prediction for Bengaluru airport. 54 features from ERA5 reanalysis, IGRA soundings, and 5 atmospheric instability indices. SHAP analysis moved ERA5_CAPE from rank 42 to rank 2 and cut false alarms by 18%.

- Test AUROC 0.871, HSS 0.318 on live afternoon slot
- 3,285 IMD station-days of training data
- 4 FastAPI endpoints pulling live GFS NOAA NOMADS data

`XGBoost` `SHAP` `FastAPI` `ERA5` `NOAA NOMADS`

</td>
<td width="50%" valign="top">

### [NeuralOps](https://github.com/Aprameya05/neuralops)
**[neuralops.pages.dev](https://neuralops.pages.dev)**

Observability for AI agents. Traces multi-hop LLM pipelines, tracks per-call cost across 15 models, and detects distribution drift using Welford stats at 2.5 sigma. Covers LangGraph, CrewAI, and AutoGen.

- Python SDK on PyPI + JS SDK
- `causal_chain_id` stitches spans into a decision tree in ClickHouse
- LLM-as-judge scoring with a CI leaderboard

`FastAPI` `Kafka` `ClickHouse` `PostgreSQL` `Redis` `Cloudflare`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ProteinSynergyDock](https://github.com/Aprameya05/ProteinSynergyDock-App)
**Drug synergy prediction across cancer cell lines**

GATv2 with cross-drug attention and FiLM conditioning trained on 107,103 NCI ALMANAC samples. Pearson r = 0.577, AUROC 0.795. Wired up to a FHIR R4 REST API with CDS Hooks for EHR integration, so predictions can surface at the point of care.

- AutoDock Vina 1.2.7 docking pipeline via RCSB
- 266-test CI/CD on Python 3.10/3.11, zero prod failures

`PyTorch Geometric` `GATv2` `RDKit` `FastAPI` `FHIR R4`

</td>
<td width="50%" valign="top">

### Cloudburst Early Warning System
**SIH 2025 National Winner**

Edge ML system for real-time cloudburst warnings with zero cloud dependency. ESP32/STM32 nodes running XGBoost on pressure-drop gradients and humidity rate-of-change, networked over LoRa 433 MHz mesh.

- Sub-3-minute end-to-end latency, 95%+ precision
- Sub-2-second mesh failover
- 7-language Next.js dashboard for offline district officials
- Only fully off-grid-capable solution across all 271 SIH problem statements

`XGBoost` `ESP32` `STM32` `LoRa` `Next.js`

</td>
</tr>
</table>

---

## Experience

```
Tietoevry                      AI Engineering Intern       Feb 2025 - May 2025
  Azure Document Intelligence + Text Analytics for Health pipeline
  Drug interaction engine across 500+ drug pairs with 3 severity tiers (RxNorm, DailyMed)
  GPT summarization grounded on Azure NER, cut factual error rate by 30%

GKVK - UAS Bengaluru           Data Science Consultant     Feb 2026 - Jul 2026
  World Bank REWARD Program
  Randomized field experiment, 6 districts, 1,951 farmers, p < 0.05
  ETL pipeline merging 5 climate and soil datasets (IMD, ERA5) into 40+ features
```

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch Geometric](https://img.shields.io/badge/PyG-3C2179?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Backend and Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Cloud and DevOps**

![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Design**

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Adobe XD](https://img.shields.io/badge/Adobe_XD-470137?style=for-the-badge&logo=adobexd&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Framer](https://img.shields.io/badge/Framer-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Aprameya05&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&rank_icon=github" height="165"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aprameya05&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact&langs_count=8" height="165"/>

<br/>

<img src="https://nirzak-streak-stats.vercel.app/?user=Aprameya05&theme=tokyonight&hide_border=true" height="150"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aprameya05&theme=tokyo-night&hide_border=true&area=true" width="100%"/>

</div>

---

## Certifications

<div align="center">

![OCI 2026](https://img.shields.io/badge/OCI_2026-Agentic_AI_Foundations-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![OCI 2025 AI](https://img.shields.io/badge/OCI_2025-AI_Foundations-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![OCI 2025 Cloud](https://img.shields.io/badge/OCI_2025-Cloud_Infrastructure-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![OCI 2024](https://img.shields.io/badge/OCI_2024-Generative_AI_Professional-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![ServiceNow CSA](https://img.shields.io/badge/ServiceNow-CSA-00C853?style=for-the-badge&logo=servicenow&logoColor=white)
![ServiceNow CAD](https://img.shields.io/badge/ServiceNow-CAD-00C853?style=for-the-badge&logo=servicenow&logoColor=white)

</div>

---

## Publications and Patents

**Papers**
- **IEEE I-SMAC 2025** (Nepal) - Attention-Enhanced Bi-LSTM + XGBoost for Predictive Maintenance, 98.14% accuracy, 0.982 PR-AUC
- **Taylor & Francis AI2024** (MIT Manipal) - Survey of Adversarial Attack and Defense Methods for Deep Learning Models

**Patents (IP India)**

| # | Title | Application No. |
|---|---|---|
| 1 | EV Charging Quality Management | 202441088582 |
| 2 | Urban Street Lighting | 202441001858 |
| 3 | Sleep Enhancement System | 202441066995 |
| 4 | Metro Parcel Transport | 202641063278 |
| 5 | Bio-AI Neurodegeneration | 202641063509 |
| 6 | AI-Driven Cancer Detection | 202641076117 |

---

<div align="center">

[![](https://visitcount.itsvg.in/api?id=Aprameya05&icon=5&color=6)](https://visitcount.itsvg.in)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:8b5cf6,100:6366f1&height=120&section=footer" width="100%"/>

</div>
