# Admin Dashboard

A responsive **Admin Dashboard** built with HTML, JavaScript, and Tailwind CSS. The project includes a signup and login system using browser Local Storage, protected dashboard access, logout functionality, and a dynamic users directory powered by the DummyJSON API.

## Live Demo

https://ishratalib.github.io/Admin-Dashboard/

## Technologies Used

* HTML5
* JavaScript
* Tailwind CSS
* Local Storage
* Fetch API
* DummyJSON API
* Git
* GitHub
* GitHub Pages

---

## Features

* User signup interface
* Login authentication using Local Storage
* Protected dashboard access
* Unauthenticated users are redirected to the login page
* Dynamic user avatar based on the registered user's first name
* Logout functionality
* Users directory
* Fetches live user data from DummyJSON API
* Dynamically generates table columns from API data
* Special styling for user roles
* Loading state while fetching users
* Responsive layout
* Built with Tailwind CSS

---

## Authentication

This project uses **Local Storage** for frontend authentication.

When a user signs up, their information is stored in the browser. During login, the entered email and password are compared with the stored credentials.

The dashboard is protected and can only be accessed when the user is logged in.

> **Note:** This is a frontend demonstration project. It does not use a backend, database, or server-side authentication.

---

## API

The dashboard retrieves user information from the **DummyJSON Users API**.

The fetched data is processed dynamically to generate the users table and display available user information.

---

## Responsive Design

The dashboard is designed to work across different screen sizes, providing a clean and responsive admin interface.

---

## Future Improvements

* Backend authentication
* Database integration
* Admin roles and permissions
* User CRUD operations
* Search and filtering
* Pagination
* Server-side authentication
* Secure password handling

---

## Author

**Ishrat Talib**
