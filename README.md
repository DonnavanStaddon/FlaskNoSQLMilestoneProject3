Headers

# UX
# Link to Live Website Hosted On Heroku
https://chatdays-d81d3a7354ce.herokuapp.com/

## Project Goals
The primary goal of Chat Days is for a user to discuss any topic thats been chosen by the admin.
In the future the any one will be able to create a topic

## "Experience Admin privileges"
### To manager and add categories you need to login as admin the login details are below

### Login as an Admin
#### Username: Admin
#### Password: 567890

### Subject Goals
The goal is for the user  to learn and have fun

Persons Experience:

1. Fun to use product
2. Easy to navigate
3. Easy Registration 
4. Educational
5. Can ask for help
6. Can become an Admin

## Design of website
I used https://materializecss.com/ for most of the css design of this website

#### Fonts
* I used fonts with images, these images match the naviagtion page so as to hepl the use understand the page hes is on better

#### Styling
* I chose cards as the main presentation of the website, because they have a nice look and feel

#### Color of webpage
* I used purple as the main color of the website because it is very reach and royal


## Backend
* Flask https://flask.palletsprojects.com/en/2.3.x/
* Mongo DB https://www.mongodb.com/
* Jinja https://jinja.palletsprojects.com/en/3.1.x/
* werkzeug https://werkzeug.palletsprojects.com/en/2.3.x/
* Heruku https://dashboard.heroku.com/

## Heroku Deployment

1. Create a requirements.tx file using the terminal command pip freeze > requirements.txt
2. Create a Procfile with the terminal command echo web: python app.py > Procfile
3. On VS Code click source control Type in a commit in the message box eg first commit then clcik the dropdown on the commit button then press commit & push to github
4. Create a new app in Heroku website by clcicking new button in the dashoard. Give it a name and set it to your closest country
5. Your new app is now created
6. From the Heroku dashboard click on deploy > "Deployment method" and select Github
7. Confirm selction
8. In the Heroku dasboard for the application click settings > reveal config vars
10. Set the following vars


| Key        | Value     |
| -----------|:----------:
| Debug      |  FALSE    |
| IP         |  0.0.0.0  |
| MONGO_URL  |mongodb+srv://cluster0.ab123.mongodb.net/myFirstDatabase Using MongoDB: 7.0|
| PORT       |  5000     |
|SECRECT_KEY |SECRECT_KEY|


11. In the Heroku dashbaord clcik deploy
12. Your site is now live 


## IDE
## Anaconda
## I installed and used Anaconda because it comes with all of the packages needed
* Link https://www.anaconda.com/
1. Install Anaconda
2. Open Visual Studio from with Anaconda's Dashboard
* Anaconda
* Visual Studio code is the IDE i used