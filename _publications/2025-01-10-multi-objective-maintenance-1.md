---
title: "Deep multi-objective reinforcement learning for utility-based infrastructural maintenance optimization"
collection: publications
permalink: /publication/mo-dcmac-2025
excerpt: "We present MO-DCMAC, a multi-objective deep centralized multi-agent actor–critic method for infrastructural maintenance planning. Unlike single-objective RL with reward shaping, MO-DCMAC optimizes directly over non-linear utilities (e.g., threshold and FMECA) and outperforms rule-based baselines across multiple maintenance environments, including a case study on Amsterdam’s quay walls."
date: 2025-01-10
venue: "Neural Computing and Applications (Springer)"
paperurl: "https://doi.org/10.1007/s00521-024-10954-0"
doi: "10.1007/s00521-024-10954-0"
authors: "Jesse van Remmerden, Maurice Kenter, Diederik M. Roijers, Charalampos Andriotis, Yingqian Zhang, Zaharah Bukhsh"
citation: "van Remmerden, J., Kenter, M., Roijers, D. M., Andriotis, C., Zhang, Y., & Bukhsh, Z. (2025). Deep multi-objective reinforcement learning for utility-based infrastructural maintenance optimization. Neural Computing and Applications. https://doi.org/10.1007/s00521-024-10954-0"
---

**Authors & Affiliations**  
Jesse van Remmerden, Yingqian Zhang, Zaharah Bukhsh — Information Systems (IE&IS), Eindhoven University of Technology, Eindhoven, The Netherlands.  
Maurice Kenter, Diederik M. Roijers — City of Amsterdam, The Netherlands.  
Diederik M. Roijers — AI Lab, Vrije Universiteit Brussel, Belgium.  
Charalampos Andriotis — Delft University of Technology, The Netherlands.  
*Corresponding author:* j.v.remmerden@tue.nl

**Abstract**  
In this paper, we introduce multi-objective deep centralized multi-agent actor-critic (MO-DCMAC), a multi-objective reinforcement learning method for infrastructural maintenance optimization, an area traditionally dominated by single-objective reinforcement learning (RL) approaches. Previous single-objective RL methods combine multiple objectives, such as probability of collapse and cost, into a singular reward signal through reward-shaping. In contrast, MO-DCMAC can optimize a policy for multiple objectives directly, even when the utility function is nonlinear. We evaluated MO-DCMAC using two utility functions, which use probability of collapse and cost as input. The first utility function is the threshold utility, in which MO-DCMAC should minimize cost so that the probability of collapse is never above the threshold. The second is based on the failure mode, effects, and criticality analysis methodology used by asset managers to assess maintenance plans. We evaluated MO-DCMAC, with both utility functions, in multiple maintenance environments, including ones based on a case study of the historical quay walls of Amsterdam. The performance of MO-DCMAC was compared against multiple rule-based policies based on heuristics currently used for constructing maintenance plans. Our results demonstrate that MO-DCMAC outperforms traditional rule-based policies across various environments and utility functions.

**Keywords**  
Reinforcement learning; Multi-objective reinforcement learning; Maintenance; Infrastructure

**Links**  
- DOI: <https://doi.org/10.1007/s00521-024-10954-0>  
- arXiv: <https://arxiv.org/abs/2406.06184v2>

**BibTeX**
```bibtex
@article{vanRemmerdenMultiObjective2025,
  abstract = {In this paper, we introduce multi-objective deep centralized multi-agent actor-critic (MO-DCMAC), a multi-objective reinforcement learning method for infrastructural maintenance optimization, an area traditionally dominated by single-objective reinforcement learning (RL) approaches. Previous single-objective RL methods combine multiple objectives, such as probability of collapse and cost, into a singular reward signal through reward-shaping. In contrast, MO-DCMAC can optimize a policy for multiple objectives directly, even when the utility function is nonlinear. We evaluated MO-DCMAC using two utility functions, which use probability of collapse and cost as input. The first utility function is the threshold utility, in which MO-DCMAC should minimize cost so that the probability of collapse is never above the threshold. The second is based on the failure mode, effects, and criticality analysis methodology used by asset managers to assess maintenance plans. We evaluated MO-DCMAC, with both utility functions, in multiple maintenance environments, including ones based on a case study of the historical quay walls of Amsterdam. The performance of MO-DCMAC was compared against multiple rule-based policies based on heuristics currently used for constructing maintenance plans. Our results demonstrate that MO-DCMAC outperforms traditional rule-based policies across various environments and utility functions.},
  author = {van Remmerden, Jesse and Kenter, Maurice and Roijers, Diederik M. and Andriotis, Charalampos and Zhang, Yingqian and Bukhsh, Zaharah},
  date = {2025/01/10},
  doi = {10.1007/s00521-024-10954-0},
  isbn = {1433-3058},
  journal = {Neural Computing and Applications},
  title = {Deep multi-objective reinforcement learning for utility-based infrastructural maintenance optimization},
  url = {https://doi.org/10.1007/s00521-024-10954-0},
  year = {2025},
```
