# Hospital Management System
Hospital Management System which is built using java technologies .This Web application helps in management of Patients, doctors, admin in a easy and comfortable way.using this Application patients can quickly Sign up, Login, view his/her profile, view doctors, book Appointment, view Report, choose doctor, view Appointments and logout. Admin can add Doctors,view patients list, view Doctors list,remove doctors, see feedback given by patients,view reports,logout.Doctor can login, view profile, viewAppointments, Attend Patients and logout.

# Key Features:

<h4>login , logout </h4>
<h4>Admin’s DashBoard </h4>
<h4>Patient’s DashBoard</h4>
<h4>Doctor’s DashBoard</h4>
<h4>Appointment-Table</h4>
<h4>Booking Appointment</h4>
<h4>Choosing Doctor</h4>

## Core Functionalities:

<h4>    Patient Record Management:</h4> Allows the efficient handling of patient data, storing personal information, medical history, and treatment records in a structured manner.

<h4>   Appointment Scheduling:</h4> Facilitates the scheduling and management of appointments between doctors and patients, ensuring a streamlined booking process and reducing scheduling conflicts.

<h4>   Administrative Management:<h4></h4> Supports hospital administrators in overseeing day-to-day activities, managing doctor schedules, generating reports, and organizing hospital resources.


# Technologies Used:
<h4>JSP (JavaServer Pages):</h4> Provides a dynamic interface for users, offering a more interactive user experience.

<h4>Servlets:</h4> Handles the business logic, enabling data processing and communication between the front end and the database.

<h4>JDBC (Java Database Connectivity):</h4> Manages database interactions, allowing CRUD (Create, Read, Update, Delete) operations for various modules like patient data, appointments, and staff records.


# Requirements Tools :

<h4>Java [JDK 17+] </h4>
<h4>Apache Maven 3.9+</h4>
<h4>MySQL 8.0+</h4>
<h4>Jdbc Driver</h4>
<h4>Apache Tomcat 10+</h4>

<h1>SETUP Instruction</h1>
<p>🧰 Setup Instructions
1. Clone or Download the Project
git clone https://github.com/your-username/Hospital_managment_project.git
cd Hospital_managment_project

2. Configure Database

Create a new MySQL database:

CREATE DATABASE hospital_db;


Update your src/main/resources/application.properties file:

spring.datasource.url=jdbc:mysql://localhost:3306/hospital_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

3. Build the Project
mvn clean install


✅ This will generate target/Hospital_managment_project.war

4. Deploy to Tomcat

Copy the WAR file to:

C:\Program Files\Apache Software Foundation\Tomcat 10.1\webapps\


Start Tomcat:

C:\Program Files\Apache Software Foundation\Tomcat 10.1\bin\startup.bat or if you Double click "Startup.Bat file" it automatically runs on local host : 8080


Visit:

http://localhost:8080/Hospital_managment_project</p>

<h1>
Default Admin Credentials 
username:admin@gmail.com
password:admin
</h>

