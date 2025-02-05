
# Course Syllabus* : GEP662: Introduction to Programming for GISs, Spring 2018
*last Updated: March 25, 2018
**subject to change based on the needs of the class

**Instructor:** Anastasia Clark  
**E-mail:** anastasiapotupalova@gmail.com  
**GitHub:** https://github.com/anastasiaclark   
**Course meetings:** Gillet Hall, Rm. 322 (GISc Lab) on Tuesdays 6:00 pm to 9:30 pm.  
**Course Slack Channel:** https://gep662.slack.com 

## Readings
There isn't a comprehensive text book for this course. We will use a combination of freely avalable books, blogs, videos and Python packages documentation as our study materials. Chapters will be asigned from below books; other readings will be linked   in the readings section of the [weekly schedule breakdown](#weekly-schedule)

* Automate the Boring Stuff with Python
    https://automatetheboringstuff.com/
    
* Python for Everybody
https://books.trinket.io/pfe/index.html
    

**Recommended books on Python programming & GIS:** 
* Lawhead, J. (2015) Learning Geospatial Analysis with Python: An effective guide to geographic information systems and remote sensing analysis using Python 3, Second edition. Packt Publishing. https://www.packtpub.com/application-development/learning-geospatial-analysis-python-second-edition  
* McKinney, W. (2012) Python for Data Analysis: Data wrangling with Pandas, NumPy and iPython, First edition. O´Reilly Media. http://shop.oreilly.com/product/0636920023784.do

## Software
For this cource, we will use the [Anaconda's distribution of Python 3](https://www.anaconda.com/download/). We will utillize two Python Development Environments, [Spyder](http://pythonhosted.org/spyder/) and [Jupyter Notebook](http://jupyter.org/). All the software is installed on the lab's computers. To install Anaconda and the required packages on your personal machine, [follow this instructions](https://github.com/anastasiaclark/GEP662_Spring2018/blob/master/installations.md#install-anacondas-distribution-of-python-on-your-machine).

## Learning Objectives
After successfully completing this course, you are expected to be able to:

* Understand fundamental programming concepts  
* Understand basics of working with data in Python
* Understand the concept of reproducible analysis in Python
* Use Python to import, create, manipulate and analyze spatial data in different formats
* Use Python to extract valuable insight from spatial and tabular data  
* Visualize data and create (interactive) maps using Python  
* Independently research and debug code-related issues  


## Course Format
This course meets once a week in the GIS lab for approximately 3.5 hours. Classes will follow a format where the basic class material is introduced during a brief presentation and the class material is continued to be explained and learned during the hands-on demonstrations and class exercises. Homework will be assigned after most sessions to reinforce what we have covered in class, and to give you the opportunity to work with the concepts and applications so you can truly learn them. Assignments will constitute the largest portion of your grade.    

All homework assignments are due at the beginning of class. Assignments not turned in at that time will be penalized 25% from the original total grade for each day the assignment is not handed in: 
* Handed in at the beginning of class, max possible grade is 100%
* Not handed in at the beginning and up to 1 day late, max possible grade is 75%
* Two days late, max possible grade is 50%
* Three days late, max possible grade is 25%
* Four days late: 0%, and participation grade is impacted

Questions about the assignments should be asked well before the deadline for assignment. Before reaching out to your fellow students or the instructor for code-related help, make sure that you did your best effort and researched the question first on your own. Independent research and debugging is very important skill and it is one of our learning objectives for this class. 

## Assessment and Grading 
Grades will not be curved, but your lowest assignment grade will be dropped before calculating your final grade. Class participation includes engagement in discussions and answering the questions during lectures and demonstrations. Class participation on Slack is also counted towards your participation grade. Lateness and absences will count against your participation grade.

**Grade Weighting**  
*  60% Homework Assignments 
*  20% Final Assignment  
*  10% Midterm Quiz  
*  10% Participation    

**Grade Scale**
*  A 93-100, A- 90-92  
*  B+ 87-89, B 83-86, B- 80-82  
*  C+ 77-79, C 73-76, C- 70-72  
*  F < 70  

## Midterm 
The midterm will be in-class and include material covered in lectures, readings, and assignments. It will be a combination of small coding challenges and short type-in answers.   

## Final Assignment 
The final project will be a Python script created by you and should be functioning properly by the last day of class. The project will be based on your individual interests and goals and you can choose yourself what Python packages/modules you want to use. Your project should be *reproducible*. That means that all the steps in your project, including data cleaning, analysis, and vizualizations should be done in Python and I should be able to reproduce it by running your script(s). Good code documentation and adhereing to the best programming practices will be highly regarded and will affect positively in the grading of your final project. 

## Weekly Schedule 

Class #   |Day    |Topics |Do/Read before class |Due Assignment|
---------|-------|-------|---------|-----------|
1|Jan 30 | Course overview, software installations, IDEs: Spyder & Jupyter Notebook, My first Python Script|Python for Everybody: Ch 1||
2|Feb 6  | Variables and Types, Flow Control and Iterations| Python for Everybody: Ch 2, 3 & 5 |Assignment 1: My Intro Script|
3|Feb 13 | Lists, Tuples & Dictionaries, Sets; reading binary files|Automate the Boring Stuff with Python: Ch 4 & 5, Ch 8 (up to the section *Saving Variables with the shelve Module*), & Ch 14|Assignment 2|
 |Feb 20 |Classes follow a Monday schedule|| |
4|Feb 27 | Functions, Lambda operator & list comprehension; Pythonic Code|1. Automate the Boring Stuff with Python: Ch 3, [2. LearnPython.org List Comprehension](https://www.learnpython.org/en/List_Comprehensions), [3. Lamda](https://www.python-course.eu/python3_lambda.php)|Assignment 3|
5|Mar 6  |Intro to Pandas, Data wrangling w. Pandas |[1.Read Greg Reda post: Intro to pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/), [2. watch 10 minute tour of pandas](https://vimeo.com/59324550) | Assignment 4|
6|Mar 13 | Spatial Data Model & Shapely|[Shapely User Manual](http://shapely.readthedocs.io/en/stable/manual.html)|Assignment 5|
7|Mar 20 | Midterm Review; Working with vector data in Python: Introduction to Geopandas|[Geopandas documentation](http://geopandas.org/)|Assignment 6 |
8|Mar 27| Midterm Quiz; More Overlay Operations with Geopandas|1. review previous reading [2. watch JuputerCon 2017 keynote](https://www.oreilly.com/ideas/design-for-reproducibility)|Assignment 7|
9|Apr 10 | Geocoding in Python and reading data from databases in Python| [1.Geopy documentation](http://geopy.readthedocs.io/en/1.11.0/), [2.get Google API](https://developers.google.com/maps/documentation/geocoding/get-api-key),  [3. read usage quota](https://developers.google.com/maps/documentation/geocoding/usage-limits)| Assignment 8|
10|Apr 17| Making (Web) Maps in Python: Matplotlib, folium|[Folium documentation](https://folium.readthedocs.io/en/latest/)|Assignment 9|
11|Apr 24| Routing and Network Vizualizations|[osmnx documentation](https://osmnx.readthedocs.io/en/stable/) |Assignment 10|
12|May 1 | Interactive Maps with Bokeh|[Bokeh documentation](https://bokeh.pydata.org/en/latest/)|Final project idea description|
13|May 8 | Working with raster data in Python: rasterio and rasterstats|[1.rasterio documentation](https://mapbox.github.io/rasterio/quickstart.html), [2. rasterstats documentation](http://pythonhosted.org/rasterstats/)|Final project pseudo-code|
14|May 15| Introduction to version control with Github. BYOL!!!|[1.create Github account](https://github.com/); [2. install Git (command line)](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)[3. read git - the simple guide](http://rogerdudler.github.io/git-guide/) Bring Your Own Laptop to class!|Work on your final project|
15|May 22| Final project presentations||Final Project|

## Course Policies 

* **Lateness and absences** 
Classes will start on time, and lateness or absence will count against your class participation grade unless there is an emergency or it is cleared with the professor in a timely fashion before class. If you miss a session, it is your responsibility to learn the missed material.

* **Cellphone and Computers use** 
Please use the computers only for class-related work. Don't browse social media, answer personal emails or visit shopping websites. We have a lot of material to cover and will be moving at fast pace. If you get distracted and miss the information, we won't have time to go back and explain it to you again. Please understand that the use of cellphones and other similar devices is not permitted during midterm.

* **Incompletes** 
A grade of incomplete will only be considered if you are clearly making a good faith effort to complete the course (i.e., attending regularly, participating in discussions) and have a good reason for not completing the work.  

* **Dropping** 
The last day to drop the course with the grade of “W” is April 16 (no refund).  

* **Academic dishonesty (as it applies to this course)** 
While looking for answers to your coding questions, you will find plenty of Python code on the web. It is ok to use snippets of the code you find in your work and as a matter of fact, one of the core Python principles is code reusability. However, you are strongly discouraged from copying and pasting functions or blocks of code in your work without understanding what they actually do. Instead, use others' code examples to learn and adapt the solutions to your own problems.
