---

layout: post
rulenumber: 34
title:  "Same retrieve by associated used in form"
characteristic: Performance
impact_prio: 3
effort_prio: 3

---

**Why**
This will result in unnecessary calls from your form to the Mendix Runtime. This will slow down page loading.

![17.png]({{ site.url }}/assets/17.png)

**How to fix**
Restructure the form to avoid calling multiple times the same association.
