---
title: Sidebar
has_children: true
nav_order: 2
---

# sidebar.html

```html
{% raw %}
<div class="sidebar">
  {% include? sidebar-header.html %}
  {% include? sidebar-nav.html %}
  {% include? sidebar-footer.html %}
</div>
{% endraw %}
```
