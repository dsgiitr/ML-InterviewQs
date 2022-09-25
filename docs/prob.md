---
layout: default
title: Probability and Statistics
nav_order: 2
permalink: probstats
---

# Probability and Statistics

{% for question in site.data.prob %}

## {{ question.title }}

#### Problem
{{ question.text }}

#### Options
{% for opt in question.opt %}
<button type="button" class="btn btn-light active w-100 text-left">{{ opt }}</button>{% endfor %}

#### Answer
<button type="button" class="btn btn-light active w-100 text-left">{{ question.ans }}</button>

#### Solution
{{ question.sol }}

---

{% endfor %} 