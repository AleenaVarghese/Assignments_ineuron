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
Q26. What is a string? How can we declare string in Python?
Ans :
A string is a sequence of characters. For example, "hello" is a string containing a sequence of characters 'h' , 'e' , 'l' , 'l' and 'o'.
We can use single quotes or double quotes to represent a string in Python. 
Example:
# create a string using double quotes
string1 = "Python programming"
# create a string using single quotes
string1 = 'Python programming'

Q27. How can we access the string using its index?
Ans : 
Individual characters in a string can be accessed by specifying the string name followed by a number in square brackets ( [] ). String indexing in Python is zero-based: the first character in the string has index 0 , the next has index 1 , and so on.
Example :
	string1 = "Python programming"
	print(“Second Character in string1:”,string1[1]) # will print y

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
Ans :
	string = "Big Data iNeuron"
desired_output = "iNeuron"
print(string.split()[-1])

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
Ans :
	string = "Big Data iNeuron"
print(string.split()[-1][::-1])

Q30. Resverse the string given in the above question.
Ans :
	string = "Big Data iNeuron"
	print(string[::-1])

Q31. How can you delete entire string at once?
Ans :
	To remove an entire string in python, we can use del command.
Example :
	string1= "Big Data iNeuron"
	del string1 

Q32. What is escape sequence?
Ans : 
An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters. Escape sequences are formed using two things: the first is a backslash (\\), and the second is the set of one or more characters following that backslash (\\).	
Example :
•	\’ : Single quote
•	\\’ : Double quote
•	\\ : Backslash
•	\n : Newline
print('Who\'s this?') # will print Who's this?


Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
Ans : 
	print(‘iNeuron\'s Big Data Course’)

Q34. What is a list in Python?
Ans : 
	Lists are used to store multiple items in a single variable. The list is a sequence data type which is used to store the collection of data. Tuples and String are other types of sequence data types. Python list can be written as a list of comma-separated values (items) between square brackets.

Q35. How can you create a list in Python?
Ans :
	We create Python List using [] or list() function and putting different comma-separated values.
Example:
	list1 = [1,2,3]
	list2 = list(“A”,”B”,”C”)

Q36. How can we access the elements in a list?
Ans :
To access values in lists, use the square brackets for slicing along with the index or indices to obtain value available at that index.
Example:
list1 = ['physics', 'chemistry', 1997, 2000];
list2 = [1, 2, 3, 4, 5, 6, 7 ];
print "list1[0]: ", list1[0]
print "list2[1:5]: ", list2[1:5]

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
Ans :
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][-1])

Q38. Take a list as an input from the user and find the length of the list.
Ans :
lst = input("enter list values:").split()
print("ength of list = ",len(lst))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
Ans :
	lst = ["Welcome", "to", "Data", "course"]
lst.insert(2,"big")
print(lst)

Q40. What is a tuple? How is it different from list?
Ans :
Tuple is a sequence data type similar to list which is used to store the collection of data. The difference between tuple and list is that tuple is immutable but list is mutable. We can’t update values present in tuple but this is possible in list. Tuple data type is appropriate for accessing the elements. Tuple consumes less memory as compared to the list. 

Q41. How can you create a tuple in Python?
Ans :
	We create Python tuple using () or tuple() function and putting different comma-separated values.
Example:
	t1 = (1,2,3)
	t2 = tuple(“A”,”B”,”C”)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
Ans:
	Not possible to add values to an existing tuple in python. Because, Tuple is immutable data type and hence we can’t update values of an existing tuple. We can convert tuple into list and do all the operations if needed and again we have to convert it back into tuple. This is the possible method of doing this.
Example:
	t1 = ('Apple','Orange','Mango')
t1 = list(t1)
t1.insert(len(t1)+1,'Aleena')
t1 = tuple(t1)
print(t1)

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Ans :
	Tuples can be appended and create a new tuple. 
	t1 = tuple(i for i in range(10,1,-1))
t2 = tuple(i for i in range(20,10,-1))
t3=t1+t2
t3

Q44. Take a tuple as an input and print the count of elements in it.
Ans:
	ip = list(input("input values:").split())
print(“Number of items in tuple: ”,len(ip))

Q45. What are sets in Python?
Ans :
	A set is a collection which is unordered, unchangeable and unindexed. Set items are unchangeable, but you can remove items and add new items. Sets cannot have two items with the same value. Sets are written with curly brackets.
Example : 
myset = {"apple", "banana", "cherry"}

Q46. How can you create a set?
Ans : 
1.	Using set() constructor 
Example: 
s = set((1,0,23))
2.	Using {}
Example :
	s = {1,4,5,6} 
Q47. Create a set and add "iNeuron" in your set.
Ans :
	s = {'Apple','Orange','Mango'}
s.add("iNeuron")
print(s)
Q48. Try to add multiple values using add() function.
Ans :
	s = {'Apple','Orange','Mango'}
s.update(["iNeuron1","iNeuron2","iNeuron3","iNeuron4"])
print(s)
Q49. How is update() different from add()?
Ans:
1.	Add() – is for adding a single element to an existing set. It will have a single element as an argument.
2.	Update() is for adding multiple elements into an existing set. It will take a list of elements ass arguments.

Q50. What is clear() in sets?
Ans :
	The clear() method removes all items from the set. 
Example:
	s.update(["iNeuron","1"])
s.clear()
print(s)

Q51. What is frozen set?
Ans :
	These are unchangeable sets. The frozenset() function returns an unchangeable frozenset object (which is like a set object, only unchangeable).

Q52. How is frozen set different from set?
Ans:
	Frozenset is unchangeable but set is changeable. Which means once we create a frozenset, we can’t add a new item or update an existing item. But In normal set, we can add new items into an existing set.

Q53. What is union() in sets? Explain via code.
Ans : 
	The union() method returns a set that contains all items from both sets, duplicates are excluded. 
Example:
	x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}
z = x.union(y)
print(z)

Q54. What is intersection() in sets? Explain via code.
Ans:
	The intersection() method returns a set that contains the similarity between two or more sets. It returns a set that contains the items that exist in both set x, and set y.
Example:
	x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}
z = x.intersection(y)
print(z)

Q55. What is dictionary in Python?
Ans:
Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered, changeable and do not allow duplicates. Dictionaries are written with curly brackets, and have keys and values.
Example:
	dict1 = {
  	"brand": "Ford",
  	"model": "Mustang",
  	"year": 1964
}
print(dict1)

Q56. How is dictionary different from all other data structures.
Ans:
	Dictionaries are used to store data values in key:value pairs and we can access values of dictionary using these unique keys.



Q57. How can we declare a dictionary in Python?
Ans :
1.	Using dict() constructor
thisdict = dict(name = "John", age = 36, country = "Norway")
print(thisdict)
2.	Using direct assignments:
thisdict = {
  "brand": "Ford",
  "electric": False,
  "year": 1964,
  "colors": ["red", "white", "blue"]
}
Print(thisdict)

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
Ans :
	<class 'dict'>

Q59. How can we add an element in a dictionary?
Ans :
	Adding an item to the dictionary is done by using a new index key and assigning a value to it.
Example:
	thisdict = {
  	"brand": "Ford",
 	 "model": "Mustang",
  	"year": 1964
}
thisdict["color"] = "red"
print(thisdict)

Q60. Create a dictionary and access all the values in that dictionary.
Ans :
	The values() method will return a list of all the values in the dictionary. 
Example :
	thisdict = {
  	"brand": "Ford",
 	 "model": "Mustang",
  	"year": 1964
}
	x = thisdict.values()


Q61. Create a nested dictionary and access all the element in the inner dictionary.
Ans :
	dict1 = {"brand": "Ford",
"model": "Mustang",
"year": 1964}
dict1['DOB'] = {'date':12,'month':7,'year':1996}
print(dict1['DOB'].values())

Q62. What is the use of get() function?
Ans :
	To access the items of a dictionary by referring to its key name, we can use get() method. 
Example :
x = thisdict.get("model") 

Q63. What is the use of items() function?
Ans:
	The items() method will return each item in a dictionary, as tuples in a list. 
Example:
	x = thisdict.items()

Q64. What is the use of pop() function?
Ans:
	The pop() method removes the item with the specified key name.
Example:
	thisdict = {
  	"brand": "Ford",
  	"model": "Mustang",
 	 "year": 1964
}
thisdict.pop("model")
print(thisdict)

Q65. What is the use of popitem() function?
Ans:
	The popitem() method removes the last inserted item from a dictionary.
Example: 
	thisdict = {
  	"brand": "Ford",
  	"model": "Mustang",
 	 "year": 1964
}
thisdict.popitem()
print(thisdict) 



Q66. What is the use of keys() function?
Ans:
The keys() method will return a list of all the keys in the dictionary.
Example:
x = thisdict.keys()

Q67. What is the use of values() function?
Ans:
	The values() method will return a list of all the values in the dictionary. 
Example:
	x = thisdict.values()

Q68. What are loops in Python?
Ans:
	Looping means repeating something over and over until a particular condition is satisfied. There are two types of looping statements available in python.
1.	For loop
2.	While loop

Q69. How many type of loop are there in Python?
Ans:
There are two types of looping statements available in python.
1.	For loop
2.	While loop

Q70. What is the difference between for and while loops?
Ans :
1.	For loop – If we know the number of iterations in advance, we can use for loop.
Example: To print hi 5 times we use
	for I in range(5):
		Print(“hi”)
2.	While loop – If we don’t know the number of iterations in advance, we will use while loop. We need to use incrementations statements directly inside while block.
Example :
	I = 1
	While I < 5:
		Print(“hi”)
		I+=1

Q71. What is the use of continue statement?
Ans :
	Continue statements are using to skip current iteration and continue with the next iteration.
Q72. What is the use of break statement?
Ans:
	Break statement is using to stop further execution of a looping statement. 
Q73. What is the use of pass statement?
Ans :
	Pass operator is used as a do nothing placeholder. In some cases, we must specify an action or statement in that cases, we don’t want to do anything then we can specify pass. When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed.

Q74. What is the use of range() function?
Ans :
	The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

Q75. How can you loop over a dictionary?

Ans :
	We can loop through a dictionary using a for loop. When looping through a dictionary, the return value are the keys of the dictionary, but there are methods to return the values as well.
Example:
1.	for x in thisdict:
  print(x)
2.	for x in thisdict:
  print(thisdict[x])
3.	for x in thisdict.values():
  print(x)
4.	for x, y in thisdict.items():
  print(x, y)

### Coding problems
Q76. Write a Python program to find the factorial of a given number.
Ans : 
	def factorial(x):
    		if x == 1:
        			return 1
    		else:
        			return (x * factorial(x-1))

num = 10
result = factorial(num)
print("The factorial of", num, "is", result)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100
Ans :
	P = 1000
	R = 2
	T = 10
	Si = (P*R*T)/100
	Print(“Simple interest=”,si)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
Ans :
	p = 1000
R = 2
t= 10
a = P*(1+ R/100)**t
ci=a-p
print("Compound interest=",ci)

Q79. Write a Python program to check if a number is prime or not.
Ans :
	num = 2
# If given number is greater than 1
if num > 1:
    # Iterate from 2 to n / 2
    for i in range(2, int(num/2)+1):
        # If num is divisible by any number between
        # 2 and n / 2, it is not prime
        if (num % i) == 0:
            print(num, "is not a prime number")
            break
        else:
        	print(num, "is a prime number")
else:
    print(num, "is not a prime number")

Q80. Write a Python program to check Armstrong Number.
Ans:
	# take input from the user
num = 371

# initialize sum
sum = 0

# find the sum of the cube of each digit
temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10

# display the result
if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")

Q81. Write a Python program to find the n-th Fibonacci Number.
Ans:
	def Fibonacci(n):
    		if n<= 0:
        			print("Incorrect input")
    			# First Fibonacci number is 0
    		elif n == 1:
        			return 0
    		# Second Fibonacci number is 1
   		 elif n == 2:
        			return 1
    		else:
        			return Fibonacci(n-1)+Fibonacci(n-2)
	print(Fibonacci(10))

Q82. Write a Python program to interchange the first and last element in a list.
Ans:
	numbers = [12, 75, 150, 180, 145, 525, 50]
	numbers[0],numbers[-1] = numbers[-1],numbers[0]
print(numbers)

Q83. Write a Python program to swap two elements in a list.
Ans:
	numbers = [12, 75, 150, 180, 145, 525, 50]
numbers[0],numbers[1] = numbers[1],numbers[0]
print(numbers)

Q84. Write a Python program to find N largest element from a list.
Ans:
	numbers = [12, 75, 150, 180, 145, 525, 50]
n = 2 
numbers.sort()
print(numbers[-n:])

Q85. Write a Python program to find cumulative sum of a list.
Ans:
	numbers = [12, 75, 150, 180, 145, 525, 50]
x = [sum(numbers[:i]) for i in range(1,len(numbers)+1)]
print(x)

Q86. Write a Python program to check if a string is palindrome or not.
Ans :
	s = "malayalam"
x = 'Palindrome' if s == s[::-1] else 'Not Palindrome'
print(x)

Q87. Write a Python program to remove i'th element from a string.
Ans:
	s = "Assignment"
i = 5
new_s = s[:i]+s[i+1:]
print(new_s)

Q88. Write a Python program to check if a substring is present in a given string.
Ans:
	s = "Assignment" 
substr = 'ing'
x ='present' if str.upper(substr) in str.upper(s) else 'not present'
print(x)

Q89. Write a Python program to find words which are greater than given length k.
Ans:
	s = "Assignment"
length = 3
x = 'length greater than given length' if length < len(s) else 'length less than given length'
print(x)

Q90. Write a Python program to extract unique dictionary values.
Ans:
	dict1 = {
 	 "brand": "Ford",
  	"model": "Mustang",
 	 "year": 1964,
  	"colors": "red",
  	"brand_name" : "Ford",
  	"model_name" : "Mustang"
}
x = set([i for i in dict1.values()])
print(x)

Q91. Write a Python program to merge two dictionary.
Ans:
	dict1 = {
  	"brand": "Ford",
  	"model": "Mustang",
  	"year": 1964,
  	"colors": "red",
  	"brand_name" : "Ford",
 	 "model_name" : "Mustang"
}
dict2 = {
 	"brand1": "Ford",
  	"model1": "Mustang",
  	"year1": 1964,
  	"colors1": "red",
  	"brand_name1" : "Ford",
  	"model_name1" : "Mustang"
}
dict3 = dict(dict1.items() | dict2.items())
print(dict3)
 
Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
Ans:
	Input = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
dict1 = dict()
for k,v in Input:
    		dict1[k] = v
print(dict1) 

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
Ans:
	ip = [9, 5, 6]
op = [(x,x ** 3) for x in ip ]
print(op)

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
Ans:
	test_tuple1 = (7, 2)
test_tuple2 = (7, 8)
op = [(x,y) for x in test_tuple1 for y in test_tuple2] + [(x,y) for x in test_tuple2 for y in test_tuple1]
print(op)

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
Ans:
	    
ip = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
ip.sort(key = lambda x : x[1])
print(ip)

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
Ans:
	n = 5
for i in range(1, n+1):
    print("*" * i)

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
Ans:
	n = 5
for i in range(1, n+1):
    print(" " * (n - i) + "*" * i)

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
Ans:
	n = 5
for i in range(1, n+1):
    print(' ' * (n - i) + '*' * (2 * i - 1))

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
Ans:
	size = 5
for i in range(size):
    for j in range(i+1):
        print(j+1, end="")
    print('\r')

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```
Ans:
	for i in range(1,6):
    		print(chr(65+(i-1))*i)
    
