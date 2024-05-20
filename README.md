# Password Manager
![Screenshot 2024-05-20 at 4 26 31 PM](https://github.com/taeleeswe/Password_manager/assets/123449246/ba40f2f5-8e1e-4c5f-a0e0-5d500508cb0e)


This is a simple password manager application built using Python and Tkinter. It allows you to generate strong passwords, save them along with the associated email/username and website, and search for stored credentials.

## Features

- **Password Generation**: Generate strong and random passwords with a mix of letters, numbers, and symbols.
- **Save Credentials**: Save website credentials (website, email, and password) to a local JSON file.
- **Search Credentials**: Search for saved credentials by website name.
- **Clipboard Copy**: Automatically copy generated passwords to the clipboard.


## Usage

1. **Run the Application**:
    python password_manager.py


2. **Generate a Password**:
    - Click on the "Generate Password" button to create a new random password. The password will be copied to your clipboard and displayed in the password entry field.

3. **Save Credentials**:
    - Enter the website name, email/username, and password.
    - Click the "Add" button to save the credentials to `data.json`.

4. **Search for Credentials**:
    - Enter the website name in the "Website" field.
    - Click the "Search" button to search for the credentials. If found, the email and password will be displayed in a message box.

## Files

- `password_manager.py`: Main application script.
- `data.json`: File where the credentials are saved.
- `logo.png`: Logo image used in the application.

## Installation

1. **Clone the Repository**:
    git clone https://github.com/your-username/password-manager.git
    cd password-manager

2. **Install Required Libraries**:
    - Ensure you have Python installed on your machine.
    - Install the required Python libraries:
      pip install pyperclip


