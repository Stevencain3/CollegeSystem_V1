# Chapters 10 & 11 | Design and Create College Database V1
___

## Overview
___
This repository contains the first version of our College Database design using MySQL Workbench (EER Diagram + Forward Engineering).
    It models a simplified college environment with students, faculty, admins, courses, semesters, rooms, enrollment, and grades.
    
## This database includes the following core entities
___
* User - stores all individuals (students, admins, faculty) with roles.
* Department - academic departments offering courses.
* Semester - academic terms (e.g., Fall 2025).
* Course - connected to a semester, section, and assigned faculty.
* Room - classrooms with seating capacity constraints.
* Enrollment - mapping of students to courses.
* GPA - each student's grades
* Faculty - faculty location and courses
* Student_has_Semester - bridge table connecting semester and student
* Faculty_has_Semester - bridge table conencting semester and faculty
* * Each table includes primary keys, foreign keys, unique constraints, and not-null requirements to maintain integrity.

## Tech Stack
___
* [![MariaDB](https://img.shields.io/badge/MariaDB-003545?logo=mariadb&logoColor=white)](#)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

## Authors
___
<img src="https://github.com/Stevencain3.png" alt="Profile Picture" width="100" />
<img src="https://github.com/Breckin1027.png" alt="Profile Picture" width="100" />

**Steven Cain & Breckin Lukehart**
* **Steven's GitHub Profile**: [Stevencain3](https://github.com/Stevencain3)
* **Breckin's GitHub Profile**: [Breckin1027](https://github.com/Breckin1027)
___
* **Steven's Email**: [StCain01@wsc.edu](mailto:stcain01@wsc.edu)
* **Breckin's Email**: [BrLuke01@wsc.edu](mailto:brluke01@wsc.edu)

[Back to the top](#overview)
