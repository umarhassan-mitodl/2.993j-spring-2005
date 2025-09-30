---
content_type: page
description: Syllabus section contains the prerequisites, textbook required, grading
  criteria, and rationale of the course.
draft: false
hide_download: true
hide_download_original: null
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: da588622-4cc0-5438-6670-e1231b794533
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
## Course Meeting Times

Lectures: 2 sessions / week, 1.5 hours / session

This subject was originally offered in Course 13 (Department of Ocean Engineering) as 13.002J. In 2005, ocean engineering became part of Course 2 (Department of Mechanical Engineering), and this subject was renumbered 2.993J.

## Prerequisite

18.03

## Rationale

Computers are playing an increasingly important role in any science and engineering curriculum. At the same time there has certainly been a dramatic increase in computer literacy among the undergraduate population during the last decade. The flip side of this development is the enormous confidence the students have in the computers and the results they give. The MIT undergraduate curriculum has a number of subjects that are aimed at training the students in scientific and engineering programming, such as [1.00](/courses/1-00-introduction-to-computers-and-engineering-problem-solving-spring-2012) and 10.001. These subjects are excellent in developing advanced programming skills, allowing the students to develop highly efficient and advanced computer programs. Unfortunately, due to lack of time, the numerical error and stability analysis which is the key to developing accurate and robust algorithms are only treated superficially in the MIT undergraduate curriculum.

The 6-unit undergraduate subject, 13.002J, is aimed at filling this gap. This subject presents the fundamental formulation, methodology and techniques for numerical solution of engineering problems. The subject is initiated with fundamental principles of digital computing and the implications for algorithm accuracy and stability. Error propagation and stability analysis is introduced from first principles. The solution of systems of linear equations, (comprising 90% of numerical effort in science and engineering) is covered extensively, including direct (Gaussian elimination) and iterative techniques, sparse and banded matrices, and matrix inversions. The error and stability issues associated with solving linear systems will be covered extensively. The numerical treatment of eigenvalue problems is briefly discussed. Several lectures are devoted to solving non-linear equations, including root finding. The concept of interpolation and its role as foundation for numerical differentiation and integration is introduced, emphasizing classical (Lagrange, Newton) polynomial interpolation. Numerical differentiation and integration is covered in depth, with particular emphasis on the error and convergence analysis. The final part of the course introduces the fundamentals of finite-difference solutions to ordinary differential equations, again with emphasis on error and convergence analysis.

The subject will be taught during the first 7 weeks of the term, with two 1.5-hour lectures per week. The grading will be based on weekly homework assignments, with half being 'pen and paper' type dealing with error and stability analysis etc., and the other half involving actual algorithm development. Students are strongly encouraged to use MATLAB® (excluding built-in routines) and should see the instructor if they wish to use another programming language. At the end of the course, the students will have developed a number of algorithms which they can apply as a reliable tool in later subjects and projects.

## Objectives

### Objective 1

Understand the implications of digital number representation and digital arithmetic for computational science and engineering.

- Outcome 1.1: Understand the fundamental principles of digital computing, including number representation and arithmetic operations.
- Outcome 1.2: Understand the linkage between accuracy, stability and convergence.
- Outcome 1.3: Perform error analysis for arithmetic operations.
- Outcome 1.4: Understand the propagation of errors through complex numerical algorithms.
- Outcome 1.5: Perform numerical stability analysis.

### Objective 2

Develop and implement numerically stable and accurate algorithms for all the basic tasks of computational science and engineering:

- Outcome 2.1: Develop stable algorithms for solving linear systems of equations.
- Outcome 2.2: Develop efficient and stable algorithms for finding roots of non-linear equations.
- Outcome 2.3: Implement numerically stable recursion algorithms for evaluating mathematical functions.
- Outcome 2.4: Understand the use of interpolation for numerical differentiation and integration.
- Outcome 2.5: Develop stable solution algorithms for ordinary differential equations.

## Textbook

Mathews, J. H., and K. D. Fink. _Numerical Methods Using MATLAB®_. 3rd ed. Upper Saddle River, NJ: Prentice Hall, 1998. ISBN: 9780132700429.

## Grading

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
ACTIVITIES
{{< thclose >}}{{< thopen >}}
PERCENTAGES
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
Homeworks
{{< tdclose >}}{{< tdopen >}}
60%
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Exam
{{< tdclose >}}{{< tdopen >}}
30%
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Class Participation
{{< tdclose >}}{{< tdopen >}}
10%
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

## Class Survey

During the first class, students are asked to fill out a survey to assess their level of knowledge and understanding in various areas of mathematics and programming languages.

Class Survey-Spring 2005 ({{% resource_link 9d1aa9e2-f27b-fc12-2715-c70e83bac8c4 "PDF" %}})