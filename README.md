How to Run the Portal Management System (XAAM App)
Install Prerequisites

Install XAMPP (or WAMP, LAMP) on your computer.
Download XAMPP
Ensure you have PHP and MySQL enabled.
Set Up the Project

Unzip your project files (if in a .rar or .zip).
Copy the entire project folder (e.g., Portal_Management) into the htdocs directory of XAMPP (usually C:\xampp\htdocs).
Import the Database

Open XAMPP Control Panel and start Apache and MySQL.
Go to http://localhost/phpmyadmin in your browser.
Create a new database (e.g., portal_db).
Use the Import feature to import the .sql file from your Sql File directory.
Update Database Connection

Open the conn.php file in your project.
Update the database name, username, and password as per your XAMPP/MySQL setup (default: user = root, password = blank).
Run the App

Open your browser and go to:
http://localhost/Portal_Management/index.php
You should see your app’s login or landing page.
# Portal_Management
