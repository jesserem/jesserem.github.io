---
title: "A Deep Multi-Objective Reinforcement Learning Approach for Infrastructural Maintenance Planning with Non-Linear Utility Functions"
collection: publications
pubtype: workshop
permalink: /publication/modem-2023
excerpt: "The workshop paper that introduced the multi-objective actor&ndash;critic approach to infrastructural maintenance planning later developed into MO-DCMAC. Presented at the Multi-Objective Decision Making (MODeM) workshop at ECAI 2023 in Krak&oacute;w."
date: 2023-10-01
venue: "Multi-Objective Decision Making Workshop (MODeM) at ECAI 2023, Krak&oacute;w"
paperurl: "https://modem2023.vub.ac.be/papers/MODeM2023_paper_15.pdf"
authors: "Jesse van Remmerden, Maurice Kenter, Diederik M. Roijers, Yingqian Zhang, Charalampos Andriotis"
citation: "van Remmerden, J., Kenter, M., Roijers, D. M., Zhang, Y., & Andriotis, C. (2023). A Deep Multi-Objective Reinforcement Learning Approach for Infrastructural Maintenance Planning with Non-Linear Utility Functions. <i>Multi-Objective Decision Making Workshop (MODeM) at ECAI 2023</i>, Krak&oacute;w, Poland."
---

**Authors**  
Jesse van Remmerden, Maurice Kenter, Diederik M. Roijers, Yingqian Zhang, Charalampos Andriotis

## Summary

This workshop paper set out the case for treating infrastructural maintenance planning as a genuinely multi-objective problem rather than a single-objective one with a shaped reward, and introduced the deep multi-objective actor–critic approach that was subsequently developed into **MO-DCMAC** ([*Neural Computing and Applications*, 2025](/publication/mo-dcmac-2025)).

The central argument is that the utility functions asset managers actually use are **non-linear** — a maintenance plan that keeps the probability of collapse below a threshold at moderate cost is not interchangeable with one that achieves a lower expected cost while occasionally exceeding it. Methods that scalarise objectives linearly cannot represent such preferences, and so cannot recover the policies practitioners want.

**Links**  
- Paper: <https://modem2023.vub.ac.be/papers/MODeM2023_paper_15.pdf>
- Presented at: [MODeM 2023, ECAI 2023, Kraków](/talks/2023-10-01-talk-1)
- Journal version: [MO-DCMAC, *Neural Computing and Applications* (2025)](/publication/mo-dcmac-2025)
