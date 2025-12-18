# StudentManagementSystem

A Student Management System built using Spring Boot, JPA (Hibernate), and PostgreSQL that allows efficient management of student records through RESTful APIs. This project follows a clean layered architecture and is suitable for fresher-level backend development projects.

## 🚀 Features

- Add new student records  
- Update existing student details  
- Delete student records  
- View all students  
- View student by ID  
- RESTful API implementation  
- Layered architecture (Controller, Service, Repository)  
- PostgreSQL database integration  

## 🛠️ Technologies Used

- Java  
- Spring Boot  
- Spring Data JPA (Hibernate)  
- PostgreSQL  
- Maven  
- REST APIs  
- IntelliJ IDEA / Spring Tool Suite  

## 🏗️ Project Structure

student-management-system  
├── controller  
│   └── StudentController.java  
├── service  
│   ├── StudentService.java  
│   └── StudentServiceImpl.java  
├── repository  
│   └── StudentRepository.java  
├── entity  
│   └── Student.java  
├── dto  
│   └── StudentDTO.java  
├── exception  
│   └── GlobalExceptionHandler.java  
└── StudentManagementApplication.java  

## ⚙️ Database Configuration

Update the following properties in `application.properties`:

spring.datasource.url=jdbc:postgresql://localhost:5432/student_db  
spring.datasource.username=postgres  
spring.datasource.password=your_password  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect  

## 🔗 REST API Endpoints

POST   /students        → Add new student  
GET    /students        → Get all students  
GET    /students/{id}   → Get student by ID  
PUT    /students/{id}   → Update student  
DELETE /students/{id}   → Delete student  

## ▶️ How to Run the Project

1. Clone the repository  
   git clone https://github.com/hariomkushwaha-1217/StudentManagementSystem
   
3. Open the project in IntelliJ IDEA or Spring Tool Suite  

4. Create a PostgreSQL database named `student_db`  

5. Update database username and password in `application.properties`  

6. Run `StudentManagementApplication.java`  

7. Test APIs using Postman  

## 📌 Future Enhancements

- Spring Security with JWT authentication  
- Pagination and sorting  
- Input validation using Hibernate Validator  
- Frontend integration using React or Angular  

## 👨‍💻 Author

Hari Om Kushwaha  
B.Tech (Computer Science)  
Java Full Stack Developer
