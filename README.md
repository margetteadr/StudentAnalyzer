# StudentAnalyzer
A Java application that helps you monitor the grades of students.

# Project Title
StudentAnalyzer - ArrayList FRQ Project

# Student Name
Margette

# Description of System
This program is a Java-based system that analyzes a list of student records using an ArrayList. Each student has a name and a mark. The system performs various operations such as counting, filtering, searching, and validating data through multiple methods. The program demonstrates the use of object-oriented programming, loops, and condition-based logic. All methods are tested in the main method using a dataset of at least ten students.

# Explanation of Algorithms
The program uses ArrayList traversal and conditional logic to perform different operations. The countAbove method iterates through the list and counts students whose marks are above a given threshold. The removeFailing method safely removes students with marks below a passing value by iterating backwards. The findTopStudent method finds the student with the highest marks by comparing values. The getTopStudents method creates a new list containing students who meet a minimum mark requirement. The hasDuplicateNames method uses a nested loop to detect duplicate student names. The isSorted method checks if the list is in non-decreasing order by comparing adjacent elements. The countImprovingPairs method counts how many times a student's marks are higher than the previous student in the list.

# Sample Output
Count above 70: 6
After removing failing: 8
Top student: Margette, 100

Top students (80+):
Margette
Sofia
Princess
Fatima

Has duplicates: false
Is sorted: false
Improving pairs: 2

# Challenges Faced
One challenge was understanding how to properly traverse an ArrayList and apply conditions to each object. Another challenge was removing elements safely without skipping values, which required looping backwards. Implementing nested loops for duplicate detection was also difficult at first. Additionally, ensuring that all methods worked correctly together and debugging errors took time and careful testing.
