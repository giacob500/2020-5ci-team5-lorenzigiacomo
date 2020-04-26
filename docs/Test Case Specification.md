# Test Case Specification for Team 5

February 3, 2020

Prepared by:

Giacomo Lorenzi

## **Table of Content**

**1 INTRODUCTION**

**2 TEST CASES: ENGLISH COURSE ON MOODLE**

## 1) Introduction

This document provides the test cases to be carried out for the English Course on Moodle. Each item to be tested is represented by an individual test case. Each case details the input and expected outputs.

## 2) Test Cases: English Course on Moodle

| Test ID | 1.0 |
| --- | --- |
| Title | Quizzes Test |
| Feature | Complete a Quiz |
| Objective | Confirm the operability of the quiz. |
| Setup | The course made by us has inside the quizzes made by us |
| Test Data | Login as student |
| Test Actions | 1. Start a lesson and complete it2. Enter the quiz page3. Enter a response4. Check if the quiz tells you the right answer |
| Expected Results | System displays the correct answer and tells you if you respond correctly, if you didn&#39;t it tells you the right response. |

| Test ID | 2.0 |
| --- | --- |
| Title | Incorrect Password |
| Feature | Login to [https://campusmarconiverona.moodlecloud.com/login/index.php](https://campusmarconiverona.moodlecloud.com/login/index.php) |
| Objective | Confirm that valid user id with an invalid password denies access to the website without leaving the user stranded |
| Setup | The device simulator has a working internet connection to run. |
| Test Data | Correct user e-mail, incorrect passwordUser Email = [17876@studenti.marconiverona.edu.it](mailto:17876@studenti.marconiverona.edu.it)Password = \*\*\* |
| Test Actions | 1. Start web browser 2. Surf to the webpage 3. Enter invalid login information |
| Expected Results | System displays error message with option to try again. |

| Test ID | 3.0 |
| --- | --- |
| Title | Using a Lesson |
| Feature | It teaches the subject for which the course is made |
| Objective | Verify that a student learns the lesson |
| Setup | The device simulator has a working internet connection to run. |
| Test Data | A student reads and learns the lesson |
| Test Actions | 1. Start web browser 2. Surf to the webpage 3. Enter valid login information 4. Study the lesson |
| Expected Results | The lessons are effective and the student understands the contents |
