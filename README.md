A comprehensive desktop application for managing student grades with SQL database backend and intuitive GUI interface.

Features
1. Student Management: Add, edit, and delete student records

2. Grade Tracking: Record and manage subject grades for each student

3. Statistics: View class averages and performance statistics

4. Data Persistence: Use Json

5 Export Capabilities: Export grade data to CSV format

6. Search Functionality: Quickly find students by name

Installation
Prerequisites
Python 3.8 or higher

pip package manager
	
Setup
Clone the repository:

bash
git clone https://github.com/yourusername/student-grade-manager.git
cd student-grade-manager
Install required packages:

bash
pip install -r requirements.txt
Run the application:

bash
python grade_manager.py

Usage Adding Students:

Click "Add New Student" button

Enter student name and optional subjects/grades

Format subjects as Subject:Grade (e.g., Math:90, Science:85)

Managing Grades:

Select a student from the list

Add new subjects/grades using the input fields

Edit student names by clicking the "Edit" button

Viewing Statistics:

Class averages and performance metrics are displayed automatically

Individual student averages appear in the student list

Exporting Data:

Click "Export Data" to save all records as CSV



Diagram
Code

![deepseek_mermaid_20250516_4d9d08](https://github.com/user-attachments/assets/176143ee-10bb-4fc6-9aa4-2e9a40db0ee3)





Screenshots

Main Interface

Details of students
![Screenshot 2025-05-16 102833](https://github.com/user-attachments/assets/a8e08265-e39e-40f5-9125-04e29177696e)

Add Student
Dialog for adding new students

![Screenshot 2025-05-16 102913](https://github.com/user-attachments/assets/c31c26a1-1d23-47ba-8962-13062a8b427d)

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository

Create your feature branch (git checkout -b feature/your-feature)

Commit your changes (git commit -am 'Add some feature')

Push to the branch (git push origin feature/your-feature)

Open a Pull Request
