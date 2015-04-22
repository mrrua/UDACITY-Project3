# UDACITY-Project3
Restaurant Menu App w/ OAUTH README
Version: 1.0
Date: 04/15/2015
Created By: Adam Rua

CONTENTS OF THIS FILE:
-------------------------------------
 * Introduction
 * Requirements
 * Installation of Python
 * How to run the Python Project script

INTRODUCTION
-------------------------------------
 This README is for use with Project 1 of UDACITY Full Stack Web Developer Nanodegree and will show the reader how to install Python if needed, as well as how to download, unzip, and run the Python script for Project 1.

REQUIREMENTS
-------------------------------------
 A. You will need Python installed (instructions for its installation can be found below). 
 B. You will need Werkzeug installed (v0.8.3).
 C. You will need Flask installed (v0.9).
 D. You will need Flask Login installed (v0.1.3).
 
 Note: If running this on the UDACITY class provided Vagrant instance, you will need to downgrade manually to avoid the error: "raise TypeError(repr(o) + " is not JSON serializable") TypeError: <oauth2client.client.OAuth2Credentials object at 0xb57ea42c> is not JSON serializable"
 
INSTALLATION OF PYTHON
-------------------------------------
 We will be using Python v2.7.9 for this Project so please ensure you have it installed. If you already do - you can skip this step. If you are not sure, or want to reinstall please continue.
 
 1. Navigate to the Python webpage via your browser. The link is: http://python.org/downloads
 2. Select Python v2.7.9 and click to download whichever version you'd like (specifically around 32 vs 64 bit options due to your preference / machine). 
 3. After download is complete - launch the installer.
 4. During the wizard ensure you select ALL options to be installed (including adding Python to PATH).
 5. You're all set installing Python.
 
HOW TO RUN THE PYTHON PROJECT SCRIPT
-------------------------------------
 Now that you have Python running on your machine. Let continue by running our Project!
 
 1. Download all files related to the project and delopy them to whatever location you'd like. Keep in mind the folder structure should be kept intact for code references to work.
 2. The DB file has used for testing the application has been included, but incase you'd like to create your own:
    a. Delete "restaurantmenuwithusers.db"
    b. Run the python program: database_setup.py - this will create the database for you.
    c. Run the python program: lotsofmenus.py - this will load the database with data so you don't have to do it manually.
    d. You now have a recreated: db file named: restaurantmenuwithusers.db
 3. Now run the python program: finalproject.py - your browser will now load and you can navigate through the webpage for testing!
 
EDITING THE CODE FOR YOUR OWN USE
-------------------------------------
 Now that you have the code running, if there is anything you'd like to change you can simply access that part of the application and edit it.

 A. For visuals, feel free to edit HTML directly in the TEMPLATES folder, or CSS in the STATIC folder. 
 B. All code structure, and CRUD features can be edited in the FINALPROJECT.py file.
 C. Any changes to the DB would occur in the database_setup.py file, and references would have to be edited in the FINALPROJECT.py file to ensure proper accessing/function is kept intact.

 
 
