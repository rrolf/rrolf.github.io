---
title: News
description: Opencast related news
---

{% for post in site.posts limit:5 %}
## [{{ post.title }}]({{ post.url }})
  _{{ post.date | date_to_long_string }}_ 
  {{ post.description }}
  [Read more...]({{ post.url }})
  
---

{% endfor %}
