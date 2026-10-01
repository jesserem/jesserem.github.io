---
title: "DROVER: Diffusion-Based Routing with Verbal Preferences"
collection: talks
type: "Talk"
permalink: /talks/2026-08-16-dso-workshop-drover
venue: "Data Science Meets Optimisation (DSO) Workshop at IJCAI-ECAI 2026"
date: 2026-08-16
location: "Bremen, Germany"
---

I presented [DROVER](/publication/drover) in Session 1 of the **Data Science Meets Optimisation (DSO)** workshop at IJCAI-ECAI 2026, held in Bremen on 16 August 2026. The workshop runs under the auspices of the DSO working group of the Association of European Operational Research Societies (EURO), and was chaired by Yaoxin Wu (TU/e), Jayanta Mandi (KU Leuven), Neil Yorke-Smith (TU Delft) and Yingqian Zhang (TU/e). The work is joint with Zaharah Bukhsh and Yingqian Zhang.

Neural routing solvers plan efficient tours against a fixed scalar objective. Real dispatchers do not work that way — they issue requests such as *"visit customer 7 before customer 4"* or *"keep these three stops on one truck"*, which vary daily and cannot practically be encoded as reward terms in advance. No existing neural routing solver accepts such a request as input.

The talk presented DROVER, which conditions a discrete diffusion model on a natural-language request read through a frozen language model, and steers the denoising trajectory toward satisfying it with a new guidance technique. It also covered the benchmark built for this setting — 26+ request types, roughly 3 × 10⁹ possible phrasings, and an automatic verifier that determines whether a proposed tour actually obeys its request, without which instruction-following is not a measurable quantity at all.

DROVER satisfies the stated request in 98–99% of cases on instances of 50 to 1,000 stops, against roughly 32% for the strongest existing neural solvers, and reaches 87–90% on request types never encountered in training, where existing solvers score 0%.

**Links**
- Workshop programme: [DSO @ IJCAI-ECAI 2026](https://sites.google.com/view/dso-workshopijcai-2026/program)
- Paper: [DROVER (under review)](/publication/drover)
