# VotingApp
A full-stack voting application that allows users to cast votes on different options and view real-time results. This project demonstrates the integration of Java (JSP/Servlets) with a MySQL database, providing a clean example of a CRUD-based web application.

---

## 📸 Preview

<img width="1920" height="877" alt="screencapture-localhost-8080-2026-04-17-13_35_07" src="https://github.com/user-attachments/assets/7cf085a9-a8aa-4481-83b5-f60597a13f7e" />

<img width="1920" height="904" alt="screencapture-localhost-8080-register-2026-04-17-13_35_15" src="https://github.com/user-attachments/assets/ec28c031-794a-47b2-80b8-62968c5f70a7" />

<img width="1920" height="877" alt="screencapture-localhost-8080-user-2026-04-17-13_38_34" src="https://github.com/user-attachments/assets/8e5a9726-e976-4315-b51f-8498c8ec0239" />

---

## 🚀 Features  

- ✅ User-friendly voting interface  
- ✅ Admin panel to manage polls & results  
- ✅ Real-time vote counting and display  
- ✅ Secure database storage with MySQL  
- ✅ Modular JSP pages with reusable header & footer  
- ✅ Responsive UI with Bootstrap

---

## 🛠️ Tech Stack  

- **Frontend:** JSP, HTML5, CSS3, Bootstrap  
- **Backend:** Java Servlets, JSP  
- **Database:** MySQL  
- **Server:** Apache Tomcat

---

## 📂 Project Structure  

VotingApp/
│── src/ # Java source files (Servlets, Database connection)
│── WebContent/ # JSP pages, CSS, JS, images
│ ├── index.jsp # Landing page
│ ├── categories.jsp # Poll categories
│ ├── results.jsp # Voting results
│ └── WEB-INF/ # web.xml configuration
│── sql/ # SQL scripts for DB setup
│── lib/ # Dependencies (MySQL Connector, etc.)
└── README.md # Project documentation

---

## ⚙️ Installation & Setup  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/iamvikash28/VotingApp.git
cd VotingApp
```

2️⃣ Import into IDE
- Open Eclipse / IntelliJ
- Select Import as Dynamic Web Project
- Configure Apache Tomcat as your server

3️⃣ Setup MySQL Database
- Create a new database:
```bash
CREATE DATABASE votingapp;
```

- Import tables from sql/votingapp.sql
- Update your DB credentials in DBConnection.java:
```bash
private static final String URL = "jdbc:mysql://localhost:3306/votingapp";
private static final String USER = "root";
private static final String PASSWORD = "your_password";
```

4️⃣ Run the Application

- Deploy on Tomcat server
- Open in browser:
```bash
http://localhost:8080/VotingApp
```

---

🎯 Usage

👤 User:
- View categories of polls
- Cast votes
- See live results

🛠️ Admin:
- Add new categories
- Manage polls
- View statistics

---
📌 Future Enhancements

- 🔐 User authentication & login system
- 📊 Graphical representation of results
- 🌐 Multi-language support
- 📱 Mobile-friendly responsive UI

---
## 👤 Author

**Vikash Verma**
Aspiring Data Analyst | Excel · SQL · Power BI · Python | E-mail- vikashverma566@gmail.com

---
