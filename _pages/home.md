---
layout: default
title: Home
order: 0
permalink: /home/
---

{% assign categoryA_posts = site.posts | where: "categories", "A-general" %}
{% assign categoryB_posts = site.posts | where: "categories", "B-method" %}
{% assign categoryC_posts = site.posts | where: "categories", "C-artifacts" %}
{% assign categoryD_posts = site.posts | where: "categories", "D-agile" %}
{% assign categoryE_posts = site.posts | where: "categories", "E-tools" %}
{% assign categoryF_posts = site.posts | where: "categories", "F-versions" %}
{% assign categoryG_posts = site.posts | where: "categories", "G-traceability" %}
{% assign categoryH_posts = site.posts | where: "categories", "H-management" %}
{% assign categoryI_posts = site.posts | where: "categories", "I-customizing" %}


On this site you find [(currently {{ site.posts | size }}) practical tips](/keywords)
regarding [req42](https://req42.de/en), organized in the following categories:

* [Tips on **req42 Sections**](/category_a/) ({{ categoryA_posts | size }})
* [Tips on **Documentation**](/category_b/) ({{ categoryB_posts | size }})
* [Tips on **req42 & Agility**](/category_c/) ({{ categoryC_posts | size }})
* [Tips on **Clean Start**](/category_d) ({{ categoryD_posts | size }})
* [Tips on **req42 & Tools**](/category_e/) ({{ categoryE_posts | size }})
* [**Frequently Asked Questions**](/category_f) ({{ categoryF_posts | size }})


<hr class="content-sep">

## If you have additional questions

Just in case **you** have any unanswered questions regarding req42 and its usage in practical situations... <br>
Please let us [**know here**](/contact/).
