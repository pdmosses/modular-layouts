---
title: Main footer
nav_order: 6
---

# main-footer.html

```html
{% raw %}
{% capture footer_custom %}
  {%- include footer_custom.html -%}
{% endcapture %}

{% if footer_custom != "" or site.last_edit_timestamp or site.gh_edit_link %}
<hr>

<footer>
  {% include back-to-top-link.html %}
  {% include custom/main-footer.html %}
  {% include custom/edit-timestamp.html %}
  {% include custom/edit-link.html %}
</footer>
{% endraw %}
```
