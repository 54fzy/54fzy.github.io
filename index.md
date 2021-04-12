---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% include head.html %}

# Intro

## Time is {{ 'now' | date: "%Y %h %a"}} 

## Something about me
## Something about me
## Something about me
## Something about me
## Something about me
## Something about me
## Home
<p name="home"> content about home </p>
## Something about me
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br>
      {{ post.content | strip_html | truncatewords: 50 }}     
    </li>
  {% endfor %}
</ul>

{{ site.theme }}
{{ site.github.contributors[0].login }} 
