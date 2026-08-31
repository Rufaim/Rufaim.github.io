---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About

I’m a machine learning researcher focused on building scalable AI systems and advancing modern deep learning architectures.

My research focuses on scalable and modular architectures for next-generation language models, with particular emphasis on Mixture-of-Experts (MoE) systems, efficient inference, and LLM evaluation. I’m interested in improving model specialization, computational efficiency, and robustness in real-world AI systems.

I’m particularly interested in challenges that emerge at scale, including efficient model routing, structured reasoning, multi-LLM orchestration, and reducing inference costs for large AI systems. My goal is to make powerful machine learning models more practical to operate efficiently in production environments.

My broader background combines machine learning research with software engineering and backend system design. I have experience building production-oriented services in Python, designing API-driven ML backends with FastAPI, and developing distributed training and inference systems on multi-GPU clusters. This engineering perspective allows me to bridge the gap between machine learning research and deployable AI systems.

**Research interests:** AI/ML/Deep Learning, Scalable Machine Learning Systems, Efficient Inference and LLM Systems, Large Language Models, Mixture-of-Experts Models, Graph Neural Networks, Neural Architecture Search.

**Technical expertise:** Python, PyTorch, Golang, FastAPI, LLMs, RAG, multi-agent systems, distributed training and inference, ML model deployment, Ray, vLLM, AWS, GCP, Docker, CI/CD, and MLflow.

# 💻 Work Experience

- *June 2023 – February 2026*, AI Research Scientist, Huawei Noah’s Arc Lab, Montreal, QC, Canada.
- *September 2021 – November 2022*, AI Developer, 6th Grain, Montreal, QC, Canada (remote).
- *September 2019 – August 2025*, Graduate AI Researcher, McGill Networks Research Lab, Montreal, QC, Canada.
- *October 2017 – July 2019*, Machine Learning Engineer, PolySoft, Moscow, Russia.

# 📖 Education

- *September 2019 – February 2026*, PhD in Electrical Engineering, McGill University, Montreal, QC, Canada.
- *September 2017 – May 2019*, Master’s Degree in Applied Mathematics, National Research University Higher School of Economics, Moscow, Russia.
- *September 2013 – May 2017*, Bachelor’s Degree in Control Systems Engineering, Moscow Technological University, Moscow, Russia.

# 💬 Talks

- *2025*, [LLM Evaluation Workshop](https://sites.google.com/view/llm-eval-workshop), NeurIPS 2025.
- *2025*, [Graph Signal Processing Workshop](https://gspworkshop.org), Graph Knowledge Distillation to Mixture of Experts.
- *2024*, Neural Architecture Search, ILLS research seminar.
- *2023*, [ICASSP 2023](https://2023.ieeeicassp.org), Efficient Zero-Shot Neural Architecture Search.

# 📝 Publications

- `NeurIPS 2025 Workshop` [FEval-TTC: Fair Evaluation Protocol for Test-Time Compute](https://openreview.net/forum?id=Fj9Ge7TdrY), Pavel Rumiantsev, Soumyasundar Pal, Yingxue Zhang, and Mark Coates.
- `NeurIPS 2025` [C3PO: Optimized Large Language Model Cascades with Probabilistic Cost Constraints for Reasoning](https://openreview.net/forum?id=e4IlBqhbTO), Antonios Valkanas, Soumyasundar Pal, **Pavel Rumiantsev**, Yingxue Zhang, and Mark Coates.
- `TMLR 2025` [Variation matters: from mitigating to embracing Zero-Shot NAS ranking function variation](https://openreview.net/forum?id=SbGt90dxdp), **Pavel Rumiantsev** and Mark Coates.
- `TMLR 2025` [Sparse Decomposition of Graph Neural Networks](https://openreview.net/forum?id=xdWP1d8BxI), Yaochen Hu, Mai Zeng, Ge Zhang, **Pavel Rumiantsev**, Liheng Ma, Yingxue Zhang, and Mark Coates.
- `TMLR 2024` [Graph Knowledge Distillation to Mixture of Experts](https://openreview.net/forum?id=vzZ3pbNRvh), **Pavel Rumiantsev** and Mark Coates.
- `ICASSP 2023` [Performing Neural Architecture Search without gradients](https://ieeexplore.ieee.org/abstract/document/10094582), **Pavel Rumiantsev** and Mark Coates.
