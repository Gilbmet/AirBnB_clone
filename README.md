AirBnB Clone

This is a command-line interface (CLI) project aimed at recreating basic functionalities of the popular online accommodation marketplace, AirBnB. The project implements a simplified version of AirBnB's backend, allowing users to create, manage, and interact with objects such as users, places, and bookings.
Command Interpreter

The command interpreter serves as the main interface for interacting with the AirBnB clone. It provides a command-line environment where users can enter commands to perform various actions on the objects within the system.
How to Start

To start the command interpreter, follow these steps:

    Clone the repository to your local machine:

    bash

git clone https://github.com/Gilbmet/AirBnB_clone.git

Change into the project directory:

bash

cd AirBnB_clone

Run the command interpreter:

bash

    ./console.py

How to Use

Once the command interpreter is running, you can enter various commands to interact with the system. The general format of a command is as follows:

css

command class_name [id] [attribute_name] [attribute_value]

Here, command refers to the action you want to perform, class_name specifies the type of object you want to manipulate, id (optional) is the unique identifier of the object, and attribute_name and attribute_value (optional) represent the attribute you want to modify and its new value, respectively.

The command interpreter supports the following actions:

    create: Creates a new object of the specified class.
    show: Displays the details of a specific object.
    destroy: Deletes an object from the system.
    all: Displays all objects of a specific class or all objects if no class is provided.
    update: Modifies the attributes of an object.

Examples

Here are some examples of how to use the command interpreter:

    Create a new user:

    sql

(hbnb) create User

Show details of a user with ID "123":

sql

(hbnb) show User 123

Delete a place with ID "456":

scss

(hbnb) destroy Place 456

Display all objects of the Review class:

scss

(hbnb) all Review

Update the name attribute of a user with ID "789":

sql

    (hbnb) update User 789 name "John Doe"

For a complete list of commands and their usage, you can use the help command within the interpreter.

Authors
Gilbmet <gilbmet254@gmail.com>
