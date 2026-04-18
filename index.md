---
layout: default
title: index
---

## Welcome!

Hello :)

The opposite of Jekyll is Hyde. lol.

---

### posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
