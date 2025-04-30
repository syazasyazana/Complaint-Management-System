# Complaint-Management-System

Complaint Management System – Project Description

The Complaint Management System is developed to streamline and manage customer complaints effectively. It includes user registration, complaint categorization, investigation, resolution, and reporting, all handled through a structured menu-driven interface using a linked list data structure.

Modules Overview:

1. User Registration Module:
Handles the registration and authentication of users. Customers and staff must log in with unique usernames and passwords. Role selection (Customer or Administrator/Staff) determines the accessible features. Only authenticated users can manage or track complaints.

2. Complaint Categorization Module:
When submitting a complaint, users must assign it to a specific category: Hygiene, Service, Billing, or Other. This module ensures structured organization of complaints and supports category-based viewing, filtering, and statistical analysis.

3. Complaint Investigation Module:
Used by staff to review submitted complaints. It includes functionality for searching, browsing by category, and examining complaint details. This supports deeper evaluation, pattern recognition, and preparation for resolution.

4. Complaint Resolution Module:
Allows staff to update complaint records, including editing complaint descriptions and marking complaints as resolved or unresolved. It also enables users to track complaint status and history over time, ensuring transparency in issue handling.

5. Reporting Module:
Accessible only by administrators, this module generates summary reports detailing complaint distribution across categories, percentage share, and highlights the category with the highest volume. It also includes mechanisms to manage complaint overflow (auto-delete when exceeding 100 complaints).

Technical Implementation:
- Developed in C++, using object-oriented programming with classes and functions for modularity.
- Uses a linked list to dynamically manage complaint records.
- Features include dynamic memory allocation, file output for printing complaints, and input validation.
