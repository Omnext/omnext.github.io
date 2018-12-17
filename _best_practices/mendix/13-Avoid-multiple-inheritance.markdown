---

layout: post
rulenumber: 13
title:  "Avoid Multiple Inheritance"
characteristic: Performance
impact_prio: 2
effort_prio: 2

---

**Why**
When an entity inherits from an object that inherits itself from another entity. Multiple inheritance is strongly discouraged because of the negative performance side effects. Query complexity will increase a lot when showing datagrids of the generalizion because all access rules of the inheriting objects are applied in an OR constraint.

![7.png]({{ site.url }}/assets/7.png)

**How to fix**
Refer with a one to one assocation to a separate entity.
