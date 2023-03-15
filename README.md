# Hospital-API-Master
API for hospital.
API for the Covid hospital for doctors, patients and reports.
## Features
- Register doctors
- Login for doctors
- Register patients
- Create Covid-19 test result
- Make list of all reports of a patients
- Make list of all reports with a specified status
## Database Models
- Doctor (name, email, password)
- Patient (name, phoneNumber)
- Report (status, doctor)
## Folder Structure
- config (configuration files)
  - moongose.js (for database connection)
  - passport-jwt-strategy.js (for passport-jwt configuration)
- controllers
    - home_cont.js (contains controller related to home page) 
    - doctor_controller.js (contains controllers related to doctors)
    - patient_controller.js (contains controllers related to patients)
    - report_controller.js (contains controllers related to reports)
- models
  - doctor.js (for creating doctor database model)
  - patient.js (for creating patient database model)
  - report.js (for creating report database model)
- routes
       - doctors.js (contains routes related to doctors)
       - patients.js (contains routes related to patients)
       - reports.js (contains routes related to reports)
       - index.js
- index.js
- package.json
- package-lock.json
## How to Start
 npm start
## When Running in Local System
 run the the code in postman with corresponding routes and data 
