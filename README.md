# STUDENT-GRADE-ANALYSIS-PREDICTION

[![author](https://img.shields.io/badge/author-Abhishek-ff69b4.svg?style=flat-square)](https://www.linkedin.com/in/abhishekmali/)
[![GitHub followers](https://img.shields.io/github/followers/AbhishekMali21?style=social)](https://github.com/AbhishekMali21?tab=followers)
[![GitHub watchers](https://img.shields.io/github/watchers/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?style=social)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/watchers)
[![GitHub stars](https://img.shields.io/github/stars/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?style=social)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?style=social)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/network/members)

![GitHub language count](https://img.shields.io/github/languages/count/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?logoColor=9cf&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?logoColor=important&style=flat-square)

[![GitHub issues](https://img.shields.io/github/issues/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?style=flat-square)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/issues?q=is%3Aopen+is%3Aissue)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?style=flat-square)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?logoColor=yellow&style=flat-square)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/pulls?q=is%3Aopen+is%3Apr)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION?logoColor=yellow&style=flat-square)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/pulls?q=is%3Apr+is%3Aclosed)
[![LICENSE](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](https://github.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION/blob/master/LICENSE)
[![HitCount](http://hits.dwyl.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION.svg)](http://hits.dwyl.com/AbhishekMali21/STUDENT-GRADE-ANALYSIS-PREDICTION)

### Objective
To predict the final grade of Portugese high school students

### Problem Statement
The problem statement can be defined as follows ”Given a dataset containing information about 396 Portuguese students, define classification algorithms based on the data available to identify if the student performs good in final exam. Also, evaluate different machine learning models using the dataset.”

### Description of the Dataset
The dataset includes information about students acquiring secondary education from two Portuguese schools. The data attributes include student grades, demographic, social, and school-related features, and it was collected by using school reports and questionnaires. Two datasets are provided which contain performance report of students in two distinct subjects: Mathematics (mat) and Portuguese language (por). The two data sets were modeled using binary/five-level classification and regression tasks [Cortez and Silva, 2008].

***Important note:*** the target attribute G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades. It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful (see paper source for more details).

### Attribute Information:
* school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
* sex - student's sex (binary: 'F' - female or 'M' - male)
* age - student's age (numeric: from 15 to 22)
* address - student's home address type (binary: 'U' - urban or 'R' - rural)
* famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
* Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
* Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
* Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
* Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
* Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
* reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
* guardian - student's guardian (nominal: 'mother', 'father' or 'other')
* traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
* studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
* failures - number of past class failures (numeric: n if 1<=n<3, else 4)
* schoolsup - extra educational support (binary: yes or no)
* famsup - family educational support (binary: yes or no)
* paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
* activities - extra-curricular activities (binary: yes or no)
* nursery - attended nursery school (binary: yes or no)
* higher - wants to take higher education (binary: yes or no)
* internet - Internet access at home (binary: yes or no)
* romantic - with a romantic relationship (binary: yes or no)
* famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
* freetime - free time after school (numeric: from 1 - very low to 5 - very high)
* goout - going out with friends (numeric: from 1 - very low to 5 - very high)
* Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
* Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
* health - current health status (numeric: from 1 - very bad to 5 - very good)
* absences - number of school absences (numeric: from 0 to 93)


### Methodology
Since universities are prestigious places to obtain higher education, students’ retention in universities is a matter of high concern. It has been found that most of the students’ drop-out from universities during their first year due to lack of support in undergraduate courses which is why the first year is referred as a “make or break” year. Getting zero support on a course’s domain and its complexity can demotivate a student and lead to withdrawal.

An appropriate solution needs to be developed to assist students’ retention in higher education institutions. One of the solutions is an early grade predictor which will monitor students’ progress in courses at university leading to improvement in students’ learning process based on predicted grades. 

Using machine learning with educational data mining can help improve the learning process of students. Different models can be developed to predict students’ grades in enrolled courses which will provide valuable information to facilitate students’ retention in those courses. This information can also be used to identify students at-risk early in the semester based on which the system can suggest the instructors to provide special attention to those students. 

Various packages such as cufflinks, seaborn & matplotlib can be used to represent the data and its different attributes graphically or pictorially to analyse the dataset for predicting the final grade(G3).

### Machine Learning Algorithms used
1. Linear Regression
2. ElasticNet Regression
3. Random Forest
4. Extra Trees
5. SVM
6. Gradient Boosted
7. Baseline

### Experimental Results
1. KDE Plot to view all attributes using cufflinks
2. Box Plot to view all attributes using cufflinks
3. Histogram Plot for G3 (Final Grade) using cufflinks
4. Pictorial representation of any null data present in the dataset.
5. Count Plot for Student Sex Attribute
6. Kernel Density Estimation for Age of Students.
7. Count PLot for Male & Female students in different age groups.
8. Count Plot for students from Urban & Rural Region.
9. Does age affect final grade?
10. Do urban students perform better than rural students?
11. Previous Failures vs Final Grade(G3)
12. Family Education vs Final Grade(G3)
13. Higher Education vs Final Grade(G3)
14. Go Out vs Final Grade(G3)
15. Reason vs Students Count



### Citation
P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.




