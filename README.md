# SWYNEX-Cloud-Architecture
Simple cloud architecture design for a web or API workload.

This repository contains the cloud architecture design for SWYNEX Technologies platform.

## 📁 Files in this Repo
- `README.md` - Project overview
- `architecture-notes.md` - Detailed notes of each layer
- `cloud-architecture.png` - Visual diagram of the architecture

## 🏗️ Architecture Overview
User -> Frontend (Vercel / AWS Amplify) -> API Gateway -> Backend (AWS Lambda) -> Database (RDS / DynamoDB) -> Response to User

## 🔒 Security & Monitoring
- HTTPS enabled
- Authentication for API
- CloudWatch for logs and monitoring

## Diagram
![Architecture](cloud-architecture.png)
