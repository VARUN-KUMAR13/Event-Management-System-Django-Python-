# Event-Management-System-Django-Python-

## Overview

The **Event Management System** is a web-based application built using **Django and Python** that allows users to create, manage, and participate in events efficiently. This project is designed for event organizers to streamline event planning and execution.

## Technologies Used

- **Django** - High-level Python web framework for rapid development.
- **Python** - Core language for backend development.
- **SQLite** - Default database for Django projects (can be switched to PostgreSQL or MySQL as needed).
- **HTML, CSS, JavaScript** - For frontend styling and interactions.

## Features

- User authentication and authorization (Admin & Users)
- Create, update, delete, and manage events
- Event registration and participation
- Dashboard for event analytics
- Email notifications for event updates

## Installation & Setup (Windows)

Follow these steps to set up the project on your local machine:

### Prerequisites

Ensure you have Python installed (check Django-compatible versions):

```sh
python --version
```

### Setup Steps

1. **Clone the repository:**

   ```sh
   git clone https://github.com/VARUN-KUMAR13/Event-Management-System-Django-Python-.git
   ```

2. **Navigate to the project directory:**

   ```sh
   cd Event-Management-System-Django-Python
   ```

3. **Create a virtual environment:**

   ```sh
   python -m venv env
   ```

4. **Activate the virtual environment:**

   ```sh
   env\Scripts\activate  # Windows
   ```

5. **Install required dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

6. **Apply database migrations:**

   ```sh
   python manage.py migrate
   ```

7. **Create a superuser (admin access):**

   ```sh
   python manage.py createsuperuser
   ```

   - Provide admin credentials (email, username, password)
   - Type `y` to bypass user validation if needed

8. **Run the development server:**

   ```sh
   python manage.py runserver
   ```

9. **Access the application:**

   - Open a web browser and go to: `http://127.0.0.1:8000/`

## Usage

- Admins can log in via `/admin` to manage events and users.
- Users can register, browse, and participate in events.

##

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

Katakam Varun Kumar

VARUN-KUMAR13
