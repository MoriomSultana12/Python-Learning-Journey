Chapter 1.1 :Basics of Python - Atoms, Variables, and Syntax

1. Constants
  Definition:Fixed values in a program that do not change
  Types- 
  Numeric Constants:int(12343),floating-point numbers(98.7)
  String Constants:"Hello World"

2.Reserved Words
  Definition: keywords in python with predefined meanings.
  Example- class,del,else,lamda,break,from,in,etc
  Rule: can not use these names as variable names, function names, or class names 

3.Variables 
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
4.Assignment and Memory Management
  The = operator stores values in variables
  x=2
  x=x+2    #adds 2 to x and stores the result in x 
  print(x) #output 4

5.Print Function
  Syntax: print()
  print("Hello,World!!")

6.Mnemonic Variable Names:
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




