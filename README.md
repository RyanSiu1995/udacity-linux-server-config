# Udacity - Linux Server Setting Up Exercise
## Introduction
This is an exercise to set up the basic linux web
server with Amazon lightsail. The basic Apache server
is set with serving python web application.
## Summary of the web server
Here are the details of the web server.
* IP Address -  13.112.126.7
* URL - http://13.112.126.7/
* Software/Packages installed
	* apache2
	* python-pip
	* libapache2-mod-wsgi
	* postgresql
* Configurations
	* Basic Setting
		* Firewall for port 80, 2200 and 123
		* Public-key Authentication (The private key udacity 
		is getting along in the repo)
		* Restrict ssh with Public-key Authentication only
		* Suoder setting up
	* apache2
		* Setting up WSGI application in 
		/var/www/html
		* Listen the apache HTTP server in port 80
	* Postgresql
		* Grant the user catalog with CRUD operation only
		* Block the port opening to public
		* Prohabit the user from connecting through md5
* Third-party resources
	* Python Libraries
		* Flask
		* SQLAlchemy
		* httplib2