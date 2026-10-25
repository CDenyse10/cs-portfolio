# cs-portfolio
Corner Grocer Item-Tracking Program

Project Summary

The Corner Grocer Item-Tracking Program is a C++ application that reads daily grocery purchase records from an input file and counts how often each item appears. The purpose of the program is to help a grocery store understand which items customers purchase most frequently. The program allows users to search for an item's frequency, display all item frequencies, and view a histogram showing purchase counts. It also creates a backup file named frequency.dat.

What I Did Particularly Well

I did particularly well organizing the program using a GroceryTracker class and a map to store grocery items and their purchase frequencies. I also added comments to explain important parts of the code and included error messages to help users understand when a file cannot be opened. Another feature I implemented was case-insensitive searching, which makes the program easier to use. These features helped me create a program that is organized, readable, and functional.

Where I Could Enhance My Code

One area where I could improve my code is by adding more input validation and handling additional file errors. For example, I could check for whitespace-only lines in the input file and verify that the backup file was written successfully. I could also separate the class into a header file and an implementation file to make the project easier to maintain as it grows. These improvements would make the program more reliable, easier to update, and better prepared for different types of input.

Most Challenging Parts and How I Overcame Them

One of the most challenging parts of this project was working with maps to store item names and count their frequencies. I also had to make sure searches worked regardless of capitalization and that the program could read the input file and create the backup file correctly. I overcame these challenges by reviewing my code, using comments to understand each section, and testing the program with different menu options. In the future, I can use C++ documentation, course resources, debugging tools in Visual Studio, and instructor feedback to help solve programming problems.

Transferable Skills

The skills I developed in this project will be useful in future programming courses and software development projects. I practiced using C++ classes, maps, loops, functions, strings, and file input and output. I also gained experience with debugging, testing, and handling errors. These skills will help me develop programs that organize information, process data, and provide useful results to users.

Making the Program Maintainable, Readable, and Adaptable

I made the program maintainable by organizing its functionality into a GroceryTracker class with separate methods for loading items, searching frequencies, displaying results, creating a histogram, and writing the backup file. I added comments to explain the purpose of important functions and used descriptive names for variables and methods. The map keeps item records organized and supports efficient searching. Separating the program's tasks into individual methods also makes it easier to update or add features in the future.

Testing

I tested the program in Visual Studio to verify that it loaded the grocery input file and created frequency.dat. I also checked that Cranberries returned a frequency of 10, that the item frequencies and histogram displayed correctly, and that menu option four exited the program. These tests helped me confirm that the main features worked as expected.

Technologies Used

C++

Visual Studio

File input and output

Maps and strings

GitHub
