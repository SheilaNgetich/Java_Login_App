# 🌸 Java Login App 🌼
🌸 A simple Java Swing login application with MySQL authentication and a cozy Home Page — perfect for beginners learning Java GUI &amp; database integration! 💻💖

## ✨ Description

The **Java Login App** is designed to help users **safely log in** to a system using a registered username and password. With its soft colors and **Comic Sans MS** font, this app brings a warm, welcoming experience to user authentication. 🎀

It includes a **Home Page** that users are redirected to after a successful login — making it ideal for personal desktop apps, admin portals, or beginner Java projects that need a login feature.

## 💫 Features

- 🔐 **Secure login system** using MySQL database  
- 🎨 **Friendly UI** with Comic Sans MS font and soft purple tones  
- 📛 Reset button to clear the fields instantly  
- 🎯 Instant feedback for incorrect login attempts  
- 🏠 Redirects to a cozy **Home Page** after successful login  

## 🖼️ Screenshots

## 📸 Screenshots

- **Login Page**  
  ![Login Page](https://github.com/SheilaNgetich/Java_Login_App/blob/main/loginPage.png)

- **Successful login to Home Page**  
  ![Successful login to Home Page](https://github.com/SheilaNgetich/Java_Login_App/blob/main/successfulLogin.png)

- **Home Page**  
  ![Home Page](https://github.com/SheilaNgetich/Java_Login_App/blob/main/homePage.png)

## 🛠️ Tech Stack

- **Java Swing** (for GUI)  
- **JDBC + MySQL** (for backend authentication)  
- **NetBeans IDE** (for development)  
- **Comic Sans MS** font 💅  

## ⚙️ How to Run

1. 💾 **Clone this repository**:
   ```bash
   git clone https://github.com/SheilaNgetich/Java_Login_App.git
   2. **Open the project** in NetBeans IDE.

3. Make sure your **MySQL server** is running.

4. Create a database named `java_user_database` and a table called `login` with the following structure:

   ```SQL
   CREATE DATABASE java_user_database;

   USE java_user_database;

   CREATE TABLE login (
       id INT PRIMARY KEY AUTO_INCREMENT,
       username VARCHAR(50),
       password VARCHAR(50)
   );

   INSERT INTO login (username, password) VALUES ('admin', 'admin123');
5. Run the LoginPage.java file in NetBeans.

6. Enter the correct credentials (e.g., admin / admin123) to log in and access the Home Page! 🏡

## 📌 Notes
This app uses plain text passwords — for production, consider implementing password hashing like BCrypt.

The HomePage opens after login — you can customize it to suit your project’s needs! 🏡

## 💖 Author
Developed with love by **Sheila** 💻🌷
If you found this helpful, feel free to ⭐ the repo or share your version!

