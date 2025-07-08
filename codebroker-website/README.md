## 🎥 Demo Videos & NDA Notice

> 📂 **Note**: Complete demo walkthroughs for this project are provided in the `videos/` folder.

Due to **NDA (Non-Disclosure Agreement) restrictions**, Iam  unable to share live hosted URLs or production deployments publicly. Therefore, all features are demonstrated using local system executions in the video walkthroughs.

I respectfully request you to refer to these demo videos for a complete understanding of the project’s functionality, architecture, and deployment behavior.

Thank you for your consideration and understanding.



## 🎯 Project Purpose

> **Centralized License Management**  
Built a secure API system to manage software licenses for client Django projects.

> **Prevents Unauthorized Use**  
Ensures only authorized clients can access protected features.

---

## ⚙️ Key Features (with Brief Explanations)

### 🧱 Modular Django Architecture
- `api` app handles all licensing logic
- Clean separation of **models**, **serializers**, **views**, and **admin**

### 🧾 Comprehensive Models
- **Client**: Stores user and device info
- **Project**: Represents licensed software
- **LicenseRequest**: Tracks requests and approval status
- **License**: Manages license keys, activation, and revocation

### 🔐 Secure Endpoints
- **License Validation**: Uses HMAC signatures for request integrity
- **Critical Operations**: API key authentication for sensitive actions

### 🛠️ Admin Dashboard
- Manage clients, projects, requests, and licenses via Django Admin
- **Revoking a license** automatically notifies the client by email

### 🚀 Deployment-Ready
- Configured for **Namecheap cPanel** hosting
- Uses `.env` files for secret management and environment variables

### 🔒 Security Best Practices
- Enforces **HTTPS**, secure cookies, and environment-based secrets
- **Rate limiting** and logging to prevent abuse

---

## 🧰 Tech Stack

- **Backend**: Django (REST Framework)
- **Database**: MongoDB
- **Deployment**: GitHub Actions, cPanel
- **Security**: HMAC, HTTPS, JWT, Email Alerts

---
