---

layout: post
rulenumber: 
title:  "Avoid to generate related objects in events"
characteristic: 
impact_prio: 
effort_prio:

---

**Why**
Unwanted behaviour if the after create event of a parent object creates child objects when this is in use in nested dataviews. 

**How to fix**
Use a microflow with a Get or Create pattern
