---
layout: default
title: DSC 180A Methodology Assignment 4
---

# DSC 180A Methodology Assignment 4

**Name:** Yidong Shi

**UCSD Email:** yis089@ucsd.edu

**Section:** D21

**Mentor:** Armin Schwartzman

## Quarter 2 Project Reflection

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic for me was how different prompting strategies affect the performance of large language models. In our Quarter 1 project, we compared sending all instructions at once, splitting instructions within the same conversation, and splitting them across separate conversations. I found it interesting that changing how instructions are delivered can affect both accuracy and token usage, even when the tasks themselves stay the same.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

For Quarter 2, I would like to investigate how task difficulty affects the performance of different prompting strategies. Our current experiment focuses on dependent math operations, so one possible direction is to increase the number of steps and compare how each method performs as the tasks become more complex. I would also like to see whether the differences in accuracy and token usage become larger as task difficulty increases.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One change I would make is to test a wider variety of tasks. In Quarter 1, we focused on dependent math problems and expanded our experiment from 30 to 100 tasks. While this helped us compare the three prompting methods with a larger sample, our results are still limited to one type of task. Adding programming or logical reasoning tasks could help us understand whether the same patterns appear in different situations.

**4. What other techniques would you be interested in using in your project?**

I would be interested in using statistical methods to better compare the results of different prompting strategies. For example, we could calculate confidence intervals for accuracy and examine whether the differences between methods are statistically significant. I would also like to explore ways to combine accuracy and token usage into a single efficiency measure, since a method that produces more correct answers may also require significantly more tokens.
