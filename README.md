# springboot-rest-mysql-app

In this project, we have created **Course CRUD Operations** using **Spring Boot**, **Spring Data JPA**, and **MySQL** as the database.

## How to Test the Application

You can test the application using the following sample endpoints and request data.

---

### 🔹 Create Course

**POST** `http://localhost:8080/course`

```json
{
  "name": "Java",
  "price": 3000.00
}

###🔹 Get All Courses
GET http://localhost:8080/courses

🔹 Get Course By ID
GET http://localhost:8080/course/3

🔹 Update Course
**PUT** `http://localhost:8080/course`

```json
{
  "cid": 2,
  "name": "Angular",
  "price": 2500
}
