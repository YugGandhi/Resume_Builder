# SGP-1
Resume Builder

Overview

Resume Builder is a web-based application that allows users to create, customize, and download professional resumes using predefined templates. The application supports user authentication, resume storage, and template-based resume generation.

Features

User authentication (Login, Registration, Password Reset)

Resume creation and customization

Multiple resume templates

Resume preview and download options

User profile management

Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Project Structure

SGP-1(Resume Builder)/
├── assets/                # Additional assets like images, icons, etc.
├── styles/                # CSS stylesheets
├── images/                # Image assets
├── actions/               # Backend action scripts
├── templetes/             # Resume template files
├── index.php              # Main entry point
├── Login.php              # User authentication handling
├── database.class.php     # Database connection handling
├── insert_user_details.php # User data processing
├── display_resume.php     # Resume preview functionality
├── resume template-X/     # Different resume templates
├── myresumes.html         # User saved resumes page
└── README.md              # Project documentation

Installation

Clone the repository:

git clone https://github.com/yourusername/resume-builder.git

Set up a local server (e.g., XAMPP, WAMP, LAMP) with PHP and MySQL.

Import the database (database.sql if available) into MySQL.

Configure database credentials in database.class.php.

Run the project in a browser:

http://localhost/resume-builder/

Usage

Register a new account or log in.

Create a new resume by filling in the required details.

Choose a resume template.

Preview and download your resume.

Contributing

If you'd like to contribute to the project, feel free to fork the repository and submit a pull request.

License

This project is open-source under the MIT License.
