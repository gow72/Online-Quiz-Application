Online Quiz Application (Java Backend)
This is a Java-based backend project for an Online Quiz Application, built using JDBC and MySQL. It supports user authentication, quiz creation, question management, quiz attempts, scoring, and leaderboard tracking.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✅ Features
User registration and login with password hashing
Quiz creation, updating, and deletion
Add questions and options to quizzes
Record user attempts and calculate scores
Leaderboard and quiz history tracking

JDBC-based MySQL database integration
🛠 Technologies Used
Java (Core)
JDBC (Database connectivity)
MySQL (Database)
Git (Version control)
📁 Project Structure
quiz-app-backend/
├── DBConnection.java
├── UserDAO.java
├── QuizDAO.java
├── QuestionDAO.java
├── AttemptDAO.java
├── LeaderboardDAO.java
├── schema.sql       # MySQL schema
└── README.md
🗃️ Database Schema
The schema includes:

users: Stores user credentials
quizzes: Quiz details
questions: Questions for each quiz
options: Options for each question
quiz_attempts: Stores attempts per user
attempt_details: Tracks user answers
leaderboard: (Optional) Tracks top scorers
Full schema is in the schema.sql file

🚀 How to Run
Clone the repository:

git clone https://gow72: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 github.com/gow72/Online-Quiz-Application
cd Online-Quiz-Application
Import into your Java IDE (e.g. IntelliJ, Eclipse)
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
Setup MySQL:

Create a database quiz_app
Run schema.sql to generate tables
Configure DB credentials in DBConnection.java:

private static final String URL = "jdbc:mysql://localhost:3306/quiz_app";
private static final String USER = "root";
private static final String PASSWORD = "password";
Run the Java classes for testing functionalities

📧 Contact
For queries or collaboration: Gowtham Tulluri 📧 tullurigowtham294@gmail.com
