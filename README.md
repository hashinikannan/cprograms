# Smart Campus Complaint Management System

## About the Project

The Smart Campus Complaint Management System is a C-based application developed to manage complaints submitted by students and faculty regarding campus facilities and services. It helps register complaints, assign priorities based on severity, track complaint status, and generate useful summaries for the campus support team.

The system aims to make complaint handling more organized and efficient by helping administrators identify and address important issues first.

## Problem Statement

Colleges receive complaints related to laboratories, classrooms, hostels, transportation, internet connectivity, electricity, and other campus facilities. Managing these complaints manually can make it difficult to identify urgent issues, monitor progress, and ensure timely resolution.

This project provides a simple, menu-driven application to organize campus complaints, prioritize issues, and track their progress.

## Features

- **Complaint Registration:** Register complaints with complaint ID, category, problem description, location, and priority.
- **Priority Assignment:** Classify complaints based on severity as Critical, High, Medium, or Low.
- **Complaint Search:** Search for a specific complaint using its ID.
- **Priority-Based Sorting:** Display complaints in priority order.
- **Status Tracking:** Update complaint status to Pending, In Progress, or Resolved.
- **Pending Complaints:** Display complaints that are waiting for resolution.
- **Complaint Summary:** Generate a summary of registered complaints and their statuses.

## Technology Stack

- **Programming Language:** C
- **IDE:** Code::Blocks
- **Compiler:** GCC (MinGW)
- **Programming Concepts:** Structures, arrays, functions, strings, loops, conditional statements, searching, and sorting algorithms.

## Complaint Priority System

| Priority | Description |
|---|---|
| Critical | Urgent issues requiring immediate attention |
| High | Serious issues affecting important facilities |
| Medium | Issues requiring attention but not immediately critical |
| Low | Minor issues that can be handled routinely |

Higher-priority complaints are displayed before lower-priority complaints.

## How to Run the Project

### Prerequisites

- Code::Blocks IDE
- GCC compiler (MinGW)

### Steps to Run

1. Download and install Code::Blocks with the MinGW compiler.
2. Clone this repository or download the source code from GitHub.
3. Open Code::Blocks.
4. Select **File → Open** and open the project's C source file (`.c`).
5. Click **Build and Run** or press **F9**.
6. The program will execute in the console.
7. Select an option from the menu to manage campus complaints.

## Example Complaint Record

```text
Complaint ID : 105
Category     : Lab
Problem      : 8_computers_not_working
Priority     : High
Location     : CSBS Lab 3
Status       : Pending
```

## Example Application Menu

```text
===== SMART CAMPUS COMPLAINT SYSTEM =====
1. Register Complaint
2. Search Complaint
3. Sort Complaints
4. Update Complaint Status
5. Display Pending Complaints
6. Generate Complaint Summary
7. Exit

Enter your choice:
```

## Future Enhancements

- Store complaint records in files and reload them when the program starts.
- Filter complaints by category, location, and status.
- Generate department-wise complaint statistics.
- Implement multiple sorting options, such as priority and complaint ID.
- Calculate complaint resolution time and generate performance reports.
- Develop a graphical user interface for students, faculty, and administrators.

## Learning Outcomes

This project demonstrates the practical application of C programming concepts to a real-world campus management problem. It provides experience in data organization, searching, sorting, string handling, and menu-driven program development.

## Disclaimer

This project is developed for educational purposes and demonstrates the basic workflow of a campus complaint management system. It is not a complete production-level campus management solution.

## Author

Developed as a C programming project.
# Emergency Rescue Priority System

## Project Overview

The Emergency Rescue Priority System is a console-based application developed using the C programming language. It helps manage emergency rescue requests by recording request details, assigning priorities, and tracking rescue operations.

The system is designed to help emergency control rooms organize requests and identify cases that require urgent attention.

## Problem Statement

During emergencies, multiple rescue requests may arrive from different locations at the same time. Managing these requests manually can be difficult and may delay the response to critical situations.

This project provides a simple computerized system to register and manage rescue requests efficiently.

## Objectives

- Register emergency rescue requests.
- Record request details such as ID, location, emergency type, resources, and status.
- Assign priority levels to emergency requests.
- Display requests according to priority.
- Assign rescue teams to requests.
- Update the status of rescue operations.
- Search for a specific request.
- Generate an emergency summary.

## Technologies Used

- **Programming Language:** C
- **IDE:** Code::Blocks
- **Compiler:** GCC
- **Concepts:** Structures, arrays, functions, conditional statements, loops, and string handling.

## Features

### 1. Register Emergency Request
Allows the user to enter details about a new rescue request, including request ID, location, number of people affected, emergency level, required resources, assigned team, and status.

### 2. Priority Management
Allows emergency requests to be assigned priority levels so that urgent cases can be identified and handled first.

### 3. Display Requests
Displays registered emergency requests according to their priority.

### 4. Rescue Team Assignment
Allows a rescue team to be assigned to an emergency request.

### 5. Update Request Status
Allows the status of a request to be updated as the rescue operation progresses.

### 6. Search Request
Allows users to find a specific emergency request using its request ID.

### 7. Emergency Summary
Provides a summary of registered requests to help users understand the current emergency situation.

## How to Run the Project in Code::Blocks

1. Open Code::Blocks.
2. Create a new **Console Application** using the C language, or open the existing project.
3. Add or open the source file containing the C program.
4. Save the source file with the `.c` extension.
5. Click **Build and Run** or press `F9`.
6. Follow the menu displayed in the console and enter the required choices.

## Sample Output

```text
==== EMERGENCY RESCUE SYSTEM ====
1. Register Request
2. Display Requests by Priority
3. Assign Rescue Team
4. Update Request Status
5. Search Request
6. Emergency Summary
7. Exit

Enter your choice: 1

Enter ID: 100
Enter location: Sathyamangalam
Enter people affected: 15
Enter emergency level: Critical
Enter resources needed: Ambulance
Enter status: Pending

Request registered successfully!
```

*Note: The sample output illustrates the intended workflow. The exact prompts and fields depend on the implemented source code.*

## Applications

- Emergency control rooms
- Disaster management coordination
- Campus emergency response
- Rescue request tracking
- Resource and team coordination

## Future Enhancements

- Store and retrieve requests using file handling.
- Dynamically allocate memory for requests.
- Track multiple rescue teams and resource availability.
- Sort requests using different criteria.
- Record response times and generate performance statistics.

## Conclusion

The Emergency Rescue Priority System demonstrates how the C programming language can be used to build a basic emergency request management application. It applies fundamental programming concepts to organize rescue requests, manage their status, and support priority-based decision-making.

This project is an educational prototype and is not intended to replace professional emergency dispatch systems.

## Author

Developed as a C programming project.

