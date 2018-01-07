
# Course Syllabus* : Introduction to Programming for GISs, Spring 2018
*last Updated: 01/06/2018 

**Instructor:** Anastasia Clark  
**E-mail:** anastasiapotupalova@gmail.com  
**GitHub:** https://github.com/anastasiaclark   
**Course meetings:** Gillet Hall, Rm. 322 (GISc Lab) on Tuesdays 6:00 pm to 9:30 pm 

## Readings
There isn't a comprehensive text book for this course. We will use a combination of freely avalable books, blogs, videos and Python packages documentation as our study materials. Chapters will be asigned from below books; other readings will be linked   in the readings section of the [weekly schedule breakdown](#weekly-schedule)

* Automate the Boring Stuff with Python
    https://automatetheboringstuff.com/
    
* Python for Everybody
https://books.trinket.io/pfe/index.html
    
* LearnPython.org interactive Python tutorials
    https://www.learnpython.org/
    

**Recommended books on Python programming & GIS:** 
* Lawhead, J. (2015) Learning Geospatial Analysis with Python: An effective guide to geographic information systems and remote sensing analysis using Python 3, Second edition. Packt Publishing. https://www.packtpub.com/application-development/learning-geospatial-analysis-python-second-edition  
* McKinney, W. (2012) Python for Data Analysis: Data wrangling with Pandas, NumPy and iPython, First edition. O´Reilly Media. http://shop.oreilly.com/product/0636920023784.do

## Software
For this cource, we will primarily use the [Anaconda's distribution of Python 3](https://www.anaconda.com/download/). We will utillize two Python Development Environments, [Spyder](http://pythonhosted.org/spyder/) and [Jupyter Notebook](http://jupyter.org/). For some on-line tutorials and our very first class, we will use the standard Python 2.7 installation from ArcGIS. All the software is installed on the lab's computers. To install Anaconda and the required packages on your personal machine, [follow this instructions](https://github.com/anastasiaclark/GEP662_Spring2018/blob/master/installations.md#install-anacondas-distribution-of-python-on-your-machine).

## Learning Objectives
After successfully completing this course, you are expected to be able to:

* Understand fundamental programming concepts  
* Understand basics of working with data in Python    
* Use Python to import, create, manipulate and analyze spatial data in different formats
* Use Python to extract valuable insight from spatial and tabular data  
* Visualize data and create (interactive) maps using Python  
* Independently research and debug code-related issues  


## Course Format
This course meets once a week in the GIS lab for approximately 3.5 hours. The course will typically begin with class lecture and discussion, followed by hands-on exercises. For shorter topics we will pivot back and forth between class lecture / discussion and exercises. Homework will be assigned after most sessions to reinforce what we have covered in class, and to give you the opportunity to work with the concepts and applications so you can truly learn them. Assignments will constitute the largest portion of your grade.    

All homework assignments are due at the beginning of class. Assignments not turned in at that time will be penalized 25% from the original total grade for each day the assignment is not handed in: 
* Handed in at the beginning of class, max possible grade is 100%
* Not handed in at the beginning and up to 1 day late, max possible grade is 75%
* Two days late, max possible grade is 50%
* Three days late, max possible grade is 25%
* Four days late: 0%, and participation grade is impacted

Questions about the assignments should be asked well before the deadline in order to give the instructor time to resolve the questions with the student. Before reaching out to the instructor for code-related help, make sure that you did your best effort and researched the question first on your own. Independent research and debugging is very important skill and it is one of our learning objectives for this class. 

## Assessment and Grading 
Grades will not be curved and no grades will be dropped. Class participation includes engagement in discussions and answering the questions during lectures and demonstrations. Lateness and absence will count against participation grade.

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


## Midterm Quiz 
The midterm quiz will be in-class and include material covered in lectures, assigned readings, and assignments. The quiz will be a combination of multiple choice questions and short write-in answers.  

## Final Assignment 
The final assignment will be a Python script created by you and should be functioning properly by the last day of class. This assignment will be based on your individual interests and goals and you can choose yourself what packages/modules you want to use, but you are required to include at least **three** of the following components in your script:
* Data munging and cleaning
* Geocoding
* Overlay operations and table joins
* Linestrings or polygons creation from set of points/coordinates (not as a result of overlay operations)
* Spatial Joins
* Raster Analysis
* Maps and other vizualizations
* more...

Your analysis should reproducible and well-documneted. Adhereing to the best programming practices will be highly regarded and will affect positively in the grading of your final assignment. 

## Weekly Schedule 

Class #   |Day    |Topics |Do/Read before class |Due Assignment|
---------|-------|-------|---------|-----------|
1         |Jan 30 |Python Basics: Variables & Types; Interpreters: Spyder & Jupyter Notebook|Python for Everybody: Ch 1||
2|Feb 6|Python Data Structures & Control Flow|Automate the Boring Stuff with Python: Ch 2,3 & 4|Assignment 1: My Intro Script|
3|Feb 13|Python Basics: Dictionaries & More Custom Functions |Automate the Boring Stuff with Python: Ch 5,  Python for Everybody: Ch4|Assignment 2|
|Feb 20|Classes follow a Monday schedule|| |
4|Feb 27|Intro to Pandas|[Greg Reda post: Intro to pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/) | Assignment 3|
5|Mar 6|Data wrangling w. Pandas| https://vimeo.com/59324550, Python for Data Analysis: Ch 7 (handout)|Assignment 4|
6|Mar 13| Midterm Review; Spatial Data Model & Shapely|[Shapely User Manual](http://shapely.readthedocs.io/en/stable/manual.html)|Assignment 5|
7|Mar 20| Midterm; Working with vector data in Python: Introduction to Geopandas|[Geopandas documentation](http://geopandas.org/)|Assignment 6 |
8|Mar 27|More Overlay Operations with Geopandas and reading data from databases|reading|Assignment 7|
9|Apr 10| Geocoding in Python|[Geoclient API documentation](https://api.cityofnewyork.us/geoclient/v1/doc) and [create NYC developer account](https://developer.cityofnewyork.us/user/register?destination=user/login)| Assignment 8|
10|Apr 17|Making Maps in Python: Matplotlib, folium||Assignment 9|
11|Apr 24|Interactive Maps with Bokeh||Final Assignment Idea Description|
12|May 1|Workinng with raster data in Python: GDAL, NymPy, rasterio||Final Assigment pseudo-code|
13|May 8|Spatial weights with PySAL||Work on your final assignment|
14|May 15|ESDA with PySAL||Work on your final assignment|
15|May 22|Introduction to version control: Git and Github||Final Assignment|


## Course Policies 

* **Lateness and absences** 
Classes will start on time, and lateness or absence will count against your class participation grade unless there is an emergency or it is cleared with the professor in a timely fashion before class. If you miss a session, it is your responsibility to check with your classmates for notes and other course materials.  

* **Cellphone and Computers use** 
Please use the computers only for class-related work. Don't browse social media or shopping webistes. We have a lot of material to cover and will be moving at fast pace. If you get distracted and miss the infomration, we won't have time to go back and explain it to you again. Please understand that the use of cellphones and other similar devices is not permitted during midterm and quizes.

Since the lectures take place in a computer lab, the following additional rules apply:
 * Absolutely NO drinking or eating of any kind in the lab
 * No printing of any materials without permission from the instructor or the lab manager  

* **Incompletes** 
A grade of incomplete will only be considered if you are clearly making a good faith effort to complete the course (i.e., attending regularly, participating in discussions) and have a good reason for not completing the work.  

* **Dropping** 
The last day to drop the course with the grade of “W” is April 16 (no refund).  

* **Academic dishonesty** 
Academic dishonesty will not be tolerated.  Academic dishonesty includes, but is not limited to, cheating, plagiarizing (including “cutting and pasting” or paraphrasing information from the internet without proper citation), fabricating information or citations, facilitating acts of academic dishonesty by others, submitting work of another person or papers written for other courses, or tampering with the academic work of other students.  Students may be asked to submit their notes and references to prove that their work is their own. For further clarification, please read CUNY's policy on academic integrity at http://www.lehman.edu/provost/documents/academic-integrity.pdf. Violators will be reported to the head of the Department and to the Dean of Student Affairs.   
 
* **Accommodation for Students with Disabilities** 
Lehman College is committed to providing access to all programs and curricula to all students.  Students with disabilities who may need classroom accommodations are encouraged to register with the Office of Student Disability Services.  For more information, please contact the Office of Student Disability Services, Shuster Hall, Room 238, tel #: 718-960-8441.  

**The Academic Center for Excellence (ACE) and the Science Learning Center (SLC)**
Lehman College has two tutoring centers on campus.  The ACE provides appointment-based and drop-in tutoring in the humanities, social sciences and writing, as well as general writing skills.  The SLC provides drop-in tutoring for natural and computer science courses.  To obtain more information about the ACE and SLC, please visit their website at http://www.lehman.edu/issp, or please call the ACE at 718-960-8175, and the SLC at 718-960-7707.  
