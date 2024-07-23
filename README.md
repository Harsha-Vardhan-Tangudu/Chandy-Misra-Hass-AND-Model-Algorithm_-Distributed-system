# Chandy-Misra-Hass-AND-Model-Algorithm_-Distributed-system
# Distributed Systems: Chandy Misra Hass AND Model Algorithm



## Overview
This project demonstrates the implementation of the Chandy Misra Hass AND Model Algorithm for deadlock detection in distributed systems. It includes code for detecting deadlocks, visualizing the wait-for graph, and analyzing process dependencies.

## Repository Structure
```
.
├── code/
│   ├── deadlock_detection.py
│   ├── process_visualization.py
├── analysis/
│   ├── analysis_code.py
│   ├── report.md
├── README.md
```

## Installation and Usage

### Prerequisites
- Python 3.x
- `networkx` library
- `matplotlib` library

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/distributed-systems-chandy-misra-hass.git
   ```
2. Navigate to the project directory:
   ```bash
   cd distributed-systems-chandy-misra-hass
   ```
3. Install the required Python libraries:
   ```bash
   pip install networkx matplotlib
   ```

### Running the Deadlock Detection Code
1. Navigate to the code directory:
   ```bash
   cd code
   ```
2. Run the `deadlock_detection.py` script:
   ```bash
   python deadlock_detection.py
   ```
3. Follow the prompts to input the number of processes, wait graph dependencies, and the deadlock detection trigger process.

### Running the Analysis Code
1. Navigate to the analysis directory:
   ```bash
   cd analysis
   ```
2. Run the `analysis_code.py` script:
   ```bash
   python analysis_code.py
   ```
3. Follow the prompts to input the number of processes and wait graph dependencies. The script will generate various visualizations of the process dependencies.

## Code Details

### Deadlock Detection (`deadlock_detection.py`)
This script implements the Chandy Misra Hass AND Model Algorithm to detect deadlocks in a set of processes with dependencies. It also visualizes the wait-for graph using NetworkX and Matplotlib.

### Process Visualization (`process_visualization.py`)
This script analyzes and visualizes the dependencies of processes using different types of plots (bar, line, dot, histogram).

## Analysis Report
The analysis report is located in the `analysis/report.md` file. It provides an in-depth look at the deadlock detection process, including input, output, and visualizations of the wait-for graph and process dependencies.

## Conclusion
The Chandy Misra Hass AND Model Algorithm successfully detects deadlocks in distributed systems. The provided visualizations help in understanding the process dependencies and identifying potential deadlocks, highlighting the importance of robust deadlock detection mechanisms.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- Our project supervisor and course instructors.
- The open-source community for their contributions to the libraries used in this project.

