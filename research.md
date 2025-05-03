---
layout: page
title: ""
permalink: /research/
---

![Research Header Image](/assets/images/Fig4_2025410_TA.png){: style="width: 100%; height: auto;" }


## Research Directions
<!-- Featured
================================================== -->
<section class="row">
  {% for post in site.posts %}
      {% if post.categories contains "Research" and post.featured  == true %}
          <div class="col-md-4 mb-5">
          {% include postbox.html %}
          </div>
      {% endif %}
  {% endfor %}
  </div>
</section>