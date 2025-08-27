# 📘 Online Quiz Application (Java Backend)

This is a **Java-based backend project** for an **Online Quiz Application**, built using **JDBC** and **MySQL**.  
It supports **user authentication**, **quiz creation**, **question management**, **quiz attempts**, **scoring**, and **leaderboard tracking**.

---

## ✅ Features
- 🔐 **User Authentication**: Registration and login with password hashing  
- 📝 **Quiz Management**: Create, update, and delete quizzes  
- ❓ **Question Handling**: Add questions and multiple-choice options  
- 🧩 **Quiz Attempts**: Record user attempts and calculate scores  
- 🏆 **Leaderboard**: Track top scorers and quiz history  
- 🗄️ **Database Integration**: JDBC-based MySQL connectivity  

---

## 🛠 Technologies Used

| Technology   | Purpose               |
|-------------|------------------------|
| **Java**   | Core backend logic    |
| **JDBC**   | Database connectivity |
| **MySQL**  | Database management   |
| **Git**    | Version control       |

---

## 📁 Project Structure
```bash
quiz-app-backend/
├── DBConnection.java       # Database connection utility
├── UserDAO.java           # Handles user-related database operations
├── QuizDAO.java           # Handles quiz CRUD operations
├── QuestionDAO.java       # Manages quiz questions and options
├── AttemptDAO.java        # Tracks user quiz attempts
├── LeaderboardDAO.java    # Manages leaderboard data
├── schema.sql             # MySQL database schema
└── README.md              # Project documentation
```

---

## 🗃️ Database Schema

The schema includes:

- `users` → Stores user credentials  
- `quizzes` → Quiz details  
- `questions` → Questions for each quiz  
- `options` → Options for each question  
- `quiz_attempts` → Stores attempts per user  
- `attempt_details` → Tracks user answers  
- `leaderboard` *(Optional)* → Tracks top scorers  

> Full schema is available in the **`schema.sql`** file.

---

## 🚀 How to Run the Project

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/gow72/Online-Quiz-Application.git
cd Online-Quiz-Application
```

### **2️⃣ Import into IDE**
- Open **IntelliJ IDEA** or **Eclipse**
- Import the project as an **Existing Java Project**

### **3️⃣ Setup MySQL Database**
```sql
CREATE DATABASE quiz_app;
```
- Run **`schema.sql`** to create all tables.

### **4️⃣ Configure Database Credentials**
Edit **`DBConnection.java`** and update your credentials:
```java
private static final String URL = "jdbc:mysql://localhost:3306/quiz_app";
private static final String USER = "root";
private static final String PASSWORD = "your_password";
```

### **5️⃣ Run the Application**
```bash
javac *.java
java Main
```
Or simply run the main classes directly from your IDE.

---

## 📧 Contact

**Author:** Gowtham Tulluri  
📩 **Email:** tullurigowtham294@gmail.com  

---

