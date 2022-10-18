# Book House (LMS)

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info

* This project is used to depict library management system for a college.
* A user can add himself as member and perform activities like searching, issuing, and returning books.
* Information is saved into database rendered through MySQL via XAMPP. 
* We can update the records including the book details.

## Technologies
Project is created with:
* Python3 (v==3.8.10)
* XAMPP (v==8.1.10)
	
## Setup
* Install the dependencies ```mysql``` and ```mysql-connector```

```
$ pip install mysql
$ pip install MySQL-Python
$ pip install mysql-connector
```

* Open the XAMPP Control Panel.
* Open admin page for MySQL. 
* Create the tables required for the database (Book, Member and Transaction) with the required schema.

* To run this project, clone it locally using git:
```
$ git clone https://github.com/bistimulus/Book-House.git
$ cd Book-House
$ python book_house.py

```
