<div align="center">

# 🗓️ DailyEpoch

### **An Engineering Journal — One Day, One Concept, One Commit at a Time**

**Building toward AI Platform Engineering from models to production infrastructure.**

<br>

DailyEpoch is my public engineering journal documenting what I learn while building toward a career in **AI Platform Engineering**, **AI Infrastructure**, and **Forward Deployed Engineering**.

From algorithms and model architectures to GPUs, Linux, cloud infrastructure, Kubernetes, MLOps, and production AI systems — each entry captures another layer of the engineering stack.

<br>

<img src="https://img.shields.io/badge/AI-Systems-red?style=for-the-badge">
<img src="https://img.shields.io/badge/AI-Infrastructure-Engineering-76B900?style=for-the-badge">
<img src="https://img.shields.io/badge/Cloud-Computing-FF9900?style=for-the-badge">
<img src="https://img.shields.io/badge/DevOps-Automation-2496ED?style=for-the-badge">
<img src="https://img.shields.io/badge/MLOps-Production-009688?style=for-the-badge">

<br><br>

<img src="https://img.shields.io/badge/Linux-Systems-FCC624?style=flat-square&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=flat-square&logo=kubernetes&logoColor=white">
<img src="https://img.shields.io/badge/AWS-Cloud-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/Terraform-IaC-844FBA?style=flat-square&logo=terraform&logoColor=white">
<img src="https://img.shields.io/badge/Python-Engineering-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">

</div>

---

# 📒 Engineering Logbook

> **Building AI systems from algorithms to production infrastructure — one day at a time.**

This is the core of **DailyEpoch**.

Each entry records a concept I studied, why it matters in real systems, what I learned from it, and the artifact produced during that learning session.

| **#** | **Date** | **Domain** | **Topic** | **Production Relevance** | **Key Takeaways** | **Artifacts** |
|:----:|:---------|:-----------|:----------|:--------------------------|:------------------|:--------------|
| 001 | 2026-08-27 | ⚡ AI Infrastructure | **CPU Architecture and Memory Hierarchy: Cores, Cache, RAM, and Data Access** | CPU architecture and memory hierarchy influence compute performance, data movement, latency, resource utilization, and interaction with accelerators in modern AI infrastructure. | Studied CPU cores, instruction execution, cache levels, RAM, memory hierarchy, data-access latency, and why efficient data movement matters to system performance. | [📘 Notes](https://github.com/themodernengineer-tech/InfraNerve/blob/main/Docs/03-Computer-Architecture/CPU-Architecture-and-Memory-Hierarchy.pdf) |
| 002 | 2026-09-07 | 🧠 Language Models | **Transformers: Architecture, Self-Attention, and Modern Language Models** | Transformers provide the architectural foundation for modern LLMs, enabling parallel sequence processing, scalable training, and context-aware representations through attention mechanisms. | Studied Transformer architecture, self-attention, multi-head attention, positional encoding, encoder-decoder structure, feed-forward networks, residual connections, and their role in modern language models. | [📘 Notes](https://github.com/themodernengineer-tech/LanguageForge/blob/main/Docs/Transformers/transformers.pdf) |
| 003 | 2026-09-08 | ⚡ AI Infrastructure | **NVIDIA Infrastructure: CUDA and TensorRT Overview** | CUDA provides the accelerated computing foundation for NVIDIA GPUs, while TensorRT optimizes trained models for high-performance inference in production environments. | Studied the CUDA software ecosystem, GPU acceleration, TensorRT inference optimization, and how these technologies connect AI applications with NVIDIA GPU infrastructure. | [📘 Notes](https://github.com/themodernengineer-tech/InfraNerve/blob/main/Docs/03-Computer-Architecture/NVIDIA-Infrastructure-CUDA-and-TensorRT-Overview.pdf) |
| 004 | 2026-09-09 | ⚡ AI Infrastructure | **AI Infrastructure Fundamentals: Compute, Storage, Networking, and Operations** | AI infrastructure provides the underlying compute, memory, storage, networking, software, and operational systems required to train, deploy, scale, and reliably operate modern AI workloads. | Studied the foundations of AI infrastructure, why AI workloads differ from traditional IT systems, and how compute accelerators, high-performance storage, networking, software stacks, and operations work together to support production AI. | [📘 Notes](https://github.com/themodernengineer-tech/InfraNerve/blob/main/Docs/03-Computer-Architecture/AI-Infrastructure-Fundamentals.pdf) |
| 005 | 2026-09-10 | 🧠 Language Models | **What Happens When You Ask an LLM a Question?** | Understanding the LLM inference pipeline helps explain latency, token generation, context handling, GPU utilization, and how user prompts move through production AI systems from request to response. | Studied how a prompt is tokenized, converted into embeddings, processed through Transformer layers and attention, evaluated into token probabilities, decoded autoregressively, and returned as a generated response through an inference/serving stack. | [📘 Notes](https://github.com/themodernengineer-tech/LanguageForge/blob/main/Docs/Transformers/ask_llm_question.pdf) |
| 006 | 2026-09-10 | 🧠 Language Models | **Breaking Language into Pieces: Understanding Tokenizers in LLMs** | Tokenization determines how text is represented before entering an LLM, directly affecting sequence length, context-window usage, computational cost, inference latency, and how efficiently different languages and inputs are processed. | Studied how tokenizers convert text into tokens and token IDs, vocabulary construction, subword tokenization, Byte Pair Encoding (BPE), WordPiece, SentencePiece, special tokens, encoding/decoding, and how tokenization connects human-readable text to Transformer model inputs. | [📘 Notes](https://github.com/themodernengineer-tech/LanguageForge/blob/main/Docs/Transformers/understanding_tokenizers.pdf) |
| 007 | 2026-09-13 | 🧠 Language Models | **From General Intelligence to Task Expert: Understanding Fine-Tuning in LLMs** | Fine-tuning adapts a pretrained language model to specific tasks, domains, behaviors, or instruction-following requirements, enabling organizations to specialize general-purpose models while avoiding the cost of training from scratch. | Studied how pretrained LLMs are adapted through fine-tuning, including supervised fine-tuning (SFT), instruction tuning, full-parameter fine-tuning, parameter-efficient fine-tuning (PEFT), LoRA, training datasets, hyperparameters, overfitting, catastrophic forgetting, evaluation, and the trade-offs between fine-tuning, prompting, and RAG. | [📘 Notes](https://github.com/themodernengineer-tech/LanguageForge/blob/main/Docs/Transformers/fine_tuning.pdf) |
<br>


---

# 🎯 Why DailyEpoch?

<table>
<tr>
<td width="50%" valign="top">

### 🎯 The Mission

Build the technical depth and systems mindset required to understand AI **from model architecture to production infrastructure**.

The long-term direction is toward engineering roles involving:

- AI Platform Engineering
- AI Infrastructure
- Forward Deployed Engineering
- MLOps
- Machine Learning Systems

</td>
<td width="50%" valign="top">



---

# 🧠 Learning Domains

Rather than treating AI, infrastructure, cloud, and operations as separate disciplines, DailyEpoch follows how they connect to form a production AI system.

<table>
<tr>

<td width="33%" valign="top">

### 🤖 AI & Models

- Machine Learning
- Deep Learning
- Neural Networks
- Computer Vision
- NLP
- Transformers
- LLMs
- Generative AI
- RAG
- AI Agents

</td>

<td width="33%" valign="top">

### ⚡ AI Infrastructure

- CPU Architecture
- GPUs
- CUDA
- TensorRT
- Linux
- Containers
- Kubernetes
- Networking
- Distributed Systems
- Distributed Training

</td>

<td width="33%" valign="top">

### ☁️ Cloud

- AWS
- EC2
- ECS
- EKS
- Fargate
- IAM
- S3
- VPC
- Load Balancing
- Cloud Architecture

</td>

</tr>

<tr>

<td width="33%" valign="top">

### ⚙️ DevOps

- Git
- GitHub
- CI/CD
- GitHub Actions
- Terraform
- Infrastructure as Code
- Helm
- Argo CD
- Prometheus
- Grafana

</td>

<td width="33%" valign="top">

### 📈 MLOps

- Model Deployment
- ML Pipelines
- MLflow
- Kubeflow
- Airflow
- Model Registry
- Experiment Tracking
- Monitoring
- Model Serving
- Production ML

</td>

<td width="33%" valign="top">

### 💻 Engineering

- Python
- Bash
- SQL
- FastAPI
- APIs
- Automation
- Linux CLI
- Debugging
- Systems Thinking
- Architecture

</td>

</tr>
</table>

---

# 🔄 From Model to Platform

<div align="center">

DailyEpoch follows the engineering path that connects an AI idea to a production system.

</div>

```text
                         AI SYSTEM
                             │
           ┌─────────────────┴─────────────────┐
           │                                   │
           ▼                                   ▼
      INTELLIGENCE                         SYSTEMS
           │                                   │
     ML / DL / LLMs                    CPU / GPU / CUDA
     CV / NLP / RAG                    Linux / Networking
           │                                   │
           └─────────────────┬─────────────────┘
                             ▼
                         SOFTWARE
                             │
                    Python • APIs • Git
                             │
                             ▼
                       CONTAINERS
                             │
                          Docker
                             │
                             ▼
                      ORCHESTRATION
                             │
                        Kubernetes
                             │
                             ▼
                           CLOUD
                             │
                            AWS
                             │
                             ▼
                          MLOps
                             │
              CI/CD • Serving • Monitoring
                             │
                             ▼
                  PRODUCTION AI SYSTEM
                             │
                             ▼
                  AI PLATFORM ENGINEERING
```

> The objective is not simply to learn individual tools. It is to understand **how the layers interact as one engineering system**.

---

# 🧭 Engineering Trajectory

<div align="center">

### **Where the learning is heading**

| 01 | 02 | 03 | 04 | 05 |
|:---:|:---:|:---:|:---:|:---:|
| 🧠 | ⚡ | 📦 | ☁️ | 🚀 |
| **Understand** | **Infrastructure** | **Orchestrate** | **Scale** | **Operate** |
| Models & Algorithms | Compute & Systems | Containers & Kubernetes | Cloud & Distributed Systems | Production AI |

<br>

**Models → Systems → Infrastructure → Platforms → Production**

</div>

This is intentionally not a completion checklist.

DailyEpoch is the record of the progression itself — the **Engineering Logbook above is the source of truth** for what I have actually studied.

---



# 🌱 Current Focus

<div align="center">

### `SYSTEM STATUS // ACTIVE LEARNING`

| Layer | Current Direction |
|---|---|
| 🧠 **AI** | Model architectures, Transformers & modern AI systems |
| ⚡ **Compute** | CPU architecture, NVIDIA GPUs, CUDA & TensorRT |
| 🐧 **Systems** | Linux, networking & infrastructure fundamentals |
| 📦 **Platform** | Docker, Kubernetes & orchestration |
| ☁️ **Cloud** | AWS infrastructure & distributed systems |
| 📈 **Operations** | DevOps, MLOps, monitoring & production AI |

</div>

The current objective is to progressively connect these layers rather than study them in isolation.

---

# 🔗 Knowledge → Evidence

DailyEpoch acts as the chronological layer of my learning ecosystem.

```text
                    DAILY LEARNING
                          │
                          ▼
                    DailyEpoch
                  Engineering Log
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
       AI / ML       AI INFRASTRUCTURE    CLOUD
          │               │               │
          ▼               ▼               ▼
   Specialized       Specialized      Specialized
   Repositories      Repositories     Repositories
          │               │               │
          └───────────────┼───────────────┘
                          ▼
                   NOTES • CODE • LABS
                          │
                          ▼
                       PROJECTS
                          │
                          ▼
                      PORTFOLIO
```

**DailyEpoch answers:** *What am I learning?*

**Specialized repositories answer:** *How deeply am I learning it?*

**Projects answer:** *Can I apply it?*

---

# 🤝 Connect

If you're also learning or working across **AI, AI Infrastructure, Cloud, Kubernetes, DevOps, or MLOps**, feel free to connect, share feedback, or discuss engineering ideas.

<div align="center">

### **Learn in Public. Build in Public. Engineer in Public.**

<br>

> **"Every commit is a lesson. Every note is a building block. Every day is another step toward engineering intelligent systems at scale."**

<br>

🧩 *“Every day logged is another gradient in the space of understanding.”*

</div>
