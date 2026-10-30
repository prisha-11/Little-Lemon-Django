# Little Lemon Restaurant API

This repository contains the back-end web development project for the Little Lemon restaurant, built using Django and Django REST Framework (DRF) as part of the Meta Back-End Developer Professional Certificate.

## Features
- **Menu Management**: Endpoints for listing, creating, retrieving, updating, and deleting menu items.
- **Table Booking**: Secure ViewSets for managing table reservations.
- **Authentication**: Token-based authentication and Djoser integration for user sign-up and login.
- **Database**: Configured to connect and persist data in MySQL.
- **Testing**: Built-in unit tests for models and API endpoints.

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/little-lemon-api.git
   cd little-lemon-api/littlelemon
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure MySQL Database:**
   - Create a MySQL database named `littlelemon`.
   - Update your credentials in `littlelemon/settings.py`.

5. **Run Migrations:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```
