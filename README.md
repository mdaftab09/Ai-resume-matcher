# Agentic Ai resume analyzer
# PROJECT ARCHITECTURE

React (UI)
   |
   |  REST API
   v
Spring Boot (Java)
   |
   |  AI API (OpenAI / HuggingFace)
   v
AI Service

-------------------------------------------------

# Frontend Structure
resume-analyzer-frontend/
 ├── src/
 │    ├── App.js
 │    └── index.js

-------------------------------------------------

# Backend Folder Structure

resume-analyzer-backend/
 ├── src/main/java/com/example/resumeanalyzer
 │    ├── controller
 │    │    └── ResumeController.java
 │    ├── service
 │    │    └── ResumeAnalysisService.java
 │    ├── dto
 │    │    └── ResumeRequest.java
 │    ├── dto
 │    │    └── ResumeResponse.java
 │    └── ResumeAnalyzerApplication.java
 └── application.properties

-------------------------------------------------

# HOW TO RUN

Front-end
mvn spring-boot:run

Back-end
npm install
npm start

