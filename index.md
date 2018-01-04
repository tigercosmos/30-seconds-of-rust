extends: default.liquid
---
{% for post in posts %}
#### {{post.title}}

#### [{{ post.title }}]({{ post.path }})
{% endfor %}
