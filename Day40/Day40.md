# Build Your Own AI Assistant  
>*From Idea to Production-Ready AI Assistant*  
>*AI Product Design*


Today you'll learn how professional AI products are designed by building an assistant from scratch—including user interviews, system prompt engineering, UI design, documentation, and live Claude integration.

**1.Assistant Design:** Design AI assistants around specific users and problems.  
**2.System Prompt Engineering:** Create production-quality prompts that define the assistant's behavior.  
**3.AI Product Thinking:** Understand how successful AI products combine UX with prompt engineering.  
**4.Production Interfaces:** Build premium interfaces tailored to each assistant instead of generic chat windows. 

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
Paste the AI Assistant Builder prompt.
7
Answer Claude's interview questions (MCQ quiz form, do not type free-form answers).
8
Generate the complete HTML application.
9
Prefer publishing the Claude artifact from the dropdown so you can run the assistant inside Claude.ai / the Claude apps no Anthropic API key is required there; the fetch call to api.anthropic.com is handled automatically.
10
If you download the HTML and open it in a browser or host it on your own website, you will need a real Anthropic API key for the live Claude API calls to work.
11
Test your assistant.
12
Review the generated system prompt.
13
Explore the documentation panel.
14
Take screenshots.
15
Create a Day40 folder in your GitHub repository.
16
Create a day40.md file.
17
Upload screenshots, generated HTML file, system prompt, and key learnings.
18
Commit and push the changes.
19
Submit the GitHub commit URL.  

**Input Prompt**:  
AI Assistant Builder

You are an expert product manager, conversation designer, prompt engineer, UX designer, and frontend developer.

Before generating anything, interview the user ONE QUESTION AT A TIME in the quiz form (MCQ, do not make user do the work of typing).

1. What kind of assistant do you want to build? (Ask their domain and then niche, then give 4 suitable options.)
2. Who is this assistant for, and what's the single most important outcome a user should get from one session with it?
3. What inputs will people give it? (free text, pasted document, form fields, uploaded file, multi-turn conversation)
4. What should the output look like? (a score/verdict, a structured report, a conversational chat, a generated document, recommendations with reasoning)
5. Any tone or personality preference? (professional, friendly, blunt/expert, playful)

Then design and build:

1. The assistant's "brain" — write a production-quality system prompt for the underlying Claude calls: role, scope, constraints, output format, edge-case handling (irrelevant input, missing info, abuse).

2. The interface — a single self-contained HTML file (HTML/CSS/JS only, no external libraries) that:
- Has a premium, purpose-built UI matching the assistant's domain (not a generic chatbot box) — e.g., an ATS checker shows a score dial and highlighted resume text; a recipe finder shows ingredient tags and recipe cards.
- Calls the Claude API live via fetch to https://api.anthropic.com/v1/messages (no API key needed, it's handled) using the system prompt from step 1.
- Handles loading states, errors, and empty states gracefully.
- Is fully responsive with smooth animations and polished micro-interactions.

3. Documentation panel — a collapsible "How this was built" section explaining the system prompt design, why the UI choices fit the use case, and how someone could extend it (add tools, memory, multi-step flows).

Generate the complete file only after all interview answers are collected.

**Learning Outcome**:  
Design purpose-built AI assistants  
Learn production-quality system prompt engineering  
Build AI-powered HTML applications  
Understand AI product architecture  
Create polished user experiences for AI products  
Learn about claude artifacts.  
