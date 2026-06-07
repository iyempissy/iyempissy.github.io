---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
- PhD in Computer Science, Leibniz University Hannover, 2024
- MPhil in Systems Engineering and Engineering Management, Chinese University of Hong Kong, 2020
- MSc in Advanced Information Systems, Hong Kong Baptist University, 2015

Professional Experience
======
- March 2024-present: Postdoctoral Researcher, CISPA, Germany
- March 2020-February 2024: Research Scientist, L3S Research Center, Germany
- May 2016-July 2017: Research Associate, Hong Kong Baptist University, Hong Kong
- November 2015-May 2016: Research Associate, Hong Kong Polytechnic University, Hong Kong
- December 2013-August 2014: Branch Operations Manager, Lorion-Eyiyemi Ventures Limited, Nigeria
- November 2012-October 2013: Volunteer Computer Instructor, National Youth Service Corps, Nigeria

Research Interests
======
- Privacy and security for machine learning
- Large language models
- Graph neural networks
- Explainability and trustworthy AI
- Health informatics

Technical Skills
======
- Python
- PyTorch and PyTorch Geometric
- Data science
- SQL
- PHP
- HTML, CSS, JavaScript, and jQuery

Selected Awards
======
- Best Student Paper, IEEE Trust, Privacy and Security in Intelligent Systems and Applications, 2021
- Postgraduate Studentship Scholarship, Chinese University of Hong Kong, 2017-2019
- High Distinction Scholarship, Hong Kong Baptist University, 2015
- Distinction Scholarship, Hong Kong Baptist University, 2014
- Corps Liaison Officer National Award, Nigeria, 2013

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
