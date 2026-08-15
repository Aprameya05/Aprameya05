<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:8b5cf6,100:06b6d4&height=220&section=header&text=Aprameya%20Bharadwaj&fontSize=52&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20MLOps%20%E2%80%A2%20Healthcare%20AI%20%E2%80%A2%20CS%20%26%20Design&descAlignY=58&descSize=17&descColor=c7d2fe" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=15&duration=3500&pause=1200&color=818CF8&center=true&vCenter=true&multiline=true&repeat=true&width=760&height=60&lines=SIH+2025+National+Winner+%7C+6+IP+India+Patents+%7C+IEEE+%26+Taylor+%26+Francis+Published;Building+production+ML+systems+that+ship+at+scale" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aprameya05)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aprameya.bharadwaj.05@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Aprameya05)

</div>

---

## About Me

I like building systems where research meets real engineering.

From training graph neural networks on cancer drug data to deploying thunderstorm prediction models with the Indian Met Department, I work across the full stack of a problem: understanding the science, designing the architecture, building the model, and shipping something that actually runs.

My work has touched clinical NLP on Azure, atmospheric forecasting with ERA5 and upper-air soundings, drug synergy prediction across 60 cancer cell lines, IoT sensor networks for disaster early warning, and FHIR-compliant healthcare APIs. Not as side projects. As systems with real users, real data, and real stakes.

Along the way I've published at IEEE, filed 6 patents, consulted under the World Bank REWARD Program, and won Smart India Hackathon 2025 at the national level.

I study CS and Design at DSCE and graduate in 2027. Always looking for the next hard problem.

---

## Highlights

<div align="center">

| Achievement | Details |
|---|---|
| **SIH 2025 - National Winner** | Hardware Track at MIT-ADT, 1 of 2,587 institutions, 826,635 students |
| **MumbaiHacks 2025 Finalist** | National finalist, shipped an AI agent prototype in 24 hours |
| **Singapore-India Hackathon 2026** | Invited participant at SMU Singapore |
| **National Deep Tech Seminar** | 1st Prize, judged by the Chief Minister of Karnataka |
| **6 IP India Patents** | EV, urban systems, healthcare AI, metro, neurodegeneration, oncology |
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
**neuralops.pages.dev**

Observability for AI agents. Traces multi-hop LLM pipelines, tracks per-call cost across 15 models, and detects distribution drift using Welford stats at 2.5 sigma. Covers LangGraph, CrewAI, and AutoGen.

- Python SDK on PyPI + JS SDK
- causal_chain_id stitches spans into a decision tree in ClickHouse
- LLM-as-judge scoring with a CI leaderboard

`FastAPI` `Kafka` `ClickHouse` `PostgreSQL` `Redis` `Cloudflare`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ProteinSynergyDock](https://github.com/Aprameya05/ProteinSynergyDock-App)
**Drug synergy prediction across cancer cell lines**

GATv2 with cross-drug attention and FiLM conditioning trained on 107,103 NCI ALMANAC samples. Pearson r = 0.577, AUROC 0.795. Wired up to a FHIR R4 REST API with CDS Hooks for EHR integration.

- AutoDock Vina 1.2.7 docking pipeline via RCSB
- 266-test CI/CD on Python 3.10/3.11, zero prod failures

`PyTorch Geometric` `GATv2` `RDKit` `FastAPI` `FHIR R4`

</td>
<td width="50%" valign="top">

### [GutSense](https://github.com/Aprameya05/GutSense-Mood-Prediction)
**Neuro-nutrition mood prediction**

Photo-log meals, model gut microbiome response, predict mood shifts. A full ML pipeline connecting nutrition intake to neurological state via microbiome proxy modeling.

- End-to-end pipeline from food image input to mood prediction
- Microbiome intermediate modeling layer
- Nutrition-to-neurotransmitter pathway features

`Python` `PyTorch` `Computer Vision` `Scikit-learn`

</td>
</tr>
</table>

---

## Experience

<table width="100%">
<tr>
<td width="38%"><b>Tietoevry</b></td>
<td width="32%">AI Engineering Intern</td>
<td width="30%">Feb 2025 – May 2025</td>
</tr>
<tr>
<td colspan="3">
<ul>
<li>Azure Document Intelligence + Text Analytics for Health pipeline</li>
<li>Drug interaction engine across 500+ drug pairs, 3 severity tiers (RxNorm, DailyMed)</li>
<li>GPT summarization grounded on Azure NER, cut factual error rate by 30%</li>
</ul>
</td>
</tr>
<tr><td colspan="3"><br/></td></tr>
<tr>
<td><b>GKVK – UAS Bengaluru</b></td>
<td>Data Science Consultant</td>
<td>Feb 2026 – Jul 2026</td>
</tr>
<tr>
<td colspan="3"><i>World Bank REWARD Program</i>
<ul>
<li>Randomized field experiment, 6 districts, 1,951 farmers, p &lt; 0.05</li>
<li>ETL pipeline merging 5 climate and soil datasets (IMD, ERA5) into 40+ features</li>
</ul>
</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,fastapi,flask,nodejs,react,nextjs,typescript&perline=10" />
<img src="https://skillicons.dev/icons?i=kafka,postgres,mongodb,redis,azure,aws,docker,git,github,cloudflare&perline=10" />
<img src="https://skillicons.dev/icons?i=figma,blender,xd,java,cpp,javascript,r,mysql&perline=10" />

</div>

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Aprameya05&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&rank_icon=github&cache_seconds=1800" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aprameya05&theme=tokyonight&hide_border=true&layout=compact&langs_count=8&cache_seconds=1800" height="160"/>

<br/><br/>

<img src="https://nirzak-streak-stats.vercel.app/?user=Aprameya05&theme=tokyonight&hide_border=true" height="150"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aprameya05&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph" width="100%"/>

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

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:8b5cf6,100:6366f1&height=120&section=footer" width="100%"/>

</div>
