# 🏥 Hospital Management System

A web-based Hospital Management System developed using PHP, MySQL, Bootstrap, HTML, CSS, and JavaScript. The system helps hospitals manage patients, doctors, appointments, prescriptions, and billing through separate login panels.

## Features

### Patient Module
- Patient Registration & Login
- Book Doctor Appointment
- View Appointment History
- View Prescriptions
- Generate Bill (PDF)
- Cancel Appointment

### Doctor Module
- Doctor Login
- View Patient Appointments
- Search Patients
- Add Prescriptions
- Manage Appointment Status

### Admin Module
- Admin Login
- Manage Patients
- Manage Doctors
- Manage Appointments
- View Patient Queries
- Add New Doctors

## Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- Bootstrap 4
- JavaScript
- XAMPP
- TCPDF

## Project Setup

1. Install XAMPP.
2. Copy the project folder into the `htdocs` directory.
3. Start Apache and MySQL from the XAMPP Control Panel.
4. Create a database named `myhmsdb`.
5. Import the `myhmsdb.sql` file into the database.
6. Update database connection settings if using MySQL on port **3307**.
7. Open the project in your browser:

```
http://localhost/Hospital-Management-System-master/
```

## Default Login Credentials

### Admin
- Username: admin
- Password: admin123

### Doctor
- Use credentials stored in the database.

### Patient
- Register a new account or use an existing patient account.

## Project Structure

```
Hospital-Management-System-master/
│── admin-panel.php
│── doctor-panel.php
│── patient-panel.php
│── func.php
│── newfunc.php
│── myhmsdb.sql
│── TCPDF/
│── assets/
│── css/
│── js/
│── images/
│── vendor/
```

## Future Enhancements

- Online Payment Gateway
- Email Notifications
- SMS Alerts
- Appointment Approval
- Password Encryption
- Responsive Dashboard
- Export Reports

## Author

**Prateek U Nayak**

Information Science Engineer

## License

This project is developed for educational and learning purposes.
