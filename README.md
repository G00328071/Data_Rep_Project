#Single-page Web Application Project

![Home Screen](screenShots/Screenshot_1.png)

#Data Representation and Querying 3rd year Project 2016

This repository contains code and information for our third-year undergraduate project for the module, Data Representation, and Querying.
The module is taught to undergraduate students at GMIT in the Department of Computer Science and Applied Physics.

Project Overview

We have created a Single-Page Web Application (SPA) that lets a user, register and login to a blog site. Each registered user can view other user's posts
or if they wish create new posts of their own. The Initial brainstorming sessions, resulted in a project idea that had to be simplistic in design and build, but still met the 
requirements laid out in the project instructions.


#Extract from project instructions
You are required to develop a single-page web application(SPA) written in the programming language Python using the Flask framework.
You must devise an idea for a web application, write the software, write documentation explaining how the application works, and write a short user guide for it.



 The concept of a blog site as the project was highly influenced by the fact that in semester 3, a course module (IT Professional Skills) 
required us to start and maintain a blog for the duration of that semester.    
 

#Team Members

In order to try duplicate a real-life work environment, we decided to complete this project as a team.
Four members, which formed the original core group, were queried as to their participation in the team.
Two decided to pursue individual projects instead, leaving two of a team.

1. Alexander Souza - G00317835@GMIT.IE

2. Alan Doyle - G00328071@GMIT.IE


#Team Meetings

Meetings were held on an ongoing basis and nearly every day in the GMIT canteen over dinner/coffee, discussions regarding
any problems encountered were discussed, and possible solutions found from the net and shared.
One such problem was the choice of database to use.  As part of this course interactions with couchbd were taught. The couch database proved problematic.
The decision to change to mongo came about from sheer research into the suitability and supporting 
documentation/tutorials on the net.
 
#How to run the application 

####Method one:

The application has been deployed to the net, and can be accessed at the following  http://alexpt2000.pythonanywhere.com/
There is no need to install the database as this is also hosted on mLab.


####Method two:

Run on your own local pc.

The application utilises Python, Flask(Jinja2), MongoDB, Bootstrap.


These can be installed simply, by installing Anaconda from the following  https://www.continuum.io/downloads
and follow the simple download/install instructions.

Flask documentation and information available from, http://flask.pocoo.org/

  

You will also need to install a mongo database Download instructions from the following  https://www.mongodb.com/download-center#community
This can be problematic especially for the Windows OS.
We found that installing Ampps was a much easier process and did the same job. http://www.ampps.com/downloads

All links above are to the downloads pages, these download procedures are subject to, and  often do change. Therefore, it wouldn't be practical to detail
the download /install processes here. 


Once the application is running, it can be accessed by pointing your browser at http://127.0.0.1:4990/.

or the port which has been set in the following code snippet on the bottom of the app.py page

```python
if __name__ == '__main__':
 app.run(port=4990, debug=True)
```

#References:  
http://flask.pocoo.org/docs/0.11/quickstart/

http://stackoverflow.com/

https://www.python.org/doc/

https://www.youtube.com/


#Template:

https://startbootstrap.com/template-overviews/clean-blog/


##Home Screen:
![Home Screen](screenShots/Screenshot_1.png)

##Login
![Login](screenShots/Screenshot_2.png)

##Sign up
![Sign up](screenShots/Screenshot_3.png)

##Create Post
![Create Post](screenShots/Screenshot_4.png)

##Post Form
![Post form](screenShots/Screenshot_5.png)

##Mobile responsive page
![Responsive page](screenShots/Screenshot_6.png)





















