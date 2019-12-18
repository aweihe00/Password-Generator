# Password-Generator

Unit 03 JavaScript Homework: Password Generator

Link to site deployed https://aweihe00.github.io/Password-Generator/

Description
Create an application that generates a random password based on user-selected criteria. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code.
The user will be prompted to choose from the following password criteria:

Length (must be between 8 and 128 characters)

Character type:

Special characters (see examples)

Numeric characters

Lowercase characters

Uppercase characters

The application should validate user input and ensure that at least one character type is selected.
Once all prompts are answered, the user will be presented with a password matching the answered prompts. Displaying the generated password in an alert is acceptable, but attempt to write the password to the page instead.
As a bonus, the user should also have the option to click a button to copy the password to their clipboard.
Your application should have a clean and polished user interface and be responsive, ensuring that it adapts to multiple screen sizes.
Your application should be deployed to GitHub Pages.
Your application's GitHub repository should contain a README.md file explaining the purpose and functionality of the application. The README.md file should include a screenshot of the completed application as well as a link to the deployed GitHub Pages URL.

User Story
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security

Business Context
For companies that handle large amounts of sensitive data, weak passwords can pose a real security threat. An application that can generate strong passwords quickly and effortlessly saves employees time and ensures secure access to data.

Acceptance Criteria
GIVEN that a user needs a new, secure password
WHEN prompted for password criteria
THEN a password is generated

![capture](https://user-images.githubusercontent.com/56567819/69487769-2c6ad880-0e25-11ea-8092-267396a64836.png)


This application's purpose is to generate a secure and random password using special characters, numeric characters, uppercase and/or lowercase letters, depending on the user-selected criteria. The user can then choose to generate another password, or copy their new password to the clipboard.

JavaScriptLogic: DECLARE characters array (charArray) variable and set them equal to to lower case & uppercase alphabet, special characters and numbers 0 - 9;

PROMPT user to generate a password
PROMPT user to select password length between 8 - 128
PROMPT user to select Character Type (i.e. - Special, #'s , Lowercase, & Uppercase)

VALIDATE user input after each prompt

GENERATES a completely random password

THEN gives user option to copy to clipboard
