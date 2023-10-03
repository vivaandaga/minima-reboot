---
layout: post
tags: github
---

Eos eu docendi tractatos sapientem, brute option menandri in vix, quando vivendo accommodare te ius. Nec melius fastidii constituam id, viderer theophrastus ad sit, hinc semper periculis cum id. Noluisse postulant assentior est in, no choro sadipscing repudiandae vix. Vis in euismod delenit dignissim. Ex quod nostrum sit, suas decore animal id ius, nobis solet detracto quo te.

{% raw %} {% if page.tags.size > 0 %} {% for tagName in page.tags %} {% capture tags_content %}{{ tags_content }} <a href='/tags?tagName={{ tagName }}'><i class='glyphicon glyphicon-tag'></i>{{ tagName }}</a> {% endcapture %} {% endfor %} {% else %} {% assign tags_content = '' %} {% endif %} {{ tags_content }} {% endraw %}
