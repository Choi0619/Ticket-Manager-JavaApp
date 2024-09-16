# Ticket-Manager-JavaApp

## Description
This project is a **GUI-based HelpDesk Ticketing System** built using **Java**, **JDBC**, **PHP server**, and **MySQL**. It is designed to manage customer support tickets efficiently, allowing users to create, update, view, and close support tickets. The system is also equipped with admin functionalities to provide greater control over ticket management.

## Key Features:
- **User Authentication**: Log in with a username and password to access the system.
- **Ticket Management**: Users can create new support tickets, view existing tickets, update ticket details, and close tickets when resolved.
- **Admin Privileges**: Administrators have the ability to delete or update tickets.
- **Database Integration**: All data is stored in a MySQL database and accessed using JDBC for efficient data management.

## Technologies Used:
- **Java**: For building the GUI and business logic.
- **JDBC**: For database connectivity and CRUD operations.
- **PHP Server**: For backend integration (optional).
- **MySQL**: For storing user and ticket data.

## How to Use:
1. Clone the repository to your local machine.
2. Set up the MySQL database and update the connection details in the `Dao.java` file.
3. Run the `Login.java` class to start the application.
4. Log in as a user or admin to manage support tickets.

## Project Structure:
- **Dao.java**: Handles database connectivity and CRUD operations.
- **Tickets.java**: Main GUI class for managing tickets.
- **Login.java**: Provides user login functionality.
- **userlist.csv**: Sample user data for testing the application.

## License
This project is for educational purposes only and uses **fake data**. Feel free to use and modify for your own learning and development.
