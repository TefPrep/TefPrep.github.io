---
title: TEF Canada
excerpt_separator: <!--end_excerpt-->
---

## Tips for Expression Ecrite
<!--end_excerpt-->

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  [![youtubethumnails]({{ myimage.path }})](https://www.youtube.com/watch?v={{ myimage.basename }})
{% endfor %}


