# Content Management System

## About
A user-friendly, editable content management system created with HTML, CSS, and Python with Flask and SQLAlchemy. This application queries a PostgreSQL database and uses CRUD (Create, Read, Update, Delete) functionality and OAuth to allow a logged-in user to add, remove, and edit the catalog's categories and products. An anonymous user is able to view the catalog without editing privileges. This application also has JSON endpoints for each created category and item.

## Running the Program
1. Download and install [Virtual Box](https://www.virtualbox.org)
1. Download and install [Vagrant](https://www.vagrantup.com/downloads.html)
1. Clone this repository and place all files and folders inside your vagrant directory
1. Navigate `cd` to your Vagrant directory within your terminal
1. Execute the command `vagrant up`
1. Follow with the command `vagrant ssh`
1. Navigate `cd` back to the Catalog Application directory within your Vagrant directory
1. Run the program `python views.py`
1. Open your default browser and visit **http://localhost:8000**
