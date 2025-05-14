Agri-Energy Connect
Agri-Energy Connect is a web application that bridges sustainable agriculture with green energy, providing farmers and employees with the tools and resources to manage agricultural products, energy solutions, and business operations.

Table of Contents
Project Description

Tech Stack

Features

Setup

Running the Application

Contributing

License

Project Description
The Agri-Energy Connect platform is designed to provide an integrated solution for farmers and employees in the agricultural industry, with a focus on sustainable energy use. The system allows farmers to register products, manage energy consumption, and connect with relevant stakeholders.

Tech Stack
Frontend: ASP.NET Core MVC, HTML, CSS, JavaScript, Bootstrap

Backend: ASP.NET Core, C#

Database: SQLite (or SQL Server, if preferred)

Authentication: ASP.NET Core Identity (for login and registration)

Version Control: Git, GitHub

Features
Login and Registration: Allows users to register and log in as Farmers or Employees.

Product Management: Farmers can add products, manage categories, and production dates.

Role-Based Access: Based on user role (Farmer or Employee), different dashboards are shown.

Sustainable Agriculture: Focus on green energy solutions and sustainable practices.

Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-repo-link/Agri-Energy-Connect.git
cd Agri-Energy-Connect
Install dependencies:

If you don’t have the .NET SDK installed, download and install it from here.

For NuGet dependencies, you can run:

bash
Copy
Edit
dotnet restore
Configure the database:

If you're using SQLite, ensure the connection string is set correctly in appsettings.json.

For SQL Server, change the connection string to your server and database.

Create Database and Migrations:

Open a terminal or command prompt and run:

bash
Copy
Edit
dotnet ef migrations add InitialCreate
dotnet ef database update
Running the Application
Run the application:

bash
Copy
Edit
dotnet run
The application will start and can be accessed at http://localhost:5000.

Access the application:

Open your browser and go to http://localhost:5000.

Login with the registered credentials or use the default login details:

Email: farmer@test.com, Password: 1234 (Farmer role)

Email: employee@test.com, Password: 1234 (Employee role)

Contributing
If you'd like to contribute to Agri-Energy Connect, feel free to fork the repository, make your changes, and submit a pull request. Please make sure to follow the coding style and include appropriate tests for your changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.
