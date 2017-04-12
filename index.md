# home page

{% for post in site.posts %}
1. [{{ post.title }}]({{ site.url }}{{ post.url }})
{% endfor %}

