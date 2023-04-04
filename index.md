


## Overview

Deep learning has achieved great success in many applications such as image processing, speech recognition and Go games. However, the reason why deep learning is so powerful remains elusive. The goal of this course is to understand the successes of deep learning by studying and building the theoretical foundations of deep learning. Topics covered by this course include but are not limited to: optimization for deep learning, generalization error analysis of deep learning, representation learning and benign-overfitting of overparamterized learning models. Instructor will give lectures on the selected topics. Students will do a course project.

## Prerequisites
CS 260A, STAT 200A and 200B, ECE 236B and 236C, or equivalent courses.

## Logistics

<!--University of California, Los Angeles  -->

- Time: **Tuesday and Thursday 2:00PM - 3:50PM**
- Location: [**BOELTER 5422**]
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Office hours: **Tuesday and Thursday 4:00-4:30PM** on [**EVI 382**]
- Course Website: [https://uclaml.github.io/CS269-Spring2021/](https://uclaml.github.io/CS269-Spring2022)

## Recommended Textbook

There is no required textbook. The following are recommended textbooks:

1. [T] Matus Telgarsky, [Deep learning theory lecture note](https://mjt.cs.illinois.edu/dlt/index.pdf), 2020
2. [A] Sanjeev Arora et al., [Theory of Deep learning book draft](https://www.dropbox.com/s/smkp4vasbiszhw4/DLbook.pdf?dl=0), 2020 （Thank Prof. Sanjeev Arora for sharing the latest version of the book draft!）
3. [SSBD] Shai Shalev-Shwartz, and Shai Ben-David. Understanding machine learning: From theory to algorithms. Cambridge University Press, 2014. 
4. [MRT] Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar. Foundations of machine learning. MIT press, 2012. 
5. [GBCB] Ian Goodfellow, Yoshua Bengio, Aaron Courville, and Yoshua Bengio. Deep learning. Vol. 1. Cambridge: MIT press, 2016.
6. [ZLLS] Aston Zhang, Zack C. Lipton, Mu Li, Alex J. Smola, Dive into Deep Learning, 2018.

## Reference

1. [BLLT] Bartlett, P. L., Long, P. M., Lugosi, G., & Tsigler, A. (2020). Benign overfitting in linear regression. Proceedings of the National Academy of Sciences, 117(48), 30063-30070.
2. [TB] Tsigler, A. & Bartlett, (2020). Benign overfitting in ridge regression. arXiv preprint arXiv:2009.14286.
3. [ZWBGK2021] Zou, D., Wu, J., Braverman, V., Gu, Q., & Kakade, S. M. (2021). Benign Overfitting of Constant-Stepsize SGD for Linear Regression. In COLT.
4. [WZBGK] Wu, J., Zou, D., Braverman, V., Gu, Q., & Kakade, S. M. (2021). Last Iterate Risk Bounds of SGD with Decaying Stepsize for Overparameterized Linear Regression. arXiv preprint arXiv:2110.06198.
5. [ZWBGFK] Zou, D., Wu, J., Braverman, V., Gu, Q., & Kakade, S. M. (2021). The Benefits of Implicit Regularization from SGD in Least Squares Problems. In NeurIPS.
6. [ZWBGK2022] Zou, D., Wu, J., Braverman, V., Gu, Q., & Kakade, S. M. (2022). Risk Bounds of Multi-Pass SGD for Least Squares in the Interpolation Regime. arXiv preprint arXiv:2203.03159.
7. [ZCLG] Zou, D., Cao, Y., Li, Y., & Gu, Q. (2021). Understanding the Generalization of Adam in Learning Neural Networks with Proper Regularization. arXiv preprint arXiv:2108.11371. 
8. [CCBG] Cao, Y., Chen, Z., Belkin, M., & Gu, Q. (2022). Benign Overfitting in Two-layer Convolutional Neural Networks. arXiv preprint arXiv:2202.06526. 
	


## Grading Policy
 
Grades will be computed based on the following factors:

- Attendance 30%
- Lecture Note Scribe 30%
- Project 40%

## Schedule


| # | Date  | Topic  | note | scribed note | reading materials  | homework |
|----|----|----|----|----|----|----|
| 1 | 3/29 | Introduction  | [note]() | [scribe note]() | ||
| 2 | 3/31 | Benign Overfitting in Linear Regression I | [note]() | [scribe note]() | [BLLT] ||
| 3 | 4/5 | Benign Overfitting in Linear Regression II | [note]() | [scribe note]() | [BLLT] |
| 4 | 4/7 | Benign Overfitting in Linear Regression III| [note]() |  [scribe note]()| [BLLT] ||
| 5 | 4/12 | Benign Overfitting in Ridge Regression I | [note]() | [scribe note]() | [TB] ||
| 6 | 4/14 | Benign Overfitting in Ridge Regression II| [note]() | [scribe note]()| [TB] ||
| 7 | 4/19 | Benign Overfitting of SGD I | [note]()| [scribe note]() | [ZWBGK2021] | |
| 8 | 4/21 | Benign Overfitting of SGD II | [note]() |  | [ZWBGK2021] ||
| 9 | 4/26 | Benign Overfitting of SGD III | [note]() | [scribe note]() | [ZWBGK2021]  ||
| 10 | 4/28 | Last Iterate Bound of SGD I |[note]() | | [WZBGK] ||
| 11 | 5/3 | Last Iterate Bound of SGD II |[note]() | | [WZBGK] | |
| 12 | 5/5 | Last Iterate Bound of SGD III | [note]() | | [WZBGK] ||
| 13 | 5/10 | Ridge Regression vs SGD | [note]() |  | [ZWBGFK] ||
| 14 | 5/12 | Ridge Regression vs SGD | [note]() | | [ZWBGFK] ||
|  | 5/17 | Canceled due to NeurIPS | [note]() | |  ||
| 15 | 5/19 | Multi-pass SGD I | [note]() | | [ZWBGK2022] ||
| 16 | 5/24 | Multi-pass SGD II | [note]() | | [ZWBGK2022] ||
| 17 | 5/26 | Benign Overfitting of CNNs I |  | | [CCBG] ||
| 18 | 5/31 | Benign Overfitting of CNNs II |  | | [CCBG] ||
| 19 | 6/2 | Benign Overfitting of CNNs III | [note]() | | [CCBG] ||
|  |  |  |  | |  ||

## Academic Integrity Policy

Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 

## Attendance

There will be a signup sheet in each lecture. Each student can skip at most 2 lectures. The student will lose 3 points for each absence.

## Lecture Note Scribing

Students are required to scribe one lecture note. The latex template for lecture note will be provided. The scribed lecture notes should be a zip file submitted on CCLE that compiles without errors, and it is due **4 days after the lecture**. This note will be graded. For example, if 2 students are assigned to scribe a given lecture, I expect to receive 2 separate notes. The individual notes are primarily for grading purposes (and also to make sure that each student scribes their own lecture notes), while the final version of the lecture note will be posted on the course website, after being proofread and edited by the Instructor. 

- The signup sheet for lecture note scribing can be found at [here](https://docs.google.com/spreadsheets/d/1sMOOK-bNIYO0njKglIbmODHWpGRUA_lULDq9CUqEaG4/edit#gid=0).
- The Latex template for lecture note scribing can be downloaded at [here](https://www.dropbox.com/s/dfsdcpszv0hwwh4/lecture%20scribing%20template.zip?dl=0)


## Project

Students are required to do a project in this class. The goal of the course project is to provide the students an opportunity to explore research directions in optimization or machine learning. Therefore, the project should be related to the course content. An expected project include but not limited to

- A novel and sound solution to an interesting problem
- Thorough theoretical analysis of existing deep learning approaches

The best outcome of the project is a manuscript that is publishable in major machine learning conferences (COLT, ICML, NeurIPS, ICLR, AISTATS, UAI etc.) or journals (Journal of Machine Learning Research). The detailed course project guideline can be found at [here](https://www.dropbox.com/s/2o0hht6qjijjbog/Course%20project.pdf?dl=0). **Students cannot use their own published work as the course project.**


## Relevant Courses

There are many other optimization for machine learning courses. To mention a few:

[Matus Telgarsky's deep learning theory course](https://mjt.cs.illinois.edu/dlt/)

[Sanjeev Arora's theoretical deep learning course](https://www.cs.princeton.edu/courses/archive/fall19/cos597B/)

[Peter Bartlett's statistical learning theory course](https://people.eecs.berkeley.edu/~bartlett/courses/281b-sp08/)

[Sham Kakade's statistical learning theory course](http://stat.wharton.upenn.edu/~skakade/courses/stat928/)

[Maxim Raginsky's statistical learning theory course](http://maxim.ece.illinois.edu/teaching/SLT/)

[Quanquan Gu's foundations of deep learning course in Spring 2021](https://uclaml.github.io/CS269-Spring2021/)

