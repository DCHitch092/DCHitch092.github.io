---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<main id="flex-posts">
{% for post in site.posts %}
  <a href="{{ post.url }}">
    <div class="post-box"></div>
    <h2>{{ post.title }}</h2>
    <p>{{ post.date | date_to_string }}</p>
  </a>
{% endfor %}
</main>
