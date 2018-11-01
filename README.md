# Android-Ransomware-app
#An Android Ransom ware app for educational purposes only
#The Following App Was Coded by pablo rotem
Ransomware
This project is use used for provide a RSA key for crypted data for any android smartophone. The api is used in a android application.

Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

API Python
Prerequisites
For use the project you must install python 3.X in your host or computer and lanch the command.

Installing
First you have to install the lib needed by the application

pip install -r requirements.txt
Launch the application
We can lanch the application in two mode :

Production
Development
Testing
Default (by default)
For launch the application :

python runserver.py
For launch with production environnment:

MODE=development python runserver.py
The keywords use in mode :

production
testing
production
default
Project strcuture
The project structre :

├── LICENSE.md
├── ransomware          # The flask application
│   ├── __init__.py
│   ├── config          # th folder contains the different config for each env
│   │   ├── __init__.py
│   │   └── config.py
│   ├── models.py       # The schema of the database
│   └── utils.py        # Some function use in the application
├── readme.md
├── requirements.txt
└── runserver.py        # Script for run the flask application
Built With
Flaks - The api framework use
Pony - The orm use
Pycryptodome - Used to generate RSA key
Sqlite - Database use
Doc Api :
Api doc
Android App
Built With
Butter Knife - Bind Android views and callbacks to fields and methods
google-gson - A Java serialization/deserialization library to convert Java Objects into JSON and back
Retrofit - Type-safe HTTP client for Android and Java
Screenshots
 

Authors
pablo rotem
