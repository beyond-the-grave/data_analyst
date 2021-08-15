# Students

Analysis of student data.

Used libraries:
  - pandas
  - numpy
  - seaborn
  - itertools
  - matplotlib
  - math
  - scipy.stats

# Datasets Information

Dataset includes 395 entries.

* <i> school </i>: The abbreviation of the school the student attends<br />
* <i> sex </i>: the student's gender (F for female, M for male) <br />
* <i> age </i>: the age of the student (between 15 and 22)<br />
* <i> address </i>: the type of address of the student ('U' - city, 'R' - out of town)<br />
* <i> famsize </i>: family size ('LE3' <= 3, 'GT3' >3)<br />
* <i> Pstatus </i>: the status of the parents' living together ('T' - living together 'A' - separated)<br />
* <i> Medu </i>: mother's education (0 - none, 1 - 4 grades, 2 - 5-9 grades, 3 - specialized secondary or 11 grades, 4 - higher education)<br />
* <i> Fedu </i>: education of the father (0 - none, 1 - 4 classes, 2 - 5-9 classes, 3 - specialized secondary or 11 classes, 4 - higher education)<br />
* <i> Mjob </i>: mother's job ('teacher' - teacher, 'health' - health care, 'services' - civil service, 'at_home' - not working, 'other' - other)<br />
* <i> Fjob </i>: father's job ('teacher' - teacher, 'health' - health care, 'services' - civil service, 'at_home' - not working, 'other' - other)<br />
* <i> reason </i>: reason for choosing a school ('home' - proximity to home, 'reputation' - school reputation, 'course' - educational program, 'other' - other)<br />
* <i> guardian </i>: guardian ('mother' is mother, 'father' is father, 'other' is other)<br />
* <i> traveltime </i>: travel time to school (1 - <15 minutes, 2 - 15-30 minutes, 3 - 30-60 minutes, 4 - >60 minutes) <br />
* <i> studytime </i>: time to study besides school per week (1 - <2 hours, 2 - 2-5 hours, 3 - 5-10 hours, 4 - >10 hours)<br />
* <i> failures </i>: the number of extracurricular failures (n if 1<=n<=3, otherwise 0)<br />
* <i> schoolsup </i>: extracurricular support (yes or no)<br />
* <i> famsup </i>: family educational support (yes or no)<br />
* <i> paid </i>: extra tuition in mathematics (yes or no)<br />
* <i> activities </i>: extracurricular activities (yes or no)<br />
* <i> nursery </i>: attended nursery school (yes or no)<br />
* <i> granular </i>: the frequency of out-of-school activities (yes or no)<br />
* <i> higher </i>: wants higher education (yes or no)<br />
* <i> internet </i>: want an Internet connection at home (yes or no)<br />
* <i> romantic </i>: in a romantic relationship (yes or no)<br />
* <i> famrel </i>: family relationships (from 1 - very bad to 5 - very good)<br />
* <i> freetime </i>: free time after school (from 1 - very little to 5 - very much)<br />
* <i> goout </i>: spending time with friends (1 - very little to 5 - very much)<br />
* <i> health </i>: current state of health (from 1 - very bad to 5 - very good)<br />
* <i> absences </i>: the number of absences<br />
* <i> score </i>: score on the state math exam<br />

# Search

  - Replacing empty values
  - Creation of new indicators
  - Creating dummy variables based on cities
  - Feature correlation
  - Creating samples for the test and for verification
  - Showing the Mean Absolute Error
  - Showing the most important features for the model

