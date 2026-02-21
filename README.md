# 🤖 Agentic AI Resume Analyzer

An AI-powered Resume Analyzer built using:

- ⚛️ React (Frontend)
- ☕ Spring Boot (Backend)
- 🤖 OpenAI / HuggingFace (AI Service)

---

## 🏗️ Project Architecture

React (UI)
│
│ REST API
▼
Spring Boot (Java)
│
│ AI API (OpenAI / HuggingFace)
▼
AI Service

---

## 📁 Frontend Structure
resume-analyzer-frontend/
├── src/
│ ├── App.js
│ └── index.js


---

## 📁 Backend Structure


resume-analyzer-backend/
├── src/main/java/com/example/resumeanalyzer
│ ├── controller
│ │ └── ResumeController.java
│ ├── service
│ │ └── ResumeAnalysisService.java
│ ├── dto
│ │ ├── ResumeRequest.java
│ │ └── ResumeResponse.java
│ └── ResumeAnalyzerApplication.java
└── application.properties


---

## 🚀 How To Run

### 🔹 Backend
mvn spring-boot:run
### 🔹 Frontend
npm install
npm start
