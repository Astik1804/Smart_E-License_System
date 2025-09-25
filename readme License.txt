# Smart-E-License System  

A smart, digital driving license issuance system designed to modernize and streamline the entire driving license workflow.

---

## ✅ Author & Creator

**[Your Name]**  
I conceived, designed, and implemented this project to address inefficiencies in the traditional licensing process. As the sole / lead developer, I oversaw all aspects — from architecture and design to coding, testing, and deployment.

You can reach me at: **your_email@example.com**  

---

## 📘 Project Overview

Smart-E-License System is an integrated, technology-driven solution for managing learner’s and permanent driving licenses. It replaces paper-based processes with digital automation.

Key goals:

- Reduce manual workload and errors  
- Speed up license issuance  
- Improve transparency for applicants  
- Centralize administrative operations  

---

## 🛠️ Features & Functionality

### User / Applicant Side

- **User Registration** — Applicants register and receive a unique learner ID to begin the licensing process.  
- **Testing Module** — Includes both computer-based and practical driving tests.  
- **License Issuance** — After passing all required stages, applicant gets learner’s license and then permanent license.  
- **Notifications** — Status updates and test results are sent via digital notifications (e.g. via SMS).  

### Administrative Side

- **Admin & Operator Dashboards** — Separate interfaces for system operators and administrators.  
- **Manage Users / Operators** — Add, update, delete system operators; view driver records.  
- **Manage Tests / Questions** — Add or remove test symbols/questions; configure test flow.  
- **Approval Workflow** — Review and approve license issuance.  

---

## 🧩 System Workflow

1. **Registration** — User signs up and receives a learner ticket / ID.  
2. **Learner License Phase** — The system issues a learner’s license valid for 6 months, given all prerequisites are met.  
3. **Symbol / Practice Test** — After ~41 days, the user can attempt a symbol/practical test.  
4. **Driving Test Phase** — Computer + practical tests are conducted.  
5. **Permanent License** — If tests are passed, the permanent license — valid for 5 years — is issued.  
6. **Notifications** — Throughout the process, the user receives status updates and results electronically.  

---

## 💻 Tech Stack & Tools

- **Language**: Java  
- **UI / Desktop**: JavaFX  
- **Database**: MongoDB  
- **SMS / Notifications**: Infobip (or equivalent SMS API)  
- **Build / Dependency Management**: Maven  

---

## 🚀 Setup & Running Instructions

1. Clone the repository to your local machine.  
2. In `DataBase.java`, put your MongoDB connection string / URL.  
3. In `sms.java`, configure your SMS / notification API keys.  
4. Run `AddAdmin.java` (in `src/main/java/Admin/`) to create your first administrator.  
5. Then run either `AdminLogin.java` (in `src/main/java/Admin/`) or the `LicenseMain` test entry point.  
6. Within the admin panel, add system operators, configure tests, etc.  

---

## ⚙️ Administration & Operator Functions

- **Admin Functions**  
 – Add / remove / update system operators  
 – View or delete operator records  
 – Add / remove / update test symbols or questions  

- **Operator (System) Functions**  
 – Access license test forms  
 – Input driver / applicant info  
 – Conduct symbol / practical tests  
 – Update license status / driver profiles  

---

## 🌐 Project Impact & Significance

This project is a stepping stone toward a **paperless, digitized licensing system** — reducing administrative burden and increasing accessibility for all users. It demonstrates how modern tools (Java, MongoDB, JavaFX, SMS APIs) can be combined to build a full-featured application with real-world utility.

---

## 📂 Repository Structure (Example)

├── src/
│ ├── Admin/
│ ├── Driver/
│ ├── UI/
│ ├── sms.java
│ └── DataBase.java
├── README.md
├── LICENSE
├── .gitignore
├── JAVA PRESENTATION.pptx
└── mongo.iml


---

## 🤝 Contributions & Collaboration

I welcome contributions! If you have ideas to improve or extend this system—new features, UI enhancements, security updates—feel free to open issues or submit pull requests.

---

## 📄 License

This project is licensed under the **GPL-3.0** (or modify to your chosen license).  

---

## 📬 Contact & Acknowledgments

Developed by Astik Kushwaha.  
Contact: astikkushwaha30@gmail.com  

Special thanks to any collaborators, mentors, or libraries used.

---

