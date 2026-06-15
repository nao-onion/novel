---
title: Manuscript
permalink: /manuscript/
---

# Manuscript

<ul class="doc-index">
  <li><a href="#s01">S01　召喚状</a></li>
  <li><a href="#s02">S02　出立</a></li>
</ul>

<article class="manuscript-body" id="s01">
  {% capture s01 %}{% include_relative manuscript/S01.md %}{% endcapture %}
  {{ s01 | markdownify }}
</article>

<article class="manuscript-body" id="s02">
  {% capture s02 %}{% include_relative manuscript/S02.md %}{% endcapture %}
  {{ s02 | markdownify }}
</article>
