GPA & CGPA Calculator
A clean, efficient Python program for calculating Semester GPA and Cumulative GPA (CGPA) with persistent data storage.

📋 Overview
This program helps students track their academic performance by calculating GPA for individual semesters and overall CGPA. It supports both letter grades (A+, A, B+, etc.) and numeric grade inputs (0-10 scale).


Features
Semester GPA Calculation: Compute GPA for current semester
CGPA Calculation: Calculate cumulative GPA across all semesters
Multiple Grade Input Formats: Accepts both letter grades and numeric scores
Persistent Data Storage: Automatically saves semester data to file
Data Management: View and clear saved semester records
Input Validation: Robust error handling for all user inputs
Clean Interface: Simple menu-driven user interface

Installation & Requirements
Requirements
Python 3.6 or higher
No external dependencies required


Installation
Download the gpa_calculator.py file
Ensure Python is installed on your system
Run the program using:
bash
python gpa_calculator.py

How to Use
1. Calculate Semester GPA
Select option 1 from main menu
Enter number of subjects
For each subject:
Input credit hours
Input grade (A+/A/B+/etc OR 0-10)
Program automatically calculates and saves GPA

2. Calculate CGPA
Select option 2 from main menu
Program automatically loads saved semesters
Option to manually enter previous semester data if no saved data exists
Displays cumulative GPA across all semesters

3. View Saved Data
Select option 3 to see all saved semester records
Displays semester number, GPA, and credits

4. Clear Data
Select option 4 to delete all saved records
Requires confirmation before deletion.

Grade Conversion Table
Grade	Points
A+	  10
A	     9
B+	   8
B	     7
C	     6
D	     5
F	     0
Note: Numeric inputs (0-10) are also accepted and converted appropriately.

Data Storage
All semester data is stored in results.txt
File format: semester_number,gpa,credits
Data persists between program sessions
File is created automatically in the same directory

GPA Calculation Formula
Semester GPA:
text
GPA = Σ(Credit × Grade Points) / Total Credits

CGPA:
text
CGPA = Σ(Semester GPA × Semester Credits) / Total Credits Across All Semesters

Technical Details
Language: Python 3
File Handling: Text-based data storage
Input Methods: Console-based interactive input
Compatibility: Cross-platform (Windows, macOS, Linux)

License
This project is for academic purposes. Feel free to modify and use according to your needs.
Contributing
This is a student project. Suggestions for improvements are welcome!
Note: This program is designed for educational purposes and follows
standard GPA calculation methodologies used in academic institutions.















