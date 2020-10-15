# Instagram-Clone

## Author
* Omar Hussein

## Description
This website is a clone of Instagram where people share their images and videos so that other users can view, comment and like on them. Users can sign up, login, logout, view and post photos, search and follow other users.

## live link

## User Story
As a user I need the following features:
1. Sign in to the application to start using.
2. Upload a pictures to the application.
3. Search for different users using their usernames.
4. See your profile with all your pictures.
5. Follow other users and see their pictures on my timeline.

## Setup Instructions
To get the project .......

#### Cloning the repository:
  - https://github.com/omarion3698/Instagram-Clone.git

#### Navigate into the folder and install requirements
  - cd Instagram-Clone
  - pip install -r requirements.txt

#### Install and activate Virtual(global)
  - virtualenv venv 
  - source venv/bin/activate

#### Install Dependencies
  - pip install -r requirements.txt

#### Setup Database
SetUp your database User,Password, Host then make migrate

  - python manage.py makemigrations instagram

#### Now Migrate
  - python manage.py migrate

#### Run the application
  - python manage.py runserver

#### Running the application
  - python manage.py server

#### Testing the application
  - python manage.py test

Open the application on your browser 127.0.0.1:8000.

## Technologies Used
- Python3.8
- Django1.11.17
- Heroku
- Html5
- Css3
- Javascript

## Contact Information
If you have any question or contributions, please email me at [omaribinbakarivic@gmail.com]

## License
- Lincense: MIT
- Copyright (c) 2020 Omar Hussein
