---
title: "Py-GraSPI"
date: 2025-05-09T06:00:20+06:00
hero: /images/posts/writing-posts/git.svg
menu:
  sidebar:
    name: Py-GraSPI
    identifier: pygraspi
    parent: Projects
    weight: 10
---

### Contents
- [what is Py-GraSPI?](#what-is-py-graspi)
- [The problem I tried to solve?](#the-problem-i-tried-to-solve)
- [how did you solve the problem?](#how-did-you-solve-the-problem)
- [What did you learn?](#what-did-you-learn)
## What is Py-GraSPI?

Py-GraSPI(Graph-based Structure Property Identifier) is a Python package designed to compute a comprehensive set of descriptors for segmented microstructures using a graph-based approach.

I contributed in Spring 2025, in the class named *Experimental Learning and Research (CSE302)* at University at Buffalo during my exchange program.

## The problem I tried to solve

There were two problems to solve:
### “How to improve the performance?”
compared to GraSPI (C++ implemented version), the execution time is 7~10x slower than GraSPI. 
Professor Wodo(client of this project) wants to improve the code so that lower the time.

### “How to simplify the code?”
In previous code, constructing graph code was too complicated to understand the process. She also wanted to simplify the code so that users can understand how it works more easily.  

## How did you solve the Problem?
![graph_construction_process_compare](graph_const.png)




What I learned

1. How to do group project
2. Importance of clear communication
3. 


[code compare & analysis slide](https://drive.google.com/file/d/1NacnO9h0Mx7XOlgGtrKKeZ-lxkF9EkP4/view?usp=sharing)
[performance comparison with previous version](https://drive.google.com/file/d/1bLdLknpW-XXEGJ5jzhbh6SX2v3u30Vwd/view?usp=sharing)
[Changes I made slide](https://drive.google.com/file/d/1g8UiOgrikpyPu6JsfVSitURTZN0v1E8U/view?usp=sharing)
[simplified slide](https://drive.google.com/file/d/1H2ZtVBoie1j5z4Qc8sXmX9AONHgye5pm/view?usp=sharing)