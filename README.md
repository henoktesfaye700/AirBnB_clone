AirBnB_clone Project

This is the first section of the AirBnB clone project, where we worked on the project's backend and used the Python cmd module to interface it with a console application.

The created data (python objects) are kept in a json file and are accessible through the use of the Python json module.

Command Interpeter Descripion

The application's interface is similar to that of the Bash shell, with the exception that it only accepts a small set of commands that are specifically defined for use with the AirBnB website.

The web application's interface, which allows users to interact with the backend created using Python OOP programming, is this command line interpreter.

Among the available commands are:

#show
#create
#update
#destroy
#count

The following tasks can be carried out as part of the implementation of the backend, file storage system, and command line interpreter

##Creating new objects (ex: a new User or a new Place)
##Retrieving an object from a file, a database etc…
##Doing operations on objects (count, compute stats, etc…)
##Updating attributes of an object
##Destroying an object

How to start it
You can use these procedures to get a local Linux distribution copy of the project up and running for testing and development.

Installing 

It is necessary for you to clone the project's Github repository. The basic shell program and all of its dependencies will be contained in here.
Once the repository has been cloned, you will have a folder named AirBnB_clone. Several files that are necessary for the program to function will be found here.

How to use it 

It can perform in two different modes:

Interactive and Non-interactive.


The console will show a prompt (hbnb) in interactive mode, letting the user write and run commands. The prompt to wait for a new command will reappear after the command has been executed. This can continue as long as the user doesn't close the application.

To execute a command as soon as the shell launches in non-interactive mode, a command input must be piped into the shell's execution. There won't be a prompt in this mode, and the user won't be asked for any more input.

Format of command input

In the event that the mode is not interactive, commands must be piped through an echo in order to be sent to the console.

When the prompt appears in Interactive Mode, the commands must be typed on a keyboard. They are recognized when the enter key is pressed (new line). When this occurs, the console will try to run the command multiple times or, in the event that it is unsuccessful, will display an error message. The CTRL + D combination, CTRL + C, quit, and EOF commands can all be used to exit the console in this mode.

Argumets

When executing a program, most commands offer a number of options or arguments that can be selected. The user needs to sever everything with spaces so that the Shell can identify those parameters.
