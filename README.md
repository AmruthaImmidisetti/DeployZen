🚀 DeployZen – Automated Static Website Deployment on AWS
🔒 Project Overview

DeployZen is a cloud-based platform that makes static website deployment fast and beginner-friendly.
It allows users to:

Upload a ZIP file or connect a GitHub repository

Automatically deploy websites on AWS S3 using Lambda

Manage metadata with DynamoDB

Secure access with Cognito

Showcase deployed projects through ZenHub

This project removes the complexity of cloud setup and enables quick, automated deployment using a simple Flask-powered web interface.

☁️ Technologies Used

Amazon EC2 – Flask backend hosting

Amazon S3 – File storage & static site hosting

AWS Lambda – Automated deployment logic

Amazon DynamoDB – Deployment metadata storage

Amazon Cognito – Authentication (signup/login)

Amazon Lex – Chatbot integration

Flask (Python) – Backend framework

HTML + Tailwind CSS – Frontend UI

UUID (Python) – Unique short URL generation

📐 Architecture & Workflow

📁 Architecture Diagram: architecture/deployzen-architecture.png

Deployment Workflow:

User uploads ZIP file or GitHub repo link

Flask backend stores data in S3 & DynamoDB

Lambda is triggered → unzips, creates bucket, hosts files

Cognito secures user sessions

Shortened URLs generated using UUID

Public projects are displayed in ZenHub Showcase

Lex Chatbot assists users with deployment steps

🔧 Setup Steps

The deployment guide is documented step-by-step with AWS screenshots in the PDF:

📄 deployment-guide.pdf

High-level steps:

Configure EC2 instance and Flask backend

Connect frontend templates with Tailwind

Integrate S3 & DynamoDB for storage

Setup Lambda triggers for deployment

Add Cognito authentication for secure access

Enable URL redirection and ZenHub Showcase

📸 Screenshots

📁 screenshots/

This folder includes UI and AWS proof:

Screenshot File	Description
home-page.png	Home page with deployment options
login.png	Cognito-based signup/login page
manual-deploy.png	ZIP upload deployment workflow
github-deploy.png	GitHub repo deployment workflow
s3-files.png	AWS S3 bucket with hosted files
dynamodb-table.png	Metadata records in DynamoDB
zenhub.png	Showcase of deployed projects
lex-chatbot.png	Chatbot assisting with deployment steps
✅ Key Takeaways

Gained practical knowledge of AWS service integration

Automated end-to-end static site deployment pipeline

Built secure authentication using Cognito

Improved user experience with Lex chatbot

Learned real-world cloud architecture automation
