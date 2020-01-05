# Software Requirements Specification

# For Team 5

January 5, 2020

Version 1.0

Prepared by:

Team 5 ( Ramascanu Robert)

Table of Content

1. Introduction        4
  1. 1.About Moodle        4
  2. 2.Overview        4
  3. 3.Goals and Objectives        4
  4. 4.Scope        4

1. General Design Constraints        4
  1. 1.Product Environment        4
  2. 2.User Characteristics        5
  3. 3.Potential System Evolution        5
2. Nonfunctional Requirements        5
  1. 1.Operational Requirements        5
  2. 2.Performance Requirements        5
  3. 3.Security Requirements        5
  4. 4.Interface        5
3. Functional Requirements        5
  1. 1.Required Features        5
    1. 1.1.Use Case: 1        5
    2. 1.2.Use Case: 2        6
    3. 1.3.Use Case: 3        6

4.1.4.Use Case: 4        7

4.1.5.Use Case: 5        7

Revision History

| **Version** | **Date** | **Description** |
| --- | --- | --- |
| 0.1 | 30/03/19 | Starting of the project |
| 0.1 | 04/04/19 | Project Charter Approved |
| 0.1 | 10/04/19 | Development of the course structure |
| 0.2 | 15/04/19 | Implementation of the lessons |
| 0.3 | 21/04/19 | Implementation of the quiz |
| 0.4 | 28/04/19 | Writing of User Guide and System Administrator Manual |
| 1.0 | 25/05/19 | Product released |

1. 1.Introduction
  1. 1.About Moodle

Moodle is a learning platform designed to provide educators, administrators andlearners with a single robust, secure and integrated system to create personalised learning environments. You can download the software onto your own web server or ask one of our knowledgeable Moodle Partners to assist you.

Moodle is built by the Moodle project which is led and coordinated by Moodle HQ, which is financially supported by a network of over 80 Moodle Partner service companies worldwide.

1.
  1. 2.Overview

The Moodle platform has given the possibility to our team to create an English course in a very short time, precisely because it is an IT environment for course management.

Project constraints will be included in separate documentation.  The Software Project Management Plan will give specifics on project budget and schedule.  A separate Test Plan document will address  test specifications and procedures.

1.
  1. 3.Goals and Objectives

The main objective is to provide school students with a platformwhere they can increase their English language skills and learn from our lessons in asimple and intuitive manner.

1.
  1. 4.Scope

The English course will provide users with the ability to access these courses from any device. Students will be able to run and check how many courses and quizzes they have already taken, and furthermore, students can at any time take quizzes or review lessons in which they do not feel confident enough, and therefore improve their weaknesses.

1. 1.General Design Constraints
  1. 1.Product Environment

The English course will reside on the Moodle platform, administrators will be able to create new quizzes and lessons thanks to the simple features that this platform offers.

1.
  1. 2.User Characteristics

Students - Students attending a secondary school with basic English skills.

Teachers - English teachers who have at least a B2 certification in the English language.

Administrators - People who have computer skills to create an English course.

1.
  1. 3.Potential System Evolution

In the future with a new version of Moodle, the English course will be updated in the following ways:
1. New lessons and quizzes will be added.

1. 2.Nonfunctional Requirements
  1. 1.Operational Requirements

To run this courseis needed asimple webbrowser.The platform isonline so there isno need of highperformancehardware on theuser pc.

1.
  1. 2.Performance Requirements

No performance requirements have been identified for this application.

1.
  1. 3.Security Requirements

Within this course only the administrator user will have the possibility to modify or create new quizzes and lessons. The administrator will also take care of authorizing students to participate in the course and view the information.

1.
  1. 4.Interface

In general the user interface will be designed so that it is intuitive and can be used by the average computer user.

1. 3.Functional Requirements
  1. 1.Required Features
    1. 1.Use Case: 1

**Description: User Login**

Actors: Student, Teacher or Administrator

Basic Path

1. Go to the course login page.
2. Insert your username.
3. Insert your password.
4. Press enter.

1.
  1.
    1. 2.Use Case: 2

**Description:**  **Create a Lesson**

Actors: Administrator or Teacher

Basic Path

1. Go to the English course.
2. As soon as you enter, press the gear in the upper right corner.
3. Active &quot;Editing&quot; mode.
4. Then scroll to the bottom of the page and press on the text &quot;+ Add an activity or resource&quot;.
5. Add a Lesson from the list of activities.
6. Set the settings and click on &quot;Save and return to course&quot;.

Once you create a lesson you will need to add some content. To do this follow this path:

1. First go back to the previous page where the lesson just created appears.

1. Pressing on it should appear: Import question, Add a cluster, Add a content page and Add a question page.
2. Choose what you want.

1.
  1.
    1. 3.Use Case: 3

**Description:**  **Create a Quiz**

Actors: Administrator or Teacher

Basic Path

1. Go to the English course.

1. As soon as you enter, press the gear in the upper right corner.
2. Active &quot;Editing&quot; mode.
3. Then scroll to the bottom of the page and press on the text &quot;+ Add an activity or resource&quot;.
4. Add a Quiz from the list of activities.
5. Now click on &quot;Edit quiz&quot;.

### 4.1.4.Use Case: 4

**Description:**  **A**** dd a database of questions**

Actors: Administrator or Teacher

Basic Path

1. If you want to add a question to a database just open any quiz and click on the settings.

1. In the drop-down list select &quot;Question bank&quot;.
2. Then click on the &quot;Create a new question&quot; button.



### 4.1.5.Use Case: 5

**Description:**  **Restore**

Actors: Administrator

Basic Path

1. We should first create and rename the course as we please.

1. Select the settings wheel and then click on &quot;Restore&quot;.
2. Select backup file and then upload it.
3. Select in the first box &quot;miscellaneous&quot; and in the second &quot;Delete the contents of this course and then restore&quot; and click continue.
4. In the items that will appear later, remove the check from the item &quot;Include enrolled user&quot; and &quot;include groups and groupings&quot;.
5. Select YES in Overwrite course configuration and finally click on Restore.