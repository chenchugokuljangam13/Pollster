# Pollster

Pollster is a web application for creating, managing, and participating in polls and voting events. Built with the Django framework, it provides a secure, scalable, and user-friendly platform for online voting.

## Features

- **User Authentication**: Secure registration, login, and profile management.
- **Poll Creation**: Easy creation and management of polls.
- **Voting System**: User-friendly voting interface and anonymous voting.
- **Real-Time Results**: Dynamic display of poll results with graphical representation.
- **Responsive Design**: Mobile-friendly and intuitive user experience.

## Technologies Used

- **Backend**: Django, Python
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite (development), PostgreSQL/MySQL (production)
- **Deployment**: Docker, Nginx, Gunicorn, AWS/GCP

## Installation

### Prerequisites

- Python 3.x
- pip
- virtualenv (optional but recommended)

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/chenchugokuljangam13/Pollster.git
   cd Pollster

2. **Create a virtual environment (optional):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install the dependencies:**
   ```bash
   pip install pipenv
   pipenv shell
   pipenv install django
   django-admin startproject pollster
   
4. **Change directory:**
   ```bash
   cd pollster

5. **Apply migrations:**
   ```bash
   python manage.py migrate

6. **Create a superuser (optional, for admin access):**
   ```bash
   python manage.py createsuperuser

7. **Run the development server:**
   ```bash
   python manage.py runserver

##  Usage
- Access the Application: Open a web browser and go to http://127.0.0.1:8000/.
- Admin Interface: Access the admin interface at http://127.0.0.1:8000/admin/ using the superuser credentials created during setup.
- Create Polls: Use the admin interface to create and manage polls.
- Vote: Participate in polls via the main application interface.
- View Results: Check real-time results of active polls.

### Contributing
1. **Fork the repository on GitHub by Clicking on the Fork Button**

2. **Clone your fork:**
   ```bash
   git clone https://github.com/chenchugokuljangam13/Pollster.git
3. **Create a new branch:**
   ```bash
   git checkout -b feature/your-feature

4. **Make your changes and commit:**
   ```bash
   git add .
   git commit -m "Add your commit message"

5. **Push to your fork:**
   ```bash
   git push origin feature/your-feature

6. **Create a pull request on GitHub.**
