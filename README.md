# Anshuman Singh

**Updated:** 09-Jan-2026

[![GitHub](https://img.shields.io/badge/GitHub-DataBoySu-181717?logo=github&logoColor=white)](https://github.com/DataBoySu)
[![Email](https://img.shields.io/badge/Email-anshumanr22%40outlook.com-0078D4?logo=microsoft-outlook&logoColor=white)](mailto:anshumanr22@outlook.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-anshumansingh2023-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anshumansingh2023/)
[![Resume](https://img.shields.io/badge/Resume-PDF-4B5563?logo=readme&logoColor=white)](su_resume.pdf)

**Aspiring AI Researcher & Engineer** | Research Internships & Applied AI

> Undergraduate CS student focused on research-driven engineering. I spend my time implementing papers, writing technical guides that make sense of complex topics, and building robust systems. I’m a big believer in rigorous documentation and creating software that’s as consistent as the research it’s based on.

## Contents

- [Education](#education)
- [Research](#research)
- [Projects](#projects)
- [Open Source](#open-source)
- [Competitions](#competitions)

---

## Education

**#### University** — B.Tech Computer Science (AI & ML) *(Sep 2023 – 2027, Expected)*

- Ranked #1 in AIML specialization batch; top performer in the B.Tech CSE program (≈300+ students)
- Current CGPA: 9.49/10.00 | Highest Semester GPA: 9.92/10.00
- Coursework: Advanced ML, NLP, Probability & Statistics, Linear Algebra, Computer Networks, Operating Systems, DBMS, Discrete Mathematics, Design & Analysis of Algorithms

---

## Research

| Topic | When | Stack | Link |
|---|---:|---|---|
| Emotion & Sentiment Classification (NLP) | Summer – Fall 2025 | Python, scikit-learn, TF-IDF, SMOTE/ADASYN, TensorFlow/Keras | https://github.com/DataBoySu/Data-Science-Projects/tree/main/Emotion_class_Research |
| Network Partition Attacks on Blockchain Consensus | Winter 2025 – Present | Python, NetworkX, NumPy, Matplotlib | https://github.com/DataBoySu/Blockchain-partition-simulation |
| TCP vs UDP in Real-Time Online Games | Winter 2025 – Present | Networking, latency/jitter measurement, packet loss tolerance | https://github.com/DataBoySu/network-studies |

### Emotion & Sentiment Classification (NLP)

- Built and benchmarked models from classical ML baselines to deep sequence models; best performance **93% accuracy** with BiLSTM + custom attention
- Used pretrained embeddings (GloVe/Word2Vec) and systematic evaluation (per-class metrics, confusion matrices) to quantify tradeoffs in context awareness
- Focused on imbalance handling and interpretability via attention analysis and error breakdowns

### Impact of Network Partition Attacks on Blockchain Consensus

- Studying forks, partitions, intentional forks, and propagation behavior through a small-scale simulator and literature review
- Measuring fork rates, orphaned blocks, reorg behavior, and chain rejoin dynamics under controlled partition scenarios

### TCP vs UDP in Real-Time Online Games

- Investigating transport-layer tradeoffs in competitive multiplayer games (e.g., Valorant/CS2): latency, reliability, jitter, and packet-loss tolerance
- Studying how games build custom reliability layers, lag compensation, and state synchronization on top of UDP

---

## Projects

| Project | When | Stack | Link |
|---|---:|---|---|
| MyGPU | Fall 2025 | Python, Click, Rich, FastAPI, Uvicorn, WebSockets, psutil, NVML (nvidia-ml-py) | https://github.com/DataBoySu/MyGPU |
| GitHub Translation Pipeline | Summer 2025 | GitHub Actions, Python, Bash, model caching, HuggingFace | https://github.com/DataBoySu/databoysu-readme-translator |
| Streax Bot (Reddit Hackathon) | Fall 2025 | React, Vite, Tailwind, Node, Firestore, Gemini | https://www.reddit.com/r/streax_bot_dev/ |

### MyGPU

- Built a lightweight local GPU monitoring + benchmarking utility with both CLI and Web dashboard; designed for privacy-first local execution
- Added admin-centric controls such as VRAM enforcement (auto-terminate over-limit processes) and watchlists; optional CUDA benchmarking (CuPy/PyTorch) support

### GitHub Translation Pipeline

- Built a privacy-first CI pipeline that runs fully on GitHub runners (no API keys), generating 20+ README translations per repository
- Sped up runs via parallel jobs and model-weight caching; added post-processing + structural validation to preserve code blocks and markdown structure

### StreaxBot | Reddit Hackathon

- Built for the Reddit Devvit Hackathon: a topic-based quiz experience with daily play limits and leaderboards to drive repeat engagement
- Designed for non-repetitive content and responsiveness using caching strategies and LLM-generated question pipelines

---

## Open Source

### Core Contributor / Maintainer — waka-readme-stats (4k+ stars)

- Link: https://github.com/anmol098/waka-readme-stats
- Contributed the README translation pipeline and helped operationalize privacy-first translations at scale
- Unblocked stalled CI workflows/PRs by fixing permissions and workflow strategy; resolved multiple bugs and improved maintainer review throughput
- Proposed an alternate PR review strategy and improved CI reliability using mock data for safer previews and faster iteration

---

## Competitions

### NES Innovation Award 2025 (Top 50 National)

- Selected among top 50 teams nationally
- Building a nation-wide client–server network for information dispersal through multiple end-point modes *(kept intentionally high-level)*

### ##### Hackathon (Healthcare Track — 3rd Place) — Feb 2024

- Led a team of 4 and shipped an end-to-end ML-powered web app prototype in 48 hours
- Built an Ayurveda-based diagnosis and treatment recommendation system; achieved **92%** accuracy
- Owned data collection (web scraping + synthetic data generation), model training (Random Forest), evaluation, and deployment

### ##### Hackathon (Special Recognition) — Fall 2024

- Led a team of 5; recognized by judges for methodology, execution, and presentation
- Built a LightGBM stacking classifier on 20K+ loan records and achieved **92.8%** accuracy
- Documented assumptions and added explainability using SHAP for stakeholder clarity
