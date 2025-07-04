# 🗳️ CloudVote – AWS-Powered Voting Application

CloudVote is a fully serverless, scalable voting application designed using modern cloud-native architecture. It features two responsive Single Page Applications (SPAs) for users and administrators, along with three backend services that handle voting logic, results processing, and authentication. The system leverages AWS infrastructure to ensure high availability, low latency, and seamless deployment.

---

## 🌐 Features

- Cast and record votes in real-time
- View live voting results
- Admin dashboard for managing polls
- Stateless, scalable backend using serverless functions
- Simple, cost-efficient architecture using AWS-managed services

---

## 🧰 Tech Stack

### Frontend
- **JavaScript (React.js)** – For building dynamic, responsive SPAs
- **AWS S3** – Static site hosting for both frontends
- **AWS CloudFront** (optional) – CDN for faster global delivery

### Backend
- **Python** – Core language for backend services
- **AWS Lambda** – Serverless compute for handling requests
- **AWS API Gateway** – Public endpoints for frontend-backend communication

### Processing
- **AWS EC2** – (Optional) for long-running vote processing logic
- *(Can be replaced with serverless alternatives like AWS SQS + Lambda)*

### Deployment & Infrastructure
- **AWS CLI / GitHub** – Deployment and version control
- **IAM Roles, CORS, API Gateway Stages** – Access control and routing

---

## ✅ Usage Scenarios

- Polling systems for online surveys
- Scalable internal voting systems (e.g., employee feedback)
- Real-time audience participation tools

---

Feel free to clone, modify, and deploy the project to suit your own voting use case.
