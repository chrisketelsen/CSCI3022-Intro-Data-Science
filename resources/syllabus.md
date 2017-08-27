## CSCI 3022: Intro to Data Science with Probability and Statistics, Fall 2017

### Course Information 

* **Section 001**: MW 4-5:15am in MUEN E050 with Chris Ketelsen 
* **Section 002**: MW 4-5:15am in MUEN E131 with Dan Larremore 

* **Prerequisites**: 
	* C- or better in Calculus 2 
	* C- or better in CSCI 2270
	* ability (or willingness to learn) to program in Python 3 

* **Office Hours**: 
	* Chris: MW 2-3:30pm in ECOT 731 and F 11am-12pm by appointment
	* Dan: TBA

### Course Description 

Data scientists attempt to gain knowledge from complex datasets. The analysis of real world data sets almost always requires the ability to reason about uncertainty, and probability and statistics provide the mathematical and philosophical foundation for such reasoning.

In this course, we will learn foundational concepts in the fields of probability and statistics. We will learn both the mathematical and statistical theory, and learn to work with real data sets in Python. In particular, at the end of this course, you should be able to:

1. load a data set into Python, clean and munge the data, perform exploratory data analysis, and report on patterns and correlations in the data, 

2. compute and interpret various measures of central tendency, such as the mean, median, and mode; and measures of dispersion, such as variance, and standard deviation,

3. write the axioms of probability theory, prove basic theorems of probability theory, and apply those theorems to solve "real-world" problems involving chance events, 

4. estimate population parameters of interest by calculating point and interval estimates from a sample/data, 

5. perform statistical hypothesis tests, 

6. construct and perform diagnostics on simple linear, multilinear, and logistic regression models to make predictions and inferences about data, and 

7. construct basic data visualizations in Python and organize analyses, findings, and recommendations into easily interpretable reports in Jupyter Notebooks

Importantly, our aim in this course is to help you become proficient in the technical aspects of data analysis; but, we also aim to help you identify when certain techniques are justified, and when certain techniques might lead you astray.  

### Textbook 

We will use two supplementary texts for the course, both freely available online: 

- [A Modern Introduction to Probability and Statistics](https://link-springer-com.colorado.idm.oclc.org/book/10.1007%2F1-84628-168-7) by Dekking et al. 
- [Think Stats](http://greenteapress.com/wp/think-stats-2e/) by Downey

### Course Web Page 

[https://piazza.com/colorado/fall2017/csci3022](https://piazza.com/colorado/fall2017/csci3022)

This term we will be using Piazza for class discussion. The system is highly catered to getting you help fast and efficiently from classmates, the grader, and the instructor. **Rather than emailing me questions, I request that you to post your questions on Piazza**.  If your question is of a private nature, Piazza allows you to send me a private message. It is your responsibility to check the web page on a regular basis. Here you will find detailed information such as news, homework assignments and solutions, and instructor office hours. 

### Computing

A major component of this course is to learn modern, practical computing skills for data analysis.  Our two main tools will be Python 3 and Jupyter Notebooks.  It is estimated that around 50% of practicing data scientists do most of their analysis using Python (while the other roughly 50% use R, which we shall not speak of).  The Jupyter Notebook is a browser-based programming environment that allows you to seamlessly mix Python code (as well as many other languages), graphics, and exposition (in Markdown).  The Jupyter Notebook has become ubiquitous in the data science community for rapidly prototyping ideas and sharing them with colleagues and the rest of the world. 

It is strongly recommended that you install Python 3 and Jupyter on your local machine. By far, the easiest way to do this is by installing the [Anaconda](https://www.continuum.io/downloads) distribution of Python 3.6.  This distribution comes with many Python packages useful for data science and scientific computation in general. It also comes with Jupyter by default.

If you are unable (or unwilling) to install Anaconda on your personal machine then you may access and use Jupyter directly on the web through [Microsoft Azure Notebooks](https://notebooks.azure.com/).  You may create a free account using your CU email address and identikey password.  Note that while this is a convenient option for using Jupyter, there are a few quirks that make it less ideal than local installations.  In particular you are unable to store anything in your online workspace that is not a Jupyter notebook (this means you can't store data locally, for instance). 

Very frequently in class we will explore computational problems directly in Jupyter notebooks.  It is highly recommended that you bring a laptop with you to class, however it's perfectly acceptable that you team up with a classmate on a single computer. 

### Coursework 

**Homework**: Homework will be assigned roughly every two weeks and due by 5pm on Fridays on Moodle.  Assignments will be a mix of theoretical and computational problems.  The theoretical problems may include by-hand computations and simple proofs.  The computational problems will involve doing some analysis on data in Python.  All assignments will be completed and submitted in Jupyter Notebooks.  Please be mindful of due dates as late homework will **NOT** be accepted or graded. **Your lowest homework score will be dropped**. You are expected to write up your solutions neatly, with full explanations and justifications. You may discuss problems with your classmates, **but all work must be your own**.  See the **Collaboration Policy** below for more details. 

**Course Participation**: Occasionally we will solve a short (5-10 minutes) tutorial problem as a class either on paper which you will submit at the end of class, or as a quick Moodle quiz.  Your course participation grade will be determined by 80% of the given tutorial problems (e.g. if we give 10 tutorial problems we will drop two of them.)  Dropped tutorial problems are to account for routine absences like minor illnesses and other unavoidable events.  You may not make up tutorial problems except in very extreme circumstances.  Attempts to subvert the integrity of participation assignments will be considered an Honor Code violation and will be met with measurable consequences.   

**Exams**: There will be an in-class midterm on October 17th and a final exam given during the university scheduled final examination time.  The final exam will be **cumulative** but will emphasize material covered after the midterm. Note that due to university regulations, **final exams can only be rescheduled due to official university excused absences**.  Please plan your holiday travel accordingly.  

**Practicum**: You will be given a practicum during the last week of the semester.  This will be like a cumulative larger homework assignment where you show off all of the skills that you have learned in the course.  The practicum must be completed **completely independently**.  You may not discuss your solutions with anyone else in the class. 

### Grade Determination 

The overall grades will be based on a cumulative score computed from 

* The homework (35% of the grade)
* The score from class participation (5% of the grade)
* The midterm exam (20% of the grade)
* The final exam (25% of the grade)
* The practicum (15% of the grade)

Unless adjustments are necessary, letter grades will be assigned using the standard grading scale: 

| Letter | Raw Average |
|--------|-------------|
|     A  |   93-100    |
|     A- |   90-92     |
|     B+ |   87-89     |
|     B  |   83-86     |
|     B- |   80-82     |
|     C+ |   77-79     |
|     C  |   73-76     |
|     C- |   70-72     |
|     D+ |   67-69     |
|     D  |   63-66     |
|     D- |   60-62     |
|     F  |   00-59     |

### Collaboration Policy 

The collaboration policy is simple:

* **Inspiration is free**: you may discuss homework assignments with anyone. You are especially encouraged to discuss solutions with your instructor and your classmates.

* **Plagiarism is forbidden**: the assignments **and code** that you turn in should be written entirely on your own. While writing the assignment you are not allowed to consult any source other than textbooks, your own class notes or the posted lecture slides. Copying/consulting from the solution of another classmate constitutes a violation of the course's collaboration policy and the honor code and will result in an **F** in the course and a trip to the honor council.

* **Do not search for a solution on-line**: You may not actively search for a solution to the problem from the internet. This includes posting to sources like StackExchange, Reddit, Chegg, etc. 

* **When in doubt, ask**: If you have doubts about this policy or would like to discuss specific cases, please ask the instructor.

### Standard Course Policies 

**Honor Code**

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the [academic integrity policy](http://www.colorado.edu/policies/academic-integrity-policy) of the institution. Violations of the policy may include: plagiarism, cheating, fabrication, lying, bribery, threat, unauthorized access, clicker fraud, resubmission, and aiding academic dishonesty. All incidents of academic misconduct will be reported to the Honor Code Council (honor@colorado.edu; 303-735-2273). Students who are found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code Council as well as academic sanctions from the faculty member. Additional information regarding the academic integrity policy can be found at [www.colorado.edu/honorcode/](http://www.colorado.edu/honorcode/).

**Disability Accommodations**


If you qualify for accommodations because of a disability, please submit your accommodation letter from Disability Services to your faculty member in a timely manner (for exam accommodations provide your letter at least one week prior to the exam) so that your needs can be addressed.  Disability Services determines accommodations based on documented disabilities in the academic environment.  Information on requesting accommodations is located on the [Disability Services website](http://www.colorado.edu/disabilityservices/students).  Contact Disability Services at 303-492-8671 or [dsinfo@colorado.edu](dsinfo@colorado.edu) for further assistance.  If you have a temporary medical condition or injury, see Temporary Medical Conditions under the Students tab on the Disability Services website and discuss your needs with your professor.


**Religious Observances**

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments, or required attendance. If you have an exam or assignment conflict due to a religious observance please notify your instructor in a timely manner. See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.

**Classroom Behavior**

Students and faculty each have responsibility for maintaining an appropriate learning environment. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy.  Class rosters are provided to the instructor with the student's legal name. I will gladly honor your request to address you by an alternate name or gender pronoun. Please advise me of this preference early in the semester so that I may make appropriate changes to my records.  For more information, see the policies on [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [Student Code of Conduct](http://www.colorado.edu/osccr/).


**Sexual Misconduct, Discrimination, Harassment and/or Related Retaliation**

The University of Colorado Boulder (CU Boulder) is committed to maintaining a positive learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct, discrimination, harassment or related retaliation against or by any employee or student. CU's Sexual Misconduct Policy prohibits sexual assault, sexual exploitation, sexual harassment, intimate partner abuse (dating or domestic violence), stalking or related retaliation. CU Boulder's Discrimination and Harassment Policy prohibits discrimination, harassment or related retaliation based on race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy. Individuals who believe they have been subject to misconduct under either policy should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127. Information about the OIEC, the above referenced policies, and the campus resources available to assist individuals regarding sexual misconduct, discrimination, harassment or related retaliation can be found at the [OIEC website](http://www.colorado.edu/institutionalequity/).



