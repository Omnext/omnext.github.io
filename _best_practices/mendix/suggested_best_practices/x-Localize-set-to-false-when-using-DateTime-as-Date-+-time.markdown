---

layout: post
rulenumber: 
title:  "Localize set to false when using DateTime as Date + Time"
characteristic: 
impact_prio: 
effort_prio:

---

**Why**
When the time of a DateTime attribute *is* relevant, set Localize to YES. This ensures that the rendering on pages and in Retrieve activities goes well, e.g. when you compare the value to [%CurrentDatetime%].

![41.png]({{ site.url }}/assets/41.PNG)

**How to fix**
Change localization of the DateTime attribute to YES. If you have existing data in your database, don't do this without intelligent conversion.
