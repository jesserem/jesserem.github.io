---
title: "Tutorial: Deep Reinforcement Learning for Combinatorial Optimization at IJCAI-ECAI 2026"
collection: talks
type: "Tutorial"
permalink: /talks/2026-08-15-ijcai-tutorial
venue: "IJCAI-ECAI 2026"
date: 2026-08-15
location: "Bremen, Germany"
---

I was one of five speakers on the half-day tutorial **"Deep Reinforcement Learning for Combinatorial Optimization"** (T17) at IJCAI-ECAI 2026, the joint International Joint Conference on Artificial Intelligence and European Conference on Artificial Intelligence, held in Bremen from 15–21 August 2026.

The tutorial was presented by the Information Systems group at TU/e: [Zaharah Bukhsh](https://research.tue.nl/en/persons/zaharah-bukhsh), [Yaoxin Wu](https://research.tue.nl/en/persons/yaoxin-wu), [Yingqian Zhang](https://research.tue.nl/en/persons/yingqian-zhang), Yue Yu and myself.

Combinatorial optimization problems such as vehicle routing and job shop scheduling are ubiquitous in real-world decision making, yet remain computationally challenging because they are NP-hard. The tutorial was built as a hands-on, step-by-step guide to developing end-to-end deep RL solutions for these problems, organised around four design pillars:

1. **Instance encoding** — how to structure raw problem data for a neural network.
2. **MDP formulation** — how to frame solution construction as sequential decision making.
3. **Neural architectures** — designs tailored to the structure of the problem.
4. **Policy optimization** — the RL algorithms used to train them.

The first half covered the theoretical foundations, the DRL algorithm landscape, applications to vehicle routing and job shop scheduling, and problems beyond the classical formulations. The second half was practical: real-world deployments, open challenges in benchmarking, generalization, safety and interpretability, followed by two code walkthroughs — one building a job shop scheduling solver, one a solver for the capacitated vehicle routing problem.

**Materials**
- Tutorial website: <https://ai-for-decision-making-tue.github.io/drl-co-tutorial/>
- Slides: <https://github.com/ai-for-decision-making-tue/drl-co-tutorial/blob/main/DRL%20for%20COP_final.pdf>
- Hands-on notebooks: <https://github.com/ai-for-decision-making-tue/drl-co-tutorial/tree/main/tutorials>
- Accompanying tutorial paper: [*Deep Reinforcement Learning for Combinatorial Optimization: A Tutorial*](https://research.tue.nl/en/publications/deep-reinforcement-learning-for-combinatorial-optimization-a-tuto/) (Wu, Bukhsh & Zhang)
