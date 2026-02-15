# YojanaMitra AI – System Design Document

## 1. Architecture Overview

The system follows a layered architecture:

User
↓
Presentation Layer (Web Dashboard UI)
↓
Application Layer (Flask Backend)
↓
Core Intelligence Layer (Eligibility & Dependency Engine)
↓
Data Layer (PostgreSQL Database)
↓
External Services (Government Portals, AWS Services)

---

## 2. Modules

### 2.1 Presentation Layer
- Responsive Web Dashboard
- Profile Forms
- Documentation & Scheme Modules

### 2.2 Application Layer
- API Layer
- Authentication Service
- Profile Service
- Documentation Service
- Scheme Service
- Redirect Controller

### 2.3 Core Intelligence Layer
- Eligibility Engine
- Dependency Mapping Engine
- Eligibility Scoring Module

### 2.4 Data Layer
- User Database
- Scheme Database
- Document Database
- User Document Status Table

---

## 3. AWS Deployment Architecture

- AWS EC2: Backend Hosting
- AWS RDS: Relational Database
- AWS S3: Frontend Hosting
- AWS Cognito: Authentication
- Amazon Transcribe: Voice Support (Optional)

---

## 4. Data Flow

1. User registers and completes profile
2. System evaluates eligibility
3. Dependency engine verifies document readiness
4. User redirected to official portal
5. All services deployed on AWS cloud infrastructure

---

## 5. Scalability & Future Enhancements

- Integration of ML-based eligibility prediction
- Multilingual NLP support
- Real-time scheme updates
- Expansion to national-scale deployment
