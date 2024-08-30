This is a basic CGPA Calculator app which is a useful tool for students to calculate their Cumulative Grade Point Average (CGPA) based on their grades and credit hours for each subject. Here's a simple breakdown of how you might design and develop such an app:

-> Features

1. Calculate Current CGPA:
Input grades and credit hours for each subject.
Calculate the weighted average based on the credit hours and grades.

2. Store and Display Previous CGPA:
Input or retrieve previous CGPA and credit hours for previous semesters.
Display the overall CGPA combining current and previous semesters.

-> Components

1. User Interface (UI):

* Input Fields:
For entering grades and credit hours for the current semester.
For entering previous CGPA and credit hours.

* Buttons:
"Calculate CGPA" button to compute the current CGPA.
"Previous Sem CGPA" button to display stored CGPA and combine with the current semester.

* Display Area:
To show the computed CGPA and overall CGPA.

2. Backend Logic:

*CGPA Calculation:
Formula: CGPA = (Sum of (Grade Points * Credit Hours)) / (Total Credit Hours)

* Combining CGPA:
Overall CGPA = (Previous Total Grade Points + Current Semester Grade Points) / (Previous Total Credit Hours + Current Semester Credit Hours)

3. Data Storage:

For simplicity, you can use local storage or a database to store previous CGPA and credit hours.

-> Sample Workflow

1. User Input:
Enter grades and credit hours for each subject in the current semester.
Enter the previous CGPA and total credit hours for previous semesters.

2 Calculation:

Compute the total grade points for the current semester:
Total Grade Points = Σ (Grade Points * Credit Hours)
Compute the total credit hours for the current semester.
Calculate the current CGPA.
Combine with previous CGPA to get the overall CGPA.
Display Results:
Show the current CGPA.
Display the overall CGPA including previous semesters.

-> Example

Current Semester:
Subject 1: 4 credit hours, Grade A (4.0 points)
Subject 2: 3 credit hours, Grade B (3.0 points)
Previous CGPA:
Previous CGPA: 3.5
Previous Total Credit Hours: 60
