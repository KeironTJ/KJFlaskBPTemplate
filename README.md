
# Basic Flask Application Template

This template provides a starting point for a Flask web application with User and Admin functionality. It is designed to be easily extendable and customizable for various project needs.

## Features

- **User Authentication**: Secure user registration and login functionality.
- **Admin Panel**: A simple admin interface to manage users.
- **Blueprints**: Organized application structure using Flask Blueprints for scalability.
- **Database Integration**: Pre-configured database setup for user data storage.
- **Form Handling**: Examples of form submission and validation.
- **Error Handling**: Basic error handling setup for a smoother user experience.

## Getting Started

### Prerequisites

- Python 3.6 or later
- Flask
- SQLAlchemy (for database interactions)
- Flask-Login (for user authentication)
- Flask-Admin (for the admin panel)

### Installation

1. Clone the repository: git clone https://github.com/KeironTJ/KJFlaskBPTemplate
2. Navigate to the project directory: cd yourprojectname
3. Install the required packages: pip install -r requirements.txt
4. Run the setup: python setup.py

## Structure

- `app.py`: The entry point of the application.
- `/models`: Contains the SQLAlchemy models.
- `/templates`: HTML templates for the application.
- `/static`: Static files like CSS and JavaScript.
- `/auth`: Blueprint for authentication functionalities.
- `/admin`: Blueprint for admin functionalities.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.