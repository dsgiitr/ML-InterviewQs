---
layout: default
title: Machine Learning
nav_order: 4
permalink: ml
---

# Machine Learning

{% for question in site.data.ml %}

## {{ question.title }}

<!-- {% for tag in question.tags %}
{{ tag }}
{: .label .label-yellow }
{% endfor %} -->

#### Problem
{{ question.text }}

#### Options
{% for opt in question.opt %}
<button type="button" class="btn btn-light active w-100 text-left">{{ opt }}</button> |{% endfor %}

#### Answer
<button type="button" class="btn btn-light active w-100 text-left">{{ question.ans }}</button>

#### Solution
{{ question.sol }}

---

{% endfor %} 
