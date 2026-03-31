# 🧑‍🎓 Online Exam System (Spring Boot)

An Online Exam System developed using Spring Boot that allows administrators to create and manage exams while students can attempt tests and view results. This project demonstrates full-stack backend development, REST APIs, and database integration.

---

## 🚀 Features

* 👨‍🏫 Admin can create, update, and delete exams
* 📝 Add and manage questions
* 👨‍🎓 Student can attempt exams
* ⏱️ Timer-based exam system *(if implemented)*
* 📊 Automatic result calculation
* 🔐 Basic authentication *(if implemented)*

---

## 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring MVC
* Spring Data JPA

### Database

* MySQL

### Tools

* Maven
* Postman (for API testing)

---

## 📂 Project Structure

```id="str123"
Online-Exam-System/
│── src/main/java/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   └── model/
│
│── src/main/resources/
│   ├── application.properties
│
│── pom.xml
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash id="clone123"
git clone https://github.com/ganesh-22-m/Online-Exam-System-Spring-Boot.git
cd Online-Exam-System-Spring-Boot
```

---

### 2️⃣ Configure Database

Update `application.properties`:

```properties id="db123"
spring.datasource.url=jdbc:mysql://localhost:3306/online_exam_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
```

---

### 3️⃣ Run the Application

* Open in IntelliJ / Eclipse
* Run main Spring Boot class

App will start on:

```
http://localhost:8080
```

---

## 📡 API Endpoints

| Method | Endpoint    | Description       |
| ------ | ----------- | ----------------- |
| GET    | /exams      | Get all exams     |
| POST   | /exams      | Create exam       |
| PUT    | /exams/{id} | Update exam       |
| DELETE | /exams/{id} | Delete exam       |
| GET    | /questions  | Get all questions |
| POST   | /questions  | Add question      |

---

## 🗄️ Database Design

### Exam Table

* id
* title
* description

### Question Table

* id
* question
* options
* correct_answer
* exam_id

---

## 📸 Screenshots

*(Add your project screenshots here)*

---

## 🔥 Future Improvements

* 🔐 JWT Authentication (Login/Signup)
* 📊 Dashboard with analytics
* ⏱️ Auto-submit on timer
* 📄 Result PDF generation
* 🌐 Frontend integration (React / Angular)

---

## 💼 Resume Description

```id="resume123"
Developed a Spring Boot-based Online Exam System with RESTful APIs to manage exams and questions. 
Implemented backend logic for exam creation, student participation, and automatic result evaluation using MySQL database integration.
```

---

## 🙌 Author

**Ganesh Mahajan**

* GitHub: https://github.com/ganesh-22-m

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
