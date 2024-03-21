# Project Documentation: Contact Form and Login Page

## Introduction
This project consists of two main components: a contact form and a login page. The contact form allows users to input their personal information, while the login page enables users to authenticate using a username and password.

## Contact Form
### Approach
The contact form is designed using HTML and styled using CSS. It includes fields for the user's first name, last name, age, email, mobile number, alternate mobile number, current address, and permanent address. JavaScript is utilized to validate the form inputs and ensure data integrity before submission.

### Validation Implemented
1. **Required Fields**: Checks if essential fields such as first name, last name, age, email, and current address are filled out.
2. **Age Validation**: Ensures that the user's age is at least 18 years old.
3. **Mobile Number**: Validates that the mobile number and alternate number are 10 digits long and not the same.
4. **Email Format**: Verifies that the email address follows a standard format with "@" and ".com".

### Challenges Faced
1. **Cross-Browser Compatibility**: Ensuring consistent behavior across different web browsers.
2. **User Experience**: Balancing between providing informative alerts and not overwhelming users with too many messages.

## Login Page
### Approach
The login page is also created using HTML, CSS, and JavaScript. It features fields for the user to input their username and password. Similar to the contact form, JavaScript is employed to validate the form inputs and provide feedback to the user.

### Validation Implemented
1. **Required Fields**: Checks if both the username and password fields are filled out.
2. **Length Requirements**: Ensures that the username is at least 6 characters long and the password is at least 8 characters long.
3. **Special Character**: Verifies that the password contains at least one special character.

### Challenges Faced
1. **Password Security**: Balancing between enforcing strong passwords and user convenience.
2. **Error Handling**: Providing clear and concise error messages without compromising security.

