---
layout: default
---

The Privacy Assuring Nondisclosure Agreement (PANDA) is a set of [standard legal terms](/versions/1.0.0) that protect the privacy of your personal information.

PANDA gives you the same protections for your personal information that companies demand for their business information:

1.  Use your information [only for specific purposes](/versions/1.0.0#limited-use).

2.  Make sure employees and contractors [also protect your information](/versions/1.0.0#oversight).

3.  Take [reasonable security measures](/versions/1.0.0#security).

4.  [Return your information, and delete copies](/verions/1.0.0#return-and-destruction), when the relationship ends.

5.  Give notice of [leaks](/versions/1.0.0#leaks) and [government requests](/versions/1.0.0#required-disclosure).

{% if site.posts.size > 0 %}
## Posts
{% for post in site.posts %}
- {{ post.date | date: "%B %-d, %Y" }}: [{{post.title}}]({{post.url}})
{% endfor %}
{% endif %}
