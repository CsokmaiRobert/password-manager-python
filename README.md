🔐 Password Manager

This is a Password Manager application built using Tkinter that securely generates, stores, and retrieves passwords for different websites. It helps users manage their credentials effectively while offering password generation and auto-copying features.

Features:
Password Generation: Automatically generates strong, random passwords with a mix of letters, numbers, and symbols.
Clipboard Copy: The generated password is copied to your clipboard automatically for easy pasting.
Secure Storage: Saves passwords locally in a data.json file, keeping your credentials organized by website.
Search Function: Allows users to search for previously saved login details by website name.
Error Handling: Includes prompts if fields are left empty or if data files are missing.

How it works:
Generate Password: Click the Generate Password button to create a strong, random password.
Add Entry: Enter the website, email, and generated password, then click Add to save the details.
Search: Use the Search button to find previously saved login details for a specific website.
Clipboard Integration: Both generated and retrieved passwords are automatically copied to the clipboard for convenience.

Tech stack:
Tkinter for the graphical user interface.
JSON for data storage and retrieval.
Pyperclip to copy passwords directly to the clipboard.

How to run:
Clone the repository.
Ensure you have the required pyperclip module installed (pip install pyperclip).
Make sure a logo.png file is in the project folder for the app's UI.
Run the main.py file using Python, and the Password Manager will launch.
Start generating and managing your passwords securely!

This app simplifies password management and ensures you always have strong, unique passwords for your accounts! 💻🔑
