<!-- Badges -->
[![NVIDIA Student Ambassador](https://img.shields.io/badge/NVIDIA-Student%20Ambassador-76B900?logo=nvidia&logoColor=white)](https://www.nvidia.com/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Bronze%20%7C%20150%2F1727%20(Top%208.7%25)-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/junmingzhao)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ShunmeiCho-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%E4%BF%8A%E8%8C%97-%E8%B6%99-3353933a9/)
[![X](https://img.shields.io/badge/X-@ZJM330-000000?logo=x&logoColor=white)](https://twitter.com/ZJM330)

# 👋 Hi, I'm **Shunmei Cho (趙 俊茗)**

🎓 M.Sc. Candidate, Computer Science @ **Tokyo University of Technology**  
🌱 **NVIDIA Student Ambassador** (AI / LLM Team)  
🏆 **Kaggle Bronze Medal** — March ML Mania 2025 (**150/1727**, Top **8.7%**)  
📌 I work on **small-data reasoning**, **structured knowledge inference**, and **LLM × robotics systems**.

---

## ⚡ 10-Second Summary

- I build **reasoning-oriented ML systems** that stay reliable under **small data / distribution shifts**
- I care about **reproducibility**: config-driven experiments, clear baselines, and honest failure analysis
- I prototype **LLM × robotics** pipelines end-to-end (speech I/O → LLM → control loop → feedback)

---

## 🔎 Research Focus

### Hierarchical Reasoning Models (HRM) for Small-Data Inference

**Problem:** RAG and generic fine-tuning can be brittle when data is limited, noisy, outdated, or contradictory.  
**What I do:** Study & build **hierarchical reasoning models** that learn structured rules and generalize compositionally.

**Typical tasks / benchmarks:**
- Compositional generalization (key→value binding, multi-step chain reasoning)
- Robust inference under partial observability (masked fields / missing attributes)
- Controlled evaluation: candidate sets, shortcut baselines, distribution shift tests

**What I emphasize:**
- Clear baselines (random / heuristic shortcuts / strong ML baselines)
- Ablations (min-steps, halt policy / step contribution, data structure choices)
- Reproducible runs (YAML configs, W&B tracking, fixed seeds)

---

## 🔎 What I Do

- 🧠 **Research**: Hierarchical Reasoning Models (HRM) for robust knowledge inference in small-data settings
- 🤖 **Systems**: LLM × Robotics prototyping with Unitree GO2 (ROS2, speech I/O, control loop)
- 🧱 **Engineering**: Reproducible ML experiments (YAML configs, W&B, Docker)
- 🏆 **Kaggle**: Bronze Medal — March ML Mania 2025 (150/1727, Top 8.7%)

> I build things that are **explainable**, **reproducible**, and **deployable**.

---

## 🤖 Systems Focus

### LLM × Robotics (Unitree GO2 Prototype)

I prototype an end-to-end system that connects:  
**Voice → ASR → LLM reasoning → action command → ROS2/SDK execution → feedback loop**,  
with constraints for safety and real-time behavior.

Key engineering points I care about:
- Interface contracts (what the LLM is allowed to output)
- Latency budget (ASR/LLM/TTS + control timing)
- Safety filters & fallback behaviors (invalid command handling, stop conditions)

---

## 🚀 Featured Projects

| Project | What it does | Why it matters | Tech |
|---------|--------------|----------------|------|
| **HRM Experiments** | Reproducible training & evaluation for compositional reasoning | Shows research rigor + reproducibility | PyTorch · W&B · Docker |
| **Go2 × LLM Prototype** | Voice → ASR → LLM → robot control with safety constraints | Shows systems skill beyond notebooks | ROS2 · Unitree SDK · TTS/ASR |
| **Kaggle: March ML Mania 2025** | Feature engineering + model ensemble pipeline | Shows practical ML & competition skill | LightGBM · XGBoost · CatBoost |
| **RAG Chatbot** | Document retrieval QA system for university applications | Shows ability to ship typical LLM apps | LangChain · FAISS · LLM |

---

## 🧱 Engineering Principles

- **Config-first**: Every experiment defined by YAML config (data, model, seeds, metrics)
- **Track everything**: W&B for metrics, artifacts, and comparisons
- **Failure cases matter**: Document what breaks and why, not only best scores
- **Readable code > clever code**: Maintainability first

---

## 🛠️ Tech Stack

**ML/DL**: Python, PyTorch, scikit-learn  
**MLOps**: Docker, W&B, Git  
**Systems**: Linux, ROS2, CUDA  
**Data**: Pandas, SQL

---

## 🌐 Languages

- 中文（Native）
- 日本語（Business Level）
- English（Fluent）

---

## 📫 Contact

- Kaggle: [junmingzhao](https://www.kaggle.com/junmingzhao)
- LinkedIn: [ShunmeiCho](https://www.linkedin.com/in/%E4%BF%8A%E8%8C%97-%E8%B6%99-3353933a9/)
- X: [@ZJM330](https://twitter.com/ZJM330)
