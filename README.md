# CPU Scheduling Algorithm Simulator

A C++ tool to simulate and analyze CPU scheduling algorithms, including FCFS (First-Come-First-Served), Round Robin, SJF (Shortest Job First), and SRT (Shortest Remaining Time). The simulator generates visual timelines and calculates key metrics such as turnaround time, waiting time, and normalized turnaround time to evaluate scheduling performance.

---

## Features

- **Algorithm Support**: Implements FCFS, Round Robin, SJF, and SRT algorithms.
- **Input Handling**: Accepts process details like arrival times, service times, and time quantum (for Round Robin).
- **Output Visualization**: Displays Gantt charts and timelines in the console.
- **Performance Metrics**: Computes and outputs metrics such as turnaround time and waiting time.

---

## Technologies Used

- **Programming Language**: C++

---

## How It Works

1. **Input**: Provide process details via console or an input file.
2. **Algorithm Selection**: Choose the scheduling algorithm to simulate.
3. **Execution**: The program simulates the scheduling based on the chosen algorithm.
4. **Output**: Displays visual timelines (Gantt chart) and performance metrics in the console.

---

## Installation and Setup

1. Clone the repository:  
   git clone https://github.com/your-username/cpu-scheduler-simulator.git
2. Navigate to the project directory:
  cd cpu-scheduler-simulator
3. Compile the program using a C++ compiler:
   g++ -o scheduler main.cpp
4. Run the program:
  ./scheduler
