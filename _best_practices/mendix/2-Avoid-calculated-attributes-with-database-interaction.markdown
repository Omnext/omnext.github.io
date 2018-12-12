---

layout: post
title:  "Style property used"
categories: Forms
prio: 5
rulenumber: 13
rulename: StylePropertyUsed
ruleset: Maintainability

---

**Why**
Microflow attributes have a strong negative impact on performance, especially the attributes that have database interaction. If you managed to eliminate for example about 100 MF attributes on a medium/large application (model size +- 100MB) you will probably increase performance on load tests with factor 3-6.

![3.png]({{ site.url }}/assets/3.png)

**How to fix**
Make the attributes 'stored' and calculate them in an event, or put the microflow attributes in a separate object.
