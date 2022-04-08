 Project: #2/ JTC: New York City Guide

Group Members: Darien Davis https://github.com/DDavis-CP
               Shawn Hing https://github.com/Shawner1

Create and run a virtual environment using venv: mkdir [name of your directory]
                                                 cd [name of your directory]
                                                 clone into directory: https://github.com/Shawner1/NYC-Guide.git 
                                                 run: python -m venv django-env (or python3 -m venv django-env)
                                                 then:(Windows users) django-env\Scripts\activate.bat 
                                                      (Bash users) source django-env/Scripts/activate
                                                      (Unix or MacOS) source django-env/bin/activate

Install project dependencies with pip:           pip install django

Run the Django application:                      pip freeze > requirements.txt
                                                 now: python manage.py runserver
                                                 finally: http://127.0.0.1:8000/

                                          









