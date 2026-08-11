🎨 Romee Sketch Art

A deliberately vulnerable pencil sketch e-commerce web application built for cybersecurity assignment demonstrating 30+ real-world vulnerabilities.

🔗 Live Demo
🌐 [romeesketchart.infinityfreeapp.com](http://romeesketchart.infinityfreeapp.com)

🛠 Tech Stack
**Frontend:** HTML5, CSS3, JavaScript (Vanilla)
**Backend:** PHP 8
**Database:** MySQL (MariaDB)
**Hosting:** InfinityFree
**Lines of Code:** 2,690+

📌 Features
🖼️ Dynamic sketch gallery with filtering (Portrait, Anime Art, Close-Up Sketch)
🛒 Buy sketches & custom order with pricing plans
👤 User authentication (Register/Login/Dashboard)
🛡️ Admin panel with full CRUD operations
📸 Multi-image upload with carousel view
📱 Fully responsive dark theme
 🔒 Change password functionality

⚠️ Vulnerabilities Demonstrated (30+)

| Category | Vulnerability |
|----------|--------------|
| **Authentication** | Hardcoded credentials, weak password policy, plaintext passwords, no brute-force protection, username enumeration |
| **Authorization** | Broken access control, IDOR, missing authentication checks, mass assignment |
| **Input Validation** | Price manipulation via URL/forms, XSS (stored), SQL injection, unrestricted file upload |
| **Data Exposure** | Plaintext passwords in DB, sensitive data in admin panel, information disclosure |
| **Session Management** | localStorage sessions, no expiry, no HttpOnly/Secure flags |

📂 Project Structure
