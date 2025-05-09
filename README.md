# eXpOS – eXperimental Operating System

This repository contains the implementation of **eXpOS**, a simplified educational operating system developed as part of the [eXpOS project](https://exposnitc.github.io/). The goal of this project is to gain a deep understanding of OS internals by implementing a basic operating system from scratch in a layered and modular manner.

## 📁 Project Structure

The project is structured in stages as per the eXpOS roadmap. Each stage introduces key OS concepts and adds functionality to the system. The major modules include:

- **Boot Module** – Initializes system data structures and loads the INIT process.
- **Process Manager** – Handles process creation, execution, scheduling, and termination.
- **Memory Manager** – Manages paging, frame allocation, and disk-to-memory transfers.
- **Exception Handler** – Handles page faults and illegal operations.
- **System Call Interface** – Provides support for system calls like `fork`, `exec`, `wait`, `exit`, `getpid`, `signal`, etc.
- **Scheduler** – Implements process scheduling (Round Robin or MLFQ).
- **Disk Scheduler** – Manages disk read/write scheduling using SCAN algorithm.
- **File System Interface** – Handles file and directory operations, including access and permission control.
- **Synchronization Support** – Implements `Wait` and `Signal` primitives for process synchronization using memoryless signals or semaphores.

## 🧰 Tools Used

- **XSM Simulator** – To simulate hardware and OS behavior.
- **ExpL Compiler** – For writing and compiling user-level programs.
