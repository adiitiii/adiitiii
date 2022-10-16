# Wommanly 
#### Video Demo:  [(https://youtu.be/tCDzU9SEUYE)
#### Description:
Wommanly is a solution to the major root cause problem prevailing in our society today i.e. RAPE and is encountered by 8 out of 10 persons everyday on an average. Wo-manly is an organization which helps people in times of emergency.

Motive behind this idea is to give assistance to all the persons whenever any situation is about to befall upon them such as sexual assault, violation, molestation, criminal assault, and seduce which is very common these days and is increasing at an alarmimg rate.
**Vision** is to make this society a better place to live in where any person of any gender can freely rome at any pl
**Mission** is to filter out people who makes our society filthy by doing such kind of things that we are all shame on.

The one thing that motivated me for the formation of this organization is the increasing filthiness of evil minded people in our society, irrelevant of gender. The kind of things that mankind is doing are unbelievable and shocking to the core.
The amount of suffering the victim has to face after such kind of practice is just immeasurable. Post-traumatic stress disorder (PTSD), including flashbacks, nightmares and severe anxiety are just some of the examples that victims go through.

The functionings are defined in the video, lets discuss about the code.

To implement this idea, I have created a website that uses HTML, CSS, Python, Javascript and Flask. My code Contains the following directories:
1. Static 
Static directory contains all the images and .css files.
2. Templates
Templates directory includes all the templated html files that are being rendered in my code like apology.html, login.html, index.html, layout.html, etc.
3. Flask_session
It basically contains the flask session.

Except for these, "Final Project" has:
1. app.py 
***In app.py, I have imported all the important flask related session needed to implement the code and it contains 4 routes :
the root route, login route, logout route and the register route. When the flask session runs, user gets directed to the login page, if not created any account, they first have to register themselves with us and then by logging in, their information will be sent to the database in the backend server, afterwards which index page loads, giving out our website information.***

2.helpers.py
All the helping functions are defined in this file. Apology is a fn() that renders apology followed by a grumpy cat whenever user fails to give in some basic input as mentioned. The second fn() is the login_required which defines that for some particular route, when user is logged in, only then they will be able to see the further data.

3. requirements.txt
Consists of all the required files while running flask.

4. womanly.db
This is the database which all the user information is being stored.

