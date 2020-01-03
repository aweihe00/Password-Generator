# Password-Generator

Unit 03 JavaScript Homework: Password Generator

Description:

Create an application that generates a random password based on user-selected criteria. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code.
The user will be prompted to choose from the following password criteria:
1. Length (must be between 8 and 128 characters)
2. Character type:
3. Special characters (see examples)
4. Numeric characters
5. Lowercase characters
6. Uppercase characters

Business Context:

For companies that handle large amounts of sensitive data, weak passwords can pose a real security threat. An application that can generate strong passwords quickly and effortlessly saves employees time and ensures secure access to data.

![capture](https://user-images.githubusercontent.com/56567819/69487769-2c6ad880-0e25-11ea-8092-267396a64836.png)

Link to site deployed https://aweihe00.github.io/Password-Generator/

This application's purpose is to generate a secure and random password using special characters, numeric characters, uppercase and/or lowercase letters, depending on the user-selected criteria. The user can then choose to generate another password, or copy their new password to the clipboard.

JavaScriptLogic: DECLARE characters array (charArray) variable and set them equal to to lower case & uppercase alphabet, special characters and numbers 0 - 9;

PROMPT user to generate a password
PROMPT user to select password length between 8 - 128
PROMPT user to select Character Type (i.e. - Special, #'s , Lowercase, & Uppercase)

VALIDATE user input after each prompt

GENERATES a completely random password

THEN gives user option to copy to clipboard
