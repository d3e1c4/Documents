
##### Computer System Structure
- Hardware
- OS
- Application programs
- Users

##### Abstract View of Computer System

![[Pasted image 20260507065615.png]]
##### Software

1. System Software
	- OS
	- Utility Software
	- Language Translators
2. Application Software 
	- General Purpose (MS word, web browsers)
	- Special Purpose

##### What is an OS ?

##### Purposes of using an OS

##### Main Types of OS
- Open Source OS
- Closed Source OS

##### What is the UI of the OS ?
- CLI
- GUI

##### Components of Operating Systems

1. Process Management 
2. Main memory Management
3. Secondary storage Management
4. File Management
5. I/O System Management
6. Protection System
7. Networking (Distributed Systems)
8. Command - interpreter System

##### Services provided by OS

- Provide a UI
- Program Execution
- I/O operations
- File System Manipulation
- Process Communication
- Error Detection

Resource Allocation
Accounting
Protection and Security

##### [[Kernel]]

The Kernel is the core part of an Operating System. It manages the computer's hardware and provides the necessary services for various programs to interact with that hardware.

**OS = Kernel + Other components**

##### User mode / Kernel Mode

##### System call

##### System Programs (System Utilities)

- File manipulation (File Explorer)
- Status Information (Task Manager)
- File modification (Notepad, nano)
- Programming Language support (compilers, interpreters)
- Communication
- Program loading and execution (absolute loader, relocatable loader)

##### Operations of OS

mode bit (1) => user mode
mode bit (0) => monitor mode / kernel mode

Privileged Instructions
Non Privileged Instructions


##### OS Development using SPOOL

##### Multi-programming OS
##### Multi-tasking (Time Sharing) OS
##### Real-time OS
- Hard Real-time System
- Soft Real-time System

##### Storage Structure

registers
cache
main memory
solid-state disk
magnetic disk

##### Computer Star-up

Start and Power Supply
BIOS / Bootstrap loader (ROM, EPROM)
POST (Power-on self Test)
Bootstrap loader
Hard-disk
Start OS

##### Computer System Architecture

- Single-process System
- Multi-process System

##### Multi-process System

- Asymmetric Multiprocessing (AMP)
- Symmetric Multiprocessing (SMP)

##### Program

##### Process (jobs/tasks)
- User Process
- System Process

a process needs certain resources
- CPU time
- Memory
- File
- I/O devices

Program Counter (PC)

two types of insructions
1. Computational instructions
2. I/O instructions

##### Process Concept

- Text Section
- Stack Section
- Data Section
- Heap Section

##### Process State

- new
- ready (ready queue)
- running
- waiting (waiting queue)
- terminated

##### Process Control Block (PCB)

Every process has a Process Control Block (PCB) to store the essential details about the process.

##### Ready Queue
##### Wait / Device Queue

##### Context Switch

##### Process Scheduling

There are tree main scheduling
- Long-term scheduling (Job scheduler)
- Short-term scheduling
- Medium-term scheduling

##### Degree of Multi-programming


Processes can be described as either:
- CPU-bound process
- I/O bound process

##### Process Scheduling with Queues (Scheduling Queues)

- Job Pool (Hard disk)
- Ready Queue (RAM)
- Wait Queue (Device Queue)

##### Operations on Processes

There are three main operations
- Process Creation
- Process Termination
- Inter Process Communication

##### Process Creation

![[Pasted image 20260507120515.png|508]]

![[Pasted image 20260507120413.png|602]]
##### Inter Process Communication

- Processes within a system may be independent or cooperating 
- Cooperating process can affect or be affected by other processes, including sharing data. 
- Cooperating processes need Inter Process communication (IPC) There are three main models of IPC 
	1. Shared memory 
	2. Message passing 
	3. Pipe


![[Pasted image 20260507120256.png|606]]
##### Sockets


##### Thread

![[Pasted image 20260507121818.png|587]]

there are two types of threads
- User Thread
- Kernel Thread

##### Multi-threading Models

- many to one
- one to one
- many to many

##### Thread Libraries

##### Thread Pools

##### Signal Handling

##### default handler and User-defined signal handler

##### Signal Handling by Threads

##### Thread Cancellation
- Asynchronous Cancellation
- Deferred Cancellation


##### CPU Scheduling

##### CPU Brust
##### I/O Brust

##### Non Preemptive Scheduling
##### Preemptive Scheduling

##### Short term scheduler (CPU Scheduler)

CPU scheduling decisions may take place when a process: 
- Switches from running to waiting state 
- Switches from running to ready state 
- Switches from waiting to ready 
- Terminates

##### Dispatcher
- Context Switching
- Switching to user mode
- Jumping to the Proper location

##### Dispatch latency

##### Scheduling Criteria
- CPU utilization
- Throughput
- Turnaround time
- Waiting time
- Response time

##### Turnaround time = Waiting time + Executing time
##### Waiting time
##### Response time

##### CPU Scheduling Algorithm

- First-come, First-Served (FCFS)
- Shortest-Job-First (SJF)
- Shortest-Job-First (SJF)
- 






