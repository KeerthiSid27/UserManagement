# UserManagement

# Spring Boot RESTful Web Services

This is a simple Spring Boot application that demonstrates building RESTful APIs with CRUD operations using MySQL, Spring Data JPA, and layered architecture (Entity, Repository, Service, Controller).

## 🚀 Technologies Used

- Java 17
- Spring Boot 3.0.0
- Spring Data JPA
- MySQL
- Maven
- Lombok

---

## 📁 Project Structure

springboot-restful-webservices/
├── src/
│ ├── main/
│ │ ├── java/net/javaguides/springboot/
│ │ │ ├── controller/
│ │ │ ├── entity/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ └── service/impl/
│ │ └── resources/
│ │ ├── application.properties
├── pom.xml


---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/springboot-restful-webservices.git
cd springboot-restful-webservices
2. Create MySQL Database
Login to MySQL Workbench or CLI and run:

sql
Copy
Edit
CREATE DATABASE user_management;
3. Configure application.properties
Edit src/main/resources/application.properties:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/user_management
spring.datasource.username=root
spring.datasource.password=Mysql@123

spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
Change username and password as per your local MySQL setup.

🛠 Build and Run the Application
Using Maven:
bash
Copy
Edit
mvn clean install
mvn spring-boot:run
📡 API Endpoints
Method	Endpoint	Description
POST	/api/users	Create a new user
GET	/api/users	Get all users
GET	/api/users/{id}	Get user by ID
PUT	/api/users/{id}	Update user by ID
DELETE	/api/users/{id}	Delete user by ID

📦 Sample JSON for POST/PUT
json
Copy
Edit
{
  "firstName": "John",
  "lastName": "Doe",
  "email": "john.doe@example.com"
}
🧪 Testing
You can test the REST APIs using tools like:

Postman

cURL

📌 Notes
Make sure MySQL is running locally.

This project uses Lombok — enable annotation processing in your IDE.
