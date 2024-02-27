# Welcome to the MQuiz !!

**--------DATABASE MYSQL---------**
### create database Authenticate;
### use Authenticate;

### CREATE TABLE user (
###     id INT AUTO_INCREMENT PRIMARY KEY,
###     name VARCHAR(255) NOT NULL,
###     username VARCHAR(255) NOT NULL UNIQUE,
###     password VARCHAR(255) NOT NULL
### );

### CREATE TABLE quiz_results (
###     id INT AUTO_INCREMENT PRIMARY KEY,
###     user_id VARCHAR(255) NOT NULL,
###     attempted_on DATETIME NOT NULL,
###     correct_answers INT NOT NULL,
###     total_questions INT NOT NULL,
###     FOREIGN KEY (user_id) REFERENCES user(username)
### );

**To execute python file run command- streamlit run "file path"**



