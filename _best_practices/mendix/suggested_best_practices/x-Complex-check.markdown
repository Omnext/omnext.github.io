---

layout: post
rulenumber: 
title:  "Avoid complexity"
characteristic: 
impact_prio: 
effort_prio:

---

**Why**
Using a long if-then-else construction within one single split will make it harder to 'read' the microflow without having to click activities for details.

![32.png]({{ site.url }}/assets/32.png)

**How to fix**
Please divide the split into multiple ones for read-ability and documentation.
