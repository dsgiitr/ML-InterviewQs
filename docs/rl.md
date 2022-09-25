---
layout: default
title: Reinforcement Learning
nav_order: 5
permalink: rl
---

# Reinforcement Learning

{% for question in site.data.rl %}

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