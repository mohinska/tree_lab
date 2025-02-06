# Algorithm Analysis and Decision Tree Classifier
**Team 9. Maryna Ohinska, Maksym Hobela**

## Overview
This repository contains implementations and performance analysis of classical graph algorithms and a decision tree classifier. The project is structured into two main parts:

1. **Graph Algorithm Analysis**
2. **Decision Tree Classifier**

## 1. Graph Algorithm Analysis
This section includes implementations and comparisons of graph algorithms, focusing on:

- **Minimum Spanning Tree (MST)**: Prim's and Kruskal's algorithms.
- **Shortest Path Algorithms**: Bellman-Ford algorithm.
- **Performance Benchmarking**: Comparison with `NetworkX` built-in implementations.

### Implementation Details
- **Custom Implementations**: Implemented Prim's and Kruskal's algorithms for MST, and Bellman-Ford for shortest path.
- **Efficiency Testing**: Each algorithm was executed multiple times to obtain consistent execution times, which were compared against the corresponding `NetworkX` implementations.
- **Negative Weight Handling**: Included check for negative cycles in Bellman-Ford algorithm.
- **Visualization**: Execution time results were plotted to provide insights into algorithm performance under different graph sizes and densities.

### Experimental Setup
- Randomly generated connected graphs with varying sizes.
- Edge probability varied to test different densities.
- Execution time recorded and compared for each of 100 iterations to get average execution time.
- Results visualized with performance graphs.

## 2. Decision Tree Classifier
This section focuses on implementing a decision tree classifier from scratch and comparing its performance with `sklearn`'s `DecisionTreeClassifier`.

### Implementation Details
- **Custom Decision Tree Implementation**: Developed a decision tree classifier capable of handling categorical and numerical data.
- **Splitting Criteria**: Implemented information gain and Gini impurity for splitting nodes.
- **Tree Construction**: Recursively built the tree, handling edge cases like pure splits and minimal data points.
- **Prediction Function**: Implemented a traversal method to classify new data points.
