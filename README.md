📘 Online Quiz Application (Java Backend)

This is a Java-based backend project for an Online Quiz Application, built using JDBC and MySQL.
It supports user authentication, quiz creation, question management, quiz attempts, scoring, and leaderboard tracking.

✅ Features

User Authentication: Registration and login with password hashing

Quiz Management: Create, update, and delete quizzes

Question Handling: Add questions and multiple-choice options

Quiz Attempts: Record user attempts and calculate scores

Leaderboard: Track top scorers and quiz history

Database Integration: JDBC-based MySQL connectivity

🛠 Technologies Used

Java (Core)

JDBC (Database connectivity)

MySQL (Database)

Git (Version control)

📁 Project Structure
quiz-app-backend/
├── DBConnection.java       # Database connection utility
├── UserDAO.java           # Handles user-related database operations
├── QuizDAO.java           # Handles quiz CRUD operations
├── QuestionDAO.java       # Manages quiz questions and options
├── AttemptDAO.java        # Tracks user quiz attempts
├── LeaderboardDAO.java    # Manages leaderboard data
├── schema.sql             # MySQL database schema
└── README.md              # Project documentation

🗃️ Database Schema

The database contains the following tables:

Table Name	Description
users	Stores user credentials
quizzes	Stores quiz details
questions	Stores questions for each quiz
options	Stores multiple-choice options
quiz_attempts	Stores quiz attempt data per user
attempt_details	Tracks user answers per attempt
leaderboard	(Optional) Tracks top scorers

The complete schema is available in schema.sql.

🚀 How to Run the Project
1️⃣ Clone the Repository
```git clone https://github.com/gow72/Online-Quiz-Application.git
cd Online-Quiz-Application```

2️⃣ Import into IDE

Open IntelliJ IDEA or Eclipse

Import the project as an Existing Java Project

3️⃣ Setup MySQL Database
CREATE DATABASE quiz_app;


Run schema.sql to create tables.

4️⃣ Configure Database Credentials

Edit DBConnection.java:

private static final String URL = "jdbc:mysql://localhost:3306/quiz_app";
private static final String USER = "root";
private static final String PASSWORD = "your_password";

5️⃣ Run the Application
# Compile the project
javac *.java

# Run the main class
java Main


Or directly run the Java classes in your IDE to test features like quiz creation, question addition, attempts, and leaderboard.

📧 Contact

Author: Gowtham Tulluri
📩 Email: tullurigowtham294@gmail.com
