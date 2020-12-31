---
title: ITA DOUBTS
excerpt_separator: <!--end_excerpt-->
---

## Tips for Expression Ecrite
<!--end_excerpt-->

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {% if myimage.extname contains 'png' %}
    {% assign words = myimage.basename | split:'_' %} 
    {% if words[1] contains 'ITADOUBTS' %}
      {{ words[2] }} 
    
    
   [![youtubethumnails]({{ myimage.path }})](https://www.youtube.com/watch?v={{ words[0] }}) 
    {% endif %}
  {% endif %}
{% endfor %}


