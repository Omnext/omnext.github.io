---

layout: post
title:  "Avoid create file doc or image  "
rulenumber: 5
impact_prio: 3
effort_prio: 1
characteristic: Security

---

**Why**
Avoid creating filedocuments or images. Because security options on both objects are very limited.

![22.png]({{ site.url }}/assets/22.png)

**How to fix**
Inherit always from system domain objects before using them. In that way you can configure your own security.
