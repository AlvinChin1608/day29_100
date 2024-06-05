# day29_100
I am currently engaged in a 100-day Python Bootcamp, which I am documenting and sharing my progress on GitHub. The boot camp is designed to progressively intensify, allowing me to deepen my understanding and proficiency in Python programming.

Additionally, I have chosen to include the beginner, intermediate and advanced in my documentation to provide a valuable reference for my future growth and development.

----------------
# Password Manager Project
This project is a simple password manager application built using Python and the Tkinter library. It allows users to generate strong passwords, save them securely, and retrieve them when needed. Below is a detailed explanation of the features and functionalities implemented in this project.

## Features
__1. Password Generation__

__2. Password Saving__

__3. User Interface (UI) Setup__

## Password Generation

The password generator creates a random password containing a mix of lowercase letters, uppercase letters, numbers, and symbols. This ensures a strong and secure password.

## Key Points:

   __- Character Sets:__ The password is generated using four different sets of characters: lowercase letters, uppercase letters, numbers, and symbols.

   __- Guaranteeing Character Diversity:__ The logic ensures that the password contains at least one character from each set.

   __- Random Selection:__ The remaining characters are randomly selected from the combined character pool to reach the desired password length.

   __- Clipboard Copying:__ The generated password is automatically copied to the clipboard using the __pyperclip__ library, making it convenient to paste the password wherever needed.

## Password Saving
The application allows users to save their generated passwords along with the associated website and email/username. The data is saved to a text file.

## Key Points:

   __- Data Validation:__ The code checks for empty fields and validates the email format before saving the data.

   __- Confirmation:__ The user is prompted to confirm the details before saving.

   __- Data Storage:__ The data is stored in a text file __(data.txt)__ in the format: __website | email | password__.

**User Interface (UI) Setup**
The UI is created using Tkinter, which provides a simple way to build graphical user interfaces in Python.

## Key Points:

   __- Labels:__ Labels are used to display text in the UI.

   __- Entries:__ Entry widgets are used to take user inputs for website, email, and password.

   __- Buttons:__ Buttons are used to trigger password generation and saving functionalities.

   __- Canvas:__ A canvas is used to display an image (e.g., logo).











   
