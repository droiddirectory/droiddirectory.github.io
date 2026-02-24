---
layout: default
---

# Android Development & Customization
Welcome to the official **Droid Directory**. Here you will find deep dives into Android internals, custom ROMs, and advanced rooting guides.

---

## Latest Technical Guides

<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
      <br><small>Published on {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

---

### About the Project
Droid Directory is a resource for power users and developers working with modern Android environments like LineageOS and APatch.
