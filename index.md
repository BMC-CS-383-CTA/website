---
title: Computational Text Analysis - CS383 Spring '23 - Bryn Mawr College
layout: default
img: <!-- turk-engraving-detail -->
img_link: <!-- http://en.wikipedia.org/wiki/The_Turk -->
caption: <!--An engraving of the Mechanical Turk, the 18th century chess-playing automaton -->
active_tab: main_page 
---
This course covers foundational concepts in computational text analysis.
The course is designed for Computer Science students interested in using text analysis methods to discover and measure concepts and phenomena in large amounts of text. Topics include core computational text analysis concepts, text-based machine learning,
deep learning, basic statistical methods, and data collection.
The course will culminate around research projects where groups of students will formulate and iteratively refine an empirical question; collect relevant textual data; implement appropriate methods of analysis; and interpret and present their results.

<!-- Display an alert about upcoming homework assignments -->
{% capture now %}{{'now' | date: '%s'}}{% endcapture %}
{% for page in site.pages %}
{% if page.release_date and page.due_date %}
{% capture release_date %}{{page.release_date | date: '%s'}}{% endcapture %}
{% capture due_date %}{{page.due_date | date: '%s'}}{% endcapture %}
{% if release_date < now and due_date >= now %}
<div class="alert alert-info">
<a href="{{page.url}}">{{ page.title }}</a> has been released.  
{% if page.deliverables %}
The assignment has multiple deliverables.
{% for deliverable in page.deliverables %}
The {{deliverable.description}} is due before {{ deliverable.due_date | date: "%I:%M%p" }} on {{ deliverable.due_date | date: "%A, %B %-d, %Y" }}.  
{% endfor %}
{% else %}
It is due before {{ page.due_date | date: "%I:%M%p" }} on {{ page.due_date | date: "%A, %B %-d, %Y" }}.
{% endif %}
</div>
{% endif %}
{% endif %}
{% endfor %}
<!-- End alert for upcoming homework assignments -->


<!--
<div class="alert alert-info" markdown="1">
Check out the [excellent final projects](http://crowdsourcing-class.org/final-projects-2016.html) from last year's class.
</div>
-->


Course number
: CMSC B383 - students from all majors are welcome!

Instructor
: [Adam Poliak](http://azpoliak.github.io)

Website 
: [https://cs.brynmawr.edu/cs383-cta/](https://cs.brynmawr.edu/cs383-cta)

Discussion Forum
: [Piazza](https://piazza.com/brynmawr/spring2023/cs383)

Time and place
: Spring 2023, MW 10:10-11:30am, Location: Park 338
: Lab M: 11:40am-1:00pm

Office Hours
: <a href="office-hours.html">Times</a>

Prerequisites
: CMSC 151 Data Structures (or equivalent)
: CMSC 231 Discrete Math (or equivalent)

Course Readings
: Each lecture has an accompanying reading that will be posted to the schedule. Some lectures will have accompanying optional reading related to the lecture's topic.
: Many of the accompanying readings will be from the following freely available textbooks:
1. Jurafsky and Martin, Speech and Language Processing (3rd ed. draft) [(online copy)](https://web.stanford.edu/~jurafsky/slp3/)
1. [Text Analysis in Python for Social Scientists](https://www.cambridge.org/core/elements/text-analysis-in-python-for-social-scientists/BFAB0A3604C7E29F6198EA2F7941DFF3). [Digital copies](1019151557604921&context=L&vid=01TRI_INST:BMC&lang=en&search_scope=BMC_Catalog&adaptor=Local%20Search%20Engine&tab=LibraryCatalog&query=any,contains,text%20analysis%20in%20python%20for%20social%20scientists&offset=0) are available to download with your BMC/HC login from the Tripod (TriCollege Libraries).

Grading
* Homeworks: 30%
* Weekly Reading Reviews: 10%
* Midterm: 20%
* Project: 35% 
* Participation: 5%

Late day policy
: To account for issues that arise in these uncertain times, each student has 10 late days for the homeworks and projects.
<br>
See the [Policies](policies.html#late-days) for more details.

<!--#### Acknowledgments-->
