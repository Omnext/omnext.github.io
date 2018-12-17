---

layout: post
rulenumber: 
title:  "Avoid use validation feedback within event microflows"
characteristic: 
impact_prio: 
effort_prio:

---

**Why**
Don't use feedback activities in Event microflows (after create/after commit etc.)

**How to fix**
Use separate submicroflows and execute them in your microflows triggered by a user action
