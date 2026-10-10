# Emergency Rescue Request Management System

## About the Project

The Emergency Rescue Request Management System is a C-based application designed to manage emergency requests received from different locations. It helps organize rescue operations by assigning priorities to emergencies and displaying critical cases before normal cases.

The system allows users to register emergency requests, assign rescue teams, update request statuses, search for specific requests, and generate emergency summaries.

## Problem Statement

During emergencies, multiple rescue requests may arrive from different locations simultaneously. Handling these requests manually can delay critical rescue operations. This project provides a simple system to organize requests according to their emergency levels and help rescue teams manage operations efficiently.

## Features

- **Emergency Registration:** Register requests with request ID, location, number of people affected, emergency level, and required resources.
- **Priority-Based Sorting:** Display critical emergencies before high, medium, and low-priority cases.
- **Rescue Team Assignment:** Assign a rescue team to a registered request.
- **Status Management:** Update requests as Pending, In Progress, Completed, or Cancelled.
- **Request Search:** Search for a specific emergency using its request ID.
- **Emergency Summary:** View total requests, people affected, emergency-level counts, and request statuses.

## Technology Stack

- **Programming Language:** C
- **Compiler:** GCC
- **Concepts Used:** Structures, arrays, functions, strings, conditional statements, loops, and sorting algorithms.

## Priority System

| Emergency Level | Priority Score | Order |
|---|---:|---:|
| Critical | 4 | 1st |
| High | 3 | 2nd |
| Medium | 2 | 3rd |
| Low | 1 | 4th |

When multiple requests have the same priority, the request affecting more people is displayed first.

## How to Run the Project

### Prerequisites

- A C compiler such as GCC
- A code editor or terminal

### Steps

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project folder.

3. Compile the program using GCC:

   ```bash
   gcc emergency_rescue_system.c -o emergency_rescue_system
   ```

4. Run the program.

   **Windows:**
   ```bash
   emergency_rescue_system.exe
   ```

   **Linux/macOS:**
   ```bash
   ./emergency_rescue_system
   ```

## Sample Usage

After running the program, the following menu is displayed:

```text
===== EMERGENCY RESCUE MANAGEMENT SYSTEM =====
1. Register Emergency Request
2. Display Requests by Priority
3. Assign Rescue Team
4. Update Request Status
5. Search Request
6. Emergency Summary
0. Exit

Enter your choice:
```

Select an option from the menu to perform the required operation.

## Example Emergency Request

```text
Request ID : ER102
Location   : Sathyamangalam
People     : 15
Emergency  : Critical
Resources  : Ambulance
Rescue Team: Not Assigned
Status     : Pending
```

## Future Enhancements

- Store and retrieve emergency records using files.
- Manage rescue team availability and resource allocation.
- Add response-time tracking and performance statistics.
- Implement dynamic memory allocation.
- Develop a graphical user interface for easier operation.

## Learning Outcomes

This project demonstrates the practical application of C programming concepts to a real-world emergency management scenario. It provides experience in data management, sorting, searching, functions, structures, and menu-driven program development.

## Disclaimer

This project is developed for educational purposes and is not intended for use as a real-world emergency dispatch system.

## Author

Developed as a C programming project.
