---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[1] Nigmatulin, G, and O Chaganova. 2021. "Research of an Optimization Model for Servicing a
Network of ATMs and Information Payment Terminals." Communications in Computer and
Information Science, Springer, in Press.
<br>
[2] Bolodurina, I, G Nigmatulin, and D Parfenov. 2021. "Intersection of Triangles in Space
Based on Cutting Off Segment." Communications in Computer and Information Science,
Springer, in Press, no. https://arxiv.org/abs/2210.15472.
<br>
[3] Nigmatulin, G. 2020. "Predicting Study Time in an Online Course System Based on Machine
Learning Methods." In Book of Abstracts for the School-Conference "Invitation to Dynamical
Systems, 2020". Higher School of Economics.
<br>
[4] Nigmatulin, G, and I Bolodurina. 2019. "Comparative Analysis of the Methods of Training
Recurrent Neural Network (Rus.).'
Step into Science, no. 2: 50-52.
<br>
[5] Nigmatulin, G, D Parfenov, I Bolodurina, and Zaporozhko. V. 2020. "Solving the Problem of
Categorical Regression Using Neural Networks and Gradient Boosting to Predict the
Academic Performance at MOOCS (Rus.)." In University Complex as a Regional Center of
Education, Science and Culture, 1529-33.
<br>
[6] Parfenov, D, G Nigmatulin, V Zaporozhko, and L Zabrodina. 2020. "Prototype of the Module
for the Intelligent Formation of an Individual Educational Trajectory of a Student for a
Digital Platform (Rus.)."
<br>
[7] Shchepacheva, N, and G Nigmatulin. 2018. "Analysis of the Company's Activities Based on
Chaos Theory (Rus.)." Step into a Science, no. 3: 35-38.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
