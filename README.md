# Building a Student Intervention System 

## Overview
This is the second official project of the Udacity Machine Learning Nanodegree, and the course is co-created with Kaggle. In this project, we are going to build a supervised learning model to predict the student intervention necessity. The objective is to learn about the basic concepts of supervised learning and have a implementation practice on it.


## Software requirement

- [Python 2.7](https://www.python.org/downloads/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [iPython Notebook](http://ipython.org/notebook.html)

## Documents included in the repository

- `README.md`
- `student-data.csv`
- `student_intervention.html`
- `student_intervention.ipynb`

### Memo to Python beginner
In case you are new to Python and you do not know how to create an environment and install the package, here are few links that could help.
- [Managing Python](http://conda.pydata.org/docs/py2or3.html)
- [Managing Environments](http://conda.pydata.org/docs/using/envs.html)
- [Create Virtual Environments for Python with Conda](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)

## Run 
1. Start your the terminal or command line
2. Activate your environment
3. Navigate to the root directory of this repository (./Building_a_Student_Intervention_System_Project/)
4. Run `jupyter notebook student_intervention.ipynb`

Then the web browser would open the jupyter notebook.


## Data

The dataset used in this project is included as `student-data.csv`. This dataset has the following attributes:

- `school` ? student's school (binary: "GP" or "MS")
- `sex` ? student's sex (binary: "F" - female or "M" - male)
- `age` ? student's age (numeric: from 15 to 22)
- `address` ? student's home address type (binary: "U" - urban or "R" - rural)
- `famsize` ? family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
- `Pstatus` ? parent's cohabitation status (binary: "T" - living together or "A" - apart)
- `Medu` ? mother's education (numeric: 0 - none,  1 - primary education (4th grade), 2 -€“ 5th to 9th grade, 3 - secondary education or 4 -€“ higher education)
- `Fedu` ? father's education (numeric: 0 - none,  1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 -€“ higher education)
- `Mjob` ? mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
- `Fjob` ? father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
- `reason` ? reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")
- `guardian` ? student's guardian (nominal: "mother", "father" or "other")
- `traveltime` ? home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
- `studytime` ? weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
- `failures` ? number of past class failures (numeric: n if 1<=n<3, else 4)
- `schoolsup` ? extra educational support (binary: yes or no)
- `famsup` ? family educational support (binary: yes or no)
- `paid` ? extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
- `activities` ? extra-curricular activities (binary: yes or no)
- `nursery` ? attended nursery school (binary: yes or no)
- `higher` ? wants to take higher education (binary: yes or no)
- `internet` ? Internet access at home (binary: yes or no)
- `romantic` ? with a romantic relationship (binary: yes or no)
- `famrel` ? quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- `freetime` ? free time after school (numeric: from 1 - very low to 5 - very high)
- `goout` ? going out with friends (numeric: from 1 - very low to 5 - very high)
- `Dalc` ? workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- `Walc` ? weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
- `health` ? current health status (numeric: from 1 - very bad to 5 - very good)
- `absences` ? number of school absences (numeric: from 0 to 93)
- `passed` ? did the student pass the final exam (binary: yes or no)
