# Authentication System
## This project is a simple Django-based authentication system designed to manage user registration, login, and access control. It provides essential authentication functionality, such as allowing users to register and create accounts, log in securely, and access a protected dashboard that requires authentication.

## The system is designed with middleware to handle authentication logic, ensuring that:
Authenticated users can access restricted areas, like the dashboard, without needing to log in again.
Guest users (non-authenticated) are redirected to the login page when trying to access protected views.
The application is structured with clean UI elements, using Bootstrap for responsive and modern layouts, providing a smooth user experience across devices.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Features
- User registration
- User login and logout functionality
- Protected dashboard accessible only by authenticated users
- Middleware to redirect authenticated users to the dashboard and guests to the login page
- Bootstrap-powered responsive design
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Technologies Used
- Django: A Python web framework used for building the backend.
- Python: The programming language used to develop the application.
- HTML: For structuring, with Bootstrap 4 for responsive design.
- Bootstrap 4: To style the UI components and layout.
- SQLite: Default Django database for storing user data.
