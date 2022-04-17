# hospital
hospital management system

How to run the Hospital Management System (HMS) Project

About project tech stack: 
Language used : PHP5.6
Database: MySQL 5.6
User interface : HTML, AJAX,JQUERY,JAVASCRIPT
Software : Xampp

Configure at local : 

1. Clone the repo https://github.com/SayaliKadam14/hospital.git

2.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)

3. Open PHPMyAdmin (http://localhost/phpmyadmin)

4. Create a database with name hms

5. Import hms.sql file(given inside the zip package in SQL file folder)

6.Run the script http://localhost/hospital (frontend) ( Please do database configuration changes in each module's config file )

Login Details
Login Details for admin : 
Username : AdminSayali
Password : Test@12345

Login Details for Patient: 
Username : ksayali70@gmail.com
Password : Test@12345

Login Details for Doctor: 
Username : ksayu14@gmail.com
Password : Test@12345
_________________________________________________________________________________________________________________________________________________


About project : 

Hospital Management System is a web application for the hospital which manages doctors and patients. In this project, we use PHP and MySQL database.
The entire project mainly consists of 3 modules, which are

Admin module
User module
Doctor module
Admin module:

Dashboard: In this section, admin can view the Patients, Doctors, Appointments and New queries.
Doctors: In this section, admin can add doctor’s specialization and mange doctors (Add/Update).
Users: In this section, admin can view users detail(who take online appointment) and also have right to delete irrelevant user.
Patients: In this section, admin can view patient’s details.
Appointment History: In this section, admin can view appointment history.
Contact us Queries: In this section, admin can view queries which are send by users.
Doctor Session Logs: In this section, admin can see login and logout time of doctor.
User Session Logs: In this section, admin can see login and logout time of user.
Reports: In this section, admin can view reports of patients in particular periods.
Patient Search: In this section, admin can search patient with the help of patient name and mobile number.
Admin can also change his/her own password.
User module (patient):

Dashboard: In this section, patients can view the his/her profile, Appointments and Book Appointment.
Book Appointment: In this section, Patient can book his/her appointment.
Appointment History: In this section, Patients can see his/her own appointment history.
Medical History: In this section, Patients can see his/her own appointment history.
User can update his/her profile, change the password and recover the password.
Doctor module:

Dashboard: In this section, doctor can view his/her own profile and online appointments.
Appointment History: In this section, Doctor can see patient’s appointment history.
Patients: In this section, doctor can manage patients (Add/Update).
Search: In this section, doctor can search patient with the help of patient name and mobile number.
Doctor can also update his profile, change the password and recover the password.


