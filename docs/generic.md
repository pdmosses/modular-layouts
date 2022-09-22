---
title: Generic
nav_order: 1
---

# generic.html

```html
{% raw %}
---
layout: table_wrappers
---
<!DOCTYPE html>
<html lang="...">
  <head>
    <title>{% include title.txt %}</title>
    {% include? metadata.html %}
  </head>
  <body>
    <a ... href="#main-content">Skip to main content</a>
    {% include? svg.html %}
    {% include? sidebar.html %}
    {% include main.html %}
   </body>
</html>
{% endraw %}
```
