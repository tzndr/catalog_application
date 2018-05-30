# catalog_application

## About
This project was created using Python and its Flask framework to build a clothing catalog (General Clothing Catalog) that utilizes SQL Alchemy to perform database queries with create, update, read, and delete (CRUD) functionality. Additionally, the catalog requires an OAuth 2.0 login session through third-party authentication with tokenization to allow for any database CRUD operations.  A logged in user is able to create and delete categories of clothing as well as create, edit and delete products within those categories including the product name, description, image, and price.  The main page will also display the last 12 products created. Additionally, all categories and products have JSON API endpoints. Users not logged in can view the catalog and its products _without_ CRUD options.

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
