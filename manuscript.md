---
title: Manuscript
permalink: /manuscript/
---

# Manuscript

<ul class="doc-index">
  <li><a href="#s01">S01　召喚状</a></li>
  <li><a href="#s02">S02　出立</a></li>
  <li><a href="#s03-1">S03-1　悪の経営</a></li>
  <li><a href="#s03-2">S03-2　拾われた日</a></li>
  <li><a href="#s04-1">S04-1　学園</a></li>
  <li><a href="#s04-2">S04-2　尾行</a></li>
</ul>

<article class="manuscript-body" id="s01">
  {% capture s01 %}{% include_relative manuscript/S01.md %}{% endcapture %}
  {{ s01 | markdownify }}
</article>

<article class="manuscript-body" id="s02">
  {% capture s02 %}{% include_relative manuscript/S02.md %}{% endcapture %}
  {{ s02 | markdownify }}
</article>

<article class="manuscript-body" id="s03-1">
  {% capture s03_1 %}{% include_relative manuscript/S03-1.md %}{% endcapture %}
  {{ s03_1 | markdownify }}
</article>

<article class="manuscript-body" id="s03-2">
  {% capture s03_2 %}{% include_relative manuscript/S03-2.md %}{% endcapture %}
  {{ s03_2 | markdownify }}
</article>

<article class="manuscript-body" id="s04-1">
  {% capture s04_1 %}{% include_relative manuscript/S04-1.md %}{% endcapture %}
  {{ s04_1 | markdownify }}
</article>

<article class="manuscript-body" id="s04-2">
  {% capture s04_2 %}{% include_relative manuscript/S04-2.md %}{% endcapture %}
  {{ s04_2 | markdownify }}
</article>
