---
layout: default
title: Midwest Algebra Conspiracy
---

# hi.
To start colluding, please see [the manual]({{ site.baseurl }}/manual/).

---

## posts.
{% for item in site.texts %}
* [{{ item.title }}]({{ site.baseurl }}{{ item.url }}) by {{ item.author }}{% endfor %}

## examples.
{% for item in site.examples %}
* [{{ item.title }}]({{ site.baseurl }}{{ item.url }}) by {{ item.author }}{% endfor %}
