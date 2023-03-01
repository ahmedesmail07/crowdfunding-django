CrowdFunding Web App Using Python "Django-FrameWork"

## About the Project:
In This CrowdFunding Web App we will allow users to :
- sign-up using addtional fields in model forms (Such as phone number with validation)
- sign-in using (email or username and password)
- reset their password if they forgot it
- they will login only if they activate thier email (Mail Activation Feature)
- Create and modify profile data (Adding Facebook Account,birth date & country)
- Create projects and donate for projects
- Admin Dashboard for only the staff and the super users without using django admin panel
- Delete his projects and also admin can delete it 
- Comment on projects 
- Report on projects or comments 
- Show projetcs details and rate projects
- All users can donate all projects and rate them 
- User can remove project in case the donation of the project less than 25% of the total

## Built With:
* [Django Framwork]
* [SQlite Database]
* [Java Script]
* [Html]
* [CSS]
* [Bootstarp]

## Installation
- Python 
- Pip  
	``` 
	(current == 4.1.1) pip install django 
	(in the future) python -m pip install --upgrade pip 
	```
- VirtualEnvironment
	```
	pip install virtualenv
	```
- Create and Activate VirtualEnvironment
	```
	virtualenv name(venv)
	```
	```
	Linux : source name/bin/activate       
	Windows : name(venv)/Scripts/activate
	```
- Install requirments
	```
	After setting up your vertualenv just use one command to install all this requirements using the following command :
	pip install -r requirements.txt

	
	```
	
- Run server in crowdfunding directory
	```
	python manage.py runserver
	```
- Don't Forget To Create A Super User 
	```
	python manage.py createsuperuser
	
	```
- Don't Forget To Change My Email & My Pass (2-Auth-KEY) 
- Note That gstmp feature causes some errors so be carefull while using it for prevent yourself from banned from google 
- Again please read about gstmp in google documentation


## DEMO : 



https://user-images.githubusercontent.com/93608128/192259742-6e9c0f5b-6e5c-4c18-9678-362554bd7d57.mp4

