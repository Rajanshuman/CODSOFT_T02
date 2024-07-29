# CODSOFT_T02
Repository contain the Second task of codsoft java programming internship. 
# STUDENT GRADE CALCULATOR. 
Input: Take marks obtained (out of 100) in each subject.
Calculate Total Marks: Sum up the marks obtained in all subjects.
Calculate Average Percentage: Divide the total marks by the total number of subjects to get the
average percentage.
Grade Calculation: Assign grades based on the average percentage achieved.
Display Results: Show the total marks, average percentage, and the corresponding grade to the user
:--- 
This Java program takes five subject marks as input from the user and calculates the total and percentage of those marks. It also assigns a grade based on the percentage obtained.

Here is how the program works:
It first imports the Scanner class from the java.util package to take input from the user.
It then creates a new Scanner object named input.
The program prompts the user to enter the marks for each of the five subjects.
It reads the input using the nextInt() method of the Scanner class and assigns each input value to a separate variable named m1, m2, m3, m4, and m5.
It calculates the total marks by adding all the input values together and assigns it to a variable named tot.
It calculates the percentage by dividing the total marks by 5 and assigns it to a variable named per.
It then prints out the total and percentage values.
It checks the value of the percentage and assigns a grade based on the following criteria:
If the percentage is greater than or equal to 90, it assigns Grade A.
If the percentage is greater than or equal to 80 but less than 90, it assigns Grade B.
If the percentage is greater than or equal to 70 but less than 80, it assigns Grade C.
If the percentage is greater than or equal to 60 but less than 70, it assigns Grade D.
If the percentage is greater than or equal to 40 but less than 60, it assigns Grade E.
If the percentage is less than 40, it assigns Grade F.
Finally, it prints out the grade assigned to the student based on the percentage obtained.
 
