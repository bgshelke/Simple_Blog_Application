Simple Django Blog Application

Overview
This is a simple blog application built using Django. 
The app allows users to read and create blog posts, with basic user authentication and CRUD functionality for managing their own posts. 
Authenticated users can create, update, and delete their posts.
Administrators can manage all posts through the Django admin interface.


Core Features:
User Authentication: Users can sign up, log in, and log out.
CRUD Operations for Blog Posts: Authenticated users can create, read, update, and delete their own blog posts.
Post Management: Users can only manage their own posts. Admin users can manage all posts via the admin interface.
Home Page: Displays all blog posts in reverse chronological order.
Post Detail Page: Users can click on a blog post title to view the details.
Admin Panel: Administrators can manage blog posts through the Django admin panel.


Sure! Here's a README.md file content for your Simple Django Blog Application project. This README.md provides a clear and concise guide for setting up, running, and understanding your Django blog application.

Simple Django Blog Application
Overview
This is a simple blog application built using Django. The app allows users to read and create blog posts, with basic user authentication and CRUD functionality for managing their own posts. Authenticated users can create, update, and delete their posts. Administrators can manage all posts through the Django admin interface.

Core Features:
User Authentication: Users can sign up, log in, and log out.
CRUD Operations for Blog Posts: Authenticated users can create, read, update, and delete their own blog posts.
Post Management: Users can only manage their own posts. Admin users can manage all posts via the admin interface.
Home Page: Displays all blog posts in reverse chronological order.
Post Detail Page: Users can click on a blog post title to view the details.
Admin Panel: Administrators can manage blog posts through the Django admin panel.


Requirements
Python 3.x
Django 4.x
SQLite (or another database of your choice)


Setup Instructions
1. Clone the Repository
Clone the project repository to your local machine:
  git clone https://github.com/bgshelke/Simple_Blog_Application.git
  cd Blog_Application

2. Set Up a Virtual Environment (Optional but Recommended)
   activate virtual environment
   venv\Scripts\activate
-create new virtual environment if required

3. Install Dependencies
Install the required dependencies listed in requirements.txt:
  pip install -r requirements.txt

4. Apply Migrations
Set up the database by applying the migrations:
py manage.py makemigrations
py manage.py migrate

5. Create a Superuser (Admin)
To access the Django admin panel, create a superuser:
python manage.py createsuperuser

6. Run the Development Server
Start the Django development server:
python manage.py runserver


application will be available at http://127.0.0.1:8000/


How to Use
Sign Up: Go to /signup/ to create an account.
Login: Once signed up, log in using /login/.
Create a Blog Post: After logging in, go to /create/ to create a new blog post.
View Blog Posts: The homepage (/) displays a list of all blog posts. Click on a title to view the full post.
Edit or Delete Posts: On a post’s detail page, you can edit or delete the post if you are the author.
Admin Interface: Access the admin panel at /admin/ (requires the superuser credentials) to manage all blog posts.


Admin Panel
To access the admin panel, navigate to:
http://127.0.0.1:8000/admin/
Use the superuser credentials created earlier to log in and manage blog posts.


Technology Stack
Django: A high-level Python web framework for building web applications quickly and securely.
SQLite: The default database used for development.
HTML/CSS: For structuring and styling the frontend templates.
