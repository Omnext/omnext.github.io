---

layout: post
title:  "Avoid excesive cross module associations"
rulenumber: 9
impact_prio: 3
effort_prio: 4
characteristic: Maintainability

---

**Why**
Module x is strongly dependent of module y. This will make it harder to reuse this module.

![9.png]({{ site.url }}/assets/9.png)

**How to fix**
Consider to combine the modules or create a façade within module y.
