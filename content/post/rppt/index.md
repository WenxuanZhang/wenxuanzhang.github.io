---
title: No more power point by hand — automate PPT creation by R Officer
subtitle: 
summary: Learn how to create powerpoint using r office and flextable 
authors:
  - admin
tags: []
categories: []
projects: []
date: '2023-05-15T00:00:00Z'
lastMod: '2023-05-15T00:00:00Z'
image:
  caption: ''
  focal_point: ''
---


As a data scientist, you draw insights from data and present it in a informative and visually appealing way. There are good tools (Tableau, Looker, Power BI) to help you tell the story, while what if your boss prefers PowerPoint?

It is not hard to make PowerPoint, but it takes time and effort. You must be patient enough to adjust each font size and make sure all elements aligned. Besides, you must get very good stamina, if your PowerPoint is 100 pages. What’s more, one single change happened, and you need to redo the slides again. Believe me, that’s not fun.

Luckily, the Officer packages (developed by [ArData](https://www.ardata.fr/), a French data consultancy) provide a solution for users to manipulate the doc and pptx documents.

This article, I will show you how to create a simple scorecard deck by region using Officer, mschart and flextable packages. Code and Data could be found in my [GitHub repo](https://github.com/WenxuanZhang/Powerpoint-Automation)

The data used here is the superstore data. The Template is the Balanced Score Card template.

![png](./final.png)


