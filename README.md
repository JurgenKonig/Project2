# CSCI 315 Project2
Repository containing every file needed for CSCI 315 Project 2.  

10/26/2019: Uploaded directory before beginning work on Project 2 to serve as a backup. 
10/28/2019: First round of edits made to the project. Focus of this variation:
      1. Setting up Person Model and Controller
          - Person.php & PersonController.php
      2. Creating the 'persons' table within the assets DB
          - fName
          - lName
          - DOB
          - email
      3. Configuring views for PersonController
          - create.blade.php
          - edit.blade.php
          - index.blade.php
          - show.blade.php
      4. Establishing the Person model
          - Person.php
      5. Things to do for next round of coding:
          - Figure out migration issue to sync up DBMS with Laravel 
                a. No 'Created-At' and 'Updated-At' in table
          - Test DBMS to receive records given through create.blade.php
          - Start working on Owner model and Controller
                a. Owner.php, OwnerController.php
                b. Discuss views for Owners with Trinklein
                c. Set up Owners table within Asset DB
