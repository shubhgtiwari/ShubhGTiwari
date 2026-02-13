# <div align="center">Hi, I'm Shubham Tiwari 👋</div>

<div align="center">
  <h3>Data Scientist & AI Engineer | Deep Learning Researcher</h3>
  <p><i>Building at the intersection of production LLMs, causal discovery, and scalable ML systems.</i></p>

  <a href="https://linkedin.com/in/shubhamgtiwari">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:shubham@shubhamtiwari.dev">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://huggingface.co/shubhgtiwari">
    <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace" />
  </a>
  <a href="https://shubhamtiwari.dev">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio" />
  </a>
</div>

---

## 🚀 Professional Summary

I am an AI Engineer specializing in **GenAI infrastructure** and **predictive modeling**. My work focuses on moving models from notebooks to production, whether that means fine-tuning 30B+ parameter LLMs, optimizing inference with quantization, or architecting multi-agent systems.

Currently, I am a **Volunteer Machine Learning Researcher** at Michigan Tech, developing novel **evolutionary algorithms** for causal discovery in Bayesian Networks.

---

## � Featured Projects

### 🤖 [Smart Interview Coach: Autonomous Agent Platform](https://smart-coach-five.vercel.app/)
> *A production-grade career platform powered by a multi-agent orchestration layer.*

- **The Problem:** Generic AI advice isn't actionable for job seekers.
- **My Solution:**
  - **Architecture:** Built a **dual-LLM routing system** where a fast 8B model handles chat and a 70B model handles deep critique, achieving sub-second latency via Groq API.
  - **Agents:** Deployed **7 autonomous agents** (Resume Tailor, Mock Interviewer, Salary Negotiator) that collaborate to solve complex user tasks.
  - **Impact:** Features **ghost job detection** (analyzing 5+ signals like posting date/bias) and **ATS optimization** that rewrites bullet points at a staff-engineer level.
- **Tech:** `FactAPI` `React` `Django` `PostgreSQL` `Docker` `AWS` `Groq API`

### 🧠 [TINA: LLM Fine-Tuning & Reasoning](https://huggingface.co/ShubhamGTiwari)
> *Advanced model adaptation for specialized reasoning tasks.*

- **Optimization:** Fine-tuned **Qwen 2.5 32B** on **300k+ records** using **QLoRA + Unsloth**, producing efficient <1GB adapters.
- **Reasoning:** Experimented with **GRPO (Group Relative Policy Optimization)** using **5 distinct reward functions** to enforce chain-of-thought logic.
- **Deployment:** Built a robust **quantization pipeline** using `llama.cpp` to generate Q2-Q8 GGUF variants for edge deployment.
- **Tech:** `PyTorch` `Unsloth` `vLLM` `Hugging Face` `WandB`

### 🧬 [Protein Family Classification](https://github.com/shubhgtiwari/Protein_Sequence_Classification)
> *High-performance bioinformatics classification at scale.*

- **Scale:** Processed **22,815 unstructured protein sequences** to classify them into distinct families.
- **Performance:** Achieved **98.96% Accuracy** and **ROC-AUC = 1.00** using SVMs and XGBoost.
- **Engineering:** Extracted **1,425 biological features** using BioPython and handled class imbalance with SMOTE oversampling.
- **Tech:** `Python` `Scikit-learn` `XGBoost` `BioPython` `TensorFlow`

### 📱 [Human Activity Recognition](https://github.com/shubhgtiwari/Human_Activity_Recognisition)
> *Real-time sensor data analysis and predictive modeling.*

- **Precision:** Classified 6 distinct activities from **10,299 smartphone sensor observations** with **98.2% accuracy** (Kappa 0.978).
- **Pipeline:** Designed a rigorous preprocessing pipeline using **Box-Cox transformation** and **PCA**, reducing feature space from 561 to 185 while maintaining signal integrity.
- **Validation:** Benchmarked 8 algorithms (LDA, Neural Networks, k-NN) using 3-fold cross-validation.
- **Tech:** `R` `Caret` `ggplot2` `Statistical Modeling`

---

## 🔬 Research Focus: Causal Discovery

My research addresses the **NP-hard problem** of learning Bayesian Network structures from high-dimensional data.
- **Approach:** Developing hybrid **evolutionary algorithms** (Genetic Algorithms) to explore the DAG (Directed Acyclic Graph) search space more efficiently than traditional score-based or constraint-based methods.
- **Goal:** Improving the scalability and accuracy of causal inference in complex systems.

---

## 🛠️ Technical Arsenal

| Domain | Stack |
| :--- | :--- |
| **GenAI & NLP** | `Llama 3.1` `Mistral` `RAG` `LangChain` `Unsloth` `QLoRA` `GRPO` `vLLM` |
| **Machine Learning** | `PyTorch` `TensorFlow` `XGBoost` `Scikit-learn` `Statsmodels` `CausalLearn` |
| **Data Engineering** | `PostgreSQL` `MongoDB` `Snowflake` `Apache Spark` `Airflow` `dbt` |
| **Backend & Cloud** | `FastAPI` `Django` `Docker` `Kubernetes` `AWS (ECS, S3)` `Terraform` |
| **Languages** | `Python` `SQL` `R` `JavaScript` `TypeScript` `Bash` |

---

## � GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ShubhGTiwari&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="Shubham's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ShubhGTiwari&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
</div>

---
<p align="center">
  <i>"I don't just train models; I build the infrastructure that makes them useful."</i>
</p>
