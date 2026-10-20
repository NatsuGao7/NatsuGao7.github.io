---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<p>
  My research spans three main areas:
  <a href="#llms">Large Language Models (LLMs)</a>,
  <a href="#cv">Computer Vision (CV)</a>, and
  <a href="#ai4science">AI for Science (AI4Science)</a>.
</p>

{% include bib_search.liquid %}

<style>
.research-section {
  margin-top: 35px;
  margin-bottom: 35px;
}

.research-section h2 {
  font-size: 1.55rem;
  font-weight: 600;
  padding-bottom: 10px;
  border-bottom: 1px solid var(--global-divider-color);
  scroll-margin-top: 90px;
}

/* Make Zhuangzhi Gao bold in publications */
.publications .author em,
.publications .author em a {
  font-weight: 700 !important;
  font-style: normal !important;
}
</style>

<div class="publications">

  <section class="research-section">
    <h2 id="llms">Large Language Models (LLMs)</h2>
    {% bibliography --query @*[research_area=LLM] --group_by none %}
  </section>

  <section class="research-section">
    <h2 id="cv">Computer Vision (CV)</h2>
    {% bibliography --query @*[research_area=CV] --group_by none %}
  </section>

  <section class="research-section">
    <h2 id="ai4science">AI for Science (AI4Science)</h2>
    {% bibliography --query @*[research_area=AI4Science] --group_by none %}
  </section>

</div>
