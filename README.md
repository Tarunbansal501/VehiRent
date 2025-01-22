# VehiRent - Vehicle Renting System

VehiRent is a simple console-based application for a vehicle renting system. It offers users the ability to login, sign up, book rides, and rent cars. The system keeps track of available cars and calculates fares based on car type and travel distance.

 # Features

1.  Authentication System

Login: Allows existing users to log in to their accounts.

Signup: Enables new users to create an account.

Forgot Password: Helps users retrieve forgotten passwords.

2.  Ride Booking

Book a single ride from a source to a destination.

Choose from different types of cars: Micro, Mini, Sedan, SUV, and Luxury.

Calculates fare based on the type of car and distance traveled.

3.  Car Rental

Rent a car for a specified number of days.

Daily charges include a base fare and additional charges for kilometers driven.

Code Structure

# Functions

1.  login(): Handles user login.

2.  signup(): Registers a new user.

3.  forgot(): Helps users retrieve forgotten passwords.

4.  rideType(): Allows the user to choose between renting a car or booking a single ride.

5.  rentalCar(): Handles car rental bookings.

6.  book(): Manages single ride bookings.

7.  calculatefare(): Calculates the fare for the selected ride.

8.  display(): Displays available cars and their counts.

# Data Structures

1.  struct Car: Represents a car type with a name and count of available cars.

2.  vector cars: Stores the list of available car types.

