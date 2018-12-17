---

layout: post
rulenumber: 36
title:  "Style property used"
characteristic: Maintainability
impact_prio: 5
effort_prio: 4

---

**Why**
Avoid using the style property, because this will make the life of your UI designer a lot more complicated. It will be harder to overrule styles from CSS file level.

**How to fix**
Use generic classes instead, defined by the theme.
