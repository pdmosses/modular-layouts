---
title: Generic
nav_order: 1
---

# generic.html

All the other top-level includes shown in the navigation panel are intended to be optional.
Some of them have children, which are also intended to be optional includes.

```html
{% raw %}
---
layout: table_wrappers
---
<!DOCTYPE html>
<html lang="...">
  <head>
    <title>{% include title.txt %}</title>
    {% include metadata.html %}
  </head>
  <body>
    <a ... href="#main-content">Skip to main content</a>
    {% include svg.html %}
    {% include sidebar.html %}
    <div class="main">
      {% include main-header.html %}
      {% include breadcrumbs-nav.html %}
      <main id="main-content">
        {% if site.heading_anchors != false %}
          {% include vendor/anchor_headings.html html=content ... %}
        {% else %}
          {{ content }}
        {% endif %}
      </main>
      {% include children-nav.html %}
      {% include main-footer.html %}
    </div>

    {% include mermaid.html %}
   </body>
</html>
{% endraw %}
```
