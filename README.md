# Solving the Traveling Salesman Problem with Genetic Algorithms

## 📌 Description
This repository contains the implementation of a **genetic algorithm** to solve the **Traveling Salesman Problem (TSP)**, optimizing the most efficient route to visit a set of cities and return to the starting point.

This project was developed as the final project for the **Computer Science** course in the third year of the Computer Engineering degree at the Public University of Navarra (UPNA).

## 🏆 Project Objectives
- Apply **genetic algorithms** for route optimization.
- Compare different strategies for **selection, crossover, and mutation**.
- Evaluate the impact of algorithm parameters on solution quality.

## 🚀 Technologies Used
- **Python** 🐍
- **NumPy** for data manipulation.
- **Matplotlib** for result visualization.
- **Genetic algorithms** implemented from scratch.

## 📂 Project Content
1. **Introduction and objectives**: Description of the problem and its relevance.
2. **Genetic Algorithms**: Explanation of the functioning and operators.
3. **Problem definition**:
   - Chromosome encoding.
   - Definition of the cost function.
4. **Experimentation**:
   - Comparison of different selection and crossover methods.
   - Evaluation with and without mutations.
5. **Results and analysis**.
6. **Conclusions**.

## 📊 Experimentation
Tests were performed with different algorithm configurations:
- **Selection methods**: Roulette, Tournament (k=2, k=5, k=10).
- **Crossover methods**: PMX (Partially Mapped Crossover), Order.
- **Mutation methods**: Swap, Insertion.
- **Initial population**: 100 individuals.
- **Number of generations**: 1000.

The best result obtained was **an optimal route of 4367 km** using **Order Crossover and Roulette Selection**.
