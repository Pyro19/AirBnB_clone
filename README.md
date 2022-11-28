# AirBnB_clone
AirBnB_clone project
![image](https://user-images.githubusercontent.com/106750453/204345014-38ee6b13-4c99-42c4-a3b6-1b0116b22d75.png)

# Description of the project

This is my first step towards building my first full web application: the AirBnB clone. This first step is very important because i will use 
what i build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration… 

# Description of the command interpreter: 

The first piece is to manipulate a powerful storage system. This storage engine will give us an abstraction between “My object” and “How they 
are stored and persisted”. This means: from my console code (the command interpreter itself) and from the front-end and RestAPI i will build 
later, i won’t have to pay attention (take care) of how your objects are stored.

And as part of the implementation of the command line interpreter coupled with the backend and file storage system, the folowing actions can be
performed:

    Creating new objects (ex: a new User or a new Place)
    Retrieving an object from a file, a database etc…
    Doing operations on objects (count, compute stats, etc…)
    Updating attributes of an object
    Destroying an object

# How to start it:

In order to start the console, you must use the following command: ./console.py

# How to use it:


    manage (create, update, destroy, etc) objects via a console / command interprete
    store and persist objects to a file (JSON file)
    Commands: create, show, destroy, all (shows all), update, help, quit

# Examples:

    # 1. interactive mode:

            $ ./console.py
            (hbnb) help
            Documented commands (type help <topic>):
            ========================================
            EOF  help  quit

            (hbnb) 
            (hbnb) 
            (hbnb) quit
            $

    # 2. non-intaractive mode:
            $ echo "help" | ./console.py
            (hbnb)
            Documented commands (type help <topic>):
            ========================================
            EOF  help  quit
            (hbnb) 
            $
            $ cat test_help
            help
            $
            $ cat test_help | ./console.py
            (hbnb)
            Documented commands (type help <topic>):
            ========================================
            EOF  help  quit
            (hbnb) 
            $













