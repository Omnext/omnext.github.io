---

layout: post
rulenumber: 11
title:  "Avoid Inheritance Except System Module"
characteristic: Performance
impact_prio: 4
effort_prio: 3

---

**Why**
Inheritance, except from system module, is strongly discouraged because of the negative performance side effects.

![8.png]({{ site.url }}/assets/8.png)

**How to fix**
Instead of inheritance, just use separate objects which are associated to the main object. As an alternative, you can add the child’s attributes to the super entity and add an ObjectType enumeration.
