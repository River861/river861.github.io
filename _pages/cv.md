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
* Ph.D in Computer Science, Fudan University, 2021 - now
  * Mentor: [Prof. Yangfan Zhou](https://cs.fudan.edu.cn/3f/a9/c25909a278441/page.htm) and [Prof. Xin Wang](https://cs.fudan.edu.cn/3f/7e/c25906a278398/page.htm)
* B.Sc. in Computer Science, Fudan University, 2017 - 2021

Work experience
======
* Research Intern at Huawei Cloud (in Shenzhen), Sept. 2022 - Aug. 2023
  * Research Topics: Storage Systems on Disaggregated Memory
  * Mentor: [Dr. Pengfei Zuo](https://pfzuo.github.io/)
  * Partner: [Dr. Jiacheng Shen](https://bernardshen.github.io/)
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <!-- <ul>
  {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul> -->
<ul>
  {% assign reversed_publications = site.publications | reverse %}
  {% for post in reversed_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>


Awards and Honors
======
* Best Spotlight Paper Award in ChinaSys, 2024 [[link](https://mp.weixin.qq.com/s/kdix73_Rek42dAL_9TnJuA)]
* National Natural Science Foundation of China (NSFC) for Ph.D. Graduate Students, 2024 [[link](https://mp.weixin.qq.com/s/mF7hdDoAGUkvgnFvx0hAOA)]
* National Scholarship for Ph.D. Graduate Students, 2023
* Rising Innovation Star Award at Huawei Cloud, 2023 [[link](https://www.huaweicloud.com/lab/storage/news_innovative_star_2023.html)]
* Student Grant from OSDI, 2023
* Huawei Scholarship at Fudan University, 2022
* Outstanding Graduate of Fudan University, 2021

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
Teaching
======
* TA, COMP130110.01 Operating Systems, Fudan University, Sept. 2021 - Dec. 2021
* TA, COMP130159.01 Software Security, Fudan University, Jan. 2022 - Apr. 2022

<!--   <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
