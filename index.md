---
layout: default
title: index for JekyllPractice
---

# Index

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
