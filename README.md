# 🎓 Student Management System (Full Stack)

A full-stack web application to manage student records built using React (frontend), Spring Boot (backend), and MySQL (database).

---

## 🚀 Features
- Add, edit, delete student details
- Connected to MySQL backend
- REST API integration with Spring Boot
- Responsive frontend UI with React

---

## 🧰 Tech Stack

| Layer     | Technology        |
|-----------|-------------------|
| Frontend  | React, Axios, CSS |
| Backend   | Spring Boot, Java |
| Database  | MySQL             |
| Protocols | RESTful API       |

---

## 🛠️ Getting Started

### 📦 Backend (Spring Boot)
1. Import the `backend/` folder into IntelliJ or Eclipse
2. Create a MySQL DB named: `student_system`
3. In `application.properties`, update:
   ```properties
   spring.datasource.username=your_username
   spring.datasource.password=your_password


### Setup  

#### Backend (Spring Boot):  
1. Clone the repository.  
2. Navigate to the backend folder.  
3. Update the `application.properties` file to configure the MySQL database:  
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/student_management
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   spring.jpa.hibernate.ddl-auto=update
