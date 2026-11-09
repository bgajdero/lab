---
project_area: "AI & Computational Modeling"
layout: post
title:  "Community Justice Advocate"
date:   2026-10-01 09:41:09
author: Bart Gajderowicz
header:
  overlay_color: "#600"
#   image: "/assets/img/bartg.jpeg"
#   teaser: /assets/img/bartg.jpeg
tag-name: ontology cids impact-model
---
<!-- ![image tooltip here](/assets/img/bartg.jpeg) -->
The Community Justice Advocate (CJA) initiative addresses an important question: **when we help someone navigate debt-related legal problems, how do we know whether their circumstances actually improve?** As the AI lead, my focus is on developing a formal, computational representation of the CJA system that connects organizations, services, practitioner activities, client needs, and measurable outcomes. Using semantic technologies and the Common Impact Data Standard (CIDS), we are building an ontology that captures how CJA interventions contribute to outcomes such as reduced debt, improved legal knowledge, avoided default judgments, and increased financial stability. Rather than simply counting the number of clients served or cases resolved, we want to understand the relationships between interventions and their outcomes, and establish a consistent framework for evaluating their impact across clients, practitioners, and organizations.

From a technical perspective, this involves developing a semantic knowledge model that represents service pathways, stakeholder characteristics, legal cases, and outcome indicators in a structured and interoperable way. We are defining eight formal indicators spanning financial, legal, housing, healthcare, and stress-related outcomes, with measurements that capture changes in client circumstances over time. Our approach also considers the **scale, depth, and duration of impact**, allowing us to move beyond individual service metrics toward a more comprehensive understanding of program effectiveness. This work provides a foundation for the broader CJA program, where knowledge graphs, AI-assisted information retrieval, and governed data integration can support service navigation, referrals, and outcome reporting. Ultimately, our objective is to create an evidence-based decision-support infrastructure that helps CJAs deliver more effective services while enabling researchers, courts, and funders to better understand which interventions work, for whom, and to what extent.


<p>Researchers and practitioners listed below are participants in the <a href="/cja-project/">Community Justice Advocates</a> (CJA) project. Their affiliations refer to the project rather than formal positions in the lab.</p>
<ul>
{% for person in site.data.team.cja_collaborators %}
  <li><strong>{{ person.name }}</strong> — {{ person.affiliation }}</li>
{% endfor %}
</ul>

<p>Students</p>


<h2>Latest Work</h2>

ConvergeAI 2026, Poster Session: [Using Ontologies to Turn a Social Work Impact Model Into Connected, Comparable Data](https://usu.box.com/v/cja-poster-convergeai-2026)
