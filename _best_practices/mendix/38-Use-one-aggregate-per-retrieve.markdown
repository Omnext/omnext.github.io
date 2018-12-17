---

layout: post
rulenumber: 38
title:  "Use one aggregate per retrieve"
characteristic: Performance
impact_prio: 2
effort_prio: 3

---

**Why**
Using one list retrieved from database within multiple aggregates has a negative performance impact. This is because Mendix Runtime will optimize a retrieve action + aggregate action to one aggregate query (e.g. SELECT SUM(..) FROM ..)) instead, retrieving the complete list in memory and a (Java) memory aggregation.

![24.PNG]({{ site.url }}/assets/24.PNG)

**How to fix**
For each aggregate, add a new database retrieve action.  This will result in more activities but will be much faster.
