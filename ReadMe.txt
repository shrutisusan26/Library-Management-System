DBMS MINI PROJECT SYNOPSIS

PARTNER:- Simran Kucheria(111803126)
Problem Statement
Library Management System

Introduction
This is a basic Library Management System using python and SQL, It can be used in schools/colleges
to monitor the day to day requirements of the library.

Functional Requirements of the system 
The system will have 2 modes depending on who is using it(Staff/Students)
Staff mode will only be accessible using password (Hardcoded as 17 for now)

Staff
1)Register-Books, Students, Authors, Genres(Categories as well as adding genres to books), Personal info
2)View-Students(All, Department wise), Personal info of students
3)Delete-Students, Books, Authors, Genres
4)Update/Modify-Books(Restocking, changing info), Authors, Students
5)Manage fines, enquiries and comments(Use to pay and acknowledge fines and enquiries)

Student
1)Display- Books(All, Genre wise, Author wise), Authors, Borrowed books(using Student ID), Fines(of a particular student)
2)Issue/Return/Report lost books
3)Search for books using Genre, Author, Title
4)Add enquiries/Comments

To run
1)Make sure that line 217/218 has correct directory address(Currently has me and my partners directories hardcoded)
2)Need to have mysql with an empty database called library with correct permissions granted
3)Add login statement to Inventory.py Create.py to access database
4)Run Create.py first
5)Then run see.py

Screenshots of all functions and menus attached

