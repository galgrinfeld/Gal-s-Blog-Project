# Flask Blog Application
## Overview
This is a blog application built with Flask, featuring user authentication, the ability to create and manage blog posts, and a commenting system. Users can register, log in, and interact with posts.

## Features
- User registration and login
- Create, edit, and delete blog posts (admin only)
- Comment on blog posts (registered users only)
- Gravatar integration for user avatars
- Rich text editing with CKEditor
- Password hash generating with werkzeug.security

## Technologies Used
- Python
- Flask
- Flask-Bootstrap
- Flask-CKEditor
- Flask-Login
- Flask-SQLAlchemy
- SQLite

## Installation
### Prerequisites
Make sure you have Python installed on your machine.

### Clone the Repository
```bash
git clone https://github.com/galgrinfeld/Gal-s-Blog-Project.git
```

### Create a Virtual Environment
```bash
python -m venv venv
```
### Activate the Virtual Environment
- On Windows:
``` bash
venv\Scripts\activate
```
- On macOS/Linux:
``` bash
source venv/bin/activate
```

### Install Required Packages
Install Required Packages
Make sure to have a ``requirements.txt`` file in the project directory. Use the following command to install the dependencies:
``` bash
pip install -r requirements.txt
```
### Running the Application
``` bash 
python main.py
 ```

Access the application in your web browser at ``http://127.0.0.1:5003``.

## Configuration
- The application uses SQLite as the database. The database will be created automatically on the first run.

- Update the ``SECRET_KEY`` in ``app.py`` for added security.

## Useage
1. Register a new account.
2. Log in to create new blog posts (admin users only).
3. Comment on posts as a registered user.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Flask](https://flask.palletsprojects.com/en/3.0.x/)

- [Bootstrap](https://getbootstrap.com/)
- [CKEditor](https://ckeditor.com/)
- [Flask-Login](https://flask-login.readthedocs.io/en/latest/)

