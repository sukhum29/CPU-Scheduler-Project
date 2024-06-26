# CPU Scheduler Project

Welcome to the CPU Scheduler Project repository! This project demonstrates various CPU scheduling algorithms using Java, with a graphical user interface (GUI) to visualize and compare their performance.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Algorithms Implemented](#algorithms-implemented)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The CPU Scheduler Project is designed to simulate and visualize different CPU scheduling algorithms, which are crucial for process management in an operating system. This project helps in understanding how these algorithms work and their efficiency in different scenarios.

## Features

- Implementation of various CPU scheduling algorithms.
- Graphical User Interface (GUI) for ease of use.
- Visualization of scheduling process.
- Comparison of algorithm performance.

## Algorithms Implemented

- First-Come, First-Serve (FCFS)
- Shortest Job First (SJF)
- Shortest Remaining Time (SRT)
- Round Robin (RR)
- Priority Scheduling (Non-Preemptive)
- Priority Scheduling (Preemptive)

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/sukhum29/CPU-Scheduler-Project.git
   ```
2. Navigate to the project directory and compile the code:
   ```bash
   cd CPU-Scheduler-Project
   javac *.java
   ```
3. Run the application:
   ```bash
   java GUI
   ```

## File Structure

- `CpuScheduler.java`: Main class to handle scheduling.
- `Event.java`: Event class used in scheduling.
- `FirstComeFirstServe.java`: FCFS scheduling algorithm.
- `PriorityNonPreemptive.java`: Priority scheduling (Non-Preemptive) algorithm.
- `PriorityPreemptive.java`: Priority scheduling (Preemptive) algorithm.
- `RoundRobin.java`: Round Robin scheduling algorithm.
- `Row.java`: Data structure for processes.
- `ShortestJobFirst.java`: Shortest Job First (SJF) scheduling algorithm.
- `ShortestRemainingTime.java`: Shortest Remaining Time (SRT) scheduling algorithm.
- `Utility.java`: Utility functions used in the project.
- `GUI.java`: Graphical User Interface class.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements. Ensure your code follows the project's coding standards and include relevant tests.


---

Feel free to explore and contribute to this project. If you encounter any issues or have suggestions, please open an issue on GitHub.

For more details, visit the [CPU Scheduler Project repository](https://github.com/sukhum29/CPU-Scheduler-Project).
