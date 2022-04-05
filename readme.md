REST API built using Spring Boot, Spring
Data JPA, PostgreSQL, and lombok.

The key files can be found in: 
src/main/java/com/SchoolApi/Enroll.

There are models for students, teachers, 
subjects, courses, and enrollments with
the necessary foreign key relationships 
configured. 

The controllers folder has the necessary 
API endpoints for students to login, search 
for classes, enroll and unenroll while 
complying with a 30 student limit for each
course and a 5 course limit for each student.
The JAva 8 stream api was used extensively 
as well.