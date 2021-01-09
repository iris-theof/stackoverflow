
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

This project is forked from a project made for the Udacity "Data Science Nanodegree" and I have added some additional exploration data ananlysis. Exploration data analysis on the Stack Overflow data survey from 2017 and the original project pursued to add the following questions:

1. How other developers suggested breaking into the field (what education to pursue)?
2. What factors about an individual contributed to salary?
3. How bias played a role in the suggestions of developers for how to break into the field?
4. What was the state of bootcamps for assisting individuals with breaking into developer roles?
5. How were bootcamps assisting with increasing diversity in tech careers?

What I explored is how the gender affects the questions based above. To this end, I have added in the new branch I created
a notebook 'HowToBreakIntoTheFieldFemaleMale.ipynb' and modified the 'PredictSalary.ipynb' so as to:

1. How other developers recommend to break into the field depending on gender
2. How to make an efficient ML model to predict the Salary

Moreover, I have made existing analysis more efficient using functional programming instead of for loops.

## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 

