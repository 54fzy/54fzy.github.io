---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% include head.html %}

# 👷 Research Interests
<a id="RI"></a>

## I. AI
## II. IoT
## III. NLP
## IV. Robotics

<br>
<br>
<br>

# 📢 News
<a id="news"></a>

### * [Fresh calculation of obscure particle's magnetism could dim hopes]({% link about.md %})
### * [Externel link to Google](https://www.google.com)
### * [Test Link]()

<br>


# 🗞 Publications

{% for post in site.posts %}
   <h3 style="color:black; "><strong> {{ post.title }} </strong></h3>  
   {{ post.excerpt }}
{% endfor %}

### You can also find publications on <a>Google Scholar</a>


<br>
<br>
<br>

