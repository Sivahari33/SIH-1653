# Smart India Hackathon Workshop
# Date:
## Register Number:
## Name:
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The Intelligent Interview Management System (IIMS) streamlines the interview process, makes it fairer, and efficient by employing AI to generate applicable questions, analyze answers, and give feedback.

Key Features:
1.Custom Questions:AI generates questions for the interview based on the resume of the candidate and the job position.

2.Real-Time Response Evaluation:AI scores answers in real-time, analyzing relevance and quality.

3.Objective Scoring:Candidates receive an overall score from their answers.
Experts can even score the relevance of their questions.

4.Instant Feedback:The candidates are given immediate feedback on each response.

5.Post-Interview Reports: An in-depth report is produced with scores and feedback for the candidate as well as the hiring team

## Proposed Solution / Architecture Diagram
+---------------------------+
|  User Interface (UI)      |
|  (Boardroom Simulation)   |
+------------+--------------+
             |
             v
+---------------------------+
|  AI Question Generator    |
|  (NLP & ML-based)         |
+------------+--------------+
             |
             v
+---------------------------+
|  Response Evaluation      |
|  (AI-driven Scoring)      |
+------------+--------------+
             |
             v
+---------------------------+
|  Expert Dashboard         |
|  (Real-time Scores)       |
+------------+--------------+
             |
             v
+---------------------------+
|  Final Scoring &          |
|  Suitability Assessment   |
+---------------------------+

## Use Cases
[Candidate]                    [Expert Panel]
         |                                |
   ------------------                -------------------
  | Apply for Interview |          | View Candidate Scores |
  | Attend Interview   |          | Finalize Selection    |
   ------------------                -------------------
         |                                |
         |                                |
     -------------------------------
    |    AI System (Processes)        |
    |  - Generate Questions           |
    |  - Evaluate Responses           |
     -------------------------------

## Technology Stack
React.js, Tailwind CSS
Python or Node.js
PostgreSQL, MongoDB
TensorFlow, OpenAI GPT, BERT 
AWS S3, Google Cloud, Docker 
OAuth 2.0, JWT, SSL/TLS Encryption

## Dependencies

Frontend-3 weeks
Backend-4 weeks
AI & NLP-5 weeks
Database-2 weeks
Cloud & Deployment-2 weeks
security-1 week
budget-Rs:1Lakh
