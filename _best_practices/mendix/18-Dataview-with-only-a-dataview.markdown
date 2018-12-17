---

layout: post
rulenumber: 18
title:  "Data view with only a data view"
characteristic: Performance
impact_prio: 4
effort_prio: 3

---

**Why**
Multiple nested dataviews instead of using an N-deep path creates unnecessary calls your form to the Mendix Runtime. This will affect page loading performance negatively.

![19.png]({{ site.url }}/assets/19.png)

**How to fix**
Put ... in the child dataview directly and retrieve over multiple associations.
