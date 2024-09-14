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
        Welcome to the repository for the <strong>Optimal Strategy for Minimum Cost from City1 to City2</strong> project. This application is designed to find the minimum cost path from a starting city to a destination city using Dynamic Programming techniques. The project involves calculating the most cost-effective route considering travel distances, petrol costs, and hotel costs.
    </p>

    <h2>Features</h2>
    <h3>Input Data</h3>
    <ul>
        <li><strong>Number of Cities:</strong> Total number of cities involved in the problem.</li>
        <li><strong>Start and End Cities:</strong> Specify the starting and ending cities for the journey.</li>
        <li><strong>Adjacent Cities:</strong> List of cities adjacent to each other, including travel distances and costs.</li>
        <li><strong>Petrol Cost:</strong> The cost of petrol required to travel between cities.</li>
        <li><strong>Hotel Cost:</strong> The cost of staying at hotels in each city.</li>
    </ul>

    <h3>Output</h3>
    <ul>
        <li><strong>Optimal Path:</strong> The most cost-effective route from the start city to the end city.</li>
        <li><strong>Minimum Cost:</strong> The total cost for the optimal path.</li>
        <li><strong>Alternative Solutions:</strong> Additional feasible paths with their respective costs.</li>
        <li><strong>Dynamic Programming Table:</strong> The DP table used for calculating the minimum cost and path.</li>
        <li><strong>User Interface:</strong> A graphical interface to display results and interact with the application.</li>
    </ul>

    <h2>Technical Stack</h2>
    <ul>
        <li><strong>Algorithm:</strong> Dynamic Programming for solving the minimum cost path problem.</li>
        <li><strong>File Handling:</strong> Read and parse input data from a text file.</li>
        <li><strong>Data Structures:</strong> Use linked lists and other appropriate data structures to manage and compute data efficiently.</li>
        <li><strong>GUI:</strong> JavaFX for creating a user-friendly graphical interface.</li>
    </ul>

    <h2>Input Data Example</h2>
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

    <h2>Performance Considerations</h2>
    <p>
        Analyze and discuss the time complexity of the Dynamic Programming approach used in the project. Be prepared to explain how the algorithm handles different scenarios, including the efficiency and computational cost of solving the minimum cost problem.
    </p>
</body>
</html>


![ؤ](https://github.com/user-attachments/assets/63a370fb-e0cb-48f1-a53d-aaa04937f32d)









