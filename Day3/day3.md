# Role-Based Prompt Engineering

# What is Role Based Prompting?

Role based prompting is a prompt engineering technique where the AI is instructed to take on a specific role or persona, shaping its tone, style and content to produce more relevant, specialized and context aware responses.

The structure is simple:

>*“Act as a [role] who [goal].”*

You’re casting an actor. The same model performs differently depending on the role — because you’ve narrowed focus, tone, and purpose to match yours.

Why it Works?

- Sharper Context- The Model selectes example and method that fits the role.
- Consistent Tone- Responses sound human not mechanical
- Better Results- You get Responses, structure, Advice, creativity alinged with your goal.

**Role Prompting experiments**:

1.No role (baseline)

**Input Prompt**: We have 3 months and $50,000 budget. Should we build an AI chatbot feature for our SaaS product? Povide Mximum 4 recommendations

Output: 
01 — Build it
Use an API-first approach, don't build from scratch
Skip training your own model. Integrate OpenAI, Anthropic, or Google via API. This cuts 80% of the engineering complexity, keeps costs well inside $50k, and gets you to market in weeks — not months. Save the remaining budget for prompt tuning and UX polish.
02 — Scope carefully
Solve one specific user problem, not "general chat"
General-purpose chatbots fail because they don't do anything well. Define a narrow job-to-be-done: onboarding help, support triage, in-app search, or report generation. A focused chatbot is faster to build, easier to evaluate, and far more likely to drive retention.
03 — Budget the full picture
Ongoing API costs will exceed build costs by month 6
$50k sounds comfortable, but factor in: API inference costs scale with usage, moderation and safety tooling, eval infrastructure, and human review of edge cases. A rough split: 25% build, 30% QA + safety, 45% reserved for 6-month operating runway. Otherwise you'll be cash-strapped at launch.
04 — De-risk first
Ship a no-AI version in month 1, add AI in month 2
The highest risk is building AI nobody uses. Start with a rule-based or search-powered version to validate the UX and adoption. Then layer in the LLM only where it outperforms the simpler solution. This gives you a working fallback if the AI underperforms, and real usage data to tune against.

2.Role: Startup Founder

**Input Prompt**: Act as a startup founder and answer the following question.
We have 3 months and $50,000 budget. Should we build an AI chatbot feature for our SaaS product? Povide Mximum 4 recommendations

Output: 
1. Validate before you build
Before writing a single line of code, talk to 10-15 existing customers this week. If fewer than 60% say they'd actively use an AI chatbot, don't build it — you're solving a problem you assumed exists. Customer conversations cost $0 and save you everything.
2. Buy, don't build — at least for now
With only $50K and 3 months, building a robust chatbot from scratch will burn your runway fast. Use an API-first approach — OpenAI, Anthropic, or Gemini. A lean integration can be shipped in 3–4 weeks, leaving budget for iteration based on real user feedback.
3. Protect your core product
AI features have a seductive pull — they feel innovative, they demo beautifully. But if your core SaaS has unresolved bugs, churn issues, or weak onboarding, an AI chatbot won't fix retention. It'll just distract your team. Ring-fence at most one developer on this; everyone else stays on the roadmap.
4. Define your success metric before day one
Decide now what "success" looks like — is it reduced support tickets? Higher feature adoption? Better trial-to-paid conversion? Without a pre-committed metric, you'll rationalize a failed feature as "still learning." Set a 60-day checkpoint: if the needle hasn't moved, kill it or pivot fast.

Bottom line: The chatbot could be worth it — but only if customers are pulling you toward it, not if you're pushing it onto them. Validate fast, build lean, and keep your exit criteria honest.

2.Role: Senior Software Developer

**Input Prompt**: Act as a Senior Software Developer and answer the following question.
We have 3 months and $50,000 budget. Should we build an AI chatbot feature for our SaaS product? Povide Mximum 4 recommendations

Output: 
Budget
$50,000
Timeline
3 months
Decision
Integrate, don't build
1.Use an API, don't build your own model
$50K and 3 months is nowhere near enough to train or fine-tune a capable LLM. Use OpenAI, Anthropic, or Gemini APIs instead — you get production-grade intelligence from day one, leaving most of your budget for product work.
OpenAI / Anthropic / Gemini
~$500–2K/mo API cost
2.Scope ruthlessly — one job, done well
Don't build a general assistant. Pick one high-value use case your users already struggle with — answering product questions, drafting outputs, summarising data. A narrow, polished feature ships in 3 months; a broad one doesn't.
Avoid scope creep
1 focused use case
3.Reserve 30–40% of budget for trust & safety
Hallucinations, prompt injection, data leakage, and user abuse are real risks in a SaaS context. Budget $15–20K for guardrails, output validation, rate limiting, audit logging, and a review period before GA release.
Guardrails required
~$15–20K allocation
4.Measure ROI before committing to scale
Launch to a small beta cohort in month 2. Track retention uplift, support ticket deflection, and feature engagement before scaling infra spend. Avoid locking in long-term API contracts or heavy infra until you have signal.
Beta → GA gating
Measure before scaling

**Claude Usage Counter**:

Helps you track your claude.ai usage caps based on tokens sent.

This extension helps you monitor how much of your Claude usage quota remains. It calculates token consumption from various sources including uploaded files, project knowledge, chat history, and AI responses. It will also send a notification when your usage limits have been replenished (if the site notified you that you were about to run out).

Most elements in the chat UI (Namely the length, cost, estimate, caching status) have a tooltip explaining them further! Be sure to check them out.

The extension tracks token usage from:
- Files - Documents uploaded to chats or synced via Google Drive, Github, etc
- Projects - Knowledge files and custom instructions
- Personal preferences - Your configured settings
- Message history - Full conversation context
- System prompts - Enabled tools (analysis, artifacts) on a per-chat basis
- MOST MCPs/Integrations - There are some limitations in cases where a "Knowledge" object is returned that I can't access, such as with web search

Limitations:
- Web search results - The full results are not exposed in the conversation history, so I can't track them properly (See above, Knowledge objects)
- Research - Most of it happens on the backend, so I can't track it at all

Token calculation is handled either through Anthropic's API (if you provide your key) or via gpt-tokenizer.


