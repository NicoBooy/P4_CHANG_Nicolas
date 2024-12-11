# P4_CHANG_Nicolas - Transportation Problem Solver  
This repository contains a Python implementation for solving the transportation problem using different methods for initial feasible solutions and optimization techniques. The goal is to minimize transportation costs between suppliers and consumers using various algorithms such as Northwest Corner Rule (NWCR), Minimum Cost Method (MCM), Minimum Row Cost Method (MRCM), Vogel’s Approximation Method (VAM), and the Transportation Simplex Method.  

## Features  
Loading CSV File with Parameters: The script reads a CSV file containing the transportation cost matrix, supply, and demand data.  

## Initial Feasible Solution Methods:  
Northwest Corner Rule (NWCR): Provides an initial feasible solution based on the northwest corner of the cost matrix.  
Minimum Cost Method (MCM): Allocates supplies to demands with the minimum transportation cost.  
Minimum Row Cost Method (MRCM): Allocates supplies based on the lowest cost in each row.  
Vogel’s Approximation Method (VAM): Uses penalty costs to minimize transportation cost by allocating supplies to the most penalized routes.  

## Finding Optimal solution
Transportation Simplex Method: Optimizes the initial feasible solution by applying the simplex algorithm to minimize the total transportation cost.  
