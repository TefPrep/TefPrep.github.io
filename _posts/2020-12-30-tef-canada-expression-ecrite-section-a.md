---
title: TEF Canada
---

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  [{{ myimage.path }}](https://www.youtube.com/watch?v={{ myimage.basename }})
{% endfor %}
