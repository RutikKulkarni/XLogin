# XLogin

## Overview

XLogin is a straightforward login form interface developed with React. It features a username and password input field, with validation ensuring the correct combination of "user" for the username and "password" for the password. The interface provides user feedback based on successful or unsuccessful login attempts.

## Application Requirements

- **Login Form:**
  - Use the **form** element to create the login form.
  - Implement fields for both username and password.
  - Use **label** and **input** elements for better structure and accessibility.
  - Label the fields as "Username" and "Password."

- **Initial Render:**
  - Display an image upon the initial render to enhance the user interface.

- **Field Validation:**
  - Both username and password fields are mandatory.
  - The user should not be able to submit the form without filling in both fields.
  - Display a message indicating the necessity to fill both fields.

- **Successful Login:**
  - Upon clicking the "Submit" button after filling the username as "user" and password as "password," display a "Welcome, user!" message.

- **Invalid Login:**
  - If the user provides a username other than "user" or a password other than "password" and clicks the "Submit" button, show the message "Invalid username or password."
