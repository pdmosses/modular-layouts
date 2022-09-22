---
title: Main header
parent: Main
has_children: true
nav_order: 1
---

# main-header.html

```html
{% raw %}
<header>
  {% include? search.html %}
  {% include? custom/main-head.html %}
  {% include? aux-nav.html %}
</header>
{% endraw %}
```
