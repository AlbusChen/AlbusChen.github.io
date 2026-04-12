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

Currently I am a PhD student in the Information Systems Technology and Design (ISTD) pillar at the **Singapore University of Technology and Design (SUTD)**, where I joined in September 2024. I am fortunate to be supervised by Professor [Wenxuan Zhang](https://isakzhang.github.io/) and to be a member of the [iNLP Lab](https://isakzhang.github.io/group.html) at SUTD. My research focuses on **Natural Language Processing (NLP)**, with interests spanning large language model reasoning and efficiency.

Before joining SUTD, I received my Master of Library & Information Science from **East China Normal University** (2022–2024). Prior to that, I completed dual bachelor's degrees — in Business Administration from **East China Normal University** and in Global BBA from **Emlyon Business School** (2018–2022).


# 🔥 News and Events
- *2026.04*: &nbsp;🌟 I will be attending **ICLR 2026** in Rio de Janeiro, Brazil. If you are around, feel free to reach out — always happy to connect!
- *2026.02*: &nbsp;🎉 New project [MoltNet](https://inlp-lab.github.io/MoltNet/) — understanding social behavior of AI agents in the agent-native MoltBook — is now available on arXiv.
- *2025.10*: &nbsp;🎉 Paper "PEAR: Phase Entropy Aware Reward for Efficient Reasoning" accepted at **ICLR 2026**.
- *2025*: &nbsp;🎉 Paper "Text Clustering as Classification with LLMs" accepted at **SIGIR-AP 2025**.
- *2025*: &nbsp;🎉 Paper "Through the Valley: Path to Effective Long CoT Training for Small Language Models" accepted at **EMNLP 2025**.

# 📝 Publications 

- [MoltNet: Understanding Social Behavior of AI Agents in the Agent-Native MoltBook](https://arxiv.org/abs/2602.13458), Y. Feng, **C. Huang**, Z. Man, R. Tan, L.P. Hoang, S. Xu, W. Zhang, *arXiv preprint arXiv:2602.13458, 2026* \| [[Project Page]](https://inlp-lab.github.io/MoltNet/)

- [Text Clustering as Classification with LLMs](https://dl.acm.org/doi/pdf/10.1145/3767695.3769519), **C. Huang**, G. He, *Proceedings of SIGIR-AP 2025*

- [Through the Valley: Path to Effective Long CoT Training for Small Language Models](https://aclanthology.org/2025.emnlp-main.251.pdf), R. Luo, J. Li, **C. Huang**, W. Lu, *Proceedings of EMNLP 2025*

- [PEAR: Phase Entropy Aware Reward for Efficient Reasoning](https://openreview.net/pdf?id=HLc2igXEA3), **C. Huang**, W. Lu, W. Zhang, *ICLR 2026*

- [Few-Shot Medical Relation Extraction via Prompt Tuning Enhanced Pre-trained Language Model](https://www.sciencedirect.com/science/article/abs/pii/S0925231225004242), G. He, **C. Huang**, *Neurocomputing 633, 129752, 2025*

# 📖 Educations
- *2024.09 - 2029.06 (expected)*, Doctor of Philosophy (PhD), Information Systems Technology and Design (ISTD), **Singapore University of Technology and Design (SUTD)**, Singapore.
- *2022.09 - 2024.06*, Master of Library & Information Science (MLIS), **East China Normal University**, Shanghai, China. Main research focus: Natural Language Processing.
- *2020.09 - 2022.06*, Bachelor, Global Bachelor Business Administration, **Emlyon Business School**, France.
- *2018.09 - 2020.06*, Bachelor, Business Administration, **East China Normal University**, Shanghai, China.

# 💻 Internships
- *2023.05 - 2023.11*, NLP Intern, **China Pacific Insurance (Group) Co Ltd (CPIC)**, Shanghai, China.
  - Deployed large language models (ChatGLM2-6b) from scratch with API serving via FastAPI and OpenAI-compatible format.
  - Explored quantization-based low-cost deployment, achieving local inference under 7 GB GPU memory.
  - Fine-tuned LLMs using P-Tuning v2 and full-parameter fine-tuning with DeepSpeed-Chat.
  - Designed a task-oriented dialogue (TOD) workflow for CPIC's intelligent voice customer service, covering intent recognition, entity slot extraction, and multi-turn dialogue management.
  - Constructed a multi-domain TOD training dataset (100K+ dialogue turns across 30 domains) by combining open-source datasets (CrossWOZ, MultiWOZ 2.2, RiSAWOZ) with proprietary data.