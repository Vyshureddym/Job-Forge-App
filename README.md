JobForge – AI-Powered Resume & Cover Letter Generator

Project Overview

JobForge is a Generative AI-based web application that helps job seekers automatically generate optimized resumes, ATS-friendly content, and personalized cover letters based on job descriptions. The system uses LLM integration to analyze job requirements and produce tailored outputs to improve hiring chances.

 Problem Statement:
 
Match their resume to job descriptions
Create personalized cover letters
Pass ATS (Applicant Tracking Systems)
JobForge solves this by:
Extracting job requirements
Generating tailored resume bullets
Creating AI-driven cover letters

 Key Features:
 
 User Authentication (JWT-based)
 Resume Data Input Form
 Job Description Analysis
 AI-generated Resume Content
 AI-generated Cover Letter
 ATS Optimization Suggestions
 Full Stack Architecture (Frontend + Backend)
 Deployed using Render
 
 How This Will Works:
 
1️ User logs in

2️ Enters job description

3️ Provides personal and skill details

4️ Backend processes request

5️  LLM generates:

Optimized resume points
Customized cover letter

6️  Response sent back to frontend

System Architecture:


Frontend (HTML/CSS/JS)
        ↓
FastAPI Backend
        ↓
LLM API (OpenAI)
        ↓
Generated Response

Tech Stack

Backend:

Python
FastAPI
JWT Authentication
SQL (Database)
OpenAI API

Frontend:
HTML
CSS
JavaScript

Deployment:

Render
Docker

Project Structure

jobforge-backend/
jobforge-frontend/
Dockerfile
requirements.txt
README.md

 API Endpoints

POST /login
POST /register
POST /generate-resume
POST /generate-cover-letter
GET /health

Authentication:

Implemented JWT token-based authentication
Secured protected routes
Used HTTP-only cookies for secure token handling

Sample Workflow

Input:

Job Description
Skills
Experience

Output:

ATS-optimized resume bullet points
AI-generated tailored cover letter

Improvements & Contributions By Me:

Integrated OpenAI API for dynamic content generation
Implemented secure JWT-based authentication
Designed backend API architecture
Improved prompt engineering for better LLM responses
Added deployment configuration using Docker & Render
Enhanced UI structure for better user experience

Challenges Faced:

Handling token security (JWT expiration)
Structuring prompts for accurate AI responses
Managing frontend-backend communication
Deploying backend with proper environment variables

Future Enhancements:

Multi-job comparison
Resume PDF download
User dashboard with history
AI resume scoring system
Multi-language support

What I Learned :

Generative AI integration in real-world apps
Prompt engineering techniques
Full stack development with FastAPI
Authentication and API security
Cloud deployment

Author : 
VYSHU REDDY


