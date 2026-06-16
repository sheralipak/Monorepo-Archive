# 💻 Doors OS - Operating System Process Simulator

A structural C++ console application that simulates core kernel-level Operating System (OS) behaviors, specifically focusing on Process Management, Memory Allocation, and I/O Device Mapping. The simulator mirrors how a real kernel schedules, updates, and tracks process states inside a processor environment.

## 📐 Kernel Architecture & Process Attributes
The simulation leverages a robust `struct` framework to model individual Process Control Blocks (PCBs), tracking vital kernel parameters dynamically:
* **Identity & Hierarchy:** Manages explicit process tracking via unique Process IDs (PID), Parent PIDs, and Child PIDs to maintain structured process tree hierarchies.
* **State Transition Control:** Tracks process lifecycles across standardized kernel states (e.g., `Created`, `Ready`, `Running`, `Blocked`, `Suspended`).
* **Memory Management:** Monitors process workspace requests in Kilobytes (KB) and displays real-time simulated physical memory address pointers (`int* memoryadd`).
* **Hardware Registry Abstraction:** Maps execution paths to simulated CPU Registers and tracks the host hardware footprint (e.g., `Intel800` architecture specifications).

## 🛡️ Cybersecurity & SOC Relevance
* **Malware Analysis:** Understanding how PIDs, Parent PIDs, and Child hierarchies interact mimics real-world forensic processes (like identifying malicious process hollowing or orphaned child processes spawned by malware).
* **Privilege & Scheduling Auditing:** Simulates priority-based scheduling management, demonstrating how system resources are guarded against unauthorized execution deprivation or Denial of Service (DoS) logic loops.

## 🛠️ Technical Stack
* **Language:** C++
* **Data Structures:** Custom Struct Arrays (Process Control Blocks), Pointer Address Metrics
* **Concepts:** Process Lifecycle Management, Kernel Memory Referencing, Hardware Abstraction, Input/Output Polling Loops
