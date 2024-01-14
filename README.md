# Dining Philosophers Simulation

This repository contains a Python simulation of the classic [Dining Philosophers Problem](https://en.wikipedia.org/wiki/Dining_philosophers_problem), a well-known problem in computer science related to resource allocation and synchronization in multiprocessing environments.

## Overview

The script `main.py` simulates multiple philosophers sitting around a table, each trying to eat spaghetti. The catch is that each philosopher needs two forks to eat, but there are only as many forks as philosophers, requiring synchronization to avoid deadlock and ensure fair access to the forks.

## Features

- Utilizes **multithreading** in Python to simulate concurrent actions of philosophers.
- Implements **synchronization** mechanisms to handle resource allocation of forks.
- Visualizes the state of each philosopher (thinking, eating, waiting) and the forks.

## Getting Started

### Prerequisites

- Python 3
- Libraries: `matplotlib`

### Installation

1. Clone the repository to your local machine.
2. Install the required Python packages:

pip install matplotlib


### Running the Simulation

Simply run the script with Python:

python main.py


## Understanding the Simulation

- Each philosopher is represented by a thread in the program.
- Forks are shared resources, and proper synchronization techniques are used to manage them.
- The state of each philosopher (thinking, eating) and the status of each fork (used, available) are visualized.

## Contributing

Contributions to enhance the simulation, such as improving synchronization mechanisms or visualization, are welcome. Please follow standard procedures for contributing to a GitHub project.


