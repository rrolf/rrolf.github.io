**Opencast is a flexible and customizable video capture and distribution system for modern institutions. Opencast is built by a growing community of developers in collaboration with leading universities and organizations worldwide.**

# Introduction video
{% include videoplayer.html id="57a2b005-fe70-4566-a234-aa864faf1e29" %}

---

# News

{% for post in site.posts %}
{% if post.categories contains "release" %}
## [{{ post.title }}]({{ post.url }})
  _{{ post.date | date_to_long_string }}_ 
  {{ post.excerpt }}
  [Read more...]({{ post.url }})
  
---

{% endif %}    
{% endfor %}

# Features

<img class="feature-image-left" src="/assets/img/schedule.png">
## Schedule
Schedule events to automatically record based on a pre-defined timetable and, capture both video of the presenter and the  PC screen.

<img class="feature-image-right" src="/assets/img/edit.png">
## Edit
Bulk edit and trim video recordings. The editor provides graphical visualization of elements such as audio can significantly reduce editing time.

<img class="feature-image-left" src="/assets/img/events.png">
## Process
A scalable infrastructure to encode video, generate metadata and preview images, create captioning and bulk edit to support video processing at scale.

<img class="feature-image-right" src="/assets/img/distribute.png">  
## Distribute
Publish recordings for download or on-demand viewing via YouTube, RSS, Atom-feeds or with OAI-PMH.

<img class="feature-image-left" src="/assets/img/playback.png">
## Playback
The media player is a standalone application or embedded on blogs, wikis or a content management system.

<img class="feature-image-right" src="/assets/img/manage.png">
## Manage
A robust dashboard to manage, configure and track the status and performance of video content and distribution channels.

---

# Trusted by a Collection of Innovative Organizations
<img class="center-image" src="/assets/img/opencast-homepage-logos-rev2.png">

