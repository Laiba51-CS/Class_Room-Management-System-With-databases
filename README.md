# Class_Room-Management-System-With-databases
## Introduction:
Class Management system  provide real-time data that enables universities to monitor and evaluate student progress accurately. Implementing  these systems for managing student projects in universities can enhance efficiency, accuracy, and student success, making them a valuable investment for any institution. The system is designed to be user-friendly, with an intuitive interface that allows users to easily add or delete students, update their data, and view attendance information. Additionally, the system can be customized to meet the specific needs of different classes or departments, making it a versatile tool for managing student attendance and other aspects of class management.Overall, the system offers a comprehensive solution for managing student attendance and other class-related issues.  It is an essential tool for universities looking to streamline their processes and improve student success.The system allows for the storage and tracking of assessment data, making it easy to generate reports on student performance in different assessments. These reports can be customized to display results for specific assessments, such as exams or assignments, and can be exported as PDF.


## Graphical User Interface

| Manage students | Managing Attendance |
|---------------------------|---------------------|
| ![GUI](https://github.com/Laiba51-CS/Class_Room-Management-System-With-databases/assets/115210630/95488da4-ac88-4515-b3de-ae1c07e87ff3) | ![Attendance](https://github.com/Laiba51-CS/Class_Room-Management-System-With-databases/assets/115210630/932ddbbc-e604-4667-ae9c-1c36130b11d6) |

| Managing Results | Generating Reports |
|------------------|--------------------|
| ![Results](https://github.com/Laiba51-CS/Class_Room-Management-System-With-databases/assets/115210630/5f87803e-626d-4c55-9022-1fb12281a947) | ![Reports](https://github.com/Laiba51-CS/Class_Room-Management-System-With-databases/assets/115210630/d1f6bdf2-e6f2-4258-b3cd-3264748de497) |

| Reports View | Result Report |
|------------------|--------------------|
| ![Results](https://github.com/Laiba51-CS/Class_Room-Management-System-With-databases/assets/115210630/76fad7c9-b203-4140-9f30-6ae856bbf5d9) | ![Reports](https://github.com/Laiba51-CS/Class_Room-Management-System-With-databases/assets/115210630/9788c1ae-903b-4555-b6dc-dd3a6759d9f1) |




## Database Explaination:

###### Assessment Table :
unique ID, a title, a date of creation, a total number of marks, and a total weightage. It is used to evaluate the performance of students in a specific course.
###### ClassAttendance:
Class attendance has a unique ID and a date that represents the attendance of students in a class
###### Clo: 
A course learning outcome (CLO) has a unique ID, a name, a date of creation, and a date of update. It represents the knowledge and skills that students are expected to acquire during a course
###### Rubric:
A rubric has a unique ID, details, and a CLO ID. It is used to evaluate the performance of students based on a predefined set of criteria.
###### RubricLevel: 
A rubric level has a unique ID, a rubric ID, details, and a measurement level. It represents the level of achievement of the student based on the rubric.
###### Student:
A student has a unique ID, a first name, a last name, contact information, an email address, a registration number, and a status. It represents a person who is enrolled in a course
###### Lookup: 
A lookup has a unique ID, a name, and a category. It is used to store a list of predefined values that can be used in various parts of the system.
###### StudentAttendance: 
Student attendance has an attendance ID, a student ID, and an attendance status. It represents the attendance status of a student in a particular class.
###### StudentResult:
A student result has a student ID, an assessment component ID, a rubric measurement ID, and an evaluation date. It represents the evaluation result of a student's performance in an assessment component.

<img src="https://github.com/Laiba51-CS/Class_Room-Management-System-With-databases/assets/115210630/55226b4f-3239-498d-9364-f02ea62a7353" alt="Image Alt Text" width="600" height="400">


 
