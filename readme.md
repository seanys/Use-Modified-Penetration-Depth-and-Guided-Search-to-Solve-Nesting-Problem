## Use modified penetration depth and guided search to solve nesting problem 

Author: Yang Shan(羊山), Wang Zilu(王子路) 

From: Department of Management Science and Engineering, Tongji University

**Paper for this work is still editing and the experiment is still in progress.** 

We modify penetration depth and realized precisely global search the first time on nesting problem. Hybridize it with guided search, we named it GLPS. 

This methodology has obtained pronounced results compared with benchmarks.

![1593867725732](img/1593867725732.jpg)

## Report(Chinese)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0001](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0001.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0002](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0002.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0003](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0003.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0004](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0004.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0005](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0005.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0006](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0006.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0007](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0007.jpg)

![1593866790902](img/1593866790902.jpg)

![1593866811805](img/1593866811805.jpg)

![1593867725732](img/1593867725732.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0009](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0009.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0010](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0010.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0011](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0011.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0012](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0012.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0013](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0013.jpg)

![通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0014](img/通过改良的渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0014.jpg)



## Introduction

2D Nesting problem is a kind of combination optimization problem which tragets at maximizing the utilization ratio by arranging the layout of all shapes. 

<img src="img/image-20200623111448965.png" alt="image-20200623111448965" height="150px" />

It is a NP-Hard problem and to achieve global optimization is almost impossible. As a result, the most common way to optimize the layout is searching a new better position for polygons step by step.

Guided cuckoo search proposed by Elkeran is the methodology that can obtain the best result by now. This approache applied a elvolution algorithm named cuckoo search to settle searching a new position on a two-dimensional plane. 

However, the searching efficiency is low because the best position can't 



**For the cuckoo search, it needs to search over 450 positions and the best position may not be found. However, take dateset fu for example, after about only 50-70 positions be tested, the location with the least penetration depth can be found.**



