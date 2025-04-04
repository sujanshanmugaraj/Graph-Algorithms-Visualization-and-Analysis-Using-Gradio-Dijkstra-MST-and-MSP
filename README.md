# Interactive Graph Algorithm Visualizer with CPU & GPU Acceleration

## Overview:

This project develops an interactive visualization tool for graph algorithms, focusing on shortest path (Dijkstra’s algorithm) and minimum spanning tree (Kruskal’s algorithm). It provides a comparative analysis of CPU and GPU execution times, offering insights into performance optimization using CUDA. The tool uses real-time graph rendering, animation, and interactive input to enhance learning and analysis.

## Tools & Technologies:

Development: Python, Gradio, Matplotlib, NetworkX, NumPy, CuPy, Flask


Graph Algorithms: Dijkstra’s Algorithm (CPU & GPU), Kruskal’s MST


Visualization & Animation: Matplotlib, NetworkX, Gradio, Pillow


GPU Acceleration: CuPy, CUDA


## Methodology & Approach:

Graph Input & Parsing: Users provide graph data in edge-list format, specifying vertices, edges, source, and sink nodes. The system parses and structures the data dynamically.


Dijkstra’s Shortest Path (CPU & GPU):


The CPU version uses NetworkX’s built-in Dijkstra algorithm for path computation.


The GPU version is implemented using CuPy for optimized parallel processing, enhancing speed for large graphs.



Kruskal’s Minimum Spanning Tree (CPU & Simulated GPU):


The CPU-based implementation sorts edges and applies the union-find algorithm for MST construction.


The GPU performance is currently simulated, with potential future integration using CuGraph.










## Graph Visualization:


The system generates static graph renderings and highlights paths or MST edges.


Users can choose between circular and force-directed layouts for a better graphical representation.



Real-time Animation:


Step-by-step visualization of the shortest path or MST construction using Matplotlib animation.


Animated GIF output for interactive analysis of algorithm execution.



## Key Insights:

Comparative Performance Analysis: Evaluates CPU vs. GPU execution times to showcase acceleration benefits.

Graph Learning & Debugging: Helps users understand algorithm steps through real-time visualization and animations.

Customizable Layouts & Graph Styles: Offers flexibility in node positioning and graphical representation.

Scalability for Large Graphs: Supports complex graph inputs, making it useful for researchers and students.

## Conclusion:

This project provides an interactive and educational tool for exploring graph algorithms, demonstrating CPU-GPU performance differences, and enhancing algorithm comprehension through real-time visualization. It serves as a valuable learning resource for students, researchers, and professionals in graph theory and optimization.

