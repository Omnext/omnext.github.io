---

layout: post
rulenumber: 33
title:  "Same microflow used in form"
characteristic: Performance
impact_prio: 3
effort_prio: 3

---

**Why**
Avoid unnecessary calls from your form to the Mendix Runtime. This will slow down page loading.

![16.png]({{ site.url }}/assets/16.png)

**How to fix**
Restructure the form to avoid calling multiple times the same microflow.
