<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0f3460,80:1f6feb,100:388bfd&height=210&section=header&text=Abdullah%20Madoun&fontSize=44&fontColor=ffffff&fontAlignY=40&desc=AI%20%2F%20ML%20Engineer%20%&descAlignY=60&descSize=18&descColor=adbac7&animation=fadeIn"/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdullah-madoun/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AbdullahMadoun)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdullah.h.madoun@gmail.com)

</div>

<br/>

**My goal is simple:** Build AI systems that **reason**, **learn**, and **scale** — closing the gap between models that work on a benchmark and models that work in messy, real-world production.

---

## 🎯 Current Focus

Researching the fundamentals of deep learning and building applied AI systems:
- **Mechanistic Interpretability:** Exploring the internal representations of deep neural networks.
- **Continual & Few-Shot Learning:** Investigating architectures that absorb novel knowledge without catastrophic forgetting.
- **Real-world Computer Vision:** Designing detection and cross-modal evaluation pipelines for deployment.
- **Autonomous Systems:** Perception and simulation for drone inspection.

**Background:** 🎓 Software Engineering (AI/ML) at KFUPM (First Honors, GPA 3.9/4.0) · 🔬 AI Research Assistant @ KFUPM · 📊 Former Data Analyst Intern @ Keeta (Meituan).

---

## :computer: Technical Skills

- **AI / ML Focus:** Continual/Lifelong Learning, Few-Shot & In-Context Learning, Vision-Language Models (VLMs), Self-Supervised Learning (DINOv2), Object Detection, Graph Neural Networks (GNNs).
- **Frameworks & Libraries:** PyTorch, PEFT (LoRA), OpenCV, AutoGluon.
- **Engineering & Infrastructure:** Python, C++, SQL, FastAPI, Docker, SLURM, Weights & Biases, Gazebo, Linux.



## 🚀 Featured Projects

<details>
<summary>&nbsp;<b>🍽️ TahamajaNet — Few-Shot Food Recognition</b> — Continual Learning & Computer Vision &nbsp;·&nbsp; <i>86.4% top-1 accuracy</i></summary>
<br/>

End-to-end system that photographs a cafeteria tray and produces an itemized bill, deployed at the KFUPM campus restaurant. The system was designed after a prior static classifier collapsed under a seasonal menu change, driving my focus toward architectures that incrementally absorb novel classes.

- **Methodology:** Investigated embedding-level In-Context Learning (ICL) with DINOv2 versus instruction-tuned VLMs, ultimately achieving 86.4% top-1 and 90.3% precise-count accuracy via LoRA fine-tuning of Qwen2.5-VL-7B.
- **Performance:** Addressed exact-count regression (predicting the wrong number of items) by implementing a custom cardinality-aware structural loss.

`Python` `PyTorch` `Qwen2.5-VL` `SAM3` `DINOv2` `LoRA`

[![Repo](https://img.shields.io/badge/View%20Repo-KFUPMRestaurant-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbdullahMadoun/KFUPMRestaurant)

</details>

<details>
<summary>&nbsp;<b>🚁 SkyLink — Autonomous Drone Perception</b> — Robotics &nbsp;·&nbsp; <i>47.8% mAP@50</i></summary>
<br/>

PX4-targeted drone autonomy stack for road-damage detection and precision landing.

- **Perception:** Multi-scale YOLO ensemble achieving 47.8% mAP@50 and 0.075m landing precision.
- **Simulation:** Engineered a cloud-based Gazebo evaluation track to stress-test generalization under severe compute constraints.

`Python` `PX4` `Gazebo` `YOLO`

[![Repo](https://img.shields.io/badge/View%20Repo-SeniorProject-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbdullahMadoun/SeniorProject)

</details>

<details>
<summary>&nbsp;<b>🏦 Arabic Bank Check Recognition</b> — NLP / OCR &nbsp;·&nbsp; <i>1.67% → 32.17% exact-match</i></summary>
<br/>

Four-stage pipeline for reading Saudi bank cheques via YOLO detection, CRNN+CTC sequence recognition, and cross-modal verification.

- **Methodology:** Designed an integer-conditioned cross-modal reranker that exploits the bijection between handwritten Arabic text and digit strings.
- **Performance:** Lifted Arabic exact-match from 1.67% to 32.17% on a data-starved domain *without new training*, purely by reframing OCR as a CTC forced-alignment scoring problem.

`Python` `PyTorch` `CRNN` `CTC` `DocLayout-YOLO`

[![Repo](https://img.shields.io/badge/View%20Repo-BankCheckNLP-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbdullahMadoun/BankCheckNLP)

</details>

<details>
<summary>&nbsp;<b>🤟 Continuous Arabic Sign Language Recognition</b> — Deep Learning &nbsp;·&nbsp; <i>15.7% WER</i></summary>
<br/>

Hybrid skeletal-temporal architecture for translating continuous Arabic sign language video to text.

- **Architecture:** Ensembled Graph Neural Networks (GNNs) for spatial joints with BiLSTMs for temporal dynamics to capture long-range sequences.
- **Learning Journey:** Achieved 15.7% WER. The project served as a deep-learning sandbox to deeply understand sequence modeling and the limits of architectural scaling.

`Python` `PyTorch` `GNN` `BiLSTM` `CTC`

[![Repo](https://img.shields.io/badge/View%20Repo-CSLR-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbdullahMadoun/CSLR)

</details>

<details>
<summary>&nbsp;<b>🏆 Tabular ML — 1st Place Solution</b> — Machine Learning &nbsp;·&nbsp; <i>82.0% F1</i></summary>
<br/>

Ensemble learning solution handling severe class imbalance.

- **Methodology:** Trained a custom deep model using Focal Loss to combat severe class imbalance, combined with TabPFN and AutoGluon in a stacked ensemble.
- **Performance:** Achieved 82.0% minority-class F1 score by running Monte Carlo simulations to approximate the optimal decision threshold.

`Python` `TabPFN` `AutoGluon` `Focal Loss`

[![Repo](https://img.shields.io/badge/View%20Repo-MLKaggleWin-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbdullahMadoun/MLKaggleWin)

</details>

<details>
<summary>&nbsp;<b>🏢 LeaseFlow / IMDAD</b> — Applied ML & FinTech</summary>
<br/>

Cloud agent designed to help small merchants access lease-to-own equipment financing via operational and market signals.

- **Architecture:** Built a Dockerized pipeline for underwriting analysis and merchant financing insights.
- **Methodology:** Combined POS-data deep dives, financial document extraction, Google Maps review scraping, rule-based checks, and payment APIs to assess credit risk.

`Python` `Docker` `REST APIs`

[![Repo](https://img.shields.io/badge/View%20Repo-LeaseFlow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbdullahMadoun/LeaseFlow)

</details>

<details>
<summary>&nbsp;<b>🤖 Applied AI & Automation Tooling</b></summary>
<br/>

| Project | Description |
|:---|:---|
| [**browseros-linkedin-skills**](https://github.com/AbdullahMadoun/browseros-linkedin-skills) | 31 reusable agentic browser skills for LinkedIn search, outreach, and job automation. |
| [**JobAssist**](https://github.com/AbdullahMadoun/JobAssist) | AI command center with ATS keyword scoring, CV tailoring, and cover letter generation. |

</details>

---

## 🏆 Honors

<div align="center">

| Award | Detail |
|:---|:---|
| **1st Place**, [ByteBank Technical Hackathon](https://github.com/AbdullahMadoun/PitchSwipe) | Real-time preference embedding system for personalized startup ranking (20+ teams) |
| **1st Place**, KFUPM MBA Algebra Contest | Ranked 1st university-wide out of 100+ contestants |
| **National Chess Champion** | 2× Gold, 1× Silver — Saudi Universities Sports Federation · Lichess Rating: **2256** |

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0f3460,80:1f6feb,100:388bfd&height=100&section=footer"/>
