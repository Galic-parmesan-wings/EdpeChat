
# EdpeChat
## Overviews
A **Python Flask-based** Twitter-clone social media web application </br>
### [Full Demo](https://edpegg.herokuapp.com/) </br>
> Loading may need to take a while

![full-demo](/screenshots/full-demo.png)
</br>
## Getting Started
### Prerequisite

 - [Python](https://www.python.org/downloads/)<br />
	Python 3.7 or above needed <br />
	To check the version installed, open a terminal window and entering the following: <br />
	``python --version``
 - SQLite <br />
	 [How To Download & Install SQLite Tools](How%20To%20Download%20&%20Install%20SQLite%20Tools)
### Dependencies
	
 - Site-packages are already included in the folder "EdpeChat\venv\Lib\site-packages"
 > Alternatively, open a terminal cd EdpeChat project directory, run  ``pip install -r requirements.txt`` to install dependencies manually
 
### Environment Setup
 - Activate Python virtual environment <br />
 Open a terminal cd EdpeChat project directory, run
  ``$ source venv/bin/activate``<br />
 If it works, you should see the prompt command like
 ``(venv)$_`` 
 > Note: If you are using a Microsoft Windows command prompt window, the activation command is slightly different: </br>
 > ``C:\EdpeChat> venv\Scripts\activate``<br />
 > ``(venv) C:\EdpeChat>``
 
 - Set ``FLASK_APP`` enviroment variable: </br>
 ``(venv) $ export FLASK_APP=runMyBlog.py``
 > Note:  If you are using a Microsoft Windows command prompt window, use `set` instead of `export`: </br>
 > `(venv) C:\EdpeChat> set FLASK_APP=runMyBlog.py`

### Run it!
 - Run the app: </br>
 `(venv) $ flask run`
 -  It should then be running on  [http://127.0.0.1:5000/](http://127.0.0.1:5000/)  (Press CTRL+C to quit)

	 
## Funtionalies
 - Sign up <sup>[see demo](#myfootnote1)</sup>
	 - Client-side validations
		 - Username must be at least four characters 
		 - Email address must be in correct format
		 - Password must be at least four characters
		 - Confirm password must match
	 - Server-side validations
		 - Username must be unique
		 - Email address must be unique
 - Login <sup>[see demo](#myfootnote2)</sup>
	 - Login failure triggers error message "Invalid Password or Username"
	 - Password reset - Automated email sending <sup>[see demo](#myfootnote9)</sup>
 - Profile-Managing
	 - User info Editing <sup>[see demo](#myfootnote3)</sup>
		 - Avatar
		 - Username
		 - Email Address
		 - About me
	- Followings and followers <sup>[see demo](#myfootnote4)</sup>
		- unfollow 
		- follow back
 - Post <sup>[see demo](#myfootnote5)</sup>
	 - Create
		 - Title 
		 - content
			 - Emoji
			 - Picture
	 - Delete
	 
 - Comment & Reply <sup>[see demo](#myfootnote6)</sup>   
	 - Like ![like-icon](https://img.icons8.com/material-sharp/24/000000/facebook-like--v1.png%22)
	 - Comment
	 - Reply
 - Messaging <sup>[see demo](#myfootnote7)</sup>
	 - Send
	 - Receive
		 - Notification
		 - Read
 - Search <sup>[see demo](#myfootnote8)</sup>
 
## Demo
- <a name="myfootnote1">Sign up demo: </a>
<br></br>
![SignUp-demo](/screenshots/SignUp.gif)
- <a name="myfootnote2">Login demo: </a>
<br></br>
![Login-demo](/screenshots/Login.gif)
- <a name="myfootnote3">Profile-creating demo: </a>
<br></br>
![SignUp-demo](/screenshots/Profile-creating.gif)
- <a name="myfootnote4">Follow & Unfollow demo: </a>
<br></br>
![SignUp-demo](/screenshots/Following1.gif)
- <a name="myfootnote5">Post-creating demo: </a>
<br></br>
![SignUp-demo](/screenshots/Post.gif)
- <a name="myfootnote6">Comment & reply demo: </a>
<br></br>
![SignUp-demo](/screenshots/Comment2.gif)
- <a name="myfootnote7">Message send & receive demo: </a>
<br></br>
![SignUp-demo](/screenshots/Messaging.gif)
- <a name="myfootnote8">Search demo: </a>
<br></br>
![SignUp-demo](/screenshots/Search.gif)
- <a name="myfootnote9">Password reset demo: </a>
<br></br>
![SignUp-demo](/screenshots/Password-reset.gif)
