# YojanaMitra AI – Requirements Document

## 1. Project Overview
YojanaMitra AI is an AI-powered government scheme assistant designed to help citizens discover eligible schemes and required documentation based on their profile.

The system simplifies access to welfare programs using intelligent eligibility and dependency mapping.

---

## 2. Functional Requirements

### User Management
- User Registration with OTP verification
- Profile Completion (Age, Income, Category, Occupation)
- Secure Login & Session Management

### Documentation Module
- Apply for new government documents
- Document eligibility verification
- Dependency checks for required documents

### Scheme Module
- Scheme eligibility evaluation
- Eligibility scoring
- Required document verification
- Guided redirect to official government portals

### AI Component
- Rule-Based Eligibility Engine
- Document Dependency Mapping
- Eligibility Scoring Algorithm

---

## 3. Non-Functional Requirements

- Secure Authentication (AWS Cognito)
- Scalable Cloud Deployment (AWS EC2)
- Reliable Data Storage (AWS RDS)
- Mobile-first Responsive Design
- Secure API Communication

---

## 4. AWS Infrastructure

- Frontend hosted on AWS S3
- Backend deployed on AWS EC2
- Database managed using Amazon RDS
- Authentication via AWS Cognito
- Optional voice support via Amazon Transcribe
