# CIT300_Student_Campus_System
 University Student Record and Campus Route Management System developed for CIT300 Data Structures and Algorithms

Project Overview

This project is a Java console-based application developed for the CIT300 Data Structures and Algorithms practical assignment.

The system manages university student records and campus routes using different data structures and algorithms.

Main Features

Add, update,delete and display student records
Manage student service requests using a Queue
Track recent system actions using a Stack
Store and display students using a Binary Search Tree (BST)
Search students efficiently using Hashing
Add and remove campus locations
Add and remove campus connections
Display campus connections using an Adjacency List
Traverse campus locations using Breadth-First Search (BFS)
Input validation and error handling
Menu-driven console interface
Data Structures Used

Data Structure	Purpose
Linked List	Store and manage student records
Stack	Store recent system actions
Queue	Manage student service requests
Binary Search Tree	Store and display students by Student ID
Hash Table	Fast student ID searching
Graph	Represent campus locations and connections
Adjacency List	Represent graph connections
BFS	Traverse connected campus locations
Project Structure

CIT300_Student_Campus_System
│
├── src
│   ├── ActionStack.java
│   ├── CampusGraph.java
│   ├── Main.java
│   ├── ServiceQueue.java
│   ├── Student.java
│   ├── StudentBST.java
│   ├── StudentHashTable.java
│   └── StudentLinkedList.java
│
└── README.md
Group Members

Member	Student ID
Afra	23DA2-0992
Aslam	23DA2-0771
Nuha	23DA2-0988
Aksha	23DA2-1103
Responsibilities and Individual Contributions

Member	Responsibility	Individual Contribution
Afra	Student Records & Linked List (Afra)	Developed student record management and Linked List operations including add, update, delete, search and display.
Aslam	Stack + Queue	Developed Stack for recent system actions and Queue for managing student service requests using FIFO.
Nuha	BST + Hashing	Developed Binary Search Tree operations and Hash Table-based student ID searching.
Aksha	Campus Graph + BFS	Developed campus location and connection management using Graph and implemented BFS traversal.
How to Run

Step 1 – Open the Project

Open the project folder in Visual Studio Code.

Step 2 – Open Terminal

Open the VS Code terminal and navigate to the src folder:

cd src
Step 3 – Compile the Program

Run the following command:

javac *.java
Step 4 – Run the Program

Run the following command:

java Main
The main menu will be displayed in the terminal.

Menu Options

Add Student Record
Update Student Record
Delete Student Record
Display All Records using Linked List
Add Service Request to Queue
Process Next Service Request
Display Recent Actions using Stack
Display Students using BST
Search Student using Hashing
Add Campus Location
Remove Campus Location
Add Campus Connection/Road
Remove Campus Connection/Road
Display Campus Connections
Traverse Campus Locations using BFS
Exit
Input Validation

The system validates user inputs and handles:

Duplicate student IDs
Missing student records
Invalid marks
Duplicate campus locations
Invalid or unavailable campus connections
Empty queues
Invalid menu choices
Testing

The system was tested using multiple student records, service requests, stack actions and campus locations.

The following operations were successfully tested:

Adding student records
Updating student records
Deleting student records
Displaying students using Linked List
Processing service requests using Queue
Displaying recent actions using Stack
Displaying students using BST
Searching students using Hashing
Adding and removing campus locations
Adding and removing campus connections
Displaying campus connections
BFS campus traversal
Input validation
Technologies Used

Java
Visual Studio Code
Git
GitHub
Conclusion

The University Student Record and Campus Route Management System demonstrates the practical use of multiple data structures and algorithms in Java.

The project combines Linked Lists, Stacks, Queues, Binary Search Trees, Hashing and Graphs to manage student information, service requests and campus routes through a menu-driven console application. Aslam - Stack and Queue