## Exam Analysis of Germany IT Operative Professionals in a Bavarian Training Center 

This Repository includes an analysis of exam grades assigned to aspiring IT Specialists who want to become IT Operative Professionals in Germany. The analysis can be found in the Jupyter Notebook of this repository. The corresponding blog post is available [here](https://fsteppich.github.io/blog/20200304-UD-DS-ExamGradeAnalysis)

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation and Dependencies<a name="installation"></a>
The project is running with Python 3 and Jupyter Notebook. These libraries are required: 

* Numpy 
* Pandas 
* matplotlib 
* Seaborn 
* Scikit-Learn 
* re 

## Motivation for the project<a name="motivation"></a>
This analysis is and linked blog post were done as a project within the Udacity Data Science Nanodegree Program.

As a trainer of aspiring IT Specialists who want to become IT Operative Professionals in Germany, I'm interested in the insights that can be gained solely by looking at exam grades. The data set provides anonymized exam grades of students. The data was provided by a training center in Bavaria, Germany where I thought classes between 2017 and 2020. The data set contains grades of one year from Q4 2017 till Q3 2018. 

I am particularly interested in answering the following three questions: 

* What exam is the easiest (highest number of passing trainees and best average grading)? 
* What exam correlates the most with the Lab Exam grade? 
* Is it possible to predict the grade in the Lab Exam based on other grades? 

## File Descriptions <a name="files"></a> 
`Exam Analysis IT Operative Professionals.ipynb`

This Jupyter Notebook contains all code required to answer the stated questions. 

`exam_grades_it_op_pro_dataset.csv`

The data set used in this analysis. 
 
## Results<a name="results"></a> 
The detailed results can be found in this [blog post](https://fsteppich.github.io/blog/20200304-UD-DS-ExamGradeAnalysis)

**In a nutshell:**

* *Which exam is the easiest to pass?* 

  The Documentation Exam is the easiest of the four exams with an average grade of 2.524 and only 1.288% failing students. 
  
  
* *What exam correlates the most with the Lab Exam?*

  The strongest correlation exists between the Foundation Exam and the Lab Exam.  
  
  
* *Is it possible to predict the grade in the Lab Exam based on other grades?*

  It is best to predict the Lab Exam grade with a linear model using all the other exam grades. 
  
  
## Thanks, Authors, Acknowledgements<a name="licensing"></a> 
Any feedback that helps me to improve this analysis is welcome.  

You can find me on LinkedIn https://www.linkedin.com/in/fst/ 

The accompanying blog post can be found on my GitHub page (https://fsteppich.github.io/blog/20200304-UD-DS-ExamGradeAnalysis)

This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA. 
 