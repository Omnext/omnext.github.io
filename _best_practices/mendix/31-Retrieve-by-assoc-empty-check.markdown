---

layout: post
rulenumber: 31
title:  "Retrieve by associated empty check"
characteristic: Performance
impact_prio: 4
effort_prio: 4

---

**Why**
Retrieving the assocation will most of the times result in a database query. Just checking that a reference != empty can already be done without retrieving the associated object. This is because Mendix is quering the references by default.

![26.png]({{ site.url }}/assets/26.png)

**How to fix**
Remove the retrieve by association and change your split to $mainobject/associationname != empty.
