---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---
{% for post in site.posts %}
<article>
  <h4>
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </h4>
</article>
{% endfor %}
