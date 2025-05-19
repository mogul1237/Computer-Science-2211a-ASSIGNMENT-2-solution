# Computer-Science-2211a-ASSIGNMENT-2-solution

Download Here: [Computer Science 2211a ASSIGNMENT 2 solution](https://jarviscodinghub.com/assignment/computer-science-2211a-assignment-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

We would like students to experience command line input with C types of character, int, and ﬂoat, to understand and use C types such as char, int, and ﬂoat, as well as the ﬂow control structures studied in class, and to use functions and recursive functions.
This assignment consists of two parts. In part one, you are required to write a C programs to perform some simple conversions. In part two, you are to wrote a C program to calculate value of exponential numbers.
Part one: 70% The goal of the exercise is to implement a simple converter, called ”converter”, which works as follows.
(1) First, the user is asked what she/he wants to do. Five characters can be entered, each corresponding to a possible action.
• 1 for conversion between Kilometer and Mile • 2 for conversion between Meter and Feet • 3 for conversion between Centimetre and Inch • 4 for conversion between Celsius and Fahrenheit • 5 for quit
(2) In case of 5, the program will terminate.
(3) In case of 1 to 4, the program will ask the direction of the conversion. In each case, two characters can be entered corresponding to each conversion direction. In case of 1, the program will prompt the user for two choices and wait for a character input
• K for conversion from Kilometer to Mile • M for conversion from Mile to Kilometer
1
In case of 2, the program will prompt the user for two choices and wait for a character input
• M for conversion from Meter to Feet • F for conversion from Feet to Meter
In case of 3, the program will prompt the user for two choices and wait for a character input
• C for conversion from Centimetre to Inch • I for conversion from Inch to Centimetre
In case of 4, the program will prompt the user for two choices and wait for a character input
• C for conversion from Celsius to Fahrenheit • F for conversion from Fahrenheit to Celsius
HINT: to read a character properly, your program should handle the leading space character, tab character, and end of line character, if any.
(4) Then the program asks for the input value, properly displays the result and returns to Step (1).
(5) The input value could be either an integer or a ﬂoat number and we assume the user will always enter valid numbers.
(6) Your program should handle non-valid character input values for (1) and (3).
(7) Your program should prompt user and display the result to user in a descriptive manner.
(8) Your program should follow good programming styles, i.e. write clear code, choose good variable names, use appropriate functions, make proper comments, and etc.
Part two: 30% The goal of this exercise is to implement an exponential number calculator, called ”exp calculator”.
(1) First, the user is asked for the base and the exponent. We assume that base is a positive ﬂoat number and exponent is an integer number.
(2) Then the exponential number is calculated using a recursive function in logarithmic time in terms of the absolute value of the exponent inputted. The result is then displayed. Hint: when n > 0 an =½ an/2 ∗ an/2 = (an/2)2 if n is even a(n−1)/2 ∗ a(n−1)/2 ∗ a = (a(n−1)/2)2 ∗ a if n is odd
2
(3) You can assume that the user always enter ﬂoat number for the base and integer number for the exponent. Your program should check if the input is positive for the base.
(4) Your program should follow good programming styles, i.e. write clear code, choose good variable names, use appropriate functions, make proper comments, and etc.
Testing your program You should test your program by running it on Gaul. For part one, each case should be tested at least once. For part two, diﬀerent bases and exponents should be tested. Capture the screen of your testing by using script command. There should be two resulting script ﬁles, one for each part.
3
