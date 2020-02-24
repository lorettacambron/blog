+++ 
draft = false 
date = 2020-02-23T18:24:46-06:00
title = "Why Is Explainability Important"
description = ""
slug = "" 
tags = []
categories = []
externalLink = ""
series = []
+++

Goeff Hinton recently tweeted [[1](https://twitter.com/geoffreyhinton/status/1230592238490615816?s=20)] a question that got me thinking. At first blush, explainability sounds fantastic, and to be clear, I'm pro-explainability. However, he poses an interesting thought - if a model, algorithm, or automated surgeon is more accurate than the prior human-run decision, does it matter if we can explain?

After an initial positive reaction (If I had cancer, I'd choose the more accurate option and not question decisions made to get the cure), I'm drawn to questioning what happens when things go wrong. In this case, the robot surgeon has a 90% cure rate. What happens in the 10% of cases that are not cured? Or worse, what happens when the robot makes a mistake? Or when it turns out the robot was only trained on human males in clinical trials (this still happens *all the time* because there isn't regulation around equal participation of the sexes in clinical trials [[2](https://www.amazon.com/Invisible-Women-Data-World-Designed/dp/1419729071)]. 

When things go wrong, or when things are unexpected, *that* is when we need to be able to see what's going on in the model. That's when we need documentation on data used, data source, model architecture, and more [[3](https://arxiv.org/pdf/1803.09010.pdf), [4](https://arxiv.org/pdf/1810.03993.pdf)].

There are broader questions here too regarding legal implications [[5](https://arxiv.org/abs/1912.00761)]. If a robot-surgeon makes a mistake, or robot-doctor prescribes a harmful treatment plan, how does a malpractice trial go? Are engineers responsible for medical ramifications? In an early version of Tesla's automated driving software, researchers were able to trick computer vision models into speeding (35 mph was read as 85 mph with a slight change to the "3" on the sign)[[6](https://www.technologyreview.com/s/615244/hackers-can-trick-a-tesla-into-accelerating-by-50-miles-per-hour/)]. In the same way, if a driver is pulled over, in a car they were told they need not drive, who gets a speeding ticket? Is Tesla liable for "bad driving" which stems from their software?

These are complicated issues, and there are as many opportunities to harm as there are to help. It's clear to me that at the very least, we need to keep circulating this topic of conversation. As technology is more and more interwoven into our lives, we should look to interdisciplinary policy and regulation to hold companies accountable and keep consumers informed.

Geoff's question is vague, and I made a few assumptions to hash out my thoughts. What are some angles to add to this conversation? How do you respond to Geoff's question?

#### Further reading and sources:
1. Geoff Hinton's tweet: https://twitter.com/geoffreyhinton/status/1230592238490615816?s=20
2. Recommend reading Caroline Criado-Parez's thoroughly researched book: https://www.amazon.com/Invisible-Women-Data-World-Designed/dp/1419729071
3. Datasheets for datasets, the way I wish all datasets were documented: https://arxiv.org/pdf/1803.09010.pdf
4. Model cards for model reporting (this paper and the previous were written by some of my favorite thought leaders, definitely them out): https://arxiv.org/pdf/1810.03993.pdf
5. Neat paper about how the fields of law and machine learning need to work together (and how it's gone wrong sometimes): https://arxiv.org/abs/1912.00761
6. Article about researchers testing (and "tricking") Tesla's software: https://www.technologyreview.com/s/615244/hackers-can-trick-a-tesla-into-accelerating-by-50-miles-per-hour/
