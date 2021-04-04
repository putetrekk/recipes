---
layout: default.liquid
---
## Recipes!

{% for post in collections.posts.pages %}
<div class="recipe-listing">
<a href={{ post.permalink }}>
<img class="slit" src="{{ post.data.image }}" alt="{{ post.title }} illustrative image" />
{{ post.title }}
</a>
</div>
{% endfor %}
