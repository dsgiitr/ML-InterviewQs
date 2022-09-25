---
layout: default
title: Deep Learning
nav_order: 3
permalink: dl
---

# Deep Learning

{% for question in site.data.dl %}

## {{ question.title }}

#### Problem
{{ question.text }}

#### Options
{% for opt in question.opt %}
<button type="button" class="btn btn-light active w-100 text-left">{{ opt }}</button> |{% endfor %}

#### Answer
<button type="button" class="btn btn-light active w-100 text-left"> {{ question.ans }} </button>

#### Solution
{{ question.sol }}

---

{% endfor %}