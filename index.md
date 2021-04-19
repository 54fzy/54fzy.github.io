---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% include head.html %}

# 📢 News
<a id="news"></a>

### * [Fresh calculation of obscure particle's magnetism could dim hopes]({% link about.md %})
### * [Externel link to Google](https://www.google.com)
### * [Test Link]()

<br>
<br>
<br>

# 👷 Research Interests
<a id="RI"></a>
## AI
## IoT
## NLP
## Robotics

<br>
<br>
<br>

# 🗞 Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br>
      {{ post.content | strip_html | truncatewords: 50 }}     
    </li>
  {% endfor %}
</ul>

<br>
<br>
<br>

### Lst Modification in {{ "now" | date: "%Y" }}.
