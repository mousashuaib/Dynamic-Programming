<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Optimal Strategy for Minimum Cost</title>
</head>
<body>
    <h1>Optimal Strategy for Minimum Cost from City1 to City2</h1>

    <h2>Overview</h2>
    <p>
        Welcome to the repository for the <strong>Optimal Strategy for Minimum Cost from City1 to City2</strong> project. This application is designed to solve the problem of finding the minimum cost route from a starting city to a destination city using Dynamic Programming techniques. The project involves calculating the optimal travel route while considering both the travel costs (e.g., petrol) and accommodation costs (e.g., hotel stays).
    </p>

    <h2>Project Definition</h2>
    <p>
        The goal of this project is to develop a program that determines the most cost-effective route from a starting city (city1) to a destination city (city2) considering:
    </p>
    <ul>
        <li><strong>Number of Stopovers:</strong> There are multiple stopovers between the start and end cities, each with various options for towns and hotels.</li>
        <li><strong>Travel Costs:</strong> Each trip segment between cities has a different petrol cost.</li>
        <li><strong>Hotel Costs:</strong> Different hotels in each city have varying costs.</li>
        <li><strong>Objective:</strong> Select the route and hotel in the destination city to minimize the overall trip cost.</li>
    </ul>

    <h2>Input Data Format</h2>
    <p>
        The input data for the project will be read from a file with the following format:
    </p>
    <ul>
        <li><strong>Number of Cities:</strong> The total number of cities.</li>
        <li><strong>Start City, End City:</strong> The starting and ending cities for the trip.</li>
        <li><strong>List of Adjacent Cities:</strong> Details of cities adjacent to each other, including travel distance and cost.</li>
        <li><strong>Petrol Cost:</strong> Cost associated with traveling between cities.</li>
        <li><strong>Hotel Cost:</strong> Cost of staying in different hotels in each city.</li>
    </ul>
    <p>
        Example:
    </p>
    <pre>
14
Start, End
Start, [A,22,70], [B,8,80], [C,12,80]
A, [D,8,50], [E,10,70]
B, [D, 25, 50], [E,10,70]
C, [D,13,50], [E,13,70]
Petrol cost
Hotel cost
D, [F,25,50], [G,30,70], [H,18,70], [I, 27,60]
E, [F,12,50], [G,10,70], [H,8,70], [I, 7,60]
F, [J,26,50], [K,13,70], [L,15,60]
G, [J,8,50], [K,10,70], [L,10,60]
H, [J,20,50], [K,10,70], [L,10,60]
L, [J,15,50], [K,10,70], [L,7,60]92
J, [End,10,0]
K, [End,10,0]
L, [End,10,0]
    </pre>

    <h2>Expected Results</h2>
    <p>
        The program should output:
    </p>
    <ul>
        <li><strong>Optimal Path:</strong> The most cost-effective route from the start city to the end city.</li>
        <li><strong>Minimum Cost:</strong> The total cost of traveling along the optimal path.</li>
        <li><strong>Alternative Solutions:</strong> Other feasible paths with their respective costs.</li>
        <li><strong>DP Table:</strong> The Dynamic Programming table used to compute the minimum cost and path.</li>
        <li><strong>User Interface:</strong> A graphical user interface (GUI) to present the results and allow for user interaction.</li>
    </ul>

    <h2>Technical Specifications</h2>
    <ul>
        <li><strong>Algorithm:</strong> Implement the Dynamic Programming technique to solve the minimum cost problem.</li>
        <li><strong>File Handling:</strong> Read input data from a file and process it to extract necessary information.</li>
        <li><strong>GUI Implementation:</strong> Develop a user-friendly interface to display results and interact with the application.</li>
        <li><strong>Data Structures:</strong> Utilize appropriate data structures to manage and compute the data efficiently.</li>
    </ul>

    <h2>Performance Considerations</h2>
    <p>
        Ensure to analyze and discuss the time complexity of the Dynamic Programming approach used in the project. Be prepared to explain how the algorithm handles different scenarios and the efficiency of the solution.
    </p>
</body>
</html>


![ؤ](https://github.com/user-attachments/assets/63a370fb-e0cb-48f1-a53d-aaa04937f32d)









