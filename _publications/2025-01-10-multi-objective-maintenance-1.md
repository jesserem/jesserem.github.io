---
title: "Deep multi-objective reinforcement learning for utility-based infrastructural maintenance optimization"
collection: publications
pubtype: journal
permalink: /publication/mo-dcmac-2025
excerpt: "MO-DCMAC is the first deep multi-objective RL method of its kind applied to a real-world infrastructure problem. Rather than collapsing cost and probability of collapse into a shaped reward, it optimizes directly over non-linear utilities &mdash; including FMECA, the risk-scoring methodology Amsterdam&rsquo;s asset managers already use in practice. It produced the best maintenance plan in 5 of 6 test settings, improving on the rule-based strategies currently in use by up to 46%."
date: 2025-01-10
venue: "Neural Computing and Applications"
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

## Summary

Amsterdam's historic quay walls are deteriorating, and the city must decide which to repair and when over a fifty-year horizon, trading off the cost of intervention against the probability of structural collapse. Reinforcement learning approaches to infrastructure maintenance have conventionally combined such objectives into a single scalar through reward shaping — a step that quietly discards the very trade-off asset managers need to reason about, and that requires the modeller to fix the relative weighting of cost against risk before any policy is learned.

MO-DCMAC optimizes over multiple objectives directly, including when the utility function is non-linear. The design decision that matters most here is the choice of objective: rather than inventing a proxy reward, we turned **FMECA** — the failure mode, effects and criticality analysis methodology that Amsterdam's asset managers already use to assess maintenance plans — into the training objective. The learned policy therefore optimizes the quantity practitioners actually act on, which is also what makes the resulting plans legible to them.

**Key results**

- Best maintenance plan in **5 of 6 test settings**, evaluated across multiple maintenance environments including ones derived from a case study of Amsterdam's historical quay walls.
- Up to **46% improvement** over the rule-based heuristic strategies currently used to construct maintenance plans.
- The **first deep multi-objective RL method of its kind applied to a real-world problem**, evaluated under two distinct utility functions (a threshold utility and the FMECA-based utility).

This work forms part of **[STABILITY](https://www.nwo.nl/en/projects/nwa143120004)** (Sustainable Circular Life Extension Strategies for Inner-City Bridges and Quay Walls, NWA.1431.20.004), a 2023–2027 Dutch Research Agenda consortium funded by NWO and the City of Amsterdam.

**Abstract**  
In this paper, we introduce multi-objective deep centralized multi-agent actor-critic (MO-DCMAC), a multi-objective reinforcement learning method for infrastructural maintenance optimization, an area traditionally dominated by single-objective reinforcement learning (RL) approaches. Previous single-objective RL methods combine multiple objectives, such as probability of collapse and cost, into a singular reward signal through reward-shaping. In contrast, MO-DCMAC can optimize a policy for multiple objectives directly, even when the utility function is nonlinear. We evaluated MO-DCMAC using two utility functions, which use probability of collapse and cost as input. The first utility function is the threshold utility, in which MO-DCMAC should minimize cost so that the probability of collapse is never above the threshold. The second is based on the failure mode, effects, and criticality analysis methodology used by asset managers to assess maintenance plans. We evaluated MO-DCMAC, with both utility functions, in multiple maintenance environments, including ones based on a case study of the historical quay walls of Amsterdam. The performance of MO-DCMAC was compared against multiple rule-based policies based on heuristics currently used for constructing maintenance plans. Our results demonstrate that MO-DCMAC outperforms traditional rule-based policies across various environments and utility functions.

**Keywords**  
Reinforcement learning; Multi-objective reinforcement learning; Maintenance; Infrastructure

**Links**  
- DOI: <https://doi.org/10.1007/s00521-024-10954-0>  
- arXiv: <https://arxiv.org/abs/2406.06184v2>  
- Code: <https://github.com/jesserem/MODCMAC>  
- Project: [STABILITY (NWO, NWA.1431.20.004)](https://www.nwo.nl/en/projects/nwa143120004)

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
