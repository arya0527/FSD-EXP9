\# 🚀 EXP9 - Spring Boot REST API (JWT Authentication)



\## 📌 Aim



To design and implement a secure REST API using Spring Boot with JWT (JSON Web Token) based authentication and authorization.



\---



\## 📖 Description



This experiment demonstrates how to build a secure backend application using Spring Boot. It implements user authentication using JWT tokens, allowing only authorized users to access protected endpoints.



The system verifies user credentials, generates a token, and uses it for subsequent requests to ensure secure communication.



\---



\## ⚙️ Technologies Used



\* Java

\* Spring Boot

\* Spring Security

\* JWT (JSON Web Token)

\* Maven

\* MySQL (optional)



\---



\## 🔑 Features



\* User authentication using username \& password

\* JWT token generation

\* Secure REST endpoints

\* Role-based authorization (optional)

\* Stateless session management



\---



\## ▶️ How to Run



1\. Clone the repository:

&#x20;  git clone https://github.com/arya0527/FSD-EXP8.git



2\. Open project in Eclipse / IntelliJ



3\. Configure database in application.properties (if used)



4\. Run the Spring Boot application



5\. Access API using:

&#x20;  http://localhost:8087



\---



\## 🔗 API Endpoints



\### 🔹 Authentication



\* POST /authenticate → Login and get JWT token



\### 🔹 Protected APIs



\* GET /api/test → Accessible only with valid token



\---



\## 🛡️ How JWT Works



1\. User sends login request with credentials

2\. Server validates and generates JWT token

3\. Client stores token

4\. Token is sent in Authorization header

5\. Server validates token for each request



\---



\## 📷 Output



(Add screenshots of API responses here)



\---



\## 📚 Conclusion



This experiment helps in understanding secure API development using JWT authentication in Spring Boot. It ensures stateless and scalable authentication mechanisms for modern web applications.



\---

OUTPUT
<img width="1916" height="1066" alt="GET png" src="https://github.com/user-attachments/assets/c63fbd0e-f1cc-4340-a7a4-84276eed2b9b" />
<img width="1919" height="1079" alt="PORT png" src="https://github.com/user-attachments/assets/094796bd-93af-480b-aa92-56ffb780c66f" />
<img width="1919" height="1079" alt="POST png" src="https://github.com/user-attachments/assets/4300e8ca-287d-48d0-9f6c-7c6e295ea5ed" />


