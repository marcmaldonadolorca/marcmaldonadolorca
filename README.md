<div align="center">

# Marc Maldonado — Data &amp; ML Engineer

**From raw data to models in production — and the 24/7 infrastructure that keeps them alive.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-181410?style=for-the-badge&logo=linkedin&logoColor=f5b544)](https://www.linkedin.com/in/marc-maldonado-lorca/)
[![Kaggle](https://img.shields.io/badge/Kaggle-181410?style=for-the-badge&logo=kaggle&logoColor=f5b544)](https://www.kaggle.com/marcmaldonado)
[![GCP Certified](https://img.shields.io/badge/GCP%20Professional%20Data%20Engineer-181410?style=for-the-badge&logo=googlecloud&logoColor=f5b544)](https://www.credly.com/badges/fdc0d8c0-a5aa-44b3-b02d-33de738dba31)
[![Kaggle Bronze](https://img.shields.io/badge/Kaggle%20Competitions-Bronze%20medal-181410?style=for-the-badge&logo=kaggle&logoColor=f5b544)](https://www.kaggle.com/marcmaldonado/competitions)
[![Email](https://img.shields.io/badge/Email-181410?style=for-the-badge&logo=gmail&logoColor=f5b544)](mailto:maldonadolorcamarc@gmail.com)

</div>

4 years of banking analytics consulting (CaixaBank, VidaCaixa) at **SDG Group** · **MSc in Deep Learning** (UPM, thesis defended Sep 2026 — **10/10**) · Google Cloud Certified **Professional Data Engineer**.

Most data profiles show notebooks. **I show systems running:** while you read this, a Raspberry Pi I run is capturing a live order book every 2 seconds — **100+ GB** so far — feeding the PyTorch models of my MSc thesis, trained on my own GPU.

## 🚀 Featured projects — real, verifiable metrics

| Project | What it is | Result |
|---|---|---|
| [3D cell tracking · Kaggle BioHub](https://github.com/marcmaldonadolorca/biohub-cell-tracking) | My own sub-voxel coordinate refinement head, in PyTorch | 🥉 **Bronze — 371 of 4,020** · **+0.006** private LB |
| [Market microstructure · MSc thesis](https://github.com/marcmaldonadolorca/polymarket-btc-microstructure) | 24/7 order-book capture + sequence models, time-stamped pre-registration | **100+ GB** · out-of-sample validated · **10/10** |
| [ECG arrhythmia · MLOps](https://github.com/marcmaldonadolorca/ecg-heartbeat-mlops) | 1D CNN, notebook → dockerized API + CI + W&B | **F1 0.877** · accuracy **0.978** |
| [Pig weight estimation · BSc 9.2](https://github.com/marcmaldonadolorca/Pig_weight_estimation) | YOLOv5 / U-Net + Open3D point clouds + CNN regression | **MAE 3.6 kg** · IoU **0.98** |
| [Deep-learning coursework ×8](https://github.com/marcmaldonadolorca/msc-deep-learning-coursework) | MLP → transformers: vision, time series, NLP, generative | **8** end-to-end projects |
| [Quant strategy · RNVV](https://www.darwinexzero.com/darwin/RNVV/performance) | Lookahead-free backtest, live 24/7 signal service | **Public**, 3rd-party-audited track record |

> Plus a production **homelab** (Raspberry Pi + GPU tower): VPN, DNS, reverse proxy, monitoring, encrypted backups verified by restoring them, and local LLM + RAG — **13** services in production, **0** ports open to the internet.

## 🛠️ Tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-181410?style=for-the-badge&logo=python&logoColor=f5b544)
![PyTorch](https://img.shields.io/badge/PyTorch-181410?style=for-the-badge&logo=pytorch&logoColor=f5b544)
![scikit-learn](https://img.shields.io/badge/scikit--learn-181410?style=for-the-badge&logo=scikitlearn&logoColor=f5b544)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-181410?style=for-the-badge&logo=huggingface&logoColor=f5b544)
![pandas](https://img.shields.io/badge/pandas-181410?style=for-the-badge&logo=pandas&logoColor=f5b544)
![NumPy](https://img.shields.io/badge/NumPy-181410?style=for-the-badge&logo=numpy&logoColor=f5b544)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-181410?style=for-the-badge&logo=postgresql&logoColor=f5b544)
![Docker](https://img.shields.io/badge/Docker-181410?style=for-the-badge&logo=docker&logoColor=f5b544)
![Linux](https://img.shields.io/badge/Linux-181410?style=for-the-badge&logo=linux&logoColor=f5b544)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-181410?style=for-the-badge&logo=googlecloud&logoColor=f5b544)
![Git](https://img.shields.io/badge/Git-181410?style=for-the-badge&logo=git&logoColor=f5b544)
![TypeScript](https://img.shields.io/badge/TypeScript-181410?style=for-the-badge&logo=typescript&logoColor=f5b544)

</div>

## 🏅 Kaggle competitions — ranked against thousands of teams

Featured competitions, scored on the private leaderboard by a third party.
Verifiable at [kaggle.com/marcmaldonado](https://www.kaggle.com/marcmaldonado/competitions).

| Competition | Teams | Result | Repo |
|---|---|---|---|
| **BioHub Cell Tracking** (Research) | 4,020 | 🥉 **371 — bronze medal** (medal cut-off: 401) | [repo](https://github.com/marcmaldonadolorca/biohub-cell-tracking) |
| ROGII Wellbore Geology | 6,125 | **1,075 — top 17.6%** (+2,299 places in the private shakeup) | [repo](https://github.com/marcmaldonadolorca/rogii-wellbore-geology-prediction) |
| Pokémon TCG AI Battle (Simulation) | 6,807 | **1,328 — top 20%** | [repo](https://github.com/marcmaldonadolorca/pokemon-tcg-battle-agent) |
| Go-Explore Red Teaming (LLM agents) | 4,186 | 3,985 — no medal, and the write-up explains why | [repo](https://github.com/marcmaldonadolorca/llm-agent-redteam-goexplore) |

In BioHub the medal came from a component I built myself: a tiny network that refines each
cell's position inside the voxel. Without it, 0.914 on the private leaderboard and no medal;
with it, 0.920 and bronze. The head and its training code are public, as a
[dataset](https://www.kaggle.com/datasets/marcmaldonado/biohub-coordref-head-public) and a
[notebook](https://www.kaggle.com/code/marcmaldonado/biohub-sub-voxel-head-0-921-private).
A second bronze, this one for a notebook, came from
[showing where the label noise in a Playground competition actually comes from](https://www.kaggle.com/marcmaldonado/code).

In ROGII my own solution beat the shared public-artifacts pipeline where it counts: that
pipeline degraded **+3.00** RMSE from public to private and ended up below every model of
mine; my simplest one degraded **+0.09**. In the red-teaming challenge I reproduced the
top public technique and scored **zero** on the private leaderboard — the public board was
a mirage, and that lesson is written up in the repo rather than buried.

## 📜 Certifications

**49 credentials, 48 of them with a verification URL.** The ones worth naming:

- **Google Cloud — Professional Data Engineer** (2025) · [verify on Credly](https://www.credly.com/badges/fdc0d8c0-a5aa-44b3-b02d-33de738dba31)
- **IELTS Academic — Overall 7.5 (C1)** (2024)
- **Anthropic Academy — 21 certificates** (Claude Code, API, MCP, agents)
- **HackerRank — 9 assessed certifications** (Software Engineer role, SQL Advanced, Problem Solving…)
- **Kaggle Learn — 15 certified courses** · **IBM Cognitive Class** (deep learning on GPUs) · **Forage — Deloitte Australia** (data analytics)

---

<div align="center">

*Honest evaluation first: out-of-sample, realistic costs, and metrics I don't dress up.*

📫 Open to **Data Engineer · Machine Learning Engineer · AI Engineer** roles — Spain &amp; remote (EU/UK)

</div>
