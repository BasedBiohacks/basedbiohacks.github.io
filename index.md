---
layout: home
---

{%- for post in site.posts -%}
  {% if post.hide == null or post.hide == false %}
    <li>
     <h3>
     <a class="post-link" href="{{ post.url | relative_url }}">
      {{ post.title | escape }}
     </a>
     </h3>          
    </li>
  
  {% endif %}
{%- endfor -%}
