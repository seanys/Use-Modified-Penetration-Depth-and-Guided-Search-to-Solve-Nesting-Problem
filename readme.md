## Use modified penetration depth and guided search to solve nesting problem 

Author: Yang Shan, Wang Zilu 

From: Department of Management Science and Engineering, Tongji University

We modify penetration depth to make searching new positions for polygons in the global scale feasible with computing complexity reduced. The report using English will be updated soon.

## Report(Chinese)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0001](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0001.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0002](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0002.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0003](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0003.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0004](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0004.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0005](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0005.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0006](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0006.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0007](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0007.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0008](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0008.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0009](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0009.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0010](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0010.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0011](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0011.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0012](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0012.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0013](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0013.jpg)

![基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0014](img/基于渗透深度与引导检索解决二维排样问题-羊山&王子路_page-0014.jpg)





## Introduction

2D Nesting problem is a kind of combination optimization problem which tragets at maximizing the utilization ratio by arranging the layout of all shapes. 

<img src="img/image-20200623111448965.png" alt="image-20200623111448965" height="150px" />

It is a NP-Hard problem and to achieve global optimization is almost impossible. As a result, the most common way to optimize the layout is searching a new better position for polygons step by step.

Guided cuckoo search proposed by Elkeran is the methodology that can obtain the best result by now. This approache applied a elvolution algorithm named cuckoo search to settle searching a new position on a two-dimensional plane. 

However, the searching efficiency is low because the best position can't 



**For the cuckoo search, it needs to search over 450 positions and the best position may not be found. However, take dateset fu for example, after about only 50-70 positions be tested, the location with the least penetration depth can be found.**



## What we have done？ 

<img src="img/image-20200623160956903.png" alt="image-20200623160956903" width="800px" />

## Algorithm Outline

<img src="img/image-20200623104625377.png" alt="image-20200623104625377" height="300px" />





## Geometry

<img src="img/image-20200623172800026.png" alt="image-20200623172800026" width="600px" />



### Convex



<img src="img/image-20200623105743665.png" alt="image-20200623105743665" height="200px" />

### Non-Convex





## Experiments



