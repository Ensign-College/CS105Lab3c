Lab 3c
======

Submit your finished code to the Dropbox. You will need to pass off the lab with the TA or tutor during their office hours (their information is in the CS 105 Course Information section of the Class Resources module), or the instructor in class. Follow the CS 105 Formatting Guide which is also found in the CS 105 Course Information section.

Read the instructions carefully. Make sure your output matches the example run.

Objectives:
===========

In this lab, you will learn how to do the following:

-   Use nested if statements
-   Use the String method equals() or its variant equalsIgnoreCase()
-   Translate categories described in a table into logical code

Structure:
==========

Create the following structure in Eclipse for this lab.

-   **Package Name: w**eek3
-   **Class Name: **Lab3c

String method equals():
=======================

You can't use the == operator to compare Strings in Java.  You must use the String method equals() or its variant equalsIgnoreCase().  Both methods return a Boolean value (true or false).

Format:  string1.equals(string2);

Examples:

Assume the user input the word "Male" and the program stored the user input into a String variable called 'gender':

Images 

Program: Sunday Classes
=======================

In this lab, you will create a program that will determine which class a member of the Church should attend on Sunday based on their age and gender. You will ask the user to enter a person's age and, **if necessary**, their gender.  The following conditions determine which class the person should attend:

Key program requirements:
=========================

-   Good programs only ask users for information they need to perform their tasks and your program should do the same. In other words, don't ask the user for the person's gender unless absolutely necessary.
-   Allow the user to enter either an 'M' or an 'm' to specify male.
-   Allow the user to enter either an 'F' or an 'f' to specify female.
-   Use nested if statements
-   Use the equals() or equalsIgnoreCase() method
-   Submit the following .java file:
-   -   Lab3c.java

Example Run:
============

*This program will ask a member's age and gender and determine which class they should attend on Sunday.*

*Please enter the member's age:*\
*0*\
*The member is a Babe in Arms.*

*--------------------------------------*

*This program will ask a member's age and gender and determine which class they should attend on Sunday.*

*Please enter the member's age:*\
*2*\
*The member should be in Nursery.*

*--------------------------------------*

*This program will ask a member's age and gender and determine which class they should attend on Sunday.*

*Please enter the member's age:*\
*8*\
*The member should attend Primary.*

*--------------------------------------*

*This program will ask a member's age and gender and determine which class they should attend on Sunday.*

*Please enter the member's age:*\
*16*\
*Please enter the member's gender:*\
*f*\
*The member should attend Young Women's.*

*--------------------------------------*

*This program will ask a member's age and gender and determine which class they should attend on Sunday.*

*Please enter the member's age:*\
*23*\
*Please enter the member's gender:*\
*M*\
*The member should attend Priesthood.*