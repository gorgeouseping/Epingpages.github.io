---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my papers on <a href="{{https://scholar.google.com/citations?hl=zh-CN&user=e9lv2fUAAAAJ&view_op=list_works&sortby=pubdate}}">Google Scholar of Yiping Chen.</a>.</div>
{% endif %}

<div style="display:none">
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}-->
</div>


