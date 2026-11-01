---
layout: archive
title: "简历"
permalink: /zh/cv/
author_profile: true
lang: zh
ref: cv
---

{% include base_path %}

教育背景
======
* 2009：鄂木斯克国立师范大学，物理与数学教育学士
* 2010：鄂木斯克国立师范大学，获数学教师专业文凭
* 2019：鄂木斯克国立技术大学，数学建模、数值方法与程序包方向（05.13.18）研究人员-教师
  * 学位论文：网络模体频率统计估计的方法与算法
  * 授予资格：研究人员-教师、科研人员

工作经历
======
* 2010 年夏 — 2011 年冬：信息学与数学教师
  * 第 51 中学，鄂木斯克
* 2011 年冬 — 2013 年夏：网络工程师
  * 市政企业“服务”
* 2013 年夏 — 2014 年秋：讲师
  * 商业、经济与服务学院
* 2014 年夏 — 2016 年夏：助教
  * 鄂木斯克国立技术大学
* 2019 年夏 — 2024 年夏：助教
  * 鄂木斯克国立技术大学

技能
======
* AnyLogic、R（igraph）、MathCAD、Gephi、Pajek
* Java、Pascal

论文
======
  <ul>{% assign cv_publications = site.publications | where: "lang", page.lang %}
    {% for post in cv_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

报告
======
  <ul>{% assign cv_talks = site.talks | where: "lang", page.lang %}
    {% for post in cv_talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

基金与获奖
======
* 以 N. P. Buslenko 命名的青年奖（俄罗斯仿真建模学会），2019
<img src='/images/immod2019.jpg'>
