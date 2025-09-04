1. Creates an empty list called marks.       
Lists can store multiple values.
Here we are storing the marks for each subject inside this list.


2. We create a for loop that runs from 1 to 5 (because range(1,6) gives numbers: 1, 2, 3, 4, 5).
Each number (i) represents the subject number (Subject 1, Subject 2, etc.).
The user will be asked to enter marks 5 times.


3. Inside the loop:
input() asks the user to type in marks.
f"Enter The Marks Of Subject {i}" is an f-string – it replaces {i} with the current subject number.
float() converts the user’s input into a decimal number.


4. Adds the entered mark to the marks list.
If the user entered 85, then marks becomes [85.0].


5. sum(marks) adds up all numbers in the list.
The result is stored in total.


6. len(marks) returns how many subjects are in the list.
total / 5 calculates the average.


7. This decides the final grade based on average marks:
If average is 90 or more → Grade A
Else if average is 75 or more → Grade B
Else if average is 50 or more → Grade C
Else (below 50) → Grade D
Only one of these conditions will run.


7. Finally, these lines display the results neatly:
Total marks
Average marks
Final grade


OUTPUT:

======STUDENT GRADE CALCULATOR======

Enter The Marks Of Subject 1 (0-100): 80

Enter The Marks Of Subject 2 (0-100): 90

Enter The Marks Of Subject 3 (0-100): 70

Enter The Marks Of Subject 4 (0-100): 85

Enter The Marks Of Subject 5 (0-100): 75

The Total Marks = 400.0

Average Marks = 80.0

Your Final Grade Is B

==============THANK YOU==============




