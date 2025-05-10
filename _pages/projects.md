---
layout: default
title: Callum Coots - Portfolio
permalink: /projects/
---

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ LeMiniHoop.md | relative_url }}">
          <img src="{{ LeMiniHoop.md | relative_url }}" alt="{{ LeMiniHoop }}" />
          <p>{{ LeMiniHoop}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
