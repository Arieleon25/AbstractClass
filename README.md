# AbstractClass
The AbstractClass project is a console application that demonstrates the usage of abstract classes and inheritance in C#. It includes an abstract class called Person with two properties: firstName and lastName. The Person class also has a method called SayName(). The project also includes a Employee class that inherits from the Person class and implements the SayName() method. The Main() method of the console app instantiates an Employee object, initializes its properties, and calls the SayName() method to display the person's name.

# Project Description
The AbstractClass project consists of two classes: Person and Employee. The classes are defined in separate files.

Person.cs

This file contains the Person abstract class, which represents a person with a first name and a last name. The class has the following members:

Properties:

FirstName: Represents the first name of the person.

LastName: Represents the last name of the person.

Methods:

abstract void SayName(): An abstract method that should be implemented in derived classes. It provides a way to output the person's name.

Employee.cs

This file contains the Employee class, which inherits from the Person class. The Employee class provides an implementation for the SayName() method.

Program.cs

This file contains the Main() method, which serves as the entry point of the application. It instantiates an Employee object, initializes its properties with sample values, and calls the SayName() method to display the person's name.

# Instructions
Start the console application.

The program will create an instance of the Employee class.

The program will set the FirstName property of the employee to "Sample" and the LastName property to "Student".

The program will call the SayName() method on the employee object.

Observe that the person's name is displayed on the screen.

The program will terminate.

You can rerun the program to create new instances of the Employee class and test the functionality.

# Skills Demonstrated
This project demonstrates the following skills and concepts related to abstract classes and inheritance in C#:

Creating an abstract class

Defining properties and methods in an abstract class

Inheriting from an abstract class

Implementing abstract methods in derived classes

Instantiating objects and initializing properties

Calling methods on objects
