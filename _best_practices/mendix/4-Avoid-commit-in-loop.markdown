---

layout: post
title:  "Avoid commit in loop  "
rulenumber: 4
impact_prio: 3
effort_prio: 5
characteristic: Performance

---

**Why**
Commiting objects within a loop will fire a SQL Update query for each iteration. This will decrease performance.

![29.png]({{ site.url }}/assets/29.png)

**How to fix**
Consider committing objects outside the loop. Within the loop, add them to a list.
