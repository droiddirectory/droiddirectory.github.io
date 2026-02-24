---
layout: default
---

<style>
  /* This targets the specific title prefix in the Hacker theme */
  header h1::before {
    content: "" !important;
    display: none !important;
  }
  /* This ensures the title we manually set in the layout is clean */
  #a-title h1::before {
    content: "" !important;
  }
</style>

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
