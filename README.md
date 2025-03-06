# 13.SQLite-student-management-system
Student Management System
This project is a Student Management System built using PyQt6 and SQLite. It provides a graphical user interface (GUI) for managing student records, including adding, editing, deleting, and searching for students. The application is designed to be user-friendly and efficient for managing student data in an educational setting.

Features
Add Students: Add new student records with details such as name, course, and mobile number.

Edit Students: Update existing student records.

Delete Students: Remove student records from the database.

Search Students: Search for students by name.

View All Students: Display all student records in a table format.

User-Friendly Interface: Built with PyQt6 for a clean and intuitive GUI.

Database Integration: Uses SQLite for storing and managing student data.

Classes and Methods
DatabaseConnection
__init__(self, database_file="database.db"): Initializes the database connection.

connect(self): Establishes a connection to the SQLite database.

MainWindow
__init__(self): Sets up the main window, including menus, toolbar, and table for displaying student data.

load_data(self): Loads student data from the database into the table.

insert(self): Opens a dialog to add a new student.

search(self): Opens a dialog to search for a student by name.

edit(self): Opens a dialog to edit an existing student record.

delete(self): Opens a dialog to delete a student record.

about(self): Displays an "About" dialog with information about the application.

InsertDialog
__init__(self): Provides a form to add a new student.

add_student(self): Inserts the new student data into the database.

EditDialog
__init__(self): Provides a form to edit an existing student record.

update_student(self): Updates the student data in the database.

DeleteDialog
__init__(self): Confirms the deletion of a student record.

delete_student(self): Deletes the student record from the database.

SearchDialog
__init__(self): Provides a form to search for a student by name.

search(self): Highlights the searched student in the table.

AboutDialog
__init__(self): Displays information about the application.
