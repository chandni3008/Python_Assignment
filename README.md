# Flask Blog
This a simple blog website created using Flask. Flask is a web application framework written in Python language.
****
## Pre-Requites:
**You should have python installed in your system.**
## Local installation guide:
**Clone the repository**
```bash
git clone https://github.com/chandni3008/Python_Assignment.git
```
**Install virtual enviornment**
```bash
pip install virtualenv   // install module to create virtual environment
virtualenv myenv OR  python -m venv myenv   //create environment
python -m enviroment --help
deactivate  //To deactivate the environment (do not use this unless you want to deactivate your environment)
```
**Activate the  virtual enviornment**
```bash
cd flaskblog\myenv
Scripts\activate
```
## Installing Flask
```bash
pip install flask
```
**Installing required dependencies**
```bash
pip install flask-sqlalchemy
pip install flask-bcrypt
pip install Flask-wtf
pip install flask-login
pip install email_validator
pip install Pillow
pip install flask-mail
pip install flask-serialize
```

## Create the Database
**Create datbase in blog directory using :**
```bash
 from flaskblog import db
 from flaskblog.models import User, Post
 db.create_all()
 ```

 
 
 
 ## Run the code at your local environment
```bash
 python app.py
 ```
>Open your browser and the site can be found running at http://127.0.0.1:5000/ 

## Your Project will look like this
![image](TargetUrl)