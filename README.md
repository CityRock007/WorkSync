# WorkSync – Team Collaboration & Task Management Platform

**WorkSync** is a cloud-based collaboration and project management system designed to help teams plan, communicate, and execute tasks efficiently.  
It brings together messaging, file sharing, and progress tracking in a single unified workspace.

---

### 👥 Key Features
- Team & project creation  
- Task assignment and progress tracking  
- Real-time chat & mentions  
- File sharing and document uploads  
- Kanban-style project board  
- Deadline reminders and push notifications  
- Admin analytics and activity logs  

---

### 🧠 Tech Stack
| Layer | Technology |
|-------|-------------|
| **Frontend (Web + Mobile)** | Flutter |
| **Backend API** | Django REST Framework / Node.js |
| **Database** | PostgreSQL (AWS RDS) |
| **Storage** | AWS S3 |
| **Notifications** | Firebase Cloud Messaging / AWS SNS |
| **Hosting** | AWS Elastic Beanstalk / ReinHost VPS |

---

### 🧩 System Architecture
Teams → Flutter App (Web + Mobile)
│
│──> Backend (Django or Node.js)
│
│──> PostgreSQL Database (AWS RDS)
│
│──> Real-time Communication via Socket.IO
│
│──> AWS S3 for file uploads
│
└──> Notifications via Firebase / AWS SNS


---

### 🔒 Security & Access
- JWT-based authentication  
- Role-based access control (Admin, Manager, Team Member)  
- Secure file uploads  
- Data encryption in transit and at rest  

---

### 🧾 Status
**Concept build for portfolio demonstration.**  
WorkSync showcases modern team collaboration with cloud hosting, real-time messaging, and productivity analytics.

---

### 👨🏽‍💻 Developer
**James Friday**  
📧 jamesfriday007@gmail.com  
🌐 GitHub: [https://github.com/CityRock007](https://github.com/CityRock007)
