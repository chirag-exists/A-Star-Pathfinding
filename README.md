# A* Pathfinding Visualizer

An interactive pathfinding tool built with **Python** and **Pygame**[cite: 1]. It uses the A* algorithm to find the shortest path between two points while navigating around user-defined barriers[cite: 8, 11].

## 🛠️ Features
* [cite_start]**Custom Grid**: A 50x50 grid for pathfinding[cite: 16].
* **Interactive UI**: 
    * [cite_start]**Left Click**: Set Start (Orange), End (Turquoise), and Barriers (Black)[cite: 17, 18, 19].
    * [cite_start]**Right Click**: Reset nodes[cite: 20].
    * [cite_start]**Space**: Run the A* Algorithm[cite: 22].
    * [cite_start]**'C' Key**: Clear the entire grid[cite: 23].

## 🧠 How it Works
[cite_start]The algorithm uses **Manhattan Distance** as its heuristic [cite: 7] [cite_start]to calculate the $f\_score$ of each node ($f(n) = g(n) + h(n)$)[cite: 8, 11].
