# Academic Impacts of AI: An Exploratory Data Analysis

This project aims to look at the impacts of AI on student academic performance. The dataset for this project was found on Kaggle <https://www.kaggle.com/datasets/bca5b9b9ebe556aade6ba0035cec6c627a2f8adaac329dd5544833e8633573c5>

## Business Problem
Creating informed educational legislation requires a clear understanding of how emerging technologies influence student outcomes.

Looking at a representative population of 8,000 students over the course of a single school year, how does the use of AI—and the manner of that use—specifically affect Final Scores and Improvement Rates?

## About This Data
The data is categorized into four key areas:

AI Interaction Metrics: Detailed tracking of AI usage, including specific tools (ChatGPT, Gemini, Copilot), daily usage time (minutes), purpose of usage (e.g., Doubt Solving, Exam Prep), and a unique AI Dependency Score.

Academic Performance: Core metrics such as Final Score, Last Exam Score, Assignment Scores, and Concept Understanding Score.

Study Habits & Lifestyle: Insight into student life outside the classroom, including Sleep Hours, Social Media Consumption, Study Consistency, and Attendance.

Demographics: Standard identifiers like Age, Gender, and Grade Level (High School to University).

## Key Columns
AI_Dependency_Score: A derived metric indicating how heavily a student relies on AI for coursework.

AI_Ethics_Score: A measure of the student's adherence to academic integrity while using AI.

Concept_Understanding_Score: Assessment of the student's grasp of core subjects, independent of AI aid.

Performance_Category: Classification of the student (Low, Medium, High) based on overall scores.

## Findings
In the dataset, there were no true non-AI users, despite what the students might report, and thus students were grouped into three groups (minimal, moderate, and heavy) depending on their level of use. This allowed us to create a pseudo-control group (minimal users) to compare the other students against.

<img width="640" height="480" alt="Distribution of Users" src="https://github.com/user-attachments/assets/8b61269c-f642-4a9b-85ff-3b92b20b04e8" />
<img width="640" height="480" alt="Distribution of Users by Usage Intensity" src="https://github.com/user-attachments/assets/34e60c41-04bf-420e-b3df-8f71b6865740" />

### Key Finding: AI use can affect a student's academic outcomes.

Moderate use, focusing on homework, doubt solving, and exam prep, appears to be the best strategy for utilizing AI to help improve Academic gains.
<img width="1200" height="600" alt="Improvement Rate by Usage Purpose" src="https://github.com/user-attachments/assets/e0adf709-55e6-444b-9449-edb6ce9f3513" />


Heavy use of AI, specifically as it relates to over reliance of AI generated content, showed a sharp decline in not only final scores, but also improvement rates.

<img width="1589" height="789" alt="scatter_trend_outlined" src="https://github.com/user-attachments/assets/6ed796df-12d5-42e0-b07e-684757ac99f0" />
<img width="1000" height="600" alt="Improvement_Rate_Line_UserClass" src="https://github.com/user-attachments/assets/a7d6efaf-bcea-451f-b9b5-a940587ed220" />

Given the ubiquity of AI among students, AI regulations and policies should focus less on out right bans and focus more on regulating the ways in which AI can be used for academic work.
As the data shows, there are strategies of AI use that are conducive to positive academic growth, just as there are strategies which hinder academic growth.
