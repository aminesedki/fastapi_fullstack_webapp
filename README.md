# fastapi-blog
This project was realized as part of the **FastAPI Full Stack Web Development** course, available on [Udemy](https://www.udemy.com/share/104zCC3@5Asna4wG9MYmeOjX40dGmH6UjMBAZbVy5KHmMDRA_EFTJCSnVjNVvwBmj1UQLoZg/).



## Technology Stack:
* FastAPI
* Uvicorn
* Pytest
* Sqlalchemy
* Postgres


## How to start the app ?
```
git clone https://github.com/aminesedki/fastapi-fullstack-webapp
cd .\fastapi-fullstack-webapp\
python -m venv env   #create a virtual environment
.\env\Scripts\activate  #activate your windows virtual environment (Linux/Mac: source env/bin/activate)
cd .\backend\
pip install -r .\requirements.txt
uvicorn main:app --reload     #start server
visit  127.0.0.1:8000/
```

Features:
 -   Connecting to Database
 -   Schemas
 -   Dependency Injection
 -   Password Hashing
 -   Unit Testing (What makes an app stable)
 -   Authentication login/create user/get token
 -   Authorization/Permissions
 -   Jinja templating
 -   Unit testing
 -   Js bootstrap frontend web app 
