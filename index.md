


## Overview

Optimization is playing a central role in machine learning and deep learning. The goal of this course is to introduce modern optimization algorithms and theory for machine learning. Topics include but are not limited to gradient descent, accelerated gradient descent, stochastic gradient descent, variance reduction, lower bounds, optimization on manifolds, optimization in probability space, implitic bias of optimization algorithms, etc. Instructor will give lectures on the selected topics. Students will do a course project.

## Prerequisites
CS 260A, STAT 200A and 200B, ECE 236B and 236C, or equivalent courses.

## Logistics

<!--University of California, Los Angeles  -->

- Time: **Tuesday and Thursday 2:00PM - 3:50PM**
- Location: [**BOELTER 5252**]
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Office hours: **Tuesday and Thursday 4:00-4:30PM** on [**EVI 382**]
- Course Website: [https://uclaml.github.io/CS269-Spring2023/](https://uclaml.github.io/CS269-Spring2023)

## Recommended Textbook

There is no required textbook. The following are recommended textbooks:

1. [N] Yurii Nesterov, Introductory Lectures on Convex Optimization
A Basic Course, 2004
2. [B] Sébastien Bubeck, [Convex Optimization: Algorithms and Complexity](https://arxiv.org/abs/1405.4980), 2014.
3. [BV] Stephen Boyd, and Lieven Vandenberghe. [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf). Cambridge University Press, 2004. 
4. [NW] Jorge Nocedal and Stephen J. Wright. Numerical Optimization. Springer press, 2006. 

## Reference

1. [JZ] Rie Johnson, Tong Zhang, Accelerating Stochastic Gradient Descent using Predictive Variance Reduction, NIPS 2013.
2. [FLLZ] Cong Fang, Chris Junchi Li, Zhouchen Lin, Tong Zhang, SPIDER: Near-Optimal Non-Convex Optimization via Stochastic Path-Integrated Differential Estimator, NeurIPS 2018.
3. [WJZLT] Zhe Wang, Kaiyi Ji, Yi Zhou, Yingbin Liang, Vahid Tarokh, SpiderBoost and Momentum: Faster Stochastic Variance Reduction Algorithms, NeurIPS 2019.
4. [CDHS] Yair Carmon, John C. Duchi, Oliver Hinder, Aaron Sidford, Lower Bounds for Finding Stationary Points I, Mathematical Programming, 2020.
5. [ZS] Hongyi Zhang, Suvrit Sra, First-order Methods for Geodesically Convex Optimization, In COLT, 2016.
6. [ZRS] Hongyi Zhang, Sashank J. Reddi, Suvrit Sra, Riemannian SVRG: Fast Stochastic Optimization on Riemannian Manifolds, In NIPS 2016.

	


## Grading Policy
 
Grades will be computed based on the following factors:

- Lecture Note Scribe 20%
- Homework 40%
- Project 40%

## Tentative Schedule


| # | Date  | Topic  | note | scribed note | reading materials  | homework |
|----|----|----|----|----|----|----|
| 1 | 4/4 | Gradient Desent  | [note]() | [scribe note]() | [B] ||
| 2 | 4/6 | Nesterov's AGD | [note]() | [scribe note]() | [N,B] ||
| 3 | 4/11 | SGD | [note]() | [scribe note]() | [B] |
| 4 | 4/13 | Variance Reduction| [note]() |  [scribe note]()| [JZ] ||
| 5 | 4/18 | Variance Reduction | [note]() | [scribe note]() | [FLLZ,WJZLT] ||
|  | 4/20 | Canceled due to travel| [note]() | [scribe note]()| [] ||
| 6 | 4/25 | Lower Bound | [note]()| [scribe note]() | [N] | |
| 7 | 4/27 | Lower Bound | [note]() |  | [CDHS] ||
| 8 | 5/2 | Lower Bound | [note]() | [scribe note]() | [CDHS,FLLZ]  ||
| 9 | 5/4 | Optimization on Riemmanian Manifold |[note]() | | [ZS,ZRS] ||
| 10 | 5/9 | Optimization on Riemmanian Manifold |[note]() | | [ZS,ZRS] | |
| 11 | 5/11 | Optimization in Probability Space | [note]() | | [] ||
|  | 5/16 | Canceled due to NeurIPS | [note]() |  | [] ||
| 12 | 5/18 | Optimization in Probability Space | [note]() | | [] ||
| 13 | 5/23 | Implicit Bias of Logistic Regression | [note]() | |  ||
| 14 | 5/25 | Implicit Bias of Logistic Regression | [note]() | | [] ||
| 15 | 5/30 | Implicit Bias of Deep Linear Networks | [note]() | | [] ||
| 16 | 6/1 | Implicit Bias of Deep Linear Networks |  | | [] ||
| 17 | 6/6 | Implicit Bias of Leaky ReLU Networks |  | | [] ||
| 18 | 6/8 | Implicit Bias of Leaky ReLU Networks | [note]() | | [] ||
|  |  |  |  | |  ||

## Academic Integrity Policy

Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 


## Lecture Note Scribing

Students are required to scribe one lecture note. The latex template for lecture note will be provided. The scribed lecture notes should be a zip file submitted on CCLE that compiles without errors, and it is due **4 days after the lecture**. This note will be graded. For example, if 2 students are assigned to scribe a given lecture, I expect to receive 2 separate notes. The individual notes are primarily for grading purposes (and also to make sure that each student scribes their own lecture notes), while the final version of the lecture note will be posted on the course website, after being proofread and edited by the Instructor. 

- The signup sheet for lecture note scribing can be found at [here](https://docs.google.com/spreadsheets/d/1arM8H_YvK1FDNrOXGnLWGUOpbj7-h1NwfILUI__v_GA/edit?usp=sharing).
- The Latex template for lecture note scribing can be downloaded at [here](https://www.dropbox.com/s/jrz9dfssmcblbio/lecture%20scribing%20template.zip?dl=0)


## Project

Students are required to do a project in this class. The goal of the course project is to provide the students an opportunity to explore research directions in optimization or machine learning. Therefore, the project should be related to the course content. An expected project include but not limited to

- A novel and sound solution to an interesting problem
- Thorough theoretical analysis of existing deep learning approaches

The best outcome of the project is a manuscript that is publishable in major machine learning conferences (COLT, ICML, NeurIPS, ICLR, AISTATS, UAI etc.) or journals (Journal of Machine Learning Research). The detailed course project guideline can be found at [here](https://www.dropbox.com/s/8yeic1gsv9rl9c6/Course%20project.pdf?dl=0). **Students cannot use their own published work as the course project.**


## Relevant Courses

There are many other optimization for machine learning courses. To mention a few:

[Suvrit Sra's Optimization for Machine Learning](https://optml.mit.edu/teach/6881/)

[Moritz Hardt's Convex Optimization and Approximation](https://ee227c.github.io)

[Martin Jaggi and Nicolas Flammarion's Optimization for Machine Learning](https://github.com/epfml/OptML_course)


