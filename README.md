# Project Description

This project is the first step towards building a full web application: an AirBnB clone. The main goal of this first step is to create a command interpreter to manage AirBnB objects. The command interpreter will be used to create, retrieve, update, and destroy objects. This project will also involve creating a parent class called BaseModel to handle the initialization, serialization, and deserialization of future instances. Additionally, all classes used for AirBnB, such as User, State, City, and Place, will be created, and the first abstracted storage engine of the project, File storage, will be implemented.

# Command Interpreter Description

The command interpreter is a tool that allows you to manage AirBnB objects through a command-line interface. It is similar to a shell but is limited to a specific use-case. With the command interpreter, you can:
- Create a new object (e.g., a new User or a new Place)
- Retrieve an object from a file, a database, etc.
- Perform operations on objects (e.g., count, compute stats, etc.)
- Update the attributes of an object
- Destroy an object

# How to Start the Command Interpreter
To start the command interpreter, navigate to the root directory of the project in your terminal and run the following command:
	'$console.py'
This will launch the command interpreter, and you will be able to start managing AirBnB objects.

# How to Use the Command Interpreter

The command interpreter supports several commands that allow you to manage AirBnB objects. Here are some examples of how to use the command interpreter:
- To create a new User, use the following command:
	'$ create User'
- To create a new Place, use the following command:
	'$ create Plale'
- To retrieve an object, use the following command:
	'$ show <class name> <id>'
For example, to retrieve a User with the id 123, use the following command:
	'$ show User 123'
- To update the attributes of an object, use the following command:
	'$ update <class name> <id> <attribute name> <attribute value>'
For example, to update the name of a User with the id 123, use the following command:
	'$ update User 123 name John Doe'
- To destroy an object, use the following command:
	'$ destroy <class name> <id>'
For example, to destroy a User with the id 123, use the following command:
	'$ destroy User 123'
