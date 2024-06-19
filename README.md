# S6_Alt2_Optimization

# Optimization Algorithms

This repository contains implementations of various optimization algorithms in Jupyter Notebooks. The algorithms covered include Gradient Descent, Simulated Annealing, Particle Swarm Optimization (PSO), and Genetic Algorithms (GA) for solving the Travelling Salesman Problem (TSP).

## Contents

1. [Gradient Descent and Simulated Annealing](GradientDescent_SimulatedAnnealing.ipynb)
2. [Particle Swarm Optimization (PSO)](PSO.ipynb)
3. [Genetic Algorithms (GA) for TSP](TSP_GAs/TSP_GAs.ipynb)

## Notebooks

### 1. Gradient Descent and Simulated Annealing

- **File:** [GradientDescent_SimulatedAnnealing.ipynb](GradientDescent_SimulatedAnnealing.ipynb)
- **Description:** This notebook demonstrates the implementation of Gradient Descent and Simulated Annealing algorithms. These algorithms are used for optimization tasks, such as finding the minimum of a function.

### 2. Particle Swarm Optimization (PSO)

- **File:** [PSO.ipynb](PSO.ipynb)
- **Description:** This notebook covers the Particle Swarm Optimization algorithm, which is inspired by the social behavior of birds. It is used to solve optimization problems by having a population of candidate solutions (particles) move around the search space according to simple mathematical rules.

### 3. Genetic Algorithms (GA) for Travelling Salesman Problem (TSP)

- **File:** [TSP_GAs.ipynb](TSP_GAs/TSP_GAs.ipynb)
- **Description:** This notebook implements Genetic Algorithms to solve the Travelling Salesman Problem (TSP). It includes functions for creating the initial population, calculating fitness, performing crossover and mutation, and evolving the population over generations.

## How to Use

1. **Clone the repository:**
   ```sh
   git clone https://github.com/mcrayssac/optimization-algorithms.git
   ```
   
2. **Navigate to the repository directory:**
  ```sh
  cd optimization-algorithms
  ```

3. **Install the required dependencies:**
  ```sh
  pip install numpy pandas matplotlib seaborn geopy geopandas contextily imageio
  ```

4. **Open the Jupyter notebooks:**
  ```sh
  jupyter notebook
  ````	
  - This will open the Jupyter Notebook interface in your web browser. You can then navigate to the specific notebook you want to explore (e.g., GradientDescent_SimulatedAnnealing.ipynb, PSO.ipynb, TSP_GAs.ipynb).

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries: numpy, pandas, matplotlib, seaborn, geopy, geopandas, contextily, imageio

Acknowledgements
- [Geopy](https://geopy.readthedocs.io/)
- [Geopandas](https://geopandas.org/)
- [Contextily](https://contextily.readthedocs.io/)
- [Imageio](https://imageio.readthedocs.io/)

## Author
Maxime Crayssac - mcrayssac
