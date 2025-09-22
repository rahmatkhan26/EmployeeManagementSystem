# EmployeeManagementSystem
A simple **Core Java + JDBC** based application that manages employee records using CRUD operations.  
This project follows standard coding practices with a modular structure to keep code clean and maintainable.

---

##  Features
- Add new employees  
- View employee details  
- Update existing records  
- Delete employees from the database  
- JDBC connectivity with **SQL Database**

---

##  Project Structure
- **EmpManagementApp**  
  Main entry point of the project where all activities (CRUD operations) are called.

- **EmployeeDAO**  
  Handles database operations (Add, Delete, Update, Fetch) using `PreparedStatement`.

- **DBConnection**  
  Manages connection with the SQL database.

- **EmployeesPOJO**  
  Defines the Employee model class with fields and getter/setter methods.

---

##  Tech Stack
- **Language:** Core Java  
- **Database:** SQL (MySQL/any RDBMS)  
- **Connectivity:** JDBC

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/rahmatkhan26/EmployeeManagementSystem.git
