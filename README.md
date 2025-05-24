# Process-scheduling-algorithm
A comprehensive GUI-based process scheduling simulator that visualizes various CPU scheduling algorithms with performance metrics and Gantt charts.

# Features

1.Six Scheduling Algorithms:
First-Come, First-Served (FCFS)

Shortest Job First - Non-Preemptive (SJF-NP)

Shortest Job First - Preemptive (SJF-P)

Round Robin (RR) with configurable time quantum

Priority Scheduling - Non-Preemptive (Priority-NP)

Priority Scheduling - Preemptive (Priority-P)

2.Interactive GUI:

Add, edit, and remove processes

Visualize scheduling with Gantt charts

View detailed performance metrics

Calculate average waiting time and turnaround time

3.Process Metrics:

Completion Time

Waiting Time

Turnaround Time

Response Time

# Requirements

Python 3.6+

tkinter (usually included with Python)

matplotlib (pip install matplotlib)

# Usage
1.Add Processes:
Enter Process ID, Arrival Time, Burst Time, and Priority (optional)

Click "Add Process"

2.Modify Processes:
Select a process from the table

Click "Edit Process" to modify or "Remove Process" to delete

3.Run Scheduling Algorithms:
Click any of the algorithm buttons (FCFS, SJF, RR, etc.)

For Round Robin, enter the time quantum when prompted

4.View Results:
The table updates with calculated metrics
Gantt chart displays the scheduling timeline
Average waiting and turnaround times are shown below

# Screenshots
![Screenshot 2025-05-24 104413](https://github.com/user-attachments/assets/e7d86691-8e1c-479e-b90b-5beb296e618e)
![Screenshot 2025-05-24 104434](https://github.com/user-attachments/assets/e8a6dd5b-b2c7-42d3-a4ad-7764814e2359)
![Screenshot 2025-05-24 104546](https://github.com/user-attachments/assets/2977ca78-4358-4845-80dc-1f5917bf139f)

# Algorithm Details
1.First-Come, First-Served (FCFS)
Processes are executed in order of arrival
Simple but can lead to long waiting times for short processes

2.Shortest Job First (SJF)
Non-preemptive: Once started, runs to completion
Preemptive: Can be interrupted if a shorter job arrives

3.Round Robin (RR)
Each process gets a fixed time slice (quantum)
Fair allocation but higher context switching overhead

4.Priority Scheduling
Non-preemptive: Higher priority processes run first
Preemptive: Higher priority processes can interrupt running ones

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
Inspired by operating system concepts and CPU scheduling algorithms
Built with Python's tkinter for GUI and matplotlib for visualization
