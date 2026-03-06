#  DeployZen – Automated Static Website Deployment on AWS

---

##  Project Overview

**DeployZen** is a cloud-based platform that simplifies **static website deployment** for students and developers.  

This project allows users to:  
- Upload a **ZIP file** or connect a **GitHub repository**  
- Automatically deploy websites on **AWS S3** using **Lambda**  
- Store project metadata in **DynamoDB**  
- Secure access with **Cognito**  
- Showcase deployed projects through **ZenHub**  

By combining AWS services with a Flask-powered backend, DeployZen removes the complexity of cloud setup and provides a **fast, secure, and beginner-friendly deployment solution**.  

---

##  Technologies Used

- **Amazon EC2** – Hosting Flask backend  
- **Amazon S3** – File storage & static site hosting  
- **AWS Lambda** – Automated unzipping & hosting logic  
- **Amazon DynamoDB** – Metadata storage for deployments  
- **Amazon Cognito** – User authentication (signup/login)  
- **Amazon Lex** – Chatbot integration for deployment guidance  
- **Flask (Python)** – Backend framework  
- **HTML + Tailwind CSS** – Frontend user interface  
- **UUID (Python)** – Short URL generation  

---

##  Architecture

**This workflow includes:**
- Cognito for secure login/signup  
- Flask backend hosted on EC2  
- S3 buckets for storing & hosting static sites  
- Lambda function to automate unzipping and hosting  
- DynamoDB to store metadata (IDs, URLs, filenames)  
- ZenHub for public showcase of projects  
- Lex chatbot to assist beginners step by step  

---

##  Setup Steps

The **complete deployment instructions** with screenshots are provided in this PDF:  

📄 [`deployment-guide.pdf`](./Project_Documentation.pdf)

High-level setup includes:  
1. Launch EC2 instance & deploy Flask backend  
2. Design frontend with HTML + Tailwind CSS + JS
3. Configure S3 buckets for storage & static hosting  
4. Setup DynamoDB tables for metadata storage  
5. Create Lambda functions to automate hosting  
6. Enable Cognito authentication & email verification  
7. Add Lex chatbot for user assistance  
8. Publish deployed projects to ZenHub showcase  

---

##  Key Takeaways

- Built an **automated static website deployment pipeline**  
- Gained hands-on with **AWS integration** (EC2, S3, Lambda, DynamoDB, Cognito, Lex)  
- Implemented **secure authentication** using Cognito  
- Enhanced usability with **Lex chatbot assistance**  
- Delivered a **scalable, beginner-friendly hosting solution**  
