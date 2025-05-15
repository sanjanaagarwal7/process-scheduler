# 🧮 CPU Scheduling Simulator in C++

This is a simple C++ program that simulates popular **CPU scheduling algorithms** like FCFS, SJF, SRTF, Round Robin, and Priority Scheduling. It provides detailed process tables and a summary for easy comparison.

---

## 🚀 Features

- ✅ Supports 5 scheduling algorithms:
  - FCFS (First Come First Serve)
  - SJF (Shortest Job First)
  - SRTF (Shortest Remaining Time First)
  - Round Robin (with user-defined quantum)
  - Priority Scheduling (Preemptive)

- ✅ Detailed output:
  - Completion Time
  - Turnaround Time
  - Waiting Time

- ✅ Comparative Summary:
  - Shows average waiting and turnaround times for each algorithm.

- ✅ Reuses input data across algorithms.

---

## 📥 Input Format

You will be asked to input:

1. **Number of processes**
2. **Priority for each process** (e.g., `3 2 1`)
3. **Arrival time for each process** (e.g., `0 1 2`)
4. **Burst time for each process** (e.g., `5 3 8`)

---

## 🧑‍💻 How to Use

> ⚠️ This is a **single `.cpp` file**. No external libraries or setup required.

### Step 1: Save the file

Save the code as, for example:

```bash
scheduler.cpp

