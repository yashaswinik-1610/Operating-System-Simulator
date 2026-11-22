# Operating System-Simulator

An interactive visual learning tool that helps us understand Operating System concepts by seeing them in action.

## Tentative Project Structure

os_visual_simulator/
│
├── main.py                     # Starting point of the application (Router)
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
│
├── core/                       # Pure logic (no GUI)
│   ├── __init__.py
│   ├── process.py              # Process class + PCB (Process Control Block)
│   ├── scheduler.py            # All scheduling algorithms
│   ├── memory.py               # Memory management logic
│   └── deadlock.py             # Deadlock related logic
│
├── gui/                        # Everything visual (Streamlit)
│   ├── __init__.py
│   ├── dashboard.py            # Main home screen
│   └── views/                  # Individual modules
│       ├── __init__.py
│       ├── introduction.py     # Introduction to OS
│       └── scheduling.py       # CPU Scheduling screen
│
├── assets/                     # Static files
│   ├── icons/                  # UI icons
│   └── images/                 # Diagrams and illustrations
│
└── docs/                       # Notes / diagrams / documentation


## Why this project?

Operating System concepts are often hard to understand because they are abstract. This project makes the concepts visual and interactive. 

Instead of only reading theory, here we can:
- Watch processes change states.
- See CPU Scheduling Algorithms work in real time.
- Observe how memory is allocated and how page faults happen.
- Visualize deadlocks and synchronization problems.
- Explore disk scheduling and file systems


## Tentative Planned Features

| Module                    | Description                                                                                           |
|---------------------------|-------------------------------------------------------------------------------------------------------|
| Introduction to OS        | Resource Abstraction, Time/Space Multiplexing, Types of OS (Batch, Time Sharing, PC, Embedded,Network)|                                                                                                                  |
| OS Architecture           | OS Functions, Kernel Types (Monolithic, Layered, Microkernel), User vs Supervisor Mode                |      
| Processes & Threads       | Process States, PCB, TCB, Context Switching, Thread Management                                        |  
| CPU Scheduling            | FCFS, SJF, Priority, Round Robin, Multi-level Queue, Performance Metrics                              |   
| Process Synchronization   | Critical Section, Semaphores, Producer-Consumer, Dining Philosophers, Reader-Writer, Monitors, IPC    |
| Deadlock                  | Prevention, Avoidance (Banker's Algorithm), Detection (RAG), Recovery                                 |   
| Memory Management         | Address Binding, Contiguous Allocation, First/Best/Worst Fit, Fragmentation, Swapping                 |      
| Virtual Memory            | Paging, Segmentation, FIFO, LRU, LFU, Page Fault, Thrashing, Working Set                              |     
| File Management           | File Operations, Allocation Methods (Contiguous, Linked, Indexed), Directory Structures               |   
| Device Management         | Device Drivers, Disk Scheduling (FCFS, SCAN, C-SCAN, SSTF), I/O Techniques, Buffering                 |
| Protection & Security     | Authentication, Authorization, Access Control, Security Attacks, Basic Cryptography                   |
| Distributed Systems       | RPC, Distributed Memory, Remote Process Management, Design Strategies                                 |
