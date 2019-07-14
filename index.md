---
layout: default
---

The Privacy Assuring Nondisclosure Agreement (PANDA) is a set of [standard legal terms](/versions/1.0.0) that protect the privacy of your personal data.  Just as companies use NDAs to protect their valuable business information, you can use PANDA to protect your valuable personal information.

{% if site.posts.size > 0 %}
## Posts
{% for post in site.posts %}
- {{ post.date | date: "%B %-d, %Y" }}: [{{post.title}}]({{post.url}})
{% endfor %}
{% endif %}
