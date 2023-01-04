## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans : 
Python is a general-purpose language, meaning it can be used to create a variety of different programs and isn’t specialized for any specific problems. This versatility, along with its beginner-friendliness, has made it one of the most-used programming languages today.
Python is an object-oriented, high-level programming language. Object-oriented means this language is based around objects (such as data) rather than functions, and high-level means it's easy for humans to understand.

Q2. Why is Python called a dynamically typed language?
Ans : Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. Python also take cares of the memory management which is crucial in programming. So, Python is a dynamically typed language.

Q3. List some pros and cons of Python programming language?
Ans:
Pros
1.	Beginner-friendly programming language 
2.	Large community support
3.	Flexible and extensible
4.	Extensive libraries 
5.	Embeddable
6.	Highly scalable 
7.	IOT Opportunities
8.	Portable 
Cons:
1.	Slower than compiled languages
2.	Security
3.	Work environment
4.	High memory conception
5.	Dynamically typed language 
6.	Complex multithreading
7.	Garbage collection leads to potential memory lose
8.	Issues with design

Q4. In what all domains can we use Python?
Ans: 
Employing python allows the user to work on multiple domains ranging from Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting, Networking, Game Development to Web Development. 

Q5. What are variable and how can we declare them?
Ans:
Variables are containers for storing data values. Python has no command for declaring a variable. A variable is created the moment you first assign a value to it.
Example : 
Variable1 = 1
Variable2 = “python”
Variables do not need to be declared with any particular type, and can even change type after they have been set. 
Example:
	X = “Python”
	X = 10

Q6. How can we take an input from the user in Python?
Ans:
Python 3.6 uses the input() method.
Example:
username = input("Enter username:")
print("Username is: " + username)
Python 2.7 uses the raw_input() method.
Example :
	username = raw_input("Enter username:")
print("Username is: " + username)

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans:
      The default datatype of the input() function is String
Q8. What is type casting?
Ans :
Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.
Example:
a = 12
b = str(a)

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans :
The developer often wants a user to enter multiple values or inputs in one line. Python user can take multiple values or inputs in one line by two methods. 
•	Using split() method
•	Using List comprehension
1.	Using split() method : 
This function helps in getting multiple inputs from users. It breaks the given input by the specified separator. If a separator is not provided then any white space is a separator. Generally, users use a split() method to split a Python string but one can use it in taking multiple inputs.

Syntax :
input().split(separator, maxsplit)

Example :
# taking two inputs at a time
x, y = input("Enter two values: ").split() 

2.	Using List comprehension : 
List comprehension is an elegant way to define and create list in Python. We can create lists just like mathematical statements in one line only. It is also used in getting multiple inputs from a user.
Example :
# taking multiple inputs at a time separated by comma
x = [int(x) for x in input("Enter multiple value: ").split(",")]

Q10. What are keywords?
Ans :
Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes. 
Example : 
break, pass, continue 
Q11. Can we use keywords as a variable? Support your answer with reason.
Ans:
Keywords are used to define the syntax of the coding. Python keywords cannot be used as an identifier, function, and variable name.
Q12. What is indentation? What's the use of indentation in Python?
Ans :
Indentation is a way of telling a Python interpreter that the group of statements belongs to a particular block of code. It increases readability of python code. 
Example :
for i in range(10):
    print(i)

Q13. How can we throw some output in Python?
Ans:
To display outputs in python, we have to use Print() function.
Example: 
Print(“python”)

Q14. What are operators in Python?
Ans:
•	Arithmetic operators – Arithmetic operators are used with numeric values to perform common mathematical operations: 
Example : +, - , * ,/,%,**,//
•	Assignment operators - Assignment operators are used to assign values to variables. 
Example : =,+=,-=,*=,/=,%=,//=,**=,&=,|=,^=,>>=,<<=, 
•	Comparison operators - Comparison operators are used to compare two values
Example: ==,!=,>,<,>=,<=
•	Logical operators : Logical operators are used to combine conditional statements.
Example : and , or , not 
•	Identity operators - Identity operators are used to compare the objects, not if they are equal, but if they are actually the same object, with the same memory location.
Example : is, is not
•	Membership operators : Membership operators are used to test if a sequence is presented in an object.
Example : in, not in 
•	Bitwise operators : Bitwise operators are used to compare (binary) numbers.
Example : & ,|,^,~,<<,>>

Q15. What is difference between / and // operators?
Ans : 
•	/ is used for the normal division of two numbers.
•	// is used for floor division. I.e. it is used to obtain the smallest integer nearest to the quotient obtained by dividing two numbers.
Example :
	a = 19
b = 4
print(a // b)  #This prints output as 4
print(a / b)  #This prints output as 4.75

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans:
Print(‘iNeuron’ *4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans: 
	v = input("enter a number:")
x = "Even" if int(v)%2 == 0 else "Odd"
print(x)
Q18. What are Boolean operator?
Ans:
It’s used to represent the truth value of an expression. For example, the expression 1 <= 2 is True, while the expression 0 == 1 is False. Python Boolean type has only two possible values:
1.	True or 1
2.	False or 0

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans :
1 or 0 - 1
0 and 0 - 0
True and False and True - False
1 or 0 or 0 - 1

Q20. What are conditional statements in Python?
Ans :
Python supports the usual logical conditions from mathematics:
•	Equals: a == b
•	Not Equals: a != b
•	Less than: a < b
•	Less than or equal to: a <= b
•	Greater than: a > b
•	Greater than or equal to: a >= b

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans : 
If , elif and else are conditional statements that provide us with the decision making that is required when we want to execute code based on a particular condition. 
Example :
	a = 1
	if a == 1:
		print(“One”)
	elif a == 2:
		print(“Two”)
	else:
		print(“New Value”)

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans: 
age = int(input(“enter your age:”))
if age >= 18:
	print(“I can vote”)
if age < 18:
	print(“I can’t vote”)



Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
x = 0
x = [x := x + i for i in numbers if i%2 == 0][-1]
print(“sum of even numbers “,x)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans : 
a,b,c = input("enter 3 numbers").split()
list1 = [int(a),int(b),int(c)]
list1.sort()
print("largest value",list1[-1])

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:
	numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i%5 == 0: #The number must be divisible by five
        if i > 150: #If the number is greater than 150, then skip it and move to the next number
            continue
        if i > 500: #If the number is greater than 500, then stop the loop
            break
        print(i)
