# Operating System-Simulator

An interactive visual learning tool that helps us understand Operating System concepts by seeing them in action.

## Tentative Project Structure

os_visual_simulator/
│
├── main.py                      # Starting point of the application
│
├── core/                       
│   ├── __init__.py              # Pure logic (no GUI)
│   ├── process.py               # Process class + PCB
│   ├── scheduler.py             # All scheduling algorithms
│   ├── memory.py                # Memory management logic
│   └── deadlock.py              # Deadlock related logic
│
├── gui/                        
│   ├── __init__.py              # Everything visual
│   ├── dashboard.py             # Main home screen
│   └── views/                  
│       ├── __init__.py          # Individual modules
│       ├── introduction.py      # Introduction to OS
│       └── scheduling.py        # CPU Scheduling screen
│
├── assets/
│   ├── icons/
│   └── images/
│
├── docs/                        # notes / diagrams
│
├── requirements.txt
└── README.md

## Why this project?

Operating System concepts are often hard to understand because they are abstract. This project makes the concepts visual and interactive. 

Instead of only reading theory, here we can:
- Watch processes change states.
- See CPU Scheduling Algorithms work in real time.
- Observe how memory is allocated and how page faults happen.
- Visualize deadlocks and synchronization problems.
- Explore disk scheduling and file systems


## Planned Features

| Module                    | Description                                                | 
|---------------------------|------------------------------------------------------------|
| Introduction to OS        | Types of OS, Resource Abstraction, Functions of OS, Kernel vs User mode, Modularity                            |
| Processes & Threads       | Process states, PCB, context switching                     |
| CPU Scheduling            | FCFS, SJF, Priority, Round Robin                           |
| Synchronization           | Semaphores, Producer-Consumer, etc.                        |
| Deadlock                  | Conditions, prevention, avoidance, detection, recovery     |
| Memory Management         | Contiguous allocation + Paging           |
| Virtual Memory            | Page replacement algorithms              |
| File System               | File allocation and directories          |
| Disk Scheduling           | FCFS, SSTF, SCAN, C-SCAN                 |
