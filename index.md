---
title: Home
nav_order: 0
---

# Modular Layouts

This website shows some initial ideas for the modular structure of layouts.

The illustrated structure for a generic default layout is _loosely_ based on the current `_layouts/default.html`.

The inclusion of particular modules would be subject to tests of site and/or page variables.
Optional elements are indicated by `include?`,
where the included file is supposed to test the relevant condition.

A particular constellation of modules could be named as a new layout,
thereby making it simpler to use consistently.
There may be constraints between inclusion of specific modules – 
e.g., a search button can be included only if a search module is included.
However, the inclusion of one module never(?) prevents the inclusion of other modules .
(It may be helpful to make a feature diagram of the module inclusions,
and .)

A minimal layout is obtained by omitting all conditionally-included modules,
leaving only the main content.
A default layout is obtained by including them all
