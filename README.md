FRIENDS
=============================================

> A blog for friends to share problems

* Live at heroku : [friendzbook.herokuapp.com](https://friendzbook.herokuapp.com/)

## Features
* Blog
* Upload image to Google Drive
* Login/Registration
* Like/Comment
* Search
* E-mailing

## Used Technologies
* Python
* Django
* SQLite3
* PostgreSQL
* HTML
* CSS
* JavaScript
* jQuery
* Bootstrap
* Google Drive API


## Installation of the project

### Create virtual environment and goto friends directory
```bash
virtualenv friends
cd .\friends\
```
* copy the project and paste in friends directory

### Activate virtualenv and install reequirements.txt
```bash
.\Scripts\activate
python -m pip install -r .\requirements.txt
```
### goto src directory and make db ready
```bash
cd .\src\
.\manage.py migrate
```
### Run dev server
```bash
.\manage.py runserver 8888
```
* now goto http://127.0.0.1:8888/

## Screenshots

***Homepage***
![image[(https://github.com/iraihankabir/friends/blob/master/screenshots/header.png)

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/index%20page.png)

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/footer.png)


***LoginRegistration***

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/login.png)

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/registration.png)

***Posts***

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/blog.png)

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/posts.png)

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/post%20detail.png)

***Profile***

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/profile.png)

![image](https://github.com/iraihankabir/friends/blob/master/screenshots/public%20profile.png)

