---
layout: default.liquid
---
## Recipes!

{% for post in collections.posts.pages %}
[{{ post.title }}]({{ post.permalink }})
{% endfor %}
