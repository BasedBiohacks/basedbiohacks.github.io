---
layout: home
---

{%- for post in site.posts -%}
  <li>
     <h3>
     <a class="post-link" href="{{ post.url }}">
      {{ post.title }}
     </a>
     </h3>          
  </li>
{%- endfor -%}
