# Todo Project

## 📌 About the Project
The **Todo Project** is a simple task management web application built using Java (Servlets & JSP), with a structured MVC pattern. It allows users to add, update, delete, and view tasks efficiently. This project is designed to help users organize their daily tasks with an easy-to-use interface.

## 🛠️ Technologies Used
- **Java** (Servlets, JSP)
- **Eclipse IDE** for development
- **Bootstrap** for frontend styling
- **MySQL** for database storage
- **Git & GitHub** for version control

## 🚀 Features
- Add new tasks
- View all tasks
- Update existing tasks
- Delete completed or unnecessary tasks

## 🔧 Project Setup & Execution
Follow these steps to set up and run the project:

### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/GouriJain17/todo_project.git
 cd todo_project
```

### 2️⃣ Configure the Database
1. Create a MySQL database (e.g., `todo_db`).
2. Run the provided SQL script (`todo_db.sql`) to create required tables.
3. Update the database connection settings in `DbUtil.java`:
   ```java
   private static final String URL = "jdbc:mysql://localhost:3306/todo_db";
   private static final String USER = "root";
   private static final String PASSWORD = "yourpassword";
   ```

### 3️⃣ Build & Deploy
1. Open the project in **Eclipse IDE**.
2. Build the project and deploy it on **Apache Tomcat**.
3. Start the Tomcat server.
4. Access the application in your browser at:
   ```
   http://localhost:8080/todo_project/
   ```

