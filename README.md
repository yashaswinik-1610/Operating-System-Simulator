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


## Tentative Planned Features

| Module                    | Description                                                                                  |
|---------------------------|----------------------------------------------------------------------------------------------|
| Introduction to OS        | Resource Abstraction, Time/Space Multiplexing, Types of OS (Batch, Time Sharing, PC, Embedded, Network)          |
| Processes & Threads       | Process states, PCB/TCB, Context switch, Thread management                                   |      
| CPU Scheduling            |FCFS, SJF, Priority, Round Robin, Preemptive vs Non-preemptive, Metrics                       |  
| Synchronization           | Critical Section, Semaphores, Monitors, Producer-Consumer, Dining Philosophers, Reader-Writer|   
| Deadlock                  | Conditions, Prevention, Avoidance (Banker's), Detection, Recovery                            |
| Memory Management         | Contiguous allocation (First/Best/Worst fit), Fragmentation, Swapping                        |   
| Virtual Memory            | Paging, Segmentation, Page replacement (FIFO, LRU, LFU), Thrashing, Working Set              |      
| File Management           | File operations, Directory structures, Allocation methods                                    |     
| Device Management           | FCFS, SSTF, SCAN, C-SCAN                 |    |
