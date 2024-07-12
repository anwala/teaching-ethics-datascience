<img align="left" width="120" height="120" src="https://github.com/anwala/teaching-web-science/blob/main/fall-2022/wm_vertical_stacked_full_color.png" alt="wm_vertical_stacked_full_color">

# W&M DATA 641-01/445-01 - Network Analysis, Spring 2024 Syllabus

[Jump to Summary Schedule](#summary-schedule) | [Self](https://github.com/anwala/teaching-network-analysis/blob/main/spring-2024/syllabus.md)

## Course Overview

Networks are everywhere in our lives: networks of friends on social media, the Web, networks of neurons in our brains, etc. It's amazing that such a simple representation --- dots and lines --- can capture a variety of relationships, whether simple or complex.

**Catalog Description:** In this course, we will survey a broad range of fundamental topics in network science, relevant to students from data/computer science and engineering, informatics, business, biology, physics, statistics, social sciences, etc. For example, we will explore the properties of social networks and the key role of hubs, and how directed and weighted networks affect the spread of information and misinformation in social media. These topics are important and useful in many job sectors from marketing to technology, management to design, and from biology to the arts and humanities. 

**Prerequisites:** DATA 301 OR MATH 351/352 OR MATH 451/452

## Course Venue and Time

Integrated Science Center, room 0280. Tuesdays/Thursdays 11am -– 12:20 pm

## Instructor Contact and Office Hours

Dr. Alexander C. Nwala
* Email: acnwala at wm.edu, 
* Website: <https://alexandernwala.com/>
* [Office hours](https://alexandernwala.com/contact/)

## Course Objectives

After completing this course, you should be able to do the following:

* Explain the [fundamental concepts of networks](https://sites.google.com/a/binghamton.edu/netscied/teaching-learning/network-concepts)
* To load, manipulate, export, and visualize networks using tools and programming languages such as Python/NetworkX, and Gephi
* Describe the structural components and properties of a network (e.g., nodes, links, degree, connectivity, sparsity, paths, etc.)
* Identify and explain various network phenomena such as small-worlds and homophily 
* Explain network structure and various algorithms on the Web, (e.g., PageRank used by search engines to rank Webpages)
* Utilize node centrality measures and their distributions to identify the most important nodes in a network and describe their roles
* Explain important properties of real-world networks (e.g., heterogeneous distribution of node/link properties, small-world)
* Explain the fundamental concepts of community detection and utilize community detection algorithms
* Explain fundamental network models and their flaws (e.g.,Erdös-Renyi Random Graph Model, Watts–Strogatz Small-world model)
* [Synthesize and apply critical analysis, solve problems in the Networks domain, create original material or original scholarship, and communicate effectively with diverse audiences.](https://web.archive.org/web/20231226205314/https://www.wm.edu/as/undergraduate/coll/400/)
* Cultivate an appreciation of the wide applicability of network science to many domains, including the Web and social media, biology, and business.
* Etc.

## Requirements

### Prerequisites

Prerequisites: Student should have taken DATA 301 OR MATH 351/352 OR MATH 451/452 OR approval from the instructor.

We will be using Python this semester. You are not required to know Python ahead of time, but since *you are required to have previous programming experience*, I expect you to be able to pick up the syntax quickly. If you are unfamiliar with Python, I strongly suggest that you spend a bit of time with it before the semester begins.

Here are some good Intro to Python resources:

* [Python Tutorial](https://www.w3schools.com/python/default.asp)
* [Introduction to Python](http://introtopython.org/)
* [CS 1110: Introduction to Computing Using Python](http://www.cs.cornell.edu/courses/cs1110/2012fa/) (Cornell University)
* [A Gentle Introduction to Programming Using Python](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2011/lectures/) (MIT)
* [Python Track: Introduction](http://courses.cms.caltech.edu/cs11/material/python/index.html) (Cal Tech)
* [Python in One Easy Lesson](http://www-cs-faculty.stanford.edu/~nick/python-in-one-easy-lesson/), Nick Parlante

### Textbook

The recommended textbook for this class is: 

> Menczer, F., Fortunato, S., & Davis, C. (2020). [A First Course in Network Science](https://www.amazon.com/First-Course-Network-Science/dp/1108471137). Cambridge: Cambridge University Press. doi:10.1017/9781108653947

Reach out to me if you're unable to get a personal copy. See also,

> [Textbook Github account](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience)

I also recommend:

> Barabási, A., (2016). [Network Science](http://networksciencebook.com/). Cambridge: Cambridge University Press. doi:10.1098/rsta.2012.0375

## Grading

There will be a total of **94 points** (50 points for assignments, 30 points for final exam (no midterms), 20 points for participation), and **4 extra** credits points. I'd advise you to do as many extra credits as possible. Consider them as a safety net.

### Assignment Types

I will post all assignments on our DATA 641-01 Piazza forum. Your grade in this class will be based on the following components:

**Homework (HW)** - **50** points

* 5 homework assignments (HW0 -- HW4), each worth 10 points
* *Don't wait until the last minute --- some are hard and time-consuming!*
* All work must be your own. You may use resources (e.g., Stack Overflow) on the Internet for reference. If you use online resources, you must cite your sources (including URL). Group work on HW assignments is not acceptable.

**Participation/Attendance** - **20** points

Participation is very important, it improves learning and contributes additional dimensions to discussions. I'd encourage participation by assigning scores to the following activities throughout the semester:
* 2 point maximum per week: Unannounced in-class quizzes

**No Midterm exam**

**Group project (final exam)**- **30** points

**Extra-credit points** - *4* points

### Graduate students (DATA 641-01)

Graduate students are expected to implement the final exam individually while undergraduate students (DATA 445-01) are allowed to form groups.

### Grading Scale

| Numerical Grade | Letter Grade | | Numerical Grade | Letter Grade |
| --- | --- | --- | --- | --- |
| 93% -- 100%| A | | 73 -- 76 | C |
| 90 -- 92 | A- | | 70 -- 72 | C- |
| 87 -- 89 | B+ | | 67 -- 69 | D+ |
| 83 -- 86 | B| | 63 -- 66 | D |
| 80 -- 82 | B- | | 60 -- 62 | D- |
| 77 -- 79 | C+ | | 00 -- 59 | F |

## Summary Schedule

*Note: This is a tentative schedule and may change during the semester.*

[W&M Spring 2024 academic schedule](https://www.wm.edu/offices/registrar/calendarsandexams/ugcalendars/index.php#spring)

|Module |Lecture Dates|Topic
|---|---|---|
|1|Jan 25          | Introductions                        
|2|Jan 30 & Feb 1  | Network Elements                     
|3|Feb 6 & 8       | Network Analysis toolkit             
|4|Feb 13 & 15     | Small Worlds                         
|5|Feb 20 & 22     | Node centrality (importance) metrics 
|6|Feb 27/29 & Mar 5 | Link Analysis                      
|7|Mar 7           | Network Visualization                
| | Mar 9 -- 17    |**NO CLASS - Spring Break**           
|8|Mar 19 & 21     | Erdös-Renyi Random Graph Model       
| | Mar 25         |*Withdrawal deadline*                 
|9|Mar 26 & 28     | Small world models                   
|10|Apr 2 & 4      | Preferential attachment models       
|11|Apr 9 & 11     | Communities                          
|12|Apr 16 & 18    | Building [StoryGraph](https://web.archive.org/storygraph/) 
|13|Apr 23 & 25    | Modeling social media behaviors with [BLOC](https://doi.org/10.1140/epjds/s13688-023-00410-9) 
|14|Apr 30 & May 2 | Group project status updates/Q&A
|  | Fri, May 3    |*last day of classes*            
|15| Tue, May 14 (2pm ET) | Final exam                                 


### Add/drop and withdrawal deadlines:
* Add/drop deadline: February 2, 2024
* Withdrawal deadline: March 25, 2024

## Course History

This course was originally developed by my Post-doc supervisor [Dr. Filippo Menczer](https://cnets.indiana.edu/fil/).
I taught an undergraduate section of this course [Spring 2023](https://github.com/anwala/teaching-network-science/blob/main/spring-2023/README.md). 

The current edition heavily borrows content/structure from,
* Filippo Menczer, Santo Fortunato, and Clay Davis @ Indiana University
* Pedro Ribeiro @ UPorto
* Jure Leskovec @ Stanford University
* Andrew Beveridge @ Macalester College

## Course Policies

### Piazza

Each student must check the class [Piazza (DATA 641-01/445-01)](https://piazza.com/class/lqmv9jitawl3a4/) daily. You should use our class Piazza forum to ask and answer general course-related questions. I will use Piazza to notify you about important updates (assignment deadline changes, office hours cancellations, etc.).

### Participation

Regularly stay involved in class activities. This includes checking Piazza for announcements, submitting assignments on time, and responding to discussion posts in a timely manner.

### Seeking Help

The course Piazza forum should be your first reference for questions about the class. If you have questions about the course requirements or materials, post your questions on Piazza. For extra help, attend [office hours](https://alexandernwala.com/contact/).

### [Student Accessibility Services](https://www.wm.edu/offices/deanofstudents/services/studentaccessibilityservices/)

W&M's Student Accessibility Services offer a variety of services (e.g., [Watson Lab](https://www.wm.edu/offices/deanofstudents/services/studentaccessibilityservices/students/services/watsonlab/index.php) and [special needs housing](https://www.wm.edu/offices/deanofstudents/services/studentaccessibilityservices/students/services/specialhousing/index.php)) for William & Mary students.

The mission of Student Accessibility Services is to create a barrier-free environment for matriculating students with debilitating diagnosed conditions by considering reasonable accommodations upon request on an individual and flexible basis. 

Student Accessibility Services strives to foster student independence, to encourage self-determination, to emphasize empowerment and accommodation over limitation, and to create a comprehensive, accessible environment to ensure that individuals are viewed on the basis of contribution, not deficit.

## W&M's [Honor Code](https://www.wm.edu/offices/deanofstudents/services/communityvalues/studenthandbook/honor_system/index.php)

Among the most significant traditions of William & Mary is its student-administered honor system. The essence of the honor system is individual responsibility. We entrust students to maintain the Code and adjudicate matters involving alleged violations of the Code.

The Honor Code is an enduring tradition at the University with documented history that originates as far back as 1736. Today, students administer the Honor pledge to each incoming student and educate faculty and administration on the relevance of the Code and its application to students' lives at the University. Students administer the Code through six Honor Councils and the Council of Chairs.

The Honor Code prohibits lying, cheating, and stealing. For definitions of each offense, view [Section VI: Infractions](https://www.wm.edu/offices/deanofstudents/services/communityvalues/studenthandbook/honor_system/section_VI/index.php) of the Honor Code.
* **Lying:** the presentation of false information with the intent to deceive.
* **Cheating:** including, but not limited to, the following acts: 
  * Plagiarism
  * Unauthorized Assistance/Collaboration
  * Use of Unauthorized Materials
  * Unauthorized Dual Submission of Previous Academic Work
  * Time Constraint Violation
  * Directions Violation
* **Stealing:** knowingly taking or appropriating the property of another, including property of the university, without the rightful owner’s permission and with the intent to deprive the owner of the property permanently or substantially. One does not receive rightful permission if it is induced by fraud or deception.

## Mental health and Statement from W&M's Counseling Center

### Mental and physical health
If you or someone you know is experiencing psychological/emotional stress, we encourage you to reach out: [W&M Counseling Center](https://www.wm.edu/offices/wellness/counselingcenter/) (757 221 3620, 240 Gooch Dr. 2nd floor). Services are free and confidential. For physical/medical concerns, please reach out to the [W&M Health Center](https://www.wm.edu/offices/wellness/healthcenter/) or call (757) 221-4386, 240 Gooch Drive. If you or someone you know is in need of additional support or resources, please contact the Dean of Students by submitting a [care report](https://www.wm.edu/offices/deanofstudents/services/caresupportservices/index.php), by phone at (757) 221-2510, or by email at deanofstudents@wm.edu.

### Statement from W&M's Counseling Center
The William & Mary [Counseling Center](https://www.wm.edu/offices/wellness/counselingcenter/students/index.php) is one of the resources made available to you through the [Division of Student Affairs](https://www.wm.edu/about/administration/senioradmin/studentaffairs/index.php). Its primary purpose is to support the mental health and emotional wellness of the community by providing education outreach programming, targeted prevision activities, and intervention services specifically designed for college students. 

The center offers individual, couples and group counseling as appropriate to student needs. We also provide referrals to other resources within the university or the local community that help to support student health and wellness. We are invested in your personal and academic success during your time at W&M, and throughout your life.
