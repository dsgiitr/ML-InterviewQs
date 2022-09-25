---
layout: default
title: Miscelleneous
nav_order: 6
permalink: misc
---

# Miscelleneous

{% for question in site.data.misc %}

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