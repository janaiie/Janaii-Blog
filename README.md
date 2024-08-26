live site: https://blog-j79b.onrender.com/

Blog  - Backend Operations
Overview

This project involves the development of backend operations for the MIT Clean Blog template. The primary focus was to enhance the template with a robust backend, enabling dynamic content management and secure user authentication.
Technologies Used

    MIT Clean Blog Template: A minimalist HTML/CSS template for personal blogs and portfolios.
    PostgreSQL: A powerful, open-source relational database used for storing blog content and user information.
    Flask: A lightweight Python web framework used to build the backend services.
    Flask-Login: An extension for Flask that manages user sessions and authentication.
    Werkzeug: A comprehensive WSGI utility library used for secure password hashing.

Features
Database Integration

    PostgreSQL: Integrated PostgreSQL to manage blog posts, user data, and other relational information. The database schema was designed to support efficient querying and data management.

Authentication

    Flask-Login: Implemented Flask-Login to handle user authentication. Users can register, log in, and log out securely. The authentication system ensures that only authorized users can access or modify certain content.

    Werkzeug: Used Werkzeug for password hashing, providing a secure way to store user passwords. Passwords are hashed before storage, enhancing the security of user credentials.


How It Works

    User Setup and Blog Management:
        Users can set up their own blogs where they can create and manage posts.
        All registered users can view, reply to, and share their views on these posts.

    Admin Role:
        The user with the first user ID is designated as the admin.
        The admin user has special privileges, including the ability to post, edit and delete blog posts.

    User Interaction:
        Regular users can interact with the posts by commenting and sharing their opinions.
        
