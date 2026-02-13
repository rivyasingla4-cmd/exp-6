# Aim

To study and implement conditional statements (if, elif, and else) in Python by writing programs to perform decision-making tasks such as number checking, grading, salary and tax calculation, leap year verification, and date validation.

# Theory

Conditional statements in Python are used to execute different blocks of code based on specific conditions.
The main conditional statements are:

if – executes a block when the condition is true

elif – checks additional conditions if the previous ones are false

else – executes when none of the above conditions are true

These statements help in decision making and controlling the flow of a program. Logical operators (and, or), relational operators (>, <, ==), and arithmetic operators are commonly used with conditional statements.

# Algorithms
# Algorithm 1: Check whether a number is Positive, Negative, or Zero

Start

Read an integer from the user

If number > 0, print “Positive”

Else if number < 0, print “Negative”

Else print “Zero”

Stop

# Algorithm 2: Check whether a number is Even or Odd

Start

Read an integer from the user

If number modulo 2 equals 0, print “Even”

Else print “Odd”

Stop

# Algorithm 3: Find the Largest of Three Numbers

Start

Read three numbers from the user

Compare the first number with the other two

If it is greatest, store it

Else compare the second and third numbers

Store the largest number

Display the largest number

Stop

# Algorithm 4: Calculate Grade Based on Marks

Start

Read subject score

If score ≥ 90, assign grade A

Else if score ≥ 75, assign grade B

Else if score ≥ 50, assign grade C

Else if score ≥ 40, assign grade D

Else assign grade F

Display grade

Stop

# Algorithm 5: Check Whether a Year is Leap Year

Start

Read year from user

If year is divisible by 4 and not by 100, it is a leap year

Otherwise, it is not a leap year

Display result

Stop

# Algorithm 6: Check Whether a Character is Vowel or Consonant

Start

Read a character

If character is in a, e, i, o, u (upper or lower case)

Print “Vowel”

Else print “Consonant”

Stop

# Algorithm 7: Calculate Gross Salary

Start

Read basic salary

If basic ≤ 10000, calculate HRA = 20% and DA = 80%

Else if basic ≤ 20000, calculate HRA = 25% and DA = 90%

Else calculate HRA = 30% and DA = 95%

Calculate gross salary

Display salary details

Stop

# Algorithm 8: Calculate Income Tax

Step 1: Start the program.

Step 2: Read the annual income from the user 

Step 3: Initialize a variable tax and set it to 0.

Step 4: Check income conditions:

If income is less than or equal to 2,50,000,

set tax = 0 (no tax).

Step 5: If income is between 2,50,001 and 5,00,000,
calculate tax as:
tax = (income − 2,50,000) × 5%

Step 6: If income is between 5,00,001 and 10,00,000,
5% tax on the first ₹2,50,000 above exemption
20% tax on the remaining amount
Formula:
tax = (2,50,000 × 5%) + (income − 5,00,000) × 20%

Step 7: If income is greater than 10,00,000,
5% tax on ₹2,50,000
20% tax on ₹5,00,000
30% tax on remaining income
Formula:
tax = (2,50,000 × 5%) + (5,00,000 × 20%) + (income − 10,00,000) × 30%

Step 8: Display the annual income.

Step 9: Display the calculated income tax.

Step 10: Stop the program.

# Algorithm 9: Validate and Increment Date

Start

Read date in dd/mm/yyyy format

Validate day, month, and year

Check leap year for February

If date is invalid, display error

Else increment the date by one day

Handle month and year change

Display incremented date

Stop

# Conclusion

Thus, Experiment–6 was successfully performed. The use of conditional statements (if, elif, and else) in Python was studied and implemented through various programs. These programs demonstrated decision-making, logical comparison, and real-world problem solving such as grading, salary computation, tax calculation, and date validation.
