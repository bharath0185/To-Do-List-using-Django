# To-Do-List-using-Django

Certainly! Here’s a detailed README file for a "To Do List" project using Django:

---

# To Do List Using Django

This project is a simple web-based "To Do List" application built using Django, a high-level Python web framework. The application allows users to manage tasks, mark them as complete, and delete them.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Database Setup](#database-setup)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [License](#license)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.x.
- You have installed Django (version 3.x or higher).

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/to-do-list-django.git
   cd to-do-list-django
   ```

2. **Create a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the Django Project:**

   If you haven't already set up the Django project, you can do so by running:

   ```bash
   django-admin startproject todolist
   cd todolist
   django-admin startapp tasks


## Database Setup

1. **Run Migrations:**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

2. **Create a Superuser:**

   ```bash
   python manage.py createsuperuser
   ```

3. **Load Initial Data (if needed):**

   If you have initial data to load, you can do so by creating fixtures and using:

   ```bash
   python manage.py loaddata initial_data.json
   ```

## Running the Application

1. **Start the Development Server:**

   ```bash
   python manage.py runserver
   ```

2. **Access the Application:**

   Open your web browser and go to `http://127.0.0.1:8000/` to see the application running.

## Usage

1. **Home Page:**

   - The home page displays a list of tasks.
   - Users can view, edit, or delete tasks.

2. **Add a New Task:**

   - Navigate to the task creation form.
   - Fill out the form with task details and submit it to add a new task.

3. **Edit a Task:**

   - Click on a task to view its details.
   - Use the edit option to modify task details.

4. **Delete a Task:**

   - Navigate to the task you want to delete.
   - Confirm deletion to remove the task.

5. **Admin Interface:**

   - Admins can log in to the admin interface to manage tasks.
   - Access the admin interface at `http://127.0.0.1:8000/admin/`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

