Author: Yang Shan, Wang Zilu 

From: Department of Management Science and Engineering, Tongji University

## Introduction

2D Nesting problem is a kind of combination optimization problem which tragets at maximizing the utilization ratio by arranging the layout of all shapes. 

<img src="/Users/sean/Documents/Projects/My Github/Use-Modified-Depth-Penetration-and-Linear-Programming-Methodology-to-Solve-Nesting-Problem/img/image-20200623111448965.png" alt="image-20200623111448965" height="150px" />

It is a NP-Hard problem and to achieve global optimization is almost impossible. As a result, the most common way to optimize the layout is searching a new better position for polygons step by step.

Guided cuckoo search proposed by Elkeran is the methodology that can obtain the best result by now. This approache applied a elvolution algorithm named cuckoo search to settle searching a new position on a two-dimensional plane. 

However, the searching efficiency is low because

## What we have done？ 

**We proposed a new methodology based on a modified penetration depth and guided search.** 

<img src="/Users/sean/Documents/Projects/My Github/Use-Modified-Depth-Penetration-and-Linear-Programming-Methodology-to-Solve-Nesting-Problem/img/image-20200623160956903.png" alt="image-20200623160956903" width="800px" />

With this modification, the noncovex searching problem over two-dimensional plane is convert into serval LP problems which can get the best position fast and efficiently under this estimation criteria.

**Based on our current experimental results, our algorithm has gotten layout with higher utilization ratio on serval benchmarks compared with other approaches. Other experiments are in progress.**

## Algorithm Outline

<img src="img/image-20200623104625377.png" alt="image-20200623104625377" height="300px" />





## Geometry

This best

<img src="img/image-20200623105743665.png" alt="image-20200623105743665" height="200px" />

## Experiments

