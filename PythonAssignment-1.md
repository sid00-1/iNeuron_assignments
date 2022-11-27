## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
->The python can be used for multiple purposes like web development, data science, data engineering, etc and not just confined to specific stream or domain so due to it's multiple use cases it's called as general purpose language. It is high level language because it's written in simple human readable format instead of low level languages like binary.

Q2. Why is Python called a dynamically typed language?
-> In python we doesn't need to explicitly declare the datatype of the variable and store the value in it instead we can directly assign the values of any data type to the variable. 

Q3. List some pros and cons of Python programming language?
-> Pros:
	1) Easy to learn
	2) Vast collection of libraries
	3) Huge community

	Cons:
	1) Comparatively slow 
	2) Uses lot of memory
	3) Less secure

Q4. In what all domains can we use Python?
-> Python can be used in domain like data science, data analytics, web development, data engineering, blockchain, web scraping.  

Q5. What are variable and how can we declare them?
-> Variable is the container to store the data. Variable is the location in memory where the value of the variable will be stored. In python we don't have specific way or command to declare the variable. We can directly assign the value to any variable. Ex: var = 21 (the data type of var is now int) 

Q6. How can we take an input from the user in Python?
-> For taking the input from the user in python we use the "input()" function . Ex: var1 = input()

Q7. What is the default datatype of the value that has been taken as an input using input() function?
-> The default data type for "input()" function is String.

Q8. What is type casting?
-> To restrict the scope of the data type of the variable to specific data type is type casting. 
	Ex: var2 = float(input()) (Here we've restricted the data type of input to float)

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
-> Yes, we can use single input() to take the data from the user by using the split function and list comprehension method.

Q10. What are keywords?
-> Keywords are the words which are reserved for the specific instruction or activity. These words are used by the programming language to describe command or action.

Q11. Can we use keywords as a variable? Support your answer with reason.
-> No, we can't use any keyword as variable as it'll throw a syntax error.

Q12. What is indentation? What's the use of indentation in Python?
-> The spaces given before the starting of the line. Indentation is used in python to specify range of the particular block of code.

Q13. How can we throw some output in Python?
-> In python we can use print() function to display the output.

Q14. What are operators in Python?
-> Operators are the symbol which performs specific functions.

Q15. What is difference between / and // operators?
-> "/" is division operator the value we get after using the operator is float. "//" is floor division operator which returns the nearest whole number.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
-> a = "iNeuroniNeuroniNeuroniNeuron"
   print(a)


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
-> num = int(input())
   if (num%2==0):
   		print("Even")
   else:
   		print("Odd")

Q18. What are boolean operator?
-> Boolean operator also known as logical operators are used to check whether the value of operands are truthy or falsy.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
-> 1, 0, False, 1
Q20. What are conditional statements in Python?
-> Conditional statements are used to filter out the output using the specific conditions. 

Q21. What is use of 'if', 'elif' and 'else' keywords?
-> We use "if" when we need the output only when the condition is satisfied. We use "elif" if we have multiple condition to be mentioned. We use "else" when any of the conditions mentioned in the "if" and "elif" doesn't get satisfied.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
-> Age = 21
   if(Age>18):
   		print("I can vote")
   else:
   		print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
-> sum = 0
   for i in numbers:
		if(i%2 == 0):
			sum = sum + i
   print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
-> x, y, z = int(input()).split()
   if(x>y and x>z):
   	print(x)
   elif(y>x, y>z):
   	print(y)
   else:
   	print(z)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
-> 
for i in numbers:
	if(i%5==0):
		if(i>150):
			continue
		elif(i>500):
			break
		else:
			print(i)