# Developers Blog

Full featured web application using flask framework, SQLite, python and deployed on linux server using nginx and gunicorn. 
This is a Blog style web application where different users can make different posts. With a user management system. Once a new user is registered, they can login and if they have forgot their password, then they can get their password reset email sent to their email address.
Once a user is signed in, they can check their Account page and update any information they please to update, including their profile picture (there is a default picture in case if a user did not have picture to upload). Profile pictures are resized automatically to save space on the web server. A user can write a new post, click on their post and they can also update or delete their post. From the home page, users can look at other user's posts.

Please note: sidebar is work under progress.


## Getting Started

These instructions will get you a copy of this project up and running on your local machine. 

### Prerequisites

To install and run this repository on your local mmachine, you will need to create an environment.

```
Read more at http://flask.pocoo.org/docs/1.0/installation/#install-flask
```

### Installing

A step by step series of examples that tell you how to get this app running on your local machine.

First: clone this repository.

```
git clone https://github.com/nahrinoda/developers-blog.git
```
second: activate your vertual enviornment.

```
venv\Scripts\activate
```

Second: run the app on your local host.

```
python run.py
```

[Live Demo](http://198.58.123.127/)

## Built With

* [Flask](http://flask.pocoo.org/) - Microframework for Python
* [SQLite](https://www.sqlite.org/index.html) - Database engine
* [Linode](https://linode.com/coreyschafer) - Linode cloud server with linux


## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
