# Vehicle-rental-system
## Vehicle Hire System (Systems Design and Development )

## The project Functionalities:
1. User registration and login: Users should be able to register on the platform 
using their accounts. Once registered, they should be able to log in to the 
platform using their credentials.
2. Car inventory management: The system should be able to manage the 
inventory of available cars. This includes adding new cars to the inventory, 
updating existing car details such as make, model, year, and price, and 
removing cars from the inventory.
3. Booking management: The system should allow users to book a car for a 
specific date and time. The user should be able to see the availability of cars and 
select the one they want to book.
4. User profile management: Users should be able to update their profile 
information such as name, email address, phone number, and password.
5. Booking cancellation: Users should be able to cancel their bookings if they 
need to.
6. Staff functionalities: The system should have an admin panel that allows the
administrator to manage the system. This includes adding new cars to the 
inventory, approving bookings, generating reports, and managing user accounts.

## Use case Diagram 
![image](https://github.com/Chandanchandums/Vehicle-rental-system/assets/93769506/4562ed9a-e46e-4b28-ad0b-2eeea0972b9d)

## Master class diagram
![image](https://github.com/Chandanchandums/Vehicle-rental-system/assets/93769506/d150ab09-f593-4040-96f1-9af27bfc9493)

## Architecture Pattern Used:
# Model-View-Controller (MVC) Pattern: 
● The Model-View-Controller (MVC) pattern is an architectural pattern 
commonly used in software development to separate an application into 
three interconnected components: the Model, the View, and the Controller. 
● The Model represents the application's data and business logic and is 
responsible for managing the data and responding to requests for data 
manipulation. 
● The View represents the user interface, which displays the data to the user 
and receives user input.
● The Controller acts as an intermediary between the Model and the View, 
handling user input, updating the Model and the View, and managing the 
flow of the application. 
● By separating the concerns of data management, user interface, and 
application logic, the MVC pattern can lead to more organized, 
maintainable, and scalable code.


## Design Principles:
# GRASP Principles:
- Creator: A class is responsible for creating new instances of other classes. 
- Controller: The Main Controller class for Course follows the Controller pattern 
by acting as a central point for handling incoming requests and delegating the 
necessary tasks to other classes.
- Low Coupling: Objects should minimize their dependencies on other objects.  
- High Cohesion: Objects should have a single, well-defined responsibility. Each 
Service class (StaffService, VehicleService) has methods that are related to the 
same responsibility.

## SOLID Principles:
- Single Responsibility Principle (SRP)
- Dependency Inversion Principle (DIP)
- Open/Closed Principle (OCP)

## Design Patterns Used:
- Singleton: The Singleton pattern ensures that only one instance of a class exists 
in the system
- Factory: The Factory pattern provides an interface for creating objects in a 
superclass, but allows subclasses to alter the type of objects that will be created. 
In a car rental system, the Factory pattern can be used to create different types of 
cars based on the customer's requirements or preferences. In our project we have 
created a CarFactory class can be created with a method that takes in a parameter 
specifying the car type required by the customer, such as "economy", "luxury", 
or "SUV". The CarFactory can then return an instance of the appropriate Car 
subclass based on the parameter.
- Facade: The Facade pattern provides a simplified interface to a complex system 
or set of classes. In a car rental system, the Facade pattern can be used to simplify 
the interaction between the client code and the different subsystems or modules 
of the system. In our Project,
The RentalSystemFacade class that has methods such as rentCar(), returnCar(), 
and processPayment(), which can handle the interactions with the different 
subsystems required to perform these actions. The client code can simply call 
these methods without having to interact with the individual subsystems directly.

## Features

1. Login Page
  ![javaw_0zChUORP90](https://user-images.githubusercontent.com/20018470/162602870-3c42dc51-863e-408b-85f6-ffaf7150601d.png)
  
2. Request car
  ![javaw_LkCwWCtQjw](https://user-images.githubusercontent.com/20018470/162602891-fa04285b-cfd6-40e6-b4fa-5de460203ff7.png)

3. Staff Account Registration Page
  ![javaw_lPzG9AJeaE](https://user-images.githubusercontent.com/20018470/162602893-ec25c8c7-9e46-4e39-8823-e276c0800740.png)
  
4. Display currently hired vehicle 
  ![javaw_mcoBYJ4XUy](https://user-images.githubusercontent.com/20018470/162602894-704956ee-92e6-4f60-9e71-4de64853b789.png)

5. Display vehicles for hire
  ![javaw_p66UCT8y2G](https://user-images.githubusercontent.com/20018470/162602895-45b054ec-e380-400d-948c-5eb873ff4ed7.png)

6. Adding a new car
  ![javaw_sZ7qA1DLfC](https://user-images.githubusercontent.com/20018470/162602900-4a8afd96-cadc-4032-907a-2392d37efd72.png)

7. List of customers
  ![javaw_pYOly9DG92](https://user-images.githubusercontent.com/20018470/162602897-3a0320d6-2d27-4920-8f08-cf17cd5db4ee.png)

8. Homepage
  ![javaw_tnyUUG2OYO](https://user-images.githubusercontent.com/20018470/162602901-93f866e6-fd31-4ecc-bc68-a1b5bcc2af85.png)

9. Add customer section
  ![javaw_u9niBjRFcD](https://user-images.githubusercontent.com/20018470/162602902-1871bf51-a6f4-4064-82ad-18263333d017.png)
