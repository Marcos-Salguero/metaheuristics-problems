# Metaheuristic Problems

This repository contains a set of problems that are solved using different metaheuristic techniques. The repository is structured into three main problem categories:

1. **Genetic Algorithm (GA)**
2. **Quadratic Assignment Problem (QAP)**
3. **Traveling Salesman Problem (TSP)**

Each folder contains the implementation of algorithms designed to solve the respective problem using metaheuristics.

## 📌 Project Overview  

This project aims to explore and solve different optimization problems using various metaheuristic approaches. The main focus is on implementing and understanding the mechanics of the following problems:

- **Genetic Algorithm (GA)**: Used for finding approximate solutions to optimization and search problems by mimicking the process of natural evolution.
- **Quadratic Assignment Problem (QAP)**: A fundamental problem in combinatorial optimization. The goal is to assign a set of facilities to a set of locations with the aim of minimizing the total cost.
- **Traveling Salesman Problem (TSP)**: A classic problem where the goal is to find the shortest possible route that visits each city once and returns to the starting point.

## 🚀 Features  

- **Genetic Algorithm (GA)**: Implements selection, crossover, and mutation to evolve better solutions over generations.
- **QAP**: Solves the Quadratic Assignment Problem using various metaheuristics.
- **TSP**: Solves the Traveling Salesman Problem using a genetic algorithm and other optimization techniques such as local search (steepest ascent).

## 📂 Project Structure  

📁 metaheuristics-problems  
│── 📂 Genetic_Algorithm/      # Genetic Algorithm problem solution  
│── 📂 QAP/                    # Quadratic Assignment Problem solution  
│── 📂 TSP/                    # Traveling Salesman Problem solution  
│── ── requirements.txt        # Project dependencies  
│── ── README.md               # Project documentation  

## 🛠️ Installation and Setup  

### 1️⃣ Clone the Repository  

```bash  
git clone https://github.com/Your-Username/metaheuristics-problems.git  
cd metaheuristics-problems
```

2️⃣ Create and Activate a Virtual Environment
```bash
python -m venv venv  
source venv/bin/activate  # On macOS/Linux  
venv\Scripts\activate     # On Windows
```

3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
# 🔍 Problem Descriptions and Solutions

## 1. **Genetic Algorithm (GA)**  
The Genetic Algorithm (GA) is implemented to solve optimization problems by mimicking the process of natural selection. The main components of the algorithm include:

- **Selection**: Choosing the best individuals based on fitness.
- **Crossover**: Combining the genetic information of two parents to produce offspring.
- **Mutation**: Introducing random changes to individual solutions to maintain genetic diversity.

### Example Problems:
- Solving combinatorial optimization problems.
- Function optimization problems.

## 2. **Quadratic Assignment Problem (QAP)**  
The Quadratic Assignment Problem (QAP) is a classical optimization problem that involves assigning a set of facilities to a set of locations to minimize the total cost. We use metaheuristics like simulated annealing or genetic algorithms to find good approximate solutions to the QAP.

### Example Problems:
- Facility layout optimization.
- Assigning tasks to processors in parallel computing.

## 3. **Traveling Salesman Problem (TSP)**  
The Traveling Salesman Problem (TSP) is a famous combinatorial optimization problem where the objective is to find the shortest possible route that visits each city exactly once and returns to the starting point. In this project, we use genetic algorithms along with local search techniques like the 2-opt algorithm to optimize the route.

### Example Problems:
- Route optimization in logistics and delivery.
- Tour planning for traveling.

# 📊 Usage  

## 1. **Genetic Algorithm (GA)**  
To solve a problem using the Genetic Algorithm, navigate to the `Genetic_Algorithm/` folder and run the respective script. The GA will generate a population of solutions, perform crossover and mutation, and evolve the best solution over generations.

## 2. **Quadratic Assignment Problem (QAP)**  
To solve the QAP, navigate to the `QAP/` folder and run the script that applies metaheuristics to find a near-optimal solution to the problem.

## 3. **Traveling Salesman Problem (TSP)**  
To solve the TSP, navigate to the `TSP/` folder. You can run the script that uses a genetic algorithm with recombination and mutation operators to solve the TSP.

# 📈 Results and Evaluation  

The results from solving each problem can be evaluated using various metrics:

- **For TSP**: The length of the route is the main evaluation metric. The objective is to minimize this length.
- **For QAP**: The cost associated with the assignments is used to evaluate the quality of the solution.
- **For GA**: Fitness scores and convergence rates are evaluated over generations.

Results are typically visualized using plots, such as showing the optimized TSP route or the cost reductions in QAP.

📄 License  
This project is licensed under the MIT License.

📞 Contact  
📧 Email: msalgueroc@gmail.com

🌍 GitHub: github.com/Marcos-Salguero