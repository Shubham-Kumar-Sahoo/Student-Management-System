# School Management System

A comprehensive School Management System built with Python and Tkinter for managing student records. This application is designed to make the management of student information seamless and efficient. Users can add, view, delete, and reset student records stored in an SQLite database through an intuitive graphical user interface (GUI).

### Features

- **Add New Student Records**: Capture essential details such as Name, Email, Contact Number, Gender, Date of Birth, and Stream.
- **View Existing Student Records**: Display all stored records in a clear and organized tabular format.
- **Delete Student Records**: Remove selected records from the database.
- **Reset Input Fields**: Quickly clear all input fields to their default state.
- **Display All Records**: View all student records in an easy-to-navigate tree view.
- **Intuitive GUI**: User-friendly interface for seamless interaction.
- **Persistent Storage**: All data is stored in an SQLite database, ensuring that records are preserved between sessions.

### Dependencies

- Python 3.x
- Tkinter
- tkcalendar
- sqlite3

## Requirement

1. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

## To Run

1. Run the application:

    ```sh
    python main.py
    ```

2. **Interact with the GUI window:**

    - **Adding a Record:**
        1. Fill in the details for Name, Email, Contact Number, Gender, Date of Birth, and Stream.
        2. Click the "Submit and Add Record" button.
        3. A confirmation message will appear, and the record will be added to the database and displayed in the tree view.

    - **Viewing a Record:**
        1. Select a record from the tree view.
        2. Click the "View Record" button.
        3. The details of the selected record will be displayed in the input fields.

    - **Deleting a Record:**
        1. Select a record from the tree view.
        2. Click the "Delete Record" button.
        3. A confirmation message will appear, and the record will be deleted from the database and removed from the tree view.

    - **Resetting Fields:**
        1. Click the "Reset Fields" button to clear all input fields.

    - **Resetting the Form:**
        1. Click the "Delete database" button to clear the tree view and reset all input fields.
