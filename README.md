📦 AirBnB Clone – Console Module
This project is the first phase of building a functional clone of the AirBnB platform. It focuses on developing a command-line interface that can be used to create, manage, and manipulate various types of data models.

🔧 Project Overview
Over the course of four months, the entire system will evolve into a complete web application consisting of:

A console-based interface for managing app data without needing a graphical UI — great for development and testing.

A user-facing front-end, both static and interactive.

A storage mechanism (file system or database) to preserve created data.

A RESTful API to handle communication between the front-end and the stored data.

For this stage, we are concentrating only on the console component, which serves as a development and administrative tool.

🖥️ The Command Line Console
The console mimics basic shell behavior but is tailored to interact specifically with objects in the AirBnB clone. It allows users to perform operations on the data models through typed commands.

🛠️ Supported Functionalities
You can interact with the system using several predefined commands, enabling you to:

Instantiate new objects (e.g., a new user or property listing).

Retrieve information about existing objects.

Modify object attributes.

Count or list all instances of a class.

Delete objects from storage.

Exit the interpreter safely.

📘 Command Syntax Guide
Here’s a reference table describing the main commands available:

Command	Description	Usage Example
help	Displays help information for commands	(hbnb) help or (hbnb) help create
quit	Exits the interpreter cleanly	(hbnb) quit
EOF	Ends the session (Ctrl+D alternative)	(hbnb) EOF
create	Instantiates a new object of a specified class	(hbnb) create User
show	Shows string representation of a given object	(hbnb) show Place 1234-5678-9012
destroy	Deletes an object based on class name and ID	(hbnb) destroy User 1234-5678-9012
all	Lists all instances, optionally filtered by class	(hbnb) all or (hbnb) all User
update	Updates an object’s attributes using its ID and the new values provided	(hbnb) update User 1234-5678 name "Alice"

🧠 Project Goals
This initial component lays the foundation for:

Object creation and manipulation from the terminal.

Persistent storage of app data using either files (via serialization) or databases.

A clear structure for future modules like the API and web interface.

