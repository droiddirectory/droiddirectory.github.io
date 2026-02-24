---
layout: default
---

# Welcome to Droid Directory

This is the central hub for Android Customization, Magisk/APatch Modules, and Tech Guides.

Stay tuned for deep dives into custom ROMs, rooting tutorials, and automation scripts!

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
