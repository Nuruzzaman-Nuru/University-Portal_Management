# University Portal Management System

A web-based Portal Management System developed by Nuruzzaman. This platform is designed to manage various academic and administrative activities, including user authentication, course management, attendance tracking, result management, and more. It supports multiple roles: Admin, Teacher, Student.
![homepage](portal2.jpg)
---
## Acknowledgements

- HTML5, CSS, Tailwind CSS,PHP, MySQL.
- Open-source community
- All contributors and testers
## Features

- **User Authentication**
  - Separate login and registration for students, teachers, and admins.
  - Password reset functionality for all user roles.
  - Secure session management.

- **Admin Functionalities**
  - View and manage all users and their requests.
  - Approve or reject student course requests.
  - Add, update, or remove courses.
  - View and manage student results.
  - Admin dashboard for quick actions.

- **Teacher Functionalities**
  - View assigned courses and class routines.
  - Enter and update student results.
  - Take and manage attendance.

- **Student Functionalities**
  - Request courses and view assigned courses.
  - View personal attendance and results.
  - Profile management.

- **General**
  - Intuitive navigation and user interface.
  - Modular code structure for easy maintenance.
  - Built-in SQL file for database setup.
  - Customizable CSS for UI enhancement.
  - Logo and branding assets included.

---

## Project Structure

```
.
├── Sql File/                   # Database SQL scripts
├── css/                        # Stylesheets
├── logo/                       # Logo and branding assets
├── add_course.php              # Add new course (Admin)
├── admin_conform.php           # Admin approval for actions
├── admin_home.php              # Admin dashboard
├── admin_log.php               # Admin login
├── admin_logout.php            # Admin logout
├── admin_reset_pass.php        # Admin password reset
├── admin_result_view.php       # View results (Admin)
├── attend_home.php             # Attendance dashboard
├── attendence.php              # Attendance management
├── class_routine.php           # Class routine view
├── confirm_student.php         # Confirm student actions
├── conn.php                    # Database connection
├── delete.php                  # Delete records
├── footer.php                  # Footer include
├── index.php                   # Landing page
├── insert_result.php           # Insert student results
├── insert_result_home.php      # Result entry dashboard
├── profile.php                 # User profile management
├── result.php                  # View student results
├── search.php                  # Search functionality
├── student_course_request.php  # Course requests (Student)
├── student_fatch_course.php    # Fetch courses for student
├── student_home.php            # Student dashboard
├── student_log.php             # Student login
├── student_logadmin.php        # Admin login for students
├── student_logout.php          # Student logout
├── student_reset_pass.php      # Student password reset
├── student_result.php          # Student result view
├── student_signup.php          # Student registration
├── taken_course.php            # List of taken courses
├── teacher_home.php            # Teacher dashboard
├── teacher_log.php             # Teacher login
├── teacher_logout.php          # Teacher logout
├── teacher_reset_pass.php      # Teacher password reset
├── update_profile.php          # Update user profile
├── Portal_By_Nuruzzaman_Main.rar  # Project archive (optional)
└── README.md                   # Project documentation
```

---

## Installation & Setup

1. **Clone the Repository**
    ```bash
    git clone https://github.com/Nuruzzaman-Nuru/Portal_Management.git
    cd Portal_Management
    ```

2. **Setup the Database**
    - Import the SQL file(s) from the `Sql File` directory into your MySQL server.
    - Update `conn.php` with your database credentials.

3. **Configure the Environment**
    - Ensure PHP and MySQL are installed on your system (XAMPP, WAMP, LAMP, etc.).
    - Place the project folder in your web server's root directory (e.g., `htdocs` for XAMPP).
    - Update any paths or configuration files as needed.

4. **Run the Application**
    - Open your browser and navigate to `http://localhost/Portal_Management` (or your configured local path).
    - Log in as an Admin, Teacher, or Student to get started.

---

## Usage

- **Admin**
  - Default admin credentials can be set in the database or upon first registration.
  - Access the admin dashboard to manage users, courses, and results.

- **Teacher**
  - Teachers can log in to view assigned tasks, manage attendance, and update results.

- **Student**
  - Students can sign up, request courses, view attendance, and check results.

---

## Customization

- **Styling:**  
  Modify the `css/` directory to change the look and feel.
- **Database:**  
  Adjust or extend the SQL structure in the `Sql File` directory as needed.
- **Assets:**  
  Replace files in the `logo/` directory for branding.

---

## Security Note

- Change default credentials after first login.
- Consider implementing stronger password hashing and CSRF protection for production use.
- Always sanitize user input to prevent SQL injection or XSS.

---

## License

This project is for educational purposes. For commercial or production use, please review and adapt security, licensing, and compliance as needed.

---

## Author

**Nuruzzaman**  
[[GitHub Profile](https://github.com/Nuruzzaman-Nuru)](https://github.com/Nuruzzaman-Nuru/University-Portal_Management)

---

## Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---






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
