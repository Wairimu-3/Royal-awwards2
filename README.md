# Royal-Awwards

## By: Margaret Kimani

## Description
+ The is an application that allows a user to post a project he/she has created and get it reviewed by his/her peers.

## Live link:

+ https://royalawwards2.herokuapp.com/

## User Story  
  
+ A user can view posted projects and their details. 

- A user can post a project to be rated/reviewed. 

+ A user can rate/ review other users' projects.

- A user can search for projects.

+ A user can view projects overall score.

- A user can view their profile page.

+ A user can add a profile picture and Bio.

- A user can logout of their page.

  
## Setup and Installation  
To get the project.......  

##### Cloning the repository:  
 ```bash 
 https://github.com/Wairimu-3/Royal-awwards2.git
```
##### Navigate into the folder
 ```bash 
cd project-awwards
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual
- source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
##### Setup Database  
SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations
 ``` 
  Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  

 ### Api Endpoints
 * https://royalawwards2.herokuapp.com/api/users/

 * https://royalawwards2.herokuapp.com/api/posts/

## Technologies used  
  
* [Python3.8.5](https://www.python.org/)  
* [Django 2.2.6](https://docs.djangoproject.com/en/2.2/) 
* [Heroku](https://heroku.com)  
  
## Known Bugs
There are no known bugs in the application.Contact me incase you find any.

## Support and contact details
For any enquiries please contact me through:

+ Email: kimanimargaret46@gmail.com

## License
MIT license

https://choosealicense.com/licenses/mit/

&copy 2020; Margaret Kimani