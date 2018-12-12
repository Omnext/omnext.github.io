---

layout: post
title:  "Avoid inheritance administration account"
rulenumber: 10
impact_prio: 4
effort_prio: 4
characteristic: Performance

---

**Why**
There is no need to inherit from administration.account. Administration.account may simply be extended, this is not a system module. Avoid unnecessary inheritance as this has a negative effect on performance.

![5.png]({{ site.url }}/assets/5.png)

**How to fix**
Just inherit from system.user instead or adapt Administration.Account so it fits your needs.
