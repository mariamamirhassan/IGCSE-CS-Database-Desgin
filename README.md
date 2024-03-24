# IGCSE-CS-Database-Desgin

## Project Description:

The IGCSE CS Database, developed by Fatma AlZahraa Bakr and Mariam Amir, is designed to assist an IGCSE teacher in maintaining student data and attendance throughout the academic year. The database encompasses various entities such as employees, students, groups, and attendance records, adhering to specific business rules and relationships.

## Aim of Database:
The primary objective of the database is to facilitate the management of student data and attendance for an IGCSE teacher. It provides a centralized platform to track student information and monitor attendance across different sessions and groups.

## Key Features and Business Rules:

Employees: Employees are categorized as either assistants or graders and cannot hold both roles simultaneously. They are assigned to multiple students.
Students: Attendance for students must be tracked, ensuring comprehensive monitoring of their presence in sessions.
Salary: Salary history is maintained for employees, providing a record of their earnings over time.
Groups: The database accounts for three sessions per week for each group (Class1, Class2, Quiz), facilitating organized scheduling and tracking.

## Schema and Relationships:
The database schema consists of multiple parts, including many-to-many relationships.
Each group has one or more graders and assistants, with each grader/assistant belonging to only one group.
Relationships between students and attendance are justified by the possibility of a student not being added to the attendance table until they attend at least one session.
## Queries and Output Examples:
The project includes various SQL queries demonstrating the functionality of the database, such as counting attendance, retrieving details of students, identifying schools in specific locations, and retrieving salary information for employees.
## Tables Creation and Insertion Examples:
The database creation involves the creation of tables such as Employee, Student, Attendance, Group, and others, along with the insertion of relevant data to populate these tables.
