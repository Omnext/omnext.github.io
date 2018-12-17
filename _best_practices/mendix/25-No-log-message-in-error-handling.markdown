---

layout: post
rulenumber: 25
title:  "No log message in error handling"
characteristic: Reliability
impact_prio: 2
effort_prio: 4

---

**Why**
Error handling without logging will make it very hard to debug errors. You won't see anything in the log.

![25.png]({{ site.url }}/assets/25.png)

**How to fix**
Add a log message in custom error handling. Make sure to check the 'Add latest stacktrace" box as well.
