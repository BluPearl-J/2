# 2 



Exercises

 Unless specified otherwise, use IPython sessions for each exercise.


 2.1 (What does this code do?) Create the variables x = 2 and y = 3, then determine what each of the following statements displays: 

a) print('x =', x) 

ANSWER
IT IS GOING TO DISPLAYS THE STRING IN SINGLE QUOTE I.E, X= THEN IT DISPLAYS DECLARED ASSIGNED VALUE OF X WHICJH IS 2.
OUTPUT WILL BE X=2. ANSWER.


b)
print('Value of', x, '+', x, 'is', (x + x)) 

ANSWER
OUTPUTS A STRING IN ALL THE SINGLE AND DOUBLE QUOTES SAYING THE VALUE OF X + PLUS 2 IS 2+2


c) print('x =') 

ANSWER 
OUTPUT IS THE STRING X= 



d) print((x + y), '=', (y + x)) 
OUTPUT IS THE INTEGER 5 FOLLOWED BY THE STRING = FOLLOWED BY 5
IE 5=5









In [1]: min(47, 95, 88, 73, 88, 84) Out[1]: 47
THIS CODE IS  UTIL ising USING MATHS MNIMUM FUNCTION DETERMINE LEAST OF SET OF NUMBERS.







In [2]: max(47, 95, 88, 73, 88, 84) Out[2]: 95 
maximum





In [3]: print('Range:', min(47, 95, 88, 73, 88, 84), '-', ...:
answer



max(47, 95, 88, 73, 88, 84)) ..95.: Range: 47 - 95 




Exercises 71 2.2 (What’s wrong with this code?) The following code should read an integer into the variable rating: 


rating = input('Enter an integer rating between 1 and 10') 

ANSWER
IT WILL OUTPUT EXACTLY A STRING DISPLAY.
A STRING PROMPT 
the int typed in can  convert string to integer



2.3 (Fill in the missing code) Replace *** in the following code with a statement that will print a message like 'Congratulations! Your grade of 91 earns you an A in this course'. Your statement should print the value stored in the variable grade: if grade >= 90: *** 

ANSWER
if grade >= 90: 
   print ( congratulations you earned an A)



2.4 (Arithmetic) For each of the arithmetic operators +, -, *, /, // and **, display the value of an expression with 27.5 as the left operand and 2 as the right operand.

27.5 + 2 = 29.5 ANSWER

27.5 * 2 = 55 ANSWER

27.5 // 2 =

27.5  / 2 = 13.75 ANSWER



 2.5 (Circle Area, Diameter and Circumference) For a circle of radius 2, display the diameter, circumference and area. Use the value 3.14159 for π. Use the following formulas (r is the radius): diameter = 2r, circumference = 2πr and area = πr2. [In a later chapter, we’ll introduce Python’s math module which contains a higher-precision representation of π.] 


pie = 3.14159
radius = int 2

diameter = 2 * radius
circumference = 2 * pie * radius
area = pie * radius * radius

print(diameter)
print(int(circumference0)
print(area)


2.6 (Odd or Even) Use if statements to determine whether an integer is odd or even. [Hint: Use the remainder operator. An even number is a multiple of 2. Any multiple of 2 leaves a remainder of 0 when divided by 2.] 


Oddoreven = int(input("Enter any number: "))
if (number % 2) == 0:
   print("even))
else:
   print(odd))
2.7 (Multiples) Use if statements to determine whether 1024 is a multiple of 4 and whether 2 is a multiple of 10. (Hint: Use the remainder operator.) 


2.8 (Table of Squares and Cubes) Write a script that calculates the squares and cubes of the numbers from 0 to 5. Print the resulting values in table format, as shown below. Use the tab escape sequence to achieve the three-column output. number square cube 0 0 0 1 1 1 2 4 8 3 9 27 4 16 64 5 25 125 The next chapter shows how to “right align” numbers. You could try that as an extra challenge here. The output would be: number square cube 0 0 0 1 1 1 2 4 8 3 9 27 4 16 64 5 25 125 2.9 (Integer Value of a Character) Here’s a peek ahead. In this chapter, you learned about strings. Each of a string’s characters has an integer representation. The set of characters a computer uses together with the characters’ integer representations is called that computer’s character set. You can indicate a character value in a program by enclosing that character in quotes, as in 'A'. To determine a character’s integer value, call the built-in function ord: 72 Introduction to Python Programming Display the integer equivalents of B C D b c d 0 1 2 $ * + and the space character. 





2.10 (Arithmetic, Smallest and Largest) Write a script that inputs three integers from the user. Display the sum, average, product, smallest and largest of the numbers. Note that each of these is a reduction in functional-style programming.



 2.11 (Separating the Digits in an Integer) Write a script that inputs a five-digit integer from the user. Separate the number into its individual digits. Print them separated by three spaces each. For example, if the user types in the number 42339, the script should print 4 2 3 3 9 Assume that the user enters the correct number of digits. Use both the floor division and remainder operations to “pick off” each digit.


 2.12 (7% Investment Return) Some investment advisors say that it’s reasonable to expect a 7% return over the long term in the stock market. Assuming that you begin with $1000 and leave your money invested, calculate and display how much money you’ll have after 10, 20 and 30 years. Use the following formula for determining these amounts: a = p(1 + r) n where p is the original amount invested (i.e., the principal of $1000), r is the annual rate of return (7%), n is the number of years (10, 20 or 30) and a is the amount on deposit at the end of the nth year.


 2.13 (How Big Can Python Integers Be?) We’ll answer this question later in the book. For now, use the exponentiation operator ** with large and very large exponents to produce some huge integers and assign those to the variable number to see if Python accepts them. Did you find any integer value that Python won’t accept?


 2.14 (Target Heart-Rate Calculator) While exercising, you can use a heart-rate monitor to see that your heart rate stays within a safe range suggested by your doctors and trainers. According to the American Heart Association (AHA) (http://bit.ly/AHATargetHeartRates), the formula for calculating your maximum heart rate in beats per minute is 220 minus your age in years. Your target heart rate is 50–85% of your maximum heart rate. Write a script that prompts for and inputs the user’s age and calculates and displays the user’s maximum heart rate and the range of the user’s target heart rate. [These formulas are estimates provided by the AHA; maximum and target heart rates may vary based on the health, fitness and gender of the individual. Always consult a physician or qualified healthcare professional before beginning or modifying an exercise program.]



 2.15 (Sort in Ascending Order) Write a script that inputs three different floating-point numbers from the user. Display the numbers in increasing order. Recall that an if statement’s suite can contain more than one statement. Prove that your script works by running it on all six possible orderings of the numbers. Does your script work with duplicate numbers? [This is challenging. In later chapters you’ll do this more conveniently and with many more numbers.



joy reuben 
