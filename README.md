To-Do list with user authentication.

config/ -> config folder with db instructions
public/ -> contains files visible to users
src/ -> source code of the application

Dependencies: composer, PHPMailer, Dotenv

Usage:
Since .env file is located in .gitignore, you should make one with following variables
-DB_USER => name of the owner of database
-DB_PASS => password of the owner
-DBC => mysql:host=<your hostname>;dbname=<your db name>;charset=UTF8
-GUSER => gmail account name
-GPASS => gmail account password

Fill out the form for registration with your credentials, email will be sent to email address given.
After clicking the link account is verified and you can log in from now on.


Todos can be removed after they are completed.
What is left, is to do some tests, add guest user, limit the number of users that can use one username and add screenshots, as well as make the site more pretty.
  
        ![Alt text](public/view/includes/login.png "Login page")
  
 
  ![Alt text](public/view/includes/todo_page.png "Login page")
