                          // Flask //

              web development, one drop at a time
              
  Novice Introduction:
  
If you're new to web development, and specifically looking at python as your language of choice, check out flask.  Even if you are a complete noob learning python, once you grasp some of the python basics, flask can make it easy for you to get up and running on creating web content in python much quicker than if you were just using python by itself.

Although it is possible to jump right into flask and go through some tutorials to create web apps right away, having a basic grasp of the following concepts will speed up your learning curve, as it will create a mental foundation for understanding flask: 

Framework - A framework is basically a set of software tools that take care of common tasks necessary for the development of web applications or sites. These common tasks include accessing databases, managing sessions, creating displays of HTML and using templating, which is a way of dissassociating the underlying template that will present the data from the actual data. A basic tenet for using a framework is to promote the efficient writing of code and avoiding repetition. The complexity of a framework is proportional to the number of tools or libraries that it offers.

Microframework - A microframework is a framework that has a minimal number of libraries or tools, leaving you the option to use python libraries that are already available elsewhere. This is what is meant by the Flask documentation when it says that it is "extensible". This actually makes it easier to get started using it, as you can incorporate different tools only as they are needed.

Jinja2 - Jinja2 is a template engine for Python. This library allows for different data to populate common templates through the use of programming logic.  Think of templating as a way to change the content of a web page or html element within a page while keeping the template or area where the changes occur constant, as for example news sites that change the latest stories when you visit them at different times of day. Check out these Jinja examples:

https://realpython.com/blog/python/primer-on-jinja-templating. 

Werkzeug - Werkzeug is a set of utilities for applications that communicate through an interface specification called WSGI (Web Server Gateway Interface), which as stated in the werkzeug documentation, "WSGI itself is a protocol or convetion that ensures that your web applicationcan speak with the webserver and more importantly that web applications work nicely together." The werkzeug tutorial can get you up and running on werkzeug, the link is this: http://werkzeug.pocoo.org/docs/0.11/tutorial/#introducint-shortly 

If you look at the documentation for werkzeug and jinja2 you can get to some pretty simple tutorials that can get you started. Then do a wider search for tutorial videos on Flask and you'll see some presentations of the capabilities of flask and get a feel for its potential. Some of the best tutorials I've found are by miguel grinberg, you can go to his site and look for some of his video tutorials on youtube, his blog is: http://blog.miguelgrinberg.com. 




    ~ What is Flask?

      Flask is a microframework for Python based on Werkzeug
      and Jinja2.  It's intended for getting started very quickly
      and was developed with best intentions in mind.

    ~ Is it ready?

      It's still not 1.0 but it's shaping up nicely and is
      already widely used.  Consider the API to slightly
      improve over time but we don't plan on breaking it.

    ~ What do I need?

      All dependencies are installed by using `pip install Flask`.
      We encourage you to use a virtualenv. Check the docs for
      complete installation and usage instructions.

    ~ Where are the docs?

      Go to http://flask.pocoo.org/docs/ for a prebuilt version
      of the current documentation.  Otherwise build them yourself
      from the sphinx sources in the docs folder.

    ~ Where are the tests?

      Good that you're asking.  The tests are in the
      tests/ folder.  To run the tests use the
      `py.test` testing tool:

        $ py.test

    ~ Where can I get help?

      Either use the #pocoo IRC channel on irc.freenode.net or
      ask on the mailinglist: http://flask.pocoo.org/mailinglist/

      See http://flask.pocoo.org/community/ for more resources.


