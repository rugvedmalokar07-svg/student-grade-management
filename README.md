## Student Grade Management System
-> A simple Python project for managing student names and their corresponding grades using a dictionary for storage.


## Features
-> This system provides a basic command-line interface with the following functionalities:

" Add Student " : Add a new student's name and grade to the system.
" Update Student details " : Modify the grade of an existing student.
" Delete Student data " : Remove a student data from the system.
" View all Student " : Display the names and grades of all students currently in the system.


## Prerequisites
-> You need to have " Python 3 " installed on your system.


## Installation
-> No special installation is required.


## Execution
1.  Save the Code:- Save the provided Python code into a file named " student_grade_management_system.py " or any other name with a ".py" extension inside your project folder.
2.  Run the Script:- Run The Python Code "student_grade_management_system.py" .

-> Once the python code is runned, you will bw presented a menu

Student grades management system
1. Add Student
2. Update Student details
3. Delete Student data
4. View  all Students
5. Exit
enter your choice:

-> enter the number according to the action you wish to perform. 

## Example

1. To Add Student Details->
   enter your choice: 1
   enter student name: Piyush
   enter student grade: 89
   Added Piyush with a 89

   enter your choice: 1
   enter student name: Rohit
   enter student grade: 73
   Added Rohit with a 73

2. To view all students->
   enter your choice: 4
   Piyush:89
   Rohit:73

3. To Exit->
   enter your choice: 5
   closing the program....


## structure of code
-> ("Functions Name" = "description")

"student_grade" = Dictionary used to store all student data.
"add_student(name,grade)" = Adds students and thier grades in key:value pair in "student_grade" dictionary. 
"update_student(name,grade)" = update the grade of exixting student.
"delete_student(name)" =  Removes a student from the dictionary.
"display_all_student()" = Displays all the student with their grade.
"main()" = Handles the menu and user input loop.
" if __name__ = "__main__": " = Ensures that tha main() function is called when we run the code.
# student-grade-management
