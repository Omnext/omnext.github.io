---

layout: post
rulenumber: 
title:  "Localize is set to true when using DateTime as Date"
characteristic: 
impact_prio: 
effort_prio:

---

**Why**
When you're only interested in a Date, don't use localization. A date is the same around the world but applying localization can result in different datevalues for your date attribute when looking at the date in different countries.

![40.png]({{ site.url }}/assets/40.png)

**How to fix**
Change localization of the DateTime attribute to NO. If you have existing data in your database don't do this without intelligent conversion.
