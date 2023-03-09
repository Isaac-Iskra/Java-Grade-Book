# Java-Grade-Book
A Grade book that records grades and let's the teacher know who's failing

The code is a Java program that implements a basic grade book management system. It consists of two classes, Student and GradeBook.

The Student class represents a student with a name and a list of grades. It has a constructor that takes the student's name as an argument and initializes the grades list to an empty ArrayList. It also has getter and setter methods for the name and grades fields, as well as a method to calculate the average grade.

The GradeBook class is the main class that manages the grade book. It contains a Scanner object to read input from the user and an ArrayList of Student objects to store the student data. The class implements a menu-driven interface with five options:

Add a student: This option prompts the user for a name and creates a new Student object with that name, which is added to the ArrayList.

Add a grade: This option prompts the user for a student name and a grade, and adds the grade to the corresponding Student object.

List failing students: This option iterates through the ArrayList and prints the names of all students who have an average grade below 60.

Print final grades: This option iterates through the ArrayList and prints each student's name and average grade.

Exit: This option ends the program.

The GradeBook class also contains four private methods to implement the functionality of the menu options: addStudent(), addGrade(), listFailingStudents(), and printFinalGrades(). These methods manipulate the ArrayList of Student objects and display information to the user using the console.
