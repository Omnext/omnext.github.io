---
layout: post
rulenumber: 27
title:  "Number of entities (>15)"
characteristic: Maintainability
impact_prio: 3
effort_prio: 2

---

**Why**
The bigger the domain models, the harder they will be to maintain. It adds complexity to your security model as well. The smaller the modules, the easier to reuse.

![1.png]({{ site.url }}/assets/1.png)

**How to fix**
Split domain model into multiple modules.
