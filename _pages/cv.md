---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
- **University of Southern California** — M.S. in Computer Science (2025–2027)
- **University of Wisconsin–Madison** — B.S. in Biomedical Engineering & Computer Science (2021–2025)  
  Coursework: AI/ML Principles, Deep Learning, Advanced Computer Vision, Linear Algebra, Probability & Statistics, Differential Equations, Circuit Analysis

---

## Skills
- **ML Frameworks:** PyTorch, DeepSpeed (distributed training), Hugging Face, TensorFlow, Scikit-learn, LangChain, LangGraph
- **Infrastructure & Serving:** AWS, GCP, Docker, Linux, Git, ETL pipelines, MLOps
- **Data & Retrieval:** SQL (PostgreSQL, SQLite), vector databases, Neo4j/Cypher, RAG, GraphRAG
- **Languages:** Python, C++, SQL, Bash
- **Domains:** Computer Vision, NLP, RL, Embeddings and Retrieval, Multimodal Models

---

## Experience

**Machine Learning Engineer Intern**
_Visa, Austin, TX (May 2026–Aug 2026)_
- Built and deployed an autonomous, containerized DS pipeline (10-agent LangGraph DAG via FastAPI and ChromaDB) to Visa's Sentinel Grid Kubernetes platform, compressing 1 week of data-scientist workflow into 30 minutes with human-in-the-loop review gates.
- Designed a dual-write experiment knowledge base (SQLite + ChromaDB, 11 vector collections) that surfaces cross-team modeling priors, improving downstream model performance **2–10%** and cutting redundant pipeline iterations **2×**.
- Implemented zero-overhead feature attribution via counterfactual metric deltas computed in SQL against historical runs, measuring feature effectiveness without in-run ablations.
- Diagnosed three production blockers (single-writer DB serialization, synchronous training blocking the async event loop, per-process event bus) and led migration to a PostgreSQL pool, dedicated REST compute service, and pub/sub events.

---

**Research Assistant — Physical Superintelligence Lab**
_University of Southern California, Los Angeles, CA (Aug 2025–Present)_
- Training a **pi0.5 vision-language-action model** on ~30M frames from DROID and other manipulation datasets for in-context adaptation to unseen robot embodiments.
- Developed an **embodiment-conditioning method** that predicts action-normalization parameters from ~20 frames of motion context (same- and cross-episode), enabling a single policy to adapt its action distribution to new kinematics without retraining.

---

**Machine Learning Intern**
_Advanced Space, Westminster, CO (May–Aug 2025)_
- Built an automated **ETL pipeline** using Python and Neo4j to ingest and structure 5,000+ technical documents, reducing data retrieval latency by 30%.
- Developed a **GraphRAG system** with a modular MCP tool integrating Cypher query generation; outperformed baseline vector search accuracy by 18% on complex, multi-hop queries.
- Created and optimized **RL/IRL algorithms** for multi-object simulation environments, achieving >85% success rates in latent goal inference through hyperparameter tuning.
- Contributed technical architecture and feasibility analysis for a **NASA NIAC Phase 1 proposal**, defining ML system requirements for autonomous space exploration.

---

**Machine Learning Engineer**
_Revilico Inc, Los Angeles, CA (Apr 2024–May 2025)_
- Architected and managed **model training pipelines on AWS**, optimizing compute resources to validate eight novel drug activity predictors.
- Standardized model inference scripts and artifacts, streamlining handoff to DevOps and enabling seamless integration into the user-facing frontend.
- Engineered **feature extraction tools for SMILES sequences**, boosting IC50/EC50 prediction R² scores by ~0.12 through improved data representation.
- Designed **deep learning architectures for proteomic classification**, improving accuracy by 15–25% over industry baselines across 30 protein families.
- Built **RL frameworks** for de novo molecular generation, yielding 100+ novel compounds optimized for electronegativity, folding patterns, and pH balance.

---

**Computer Vision Researcher**
_University of Wisconsin–Madison (May 2024–May 2025)_
- Contributed to a novel framework for **temporally stable and corruption-robust video inference**, integrating stabilization adapters into frozen vision backbones.
- Headed design and evaluation of adversarial robustness experiments, delivering **+11.8% accuracy under iterative attacks** without retraining base networks.
- Crafted **stabilizer modules for ResNet architectures**, reducing fine-tuning time by 40% while maintaining state-of-the-art robustness.
- Constructed and benchmarked a **binary human/nonhuman classification task** on the DAVIS dataset (3,455 annotated frames) with a fine-tuned ResNet-50.

---

**Visual Large Language Model Researcher**
_University of Central Florida (May–Oct 2023)_
- Oversaw collaboration with researchers from UCF and Meta, driving advancements in large language model research.
- Refined complex **65B-parameter models** into streamlined 7B-parameter university-level models, reducing compute cost by 92%.
- Devised a **VLLM training method** merging 150k+ images and 160k+ text examples across multiple training stages.
- Attained **95% of industry-leading text-based model performance** using a practical-sized VLLM.
- Utilized **PyTorch and DeepSpeed** frameworks for parallel training on high-performance GPU clusters.

---

**Quantitative Cell Imaging Researcher**
_University of Wisconsin–Madison (Feb–Sep 2023)_
- Built DL tools for tumor micro-environment quantification (**95% IoU**).
- Increased imaging throughput **1.2×**, enabling 10,000 cells/day analysis.

---

## Publications
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

## Awards & Honors
- **Peter Tong Award** (2025) — Best Design Project  
- **Congressional Hackathon Honorable Mention** (2024)  
- **Design Excellence Award Honorable Mention** (2024)  
- **James Marshall Scholarship** (2024)  
- **Fred W. & Josephine Colbeck Scholarship** (2024)  
- **Koch Family Foundation Scholarship** (2024)  
- **Norman & Marie Ahlswede Endowment Scholarship** (2023)  
- **IFC Distinguished Brother Scholarship** (2022)  

---

## Projects
- **Wireless Pressure Sensor for Casts** — Real-time Bluetooth-enabled sensor for preventing ulcers; app and hardware lead.  
- **Catch Up With My Committee** — NLP-powered platform simplifying legislation; presented at 2024 Congressional Hackathon.  
- **Intraoperative Patient Warming Device** — Eco-friendly surgical warming device with 20% better heat retention.  

---

## Leadership
**Triangle Fraternity (2021–Present)**  
- VP of Academics: Led tutoring and workshops; raised chapter to **Top-5 GPA** on campus.  
- Treasurer: Organized philanthropy, raising **$2,000+**; taught finance literacy workshops.

---

## References
- **Prof. Niels Lobo** — University of Central Florida — niels@cs.ucf.edu  
- **Prof. Mohit Gupta** — University of Wisconsin–Madison — mohitg@cs.wisc.edu  
- **Prof. John Puccinelli** — University of Wisconsin–Madison — john.puccinelli@wisc.edu  
