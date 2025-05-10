---
layout: default
title: Callum Coots - Portfolio
permalink: /projects/
---

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ LeMiniHoop.md | /_projects/1-LeMiniHoop.md }}">
          <img src="{{ LeMiniHoop.md | _projects/1-LeMiniHoop.md }}" alt="{{ LeMiniHoop }}" />
          <p>{{ LeMiniHoop}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
