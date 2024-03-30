# Linear-Equation-Solver-using-LU-Decomposition

This repository contains implementations of a linear equation solver capable of solving systems of linear equations with multiple unknowns. Three different implementations are provided: a single-threaded application, a multi-threaded application using individual threads, and a multi-threaded application utilizing a thread pool.

## Problem Statement

The task is to implement an efficient algorithm for solving systems of linear equations with \( n \) unknowns. The chosen algorithm should support parallelization, enabling the decomposition of the problem into independent parts for concurrent processing.

## Implementations

### Single Threaded Application

The single-threaded implementation solves the system of linear equations sequentially without parallelization.

### Multi-threaded Application (Individual Threads)

This implementation utilizes individual threads to parallelize the solving of multiple linear systems. Each linear system is solved concurrently using separate threads.

### Multi-threaded Application (Thread Pool)

The thread pool implementation employs a thread pool to manage multiple threads efficiently. The thread pool dynamically allocates threads to solve linear systems, optimizing resource utilization.

## Usage

1. **Clone the Repository:**

   ```bash
   [git clone https://github.com/your_username/linear-equation-solver.git](https://github.com/kingmudassir/Linear-Equation-Solver-using-LU-Decomposition.git)

Open the Project:
Open the project in Visual Studio.

Build and Run:
Build and run each implementation to observe their behavior and performance.

# Input Data
The input data for the linear systems is read from the file "input.txt". Each set of equations is separated by a delimiter line "-----".

## Contributing

If you'd like to contribute to this project, you can:

- Fork the repository
- Create a new branch (`git checkout -b feature`)
- Make your changes
- Commit your changes (`git commit -am 'Add new feature'`)
- Push to the branch (`git push origin feature`)
- Create a pull request
