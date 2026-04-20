---
layout: default
title: index
---

## Welcome!

Hello :)

The opposite of Jekyll is Hyde. lol.

- [about](./about)
- [readme](./readme)
- [top page](../index.htm)

---

### posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
