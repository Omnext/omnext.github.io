---

layout: post
rulenumber: 
title:  "Avoid using validation rules"
characteristic: 
impact_prio: 
effort_prio:

---

**Why**
Validation rules on domain model level will give the users unexpected errors. For example, when importing data you maybe want to store invalid data temporary.

![39.png]({{ site.url }}/assets/39.png)

**How to fix**
Remove datamodel validations and validate by microflows from UI. If you really need a validation rule, make sure to document it.
