---
title: TEF Canada Exam Tips
excerpt_separator: <!--end_excerpt-->
---

## Tips for Expression Ecrite
<!--end_excerpt-->

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {% if myimage.extname contains 'png' %}
    {% assign words = myimage.basename | split:'_' %} 
    {{ words[1] }} 
    
    
   [![youtubethumnails]({{ myimage.path }})](https://www.youtube.com/watch?v={{ words[0] }}) 
  {% endif %}
{% endfor %}


