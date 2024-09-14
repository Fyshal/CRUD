
# CRUD Application with Login SignUP System

## Overview

This project is a Windows Forms application developed in C# that demonstrates basic CRUD (Create, Read, Update, Delete) operations with a login system. The application allows users to sign up, log in, and manage user records in a SQL Server database.

## Features

- **User Registration**: Users can register with email, name, username, and password.
- **User Login**: Users can log in with their username and password.
- **Record Management**:
  - **Create**: Add new user records.
  - **Read**: View all user records in a data grid.
  - **Update**: Modify existing user records.
  - **Delete**: Remove user records by ID.

## Technologies Used

- C#
- Windows Forms
- SQL Server
- ADO.NET

## Setup and Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   Open the Project
2. **Open the solution file(.sln) in Visual Studio**
Open the solution file (.sln) in Visual Studio.
3.	Configure Database Connection
o	Ensure you have SQL Server installed.
o	Create a database named CRUD.
o	Update the connection string in the SignUP and Login classes to match your SQL Server instance.
csharp
Copy code
// Connection String Example
string connectionString = "Data Source=YOUR_SERVER_NAME;Initial Catalog=CRUD;Integrated Security=True;Encrypt=True;TrustServerCertificate=True";
4.	Build and Run the Application
o	Build the project in Visual Studio.
o	Run the application to start using the CRUD functionality.
Usage
•	Sign Up: Use the SignUP form to create a new user account. Ensure all fields are filled before submission.
•	Login: Use the Login form to authenticate and access the CRUD functionality.
•	Manage Records: After logging in, you can:
o	View all user records by clicking the "View Records" button.
o	Update existing records by specifying an ID and updating the relevant fields.
o	Delete records by specifying an ID.
Code Structure
•	SignUP.cs: Handles user sign-up, record management, and UI interactions.
•	Login.cs: Manages user login and authentication.

