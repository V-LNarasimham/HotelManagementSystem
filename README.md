# HotelManagementSystem

## Overview  
This Java console-based application simulates a hotel room booking system with food ordering and checkout features.  
Users can book different types of rooms (luxury/double, deluxe/double, luxury/single, deluxe/single), check availability, place food orders, and checkout with a bill.

## Features  
- Room types:  
  - Luxury Double Room  
  - Deluxe Double Room  
  - Luxury Single Room  
  - Deluxe Single Room  
- Booking system with customer details  
- Food ordering menu integrated into room booking  
- Checkout with detailed bill (room charge + food charges)  
- Data persistence using Java Serialization (saving/restoring object state)  
- Custom exception handling for unavailable rooms  
- Simple console-based UI (menu-driven)  

## Technology Used  
- Java SE (core)  
- Object Oriented Concepts: inheritance, polymorphism  
- Arrays & ArrayList for storing room and food objects  
- Serializable interface for file persistence  
- Exception handling (custom exception)  
- Basic file I/O (ObjectInputStream / ObjectOutputStream)  
- Console I/O (Scanner)  

## How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/V-LNarasimham/HotelManagementSystem.git
   ```


## What I Learned
- Building a real-world console application from scratch.
- Applying Object Oriented Programming in a practical project.
- Creating custom exceptions for better error handling.
- Managing arrays and object collections.
- Using Java serialization for saving/restoring application state.
- Designing a menu-driven system.
- Writing clean, modular code using multiple classes.

## Future Enhancements
-Add GUI using JavaFX or Swing.
-Replace file serialization with MySQL database.
-Add admin dashboard (view all bookings, total earnings, food sales, etc.).
-Add room service, cancellation, and refund modules.
-Convert the whole project into a Spring Boot + React web app.
-Add logging and exception monitoring.

## Author
Velidi Lakshmi Narasimham
