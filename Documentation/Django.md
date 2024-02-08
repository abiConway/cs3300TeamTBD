# Creating a Virtual Environment & Django Project
1. First, Before Anything: Check Pyton Version -- should be using 3.11
     - Linux/MacOS\
       `python3 --version`
     - Windows\
       `py -3 --version`
     - To make sure what Python versions are compatible with Django versions, see this [link](https://docs.djangoproject.com/en/4.2/faq/install/)

2. Next, after you have organized & set up your directories to your liking: create virtual environment
     - `python3 -m venv djvenv`
  
3. Activate virtual environment
     - `source djvenv/bin/activate`

4. Install django in virtual environment. For this specific instance, please make sure it is django version 4.2. To do this, simply add this syntax after the command to install django:
     - `pip install Django==4.2`

5. Upgrade pip
     - `python3 -m pip install --upgrade pip`

7. Create a django project
     - `django-admin startproject django_project`

9. Run server (ignore mitigation warnings)
      - `python manage.py runserver`

11. Open second terminal, activate the virtual environment (go to directory venv is in, enter command: source `djvenv/bin/activate`)

12. From virtual environment create requirements file of what is installed
      - `pip freeze > requirements.txt`
      - for more info on pip freeze, visit this [link](https://note.nkmk.me/en/python-pip-list-freeze/)
