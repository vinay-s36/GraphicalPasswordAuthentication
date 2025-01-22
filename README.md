
# Graphical Password Authentication

## Introduction
Graphical Password Authentication is a Django-based web application that provides a graphical approach to user authentication. Users authenticate using graphical patterns instead of traditional text-based passwords, enhancing security and user experience.

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite

## Setup Instructions

### Prerequisites
- Python 3.8 or later
- pip (Python package manager)
- Virtual environment (recommended)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/vinay-s36/GraphicalPasswordAuthentication.git
   cd GraphicalPasswordAuthentication
   ```

2. **Create and Activate a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the Database**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Configure Environment variables**
- Copy the `.env.example` file to `.env`:

   ```sh
   cp .env.example .env
   ```

- Open the `.env` file and add your email credentials:
   ```env
    EMAIL_USER='username'
    EMAIL_PASS='password'
   ```

    Replace `username`, `password` with your email credentials.


6. **Run the Development Server**
   ```bash
   python manage.py runserver
   ```
   Access the application at `http://127.0.0.1:8000/`.
