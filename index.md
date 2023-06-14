# SLR - Symbolic Execution Limitations

Please check [how to contribute](https://github.com/mximp/se-limitations-slr).  
Assessment details can be found [here](/assessment-list.md).

```mermaid
pie showdata title Assessment in progress
    "Round I completed" : 7
    "Round I in progress " : 8
    "Round II completed" : 0
    "Round II in progress" : 6
    "Pending assignment" : 535
```

## Updates
{% for post in site.posts %}
  <h3>{{ post.date | date: "%Y, %b %d" }}: <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
  {{ post.excerpt }}
  <hr/>
{% endfor %}
