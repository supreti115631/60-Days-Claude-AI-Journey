# Build Personal AI Playbook  
>*Turn Your Own AI Habits Into Reusable Workflow Systems*  
>*Personal AI Systems*


Today you'll learn how to turn your own recurring AI use cases into a personalized system of reusable prompt building blocks, rather than a static library of one-off prompts — and how to make that system self-explanatory to anyone who opens it.

**1.Modular Prompt Design:** Break prompts into reusable blocks — role, objective, context, constraints, and more — that recombine into thousands of variations.  
**2.Autonomous Loop Prompts:** Convert any one-shot prompt into a self-evaluating, self-improving loop with real stop conditions and safety rules.  
**3.Personalization From Interview:** Use an interview-driven build process so the final system matches your actual role, tools, and bottlenecks.  
**4.Self-Explanatory UX:** Design interfaces that make their own purpose obvious at a glance, not just after reading documentation.  

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
Paste the Personal AI Playbook prompt.
7
Answer Claude's interview questions about your role, use cases, and bottlenecks.
8
Generate the complete HTML application.
9
Save the generated HTML file.
10
Open it locally in your browser.
11
Explore your personalized workflow library.
12
Assemble a prompt block-by-block in the Prompt Builder.
13
Convert a prompt into an autonomous loop in the Loop Builder.
14
Save, favorite, and search your own workflows.
15
Export your workflow library as a backup file.
16
Take screenshots.
17
Create a Day49 folder in your GitHub repository.
18
Create a day49.md file.
19
Upload screenshots, generated HTML file, exported workflow JSON, and key learnings.
20
Commit and push the changes.
21
Submit the GitHub commit URL.  

**Input Prompt**:  
Personal AI Playbook

You are an expert AI workflow designer, prompt engineer, productivity consultant, UX designer, and senior frontend developer.

Interview first, one question at a time using MCQs whenever possible (free text only when absolutely necessary). Your goal is to understand how the user actually uses AI.

Discover things like:

* Profession or role
* Primary AI use cases
* Daily repetitive tasks
* Biggest productivity bottlenecks
* Preferred AI models
* Experience level
* Desired outcomes

Only begin building after you have enough context.

Generate a premium, fully interactive Personal AI Playbook as a single self-contained HTML file using only HTML, CSS, and JavaScript (no external libraries).

The playbook should be completely personalized based on the interview. Instead of generic prompts, create reusable AI workflow systems that match the user's needs. Each workflow should include editable templates, customizable variables, practical examples, best practices, and one-click copy.

The application should intelligently organize workflows into relevant categories instead of showing unnecessary ones.

Include a Prompt Builder that lets users assemble prompts from reusable building blocks such as role, objective, context, constraints, reasoning strategy, output format, tone, examples, and quality checks while showing a live preview.

Include a Loop Builder that converts any normal prompt into an autonomous looping prompt by allowing users to define goals, evaluation criteria, improvement strategy, stop conditions, and safety rules.

Rather than storing hundreds of prompts, generate modular building blocks that can be combined into thousands of prompt variations tailored to the user's workflow. Give dropdown options wherever needed, to avoid workload on the user.

Allow users to create, edit, duplicate, favorite, search, filter, and save their own workflows using local storage.

## Make the purpose unmistakable to a first-time viewer
Someone opening this file cold — with no context, possibly just a screenshot — should understand what it is within seconds. To achieve that:
- Include a persistent, plain-language explainer visible on the main view by default (not just a one-time onboarding modal), stating what the tool does and what its main sections are for. It can be dismissible, but only via user action.
- Add a permanent, always-visible "What is this?" affordance (e.g. a small help button) that re-opens the full explanation on demand, at any time — not just on first run.
- Use plain, self-descriptive navigation labels for every section (e.g. "Dashboard," not invented jargon like "Deck" or "Hub"). If you introduce a novel term for a feature, define it in the UI the first time it appears.
- In both the Prompt Builder and Loop Builder, every building block must carry a short, visible explanation of what it does and why it matters — shown both (a) in the block picker before it's added, and (b) inside the assembled block once it's in use. Someone should never have to guess what "Reasoning strategy" or "Stop conditions" means or why it's there.
- Section subtitles and empty states should describe purpose in plain language, not just decorative flavor text (e.g. "Your saved AI prompt workflows, at a glance" rather than "Your AI operating system, at a glance").

The interface should feel like a polished commercial SaaS product with beautiful typography, smooth animations, responsive design, dark mode, keyboard shortcuts, onboarding, import/export, and thoughtful UX throughout.

Focus on teaching users how to build reusable AI systems rather than simply giving them prompts.  

**Learning Outcomes**:  
Design personalized AI workflow systems instead of one-off prompts  
Build reusable, modular prompt building blocks  
Understand how to convert any prompt into a self-improving autonomous loop  
Design self-explanatory, first-glance-clear SaaS interfaces  
Create production-quality, locally-persisted HTML applications using Claude  
