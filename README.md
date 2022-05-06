# HospitalMgmt-AcademicProject
Hospital Management

This Project depends on Hospital Appointment system

Where 3 types of users can login **Admin, Doctor and Patient**
- Admin has all kind of permissions and can add doctor to the system
- Admin provides login credentials for Doctor to login
- Doctor can edit the profile and see all his patients with appointment history
- Patient user has to register first and then login to system to get appointment


Functionality-
  - Admin can show, approve, delete and can delete appointments
  - Doctor can approve and complete appointments
  - Patient can show, edit and delete appointments
  - Once appointment approved patient can see approved appointment tag on wall and unable to edit or delete particular appointment
  - System maintains all kind of history

Currently project using the MySQL Database, To use present SQLite DB you need to make some changes in settings.py
Just comment out SQLite default and comment MySQL default
