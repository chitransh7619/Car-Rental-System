# Car Pool Management System

## Overview

The **Car Pool Management System** is a robust and user-friendly application developed using C++ and the Qt framework. This application is designed to streamline the process of car pooling, offering users an intuitive interface for logging in, signing up, finding rides, reserving cars, and managing rides. It also includes administrative functionalities for managing user profiles and system settings.

## Features

- **User Authentication**: Secure login and registration system to ensure user data privacy and integrity.
- **Find and Reserve Rides**: Users can search for available car pools and reserve a seat with ease.
- **Create Rides**: Enables users to offer rides, specifying details such as destination, time, and available seats.
- **Profile Management**: Allows users to update their profile information seamlessly.
- **Administrative Controls**: Comprehensive admin panel to oversee and manage the entire car pool system.

## Project Structure

### Source Files

- `log_in.cpp`: Handles user login functionalities.
- `Sign_In.cpp`: Manages user registration and sign-up processes.
- `clickableLabel.cpp`: Custom QLabel implementation to enhance interactivity.
- `updateProfile.cpp`: Facilitates user profile updates.
- `MainScreen.cpp`: The main dashboard where users can access primary features.
- `findRidePage.cpp`: Interface for finding and reserving car pool rides.
- `reserveCar.cpp`: Manages car reservation functionalities.
- `createRide.cpp`: Allows users to create new car pool rides.
- `adminstrator.cpp`: Administrative interface for system management.

### Header Files

- `log_in.h`
- `Sign_In.h`
- `clickableLabel.h`
- `updateProfile.h`
- `findRidePage.h`
- `mainScreen.h`
- `reserveCar.h`
- `createRide.h`
- `adminstrator.h`

### UI Files

- `log_in.ui`: Login interface design.
- `Sign_In.ui`: Sign-up interface design.
- `mainScreen.ui`: Main dashboard design.
- `updateProfile.ui`: User profile update interface.
- `findRidePage.ui`: Interface for finding rides.
- `reserveCar.ui`: Car reservation interface.
- `createRide.ui`: Ride creation interface.
- `adminstrator.ui`: Admin panel interface.

### Resources

- `images.qrc`: Resource file containing images and other assets.

## Getting Started

### Prerequisites

- Qt 5 or higher
- C++ compiler (e.g., GCC, MSVC)
- Qt Creator or Visual Studio Code with Qt extensions

### Building the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/car_pool.git](https://github.com/chitransh7619/Car-Rental-System.git
   cd Car-Rental-System
