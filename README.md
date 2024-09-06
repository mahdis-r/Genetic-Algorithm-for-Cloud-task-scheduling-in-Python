# Genetic-Algorithm-for-Cloud-task-scheduling-in-Python

## 1. Initial Setup:

The notebook imports necessary libraries like `random` and `plotly` for visualizing the results.
Parameters related to task scheduling and the cloud environment are defined.

## 2. Generate Initial Population:

A function `generate_initial_population()` is created, to initialize a population of potential solutions based on some heuristic like "Longest Cloudlet to Fastest Processor (LCFP)."

## 3. Fitness Function:

The `evaluate_fitness()` function is defined to evaluate the quality of each task schedule. It distributes tasks among processors and calculates the fitness of the schedule, which would indicate how well tasks are balanced across processors.

## 4. Genetic Algorithm:

The `genetic_algorithm()` function contains the main logic for running the GA. It includes:
- Generating the initial population.
- Keeping track of the best and average fitnesses across generations.

## 5. Visualization:

Plotly is used to visualize the results, which is the fitness scores over time or generations for different scheduling algorithms.

### References:
Here is the link to the publication I used to implement this modified genetic alorithm for cloud task scheduling: https://www.researchgate.net/publication/265662159_An_Efficient_Approach_to_Genetic_Algorithm_for_Task_Scheduling_in_Cloud_Computing_Environment
