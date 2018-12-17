---

layout: post
rulenumber: 32
title:  "Retrieve result only used in filter"
characteristic: Performance
impact_prio: 2
effort_prio: 4

---

**Why**
A filter is used on a retrieve action but the list is not used again. This can be a performance killer because Mendix is retrieving all your objects in memory because the filter is modeled a a separate action.

![23.png]({{ site.url }}/assets/23.png)

**How to fix**
Add the filter to the xPath constraint property instead of filtering. Now you will directly get the list of objects that's needed.
