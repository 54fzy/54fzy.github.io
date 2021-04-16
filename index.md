---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% include head.html %}

# News

### [Fresh calculation of obscure particle's magnetism could dim hopes for new physics]({% link about.md %})
### [Externel link to Google](https://www.google.com)

# Home
<p name="home"> content about home </p>
# Something about me
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br>
      {{ post.content | strip_html | truncatewords: 50 }}     
    </li>
  {% endfor %}
</ul>

### Lst Modification on {{ "now" | date: "%Y-%m-%d %H:%M:%S %p" }}.

