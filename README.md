# 🩸 Smart Blood Connect – LPU

> **Donate Blood, Save Lives ❤️**

A Java-based web portal exclusively for **Lovely Professional University** campus community to connect blood donors and recipients — hostel-wise, fast, and secure.

![Java](https://img.shields.io/badge/Java-JSP%2FServlet-red?style=flat-square&logo=java)
![MySQL](https://img.shields.io/badge/Database-MySQL-blue?style=flat-square&logo=mysql)
![Tomcat](https://img.shields.io/badge/Server-Apache%20Tomcat-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow?style=flat-square)

---

## 📌 About the Project

Smart Blood Connect is a web-based blood donor portal designed exclusively for LPU students, faculty, and staff. It enables hostel-wise donor search, blood request management, and PDF certificate generation — all within the LPU campus ecosystem.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | Java (JSP / Servlet) |
| **Database** | MySQL |
| **Frontend** | HTML, CSS, JavaScript |
| **PDF Generation** | iText PDF Library |
| **IDE** | VS Code |
| **Server** | Apache Tomcat 10 |

---

## ✨ Features

- 🏠 **Hostel-wise donor search** — find donors in your hostel block instantly
- 🩸 **Blood group database** — structured donor registry for LPU users only
- 📋 **Blood request system** — pending → approved workflow
- 🏥 **Emergency hospital access** — admin-controlled access for nearby hospitals
- 📜 **PDF certificate generation** — downloadable donor certificate
- 👨‍💼 **Admin dashboard** — manage donors, requests, and events
- 📢 **Campus Hospital awareness** — seminars and events via UMS notifications

---

## 📁 Project Structure

```
SmartBloodConnect/
├── src/com/smartblood/
│   ├── model/          # Donor.java, Request.java
│   ├── dao/            # DBConnection.java, DonorDAO.java, RequestDAO.java
│   └── servlet/        # RegisterServlet, SearchServlet, AdminApproveServlet
├── WebContent/
│   ├── WEB-INF/lib/    # MySQL connector, iText JAR
│   ├── css/style.css
│   ├── index.jsp       # Home page
│   ├── register.jsp    # Donor registration
│   ├── search.jsp      # Search donors
│   ├── request.jsp     # Request blood
│   └── admin.jsp       # Admin dashboard
```

---

## ⚙️ How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/smart-blood-connect.git
   ```

2. **Set up the database**
   - Open MySQL and run the SQL file provided in `/database/schema.sql`

3. **Configure DB credentials**
   - Open `src/com/smartblood/dao/DBConnection.java`
   - Update `USER` and `PASS` with your MySQL credentials

4. **Add JAR files** to `WebContent/WEB-INF/lib/`
   - `mysql-connector-j-8.x.x.jar`
   - `itextpdf-5.5.13.jar`

5. **Run on Apache Tomcat 10**
   - Open in VS Code → Run on Server → Tomcat 10

6. **Open in browser**
   ```
   http://localhost:8080/SmartBloodConnect/
   ```

---

## 👥 Team Members

| Name |  Role |
|------|------|
| Sunny Kumar | Frontend + UI |
| Podugu Avinash | Backend + Database |
| Medabalini Sai Koti | Servlets + Testing |

---

## 🏫 University

**Lovely Professional University**, Phagwara, Punjab
MCA – Java Subject Project | 2025–26
