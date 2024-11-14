Django User Authentication System

This is a Django web application that implements a user authentication system with features like sign-up, login, password reset, password change, and user profile management.
Features

- User Registration: Allows users to sign up using a username, email, and password.
- User Login: Users can log in with their username/email and password.
- Password Reset: Users can reset their password if they forget it by receiving a password reset email.
- Password Change: Authenticated users can change their password.
- Profile Management: Users can view their profile information (username, email, date joined, last updated).
- Dashboard: Displays a greeting message and quick links to profile and change password.

Technologies Used

- Django: Web framework used for building the application.
- SQLite: Database used to store user data (can be replaced with PostgreSQL, MySQL, etc. in production).
- HTML/CSS: For frontend user interface.
- Bootstrap: For styling and responsiveness.
- Email Functionality: Uses Django's email system to send password reset instructions.

Installation

1. Clone the repository:
  
    git clone https://github.com/hrbhoomi/Django_Project.git
    cd myproject  // main folder includes accounts , myproject
  
2. Install dependencies:

    pip install -r requirements.txt

3. Apply migrations to set up the database:
   
    python manage.py migrate


4. Create a superuser to access the Django admin:
    
    python manage.py createsuperuser

5. Run the development server:
    
    python manage.py runserver

    Access the app at `http://127.0.0.1:8000/`.

Screenshots

Below is a screenshot of the Sign-Up page:


![Sign-Up Page](static/images/signup.png)

## File Structure

- **accounts/**: Contains user-related views, forms, and templates.
- **myproject/**: Contains the main Django project settings and URLs.
- **static/**: Contains static files like CSS, images, and JavaScript.
- **templates/**: Contains HTML templates for user interfaces.
- **media/**: Store uploaded user files (if any).

## Credits

- Django Documentation: https://www.djangoproject.com/
- Bootstrap: https://getbootstrap.com/
- Email Functionality: For password reset emails, see Django's `send_mail` documentation.

---

### Adding Image to README

To include an image in your README file, follow these steps:

1. Place the image (e.g., `signup.png`) in a directory inside your project, such as `static/images/`.
   
2. In your **README.md**, use the following syntax to add the image:

    ```markdown
    ![Sign-Up Page](static/images/signup.png)
    ```

    Make sure the path is relative to the root of your repository. If you store the image in a folder such as `static/images`, the above syntax will work correctly.

---

Feel free to modify and expand upon this template depending on the specific details of your project!
