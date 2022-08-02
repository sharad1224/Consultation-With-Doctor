# Online-Doctor-Consultation-
--------------Patient---------------------------

Patient Class:
Pid
Pname
PEmail
PContact
PWD


User Story and Views Action Method:
Login(Email and Pwd)
Register(Patient)
ViewSpecialization
ViewDoctor(specialization:string)
BookAppointment(DoctorId)
ViewPrescrption(AppointmentId)
AddRating (AppoinmentId)

Services:
Patient

Components:
Patient
Login
Register
ViewSpecialization
ViewDoctor
BookAppointment
ViewPrescrption
AddRating


--------------Doctor---------------------------
APIs:

1st API: Doctor Registration 
	 Fields: DoctorID (auto generated)
		 FirstName
		 Last Name
		 Phone No
		 Email
		 Speciality
		 Password
		

Doctor Login
	Fields: Email
		Password

2 API: Appointment API (Get), 
3 API:  Do Online Consulation
4 API:Post Prescription 
5 API: View Ratings

Services:
1. Doctor Registration Service, Login
2. Appointment Service.
3. Prescription 
4. Ratings


Component:
1. Registration (POST), Login
2. Appointment List(Get), 
3. Prescription (POST), 
4. Patient's Review(Get) 

------------------------------Patient-------------------------------------------------------
Feature 1:

1. I as Patient I should be able to view registration page.
2. I as Patient I should be able to register by entering Name,Contact,Email,Password and confirm password fields
3. I as Patient I should be able to navigate to login page after succesfull registration.
4. I as Patient I should be able to view login page.
5. I as Patient I should be able to login using emailId and password.
6. I as Patient I should be able to view patient home page after successfull login. 


Feature 2:
1. I as Patient I should be able to view all the specialization.
2. I as Patient I should be able to select the specific specialization.
3. I as Patient I should be able to view all the available doctors in the selected specializzation.
4. I as Patient I should be able to select the doctor.


Feature 3:
1. I as Patient I should be able to view the book appoinment page.
2. I as Patient I should be able to book appoinment by giving date,time and health issue fields.
3. I as Patient I should be able to able view my appoinment after succesfully booking an appoinment.
4. I as Patient I should be able to to view my prescription after succesfull consultaion.

5. I as Patient I should be able to click on add rating.
6. I as Patient I shold be able to  view the add prescrpition page.
7. I as Patient should be able to fill the respective fields and submit.


---------------------------------------Doctor--------------------------------------------------------
Feature 1:

1. I as Doctor I should be able to view registration page.
2. I as Doctor I should be able to register by entering Name,Contact,Email,Specialization,Password and confirm password fields
3. I as Doctor I should be able to navigate to login page after succesfull registration
4. I as Doctor I should be able to view login page.
5. I as Doctor I should be able to login using emailId and password.
6. I as Doctor I should be able to view Doctor home page after successfull login. 

Feature 2:

1.I as Doctor I should be able to view all My Appointments
2.I as Doctor I should be able to Accept/Cancel the Appointment

Feature 3:

1.I as Doctor I should be able to have the consultation session with Patient
2.I as Doctor I should be able to Submit the Prescription
3.I as Doctor I should be able to view the Reviews given by the patient.

