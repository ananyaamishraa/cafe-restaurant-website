# Cafe & Restaurant Website – DevOps Deployment

This project is a simple static Cafe & Restaurant website deployed on an AWS EC2 instance using Nginx as a web server.  
The purpose of this project is to demonstrate basic DevOps skills including cloud provisioning, web server setup, and deployment.

---

## 🚀 Tech Stack

- Frontend: HTML, CSS
- Web Server: Nginx
- Cloud Platform: AWS EC2 (Ubuntu 24.04)
- Version Control: Git & GitHub

---

## 📦 Project Features

- Responsive static website
- Hosted on AWS EC2
- Served using Nginx
- Publicly accessible via EC2 Public IP

---

## 🛠️ Deployment Steps

1. Launched an EC2 instance (Ubuntu 22.04) on AWS.
2. Configured Security Group to allow:
   - SSH (22)
   - HTTP (80)
3. Connected to the instance using SSH.
4. Installed Nginx web server.
5. Cloned the GitHub repository into `/var/www/html`.
6. Configured permissions for Nginx.
7. Restarted Nginx to serve the website.

---

## 🌐 Live URL

http://35.154.48.164 

---

## 📁 Repository Structure

```
cafe-restaurant-website/
├── index.html
├── css/
│   └── style.css
└── README.md
```

---

## 👩‍💻 Author

Ananya Mishra  
DevOps Intern Applicant



