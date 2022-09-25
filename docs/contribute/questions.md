---
layout: default
title: Add Questions
parent: Contribute
permalink: questions
nav_order: 3
---

# Add Questions

All the questions are stored in ```.yaml``` files within the [`_data` folder](). For more information about ```.yaml``` files, please visit:

- [The official YAML website](https://yaml.org/)
- [YAML Syntax](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html)

### Segregation

Questions are divided into five broad categories: 

- [Machine Learning](https://github.com/dsgiitr/ML-InterviewQs/questions/ml.yml)
- [Deep Learning](https://github.com/dsgiitr/ML-InterviewQs/questions/dl.yml)
- [Probability and Statistics](https://github.com/dsgiitr/ML-InterviewQs/questions/prob.yml)
- [Reinforcement Learning](https://github.com/dsgiitr/ML-InterviewQs/questions/rl.yml)
- [Miscellaneous](https://github.com/dsgiitr/ML-InterviewQs/questions/misc.yml) 

To request the addition of a new category you can [create an issue](/basics#create-a-new-issue).

### YAML list of acceptable values for each key
Each question is stored in a key-value format. There are a fixed set of keys, some of which must neccessarily have ```non-NULL``` values. Here is the list of keys alongwith the list of values they can accept:

| Key | Description | Accepted Values |
| --- |    ----     |      ----       |
| title      | The title of the question (for later review)       |any string                 |
| type      | This specifies the type of question (e.g., MCQs, descriptive, etc.).       |mcq, descriptive, num                 |
| text   | The main body of the question.        |any string                 |
| opt   | The list of options in case the question is a multiple choice question.        |array, NULL                 |
| ans   | The final answer.        |any string                 |
| q_img   | The path of the image file(s) that you may want to display with the question.        |array, NULL                 |
| sol   | Further explanation that you may include for how you arrived at the answer.        |any string, NULL                 |
| sol_img   | The path of the image file(s) that you may want to display with the solution.        |array, NULL                 |
| tags   | You can assign tags to your question based on the domains it requires knowledge of.         |[List of Tags](/tags)                 |
| diff   | The difficulty level of the question|easy, medium, hard                 |
| ref   | References (Where did you encounter the question)        |any string                 |

To request the addition of a new key you can [create an issue](/basics#create-a-new-issue).
