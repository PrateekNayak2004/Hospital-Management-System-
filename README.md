

Today 7:22 PM
I can run this project to my laptop full code i can found in github how to transfer to all the details and how to execute in my laptop step by step procegure 





image-1784124515664.jpg
image-1784124520680.jpg


I can register as patiant it canot be work 

image-1784124900500.jpg
image-1784124912947.jpg
image-1784124920150.jpg



I can set all 3 

Warning doenot appeared but no one can be open why

It is same page






image-1784126081677.jpg
image-1784126126192.jpg

image-1784126222548.jpg
image-1784126236056.jpg




Hospital-Management-System-master.zip
Zip Archive

I can first created new repository in github ..givethe description 

Great! Now do the following.

Step 1: Open VS Code
Open your Hospital-Management-System-master folder.

Step 2: Open the terminal
Go to:

Terminal → New Terminal

Step 3: Run these commands one by one
Replace the repository URL with your own if it's different.

git init
git add .
git commit -m "Initial commit - Hospital Management System"
git branch -M main
git remote add origin https://github.com/PrateekNayak2004/Hospital-Management-System.git
git push -u origin main
Step 4: If Git asks for your username/password
Use your GitHub username and a Personal Access Token (PAT) instead of your GitHub password.

If you get any error
Don't try to fix it yourself.

Take a screenshot of the terminal after running the commands or copy the error message here, and I'll tell you exactly what to do next. We'll get it uploaded successfully.


image-1784128637347.jpg

image-1784128779318.jpg
But name is defferent 

That's completely fine. The repository name doesn't have to match the folder name on your computer.

Your local folder:

Hospital-Management-System-master
Your GitHub repository:

Hospital-Management-System-
Git can connect them without any problem.

Now do this:
Open VS Code.

Click Terminal → New Terminal.

Run these commands one by one:

git init
git add .
git commit -m "Initial commit"
If the commit is successful, then run:

git branch -M main
Then connect it to your GitHub repository:

git remote add origin https://github.com/PrateekNayak2004/Hospital-Management-System-.git
Finally upload it:

git push -u origin main
Send me a screenshot after you run git commit -m "Initial commit".
I'll help you fix any errors if they appear before you push.



Pasted markdown.md
File
...convert to my redme file and remove video links

Yes. I recommend removing the original author's video and live demo links before uploading to your GitHub, since they point to someone else's project. The uploaded README contains those links. 


Replace the top section of your README.md with this:

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

Computer Science Engineer

## License

This project is developed for educational and learning purposes.
Also remove these sections from the original README:

❌ Video Demo

❌ Live Demo

❌ All YouTube links

❌ All 000webhost links

❌ Star History

❌ References to kishan0725

This will make the README appropriate for your own GitHub repository while accurately describing your project.


i have photoes but u delet that also

Don't delete your screenshots if they're your own project screenshots.

Keep the images, but remove only the links that point to the original developer's content.

Keep these
✅ Screenshots of your Hospital Management System

✅ Login page

✅ Admin Dashboard

✅ Patient Dashboard

✅ Doctor Dashboard

✅ Appointment page

✅ Prescription page

✅ Billing page

Remove these
❌ YouTube video link

❌ Live Demo (000webhost)

❌ Star History

❌ References to kishan0725

Update the image links
If your screenshots are stored in a folder like:

images/
then in your README use:

## Screenshots

### Home Page
![Home](images/home.png)

### Patient Dashboard
![Patient](images/patient-dashboard.png)

### Doctor Dashboard
![Doctor](images/doctor-dashboard.png)

### Admin Dashboard
![Admin](images/admin-dashboard.png)

### Appointment Booking
![Appointment](images/appointment.png)

### Prescription
![Prescription](images/prescription.png)
GitHub will display those images automatically.

Since this is your modified version (you changed the database port to 3307, fixed issues, and are uploading it to your own GitHub), you should keep your own screenshots and remove only the original author's external links.

If you want, I can also create a professional README.md with all your screenshots included in the correct order, suitable for your GitHub portfolio.


Hospital Management System
Hospital Management System using MySQL, Php and Bootstrap

Video Demo : Hospital Management System - Youtube

Live Demo : Hospital Management System - 000webhost by Kishan

Need to work on:
Ability to accept the appointment by the doctor to acknowledge the patient that their appointment has been approved.

User should not be allowed to register if he/she tries to provide the already registered email ID.

The password should be encrypted and the password field shouldn't be displayed in the admin panel.

Implementation of pagination for all the list view across the application.

Bug fix - Bill payment receipt contains multiple record if the patient has associated with the same doctor multiple times.

Addition of more fields in the prescription statement to make it more specific one.

Addition of more details on payment - such as date of the payment made, amount paid, etc.

Implementation of export button in admin module to export all details to an excel sheet.

Prerequisites
Install XAMPP web server

Any Editor (Preferably VS Code or Sublime Text)

Any web browser with latest version

Languages and Technologies used
HTML5/CSS3

JavaScript (to create dynamically updating content)

Bootstrap (An HTML, CSS, and JS library)

XAMPP (A web server by Apache Friends)

Php

MySQL (An RDBMS that uses SQL)

TCPDF (to generate PDFs)

Steps to run the project in your machine
Download and install XAMPP in your machine

Clone or download the repository

Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.

Start the Apache and Mysql in your XAMPP control panel.

Open your web browser and type 'localhost/phpmyadmin'

In phpmyadmin page, create a new database from the left panel and name it as 'myhmsdb'

Import the file 'myhmsdb.sql' inside your newly created database and click ok.

Open a new tab and type 'localhost/foldername' in the url of your browser

Hurray! That's it!

SOFTWARES USED
XAMPP was installed on the Ubuntu 19.04 machine and APACHE2 Server and MySQL were initialized. And, files were built inside opt/lampp/htdocs/myhmsp

Sublime Text 3.2 was used as a text editor.

Google Chrome Version 77.0.3865.90 was used to run the project (localhost/myhmsp was used as the url).

Starting Apache And MySQL in XAMPP:
The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.

<p align="center"><img src="https://user-images.githubusercontent.com/36665975/59350977-fcc68900-8d3a-11e9-9450-e5c478497caa.png"></img></p>

GETTING INTO THE PROJECT:
Hospital Management System in php and mysql. This system has a ‘Home’ page from where the patient, doctor & administrator can login into their accounts by toggling the tabs accordingly. Fig 1.1 shows the ‘Home’ page of our project.



'About Us' page (Fig 1.2) allows us to get some more information about the quality and the services of the hospital.



‘Contact’ page allows users to provide feedback or queries about the services of the hospital. Fig 1.3 shows the ‘Contact’ page.



The ‘Home’ page consists of 3 modules:

Patient Module

Doctor Module

Admin Module

Patient Module:
      This module allows patients to create their account, book an appointment to see a doctor and see their appointment history.
The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.



Once the patient has created his/her own account after clicking the ‘Register’ button, then he will be redirected to his/her Dashboard(Fig 1.5).



The Dashboard page allows patients to perform two operations:

1. Book his/her appointment:

      Here, the patients can able to book their appointments to see a doctor. The appointment form(Fig 1.6) requires patients to select the doctor that they want to see, Date and Time that they want to meet with the doctor. The consultancy fee will be shown accordingly to the patient as it was already determined by the doctor.



After clicking on the ‘Create new entry’ button, the patient will receive an alert that acknowledges the successful appointment of the patient.(See Fig 1.7)



2. View patients’ Appointment History:

      Here, the patient can see their appointment history which contains Doctor Name, Consultancy Fee, Appointment Date and Time.(See Fig 1.8).



Once the patient has logged out of his account, if he wants to go into his account again, he can login his account, instead of register his account again. Fig 1.9 shows the login page.
Clicking on ‘Login’ button will redirect the patient to his dashboard page which we have seen earlier (Fig 1.5)



This is how the patient module works. On the whole, this module allows patients to register their account or login their account(if he/she has one), book an appointment and view his/her appointment history.

Doctor Module:
      The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’. Fig 1.10 shows the login form for a doctor. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.



Once the doctor clicking the ‘Login’ button, they will be redirected to their own dashboard which is shown in Fig 1.11



In this page, doctor can able to see their appointments which has been booked by the patients. Fig 1.12 shows the appointment of the doctor ‘Ganesh’ which has been booked by the patient ‘Kenny Sebastian’ (Fig 1.6). This means that the doctor ‘Ganesh’ will have an appointment with the patient ‘Kenny Sebastian’ on 10-10-2019 10AM.



In real-time, the doctors will have thousands of appointments. It will be easier for a doctor to search for appointment in the case of more appointments. To make it easier, I have a ‘Search’ box in the navigation bar (See Fig 1.12) which allows doctors to search for a patient by their contact number.
      Once everything is done, the doctor can logout of their account. Thus, in general, a doctor can login into his/her account, view their appointments and search for a patient. This is all about Doctor Module.

Admin Module:
      This module is the heart of our project where an admin can see the list of all patients. Doctors and appointments and the feedback/queries received from the ‘Contact’ page. Also admin can add doctor too.
      Login into admin account can be done by toggling into admin tab of the Home page. Fig 1.13 shows the login page for admin.
      username: admin, password: admin123



On clicking the ‘Login’ button, the admin will be redirected to his/her dashboard as shown in
Fig 1.14.



This module allows admin to perform five major operations:

1. View the list of all patients registered:

      Admin can able to view all the patients registered. This includes the patients’ First Name, Last Name, Email ID, Contact Number and Password. (See Fig 1.15).As like in doctor module, admin can also search for a patient by their contact number in the search box.



2. View the list of all doctors registered:

      Details of the doctors can also be viewed by the admin. This details include the Name of the doctor, Password, Email and Consultancy fees, shown in Fig 1.16. Searching for a doctor can be done by using the doctor’s Email ID in the search box.



3. View the Appointment lists:

      Admin can also able to see the entire details of the appointment that shows the appointment details of the patients with their respective doctors. This includes the First Name, Last Name, Email and Contact Number of patients, doctor’s name, Appointment Date, Time and the Consultancy Fees. (See Fig 1.17).



4. Add Doctor:

      Admin alone can add a new doctor since anyone can register as a doctor if we put this section on the home page. This form asks Doctor’s Name, Email ID, Password and his/her Consultancy Fees.(See Fig 1.18)



After adding a new doctor, if we check the doctor’s list, we will see the details of new doctor is added to the list as shown in the Fig 1.19



5. View User’s feedback/Queries:

      Admin is allowed to view the feedback/Query that has been given by the user in the ‘Contact’ page (Refer Fig 1.3). This includes User’s Name, Email Id, Contact Number and the message(Feedback/ Query) as shown in the Fig 1.20.



      Taking everything into consideration, admin can able to view the details of patients and doctors, appointment details, Feedback by the user and can add a new doctor. Once everything is done, the admin can logout from his account.

Updates
1. Cancel Appointments
      Patients and doctors can able to delete their appointments.



If the patient deletes the last record (for doctor Ganesh), then a label "deleted by you" will be displayed in the column 'Current Status' and the action will change to cancel state.



Now if we login to the doctor Ganesh's account and view his appointment details, then it will look like this:



Similarly doctors can also delete their appointments and patients can view their updated appointment details.

2. Remove Doctors by Admin
      Admin can also delete the doctors from the system. This let admin to have more control over the system.



Star History









Close
