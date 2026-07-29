# ai-mock-interview-bot
AI-powered mock interview platform that analyzes resumes, generates personalized interview questions, evaluates answers, provides feedback, and scores resumes with ATS-style analysis.
AI Mock Interview Bot is a web-based application designed to help job seekers practice interviews using their own resume as the foundation for personalized interview preparation.

The application allows users to upload their resume in formats such as PDF, DOCX, DOC, or TXT. The system parses the resume to extract important candidate information, including skills, experience, education, and projects. Based on the extracted information and the selected job role, the application generates personalized interview questions covering areas such as introduction, experience, technical knowledge, projects, education, behavioral skills, and closing questions.

Users can answer the generated questions one by one and receive detailed feedback and performance scores. The results include an overall interview score, category-wise performance breakdown, comments, and suggestions for improvement, helping candidates identify their strengths and areas that need further practice.

The project also includes an ATS-style resume scoring feature that analyzes the parsed resume and provides a resume score. The backend is built using Python and Flask, with resume parsing supported by libraries such as PyPDF2 and python-docx.

 Key Highlights
 
 Upload and analyze resumes in multiple formats
 Extract candidate skills, experience, education, and projects
 Generate personalized interview questions based on resume content
 Support job-role-specific interview preparation
 Practice technical and behavioral interview questions
 Evaluate answers and provide performance scores
 Get personalized feedback and improvement suggestions
 View category-wise interview performance
 Analyze resumes with an ATS-style scoring feature
 Simple web interface built with Flask and vanilla JavaScript
 
 Technology Stack
 Backend: Python, Flask
 Frontend: HTML, CSS, JavaScript
 Resume Processing: PyPDF2, python-docx
 Interview Engine: Template-based question generation
 Feedback System: Rule-based answer evaluation
 Session Management: Flask Sessions
