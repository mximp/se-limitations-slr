# SLR - Symbolic Execution Limitations

Please check [how to contribute](https://github.com/mximp/se-limitations-slr)

{% for post in site.posts %}
  <h3>{{ post.date | date: "%Y, %b %d" }}: <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
  {{ post.excerpt }}
  <hr/>
{% endfor %}
