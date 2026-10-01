---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/CV_Jesse_van_Remmerden.pdf" class="btn btn--primary">Download CV (PDF)</a></p>

I am a fourth-year PhD candidate at Eindhoven University of Technology working on reinforcement learning, discrete diffusion models and language models for combinatorial optimization. I expect to defend in January 2027 and am interested in postdoctoral and research positions.

**Email:** [j.v.remmerden@tue.nl](mailto:j.v.remmerden@tue.nl) · [jessevanremmerden@gmail.com](mailto:jessevanremmerden@gmail.com)  
**Links:** [Google Scholar](https://scholar.google.com/citations?user=53Qmfec3f8EC) · [GitHub](https://github.com/jesserem) · [ORCID](https://orcid.org/0009-0005-1966-6907) · [LinkedIn](https://www.linkedin.com/in/jesse-van-remmerden-9964b114b/) · [TU/e profile](https://www.tue.nl/en/research/researchers/jesse-van-remmerden)

Education
======
* **PhD Candidate, Artificial Intelligence for Planning and Scheduling**, Eindhoven University of Technology (TU/e), Jan. 2023 – Jan. 2027 (expected)
  * Information Systems group, Department of Industrial Engineering & Innovation Sciences (IE&IS); AI for Decision Making cluster
  * Supervised by Dr. Yingqian Zhang (promotor) and Dr. Zaharah A. Bukhsh (daily supervisor)
  * Five first-author papers (three journal, one workshop, one under review); three open-source codebases

* **MSc Artificial Intelligence**, Utrecht University, Feb. 2020 – Jun. 2022
  * *Cum Laude*, 8.2/10
  * Thesis (8.6/10): [Utilising Reinforcement Learning for the Diversified Top-*k* Clique Search Problem](https://studenttheses.uu.nl/handle/20.500.12932/43388)
  * Honours Young Innovators programme, Utrecht Honours College

* **BSc Computer Science**, University of Amsterdam, Sept. 2016 – Oct. 2019
  * Thesis (9/10): detecting dolphins in video footage with deep learning (Faster R-CNN)

Research
======

**DROVER — routing from instructions written in plain English** (2025 – present)  
First author; under review. Language-conditioned discrete diffusion. Built the first benchmark for instruction-following vehicle routing (26+ request types, ~3 × 10⁹ phrasings, reference solutions and an automatic verifier), and a diffusion model that reads the request through a frozen language model and steers its solution toward satisfying it. Obeys the stated request in **98–99%** of cases on 50–1,000 stops versus ~32% for the strongest existing neural solvers, and **87–90%** on request types never seen in training, where existing solvers achieve 0%. [Details](/publication/drover)

**CDQAC & Offline-LD — learning factory schedules from data, not simulators** (2023 – 2026)  
First author; *Machine Learning* (2025) and *TMLR* (2026). Offline RL for job shop and flexible job shop scheduling. Offline-LD was the first method to learn JSSP dispatching policies purely from a fixed set of past schedules, matching or beating simulator-trained baselines from only 100 examples. CDQAC went further: trained on schedules produced by *random* decisions, it matches or beats the best simulator-trained methods across four benchmark suites, scales to problems with ten times as many jobs as seen in training, and needs 10–25 training instances. Established that offline performance is governed by how much of the decision space the data covers rather than the quality of its solutions (rank correlation −0.95). [CDQAC](/publication/cdqac-2026) · [CDQAC project page](/cdqac/) · [Offline-LD](/publication/offline-ld-2025)

**MO-DCMAC — 50-year maintenance planning for Amsterdam's historic canal walls** (2023 – 2025)  
First author; *Neural Computing and Applications* (2025), with the City of Amsterdam. Multi-objective RL. Turned FMECA — the risk-scoring methodology Amsterdam's asset managers use in practice — into the training objective, so the learned plan optimizes cost and probability of collapse directly. Best plan in 5 of 6 test settings, up to 46% better than the rule-based strategies in use; the first deep multi-objective RL method of its kind applied to a real-world problem. [Details](/publication/mo-dcmac-2025)

Funded projects
======
* **STABILITY** — Sustainable Circular Life Extension Strategies for Inner-City Bridges and Quay Walls (NWA.1431.20.004), 2023 – 2027. Dutch Research Agenda consortium funded by NWO and the City of Amsterdam. [Project page](https://www.nwo.nl/en/projects/nwa143120004)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks and tutorials
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Professional experience
======
* **Blockchain Engineer**, Kryha, Amsterdam, Aug. 2018 – Jan. 2020
  * Built proofs-of-concept with smart contracts, tokenization, cryptography and federated learning
  * First prize, Odyssey Hackathon 2019 (Nature 2.0 track): a federated-learning, blockchain and evolutionary-computing proof-of-concept built in one weekend

Service and leadership
======
* **Member, PhD Council**, Eindhoven University of Technology, 2024 – 2025
* **Tutorial speaker**, [Deep Reinforcement Learning for Combinatorial Optimization](/talks/2026-08-15-ijcai-tutorial), IJCAI-ECAI 2026, Bremen
* Co-author of the 2022 municipal election programme, Volt Amsterdam (2021)
* Head of the Health, Welfare and Sports Committee, Jonge Democraten Amsterdam (2016 – 2017)

Technical skills
======
* **Programming:** Python (8+ years; PyTorch, PyTorch Lightning, JAX), C/C++, Rust, SQL, LaTeX
* **Machine learning:** Offline and online reinforcement learning (CQL, QR-DQN, SAC, multi-objective RL), discrete diffusion and classifier-free guidance, graph transformers, conditioning on frozen LLM encoders, reward/verifier/benchmark design, synthetic data generation
* **Optimization:** OR-Tools (CP-SAT), Gurobi, LKH
* **Infrastructure:** Linux/HPC (SLURM, Apptainer, Kubernetes/Run:AI), multi-GPU training on A100/H100/B200, Docker, Git, Weights & Biases
* **Languages:** Dutch (native), English (fluent, C1)

References
======
* **Dr. Yingqian Zhang** — PhD promotor, Information Systems, Eindhoven University of Technology — [yqzhang@tue.nl](mailto:yqzhang@tue.nl)
* **Dr. Zaharah A. Bukhsh** — daily supervisor, Information Systems, Eindhoven University of Technology — [z.bukhsh@tue.nl](mailto:z.bukhsh@tue.nl)
