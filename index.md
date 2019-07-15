---
layout: default
permalink: /
---

The <u>P</u>rivacy <u>A</u>ssuring <u>N</u>on<u>d</u>isclosure <u>A</u>greement (PANDA) is a set of [standard legal terms](/versions/1.0.0) that protect the privacy of your personal information.

PANDA gives you the same protections for your personal information that companies [routinely demand for their business information](https://en.wikipedia.org/wiki/Non-disclosure_agreement):

- Use your information [only for specific purposes](/versions/1.0.0#limited-use).

- Make sure employees and contractors [also protect your information](/versions/1.0.0#oversight).

- Take [reasonable security measures](/versions/1.0.0#security).

- [Return your information, and delete copies](/verions/1.0.0#return-and-destruction), when the relationship ends.

- Give notice of [leaks](/versions/1.0.0#leaks) and [government requests](/versions/1.0.0#required-disclosure).

Service providers can read [more about how to use PANDA](/how).

Everyone is welcome to [contribute to PANDA terms](/contribute).

{% if site.posts.size > 0 %}
## Posts
{% for post in site.posts %}
- {{ post.date | date: "%B %-d, %Y" }}: [{{post.title}}]({{post.url}})
{% endfor %}
{% endif %}
