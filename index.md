---
layout: page
---

# A Fresh Start for South Jersey

We need new thinking in Congress to tackle the challenges — at home and across the country — on our way to building a bright future for South Jersey.

Learn more about our policy platform in the sections below. If you have suggestions about any of these issues, you can leave a comment or suggest changes to the content.

{% for post in site.posts reversed %}
  - [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endfor %}
