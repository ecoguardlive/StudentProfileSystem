Student Profile System
A simple Python command-line program that collects, stores, and displays student
information. Built as part of a practical assignment to demonstrate data types, variables,
input/output, and type conversion.
Features
Collects student details via user input
Converts data to the correct types (int, float, list)
Stores all data in a Python dictionary
Displays a neatly formatted profile
Shows the data type of each stored value
How to Run
Make sure you have Python 3 installed, then run:
python student_profile.py
What It Collects
Field
Type
Description
Full Name
str
Student’s full name
Age
int
Converted from input string
GPA
float
Converted from input string
Courses
Split from a comma-separated string
list
No. of Courses
int
Auto-calculated from the courses list
Sample Output
=============================================
       STUDENT PROFILE SYSTEM
=============================================
Enter your full name: Anyan Dennis Amoako
Enter your age: 22
Enter your GPA: 3.89
Enter courses enrolled (comma-separated): Networks, Database, Systems Analysis
=============================================
           STUDENT PROFILE
=============================================
  Name        : Dennis Asante
  Age         : 21 years old
  GPA         : 3.75
  Courses     : Networks, Database, Systems Analysis
  No. Courses : 8 (oftware Engineering, Database Administration, Programming in Java, Programming in Python, Numerical Analysis and computation, Computer Architecture)
=============================================--- Data Types --
  name        
→ <class 'str'>
  age         
  gpa         
  courses     
→ <class 'int'>
→ <class 'float'>
→ <class 'list'>
  num_courses → <class 'int'>
Author
Anyan Dennis Amoako — ITC Level 200
