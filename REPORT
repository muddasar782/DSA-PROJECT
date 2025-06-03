Project Report

EXPLANATION:

The Hospital Management System provided in the code implements a functional program to manage hospital operations. This program uses data structures like linked lists and queues to effectively manage data and processes. Here's a breakdown of its design and functionality:

1.	 Overview of Features

•	Patient Management:
o	Add, view, search, and delete patient records.
•	Doctor Management:
o	Add, view, and search doctors by specialization.
•	Appointment Management:
o	Schedule, view, and serve appointments using a queue.
•	Hospital Statistics:
o	Displays the total number of patients, doctors, and appointments.
•	File Handling:
o	Persistent storage of patients, doctors, and appointments using text files for saving and loading data.

2.	 Data Structures Used

2.1	Linked Lists

Used for storing and managing records for:

•	Patients:
 
o	Each patient is stored as a Patient struct, linked to the next patient in the list.
o	Operations like addition, searching, deletion, and traversal are straightforward.
o	Head pointer: patientHead points to the first patient in the list.
•	Doctors:
o	Each doctor is stored as a Doctor struct, linked to the next doctor in the list.
o	Similar to patients, operations like addition and searching are performed on this list.
o	Head pointer: doctorHead points to the first doctor in the list.

2.2	Queue

Used for managing appointments:

•	A queue ensures First-In-First-Out (FIFO) order, making it suitable for serving appointments in chronological order.
•	Appointment Queue:
o	Managed using an AppointmentQueue struct that has pointers to the front and rear of the queue.
o	Operations:
	Enqueue: Adds a new appointment to the rear.
	Dequeue: Removes and serves the appointment from the front.
	Display: Traverses all appointments for listing them.

3.	 Functional Flow

3.1	Patient Management

•	Add Patient: Creates a Patient node and adds it to the head of the linked list.
•	View Patients: Traverses the linked list to display all patient records.
•	Search by ID: Searches the linked list for a patient with a matching ID.
•	Delete Patient: Searches for the patient by ID and removes the node from the linked list.

3.2	Doctor Management

•	Add Doctor: Creates a Doctor node and adds it to the head of the linked list.
•	View Doctors: Traverses the linked list to display all doctor records.
•	Search by Specialization: Traverses the list to find doctors with a specific specialization.

3.3	Appointment Management

•	Schedule Appointment: Creates an Appointment node and enqueues it to the AppointmentQueue.
•	Serve Appointment: Removes and serves the front appointment from the queue.
•	Display Appointments: Traverses the queue to display all upcoming appointments.
 
3.4	Hospital Statistics

Counts the number of patient nodes, doctor nodes, and appointment nodes to generate statistics about the hospital's operations.

3.5	File Handling

•	Saving Data:
o	Writes all patient, doctor, and appointment records to separate text files for persistence.
•	Loading Data:
o	Reads from the files during startup to populate the respective data structures.

4.	 Key Design Aspects

Advantages of Using Data Structures

•	Linked Lists:
o	Dynamic memory allocation avoids fixed storage size.
o	Simplified addition and deletion of nodes.
•	Queues:
o	FIFO ensures logical processing of appointments.
Flexibility:

•	Each operation is modular and can handle multiple patients, doctors, or appointments efficiently.

Summary:

This system showcases a simplified DSA-based hospital management system using linked lists for dynamic data storage and queues for process management. It handles real-world scenarios like record-keeping, efficient appointment scheduling, and persistence, making it a practical demonstration of data structure applications in software design.

