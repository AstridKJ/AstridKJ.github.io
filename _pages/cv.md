---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

- **M.A. in Cognitive Science**, Johns Hopkins University, 2025 - 2026
- **M.S. in Neuroscience**, Johns Hopkins University, 2024 - 2025
- **B.S. in Neuroscience and Computer Science, Minor in Visual Arts**, Johns Hopkins University, 2020 - 2024

Research Experience
======

### Visual Integration, Recognition, and Lateralization of Human Social Vision

**Research Assistant**, Isik Lab, Johns Hopkins University  
2025 - 2026


### Electrode Interaction Analysis and Sub-Array Phosphene Mapping in Intracortical Visual Prosthesis

**Research Assistant**, Ultra Low Vision Lab, Wilmer Eye Institute, Johns Hopkins Medicine  
2022 - 2025

Publications
======

{% assign cv_publications = site.publications | where: "category", "publications" | sort: "date" | reverse %}
{% if cv_publications.size > 0 %}
<ul>
{% for post in cv_publications %}
  <li><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
No publications listed yet.
{% endif %}

Presentations
======

{% assign cv_presentations = site.publications | where: "category", "presentations" | sort: "date" | reverse %}
{% if cv_presentations.size > 0 %}
<ul>
{% for post in cv_presentations %}
  <li><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
No presentations listed yet.
{% endif %}

Teaching and Mentoring
======

- **Study Consultant and Advisory Board, Study Consulting Program**, Johns Hopkins University, 2022 - 2025  

- **Teaching Assistant, Linear Algebra and Differential Equations**, Johns Hopkins University, 2022 - 2024  

- **Teaching Assistant, Linear Algebra and Data Science**, Johns Hopkins University, 2023

- **Teaching Assistant, Computer Science and Psychology**,  Center for Talented Youth, 2023 and 2024 Summer  


Service and Leadership
======

- **Publicity Chair, JHU Photography Club**, 2024 - 2025  
  JHU Photography Team member
- **Vice President, JHU Chinese Students and Scholars Association**, 2021 - 2024  
  
- **Publicity Chair, Johns Hopkins Undergraduate Brain Computer Interface Society**, 2021 - 2022  

