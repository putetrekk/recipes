---
layout: default.liquid
---
## Recipes!

{% for post in collections.posts.pages %}
<img class="slit" src="/img/placeholder.jpg" alt="{{ post.title }} illustrative image" href={{ post.permalink }}><br>
[{{ post.title }}]({{ post.permalink }})
{% endfor %}
