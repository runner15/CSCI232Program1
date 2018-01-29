# CSCI232Program1

CSCI 232: Data Structures and Algorithms
Programming Assignment 1: Huffman Codes
Due Date:  2/6/2018 by 11:59 PM.
Teams: You must work in a team of two or three students (you plus one or two other students) for this assignment. Your partners must be from your lab section. 20 points will be deducted from your grade if you do not work in a team.
Purpose: One of the binary tree applications that we talked about in lecture was the assigning of Huffman codes to characters that appear in a message. The intention is that once the characters are given Huffman codes, that the message can be compressed to require fewer bits than before. In this assignment, you will write a program that reads in an input file, encodes the characters using Huffman coding, and then decodes the message from binary back to text.
What to do:
Setup: Setup input and output text files similar to lab 1. The input file to encode will be named “input.txt”. The decoded message should be written to “output.txt”. Be sure to add a message to input.txt, so you can test your application.When your program is working correctly, the contents of input.txt and output.txt should be the same. During the execution of your program, pr  int the original message, the frequency table, code table, and encoded message to the console.
Here are the general steps to follow:
•Accept a text message.
•Construct a frequency table for the message.
•Create a Huffman tree for this message.
•Create a code table.
•Encode the message into binary
•Decode the message from binary back to text.
Note that you can use String variables to store binary numbers as arrangements of characters 1 and 0. Do not do actual bit manipulations for this assignment.Also, note that your program should work for any text message (not just the one you initially added to input.txt to test your program).Using the following as a template, place a comment near the top of each java file you submit containing accurate information about the author(s), date, and overview of the program.
/* * Authors: <Insert names of yourself and group you are working with> * Date: <Date you submitted the assignment> * Overview: <Program overview. What is this software? Do you have * any special instructions to run this software?>*/
Note feel free to use/modify the TreeApp.java code on the course website as part of this project. If you do,  please attribute the source (Robert Lafore. 2002.Data Structures and Algorithms in Java(2 ed.). Sams, Indianapolis, IN, USA) in a comment.
Grading Criteria: 
oOriginal message is read from input.txt and is displayed to console correctly (10 points)
oA comment near the top of each java file contains accurate information about the author(s), date, and overview of the program (10 points)
oFrequency table is correct and displays to console (20 points)
oCode table is correct and displays to console (20 points)
oOriginal message is encoded and displayed to console correctly (20 points)
oEncoded message is decoded and written to output.txt correctly (20 points)
Submission: Upload your project to D2L. In a comment, submit the names of your partners along with any special instructions for running your program. If the TA cannot run the program, you will initially receive a 0 for the assignment until you can demonstrate to the TA that the uploaded program runs. The D2L assignment drop box will close at 11:59 PM on the day the lab is due. Late assignments will not be accepted and a grade of 0 will be assigned. (Exceptions will be made for extraordinary circumstances, such as an excused medial emergency). If your project is not finished, upload what you have as partial credit may be given as long as the project compiles and runs.  
Collaboration:  Students are required to work in groups of two or three on this assignment. 
•You may
oWork with the other people on your team if teams are allowed. Each assignment will specify the maximum number of people per team.
oShare ideas with people in other teams.
oHelp other teams troubleshoot problems.
