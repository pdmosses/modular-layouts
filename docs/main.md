---
title: Main
has_children: true
nav_order: 3
---

# main.html

```html
{% raw %}
<div class="main">
  {% include? main-header.html %}
  {% include? breadcrumbs-nav.html %}
  <main id="main-content">
    {% include? anchor-headings.html html=content %}
  </main>
  {% include? children-nav.html %}
  {% include? main-footer.html %}
</div>
{% include? search-button.html %}
{% include? mermaid.html %}
{% endraw %}
```
