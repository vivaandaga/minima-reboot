---
layout: post
tags:
- github
---

Eos eu docendi tractatos sapientem, brute option menandri in vix, quando vivendo accommodare te ius. Nec melius fastidii constituam id, viderer theophrastus ad sit, hinc semper periculis cum id. Noluisse postulant assentior est in, no choro sadipscing repudiandae vix. Vis in euismod delenit dignissim. Ex quod nostrum sit, suas decore animal id ius, nobis solet detracto quo te.

{% for tag in post.tags %}
  {% assign tag_slug = tag | slugify: "raw" %}
  <a class="tag-link"
    href={{ site.baseurl | append: "/tags/" | append: tag_slug | append: "/" }}
    rel="category tag">
    #{{ tag }}
  </a>
{% endfor %}
