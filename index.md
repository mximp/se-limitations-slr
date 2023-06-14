# SLR - Symbolic Execution Limitations

Please check [how to contribute](https://github.com/mximp/se-limitations-slr).  
Assessment summary can be found [here](/assessment-list.md).

## Current stats

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```

## Updates
{% for post in site.posts %}
  <h3>{{ post.date | date: "%Y, %b %d" }}: <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
  {{ post.excerpt }}
  <hr/>
{% endfor %}
