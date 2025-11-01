<!-- PROJECT LOGO -->
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/891/891462.png" alt="Logo" width="100" height="100">
</p>

<h1 align="center">🛍️ ECOMMERCE - Java Web Application</h1>

<p align="center">
  A fully functional <b>eCommerce Web Application</b> built with Java, Servlets, JSP, and Maven.  
  <br/>
  <a href="https://github.com/lelixn/ECOMMERCE"><strong>Explore the project »</strong></a>
  <br/>
  <br/>
  <a href="#features">Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#setup--installation">Setup</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#contact">Contact</a>
</p>

---

## 🧾 Overview

**ECOMMERCE** is a complete **Java-based web application** designed to simulate an online shopping experience.  
It includes both **user** and **admin** functionalities — customers can browse, add to cart, and order products, while admins can manage products and view orders.

This project demonstrates:
- 💡 Full-stack Java web development (Servlet + JSP + JDBC)
- 🧩 MVC architecture and database connectivity
- 🧠 Scalable design for learning or production deployment

---

## ✨ Features

| Category | Features |
|-----------|-----------|
| 🧑‍💻 User | Register/Login, Browse Products, Add to Cart, Place Orders, View Order History |
| 🛠️ Admin | Manage Products (Add/Edit/Delete), View All Orders, Manage Users |
| 💽 Database | Persistent MySQL/SQLite storage, user and order tracking |
| 🖥️ UI | Responsive web pages using HTML, CSS, JS |
| 🔐 Security | Basic authentication and session management |
| ⚙️ Build Tool | Maven project setup for easy dependency management |

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-------------|
| 💻 Frontend | HTML, CSS, JavaScript |
| ⚙️ Backend | Java Servlets, JSP |
| 🛢️ Database | MySQL / JDBC |
| 🧰 Build Tool | Maven |
| 🧑‍💼 IDE | Eclipse / IntelliJ |
| 🌐 Server | Apache Tomcat |

---

## 📂 Project Structure
```
├── src/
│ └── com/shashi/ # Java backend (servlets, database handlers)
├── WebContent/
│ ├── assets/ # CSS, JS, Images
│ ├── pages/ # JSP files
│ └── index.jsp # Homepage
├── databases/ # SQL scripts
├── pom.xml # Maven dependencies
└── README.md
```

---

## ⚡ Setup & Installation

### 🧩 Prerequisites
- ☕ **Java JDK** 8 or later  
- 🧱 **Maven** installed  
- 🐬 **MySQL Database** (or any JDBC-compatible DB)  
- 🚀 **Tomcat Server** (v9+ recommended)

---

### 🛠️ Installation Steps

```bash
# 1️⃣ Clone the repository
git clone https://github.com/lelixn/ECOMMERCE.git

# 2️⃣ Navigate into the project
cd ECOMMERCE

# 3️⃣ Build the project using Maven
mvn clean install
```

Run the Application
Run on Tomcat Server (Eclipse → Run as → Run on Server)
OR via terminal:
```
mvn tomcat7:run
```

🖼️ Screenshots

(You can replace the image links below with your own screenshots later.)

<p align="center"> <img src="https://github.com/lelixn/ECOMMERCE/assets/demo-home.png" width="80%" alt="Homepage Screenshot"/> <br/> <em>🛍️ Homepage — Clean and Responsive UI</em> </p> <p align="center"> <img src="https://github.com/lelixn/ECOMMERCE/assets/demo-admin.png" width="80%" alt="Admin Panel Screenshot"/> <br/> <em>🧑‍💼 Admin Dashboard — Manage Products & Orders</em> </p>

 Author
👤 Lelien Panda

This project is licensed under the MIT License — see the LICENSE
 file for details.
You’re free to use and modify it with proper credit.

<p align="center"> Made with ❤️ by <a href="https://github.com/lelixn">Lelien Panda</a> <br/> <sub>“Turning ideas into interactive experiences.”</sub> </p> 
