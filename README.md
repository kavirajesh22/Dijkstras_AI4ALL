# Dijkstra's Algorithm For Path Planning

Final AI4ALL (Summer 2020) Project by Kavi Rajesh

Project Problem Info: 
Fast access for blood and other medical supplies are vital for public health. Blood transfusions save around 4.5 million lives per year in the United States, but storage and distribution makes equal access hard. We have discovered a solution to provide fast access to medical supplies through drones, limiting the reliance on existing and slow delivery processes. 

General Info:
Search algorithms can be used to find a path from the start location to the end location that the drone would lay out. Dijkstra's is a single-source shortest path algorithm. Dijkstra's algorithm may be used to find the shortest path from the start location to the desired end location, or from the start location to all nodes, or vertexes, inside the graph. In this project, Dijkstra's algorithm is used to find the shortest path from the hypothetical start location to all nodes in the graph.

Implementation Procedure:
1. Found a satellite map image of Los Angeles (11 * 18). Converted this into a NumPy Array, and visualized. Green=Flyable (1), Red= Not Flyable (0)
2. Performed Uniform Cost Search (also Unoptimized Dijkstra's) 
3. Performed Dijkstra's

View the Visualization of the costs using Dijkstra's algorithm in the Dijkstra's Algorithm AI4ALL Final Project (1).ipynb file.
