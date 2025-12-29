# Student Enrollment Form using JsonPowerDB

## Project Description
This project is a **Student Enrollment Form** web application developed using **HTML, JavaScript, jQuery, and JsonPowerDB (JPDB)**.  
It allows users to **store, retrieve, and update student records** using **Roll Number** as the primary key.

The application follows proper form control logic, validation, and database interaction as per the micro-project requirements.

---

## Technologies Used
- HTML  
- JavaScript  
- jQuery  
- JsonPowerDB  
- jpdb-commons.js  

---

## Database Details
- **Database Name:** SCHOOL-DB  
- **Relation Name:** STUDENT-TABLE  
- **Primary Key:** Roll-No  

### Fields
- Roll-No  
- Full-Name  
- Class  
- Birth-Date  
- Address  
- Enrollment-Date  

---

## Application Features

### Initial State
- Form loads empty  
- Cursor focuses on Roll No field  
- All other input fields and buttons are disabled  

### New Roll Number
- Save and Reset buttons are enabled  
- User can enter student details  
- Empty field validation is applied  
- Data is stored in database  

### Existing Roll Number
- Data is fetched from database  
- Form fields are populated  
- Update and Reset buttons are enabled  
- Roll No field is disabled  
- Other fields can be updated  

### Reset Functionality
- Clears all input fields  
- Disables fields except Roll No  
- Cursor moves back to Roll No field  

---

## Application Flow
1. Enter Roll Number  
2. System checks database  
3. If Roll No does not exist → Enable Save  
4. If Roll No exists → Display data and enable Update  
5. Save or Update data  
6. Reset returns form to initial state  

---

## Validation Rules
- No input field can be empty  
- Primary key must be unique  
- Roll No cannot be edited during update  

---

## Project Structure
Student-Enrollment-Form
│
├── index.html
└── README.md


---

## How to Run the Project
1. Download or clone the project  
2. Replace the JsonPowerDB connection token in the code  
3. Open `index.html` in a web browser  
4. Enter student details and perform Save or Update operations  

---

## Conclusion
This project demonstrates efficient form handling, primary key validation, and CRUD operations using JsonPowerDB.  
It satisfies all micro-project requirements and is suitable for academic and internship submissions.

---

## Author
**Paridhi Patidar**  
M.Tech Integrated (4th Year)  
International Institute of Professional Studies, DAVV  
