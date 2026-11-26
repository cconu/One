# Python-Project

# **Project Title : Bus Route Management System**
**Problem 
Statement:**
Store a bus network as a dictionary of stops and distances. The program shows a stop's connections and
finds the route with the fewest stops (BFS) between two stops, with distance and fare (Rs. 1.50 per km).
**Language:** Python 3 Concepts: Lists, Dictionaries, Graph Basics
**Note:** Roads (km): Durg-Bhilai 10, Bhilai-Raipur 30, Durg-Raipur 40, Raipur-Bilaspur 110, RaipurDhamtari 80, Durg-Rajnandgaon 45, Jagdalpur-Kondagaon 75.
**Note:** Roads work in both directions. Jagdalpur and Kondagaon are not connected to the other stops


  **Test Cases / Case Statements
(4 cases):**
INPUT EXPECTED OUTPUT
**Test Case 1: Normal Input**
Menu: Show connections
Stop: Raipur
Raipur connects to: Bhilai (30 km), Bilaspur (110 km),
Dhamtari (80 km), Durg (40 km)
Test Case 2: Boundary / Minimum Input
Menu: Find route
From: Durg
To: Durg
Source and destination are the same. Distance: 0 km.
Fare: Rs. 0.00
**Test Case 3: Invalid Input**
(a) Menu: Find route, From Durg, To Jagdalpur
(b) Menu: Show connections, Stop: Delhi
(a) No route available between Durg and Jagdalpur.
(b) Stop 'Delhi' not found.
**Test Case 4: Different Valid Scenario**
Menu: Find route
From: Bhilai
To: Bilaspur
Route: Bhilai -> Raipur -> Bilaspur
Stops: 3 | Distance: 140 km | Fare: Rs. 210.00


  **Bare Minimum Requirements:**
1. Write the solution in Python 3 (one .py file) and run it from the console.
2. Store the bus network as a dictionary of dictionaries (stop -> neighbours -> distance).
3. Show all stops and the direct connections of a chosen stop.
4. Find the route with the fewest stops between two stops using BFS.
5. Test the program with all four test cases.

   **Instruction:**
1. Understand the problem statement and define the problem clearly.
2. Develop the solution using proper logic and programming concepts.
3. Implement all required features and pass the given test cases.
4. Test and debug the project to ensure correct output.
5. Prepare the documentation/report and upload the code and report to GitHub.
6. Complete and submit the project within the given deadline.

**Asset**
[one.py](https://github.com/user-attachments/files/34248476/one.py)
