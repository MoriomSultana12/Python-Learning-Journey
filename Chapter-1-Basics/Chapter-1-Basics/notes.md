**Chapter 1.1: Basics of Python - Atoms, Variables, and Syntax**

1. **Constants**
  Definition:Fixed values in a program that do not change
  Types- 
  Numeric Constants:int(12343),floating-point numbers(98.7)
  String Constants:"Hello World"

2.**Reserved Words**
  Definition: keywords in python with predefined meanings.
  Example- class,del,else,lamda,break,from,in,etc
  Rule: can not use these names as variable names, function names, or class names 

3.**Variables**
  Definition:Named storage location in a memory that hold a data
  Assignment Statement-
  x=12.2   #assigns 12.2 to x 
  y=14     #assigns 14 to y
  x=100    #updates x with a new value
  Rules for naming the variables-
      Must start with a letter or an underscore(_) , but avoid _ at the beginning
      can contain letters, numbers and underscores
      Case-sensitive:spam,Spam and SPAM are different
      Should not start with a num or contain special characters(@,$,%)
4.**Assignment and Memory Management**
  The = operator stores values in variables
  x=2
  x=x+2    #adds 2 to x and stores the result in x 
  print(x) #output 4

5.**Print Function**
  Syntax: print()
  print("Hello,World!!")

6.**Mnemonic Variable Names**:
  Definition: Using meaningful variable names for better code readability
  Unclear naming -
      a=12
      b=34
      c=(a*b)
      print(c)
  Better naming-
      hours=35
      rate=12
      pay=hours*rate
      print(pay)

# Chapter 1.2 - Expressions 

## Overview
This lecture covers advanced concepts of expressions in Python, including type conversion, operator precedence, and evaluation rules.

## Arithmetic Expressions
Expressions in Python consist of values and operators. They are evaluated following Python's precedence rules.

## Order of Operations (Precedence Rules)

1. **Parentheses** `()` - Highest precedence
2. **Exponentiation** `**`
3. **Unary operators** `+`, `-` (e.g., `-x`, `+y`)
4. **Multiplication, Division, Modulus, Floor Division** `*`, `/`, `%`, `//`
5. **Addition, Subtraction** `+`, `-`
6. **Comparison operators** `<, >, <=, >=, ==, !=`
7. **Logical operators** `not`, `and`, `or`

## **Examples:**

print(2 + 3 * 4)  # Output: 14 (Multiplication has higher precedence)
print((2 + 3) * 4)  # Output: 20 (Parentheses override precedence)
print(10 / 3)  # Output: 3.3333 (True division)
print(10 // 3)  # Output: 3 (Floor division - integer result)
print(10 % 3)  # Output: 1 (Modulo - remainder of division)
print(2 ** 3)  # Output: 8 (Exponentiation)

## **Type Conversions in Expressions**
Python performs **implicit type conversion** when necessary:
- Integer and float operations result in **float**.
- Explicit conversion can be done using `int()`, `float()`, or `str()`.

### **Example:**
print(3 + 2.5)  # Output: 5.5 (int + float → float)
print(int(3.9))  # Output: 3 (Explicit conversion, truncates decimal part)
print(float(3))  # Output: 3.0 (Explicit conversion to float)
print(str(25))  # Output: '25' (Converts integer to string)

## **Complex Expressions**
Expressions can be written using different types of operators and functions:
x = 5
y = 3
result = (x ** 2 + y ** 2) ** 0.5  # Calculates the hypotenuse
print(result)  # Output: 5.830951894845301

## **Boolean Expressions**
Boolean expressions evaluate to `True` or `False` using comparison and logical operators.

print(5 > 3)  # Output: True
print(10 == 10)  # Output: True
print(10 != 5)  # Output: True
print(5 < 3)  # Output: False

## **Logical Operators:**
print(True and False)  # Output: False
print(True or False)  # Output: True
print(not True)  # Output: False

## input() function. Here’s a simple example:
name = input("Who are you?")
print("Hello" , name)

## **Summary**
- **Python evaluates expressions following precedence rules.**
- **Type conversion happens automatically, but explicit conversion is also possible.**
- **Boolean expressions return `True` or `False`.**
- **Logical operators (`and`, `or`, `not`) help in evaluating conditions.**









