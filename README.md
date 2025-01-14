# FCFS Scheduling Algorithm Visualizer

This project implements the **First-Come, First-Served (FCFS)** CPU scheduling algorithm using HTML, CSS, and JavaScript. It provides an interactive, web-based interface for users to input process details and visualize the Gantt chart and scheduling details.

## Features
1. **Input Page**: 
   - Users can input the number of processes.
   - Dynamically generates a table for entering **arrival time** and **burst time** for each process.
   - A button to generate the Gantt chart.

2. **Visualization Page**:
   - Displays the Gantt chart for the FCFS scheduling algorithm.
   - Includes detailed statistics:
     - Arrival time
     - Burst time
     - Completion time
     - Turnaround time
     - Waiting time
   - Shows the **ready queue** and **process queue** at each step of execution.

## Technologies Used
- **HTML**: For creating the structure of the web pages.
- **CSS**: For styling the interface and making it visually appealing.
- **JavaScript**: For implementing the logic of FCFS scheduling and dynamically updating the pages.

## How It Works
1. **Page 1** (Input Page):
   - User enters the number of processes in an input field.
   - On clicking the "Create" button, a table is generated dynamically to input arrival time and burst time for each process.
   - After entering the details, the "Gantt Chart" button navigates to the visualization page.

2. **Page 2** (Visualization Page):
   - Displays the Gantt chart and a table with detailed scheduling statistics.
   - Visualizes the ready queue and process queue during execution for better understanding.
