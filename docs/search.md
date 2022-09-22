---
title: Search
parent: Main header
nav_order: 1
---

# search.html

```html
{% raw %}
{% capture search_placeholder %}
  {% include custom/search_placeholder.html %}
{% endcapture %}
<div class="search">
  <div>
    <input placeholder="{{ search_placeholder }}">
    <label> ... </label>
  </div>
  <div id="search-results">
  </div>
</div>
{% endraw %}
```
