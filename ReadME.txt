# Predict-Progression-Outcome

This program was developed using Python for my computer science coursework in my first semester at university.
The code predicts the progression outcomes of the students at the end of each academic year based on three inputted values by the user: Pass, Defer, & Fail.
Based on the three inputted values, the outcomes will be: Progress, Progress (module trailer), Do not Progress - module retriever or Exclude.
The code only accepts integer values, and the numbers must be 0, 20, 40, 60, 80, 100 and 120.

The progression outcome is given if:
1. Progress: Pass = 120, Defer = 0 & Fail = 0
2. Progress (module trailer): Pass = 100, Defer + Fail = 20
3. Do not Progress - module retriever: Pass < 100, Defer <= 120 & Fail <= 60
4. Exclude: Pass <= 40, Defer <= 40 & Fail >= 80

The program loops allow the user to predict the progression outcomes for multiple students. If the user enters 'q', the loop is broken; otherwise, the loop will still function if they enter 'y'.

After the loop is broken, a Histogram will be outputted to the user with the number of credits and the progression outcome for each student, together with the total number of the progression outcomes represented in this format '(Progression outcome) N : * x N' where N represent how many time that outcome has been repeated.

The output is shown in the format mentioned above in a list in Part 2 or with the student ID in Part 4. Part 3 displays the same values written in a text file while in the loop, which are then read and outputted once the loop is broken.
