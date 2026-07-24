# Build Defend Your Experience  
>*Create an AI-Powered Adaptive Interview Defense Simulator*  
>*AI Career Intelligence*


Today you'll build an intelligent interview preparation platform that uses Claude to extract claims from resumes, portfolios, research, and professional experiences, then continuously challenges users with adaptive interview questions to improve confidence and storytelling.  

**1.Adaptive Interviews:** Generate personalized interview questions based on uploaded experiences.  
**2.Experience Validation:** Challenge every meaningful claim with intelligent follow-up questions.  
**3.Defense Report:** Measure confidence, identify weak areas, and provide actionable improvements.  
**4.Premium UX:** Build a production-grade interview simulator with responsive design and rich interactions.  

**Tasks**:  
1
Read the provided resources.
2
Watch the solution video.
3
Open Claude.
4
Set Claude effort level to Low.
5
Start a new conversation.
6
Paste the Defend Your Experience prompt.
7
Answer Claude's interview questions.
8
Generate the complete HTML application.
9
Save the generated HTML file.
10
Open it locally in your browser.
11
Upload your resume or portfolio.
12
Practice defending your experience.
13
Review the AI-generated Defense Report.
14
Take screenshots.
15
Create a Day50 folder in your GitHub repository.
16
Create a day50.md file.
17
Upload screenshots, generated HTML file, Defense Report, and key learnings.
18
Commit and push the changes.
19
Submit the GitHub commit URL.  

**Input Prompt**:  
# Defend Your Experience

You are an expert interviewer, recruiter, hiring manager, behavioral psychologist, communication coach, UX designer, and senior frontend developer.

Interview the user first, asking one question at a time and using MCQs whenever possible. Understand what they want to defend, why they are preparing, and the type of audience they expect to face. They may upload a resume, LinkedIn profile, portfolio, bio, project, research, performance review, startup story, freelance work, or any document describing their experience.

Before building the application, determine the user's preferred visual style. If previous conversation memory already indicates their design preferences, use those automatically. Otherwise, ask using an MCQ. Adapt the entire interface, typography, layout, animations, and interactions to that style instead of using a default design.

Generate a premium, fully interactive Defend Your Experience application as a single self-contained HTML file using only HTML, CSS, and JavaScript.

The application should use the Anthropic Messages API directly from the HTML application. Assume it runs inside Anthropic's HTML artifact environment where authentication is handled automatically. Never ask for an API key or build a backend.

Instead of reviewing the uploaded document, extract every meaningful claim and treat it as something that must be defended. Become an intelligent skeptic that continuously challenges the user with personalized follow-up questions generated specifically from their own experience. Every answer should influence the next question, allowing the conversation to naturally become deeper, more specific, and more realistic over time.

The application should feel like an adaptive interview rather than a fixed questionnaire. It should identify weak claims, missing evidence, vague statements, and opportunities to tell stronger stories while helping the user build confidence in defending their own experience. Every challenge and every recommendation should be unique to the uploaded content rather than based on generic interview templates.

Provide meaningful visualizations, progress tracking, confidence indicators, and a final Defense Report that clearly shows which experiences are well defended, which need improvement, and how the user can strengthen them before facing a real interviewer.

Make the purpose immediately obvious to first-time users with clear explanations, intuitive navigation, and helpful empty states. Support drag-and-drop uploads, local storage, session history, exports, responsive design, and graceful fallback handling for temporary API errors such as rate limits.

The objective is not to improve a resume. The objective is to help users confidently defend every claim they make about themselves.

Return only the complete HTML file.  

**Learning Outcome**:  
Build adaptive AI interview simulators   
Generate personalized follow-up interview questions   
Create intelligent defense reports using Claude   
Design premium interview preparation dashboards  
Develop production-grade HTML applications powered by AI
