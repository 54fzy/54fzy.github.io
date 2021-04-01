---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% include head.html %}

# Intro

## Time is {{ 'now' | date: "%Y %h %a"}} 

## Something about me

<ul>
  {% for post in site.posts %}
    <li>
      <a target="_blank" href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


