  **CITY PATH FINDER OR MAP NAVIGATOR USING DIJKSTRA'S ALGORITHM**



**PROJECT OVERVIEW**:

  To create a console-based India Map Navigator that helps users find the shortest route between two cities in India using Dijkstra’s algorithm.



**OBJECTIVES**
1. Build a graph of Indian cities connected by roads with defined distances.
2. Implement Dijkstra's algorithm to find the shortest path between two cities.
3. Display the shortest path and total distance.



**KEY FEATURES:**

1.Graph-Based Representation:

Each city is a node, and each road (distance) is an edge.
Stored using unordered_map for fast lookups.

2. Shortest Path Calculation:

Uses Dijkstra's algorithm with a priority queue (min-heap) for efficiency.
Keeps track of minimum distances and previous nodes.

3.User Interaction:

User inputs starting and destination cities.
Program calculates and displays the shortest route and total distance.

4.Data Handling:

Supports multiple cities and routes.
Handles invalid inputs and cases where no path exists.



**TECHNOLOGIES USED**
1. C++ – Core programming language
2. STL (Standard Template Library): unordered_map, priority_queue, vector.


   

**SAMPLE OUTPUT**

Enter the starting city: Delhi
Enter the destination city: Mumbai
Shortest path from Delhi to Mumbai: Delhi -> Jaipur -> Ahmedabad -> Mumbai
Total distance: 1400 units



**Why Dijkstra’s Algorithm?**
1.Efficient for weighted graphs.
2. Ensures shortest path calculation with non-negative weights.
3. Handles large data sets effectively.



**CHALLENGES**

Managing graph creation and connectivity.
Handling edge cases (invalid city names, no paths).

**OUTCOME**
A functional navigation system for Indian cities, providing an optimized shortest path solution using Dijkstra’s algorithm.




