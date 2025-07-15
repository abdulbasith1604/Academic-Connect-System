Academic Connect System

Developed a Java-based application to manage registration and login for students and colleges, allowing users to
perform role-specific operations. Implemented a MySQL database with JDBC for data storage and retrieval, supporting user authentication, data
updates, and deletions based on user roles.

Features
- Role-based registration and login for Students and Colleges
- Students can:
  - Register with personal and academic details
  - Login, update, and delete their data
- Colleges can:
  - Register with institutional details
  - Login, update details, delete their account
  - View student data

Tech Stack
- Java (Core)
- MySQL (Database)
- JDBC (Database Connectivity)
- Eclipse IDE

Project Structure
- `college` package:
  - `User`, `Student`, `College` classes
  - DAOs: `UserDAO`, `StudentDAO`, `CollegeDAO`
  - `DbConnection.java`
  - `Main.java` — program flow

Author
Abdul Basith
