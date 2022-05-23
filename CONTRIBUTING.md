# Contribution Guide
Welcome to DSG's Machine Learning Interview Questions contribution guide. We thank you for investing your time in contributing to our project! 

In this guide you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR.

## New contributer guide
To get an overview of the project, read the README. Here are some resources to help you get started with open source contributions:

- [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
- [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow)
- [Collaborating with pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests)

## Getting Started
We store all of the questions in ```.yaml``` files. For more information about ```.yaml``` files, you can go through these resources:

- [The official YAML website](https://yaml.org/)
- [YAML Syntax](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html)

### Issues

#### Create a new Issue
If you spot a problem in this repository, or need to request a new tag, or a new key, [search if an issue already exists](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments). If a related issue doesn't exist, you can open a new issue using a relevant [issue form](https://github.com/dsgiitr/ML-InterviewQs/issues/new/choose).

#### Solve an Issue

Scan through our [existing issues](https://github.com/dsgiitr/ML-InterviewQs/issues) to find one that interests you. You can narrow down the search using ```labels``` as filters. See [Labels](https://github.com/github/docs/blob/main/contributing/how-to-use-labels.md) for more information. As a general rule, we don’t assign issues to anyone. If you find an issue to work on, you are welcome to open a PR with a fix.

### Add questions

#### Segregation

We have divided all the questions into five broad categories: 

- [Machine Learning](https://github.com/dsgiitr/ML-InterviewQs/questions/ml.yml)
- [Deep Learning](https://github.com/dsgiitr/ML-InterviewQs/questions/dl.yml)
- [Probability and Statistics](https://github.com/dsgiitr/ML-InterviewQs/questions/prob.yml)
- [Reinforcement Learning](https://github.com/dsgiitr/ML-InterviewQs/questions/rl.yml)
- [Miscellaneous](https://github.com/dsgiitr/ML-InterviewQs/questions/misc.yml) 

To request the addition of a new category you can [create an issue](#Create-a-new-Issue).

#### YAML list of acceptable values for each key
Each question is stored in a key-value format. There are a fixed set of keys, some of which must neccessarily have ```non-NULL``` values. Here is the list of keys alongwith the list of values they can accept:
| Key         | Description | Accepted Values |
| :---        |    :----:   |      :----:     |
| type      | This specifies the type of question (e.g., MCQs, descriptive, etc.).       |mcq, descriptive, num                 |
| text   | The main body of the question.        |any string                 |
| opt   | The list of options in case the question is a multiple choice question.        |array, NULL                 |
| ans   | The final answer.        |any string                 |
| q_img   | The path of the image file(s) that you may want to display with the question.        |array, NULL                 |
| sol   | Further explanation that you may include for how you arrived at the answer.        |any string, NULL                 |
| sol_img   | The path of the image file(s) that you may want to display with the solution.        |array, NULL                 |
| tags   | You can assign tags to your question based on the domains it requires knowledge of.         |[List of Tags](https://github.com/dsgiitr/ML-InterviewQs/blob/main/docs/tags.md/#List-of-Tags)                 |
| diff   | The difficulty level of the question|easy, medium, hard                 |
| ref   | References (Where did you encounter the question)        |any string                 |

To request the addition of a new key you can [create an issue](#Create-a-new-Issue).

#### Style guide
We follow standard effective yaml guidelines. You can refer to [this guide](https://developers.home-assistant.io/docs/documenting/yaml-style-guide/) for more information.

### Pull Request
When you're finished with the changes, [create a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request), also known as a PR. To know more about pull requests, see [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

Keep these in mind while creating a pull request:

- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge. Once you submit your PR, a Docs team member will review your proposal. We may ask questions or request for additional information.
- We may ask for changes to be made before a PR can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues, checkout this [git tutorial](https://lab.github.com/githubtraining/managing-merge-conflicts) to help you resolve merge conflicts and other issues.

### Your PR is merged!
Congratulations :tada::tada: Team DSG thanks you :sparkles:
