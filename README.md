# AIHealthcare
# 🏥 AI-Powered Healthcare & Smart Patient Assistance System

**VCUBE HACK QUEST 1.0 | Problem 2 – Healthcare**

An intelligent healthcare platform designed to connect patients, doctors, and hospitals through digital healthcare management and AI-powered assistance.

Our platform aims to simplify healthcare management by providing appointment booking, medical history management, medical report uploads, and AI-powered medical report summarization.

---

## 📌 Project Overview

The AI-Powered Healthcare & Smart Patient Assistance System is a web-based application that helps patients manage their healthcare information and interact with doctors more efficiently.

The system integrates Artificial Intelligence to help users understand medical reports, explain medical terminology, provide general healthcare information, and prepare for doctor appointments.

**Important:** The AI assistant is designed only for informational and assistance purposes. It does not independently diagnose diseases or prescribe medication.

---

## 🎯 Key Features

### 👤 User Management
- Patient registration and login.
- Doctor registration and login.
- Role-based access for patients, doctors, and administrators.
- Secure authentication and authorization.

### 🩺 Doctor Management
- Doctor profile creation and management.
- View doctor information and availability.
- Manage patient appointments.

### 📅 Appointment Management
- Book doctor appointments.
- View appointment details.
- Manage appointment status.

### 📂 Medical History Management
- Maintain patient medical history.
- Upload and manage medical reports.
- Access relevant medical information.

### 🤖 AI-Powered Features
1. **Medical Report Summarizer** – Summarizes uploaded medical reports into understandable information.
2. **Healthcare Information Assistant** – Provides general healthcare-related information.
3. **Medical Terminology Explainer** – Explains complex medical terms in simple language.
4. **Appointment Preparation Suggestions** – Suggests relevant questions and preparation points before doctor appointments.

---

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React.js |
| Backend | Java, Spring Boot |
| ORM | Spring Data JPA, Hibernate |
| Security | Spring Security |
| Database | MySQL |
| API | REST APIs |
| AI Integration | Spring AI / Compatible LLM API |
| API Testing | Postman |
| Version Control | Git & GitHub |
| Deployment | Render / Suitable Cloud Platform |

---

## 🗄️ Database Design

The project uses MySQL with a minimum of five related tables.

| Table | Description |
|---|---|
| users | Stores user authentication and basic information |
| doctors | Stores doctor profiles and professional information |
| patients | Stores patient-specific information |
| appointments | Stores appointment details between patients and doctors |
| medical_reports | Stores uploaded medical report information |

---

## 🏗️ Project Architecture

The application follows a client-server architecture.

```text
              REACT FRONTEND
                    |
                    | REST API Requests
                    |
              SPRING BOOT
                    |
        +-----------+-----------+
        |           |           |
    Controllers  Services   Security
        |           |
        |       Repositories
        |           |
        +-----------+
                    |
                 MYSQL
                    |
             APPLICATION DATA

              SPRING BOOT
                    |
                SPRING AI
                    |
                LLM API
```

AI integration is handled through the Spring Boot backend, allowing AI features to use relevant application data where required.

---

## 📁 Project Structure

```text
AIHealthcare/
│
├── backend/
│   └── Spring Boot Application
│
├── frontend/
│   └── React Application
│
├── database/
│   └── Database Scripts
│
├── docs/
│   ├── ER-Diagram
│   └── API-Documentation
│
├── postman/
│   └── Postman Collection
│
├── README.md
└── .gitignore
```

*The directory structure may evolve as development progresses.*

---

## 🚀 Getting Started

### Prerequisites

Install the following tools before running the application:

- Java JDK
- Maven
- MySQL
- Node.js and npm
- Git
- Postman

### 1. Clone the Repository

```bash
git clone https://github.com/AustinSurya/AIHealthcare.git
```

```bash
cd AIHealthcare
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Configure your MySQL database and application properties.

Run the Spring Boot application using Maven:

```bash
mvn spring-boot:run
```

### 3. Frontend Setup

Navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

## 🧪 Testing

Postman will be used to test and validate backend REST APIs.

Testing will cover:

- User registration and authentication.
- Doctor profile management.
- Appointment booking.
- Medical history management.
- Medical report uploads.
- AI feature integration.
- API validation and error handling.

---

## 🔐 Security Considerations

- Secure user authentication.
- Role-based authorization.
- Protected patient information.
- Backend validation of incoming requests.
- AI responses must not independently diagnose or prescribe medication.

---

## ☁️ Deployment

The application is intended to be deployed with:

- Live React frontend.
- Live Spring Boot backend.
- Production MySQL database.
- Configured AI API integration.

Deployment URLs will be added after successful deployment.

---

## 👥 Team Members

| Role | Member |
|---|---|
| Team Lead | To be updated |
| Backend Developer | To be updated |
| Frontend Developer | To be updated |
| AI Integration Developer | To be updated |
| Integration & QA Engineer | Austin Surya |

---

## 📋 Project Deliverables

- [ ] Functional web application.
- [ ] Spring Boot backend with REST APIs.
- [ ] React responsive frontend.
- [ ] MySQL database with minimum five related tables.
- [ ] AI-powered healthcare features.
- [ ] Database ER diagram.
- [ ] Postman API collection.
- [ ] Live application deployment.
- [ ] Final project demonstration.

---

## 🤝 Contribution Guidelines

We welcome contributions from all team members.

1. Clone the repository.
2. Create a separate feature branch.
3. Make changes related to your assigned task.
4. Commit changes with meaningful commit messages.
5. Push your branch to GitHub.
6. Create a Pull Request for review.
7. Merge changes after review and approval.

### Branch Naming Convention

```text
main
develop
feature/backend-setup
feature/frontend-setup
feature/ai-integration
feature/database
bugfix/issue-description
```

### Commit Message Convention

```text
feat: add patient registration API
fix: resolve appointment booking issue
docs: update project README
test: add user registration test cases
refactor: improve service layer
```

---

## 📄 License

This
