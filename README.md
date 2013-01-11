Programming Skills Test (Hands-on programming skills)
=============

* Loop Control
* Operators
* String Handling
* Arrays
* Hash table/Collections
* Regular Expressions
* Numbers
* Files & I/O

### 1. Maximum fluctuation
  
  Write a program that accepts a comma separated string of numbers depicting the daily stock price of AXY Company. The program should calculate the biggest daily fluctuation (in terms of percentage) of the stock price on any given day.

  For example, let us suppose the following is the input string:

  INPUT
  
    20,23,25,30,22,21,16

  Then the corresponding biggest fluctuation is:

  OUTPUT
  
    26.6666666666667 (As the maximum fluctuation in price is between 22 and 30)

### 2. Palindromes

  Write a program that accepts 4 words as input (one per line) and identifies whether they are palindromes. A palindrome is a word that reads the same when read back to front. The program should print the alphabetically sorted list of palindromes (one per line). The program output should be in lowercase.
  
  INPUT

    waas
    gaag
    haaha
    ABBA

  OUTPUT

    abba
    gaag
    
### 3. Area of the square

Write a program which will take the volume of the cube as its input. The program should calculate the area of a square whose side is half the length of the side of 
the cube. The program should print the area of the square. 

Definitions:

Volume of cube = a*a*a, where a is the side of a cube

Area of Square = b*b, where b is the side of the square

For example, let us suppose the following is the volume inputted to the program:

  INPUT
  
    8
    27

Then the corresponding output will be as follows:

  OUTPUT

    1
    2.25

### 4. First and last digit of the sum

Write a program which will accept a number as its input. You are required to calculate the sum of the first and last digits of the square of the number given as inp
ut. In case the square of the number is a single digit number then the square should be printed as it is.

For example, let us suppose the following input is given to the program:

  INPUT

    3
    5
    6

Then the corresponding output should be:

  OUTPUT

    9
    7
    9
    
### 5. Number to ASCII

Write a program that accepts a number of ASCII values between 40 and 125 (both inclusive) and concatenates the corresponding characters to form a string. The progra
m accepts a multi-line input. The first line contains a number representing how many ASCII values are in the input. The subsequent lines contain the ASCII values th
emselves (one ASCII value per line).


The following is an example of a valid input:

INPUT

    5 (this indicates the total number of ASCII values in the input set)
    65
    67
    69
    70
    71

The output is printed as a string. The ASCII value of A is 65, C is 67, E is 69, F is 70, G is 71 and therefore the output will be as follows:

OUTPUT

    ACEFG

### 6. Sort racers

During a car rally the time keeper wrote down the driver names along with their finishing positions in random order. Write a program to sort the names of the driver
s in ascending order of their finishing positions.


For example, let us suppose the following input is given to the program:

INPUT

    Eddie-3
    Michael-1
    Nica-4
    Montoya-6

Then the program should print the output as follows:

OUTPUT

    Michael-1
    Eddie-3
    Nica-4
    Montoya-6
