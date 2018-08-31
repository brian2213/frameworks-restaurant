**Author**: Lai Man Tang<br /><br />
**Github**: https://github.com/littlecloud1/frameworks-restaurant<br /><br />
**Date**: 8-20-2018<br /><br />

## Project
  This project aim to provide a user interface that user can create, read, update and delete restaurants and its menu.
  Also, user can eaily retreive data in 4 ways by using JSON.
  
  There are some new features is ongoing:
   * Oauth : implement google OAuth login method.


## Requirement
  * Python 3 version < 3.7 (cgi.parse_multipart does not work on 3.7)
  #### Python Lib
  * Flask
  * SQLAlchemy
  * OAuth2Client
  * Request
  
## Files
Inputfile:
  - **webserver-restaurant.py**: do_POST and do_GET function for restaurant CRUD 
  - **webserver-post.py**: return whatever user input
  - **database_setup.py**: Restaurant database sqlalchemy schema 
  - **lotsofmenu.py**: Restaurant database from Udacity, I modify it to python 3 version
  
## How To run:

#### To run the SPark server you will have to run below command on your terminal at project folder
``` bash 
# run the server
python SPark-server/manage.py runserver
``` 
The website will run in port 8080: <br/>
 localhost:8080/

