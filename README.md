# Traveling Salesman Problem (TSP) Optimization

## Project Overview
This project implements a solution to the Traveling Salesman Problem (TSP), a classical NP-hard combinatorial optimization problem. The objective is to determine the shortest possible tour that visits each city exactly once and returns to the starting city.

## Problem Definition
Given the coordinates (x, y) of cities provided in a CSV file, the goal is to compute the minimum-cost Hamiltonian cycle by minimizing the total Euclidean distance traveled.

## Methodology
- City coordinates are loaded from a CSV dataset using Pandas.
- Euclidean distances between cities are computed programmatically.
- Total route cost is calculated dynamically.
- Optimization logic is implemented to search for an improved tour.
- Performance-critical computations are accelerated using Numba (@njit).
- Execution time is measured for performance evaluation.

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib (route visualization)
- Numba (performance optimization)
- Math
- Random

## Dataset
The CSV file contains city coordinates.
The dataset file must remain in the same directory as the notebook for correct execution.

## How to Run
1. Download the repository.
2. Ensure the CSV dataset file is in the same directory as the notebook.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells sequentially.

## Academic Context
This project was developed as part of an Industrial Engineering coursework focused on optimization, algorithm design, and computational efficiency analysis.

