---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 20XX.09 – 至今：【学校名称】【学院】【专业】，本科生
  * 主修课程：传播学概论、计算传播学导论、社会研究方法、数据分析与可视化
  * 绩点 / 排名：【想写就写，不想公开可以直接删掉这一行】
* 20XX.09 – 20XX.06：【高中名称】

科研与项目经历
======
* 20XX.XX – 20XX.XX：【项目 / 课程作业名称】
  * 【你做了什么、用了什么方法和工具、得到了什么结论】
  * 指导老师：【老师姓名】
* 20XX.XX – 20XX.XX：【项目名称】
  * 【同上】

实习与社会实践
======
* 20XX.XX – 20XX.XX：【单位名称】，【岗位】
  * 【主要工作内容】

技能
======
* 数据处理：Python（pandas / matplotlib）、R、SPSS
* 文本分析：【如 jieba 分词、SnowNLP 情感分析、LDA 主题模型等，按实际填写】
* 其他工具：Markdown、HTML / CSS 基础、Git / GitHub、Excel
* 语言：普通话（母语）、英语（CET-4 / CET-6 / 雅思 X 分）

荣誉与奖励
======
* 【奖项名称】，【颁发单位】，20XX 年

论文发表
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
学术报告
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
教学
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
