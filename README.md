# To-Do Lists with Python, Django and Bootstrap
The project is a Django application that works as to-do list manager. Bootstrap is used to style the application.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)


## General Information
The main page of the application displays all of to-do lists. There you may create a new list, edit the exisiting one or delete it.


## Technologies Used
- Django 3.2.9
- Bootstrap 5


## Features
By clicking the "Add a new list" button, a page will be displayed where it is possible to name and create a new list. Next, you give a title to your list. It is also possible to add to-do items to the list by clicking "Add a new item". After choosing the option, the item may be given a title, and more details can be added in the "Description" box. It is also possible to set up the due date. To delete the list you just need to click "Delete this list" button.


## Setup
The project's requirements are listed in a requirements.txt file.

Download the code from this GitHub repository and activate the virtual environment. Make sure that you have Python 3.6 or newer installed. The next step is to install the Django library and its dependencies. You may specify a particular version or leave the version unspecified. In the Windows Command Prompt write:

    (venv) C:\> python -m pip install django=="3.2.9"

Start the Django development server writing in the Windows Command Prompt:

    (venv) C:\> python manage.py runserver

And next navigate to http://localhost:8000/ in your browser.


## Usage
Click on "Add a new list". A new screen appears, offering a blank text box for the new list’s title.
Give your new list a name and press "Save". You are taken to the Edit List page, with the message "There are no to-do items in this list."
Click on "Add a new item". The "Create a new item" form appears. Fill in a title and a description, and notice that the default due date is exactly one week ahead. You can change it if you like.
Click again on "Django To-do Lists" to return to the home page. Now you can continue to test the app’s navigation and functionality by adding more lists, adding more items to lists, modifying item details, and deleting items and lists.


## Project Status
The project's status is _complete_.


## Acknowledgements
This project was based on "Manage Your To-Do Lists Using Python and Django" (https://realpython.com/django-todo-lists/).
I have also used "Bootstrap 5 Tutorial" (https://www.w3schools.com/bootstrap5/).


## Contact
Created by Adam Hoppe (adhoppe@poczta.fm) - feel free to contact me!


## License
This project is open source and available under the MIT License.
