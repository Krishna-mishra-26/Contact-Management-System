# Contact Management System

A Python-based GUI application for managing contacts using `Tkinter` and `SQLite`. This Contact Management System allows users to add, update, delete, and view contact information in a structured table format.

## Features

- Add new contacts with details like firstname, lastname, gender, age, address, and contact number.
- Update existing contact details.
- Delete unwanted contacts.
- View all contacts in a sortable table.
- Interactive graphical user interface (GUI) with Tkinter.

## Technologies Used

- **Programming Language:** Python
- **Database:** SQLite
- **GUI Library:** Tkinter

## Prerequisites

- Python 3.x

## Usage

1. Run the application:
   ```bash
   python index.py
   ```
2. Use the buttons to:
   - Add new contacts.
   - Update selected contacts.
   - Delete unwanted contacts.
   - View and interact with the contact list.

## Project Structure

- `contact_management_system.py`: Main application file containing all logic and GUI implementation.
- `Contact.db`: SQLite database file created automatically to store contact information.

## How It Works

1. **Database Initialization:**
   - The application initializes a SQLite database (`Contact.db`) with a `member` table if it doesn't exist.

2. **CRUD Operations:**
   - **Create:** Add new contact records to the database.
   - **Read:** Fetch and display all contact records in a treeview table.
   - **Update:** Modify existing records using the "Update" functionality.
   - **Delete:** Remove selected records.

3. **GUI Components:**
   - `Tkinter` is used to build an interactive GUI with buttons, labels, entries, and a treeview widget for displaying contacts.

## Screenshots

![image](https://github.com/user-attachments/assets/e932351a-09e7-4919-8998-659d6c1587ff)
![image](https://github.com/user-attachments/assets/1025c2a5-8248-4adc-bf2b-c97f1e6a8993)
![image](https://github.com/user-attachments/assets/839a4ecf-6316-4859-a269-c62b2d06c999)


## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Commit your changes.
4. Push the branch and create a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or support, feel free to reach out at [Krishnamis8634@gmail.com](mailto:your-Krishnamis8634@gmail.com).

---

