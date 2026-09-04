🩸 Smart Blood Bank and Donor Matching System

📌 Overview

The Smart Blood Bank and Donor Matching System is a database-driven application designed to efficiently manage blood donors, recipients, and donation appointments.

The system provides an admin-secured interface for managing records, validating donor eligibility, checking blood-group compatibility, and handling appointments through a centralized MySQL database.

✨ Key Features

* 🔐 Admin-secured login system
* 🧑‍⚕️ Donor management with personal and medical information
* 🏥 Recipient management
* ✅ Donor eligibility validation
* 🩸 Blood-group compatibility checking
* 📅 Appointment scheduling and management
* 🔄 Complete CRUD operations
* 🖨️ Appointment slip generation and printing
* 🔑 Unique CNIC, phone number, and email validation
* 🗄️ MySQL database integration

🧑‍⚕️ Donor Eligibility Constraints

The system applies predefined eligibility constraints for donors:

* Age greater than 18 years
* Weight greater than 50 kg
* Hb level greater than 13
* Donor must not have any of the restricted diseases
* CNIC, phone number, and email must be unique

🛠️ Technology Stack

* Frontend: HTML, CSS
* Backend: PHP
* Database: MySQL
* Database Management: phpMyAdmin
* Local Server: XAMPP

🗄️ Database Operations

The system implements complete CRUD functionality:

* Create — Add new records
* Read — Display stored records
* Update — Edit existing records
* Delete — Remove records

🔄 System Workflow

1. XAMPP is used to run Apache and MySQL locally.
2. The database is created and managed through phpMyAdmin.
3. Normalized database tables are created using SQL queries.
4. PHP connects the application to MySQL using mysqli.
5. CRUD operations are implemented for managing records.
6. Blood-group compatibility is checked while scheduling appointments.
7. Appointment slips can be generated and printed.

📁 Project Structure

The repository contains the application source code, database files, and supporting resources required to run the system locally.

⚙️ Installation & Setup

1. Install XAMPP

Start the following services:

* Apache
* MySQL

2. Configure the Database

Open phpMyAdmin and create the project database.

Import the provided SQL database file if available.

3. Add the Project

Place the project folder inside the XAMPP htdocs directory.

4. Configure Database Connection

Update the PHP database connection settings according to your local MySQL configuration.

5. Run the Application

Open the application through the local XAMPP server and access the admin login page.

🧪 Testing

The application was tested to verify that its pages function correctly and that database records can be successfully stored and retrieved from MySQL.

👥 Project Team

Team Urneeb Zahra

* Urneeb Zahra
* M. Ahmed Bin Kashif Malik
* Muhammad Saad Asghar

🎓 Academic Project

Course: Database Management System
Assignment: 3
Institution: Institute of Space and Technology, Islamabad, Pakistan

📄 License

This project was developed for academic purposes.

