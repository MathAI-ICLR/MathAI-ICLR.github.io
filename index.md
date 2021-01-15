---
layout: page
title: MATH-AI
subtitle: The Role of Mathematical Reasoning in General Artificial Intelligence
use-site-title: true
---
<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" />

# Overview

The machine learning community in the past decade has greatly advanced methods for recognizing perceptual patterns (e.g., image recognition, object detection), thanks to advancements in neural network research. However, one defining property of advanced intelligence – reasoning – requires a much deeper understanding of the data beyond the perceptual level; it requires extraction of higher-level symbolic patterns or rules. Unfortunately, deep neural networks have not yet demonstrated the ability to succeed in reasoning.

In this workshop, we focus on a particular kind of reasoning ability, namely, mathematical reasoning. Advanced mathematical reasoning is unique in human intelligence, and it is also a fundamental building block for many intellectual pursuits and scientific developments. We believe that addressing this problem has the potential to shed light on a path towards general reasoning mechanisms, and hence general artificial intelligence. Therefore, we would like to bring together a group of experts from various backgrounds to discuss the role of mathematical reasoning ability towards the path of demonstrating general artificial intelligence. In addition, we hope to identify missing elements and major bottlenecks towards demonstrating mathematical reasoning ability in AI systems. 

To fully address these questions, we believe that it is crucial to hear from experts in various fields: machine learning/AI leaders who assess the possibility of the approach; cognitive scientists who study human reasoning for mathematical problems; formal reasoning specialists who work on automated theorem proving; mathematicians who work on informal math theorem proving. We hope that the outcome of the workshop will lead us in meaningful directions towards a generic approach to mathematical reasoning, and shed light on general reasoning mechanisms for artificial intelligence.

<!-- | ------------- |:-------------:|
| **Submission** | October 09, 2020 (midnight Pacific Time) |
| **Notification** | October 30, 2020 |
| **Submission link**| [https://cmt3.research.microsoft.com/KR2ML2020](https://cmt3.research.microsoft.com/KR2ML2020) -->

<!--* Thank you Amazon for sponsoring a best paper award!
* The 3 best papers will be presented in talks at the workshop! 
* <a href="schedule">The schedule is online now!</a> 
* <a href="papers">List of accepted papers available!</a> -->
<!--* **NEW** Updates to existing submissions possible until October 12 (11:59pm Pacific Time) <br>New submissions close on October 09 (11:59pm Pacific Time)-->


<hr>

# Speakers & Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
  {% for p in site.data.speakers %}
  {% if forloop.index<=5 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>3 and forloop.index<=6%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>6%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
<a href="speakers">More Info</a>
</div>

<hr>

# Organizers

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <div class="row">
  {% for p in site.data.organizers %}
  {% if forloop.index<=3 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>3 and forloop.index<=6%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

<!--# Program Committee
<!-- prettier-ignore 
<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr>-->

# Related Venues

<div class="container" style="margin-bottom: 10px;"></div>

- [Conference on Artificial Intelligence and Theorem Proving (AITP)](http://aitp-conference.org)
- [Conference on Intelligent Computer Mathematics (CICM)](https://cicm-conference.org/cicm.php)
- [Workshop on Big proof](https://www.newton.ac.uk/event/bpr)
- [Workshop on Neural-Symbolic Learning and Reasoning (NeSys'19)](https://sites.google.com/view/nesy2019/home), see more on <http://www.neural-symbolic.org/>
- [Workshop on Knowledge Representation & Reasoning Meets Machine Learning (KR2ML'20)](https://kr2ml.github.io/2020/)

<div class="container" style="margin-bottom: 10px;"></div>

<hr>

Contact: <mathai.iclr2021@gmail.com>.
