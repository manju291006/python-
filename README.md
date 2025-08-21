# Experiment No: 1b DATATYPES- print the type of the variable.

## AIM 
To write a Python program to read a variable and print its type.
## ALGORITHM  
Step 1: Start the program.
Step 2: Read the value of the variable from the user using the input() function.
Step 3: Use the built-in type() function to find the type of the variable.
Step 4: Print the type of the variable using the print() function.
Step 5: Stop the program

## PROGRAM
```
a=bool(input())
print(type(a))
```

## OUTPUT
<img width="436" height="156" alt="image" src="https://github.com/user-attachments/assets/e1dc9a06-fa05-416e-a2c9-9b89819de8fe" />


## RESULT
Thus the program "Print the Type of the Variable" was successfully executed and verified.




# Experiment No: 1c VARIABLES & EXPRESSIONS OPERATOR- convert temperature from degree Celsius to Fahrenheit

## AIM  
To write a Python program to convert temperature from degree Celsius to Fahrenheit.

## ALGORITHM  
Step 1: Start the program.
Step 2: Read the temperature in Celsius from the user using input().
Step 3: Apply the formula to convert Celsius to Fahrenheit.
Step 4: Display the converted temperature in Fahrenheit using print().
Step 5: Stop the program.

## PROGRAM
```
a=float(input())
f = (a * 1.8) + 32
print("Celsius = {:.2f}".format(a))
print("Fahrenheit = {:.2f}".format(f))
```

## OUTPUT
<img width="567" height="277" alt="image" src="https://github.com/user-attachments/assets/e36d088b-6146-4633-b7f3-94d8e350409b" />


## RESULT
Thus the program "Convert Temperature from Degree Celsius to Fahrenheit" was successfully executed and verified.





# Experiment No: 1d CONDITIONAL STATEMENTS- find the maximum of two float numbers using conditional expression

## AIM  
To write a Python program to find the maximum of two float numbers using a conditional expression.
## ALGORITHM  
Step 1: Start the program.
Step 2: Read two float numbers from the user using the input() function.
Step 3: Use the conditional expression (ternary operator) to find the maximum number:
max=a if a>b else b
Step 4: Display the maximum number using the print() function.
Step 5: Stop the program.
## PROGRAM
```
a=float(input())
b=float(input())
max=max(a,b)
print("The maximum of {} and {} is {}".format(a,b,max))
```


## OUTPUT

<img width="897" height="208" alt="image" src="https://github.com/user-attachments/assets/108c3d8f-d5c2-434b-a9b4-64294256e4f8" />


## RESULT

Thus the program "Find the Maximum of Two Float Numbers Using Conditional Expression" was successfully executed and verified.




# Experiment No: 1e SEB- find the largest among three Integer Numbers 

## AIM  
To write a Python program to find the largest among three integer numbers.

## ALGORITHM  
Step 1: Start the program.
Step 2: Read three integer numbers from the user using the input() function.
Step 3: Use conditional statements to compare the numbers:

If a > b and a > c, then a is the largest.

Else if b > c, then b is the largest.

Otherwise, c is the largest.
Step 4: Display the largest number using the print() function.
Step 5: Stop the program.

## PROGRAM
```
a=int(input())
b=int(input())
c=int(input())
max=max(a,b,c)
print("The largest of the three a= {} b= {} c= {} is {}".format(a,b,c,max))
```

## OUTPUT
<img width="1098" height="277" alt="image" src="https://github.com/user-attachments/assets/b4f43d2a-ab97-426b-96bf-23d2f2701b7d" />


## RESULT
Thus the program "Find the Largest Among Three Integer Numbers" was successfully executed and verified.
