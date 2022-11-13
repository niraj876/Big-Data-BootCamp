## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: 
    We call python as a general purpose programming language, because we can use python in many popular fields like machine learning, artificial intelligence, health care, etc.
    Python is high-level programming language, becasue it designed to easy to read and simple to implement.

Q2. Why is Python called a dynamically typed language?
Ans: Yes, Python is a Dynamically typed language, because we not need to declase the type of variable while assigning a value to a variable in Python

Q3. List some pros and cons of Python programming language?
    List of some pros of Python Programming Language:
    1. easy to read aand learn
    2. Dynamic Programming language
    3. Variable can change it's datatype throughout the program
    4. Improved Productivity
    5. Interpreted Language
    6. Free and open source
    7. Vast libaries support

    List of some cons of Python Programming Language:
    1. Slow speed
    2. Not memory efficient
    3. Weak in programming for mobile device
    4. Difficult to innteract with database layer

Q4. In what all domains can we use Python?
Ans: We can use Python in many domains, like:
    1. Health Care
    2. Banking
    3. Fianance
    4. Data Science
    5. Machine Learning
    6. Web Development
    7. Game Development 
    8. Data Analysis etc.

Q5. What are variable and how can we declare them?
Ans: Variable is containers, it is used to store value.
Python has no command to declare variable.
Just name the variable Assign the required value to it, The data type of the variable will be automatically determined from the value assigned.

Q6. How can we take an input from the user in Python?
Ans: We can  take input from the user in python using input() method.
for example:
    name = input("Enter your name: ")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans: String

Q8. What is type casting?
Ans: Type casting is type conversion, means it is used to convert one type to another type.
For example:
a = 10 # Here a is integer variable
a = str(a) # Here a is String, because we are doing type casting of variable a

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans: Yes, we can take more than one input from the user using single input() function Using split() function.
for example:
    num1, num2, num3 = input("Enter any three number: ").split()

Q10. What are keywords?
Ans: keywords are reserverd words in python. It has special meaning to the interpreter (or compiler)


Q11. Can we use keywords as a variable? Support your answer with reason.
Ans: No, we can't use keywords as a variable, because keyword has a special meaning to the interpreter (or compiler). If any of the keywords is 
    used as a variable, then we will get the error message SyntaxError: invalid syntax 
    

Q12. What is indentation? What's the use of indentaion in Python?
Ans:  Python indentation is a way of telling a Python interpreter that the group of statements belongs to a particular block of code.

Q13. How can we throw some output in Python?
Ans: We can throw some output in Python using return.

Q14. What are operators in Python?
Ans: Operators are used to perform operations on variables and values.
    Types of Operators:
    1. Arithmetic Operators (+,-, *, /, %, //, **)
    2. Assignment Operators (=, +=, -=, *=, /=, %=, //=, &=, |=, ^=, >>=, <<=, **=)
    3. Comparision Operators (<, >, == !=,  >=, <=, is, is not)
    4. Logical OPeraotrs (and, or, not)
    5. Identity Operators (is, is not)
    6. Bitwise Operators (&, |, ~, ^, >>, <<)
    7. Membership Operators (in, not in)


Q15. What is difference between / and // operators?
Ans: / --> divide the first operand by the second and return float value
    // --> divide the first operand by the second and return integer value (floor)

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Sol:
    print("iNeuron" * 4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Sol:
    num = int(input("Enter an number: "))
    if num%2 == 0:
        print("even")
    esle:
        print("odd")

Q18. What are boolean operator?
Ans: Boolean operators are True and False in python

Q19. What will the output of the following?
```
1 or 0
Ans: 1

0 and 0
Ans: 0

True and False and True
Ans: False

1 or 0 or 0
Ans: 1
```

Q20. What are conditional statements in Python?
Ans: Instead of a sequential execution, we often need to execute a specific code based on a conditional, and that's where Conditional statements are utilized
     in Python. It also helps in decision-making in Python.
     List of Conditional statements in Python:
     1. if
     2. if else
     3. elif
     4. switch
     5. pass
     6. ternary Operators



Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans: 
    if ==> if keyword to specify a block of code that runs if a condition is true.
    for examples:
        if 3 > 2:
            print("3 is greater than 2")
        output: 3 is greater than 2

    elif ==> Sometimes we want to test against multiple conditions before reaching an else keyword.
            Multiple conditions can be checked by including one or more elif checks after your initial if statement. Just keep in mind that only one condition will execute:
    for example:
        if 2 < 1:
            print("This block of code never run")
        elif 2 > 1:
            print("This block of code run")
        output: This block of code run

    else ==> else keyword to specify a block of code that runs if a condition is false.
    for examples:
        if 3 > 2:
            print("3 is greater than 2")
        else:
            print("3 is not greater than 2")
        output: 3 is not greater than 2


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Sol:
    age = int(input("Enter the age of the person: "))
    if age >= 18:
        print("I can vote")
    else:
        print("I can't vote") 


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Sol: 
    even_sum = 0
    for x in numbers:
        if x%2 == 0:
            even_sum += x
    print(even_sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Sol:
    num1 = int(input("Enter 1st Number:"))
    num2 = int(input("Enter 2nd Number:"))
    num3 = int(input("Enter 3rd Number:"))

    if num1>num2 & num1>num3:
        print("Greatest Number: ", num1)
    elif num2 > num3:
        print("Greatest Number: ", num2)
    else:
        print("Greatest Number: ", num3)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Sol:
    for x in numbers:
    if x > 500:
        break
    if x%5 == 0:
        if x > 150:
            continue
        print(x)

