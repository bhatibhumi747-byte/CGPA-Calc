GPA & CGPA Calculator (Python)

A simple and user-friendly Python program that helps students calculate
their GPA for a semester and CGPA across multiple semesters.

Features

-   Calculate GPA
-   Calculate CGPA
-   Credit-based system
-   Menu-driven
-   Beginner-friendly

How It Works

GPA = (Σ credit × grade_point) / Σ credits
CGPA = (Σ GPA) / number of semesters

Example Output

Your GPA is: 8.70
Your CGPA is: 8.75

Python Code

def calculate_gpa(): subjects = int(input(“Enter number of subjects:”))
total_credits = 0 total_points = 0 for i in range(1, subjects + 1):
credit = float(input(f”Enter credits for subject {i}: “)) grade =
float(input(f”Enter grade point for subject {i}: “)) total_credits +=
credit total_points += credit * grade gpa = total_points / total_credits
print(f”Your GPA is: {gpa:.2f}“)

def calculate_cgpa(): semesters = int(input(“Enter number of
semesters:”)) total_gpa = 0 for i in range(1, semesters + 1): gpa =
float(input(f”Enter GPA for semester {i}: “)) total_gpa += gpa cgpa =
total_gpa / semesters print(f”Your CGPA is: {cgpa:.2f}“)

while True: print(“1. Calculate GPA”) print(“2. Calculate CGPA”)
print(“3. Exit”) choice = input(“Enter your choice:”) if choice == “1”:
calculate_gpa() elif choice == “2”: calculate_cgpa() elif choice == “3”:
break else: print(“Invalid choice”)
