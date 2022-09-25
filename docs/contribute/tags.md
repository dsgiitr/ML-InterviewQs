---
layout: default
title:
parent: Contribute
permalink: tags
nav_order: 4
---

# Question Tags

### What are Tags?
Each question can be assigned various tags based on the domains it requires knowledge of.

For example, consider the question:

```
Q. Using which layer can you make your CNN invariant to the size of the input?

A. Global Average Pooling. Similar to max pooling layers, GAP layers are used to reduce the spatial dimensions of a
three-dimensional tensor. However, GAP layers perform a more extreme type of dimensionality reduction, where a tensor
with dimensions h×w×d is reduced in size to have dimensions 1×1×d. GAP layers reduce each h×w feature map to a single
number by simply taking the average of all hw values, making the network invariant to the size of the input.
```

This question may be tagged with the tags ```cnn```, ```pooling```.

### Why use Tags?
Assigning tags to each question allows for better and finer segregation of questions, and is an important aspect of the application we're building.

### List of Tags
Currently, there is a standard list of tags to be used, in order to avoid duplicate tags:

| gradient-descent | regression | softmax | regularization |
| multicollinearity | svm | trees | ensemble-learning |
| validation | nlp | cv | eda |
| clustering | unsupervised | supervised | bayes-theorem |
| naive-bayes | hypothesis-testing | statistics | knn |
| dimensionality-reduction | metrics | cnn | pooling |
| ann | rnn | backprop | random-forest |
| boosting | | | |

To request the addition of a new tag, [create an issue](/basics#create-a-new-issue).
