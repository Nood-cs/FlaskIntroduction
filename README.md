# Flask Introduction

Basic CRUD app in Python and Flask. 

### Getting Started

  1. [Python](https://www.python.org/downloads/) Version: 3.9+
  2. Clone this repo: `git clone https://github.com/Nood-cs/FlaskIntroduction.git`
  3. Activate virtualenv: 
  ``` 
  python -m venv venv
  
  venv\Scripts\activate
  ```
  *You might need to change the ExecutionPolicy to Unrestricted, so that you can run the script Activate.ps1*
  ```
  Set-ExecutionPolicy Unrestricted -scope Process
  ```
  
  4. Install dependencies with pip: `pip3 install -r requirements.txt`
  5. Make sure to populate the database by opening a Python shell from within the app and running
  ```
  from app import db
  
  db.create_all()
  
  exit()
  ```
  6. Run the app: `python app.py`
  
