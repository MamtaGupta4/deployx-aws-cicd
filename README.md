# 🚀 DeployX - AWS CI/CD Pipeline

This project demonstrates an end-to-end CI/CD pipeline using AWS DevOps services.

The application code is integrated using AWS CodeCommit, built with AWS CodeBuild, and deployed automatically to an EC2 instance using AWS CodeDeploy and NGINX.

---

## 🛠️ Services Used

- AWS CodeCommit
- AWS CodeBuild
- AWS CodeDeploy
- Amazon EC2
- Amazon S3
- IAM
- NGINX

---

## ⚙️ Tech Stack

- Linux / Ubuntu
- Shell Scripting
- Git & GitHub
- HTML & CSS
- VS Code

---

## 🚀 Workflow

1. Push code to CodeCommit  
2. Build triggered using CodeBuild  
3. Artifacts stored in S3  
4. Deployment handled using CodeDeploy  
5. Application hosted on EC2 with NGINX  

---

## 📂 Project Structure

```bash
├── appspec.yml
├── buildspec.yml
├── index.html
├── scripts/
│   ├── install_nginx.sh
│   └── start_nginx.sh
└── README.md
```
---

## 👩‍💻 Author

Mamta Gupta  
AWS & DevOps Enthusiast

---

## 🌐 Deployment

Successfully deployed a static web application on Amazon EC2 using AWS CodeDeploy and NGINX.
