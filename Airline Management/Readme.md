<h2><b>Airline Managment System using Data Structures and Algorithms</b></h2>


This C++ program is a Travel Management System that helps users find the most cost-effective flight routes between cities. It incorporates the Bellman-Ford algorithm for efficient cost calculations and provides functionalities such as user authentication, city information display, and ticket booking.

<b>Functionalities: </b>

1. Shows a list of all the cities serviced by airline in a tabular form.
2. Show a list of flight departures for a city, sorted by the time of departure.
3. Shows a list of flight arrivals for a city, sorted by the time of arrival.
4. Shows a list of all the cities which can be reached from a particular city.
5. Shows the list of cities in the shortest path between any two cities.
6. Makes an airline reservation for a passenger between two cities.
7. Prints a passenger's reservation schedule.
8. Deletes a passenger's reservation.
9. Prints a list of passengers of a particular flight (in order of last name).

<b>Data Structures:</b> 
1) Array: Used to store city names and user input data.


2) Struct:

     a) Store: Struct to store cost and array information for each city. <br></br>
     b) initialdata: Struct to store initial cost information for each city.

3) Classes:

     a) datamodule: Class to manage city-related data and initialize city names.<br></br>
     b) bellmanfordalgorithm: Class implementing the Bellman-Ford algorithm for cost calculations.<br></br>
     c) filehandlingmodule: Class for handling file operations, specifically for user authentication and ticket creation.<br></br>
     d) inputmodule: Class for user input related operations.<br></br>
     e) outputmodule: Class for displaying output and managing the ticket booking process.

<b>Algorithms: </b>

<b>Bellman-Ford Algorithm:</b>

Used in the bellmanfordalgorithm class for finding the minimum cost path between any two cities.

<b>File Handling:</b>

File operations are used for user authentication (filehandlingmodule class) and ticket creation.

<b>User Authentication:</b>

A simple form of user authentication is implemented using file handling to check the validity of the entered username and password.

<b>Input Handling:</b>

User input is handled using the inputmodule class to obtain details like source, destination, username, and password.

<b>Output Display:</b>

The outputmodule class is responsible for displaying information such as the list of cities, ticket details, and passenger information.

<h2><b>Miscellaneous:</b></h2>

<b>Preprocessor Directives:</b>

Used for including header files, defining constants (#define infinity), and simplifying code.

<b>Standard Template Library (STL):</b>

Utilizes the iostream, cstring, fstream, and vector headers for various functionalities.

<b>Dynamic Memory Allocation:</b>

Dynamic memory is not explicitly used in the provided code.

<b>Control Structures:</b>

Implements if, else, for, while, and switch control structures for flow control.

<b>Object-Oriented Programming (OOP) Concepts:</b>

Classes and objects are used to structure the code in an object-oriented manner.
