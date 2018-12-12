---

layout: post
title:  "Avoid commit in before and after commit action  "
rulenumber: 3
impact_prio: 1
effort_prio: 3
characteristic: Reliability

---

**Why**
Before and after commit actions should not commit the object itself with an event. The result is an infinite loop in the microflow.

![10.png]({{ site.url }}/assets/10.png)

**How to fix**
Don't commit in BCo actions and commit without events in ACo actions.
