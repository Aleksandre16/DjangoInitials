# Django Initial Project Setup

This repository contains a Django project setup with basic authentication and an admin interface.

## Getting Started

### Prerequisites

-Check The Requirements File

### Installation

1. **Clone the Repository (Optional):**
   ```
   git clone Aleksandre16/DjangoInitials
   ```
6. **Apply Migrations:**
   ```
   python manage.py migrate (it was necessary for me)
   ```

7. **Create a Superuser:**
   ```
   python manage.py createsuperuser
   ```
   Follow the prompts to create a superuser with a username, email, and password.

8. **Run the Development Server:**
   ```
   python manage.py runserver
   ```

9. **Access Django Admin:**
    - Open a web browser and go to `http://127.0.0.1:8000/admin/` (local)
    - Log in with the superuser credentials you just created.

