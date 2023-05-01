# Student_Management_System
My teammate and I created a project for our Programming 1 class. We built a Student Management system program to help students calculate 
their GPA and to show their degree progress. 

# Running the Code
To run this code you can download the zip file from this repository, extract it, and open it in clion or other c++ coding enviorments.

# Project Description
In this project we made a series of degree functions to asses a users current degree status and also the option to update it. We also wanted to create a function that would take a users current GPA and update it with new semester grades.

# Editing the Code
This code has a mulitude of functions, varibles, and a class that will now be gone over!
The first part of our program is the class "UserData" which is used to store the input data of the user. This way it can be accessed across more functions and changed easier. 
The first function is of course the "main" function which in this case basically acts as a menu for our program. With only the menu_option and major variables used. The menu option varible just asses the menu option the user chooses and calls a function based on that. The major varible accepts the input from the degree_progress function menu and calls a function based of that input as well. It is also used to exit the code.
The "intro" function is just text to introduce the user to our code :). 
The "welcome_and_info" function accepts the user inoput for their infromation and stores it in the class objects. It also opens a file that stores that same information called "student_registry". Laslty this function welcome the user.
The "menu" function simply acts as text for the menu in the "main" function.
The "degree_progress" function is another menu that accepts the users major as an answer. Then the "main" function uses that answer to direct the code.
The "update_degree_progress" function is pretty loaded. It has a couple varibles and accepts the class objects as parameters. The "full_name" variable concatinates the first and last name object from the "UserData" class. We use vectors to store all the courses for every major as to be able to find how many credits each course is worth to add to needed courses. It also opens a file with the users name to store the course they still haven't taken so it can be updated again in the future. It goes through each course and asks the user if they have taken that course.
The "cumulative_gpa_calculator" function is a simple math function that does the calculations for the users cumultative GPA.
All of the rest of the functions are "major" functions and they act similalry to the "update_degree_progress" function.
