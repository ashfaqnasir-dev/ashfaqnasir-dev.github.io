---
layout: page
title: Microsoft Certifications
permalink: /certifications/
---

## Active Certifications
<div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 20px;">

{% for cert in site.certifications %}
<div style="border: 1px solid #ddd; padding: 15px; border-radius: 8px; text-align: center;">
  <img src="{{ cert.badge }}" alt="{{ cert.name }}" width="100" style="margin-bottom: 10px;">
  <h4>{{ cert.name }}</h4>
  <p><strong>{{ cert.code }}</strong></p>
  <p>Earned: {{ cert.date }}</p>
</div>
{% endfor %}

</div>

**Total:** 8 Active Certs | 15 Historical | 23 Exams Passed  
**Verify:** [Microsoft Learn Profile]()
