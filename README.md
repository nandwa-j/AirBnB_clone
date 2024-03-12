AirBnB Clone License: MIT Build Status
HBnB Logo

Project description
This is the first phase of a four phase project, to create a basic clone of the AirBnB web app. In this first phase a basic console was created using the Cmd Python module, to manage the objects of the whole project, being able to implement the methods create, show, update, all, and destroy to the existing classes and subclasses.

Environment
The console was developed in Ubuntu 20.04LTS using python version 3.4.3

Command interpreter
It will be used to manage the Airbnb objects as everything within this project will be used with all the other following projects and each task is linked.
The command interpreter is the same as the shell but it is limited to a specific use-case. In our case we want it to manage the objects of our project which inludes creating a new object ex: a new User or a new Place, retrieving an object from a file, a database etc,doing operations on objects (count, compute stats, etc…), updating attributes of an object and finally destroying an object
It should be able to work both in the interactive mode and non interactive mode as shown below
In interactive mode:

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
In non-interactive mode: (like the Shell project in C)

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


Installation 
Clone the repository and run the console.py

$ git clone https://github.com/nandwa-j/AirBnB_clone.git

Authors 
Nandwa Japheth
