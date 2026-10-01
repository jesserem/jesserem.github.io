---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% comment %}
Grouped rendering when site.publication_category is defined in _config.yml,
otherwise a flat list. Note: every line that emits HTML must start at column 0.
Markdown treats four or more leading spaces as a code block, which would make
kramdown escape the heading and print the raw tags on the page.
{% endcomment %}

{% if site.publication_category %}
{% for category in site.publication_category %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.pubtype != category[0] %}{% continue %}{% endif %}
{% unless title_shown %}
<h2 class="archive__subtitle">{{ category[1].title }}</h2>
{% assign title_shown = true %}
{% endunless %}
{% include archive-single.html %}
{% endfor %}
{% endfor %}
{% else %}
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
{% endif %}
