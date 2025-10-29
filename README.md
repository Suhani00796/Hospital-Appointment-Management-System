# Hospital-Appointment-Management-System
Developed an Online Library Management System using Java, JavaFX, and MySQL to automate book issue and return processes. The system provides role-based access for librarians, students, and administrators, ensuring secure transactions, real-time inventory updates, and efficient management of library records.
# Features
* Secure login for three user roles: Patient, Doctor, and Administrator.
* Patients can search for doctors, view real-time availability, and book or cancel appointments.
* Doctors can manage their schedules and view a list of all their upcoming appointments.
* Administrators can manage patient and doctor accounts and oversee all system activity.
* The system prevents common scheduling conflicts like double-booking.
# Requirements
* Java JDK 11 or higher
* MySQL Server
* Apache Maven
# Installation
1. Clone the repository
git clone https://github.com/your-username/your-repository-name.git
2. Set up the Database
* Create a new database in your MySQL server.
* Import the database schema from the database_setup.sql file to create the tables.
3. Configure Database Connection
* Update the database credentials (URL, username, password) in the project's configuration file.
4. Build and Run
* Open the project in your IDE (like IntelliJ or Eclipse).
* Let Maven build the project and download dependencies.
* Run the application from the main class.
