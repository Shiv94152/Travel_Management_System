# Travel_Management_System
## Overview

The **Travel Management System** is a C++ console application designed to automate the management of travel services. It provides an efficient way to handle customer details, cab bookings, hotel reservations, and generates bills, making it a suitable tool for travel agencies or individual users. The project is built using Object-Oriented Programming (OOP) principles, ensuring modularity, reusability, and maintainability.

## Features

- **Customer Management:** Add and view customer details.
- **Cab Booking:** Rent standard or luxury cabs and calculate travel costs.
- **Hotel Booking:** Choose from multiple hotels and book different packages.
- **Bill Generation:** Automatic generation of receipts for bookings.
- **User-Friendly Interface:** Easy-to-navigate console-based interface.

## Project Structure

- **`ManageMenu` Class:** Handles the main menu and administrative access.
- **`Customer` Class:** Manages customer information and records.
- **`Cabs` Class:** Handles cab booking and cost calculation.
- **`Booking` Class:** Manages hotel bookings and package selection.
- **`Chargers` Class:** Inherits from `Booking`, `Cabs`, and `Customer` to generate and display bills.

### Prerequisites

- **C++ Compiler:** Ensure you have a C++ compiler installed (e.g., g++, clang).
- **Operating System:** The system is platform-independent and can run on Windows, Linux, or macOS.


## Future Enhancements

- **GUI Implementation:** Develop a graphical user interface for better user experience.
- **Database Integration:** Implement database support for persistent data storage.
- **Online Booking:** Introduce features for online booking and payments.
