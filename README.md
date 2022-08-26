In this lab, we will practice getting input from the user as well as showing them output. We will also start using variables.

The purpose of the program will be to allow the user to set an alarm so that it looks like:

```
Set your alarm.
Hour:
9
AM or PM (enter A or P):
P
Give a one-word alarm title:
School
School alarm has been set for 8 AM
```

In this example, the user typed in the responses: 

**9**, **P**, and **School**

First, identify what **data type** is most appropriate to store each of those three pieces of information: a **whole number**, a **letter**, and a **word**. 

Declare three variables to store those and make sure to give them meaningful names.

Next, display the message **Set your alarm.** followed by an end of line. 

At this point, check to see if there are any errors and if it displays it similar to the first line of the above example. To do so, first **compile** your code (to see if the code is grammatically correct) by typing this in the *terminal*:

`g++ main.cpp --std=c++17`

If it gives you any errors, read them and try to fix them in your code (before saving and compiling again). If it does not give any errors, then it has compiled successfully! You should then see a file called `a.out`. To run your program, type this in the terminal:

`./a.out`

Once you have that working, continue to build the user interaction:

1. Prompt for the hour
2. Have the user input their hour and store it in the appropriate variable
3. Prompt for AM/PM
4. Have the user input A or P and store that in the appropriate variable
5. Prompt the user for an alarm title
6. Have the user input the title and store that in the appropriate variable

Compile and run it and type the user input yourself to test that it works.

Finally, output the message `School alarm has been set for: ` and then display...

7.  the variable storing the hour,
8.  a literal space (`" "`)
9.  the variable storing either A or P
10.  a literal letter M (`"M"`)
11.  an end of line

Again, compile and run it and check to see what it does, compared to what was expected.