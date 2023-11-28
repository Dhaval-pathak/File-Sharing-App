# File-Sharing-App

## Overview
File storage & sharing system (like Google Drive) built with Django (Python). This feature-rich drive storage system allows you to manage and back up your files in the cloud. You can upload any file to the drive.

### Features
- **File Sharing**: Share files and folders with other people easily.
- **Vault**: Hide your important and confidential files in a secure vault, which requires a password to access.
- **Modern Material Design**: Enjoy a better and simpler UI for easy file management.

## Screenshots
### Login / Signup
![Login / Signup](https://user-images.githubusercontent.com/30389552/79065779-88e56c00-7cd0-11ea-90ec-95c9a39b5304.png)

### Dashboard
![Dashboard](https://user-images.githubusercontent.com/30389552/79065790-a1558680-7cd0-11ea-8211-f1e652631b72.png)

### Upload Files
![Upload Files](https://user-images.githubusercontent.com/30389552/79065842-0dd08580-7cd1-11ea-9232-ac7a2349a4f3.png)

### Vault
![Vault](https://user-images.githubusercontent.com/30389552/79065849-1a54de00-7cd1-11ea-8e38-bddc42591348.png)

## Installation and Setup

### Prerequisites
- Python
- Django
- PyMySQL
- MySQL

### Setup Steps

1. **Install Python and Django**:
   - Ensure Python is installed on your machine.
   - Install Django using `pip install Django`.

2. **Install PyMySQL**:
   - Install PyMySQL with `pip install pymysql`.
   - Replace the `__init__.py` file in the PyMySQL directory with the provided one in the project's `pymysql` folder.

3. **Install MySQL and Set Up the Database**:
   - Download and install MySQL Server.
   - Optionally, install PHPMyAdmin for database management.
   - Create a new database for the Django project.
   - Import the `pydrive_db.sql` file into your MySQL database.

4. **Configure Django to Use the Database**:
   - Update the `DATABASES` setting in the Django project's `settings.py` file with your MySQL database details.

5. **Migrate Django Models**:
   - Run `python manage.py migrate` in your Django project directory.

6. **Run the Django Project**:
   - Start the server using `python manage.py runserver`.
   - Access the project at `localhost:8000` or the appropriate port.
