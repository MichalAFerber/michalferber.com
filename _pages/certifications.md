
---
title: Certifications
layout: default
permalink: /certifications/
published: true
---

  {% for certification in site.certifications %}

  {% if certification.redirect %}

          <a href="{{ certification.redirect }}" target="_blank">

              <h2>{{ certification.title }}</h2>

              <p>{{ certification.description }}</p>
          </a>

  {% endif %}

  {% endfor %}
