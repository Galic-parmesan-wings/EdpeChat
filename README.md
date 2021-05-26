
# EdpeChat
## Overviews
A **Python Flask-based** Twitter-clone social media web application </br>
### [Full Demo](https://edpegg.herokuapp.com/) </br>
> Loading will take a while

![full-demo](/screenshots/full-demo.png)
</br>
## Getting Started
### Prerequisite

 - [Python](https://www.python.org/downloads/)<br />
	Python 3.7 or above needed <br />
	To check the version installed, open a terminal window and entering the following:
	``python --version``
 - SQLite <br />
	 [How To Download & Install SQLite Tools](How%20To%20Download%20&%20Install%20SQLite%20Tools)
### Dependencies
	
 - Site-packages are already included in the folder "EdpeChat\venv\Lib\site-packages"
 > Alternatively, open a terminal cd EdpeChat project directory, run  ``pip install > requirements.txt`` to install dependencies manually
 
### Environment Setup
 - Activate Python virtual environment
 Open a terminal cd EdpeChat project directory, run
  ``$ source venv/bin/activate``<br />
 If it works, you should see the prompt command like
 ``(venv)$_`` 
 > Note: If you are using a Microsoft Windows command prompt window, the activation command is slightly different: </br>
 > ``venv\Scripts\activate``<br />
 > ``(venv) C:\EdpeChat>``

### Run it!

 - Set ``FLASK_APP`` enviroment variable: </br>
 ``(venv) $ export FLASK_APP=runMyBlog.py``
 > Note:  If you are using a Microsoft Windows command prompt window, use `set` instead of `export`: </br>
 > `(venv) $ set FLASK_APP=runMyBlog.py`
 - Run the app: </br>
 `(venv) $ flask run`
 -  It should then be running on  [http://127.0.0.1:5000/](http://127.0.0.1:5000/)  (Press CTRL+C to quit)

	 
## Funtionalies
 - Sign up
	 - Client-side validations
		 - Username must be at least four characters 
		 - Email address must be in correct format
		 - Password must be at least four characters
		 - Confirm password must match
	 - Server-side validations
		 - Username must be unique
		 - Email address must be unique
 - Login
	 - Login failure triggers error message "Invalid Password or Username"
	 - Password reset - Automated email sending
 - Profile-Managing
	 - User info Editing
		 - Avatar
		 - Username
		 - Email Address
		 - About me
	- Followings and followers
		- unfollow 
		- follow back
 - Post
	 - Create
		 - Title 
		 - content
			 - Emoji
			 - Picture
	 - Delete
	 
 - Comment & Reply   
	 - Like ![like-icon](https://img.icons8.com/material-sharp/24/000000/facebook-like--v1.png%22)
	 - Comment
	 - Reply
 - Messaging
	 - Send
	 - Receive
		 - Notification
		 - Read
 - Search
 
## Demo

