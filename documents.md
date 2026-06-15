---
title: Documents
permalink: /documents/
---

# Documents

<p class="lead">既存のMarkdown/YAMLファイルをそのまま読み込んで表示しています。</p>

<ul class="doc-index">
  <li><a href="#project-spec">Project Spec</a></li>
  <li><a href="#concept-spec">Concept Spec</a></li>
  <li><a href="#reader-experience-spec">Reader Experience Spec</a></li>
  <li><a href="#ending-spec">Ending Spec</a></li>
  <li><a href="#plot-spec">Plot Spec</a></li>
  <li><a href="#characters-spec">Characters Spec</a></li>
  <li><a href="#scene-specs">Scene Specs</a></li>
  <li><a href="#decision-log">Decision Log</a></li>
  <li><a href="#plot-outline">Plot Outline</a></li>
  <li><a href="#acts-yaml">Acts YAML</a></li>
  <li><a href="#characters-yaml">Characters YAML</a></li>
</ul>

<section class="doc-section" id="project-spec">
  <h2>Project Spec</h2>
  <p class="doc-source">Source: <code>specs/00_project.md</code></p>
  {% capture project_spec %}{% include_relative specs/00_project.md %}{% endcapture %}
  {{ project_spec | markdownify }}
</section>

<section class="doc-section" id="concept-spec">
  <h2>Concept Spec</h2>
  <p class="doc-source">Source: <code>specs/01_concept.md</code></p>
  {% capture concept_spec %}{% include_relative specs/01_concept.md %}{% endcapture %}
  {{ concept_spec | markdownify }}
</section>

<section class="doc-section" id="reader-experience-spec">
  <h2>Reader Experience Spec</h2>
  <p class="doc-source">Source: <code>specs/02_reader_experience.md</code></p>
  {% capture reader_experience_spec %}{% include_relative specs/02_reader_experience.md %}{% endcapture %}
  {{ reader_experience_spec | markdownify }}
</section>

<section class="doc-section" id="ending-spec">
  <h2>Ending Spec</h2>
  <p class="doc-source">Source: <code>specs/04_ending.md</code></p>
  {% capture ending_spec %}{% include_relative specs/04_ending.md %}{% endcapture %}
  {{ ending_spec | markdownify }}
</section>

<section class="doc-section" id="plot-spec">
  <h2>Plot Spec</h2>
  <p class="doc-source">Source: <code>specs/05_plot.md</code></p>
  {% capture plot_spec %}{% include_relative specs/05_plot.md %}{% endcapture %}
  {{ plot_spec | markdownify }}
</section>

<section class="doc-section" id="characters-spec">
  <h2>Characters Spec</h2>
  <p class="doc-source">Source: <code>specs/06_characters.md</code></p>
  {% capture characters_spec %}{% include_relative specs/06_characters.md %}{% endcapture %}
  {{ characters_spec | markdownify }}
</section>

<section class="doc-section" id="scene-specs">
  <h2>Scene Specs</h2>
  <p class="doc-source">Source: <code>specs/09_scene_specs.md</code></p>
  {% capture scene_specs %}{% include_relative specs/09_scene_specs.md %}{% endcapture %}
  {{ scene_specs | markdownify }}
</section>

<section class="doc-section" id="decision-log">
  <h2>Decision Log</h2>
  <p class="doc-source">Source: <code>specs/decision_log.md</code></p>
  {% capture decision_log %}{% include_relative specs/decision_log.md %}{% endcapture %}
  {{ decision_log | markdownify }}
</section>

<section class="doc-section" id="plot-outline">
  <h2>Plot Outline</h2>
  <p class="doc-source">Source: <code>plot/outline.md</code></p>
  {% capture plot_outline %}{% include_relative plot/outline.md %}{% endcapture %}
  {{ plot_outline | markdownify }}
</section>

<section class="doc-section" id="acts-yaml">
  <h2>Acts YAML</h2>
  <p class="doc-source">Source: <code>plot/acts.yaml</code></p>
  {% capture acts_yaml %}{% include_relative plot/acts.yaml %}{% endcapture %}
  <pre><code>{{ acts_yaml | escape }}</code></pre>
</section>

<section class="doc-section" id="characters-yaml">
  <h2>Characters YAML</h2>
  <p class="doc-source">Source: <code>bible/characters.yaml</code></p>
  {% capture characters_yaml %}{% include_relative bible/characters.yaml %}{% endcapture %}
  <pre><code>{{ characters_yaml | escape }}</code></pre>
</section>
