# PRODIGY_SD_03
# Contact Management System

## Description
The Contact Management System is a simple graphical user interface (GUI) application built using Python and Tkinter. It allows users to add, view, edit, and delete contact information, including names, phone numbers, and email addresses. The contacts are saved in a JSON file (`contacts.json`).

## Features
- **Add Contact**: Users can add a new contact with a name, phone number, and email address.
- **View Contacts**: Users can view all contacts and their details.
- **Edit Contact**: Users can edit the phone number and email address of an existing contact.
- **Delete Contact**: Users can delete a selected contact.
- **Persistent Storage**: Contact information is stored in a JSON file, allowing data to persist between sessions.

## Requirements
- Python 3.x
- Tkinter library (usually included with Python installations)

## How to Run
1. Make sure you have Python installed on your system.
2. Save the provided code in a file named `contact_manager.py`.
3. Run the script using the command:
   ```
   python contact_manager.py
   ```

## File Structure
- `contacts.json`: This file stores the contacts in JSON format. It is created automatically when the application is run for the first time.

## Usage
- **Add Contact**: Click the "Add Contact" button and enter the required information in the dialog boxes.
- **View Contacts**: Click the "View Contacts" button to open a new window displaying all contacts.
- **Edit Contact**: Select a contact from the list and click the "Edit Contact" button to update the phone number or email address.
- **Delete Contact**: Select a contact from the list and click the "Delete Contact" button to remove the contact from the list.
- **Exit**: Click the "Exit" button to close the application.

## Note
- The application does not perform detailed validation of the inputs, such as checking for valid email addresses or phone numbers. Users should ensure the correctness of the data entered.

## License
This project is open-source and can be modified or redistributed under the terms of the MIT License.

## Author

 - [Gautham Krishna R](https://github.com/Gauthammq)
