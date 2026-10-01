##  ## ##  ## ## #####  ###### ###### ##  ##
##  ## ### ## ## ##  ## ##  ## ##     ## ##
##  ## ###### ## #####  ###### ##     ####
##  ## ## ### ## ##  ## ##  ## ##     ## ##
###### ##  ## ## #####  ##  ## ###### ##  ##



######################################
###                                ###
###       How to use UniBack?      ###
###                                ###
######################################

1. Requirements:
    To get started, please install JavaScript on your machine. You also need a tool that allows you to use PHP and SQL.
    We recommend — and will use as an example — XAMPP, a software package that allows you to set up a local web server.
    The XAMPP tools required are Apache and MySQL.


2. Setting up the database:
    Once everything is installed, start Apache and MySQL, then enter "localhost/phpmyadmin" in your browser's address bar.
    In the left-hand tab, click on "New".
    A new "Create database" section should appear.
    Enter "bddres" in the "Database name" field and click the "Create" button.
    The database should be empty. Drag the SQL file provided in the project folder, "bddres.sql", into it.

    There is only one step left to set up the database.
    On the same screen, you should find a list of clickable tabs at the top.
    Click on "Privileges", then add a user account (at the bottom), and enter the following respectively:
        - testadmin
        - localhost
        - 123
        - 123

    Leave the other fields empty, then check all options under "Global privileges".
    Finally, click "Execute".

    Congratulations, the database is now operational!


3. Launching the website:
    To access the website, enter "localhost/uniBack" in your browser.
    Create your account and you are ready to discover UniBack!


4. Admin mode:
    To test the admin mode, everything has already been prepared for you!
    To do so, go to the login page.
        -> You must log out first if you are currently logged in.

    Finally, log in using the following account:
        - Username: root
        - Password: admin
