Pathfinding using A*Algorithm:
This project is a web-based visualization of the A* (A-star) pathfinding algorithm, created using HTML, CSS, and JavaScript. It demonstrates how the A* algorithm finds the shortest path between a start node and a target node in a grid-based environment.

The A* algorithm works by evaluating the cost of moving from the start node to the target node. It uses a formula f(n)=g(n)+h(n)f(n) = g(n) + h(n)f(n)=g(n)+h(n), where g(n)g(n)g(n) is the actual cost from the start node to the current node, and h(n)h(n)h(n) is the heuristic estimate of the remaining cost to the target. The algorithm prioritizes nodes with the lowest total cost f(n)f(n)f(n), exploring neighbors of each node and updating their paths if a more efficient route is found. Once the target is reached, the algorithm backtracks through the nodes to reconstruct the shortest path.


How to Use
1.	Open the project in your browser.
2.	Set the start and end nodes by clicking on the grid.
3.	Add obstacles by clicking on other grid cells.
4.	Click "Start" to visualize the algorithm in action.
5.	Watch the algorithm explore the grid and highlight the shortest path.

   
This project provides an engaging platform to visualize pathfinding concepts while demonstrating the practical application of the A* algorithm.
